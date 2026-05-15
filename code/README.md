# Source Code

## Code Explanation

This project is implemented using ESP32-CAM and integrates WiFi communication with Telegram Bot API for remote access control.

### Key Functional Blocks

#### 1. WiFi Connection
The ESP32 connects to the local WiFi network using SSID and password.

#### 2. Telegram Bot Integration
- Uses UniversalTelegramBot library
- Sends captured images to user
- Receives commands like:
  - `/photo`
  - `/lock`
  - `/unlock`

#### 3. Camera Module
- Captures image using ESP32-CAM
- Sends image via HTTP POST to Telegram servers

#### 4. Door Lock Control
- Uses GPIO pin connected to transistor (TIP122)
- Controls electronic lock:
  - HIGH → Unlock
  - LOW → Lock

#### 5. Button Trigger
- When push button is pressed:
  - Captures image
  - Sends to Telegram automatically

#### 6. Security Feature
- Only authorized chat ID can control the system

---
