# Mercedes-Benz W202 Speedometer Replacement (rusEFI)

This project is a custom **speedometer replacement** for a **1994 Mercedes-Benz W202 C180 (pre-facelift)** running on a **rusEFI open-source standalone ECU**.  

⚠️ **Disclaimer:**  
This is an **open-source project** provided *as-is*, without any warranty or support.  
It is intended strictly for **educational and hobbyist purposes only**.  

---

## 📖 Background

This project builds upon the excellent work by [Pazi88](https://github.com/pazi88/E12_CAN_gauges), originally designed for a BMW E12 speedometer.  

Test implementation has been successfully tested with **rusEFI Dash CANBUS** with a BMW E46 CAN Dash setting, supporting:  
- **RPM**  
- **VSS (Vehicle Speed Sensor)**  
- **CLT (Coolant Temperature)**  

---

## 📟 Hardware Integration

For this adaptation, additional components were introduced:  
- **Nextion Enhanced 3.5” display**  
- **STM32F103C8T6 “Blue Pill” MCU**  

These allow enhanced visualization of live ECU data.  

The **schematic and hardware design** were adapted specifically to meet the requirements of this W202 project.  

---

## 💻 Firmware Status

- Development for the **STM32F103C8T6** firmware is still in progress.  
- For working code examples and inspiration, refer to Pazi’s original repository.  

---

## ⚠️ Important Notice

- ✅ **Responsibility**: You are solely responsible for checking and complying with all **local laws and regulations** before using this project.  
- ✅ **Road Use**: Compliance with vehicle safety and legal standards for public road use is mandatory.  
- ✅ **Liability**: No liability is accepted for misuse, damages, or legal issues resulting from use of this project.  
- 🚫 **Commercial Use**: Strictly prohibited.  
- 📌 **Recommendation**: Ensure you fully understand the project before attempting implementation.  

---

## 📜 License

This project is open-source, non-commercial, and intended for **educational/hobbyist purposes only**.  
Please respect the open-source spirit of this project — it is not to be used for making money
