# Cosmic Ray WAT Idea
This is an official Military University of Technology application designed to display information about recently detected cosmic rays, as well as to configure sensors by updating their software, turning them on or off, and adjusting their settings.

# <img src="https://icons.veryicon.com/png/o/education-technology/technology-big-data-visualization/network-detection.png" width="30" height="30"> Displaying Last Detections

<img align="right" src="https://github.com/user-attachments/assets/82f9eab8-4cfe-4a93-8a24-7345f3b18b6e">

1. **ID** - Is an unique ID of the device in our DB
2. **Delta Time** - first Delta Time is date of detection, all remaining are intervals(in minutes) between each other.
3. **Direction(in degrees)** - at what angle the radiation particle came
4. **Intensity** - recorded brightness on the matrix
5. **Arrows** - Display previous/next detections. It blocks as you reach last or first detection correspondingly
<br clear="right"/>

# <img src="https://cdn-icons-png.freepik.com/512/7555/7555805.png" width="30" height="30"> Map With Markers
<img align="right" src="https://github.com/user-attachments/assets/ca0e6268-8bcc-4288-89ef-1f8d5263a3da">

1. **Save/Update** - Saves or updates current map configuration
2. **Set Time Variables** - Choosing date range to display detections of particles occurred within this range. This form also allows to set step of moving range back and forth - used in "Up" and "Down" buttons
3. **Up** - adds step value to "From" and "To" boundaries in date range
4. **Down** - subtracts step value from "From" and "To" boundaries in date range
5. **Device Indicator** - marker is representation of device on the map. It's rotation shows from which direction particle came from.


<img src="https://github.com/user-attachments/assets/45a8aa73-f5d1-469e-88ec-0e62662cadc2" height="400" padding="8">
<img src="https://github.com/user-attachments/assets/f6dbb504-a64a-4b6f-92fb-4aafc69b6770" height="400" padding="8">

<br clear="right"/>

