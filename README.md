# 7-Segment Display with Arduino

A simple project that demonstrates how to control a 7-segment display using an Arduino, built and simulated in [Tinkercad Circuits](https://www.tinkercad.com/).

---

## 📸 Demo

<!-- Replace with your actual screenshot or GIF from Tinkercad -->
![7-Segment Display Demo](https://github.com/user-attachments/assets/9c4f3a7b-e835-4362-8053-62420d55d092
)

---


## 🔧 Components Used

| Component         | Quantity |
|------------------|----------|
| Arduino Uno       | 1        |
| 7-Segment Display (Common Cathode) | 1 |
| 1kΩ Resistors  v  | 2        |
| Breadboard        | 1        |
| Jumper Wires      | Several  |

---

## 📐 Circuit Diagram

<!-- Replace with your own Tinkercad circuit screenshot -->
![Circuit Diagram](https://github.com/user-attachments/assets/ef093201-9aa2-42b7-ab4c-dde6f9e02b6d
)


---

## 🔌 Pin Connections

| 7-Seg Pin | Segment | Arduino Pin |
|-----------|---------|-------------|
| a         | Top     | 11          |
| b         | Top-right | 10        |
| c         | Bottom-right | 7      |
| d         | Bottom  | 8           |
| e         | Bottom-left | 9       |
| f         | Top-left | 12         |
| g         | Middle  | 13          |
| GND       | Common Cathode | GND  |


## 🚀 How to Run

1. Open the [Tinkercad project](https://www.tinkercad.com/) *(replace with your share link)*
2. Click **Start Simulation**
3. Watch the display count from 0 to 9

Or upload the code to a real Arduino:
1. Open `sketch.ino` in the [Arduino IDE](https://www.arduino.cc/en/software)
2. Select **Board:** Arduino Uno and the correct **Port**
3. Click **Upload**

---

## 📁 Project Structure

```
├── sketch.ino          # Arduino source code
├── assets/
│   ├── demo.png        # Tinkercad simulation screenshot
│   └── circuit.png     # Circuit diagram screenshot
└── README.md
```

---

