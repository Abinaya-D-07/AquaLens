# AquaLens

AquaLens is an IoT-based visual monitoring prototype using the AI Thinker ESP32-CAM to capture and store images of water environments at regular intervals.

## Objective

* Capture water-environment images automatically.
* Store images locally for observation and analysis.
* Provide a foundation for future AI-based water pollution monitoring.

## Components

* AI Thinker ESP32-CAM
* MicroSD Card
* Wi-Fi
* Arduino IDE

## Working

* Initialize the camera and MicroSD card.
* Connect to the configured Wi-Fi network.
* Capture an image every 30 seconds.
* Save the image as `photo.jpg` on the MicroSD card.
* Repeat the process continuously.

## Output

* JPEG images stored on the MicroSD card.
* Wi-Fi and capture status displayed on the Serial Monitor.


