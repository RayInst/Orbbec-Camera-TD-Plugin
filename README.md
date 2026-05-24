🌟 New Features

Plug-and-Play LiDAR Support: Full support for Orbbec LiDAR devices is now available! Simply connect your LiDAR, and the plugin will automatically detect it, adapt the user interface, and start streaming.
Native 3D Instancing Ready: LiDAR point cloud data is now natively streamed into TouchDesigner channels (X, Y, Z, and Reflectivity/Intensity), making it instantly ready for 3D geometry instancing and rendering.
Dedicated LiDAR Controls: Added new UI parameters to easily adjust LiDAR scanning profiles (frequencies) and hardware noise reduction (Tail Filter).
LiDAR Motion Tracking: Accelerometer and Gyroscope (IMU) data from LiDAR devices is now fully supported.
🛠 Stability & UX Improvements

Smart Hardware Detection: The plugin is now smarter about your hardware capabilities. Features unsupported by your specific camera model (such as the Confidence Sensor) are automatically disabled in the UI to prevent accidental freezes and pipeline crashes.
Better Error Feedback: Network timeouts and connection issues are now clearly communicated directly within the TouchDesigner interface, eliminating silent connection failures.
Cleaner UI State: The device information panel now properly resets itself when a camera is disconnected.
✨ Image Quality Enhancements

Edge Noise Removal: The Edge Noise Removal filter is now fully operational. Enabling this will significantly reduce jagged edges and flying pixels in your depth point clouds.

SDK vesion 2.1.1

Support Models:

Supported Devices and Recommended Firmware Version
Products List	Recommended FW Version	Note
Gemini 305g	1.0.70	
Gemini 305	1.0.70	
Astra Mini Pro	2.0.03	Version of v2.x.x (major version 2) indicates firmware using the UVC protocol, which is only supported by Orbbec SDK v2.
Astra Mini S Pro	2.0.03	Version of v2.x.x (major version 2) indicates firmware using the UVC protocol, which is only supported by Orbbec SDK v2.
Gemini 435Le	1.3.6	
Gemini 330 series	1.6.00	Gemini 330/330L/335/335L/336/336L/335Lg/335Le
Gemini 215	1.0.9	
Gemini 210	1.0.9	
Gemini 2	1.4.98	
Gemini 2 L	1.5.2	
Femto Bolt	1.1.3	
Femto Mega	1.3.1	
Femto Mega I	2.0.4	
Astra 2	2.8.20	
Gemini 345	1.9.03	
Gemini 345Lg	1.9.03	
Pulsar SL450	2.2.4.5	
Pulsar ME450	1.0.0.6	

<img width="1183" height="823" alt="f2fce568-0b7d-4dc0-b510-1d2ceea860c9" src="https://github.com/user-attachments/assets/670234ea-9850-4761-a22a-9279bea22cf2" />



<img width="1909" height="849" alt="orbbec plugin" src="https://github.com/user-attachments/assets/3d9b2c03-26a4-405c-9219-9ed45d566c22" />

