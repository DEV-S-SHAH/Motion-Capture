# Human Motion Capturing Using Wearables

This repository demonstrates real-time human motion capturing through wearable technology, leveraging the MPU6050 sensor and Arduino Uno for data processing. The motion data is visualized in a 2D representation using the Pygame Python library.

## Components Used

1. **MPU6050 Sensor:** A 6-DoF (Degrees of Freedom) sensor, combining gyroscope and accelerometer, for accurate motion tracking.

2. **Arduino Uno:** Responsible for data processing, sensor interfacing, and real-time data transmission.

3. **Arduino Software:** The official integrated development environment (IDE) for writing and uploading code to the Arduino board.

4. **Pygame Library:** A Python library used for building interactive 2D games and simulations, applied here for real-time motion visualization.

## How It Works

1. **Data Acquisition:** The MPU6050 sensor records motion data (gyroscope and accelerometer readings) as the subject moves.

2. **Arduino Processing:** Arduino Uno processes raw data, performs necessary calculations, and prepares the data for visualization.

3. **Data Transmission:** Processed data is transmitted from Arduino to the computer via a serial connection.

4. **Python Visualization:** The Pygame library decodes and interprets the data, creating a 2D representation of the subject's motion.

5. **Real-Time Display:** The motion visualization updates in real time, providing an intuitive representation of the captured human motion.

## Getting Started

1. Clone this repository: [`Wearable-Motin-capturing`](https://github.com/DEV-S-SHAH/Wearable-Motion-Capture.git)

2. Connect the MPU6050 sensor to the Arduino Uno following the provided schematic.

3. Upload the Arduino code [`arduino_code.ino`](https://github.com/DEV-S-SHAH/Wearable-Motion-Capture/blob/main/Wearable-Motion-Capturing/arduino_code.ino)using the Arduino Software.

4. For the calcualtion using graphs use [`calculations.ino`](https://github.com/DEV-S-SHAH/Wearable-Motion-Capture/blob/main/Wearable-Motion-Capturing/calculations.ino).

5. Install Python and Pygame library on your computer.

6. Run the Python script [`left_hand.py`](https://github.com/DEV-S-SHAH/Wearable-Motion-Capture/blob/main/Wearable-Motion-Capturing/left_hand.py) to start the real-time motion visualization.

7. Wokwi Simulator: An online platform [`wokwi sumlator`](https://wokwi.com/projects/372849380809466881) for simulating and testing Arduino projects virtually.
                     

## Future Enhancements

- Implement more advanced motion analysis algorithms.
- Expand the visualization to support 3D representations.
- Integrate machine learning for gesture recognition.

## Contributions

Contributions are welcome! If you have ideas or improvements, please open an issue or submit a pull request.

---

Feel the pulse of motion as you explore the synergy of hardware and software. Dive into the captivating world of human motion tracking using wearables and embark on a journey of innovation.

If you have any questions or inquiries, feel free to reach out to me via email at [`DEV-S-SHAH`](mailto:devs4452@gmail.com).

