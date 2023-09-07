# FastAPI Image Enhancement Flutter App

## Overview

The FastAPI Image Enhancement Flutter App is a mobile application that empowers users to enhance their photos. By selecting an image from their device's gallery, users can initiate a POST request to a FastAPI-based image enhancement service. The service processes the chosen image by applying various enhancements, including resizing, contrast and color saturation adjustments, and sharpening. Subsequently, the improved photo is sent back as a response.

## Features

- **Select Photos**: Users can pick photos from their device's gallery.

- **Enhance and Process**: The selected photo is sent to a FastAPI image enhancement service, which performs enhancements on the image.

- **Display Enhanced Photos**: Users can view the improved photo directly within the app.

## User Flow

1. **App Launch**:

   - Open the app on your mobile device.

2. **Select a Photo**:

   - Tap the "Choose Photo" button to access your device's photo gallery.
   - Pick an image from your gallery that you wish to enhance.

3. **Initiate Enhancement**:

   - After selecting a photo, tap the "Enhance" or "Process" button.
   - The app sends a POST request to the FastAPI image enhancement service.

4. **Processing Indicator**:

   - While the image is being processed, a loading indicator is displayed to keep the user informed.

5. **View Enhanced Photo**:

   - Once processing is complete, the improved photo is displayed within the app.

6. **Save or Share**:

   - Users can choose to save or share the enhanced photo as desired.

## Technologies Used

- **Flutter**: An open-source UI development framework that facilitates the creation of natively compiled applications for mobile, web, and desktop.

- **HTTP Package**: Utilized for sending POST requests to interact with the FastAPI service.

- **Image Picker Package**: Enables users to select photos from their device's gallery effortlessly.
