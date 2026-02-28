# SmartParkAssistant
# 1.Introduction
Parking in tight or crowded spaces is a constant challenge for drivers, often leading 
to avoidable accidents and vehicle damage. While cars built-in sensors, many 
drivers still struggle with “Blind spots” and poor distance judgement. Smart Park 
Assist offers a smart, low cost solution by using ultrasonic technology to “see” 
obstacles in real time. 
By using the combination of Esp 32 microcontroller and Sound wave sensors, the 
system warns the driver in two way: through a light indication and live update in 
their phone. This project makes parking safer, easier and much more accurate by a 
tiny computer into a personal parking assistant. 
# 2.Aim 
To design and implement an intelligent parking assistance system that provides 
both visual (LED) and digital (Web Interface) real-time feedback to prevent 
vehicle collisions during parking. 
# 3. Objective
a. High precision Distance Measurement: 
  To utilize ultrasonic sound wave propagation to detect obstacles with a resolution 
  of 1cm. By calculating the “Time of Flight” (The time taken for the sound pulse to 
  bounce back), the system provides an accurate digital measurement of the 
  remaining space. 
b. Visual warning system: 
  To design a 5-stage LED bar graph that acts as a physical proximity gauge. This 
  provides the driver with an accurate status: 
  • Green(safe); Distance >10cm 
  • Red (Critical): Distance<10cm 
  This mimics the parking sensors found in high-end luxury vehicles. 
c. Standalone IoT Integration: 
  To configure the ESP32 as a Wireless Access Point. This objective ensures the 
  system functions as a "Private IoT Cloud," allowing any smartphone to connect to the "ESP32" Wi-Fi network to view a live, high-definition distance dashboard 
  without needing an internet connection or a router.
d. Real-Time Latency Optimization
  To maintain a system refresh rate of 10Hz (100ms). This ensures that the distance 
  displayed on the web interface and the LED status are synchronized with the 
  vehicle's movement in real-time, preventing "lag-induced" collisions.
