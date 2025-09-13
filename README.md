# smart-window-multi-sensor
Prototipe Jendela Cerdas berbasis Arduino Uno dengan sensor MQ-2, hujan, dan LDR
# Smart Window System using Arduino Uno

Prototipe jendela otomatis berbasis Arduino dengan sensor asap (MQ-2), hujan, dan cahaya (LDR).

 📋 Komponen
- Arduino Uno
- Sensor MQ-2
- Sensor Hujan
- LDR
- Servo MG90S

🔌 Wiring Diagram
1. SENSOR MQ-2
VCC → +5V Arduino

GND → GND Arduino

A0 → Pin Analog A0 Arduino

2. SENSOR HUJAN
VCC → +5V Arduino

GND → GND Arduino

A0 → Pin Analog A1 Arduino

3. SENSOR CAHAYA (LDR)
Salah satu kaki → +5V

Kaki lainnya → Pin Analog A2 Arduino + Resistor 10kΩ ke GND

(Membentuk pembagi tegangan)

4. SERVO MOTOR
VCC (Merah) → +5V Arduino (gunakan sumber eksternal jika perlu)

GND (Coklat) → GND Arduino

Sinyal (Oranye) → Digital Pin 9 (PWM)

🚀 Cara Menggunakan
1. Download kode dari folder code/
2. Upload ke Arduino menggunakan Arduino IDE
3. Hubungkan komponen sesuai diagram

 Jurnal](link)
