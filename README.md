# Eye-Blink-Detection
Spoofing refers to the act of attempting to deceive a biometric system by presenting fake or artificial biometric data. In the case of eye-based biometric systems, such as iris recognition or eye-tracking, it is possible to spoof the system by presenting a static image or video of an individual's eyes instead of their actual eyes. To prevent such spoofing attacks, eye blink detection can be used as a countermeasure.  

# install important Packages  
```bash
pip install opencv-python cvzone
pip install mediapipe --user
```  

# Prep Work for Video save
 1. Download the ffmpeg build from this [Link](https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl.zip) (**Recomended for simplicity**),  or you can Go to the Repo and get the latest Build [Here](https://github.com/BtbN/FFmpeg-Builds/releases)
 2. Extract the `.Zip` folder and add the `bin` folder to your path environment variables
 3. after that close your currnet `shell` or `cmd`  and RUN `ffmpeg --version` to make sure it's corctly installed 
 4. install the python bindings for ffmpeg with 
```bash
pip install ffmpeg-python
```