# Video Conferencing App

- This Android Application is tailored for creating simple video conferencing app by integrating the [VideoSDK](https://www.videosdk.live/) into an Android project. The VideoSDK provides powerful APIs for real-time video and audio communication, making it an excellent choice for developers looking to implement video conferencing features.

## Features

- **Interactive UI**: A simple and clean interface for users to join or create meetings.
- **Toggle Microphone/Camera**: Users can mute/unmute their microphone and turn their camera on/off.

# Prerequisites
- Make sure you have the following before we begin.

1. Basics of Android development.
2. Android Studio installed on your computer.
    -  Java Development Kit.
    -  Android Studio `3.0` or `later`.
    -  Android SDK API Level `21` or `higher`.
    -  A mobile device that runs `Android 5.0` or `later`.  
3. VideoSDK account to get your API key.

## Getting Started

To set up the project, ensure you have the following configurations:


| **Configuration key**                          | **Configuration value**                 |
|------------------------------------------------|-----------------------------------------|
| 1. compileSdk                                  | `33`                                    |
| 2. minSdk                                      | `24`                                    |
| 3. targetSdk                                   | `33`                                    |
| 4. JavaVersion                                 | `1_8`                                   |
| 5. plugins                                     | `7.2.1`                                 |
| 6. buildToolsVersion                           | `30.0.3`                                |

<h1>Installation Instructions</h1>
  
To run this project locally, follow these steps:

**1. Clone the repository:**

```bash

git clone https://github.com/RomilMovaliya/Video-Conferencing-App.git

```

**2. Nevigate To Our Directory:**
```bash
cd videosdktask2
```

**4. Replace `api-key` in `JoinActivity.java` with your actual API key from VideoSDK.live.**

```bash


//Replace with the token you generated from the VideoSDK Dashboard
    private String sampleToken ="YOUR-TOKEN";


```

**5. Run After completion of above steps**
- If all is done then `run` your project.

# Screenshots

<div align="center">
    <img src="https://github.com/RomilMovaliya/Video-Conferencing-App/blob/main/WhatsApp%20Image%202024-11-02%20at%205.59.06%20PM.jpeg" alt="SLIDE1.JPG" width="200" />
    <img src="https://github.com/RomilMovaliya/Video-Conferencing-App/blob/main/WhatsApp%20Image%202024-11-02%20at%205.59.07%20PM%20(1).jpeg" alt="SLIDE2.JPG" width="200"/>
    <img src="https://github.com/RomilMovaliya/Video-Conferencing-App/blob/main/WhatsApp%20Image%202024-11-02%20at%205.59.07%20PM.jpeg" alt="SLIDE3.JPG" width="200"/>
    
</div>
<br>

<div align="center">
<img src="https://github.com/RomilMovaliya/Video-Conferencing-App/blob/main/WhatsApp%20Image%202024-11-02%20at%205.59.37%20PM.jpeg" alt="SLIDE4.JPG" width="200"/>
<img src="https://github.com/RomilMovaliya/Video-Conferencing-App/blob/main/WhatsApp%20Image%202024-11-02%20at%205.59.38%20PM.jpeg" alt="SLIDE5.JPG" width="200"/>
</div>
  
## License
This repository is licensed under the MIT License.
