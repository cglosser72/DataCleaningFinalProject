#  Codebook for summary dataframe

Fields 1.\ to 3.\ contain the header information (activity_code, activity, and subject number).  The remaining fields are averaged.  

## Times (4-43)

Time data begins with "time" and is broken out by:
1. body acceleration ("BodyAcc")
2. gravity acceleration ("GravityAcc")
3. body acceleration jerk (BodyAccJerk)
4. body gyroscopic direction ("BodyGyro")
Componments are given ("X", "Y", "Z") as are magnitudes ("Mag").  The averages by subject of the provided mean and standard devations are include 

## Frequencies (44-82)
Frequency data broken out as:
1.  body acceleration ("BodyAcc")
2.  body acceleration jerk (BodyAccJerk)
3.  body gyroscopic direction ("BodyGyro")

## Angles (83-85)
These are the averages of various angles between vectors (e.g. "angle_X_gravityMean" is the average angle between aceleration and the mean gravity vector)

##  List of Fields
1.  "activity_code"
2.  "activity"
3.  "subject"
4.  "timeBodyAcc_mean_X"
5.  "timeBodyAcc_mean_Y"
6.  "timeBodyAcc_mean_Z"
7.  "timeBodyAcc_std_X"
8.  "timeBodyAcc_std_Y"
9.  "timeBodyAcc_std_Z"
10. "timeGravityAcc_mean_X"
11. "timeGravityAcc_mean_Y"
12. "timeGravityAcc_mean_Z"
13. "timeGravityAcc_std_X"
14. "timeGravityAcc_std_Y"
15. "timeGravityAcc_std_Z"
16. "timeBodyAccJerk_mean_X"
17. "timeBodyAccJerk_mean_Y"
18. "timeBodyAccJerk_mean_Z"
19. "timeBodyAccJerk_std_X"
20. "timeBodyAccJerk_std_Y"
21. "timeBodyAccJerk_std_Z"
22. "timeBodyGyro_mean_X"
23. "timeBodyGyro_mean_Y"
24. "timeBodyGyro_mean_Z"
25. "timeBodyGyro_std_X"
26. "timeBodyGyro_std_Y"
27. "timeBodyGyro_std_Z"
28. "timeBodyGyroJerk_mean_X"
29. "timeBodyGyroJerk_mean_Y"
30. "timeBodyGyroJerk_mean_Z"
31. "timeBodyGyroJerk_std_X"
32. "timeBodyGyroJerk_std_Y"
33. "timeBodyGyroJerk_std_Z"
34. "timeBodyAccMag_mean"
35. "timeBodyAccMag_std"
36. "timeGravityAccMag_mean"
37. "timeGravityAccMag_std"
38. "timeBodyAccJerkMag_mean"
39. "timeBodyAccJerkMag_std"
40. "timeBodyGyroMag_mean"
41. "timeBodyGyroMag_std"
42. "timeBodyGyroJerkMag_mean"
43. "timeBodyGyroJerkMag_std"
44. "frequencyBodyAcc_mean_X"
45. "frequencyBodyAcc_mean_Y"
46. "frequencyBodyAcc_mean_Z"
47. "frequencyBodyAcc_std_X"
48. "frequencyBodyAcc_std_Y"
49. "frequencyBodyAcc_std_Z"
50. "frequencyBodyAcc_meanFreq_X"
51. "frequencyBodyAcc_meanFreq_Y"
52. "frequencyBodyAcc_meanFreq_Z"
53. "frequencyBodyAccJerk_mean_X"
54. "frequencyBodyAccJerk_mean_Y"
55. "frequencyBodyAccJerk_mean_Z"
56. "frequencyBodyAccJerk_std_X"
57. "frequencyBodyAccJerk_std_Y"
58. "frequencyBodyAccJerk_std_Z"
59. "frequencyBodyAccJerk_meanFreq_X"
60. "frequencyBodyAccJerk_meanFreq_Y"
61. "frequencyBodyAccJerk_meanFreq_Z"
62. "frequencyBodyGyro_mean_X"
63. "frequencyBodyGyro_mean_Y"
64. "frequencyBodyGyro_mean_Z"
65. "frequencyBodyGyro_std_X"
66. "frequencyBodyGyro_std_Y"
67. "frequencyBodyGyro_std_Z"
68. "frequencyBodyGyro_meanFreq_X"
69. "frequencyBodyGyro_meanFreq_Y"
70. "frequencyBodyGyro_meanFreq_Z"
71. "frequencyBodyAccMag_mean"
72. "frequencyBodyAccMag_std"
73. "frequencyBodyAccMag_meanFreq"
74. "frequencyBodyBodyAccJerkMag_mean"
75. "frequencyBodyBodyAccJerkMag_std"
76. "frequencyBodyBodyAccJerkMag_meanFreq"
77. "frequencyBodyBodyGyroMag_mean"
78. "frequencyBodyBodyGyroMag_std"
79. "frequencyBodyBodyGyroMag_meanFreq"
80. "frequencyBodyBodyGyroJerkMag_mean"
81. "frequencyBodyBodyGyroJerkMag_std"
82. "frequencyBodyBodyGyroJerkMag_meanFreq"
83. "angle_timeBodyAccMean_gravity"
84. "angle_timeBodyAccJerkMean_gravityMean"
85. "angle_timeBodyGyroMean_gravityMean"
86. "angle_timeBodyGyroJerkMean_gravityMean"
87. "angle_X_gravityMean"
88. "angle_Y_gravityMean"
89. "angle_Z_gravityMean"
