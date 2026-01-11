# Suraksha Sakhi 🛡️

<!-- <p align="center">
  <img src="assets/images/logo.png" alt="Suraksha Sakhi Logo" width="120"/>
</p> -->

<p align="center">
  <strong>Your Personal AI-Powered Safety Companion</strong>
</p>

<p align="center"><a href="https://github.com/user-attachments/assets/7577db9c-9ee1-474f-86f5-9e4e165d7137"> App Demo Video Link </a></p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#how-it-works">How It Works</a> •
  <a href="#ai-agent">AI Agent</a> •
  <a href="#installation">Installation</a> •
  <a href="#privacy">Privacy</a>
</p>

---

## 📱 Overview

**Suraksha Sakhi** is a comprehensive women's safety application designed to provide real-time protection, intelligent threat detection, and instant emergency response. Built with cutting-edge AI technology, Suraksha Sakhi works silently in the background, continuously monitoring your safety and ready to act within seconds when you need help.

Whether you're walking alone at night, commuting through unfamiliar areas, or simply want peace of mind, Suraksha Sakhi is your 24/7 digital guardian.

---

## ✨ Features

### 🚨 Emergency SOS Alert
- **One-Tap SOS**: Instantly send emergency alerts to your trusted contacts with a single tap
- **Shake to Alert**: Discreetly trigger SOS by shaking your phone when in danger
- **Voice Activation**: Say the secret safe word to activate emergency mode hands-free
- **Countdown Timer**: 10-second countdown with option to cancel false alarms
- **Silent Mode**: Send alerts without any sound or visual indication on your phone

### 📍 Real-Time Location Tracking
- **Live Location Sharing**: Share your real-time location with trusted contacts
- **Journey Monitoring**: Set your destination and let Suraksha Sakhi track your route
- **Geo-Fencing**: Get alerts when entering or leaving designated safe/unsafe zones
- **Location History**: Review your travel history for safety analysis
- **Offline Caching**: Location data stored locally when internet is unavailable

### 👥 Trusted Contacts Network
- **Emergency Circle**: Add up to 10 trusted contacts for emergency notifications
- **Priority Levels**: Set primary, secondary, and tertiary contact priorities
- **Auto-Call Feature**: Automatically call emergency contacts when SOS is triggered
- **Contact Verification**: Ensure contacts receive and acknowledge alerts
- **Group Messaging**: Send updates to all contacts simultaneously

### 🤖 AI-Powered Safety Intelligence
- **Threat Detection**: AI analyzes environmental factors to predict potential threats
- **Behavioral Analysis**: Learns your daily patterns to detect anomalies
- **Smart Alerts**: Intelligent notifications based on context and risk level
- **Route Safety Scoring**: AI evaluates route safety before you travel
- **Crowd-Sourced Safety Data**: Community-driven safety information

### 🎯 Motion & Activity Detection
- **Fall Detection**: Automatically detects falls and triggers emergency response
- **Unusual Movement**: Identifies running, struggling, or sudden stops
- **Vehicle Detection**: Knows when you enter/exit vehicles
- **Stationary Alert**: Alerts if you're stationary too long in an unusual location
- **Activity Classification**: Distinguishes between walking, running, cycling, and driving

### 🔊 Audio & Environmental Monitoring
- **Ambient Sound Analysis**: AI listens for distress sounds (screaming, glass breaking)
- **Keyword Detection**: Recognizes distress phrases like "Help me" or "Leave me alone"
- **Audio Recording**: Automatically records audio evidence during emergencies
- **Noise Level Monitoring**: Alerts when environment becomes unusually quiet or loud

### 📞 Emergency Services Integration
- **Direct 112/100 Calling**: One-tap connection to emergency services
- **Women Helpline**: Quick access to women's helpline numbers
- **Nearby Police Stations**: Find and navigate to closest police stations
- **Hospital Locator**: Locate nearest hospitals and emergency rooms
- **Safe Places Map**: Community-verified safe locations nearby

### 📊 Safety Dashboard
- **Safety Score**: Daily safety score based on your activities and locations
- **Risk Analysis**: Visual representation of risk factors throughout the day
- **Weekly Reports**: Comprehensive safety reports and insights
- **Incident History**: Log and review past safety incidents
- **Safety Tips**: Personalized safety recommendations based on your patterns

### ⚙️ Customization & Settings
- **Alert Customization**: Configure what information is shared during emergencies
- **Timer Settings**: Adjust countdown duration and auto-trigger settings
- **Notification Preferences**: Control when and how you receive alerts
- **Battery Optimization**: Power-saving modes for extended protection
- **Offline Mode**: Core safety features work without internet

