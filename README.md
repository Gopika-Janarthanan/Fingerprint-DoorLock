# Fingerprint DoorLock Using Arduino Uno  

This project, developed by our team, is a **Fingerprint DoorLock Using Arduino Uno** system powered by Arduino. It combines biometric technology and embedded systems to provide a secure and efficient way to control access to lockers or enclosures. Our goal was to build an affordable and customizable locking system that is both practical and educational.  

---

## Project Highlights  
- **Biometric Access**: Uses fingerprint recognition for authentication.  
- **User-Friendly Design**: Easy to set up and operate with clear visual indicators.  
- **Customizable**: Flexible enough to be adapted for various applications, such as home lockers or office storage.  
- **Team Collaboration**: This project reflects our joint efforts in electronics, programming, and innovation.  

---

## Components We Used  
1. **Arduino Uno**  
2. **Fingerprint Sensor**  
3. **Servo Motor**  
4. **Push Buttons** (for enrolling and deleting fingerprints)  
5. **LED Indicators** (Green - Success, Red - Error, Yellow - Processing)  
6. **Breadboard and Jumper Wires**  
7. **5V Power Supply**  

---

## How It Works  
1. **Enrollment Mode**:  
   - Users can add their fingerprints using a dedicated push button.  
   - Each fingerprint is stored in the Arduino's database.  

2. **Verification Mode**:  
   - Users scan their fingerprints for authentication.  
   - If the fingerprint matches a stored entry, the servo motor unlocks the system.  

3. **Feedback System**:  
   - Green LED: Successful Authentication  
   - Red LED: Access Denied  
   - Yellow LED: System is Processing  

4. **Delete Mode**:  
   - Use another push button to delete registered fingerprints.  

---

## Setup Instructions  
1. Assemble the circuit as per the circuit diagram (included in the project folder).  
2. Install the required libraries:  
   - `Adafruit_Fingerprint` for the fingerprint sensor  
3. Upload the provided Arduino code to the board using Arduino IDE.  
4. Test the system by enrolling fingerprints and verifying access.  

---

## Challenges We Faced  
- Configuring the fingerprint sensor for precise recognition.  
- Debugging hardware connections during initial tests.  

---

## Applications  
- Personal lockers and safes.  
- Office storage solutions.  
- Educational purposes to learn about biometrics and IoT systems.  

---

## Future Enhancements  
- Integrating a display for better user interaction.  
- Adding Wi-Fi or Bluetooth connectivity for remote control.  
- Expanding the database capacity for more fingerprints.  

---

## Acknowledgments  
We extend our gratitude to #FlyRobo for providing inspiration and resources for this project.  

---

## License  
This project is open-source and free to use for educational purposes. 

