# -Design-and-pregaming-of-digital-and-along-sensor


![Screenshot 2025-01-26 221559 (2)](https://github.com/user-attachments/assets/225ab939-7105-427d-bf42-409ad9f6f665)
Circuit Description:
This circuit consists of an (Arduino UNO) board and essential components to read temperature values from a TMP sensor.

Components:
1. (Arduino UNO): The main control unit managing the readings and processing.
2. (TMP Sensor): Measures temperature, connected to the analog pin A0.
3. (LEDs): Three LEDs (green, yellow, red) indicate the system status based on temperature readings.
4. (Breadboard): Facilitates easy connections without soldering.
5. (Jumper Wires): Used for connecting components.



![image](https://github.com/user-attachments/assets/a550d216-17d3-4979-8a4a-dbcbda76f3d7)


The following logic is implemented using a visual programming environment to manage temperature readings from the TMP sensor and control the LEDs Consequently:
1. (Reading Temperature):
    a- The code reads the analog value from the TMP sensor connected to pin A0.
    b- This value is then mapped from a range of 20 to 3.04 to a new range of -40 to 125, allowing the conversion of raw sensor data into meaningful temperature values.

2. (Printing to Serial Monitor):
   a- The mapped temperature value is printed to the Serial Monitor for real-time monitoring.

3. (LED Control Logic):
    a- If the temperature is less than 20:
    b- Set pin 2 (green LED) to HIGH (on) and pin 3 (yellow LED) and pin 4 (red LED) to LOW (off).
   
---> If the temperature is between 20 and 40:
     Set pin 3 (yellow LED) to HIGH (on) and the other LEDs to LOW (off).
---> If the temperature exceeds 40:
     Set pin 4 (red LED) to HIGH (on) and the other LEDs to LOW (off).


Here is the code:
https://1drv.ms/t/c/9448f0a8866e182f/EdY8PDjj_YBFqawiN7-MUNsBMsHYlvh_d8Xf_C_BEdujww?e=oAGxWK




