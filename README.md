 # NI LabVIEW Motor Control Project  

This project demonstrates a motor control system designed and simulated in **NI LabVIEW**. The system focuses on implementing control logic for motor **speed regulation, direction switching, and feedback monitoring**. While this version has not yet been tested with physical hardware, it provides a strong foundation for integration with a DC motor and data acquisition hardware in future iterations.  

---

## Features  
- **Speed Control** – Adjustable motor speed via front panel controls  
- **Direction Control** – Forward/reverse switching  
- **Scalable Design** – Structured for expansion to physical testing with NI DAQ devices or FPGA boards  

---

## Project Structure  
- `Motor_Control.vi` → Main LabVIEW VI for speed/direction control  

---

## Requirements  
- **NI LabVIEW 2020 or later**  
- Basic knowledge of LabVIEW front panel and block diagram programming  

---

## Usage  
1. Open `Motor_Control.vi` in LabVIEW  
2. Use the **front panel** to:  
   - Adjust motor speed slider  
   - Switch motor direction toggle  
   - Monitor feedback indicators  
3. (Optional) Expand by connecting the VI to NI DAQ hardware for physical motor testing  

---

## Future Work  
- Test with a **DC motor and NI DAQ** hardware  
- Add support for **PID control** to improve stability  
- Integrate safety features (overcurrent, stall detection, etc.)  

---

