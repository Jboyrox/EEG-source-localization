# EEG-source-localization
EEG or Electroencephalography is a powerful tool for neuroscientists in understanding brain activity. In EEG, a patient wears a headset with electrodes that measures voltages at a number of points on the scalp. These voltages arise from ionic currents within the brain. A common inverse problem is to estimate the which parts of the brain caused the measured response. Source localization is useful in understanding which parts of the brain are involved in certain tasks. A key challenge in this inverse problem is that the number of unknowns (possible locations in the brain) is much larger than the number of measurements. I use LASSO regression on a real EEG dataset to overcome this problem and determine the brain region that is active under an auditory stimulus.
In addition to this I also:
1)Represent responses of multi-channel time-series data, such as EEG, using linear models
2)Perform LASSO and Ridge regression
3)Select the regularization level via cross-validation
4)Visually compare the sparsity between the solutions

The results of this experiment are present in the notebook eeg.ipynb
