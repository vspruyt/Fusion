# Fusion for Arduino

A PlatformIO compatible library package of Madgwick's latest AHRS sensor fusion approach (https://github.com/xioTechnologies/Fusion). Tested on a Teensy 4.0 board.

Note: This is not based on the older gradient based Madgwick filter that lots of people still use! Instead, it's based on the latest version of his attitude estimator that Madgwick himself recommends: https://github.com/xioTechnologies/Fusion

In Sebastian Madgwick's PhD thesis, titled "AHRS algorithms and calibration solutions to facilitate new applications using low-cost MEMS", he first discusses the gradient based filter that most people know about. At the end of his thesis, he then discusses his 'revised algorithm', which offers several improvements upon the original algorithm, is much more efficient and robust against bad sensor readings from typical low-cost sensors, and is similar to the complementary filter of Mahony.