# Kalman Filter Power Systems Lab V1

Reduced 10-machine swing-equation benchmark, RK4, 50 Hz, synthetic angle/speed observations, seeded Gaussian noise and packet loss. KF, EKF, UKF and bootstrap PF share measurements. The island case uses a disconnected topology from initialization. Frequency RMSE covers all machines and times. Educational model, not validated against an industrial benchmark. No Koopman, modal identification, observability rank, converter/governor dynamics, or adaptive covariance yet. No full AC network or terminal phasor model.
