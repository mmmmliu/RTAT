# RTAT dataset description

The data is collected based on VR Reference Frame.
X axis is the right direction, Y axis is the up direction, Z axis is the front direction. 

Cloumns:

1: Time

2-4: Raw accelerometer readings (x, y, z) reported by smartwatch  

5-7: Raw gyroscope readings (x, y, z) reported by smartwatch

8-10: Normalized magnetometer readings (x, y, z) reported by smartwatch

11-13: Groundtruth location (x, y, z) of smartwatch derived from the VR system

14-16: Groundtruth orientation vector (x, y, z) of smartwatch derived from the VR system

17-20: Groundtruth orientation quaternion (w, x, y, z) of smartwatch derived from the VR system

21-23: Groundtruth velocity from the VR system

24-26: Groundtruth angular velocity from the VR system
