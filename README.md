# Nail pHolish App

## Overview
The Nail pHolish app is designed to work in conjunction with the Nail pHolish biosensor, a colorimetric nail polish that detects pH changes through interactions with body and environmental fluids. Using a Nix Color Sensor (Nix Spectro 2), the app converts the color of the nail polish into pH levels through RGB analysis, providing users with real-time chemical detection information. The app is intuitive and user-friendly, featuring three main pages: Home, Nix Sensor, and Results.

## Features
- **Biosensor Nail Polish Detection**: 
   - Nail polish made with anthocyanins detects pH changes (e.g., pH 5, 6, 7, 8).
   - Captures color changes on the nail and processes RGB data via the Nix Spectro 2 color sensor.
   
- **pH-Level Detection System**:
   - Uses the Nix Spectro 2 to capture RGB values from the nail surface.
   - Converts RGB values into pH levels using colorimetric analysis.
   - Euclidean distance calculation for accurate pH estimation.
   - Supports custom RGB value input for dynamic recalibration and adaptation to different biosensors.

- **Customizable Calibration**:
   - Users can create and save custom target RGB values for various biosensor swatches.
   - Allows flexibility for use in a wide range of scenarios beyond pH detection.

## Pages

### 1. Home Page
The Home page is the app's landing screen and serves as the starting point for using the Nail pHolish biosensor. From this page, users can:
- Navigate to the Nix Sensor page to connect to their Nix Color Sensor.
- View general information about the Nail pHolish system.
- Access settings for the app and user preferences.
<img src="https://github.com/user-attachments/assets/7ba81a08-5c24-4031-b81a-5ea6160db586" alt="Home" width="400"/>

### 2. Nix Sensor Page
This page allows users to interact directly with the Nix Color Sensor (Nix Spectro 2). Key functionalities include:
- **Sensor Pairing**: Establish a Bluetooth connection with the Nix Color Sensor.
- **Color Measurement**: Capture RGB values from the biosensor nail polish on the user's fingernails.
- **Calibration**: Adjust target RGB values for more accurate pH detection or to accommodate new biosensor colors.
- **Manual Input**: Allows users to input custom target values for specific use cases.

<img src="https://github.com/user-attachments/assets/3bb2a1e3-ba87-46a3-a8a8-0cd375b705b6" alt="Nix" width="400"/>
<img src="https://github.com/user-attachments/assets/e5b07c16-ce37-4c11-b7dc-8d77cef5208f" alt="Edit" width="400"/>

### 3. Results Page
The Results page displays the processed data after RGB color capture, showing the estimated pH level based on the biosensor’s color change. The page features:
- **Real-time pH Display**: Shows the pH level detected from the nail polish.
- **Graphical Visualization**: Provides a visual representation of the pH change over time or after different measurements.
- **Data Logging**: Stores previous readings for tracking trends and comparisons.

<img src="https://github.com/user-attachments/assets/a44f6474-6d17-45e1-9b54-c36b25cb5b20" alt="Results" width="400"/>

## Setup and Installation

### Hardware Requirements:
- Nix Color Sensor (Nix Spectro 2)
- Android/iOS mobile device

## License
The Nail pHolish app is open-source and distributed under the MIT License. For more information, please refer to the LICENSE file in the repository.




