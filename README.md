# 🚗 Bluetooth Controlled RC Car using Arduino

Control your robot car wirelessly using a phone and an HC-05 Bluetooth module.

## 📦 Components
- Arduino UNO
- HC-05 Bluetooth Module
- L298N Motor Driver
- 2 DC Motors
- Battery
- Android phone (Bluetooth app)

## 🔌 Hardware Connections

### 🔋 L298N Motor Driver:
| L298N Pin | Arduino Pin | Description            |
|-----------|-------------|------------------------|
| IN1       | D2          | Motor A control        |
| IN2       | D3          | Motor A control        |
| IN3       | D4          | Motor B control        |
| IN4       | D5          | Motor B control        |
| ENA       | 5V (or D6 for PWM) | Enable Motor A |
| ENB       | 5V (or D7 for PWM) | Enable Motor B |
| VCC       | Battery +   | External motor power   |
| GND       | GND         | Common ground          |

### 📶 HC-05 Bluetooth Module:
| HC-05 Pin | Arduino Pin | Note                             |
|-----------|-------------|----------------------------------|
| VCC       | 5V          | Power supply                     |
| GND       | GND         | Ground                           |
| TXD       | D0 (RX)     | Bluetooth TX to Arduino RX       |
| RXD       | D1 (TX via voltage divider) | Avoid 5V damage |


## 📱 Controls
- 'F' → Forward  
- 'B' → Backward  
- 'L' → Left  
- 'R' → Right  
- 'S' → Stop  

## 🧠 Author
Rajesh Kanna PB 
