# TP LiveView

TP LiveView is a macOS app that displays live TrainingPeaks ride data in a floating window. Keep your metrics visible while watching videos, working, or using other apps.

This project is currently paused – I will resume development in November 2025. Planned improvements include settings for graph duration, colour coding power zones for the immersive mode combined graph, and fixing 'red zone' on the mini graphs which are not working as intended.

Check it out in action ↓

![In Action](https://github.com/ctrlaltwill/TPLiveView/blob/main/Screenshots/In%20Action.png?raw=true)

&nbsp;

## Features

- **Live display** of TrainingPeaks ride metrics.
- **Floating window** that stays on top of other apps.
- **Multiple views**: Compact, Extended, and Immersive.
- **Menu bar integration** for quick switching and status updates.
- **Settings**, set your FTP and Max HR for real-time colour changing on the graphs.
  
&nbsp;

## Screenshots

### Compact View
![Compact View](https://github.com/ctrlaltwill/TPLiveView/blob/main/Screenshots/Compact%20View.png?raw=true)

### Extended View
![Extended View](https://github.com/ctrlaltwill/TPLiveView/blob/main/Screenshots/Extended%20View.png?raw=true)

### Immersive View
![Immersive View](https://github.com/ctrlaltwill/TPLiveView/blob/main/Screenshots/Immersive%20View.png?raw=true)

&nbsp;

## Installation

### From GitHub Zip

1. Download the [TP-LiveView-v1.0.0-beta.zip](https://github.com/ctrlaltwill/TPLiveView/raw/main/TP-LiveView-v1.0.0-beta.zip) file.
2. Unzip the file.
3. Move `TP LiveView.app` to your `Applications` folder.
4. Open the app.
5. Use the settings dialog (from the menubar) to set save your broadcast folder, this will find the focused rider JSON file which the live data feed comes from. You can also set your preferred view and your zones which automatically generates 'red zones' based on % FTP and % MaxHR.

&nbsp;

> ⚠️ **Note:** TP LiveView is built without an official Apple Developer (I am a casual developer and cannot justify paying them annually to distribute my apps), so macOS cannot verify it. The first time you open it, you may see a warning:  
> “Apple cannot verify TP LiveView is free of malware.”  
>
> To bypass this:  
> - Go to **System Settings → Privacy & Security → General**  
> - Click **Open Anyway** for TP LiveView.  
> - Subsequent launches will open normally.

