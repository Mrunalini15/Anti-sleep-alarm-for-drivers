# Anti-sleep-alarm-for-drivers


Feeling sleepy while driving could cause hazardous traffic accident. However, when driving alone on highway or driving over a long period of time, drivers are inclined to feel bored and sleepy, or even fall asleep. Nowadays most of the products of driver anti-sleep detection sold in the market are simply earphone making intermittent noises, which is quite annoying and inefficient. As such, there is a high demand for cheap and efficient driver sleep detection. Therefore, we came up with an idea and successfully developed a sleepy detection and alarming system, which could effectively meet this demand.

# Modules
Wireless anti-sleep alarm Wake up call with vibration Sleep Alert Notification to contacts Converting into detachable device

# Implementation
The batteries are connected to a switch. The switch is connected to the IR sensor and the ESP32 microcontroller. When the switch is turned ON the power is supplied to the IR sensor and the ESP32 microcontroller. The ESP32 microcontroller is the central processing unit of the system. It receives the input from the IR sensor and analyzes the data to determine if the driver is becoming drowsy. The microcontroller is connected to a buzzer and a vibrator which turns ON when the IR sensor detects the drowsiness.