---

## 🧠 How the AI Agent Works

Suraksha Sakhi's AI Agent is the brain behind your safety, working tirelessly in the background to keep you protected. Here's how it operates:

### Background Processing Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                    Suraksha Sakhi AI Agent                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐          │
│  │   Location   │  │   Motion     │  │    Audio     │          │
│  │   Sensor     │  │   Sensor     │  │   Sensor     │          │
│  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘          │
│         │                 │                 │                   │
│         └────────────┬────┴────────────────┘                   │
│                      ▼                                          │
│         ┌────────────────────────┐                             │
│         │   Data Fusion Layer    │                             │
│         │  (Sensor Integration)  │                             │
│         └───────────┬────────────┘                             │
│                     ▼                                           │
│         ┌────────────────────────┐                             │
│         │   Pattern Recognition  │                             │
│         │   & Anomaly Detection  │                             │
│         └───────────┬────────────┘                             │
│                     ▼                                           │
│         ┌────────────────────────┐                             │
│         │   Risk Assessment      │                             │
│         │   Engine               │                             │
│         └───────────┬────────────┘                             │
│                     ▼                                           │
│         ┌────────────────────────┐                             │
│         │   Decision & Response  │                             │
│         │   System               │                             │
│         └────────────────────────┘                             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 1. Continuous Monitoring Layer

The AI Agent runs as a background service, continuously collecting data from multiple sensors:

- **GPS/Location Services**: Tracks your position every 30 seconds (configurable)
- **Accelerometer**: Monitors movement patterns 50 times per second
- **Gyroscope**: Detects orientation changes and sudden movements
- **Microphone** (when permitted): Periodically samples ambient audio for threat detection

### 2. Pattern Learning & Recognition

```
Daily Pattern Learning:
├── Home Location Detection
├── Work/School Location
├── Regular Commute Routes
├── Typical Travel Times
├── Frequently Visited Places
└── Normal Activity Patterns
```

The AI learns your routine over 7-14 days and establishes a behavioral baseline:

- **Time-Based Patterns**: When you typically leave home, arrive at work, etc.
- **Location Patterns**: Places you regularly visit
- **Movement Patterns**: How you typically walk, your average speed
- **Route Patterns**: Your usual paths for commuting

### 3. Anomaly Detection Engine

The AI continuously compares real-time data against your learned patterns:

| Anomaly Type | Detection Method | Risk Level |
|--------------|------------------|------------|
| Route Deviation | GPS path analysis | Medium |
| Unusual Stop | Location + time analysis | High |
| Sudden Speed Change | Accelerometer data | High |
| Late Night Travel | Time + location | Medium |
| Unfamiliar Area | Location history | Low-Medium |
| Erratic Movement | Motion patterns | High |
| Fall Detection | Accelerometer spike | Critical |

### 4. Risk Assessment Algorithm

```python
# Simplified Risk Calculation
risk_score = (
    location_risk × 0.25 +
    time_risk × 0.20 +
    motion_anomaly × 0.25 +
    route_deviation × 0.15 +
    environmental_factors × 0.15
)

# Risk Levels
LOW:      0.0 - 0.3  → Silent monitoring
MEDIUM:   0.3 - 0.6  → Increased monitoring frequency
HIGH:     0.6 - 0.8  → Alert user, prepare emergency
CRITICAL: 0.8 - 1.0  → Auto-trigger emergency protocol
```

### 5. Intelligent Response System

Based on the risk assessment, the AI Agent takes appropriate actions:

#### Low Risk (Green Zone)
- Standard monitoring every 30 seconds
- Battery-optimized operation
- Background data collection

#### Medium Risk (Yellow Zone)
- Increased monitoring frequency (every 10 seconds)
- Pre-loads emergency contacts
- Subtle notification to user
- Prepares location sharing

#### High Risk (Orange Zone)
- Real-time continuous monitoring
- Displays safety prompt to user
- Auto-enables audio recording
- Notifies primary emergency contact of concern
- Ready to escalate within seconds

#### Critical Risk (Red Zone)
- Immediate SOS activation
- Auto-calls emergency contacts
- Sends location to all trusted contacts
- Begins audio/video recording
- Contacts emergency services if configured
- Activates loud alarm (if enabled)

### 6. Machine Learning Models

Suraksha Sakhi employs several ML models:

