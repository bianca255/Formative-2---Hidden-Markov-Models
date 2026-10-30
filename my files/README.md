# Formative 2: Modeling Human Activity States with a Hidden Markov Model

 A Gaussian-emission HMM implemented from scratch in NumPy (Viterbi decoding and Baum-Welch training with a log-likelihood convergence check) to infer four activities from smartphone accelerometer and gyroscope data: **standing, walking, jumping, still**.

## Repository structure
```
data/                          training clips (38 CSV files, 6 s each)
data_test/                     unseen test clips from separate recording sessions (29 CSV files)
hmm_activity_recognition.ipynb notebook with outputs
report.pdf                     short report (4-5 pages)
```

## Data
- Device: iPhone 11 Pro, Sensor Logger app (uncalibrated accelerometer and gyroscope, about 100 Hz native, resampled to 50 Hz).
- File naming: `<activity>_bianca_<nn>.csv`; columns: `seconds_elapsed, ax, ay, az, gx, gy, gz`.
- Each long recording was trimmed by 3 s at both ends and cut into 6 s clips.
- `data_test/` clips come from separate recording takes that were never used for training.



## Videos
| Activity | Link |
|---|---|
| Standing | ADD LINK |
| Walking | ADD LINK |
| Jumping | ADD LINK |
| Still | ADD LINK |
