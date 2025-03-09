# SnakeGameArduino
🕹️ Snake Game with Arduino, Joystick, and OLED Display

# Components Required:
Arduino Uno (or compatible board)
- Joystick Module (with VRX, VRY, SW pins)
- 0.96" OLED Display (128x64, SSD1306, I2C)
- Jumper Wires
- Breadboard

# Wiring Diagram:
OLED Display (I2C - 4 Pins):
- VCC → 5V (Arduino)
- GND → GND (Arduino)
- SDA → A4 (Arduino Uno I2C SDA)
- SCL → A5 (Arduino Uno I2C SCL)

Joystick Module:
- VRX → A0 (Analog X-Axis)
- VRY → A1 (Analog Y-Axis)
- SW → D2 (Digital Pin for button press)
- VCC → 5V
- GND → GND
