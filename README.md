# Cosmic Ray WAT Idea
This is an official Military University of Technology application designed to display information about recently detected cosmic rays, as well as to configure sensors by updating their software, turning them on or off, and adjusting their settings.

# <img src="https://icons.veryicon.com/png/o/education-technology/technology-big-data-visualization/network-detection.png" width="30" height="30"> Displaying Last Detections
<div>
  <img align="right" src="https://github.com/user-attachments/assets/82f9eab8-4cfe-4a93-8a24-7345f3b18b6e">
</div>


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

1. **ID** - This refers to a unique identifier assigned to each device within our database. It ensures precise tracking and identification, facilitating accurate data aggregation and analysis across different devices.
2. **Occurance Time** - Indicates the exact date and time when the cosmic ray was detected. This timestamp is critical for logging events and enables researchers to correlate detections with other celestial phenomena.
3. **Direction(in degrees)** - This measures the angle at which the cosmic radiation was detected by the sensor. Expressed in degrees, this parameter helps determine the trajectory of the incoming particles and can be crucial for spatial mapping of cosmic ray origins.
4. **Intensity** - Reflects the luminosity or strength of the detection as recorded by the device's sensors. Higher intensity values might indicate closer or more significant cosmic ray events, making this a vital metric for studying cosmic radiation.
5. **1 Arrows** - These controls allow users to cycle through the list of devices in the database. This functionality is essential for quickly navigating between different sensors or setups to compare data or analyze specific device outputs.
6. **2 Arrows** - Facilitates navigation among various detections recorded by a selected device. This feature enhances user interaction, enabling detailed examination of the chronological sequence of events or comparisons of activity across different times.

<br clear="right"/>

# <img src="https://png.pngtree.com/png-vector/20230822/ourmid/pngtree-app-drawer-icon-vector-template-design-download-png-image_6852897.png" width="30" height="30"> Navigation And Another Options
<img align="right" src="https://github.com/user-attachments/assets/1b76304a-3611-40fd-9f19-307510d176a0">

1. **Last Detections** - Displays the most recent cosmic ray detection events recorded by our sensors. This feature provides quick access to the latest data, helping users stay updated with real-time observations.
2. **Map Of Sensors** - This interactive map showcases the geographical distribution of all the sensors involved in detecting cosmic rays. Users can visually locate and select different sensors to view specific data or compare readings across locations.
3. **Saved Maps** - Allows users to access previously saved layouts of sensor maps. This feature is useful for revisiting specific studies or comparisons without the need to recreate the map setup from scratch.
4. **Sensors' Images** - Presents photographic or graphical images of detections made by the sensors. These images are valuable for visual analysis and verification of the cosmic ray events.
5. **Set Threshold Of Device** - Enables users to adjust the sensitivity of a sensor. Setting the threshold is crucial for optimizing detection capabilities and can be tailored to focus on events of particular interest or intensity.
6. **Reset Device** - This function allows users to restart a device remotely. Resetting is useful for troubleshooting or clearing errors, ensuring that sensors operate without disruptions.
7. **Turn Off/On Device** - Provides the ability to remotely deactivate or activate a device. This control is essential for managing the operational status of sensors, allowing for maintenance or conservation of power when necessary.
8. **Upload Software** - Facilitates the selection of software versions and their application to a specific device. This feature ensures that all devices are up-to-date with the latest enhancements and security patches.
9. **Update Location** - Retrieves and updates the GPS coordinates of a device. Accurate location data is critical for aligning detection data with geographic information, aiding in precise mapping and analysis.

<br clear="right"/>
