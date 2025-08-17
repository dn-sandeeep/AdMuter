# AdMuter 🎧🔇

**AdMuter** is an Android app that automatically mutes your device’s media volume when ads are detected from music streaming apps (like Spotify). It enhances your listening experience by eliminating audio interruptions — **without needing root access**.

<br>

## 🌟 Key Features

### 🔇 Auto Mute During Ads

- Detects when an advertisement is playing (via notification listener)

- Instantly mutes the device’s media volume

- Automatically unmutes when the song resumes

- Works entirely using notification access and media volume control

- Doesn’t interfere with the Spotify app directly

- Runs as a background service

## 📸 Screenshots

<img src = "https://github.com/user-attachments/assets/3eddfc40-532b-42e7-b9a7-9810e975a69a" width = 300 />

## ⚙️ How It Works

1. Spotify (or another media app) posts a notification when playing a track or ad.

2. AdMuter listens to the title/text of each media notification.

3. If it matches known ad patterns, it:
   - Mutes the device volume
4. When the notification changes (song resumes), it unmutes automatically.

## 🛠️ Built With

- **Kotlin**
  
- **Jetpack Compose**
  
- **NotificationListenerService**

- **Material Design 3**
