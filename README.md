🌙 Moon Phase Tracker with Arduino + RTC
An elegant moon phase tracker built using Arduino, a real-time clock (RTC) module, and an OLED display. This compact device calculates and displays the current moon phase based on real-time date data — perfect for space enthusiasts, night photographers, or just anyone who loves to track the night sky.

🧠 How It Works
The DS3231 RTC module provides accurate current date/time to the Arduino.

The code calculates the current moon phase using astronomical algorithms.

The OLED display shows:

Current date

Calculated moon phase (e.g., Full Moon, Waxing Crescent)

Optional: a simple moon icon representing the phase

🛠️ Hardware Used
🧠 Arduino Nano / Uno / Pro Mini

🕒 DS3231 RTC Module

🖥️ SSD1306 128x64 OLED Display

🔋 Battery pack or USB power

💻 Software Tools & Libraries
RTClib by Adafruit (for DS3231)

Adafruit_SSD1306 and Adafruit_GFX (for OLED)

Custom moon phase calculation logic

🚀 Features
🌑 Accurate moon phase calculation based on RTC date

📅 Date display from the real-time clock

🖼️ Simple user interface on OLED screen

⚡ Low power consumption

📦 Compact and 3D-printable enclosure ready

📦 Installation
Wiring:

Module	Arduino Pin
OLED (SDA)	A4
OLED (SCL)	A5
RTC (SDA)	A4
RTC (SCL)	A5

Install required libraries in the Arduino IDE:

Adafruit SSD1306

Adafruit GFX

RTClib

Upload the code via Arduino IDE.

🖼️ Display Example
yaml
Copy
Edit
📆 Aug 1, 2025
🌔 Waxing Gibbous
Optional: Icon representing moon phase shown graphically.

🔄 Future Upgrades
Add moonrise/moonset time calculations

Show lunar illumination percentage

Add zodiac signs or sunrise/sunset for each day

Sync date/time over Bluetooth or GPS

🎁 Applications
Astronomy education tools

Nighttime photography planning

Calendar companion

Desktop or wall-mounted lunar gadget

👨‍🚀 Built By
Project by SOoooorya