| Model | Purpose | Update Frequency |
|-------|---------|------------------|
| Location Classifier | Safe/Unsafe area prediction | Weekly |
| Activity Recognition | Movement type detection | Real-time |
| Anomaly Detector | Unusual behavior identification | Daily |
| Time Series Predictor | Route and ETA prediction | Per journey |
| Audio Classifier | Threat sound detection | Real-time |

### 7. Privacy-First AI Processing

All AI processing happens **on-device** to protect your privacy:

- ✅ Sensor data processed locally
- ✅ Patterns stored only on your device
- ✅ No personal data sent to servers
- ✅ Emergency data shared only with your contacts
- ✅ You control all data sharing settings

---

## 📲 Installation

### Requirements
- Android 8.0 (API 26) or higher
- iOS 12.0 or higher
- Location services enabled
- Motion & Fitness permissions
- Microphone access (optional, for audio monitoring)

### Download

**Android:**
```bash
# Build from source
flutter build apk --release

# APK location
build/app/outputs/flutter-apk/app-release.apk
```

**iOS:**
```bash
flutter build ios --release
```

### Permissions Required

| Permission | Purpose | Required |
|------------|---------|----------|
| Location (Always) | Real-time tracking & safety monitoring | Yes |
| Activity Recognition | Motion pattern analysis | Yes |
| Microphone | Audio threat detection | Optional |
| Contacts | Emergency contact access | Yes |
| Phone | Emergency calling | Yes |
| SMS | Alert message sending | Yes |
| Notifications | Safety alerts | Yes |
| Background App Refresh | Continuous protection | Yes |

---

## 🔒 Privacy & Security

Suraksha Sakhi is built with privacy as a core principle:

### Data Protection
- 🔐 **End-to-End Encryption**: All emergency communications are encrypted
- 🏠 **On-Device Processing**: AI runs locally, your patterns never leave your phone
- 🗑️ **Data Deletion**: Delete all your data anytime from settings
- 👁️ **Transparency**: See exactly what data is collected and how it's used

### What We DON'T Do
- ❌ Sell your data to third parties
- ❌ Store your location history on our servers
- ❌ Listen to your conversations
- ❌ Share information without your explicit consent
- ❌ Track you for advertising purposes

### What We DO
- ✅ Process all safety data on your device
- ✅ Encrypt all emergency communications
- ✅ Give you full control over your data
- ✅ Allow complete data export and deletion
- ✅ Maintain transparent privacy practices

---

## 🛠️ Technical Stack

- **Framework**: Flutter 3.x
- **Language**: Dart
- **AI/ML**: TensorFlow Lite (on-device)
- **Location**: Geolocator, Google Maps
- **Background Processing**: WorkManager, Background Fetch
- **Local Storage**: Hive, SharedPreferences
- **Security**: Flutter Secure Storage, Encryption

---

## 📞 Emergency Numbers (India)

Suraksha Sakhi includes quick access to important emergency numbers:

| Service | Number |
|---------|--------|
| Police | 100 |
| Women Helpline | 1091 |
| Emergency | 112 |
| Ambulance | 108 |
| Women in Distress | 181 |
| Domestic Abuse | 181 |
| Child Helpline | 1098 |

---

## 🚀 Getting Started

### For Developers

```bash
# Clone the repository
git clone https://github.com/yourusername/suraksha-sakhi.git

# Navigate to project directory
cd suraksha-sakhi

# Install dependencies
flutter pub get

# Run the app
flutter run
```

### Build Release APK

```bash
# Build release APK
flutter build apk --release

# The APK will be at:
# build/app/outputs/flutter-apk/app-release.apk
```

---

## 🤝 Contributing

We welcome contributions to make Suraksha Sakhi even better! 

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 💜 Our Mission

> *"Every woman deserves to feel safe, everywhere, every time. Suraksha Sakhi is our commitment to making that a reality through technology."*

Suraksha Sakhi was created with a simple belief: **safety is a right, not a privilege**. We're dedicated to using AI and technology to create a safer world for women everywhere.

---

## 📧 Contact & Support

- **Email**: ridhampatel2k4@gmail.com
- **Issues**: [GitHub Issues](https://github.com/ridh21/suraksha-sakhi/issues)

---

<p align="center">
  Made with ❤️ for women's safety
</p>

<p align="center">
  <strong>Suraksha Sakhi - Because Your Safety Matters</strong>
</p>

---

## ⭐ Star History

If you find Suraksha Sakhi helpful, please consider giving it a star! It helps others discover this project.
