# 🔥 Temperature-Based Heater Control System using Arduino

This project demonstrates a temperature-controlled heater system using an **Arduino UNO**, **LCD Display**, and a **relay module**. The system reads temperature values (via LM35 or simulated potentiometer), displays it on an LCD, and toggles a relay (heater) ON/OFF based on a defined temperature threshold.

---

## 📦 Features

- 📟 LCD 16x2 to display real-time temperature
- 🔁 Relay control for heater switching
- 🌡️ Temperature input via LM35 sensor or potentiometer (in simulation)
- ✅ Fully simulated in **Proteus 8**
- 💡 LED indicator for heater status

---

## 🔧 Components Used

- Arduino UNO
- LM35 / Potentiometer
- LCD 16x2
- Relay module (with transistor & diode)
- NPN Transistor (e.g., 2N2222 or MP6514)
- 1N4007 Flyback Diode
- 1kΩ Resistor
- LED
- Power supply (5V/12V)
- Proteus simulation environment

---

## 🖥️ Simulation Guide (Proteus)

1. Open the provided Proteus `.pdsprj` file.
2. Upload the compiled `.hex` file to the Arduino model.
3. Use a potentiometer in place of LM35 for testing temperature ranges.
4. Observe LCD and relay behavior based on temperature threshold.

---

## 🧠 Logic

- Temperature < 30°C → Heater ON
- Temperature ≥ 30°C → Heater OFF
- Status is shown on the LCD along with temperature

---

## 📁 Project Structure

