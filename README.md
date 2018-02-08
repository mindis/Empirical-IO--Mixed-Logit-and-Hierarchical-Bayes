## Static Nested Logit Model and MLE

 1. Click DataSimulator.py and wait for ~15min for it to simulate the data. As an alternative, you can call
	`ds = DataSimulator(I, J, T, pdf, intercept, coefficient, M, SIG)`
	`ds.make_data()`
    to generate the simulated data. Before that, please specify the parameters in the DataSimulator class, e.g.,
    `J = 2, I = 500, T = 20`
    `(a1, a2) = (0.0, 0.0)`
	`Pjt ~ N(1, 0.3^2)`
	`coef ~ N(-1.5, 0.4^2)`
	`M = 10`

 2. Once data (i.e., "Data_m.csv") were generated, click MaximumLikelihood.py to get the estimation results.
