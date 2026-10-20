# GPS/INS Integration & Inertial Sensing Reference

A lookup-ready index of reference notes on GPS/INS integration and inertial navigation sensing, ordered by subject. This page only collects and points; the notes themselves live at the archive: [appliedanalyticsinc.com](https://appliedanalyticsinc.com).

This document assembles public reference material on the subject into one browsable document. Each entry keeps its original title. It is meant as a verification entry point, not a replacement for the source.

17 entries. Titles are kept exactly as published at the archive, so a search on either page returns the same results.

## Contents

1. GPS SPS Performance Standard 2020
2. Space shuttle navigation analysis. Volume 2: Baseline system navigation
3. GPS/Optical/Inertial Integration for 3D Navigation Using Multi-Copter Platforms
4. Attitude Sensor and Gyro Calibration for Messenger
5. Absolute Navigation Performance of the Orion Exploration Fight Test 1
6. Airdata calibration of a high-performance aircraft for measuring atmospheric wind profiles
7. A Short Tutorial on Inertial Navigation System and Global Positioning System Integration
8. Application of GPS to Enable Launch Vehicle Upper Stage Heliocentric Disposal
9. Testing of the high accuracy inertial navigation system in the Shuttle Avionics Integration Lab
10. Integrated INS/GPS Navigation from a Popular Perspective
11. Orion Exploration Flight Test-l (EFT -1) Absolute Navigation Design
12. NASA modular GPS navigation software
13. NASA Space Shuttle navigation GPS IMU
14. Optimization of the effective GPS data rate
15. Overview of NASA's Ocean Color Instrument Solar Calibration Architecture, Pre-Launch Tests and Preliminary On-Orbit Resu
16. An inertial velocity reference for the NASA airborne Doppler lidar
17. Lightweight, Miniature Inertial Measurement System

## 1. GPS SPS Performance Standard 2020

Primary source: <https://www.gps.gov/performance-standards-specifications>

values are NWT 1.16, 95.0% of the HDOP values are NWT 1.25, 98.0% of the HDOP values are NWT 1.37, and 99.9% of the HDOP values are NWT 1.80. Figure B.3 -2 shows the corresponding VDOP distribution, also in the form of two histogram curves. Recognize that there really is only one HDOP distribution shown in Figure B.3-1 and one VDOP distribution shown in Figure B.3 -2. The direct distribution curve and the cumulative distribution curve in each figure are just two different ways of looking at the same DOP distribution. The HDOP distribution in Figure B.3-1 is only one out of a great many possible HDOP distributions for the baseline 24-slot constellation (equivalently for the VDOP distribution in Figure B.3-2). That is why it is said to be an HDOP distribution, not the HDOP distribution. The HDOP distribution in Figure B.3-1 is specific to the particular conditions identified on the figure

## 2. Space shuttle navigation analysis. Volume 2: Baseline system navigation

Primary source: <https://ntrs.nasa.gov/citations/19800022935>

onding error sources; the latter are also shown in Table 2.4-4. The result of this oper- ation is shotcn in Table 2.4-5 which contains the factors by which an error source is amplified to determine its contribution to a calibration error. A similar table was constructed for the accelerometer bias attitude sensitivity errors which, as per Ref. 7, will also be compensated within the IMU software. Table 2.4-6 contains .:he corresponding error amplification factors. In Table 2.6-5 it can be seen that error amplification factors as high as 4.4 and 4.7 occur several times. The highest factor in Table 2.4-6 is 3.4. Information on these amplifica- tion factors was provided to RI to help them specify accuracy requirements for the dynamic compensation of accelerometer attitude sensitivity. The amplification factors shown in Table 2.4-5 and 2.4-6 depend strongly on the particular platform positions

gh Gain Resolver Output Noise Resolver Quantization ['e hi c i e ?lot ion LXITS sec/sec - 3/2 UB f t/sec Et/sec h sac SGt 0 * 00s 0.00s 0,025 0.025 0.005 0.005 See Table 2.34- o.ol ,-t,'1?0 tl)* Low Gain High Gain 15 150* 10 100' 5 50* See Table 2.3-ki See Table 2.34- 200 See Text DATA SOURCE - Ref. 12 Ref. i2 Ref. 12 Ref. 1: Ref. 12 Ref. 12 See Text See Text See lex€ See Test See Text See Text See Text Ref. 1 Ref. 12 Ref. 11 Ref. :? kef. 12 See Text Ref. 1 See Text See Text See Text See Text See Text \l) t 8 seconds after rompletins a cluster repositioning. (2) Standard dw:ation of maximum amplitude. ??heso error terns differ from those given ir. Ref. L: they are discussed in :cy.:. 2-13 TABLE 2.3-4 IMU TRUTH MODEL DATA BASE FOR HEADING SENSITIVE GYRO AND ATTITUDE SENSITIVE ACCELEROMETER ERRORS T-3278 .~ ? STANDARD DEVIATION OF UUIOR COEFFICIEhT ERROR GSRO OR ACCLL. Gf?lBAL j xi I S 16.

oftware. According to RI (Ref. 14) the ms residual errors of these ternis are less than 10 ppm. 2-17 Group 17: Gyro Thermal Transient Drift (Table 2.3-3) - A new magnitude end time constant were recommended by SKD (Ref. 17) for the gyro thermal transient drift error. Because of the smaller time constant (originally 600 see), the effect of this error group will be diminished. Groups 18 and 19: Acceleromter Nonlinearities (Table 2.3-3) - SKD has pointed out (Ref. 17) that the second- order and third-order accelerometer nonlinearities are ten times larger in high gain than in low gain. With this change these error groups will become significant contributors to calibration inaccuracies. Group 24: Gyro Randomness (Table 2.3-3) - The gyro randomness error model used by TASC assumes a random walk (Ref. 10). The growth rate has been adjusted to yield the same error growth over periods of up to t

lity for the low gain asymmetry error. The high gain. asymmetry error equals the low $sin error plus an uncorrclated error of 33 ppm (100 ppm, 30) with no turn-off turn-on inota- bilitg. Note that now the uncorrelrtcd part of the high pain asymmetry error is not calibrated. This shortcoming is deemed less serious than the errors that are introduced when attempt- ing to calibrate the high gain asymmetry errors usin8 high gain accelerometer data (Ref. 14). Turn-off Turn-on Instabilities (Table 2.3-2) - All error terms marked with a "f" were increased in magnitude from those used in Ref. 4. The new values are the long-term sta- bility errors specified in Ref. 8. These changes were recom- mended by SKD (Ref. 15). The values for error Group 10 are discussed in the foreBoing paragraph. 2-16 Croups 16, 20, and 21: Heding Sensitive Drift and Attitude Sensitive Bias and Scale Factor (Table 2.3-4)

hroughout the entire calibration and alignment procedure. 2.4.1 Hanaar Calibration Performance The Hangar cal/align sequences have the following functions: 0 Hangar Coarse Alignment - Estimate the IMU case orientation. Table 2.4-1 displays both the rms level error and the azimuth error of this estimate. Nan ar Cal A - Calibrate a total of 35 These parameters are organized into 10 different groups. Table 2.4-1 displays the rms value of the calibration error of all parameters contained in each group. The corresponding column headings are identified by codes similar to those used in Table 2.3-1 (DF=gyro bias drifts, etc.). melerometer error parameters. 0 Gangar Cal B - Calibrate 4 resolver error parameters and 2 misalignments of the compensated accelerometer-frame with respect to the platform 2 (azimuth rotation) axis. These parameters are organized into two groups. Table 2.4-1 displays the

utions are negligible. :In low gain the error is 20 ppm. in high gain the error is 36.1 pp. 1. Determined from limits of tilt removal mechanization during calibration. 2. Value recommended by Singer-Kearfott. 3. N.S. = Not Specified. AZIMJTH sec - 83.8 - - - - - - 17.4 20.0 + 10 .4 34.8 8.4 5.0 15.4 28.9 - 59.8 13.3 768.2 18002 - 1_1_ - 2-30 TABLE 2.4-2 PREFLIGHT CALIBRATION ERROR liL*DCET b T-3271 1 &ZZIMlTH sec 7 w - 83.8 - - - - - 17.4 20.0 34.8 8.4 5.0 15.4 28.9 - 59.8 13.3 768.2 18002 - RMS CALIBRATION E-S-OL INU PARARETERS DF G/sec - DIT ,S ,O Sc/sec/g I 0.003 - - - - - - - 0.002 - - 0.001 - - 0.022 0.025 - B+ STC N.S. 2-30 w 7. 7 2-31 THE ANALVYIC SCIENCES CORPORATlOM Tables 2.4-2 and 2.4-3 summarize the performance results (both error budgets and overall performance) for these cal/align sequences. Host entries in these tables are analogous to those of Table 2.4-1. In addition, Ta

* sin (2+ cos (29 sin (28 cos (2* sin (2r1, cns (2e uir (20 cos (2R sin (20 cos (251 sin (2@ T- 3273 I CROUPS 6.8 GROUPS 7 $9 C;ROUP 10 17.4 13.4 7.1 7.1 11.5 11.5 3.4 3.4 6.7 6.7 11.5 11.5 6.7 6.7 7.1 7.1 11 .O 11 .u - - - 3 -1 2 - - Because of the overwhelming effect of the accelerometer attitude sensitive errors it was decided (see Ref. 7) to dynam- ically compensate these errors within the LMU software. Given this situation, it is of interest to know how small the residual attitude sensitivity errors (after cornpens-ation) have to be in order that this error source ceases to be a dominant contributor to cal/align errors. To help answer this question, the error budget contributions in Table 2.4-4 were normalized by dividing 2-37 t.hese by the magnitude of the corresponding error sources; the latter are also shown in Table 2.4-4. The result of this oper- ation is shotcn in Table 2.4-5

.9 - 13.3 217.1 16001 - + These error budget contributions are negligible. In low gain the error is 0 ppm, in high gain the error is 30 ppm. Excluding contributions from Error Group 26 which are not significant. * 1. Determined from limits of tilt removal mechanization during calibration 2. Value recommended by Singer-Kearfott. 3. 30 sa for gimbal nonorthgonality. 4. N.S. = Not Specified 421MJ. see - 9 - - - 10.9 - - & 11 .2 - - - - 28.9 23.7 13.3 784.1 18002 - - DF Fc/sec - - - - - - - - - 0.002 - 0.001 0.003 - 0.013 0.015 - 2-24 TABLE 2.4-1 HANGAR CALIBRATION ERROR BUDGET 2- 24 Han ar Cal C - Determine the discrepancies cation of platform le~l misalignments and store the difference of these discrep- ancies between each pair of IMU's. These differences will be computed once again during Gyrocompassing and, when compared against the stored differences, constitute the Gyrocompass Goodness

able 2.4-4. Each row of the table represents an individual error in Group 21, and each column represents an individual accelerometer calibration error in one of Groups 6 to 10. (The high gain results are identical to the low gain results. ) As can be seen in Table 2.4-4, the accelerometer bias and asymmetry calibration. errors are affected to much greater degree than are the scale factor calibration errors. The largest error contributions come from the X accelerometer roll gimbal sensitivity, followed by the 2 accelerometer azimuth gimbal sensitivity. 2-36 ACCEI I\XlS X Y z G I HBAL Roll I I 1 I Pitch I Azimuth f i Rol I i Pitch ! I Azimuth TABLE 2.4-4 DETAILED ERROR BUDGET FOR ERROR GROUP 21 IN HANGAR CAL A TERN* cos (26 sin (2+ cos (29 sin (28 cos (2$ sin (211, cos (2* sin (2+ cos (29 sin (28 cos (2* sin (2r1, cns (2e uir (20 cos (2R sin (20 cos (251 sin (2@ T- 3273 I CROUPS 6.8 GROUPS

Correlated Accel. Nonorthogonality Accel. and Gyro Misalignment Resolver Offset. Gimbal Nonorthogonality - Uncorrelated NONCALIBRATED IMU ERRORS Gyro hisoelasticity Gyro Output Axis Mass Unbalance Gyro Attitude Sensitive Drift Gyro Themal Transient Drift Accel. NonlineariLy - 2nd Order Accel. Nonlinearity - 3rd Order Accel. Attitude Sensitive Bias Accel. Attitude Sensitive Scale Factor Outer Roll Offset and Misalignment Resolver Harmonic 111. RANDOM AND QUANTIZATION ERRORS 24. Gyro Randomness and Quantization I 25. Accel. Randomness and Quantization 27. Vehicle Motion 26. Resolver Randomness and Quantization I RSS OF ERROR CROUPS 2-27 PERFORMANCE SPECIFICATION MAGNITUDE C-e Table 2.3-3 See Table 2.3-3 ZOARSE ALIGNMEN LEVEL sec - + - - - - - - 20.6 7.7 7.7 & - 4.9 3.8 28.9 - 13.3 217.1 16001 - + These error budget contributions are negligible. In low gain the error is 0 ppm, in high gain

## Service pages maintained with this archive

The reference notes above support the production work documented on the shop's own service pages:

* **[IMU Calibration Service — Specification Guide](https://appliedanalyticsinc.com/services/imu-calibration-service.html)** — How IMU and INS calibration works: factory versus field methods, six-position and rate-table tests, temperature modeling, certificate contents, and recalib
* **[INS Alignment Procedure — Specification Guide](https://appliedanalyticsinc.com/services/ins-alignment-procedure.html)** — Guide to INS alignment: coarse versus fine alignment, gyrocompassing time-versus-latitude trade-off, transfer alignment, quality metrics, and field degrada
* **[GNSS](https://appliedanalyticsinc.com/services/gnss-denied-navigation.html)** — Guide to GNSS-denied navigation: inertial coasting error growth, visual/terrain/SoOP aiding, Kalman filter reversion, and realistic position error budgets.
