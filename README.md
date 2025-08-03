Drowsiness Detection System 🚗💤

This project is an AI-powered real-time drowsiness detection system that monitors a driver's eyes and provides audio alerts if signs of sleepiness are detected. If drowsiness persists beyond a set threshold, an emergency WhatsApp message is sent to a registered contact using Twilio.

Features
- Real-time face & eye tracking using OpenCV & dlib
- Drowsiness detection using Eye Aspect Ratio (EAR)
- Voice alerts to wake up the driver (via pyttsx3)
- Emergency WhatsApp alert if drowsiness continues (via Twilio)

How It Works
- The webcam detects the face and eyes.
- The program calculates the Eye Aspect Ratio (EAR).
- If EAR drops below the drowsiness threshold (0.14), an audio alert is triggered.
- If drowsiness lasts more than 3 seconds, an emergency WhatsApp message is sent.

Future Enhancements
- Mobile app integration
- Advanced AI-based drowsiness detection
- Cloud-based alert system

License
This project is open-source. Feel free to modify and enhance it!
