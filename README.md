# The system of predicting cash withdrawals at ATMs and optimizing cash management strategies
The essence of the project is to develop a system for managing cash in ATMs, the main purpose of which is to avoid running out of cash at ATMs and earn the maximum amount of money by investing the released funds from frozen cash at ATMs in short-term highly liquid and risk-free financial instruments (for example, RuOnIa).

The developed system consists of two parts.

First, it predicts cash withdrawals at ATMs for 14 days ahead using method of Triple exponential smoothing (Holt-Winters), Recurrent Neural Network with Long Short-Term Memory (RNN LSTM), and Singular Spectral Analysis (SSA). Errors of the I (first) and II (second) type are calculated, as well as the main metrics (Accuracy, Precision, Recall, F1 score) and the conclusion is made which forecast should be used.

The second part is a system for building an optimal schedule for loading cash into ATM's. The obtained forecast values from the first part were used in the system of Discrete Optimal Control. Using the principle of dynamic programming, an optimal schedule was obtained, including the amount of cash and the number of days when it is necessary to conduct collection.

This system allows you to manage the collection process more reliably and efficiently, earning on average 30% more money from investing in short-term financial instruments and completely eliminating the possibility of running out of funds in the terminal, compared to the classic Baumol-Tobin cash management model.

From an economic point of view, when using the considered model of managing money reserves in a network of information payment terminals for a single terminal, considered an ATM in India, the revenue per year will be about 200 thousand rupees, while for a city network consisting, on average, of 50 terminals, this amount will be 11.5 million rupees.
