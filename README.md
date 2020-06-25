# Forecasting cash withdrawals at ATMs and optimizing cash management
The essence of the project is that a system is being developed that consists of two parts.

First, it predicts cash withdrawals at ATMs for 14 days ahead using method of Triple exponential smoothing (Holt-Winters), Recurrent Neural Network with Long Short-Term Memory (RNN LSTM), and Singular Spectral Analysis (SSA). Errors of the I (first) and II (second) type are calculated, as well as the main metrics (Accuracy, Precision, Recall, F1 score) and the conclusion is made which forecast should be used.

The second part is a system for building an optimal schedule for loading cash into ATM's.
The second part is a system for building an optimal replenishment schedule. The obtained forecast values from the first part were used in the system of Discrete Optimal Control. Using the principle of dynamic programming, an optimal schedule was obtained, including the amount of cash and the number of days when it is necessary to conduct collection.
