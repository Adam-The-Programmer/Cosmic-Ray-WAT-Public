# Cosmic Ray WAT Idea
This is an official Military University of Technology application designed to display information about recently detected cosmic rays, as well as to configure sensors by updating their software, turning them on or off, and adjusting their settings.

# <img src="https://icons.veryicon.com/png/o/education-technology/technology-big-data-visualization/network-detection.png" width="30" height="30"> Displaying Last Detections

<img align="right" src="https://github.com/user-attachments/assets/82f9eab8-4cfe-4a93-8a24-7345f3b18b6e">

1. **ID** - This represents a unique identifier for each device within our database. It is essential for tracking specific data points and distinguishing between the different devices contributing to our measurements.
2. **Delta Time** - The initial Delta Time is the timestamp of the first detection. Subsequent entries represent the time intervals, in minutes, between each consecutive detection. This data helps in analyzing the frequency and timing of cosmic ray events.
3. **Direction(in degrees)** - This specifies the angle at which the cosmic ray particles have been detected relative to the sensor. The direction is measured in degrees, aiding in understanding the spatial distribution and origin of the rays.
4. **Intensity** - This refers to the measured brightness or strength of the detected signal on the sensor matrix. Intensity levels are crucial for assessing the energy and potential impact of each cosmic ray particle.
5. **Arrows** - These navigational elements enable users to scroll through previous and next detections. The functionality automatically disables at the boundary points, preventing navigation beyond the available dataset. This feature is instrumental in efficiently reviewing sequential cosmic ray events.
<br clear="right"/>

# <img src="https://cdn-icons-png.freepik.com/512/7555/7555805.png" width="30" height="30"> Map With Markers
<img align="right" src="https://github.com/user-attachments/assets/ca0e6268-8bcc-4288-89ef-1f8d5263a3da">

1. **Save/Update** - Saves or updates current map configuration
2. **Set Time Variables** - Choosing date range to display detections of particles occurred within this range. This form also allows to set step of moving range back and forth - used in "Up" and "Down" buttons
3. **Up** - adds step value to "From" and "To" boundaries in date range
4. **Down** - subtracts step value from "From" and "To" boundaries in date range
5. **Device Indicator** - marker is representation of device on the map. It's rotation shows from which direction particle came from.


<img src="https://github.com/user-attachments/assets/45a8aa73-f5d1-469e-88ec-0e62662cadc2" height="500">
<img src="https://github.com/user-attachments/assets/f6dbb504-a64a-4b6f-92fb-4aafc69b6770" height="500">

<br clear="right"/>

# <img src="https://cdn-icons-png.freepik.com/256/8479/8479052.png?semt=ais_hybrid" width="30" height="30"> Images Of Detections
<img align="right" src="https://github.com/user-attachments/assets/05c3312a-3814-4717-bf7a-8724b05e3b25">

1. **ID** - Is an unique ID of the device in our DB
2. **Occurance Time** - Date of Detection
3. **Direction(in degrees)** - at what angle the radiation particle came
4. **Intensity** - recorded brightness on the matrix
5. **1 Arrows** - Choosing Device
6. **2 Arrows** - Choosing Detection Of Device

<br clear="right"/>

# <img src="https://png.pngtree.com/png-vector/20230822/ourmid/pngtree-app-drawer-icon-vector-template-design-download-png-image_6852897.png" width="30" height="30"> Navigation And Another Options
<img align="right" src="https://github.com/user-attachments/assets/1b76304a-3611-40fd-9f19-307510d176a0">

1. **Last Detections**
2. **Map Of Sensors**
3. **Saved Maps**
4. **Sensors' Images** - Images of Detections
5. **Set Threshold Of Device** - Configures sensitivity of sensor
6. **Reset Device** - Forces device to rerun
7. **Turn Off/On Device**
8. **Upload Software** - Selecting soft version and applying it to particular device
9. **Update Location** - Get's GPS data and aplies it to device

<br clear="right"/>
