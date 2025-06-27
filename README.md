# 🧪 Simulation-Microwave-Oven-Project-Code-For-PIC16F877A

This project is a simulated **Microwave Oven** developed using the **PIC16F877A microcontroller** in **PICSimLab**. It features a digital timer, heating simulation, mode selection, and user interface similar to a real microwave oven.

---

## 📸 Screenshots

![Microwave Simulation](![prototype](https://github.com/user-attachments/assets/c9c71ae5-a671-42a4-8cc5-3dbac33341fa))

---

## 🔧 Features

- ⏲️ **Time Setting** using keypad
- 🍽️ Multiple Cooking Modes: Micro, Grill, Convection
- ▶️ **Start / Resume** functionality
- ⏸️ **Pause** and ⏹️ **Stop** features
- 🔔 **Time Up Message** with buzzer
- 🌬️ Heater and Cooler simulated
- 💻 Simulated on **PICSimLab**

---

## 🧠 Components Used

- **Microcontroller**: PIC16F877A  
- **Simulator**: PICSimLab  
- **LCD Display** (16x2)  
- **Keypad** (Matrix 4x4)  
- **Buzzer**
- **Heater and Cooler (LED/Simulated fans)**  
- **Internal Timer Logic**

---

## 🖥️ Project Flow

1. **Welcome Screen** ➡️
2. **Mode Selection Menu**  
3. **Set Cooking Time (MM:SS)**  
4. **Start, Pause, Stop Options**  
5. **Countdown Timer Displayed**  
6. **“Time Up” Message** when cooking ends  

---

## 🚀 How to Simulate

1. Open **PICSimLab**  
2. Load the `.hex` file generated from MPLAB or XC8  
3. Ensure proper connections of LCD, Keypad, and Buzzer in simulation  
4. Run the project and interact using the keypad

---

## 🛠️ Source Code

> Add your main `.c` or `.asm` files in the `/src` folder  
> Add `.hex` files in `/build` folder if available

Example file structure:

---

## 📚 Tools & Software

- [PICSimLab]
- [MPLAB X IDE](https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide)
- [XC8 Compiler](https://www.microchip.com/en-us/tools-resources/develop/mplab-xc-compilers)
