# Smart Self-Heating Mug – Intelligent Temperature-Controlled Beverage Heating System

## 1. Project Overview

The Smart Self-Heating Mug is an intelligent beverage temperature-maintenance system designed to keep hot beverages at their desired drinking temperature for extended periods. The primary problem addressed by this project is the gradual cooling of hot beverages when exposed to room temperature. Conventional mugs do not provide any mechanism to restore the beverage temperature once it falls below a comfortable level.

To overcome this limitation, the proposed system incorporates an automatic temperature-sensing and heating mechanism that detects the beverage temperature and activates heating whenever it falls below a predefined reference temperature. The system aims to restore the beverage towards its initial temperature, providing a convenient and consistent drinking experience without requiring repeated manual heating.

The product design was registered under the name **SMART SELF-HEATING MUG**, Design No. 412581-001, with the registration dated 04 April 2024.

## 2. Embedded Control System

The entire system is controlled using an Arduino Nano microcontroller, which acts as the central processing unit. It receives temperature measurements from the temperature sensor and processes them to determine whether the beverage requires additional heating.

A predefined reference temperature is established based on the initial beverage temperature. Whenever the measured temperature falls below this reference value, the Arduino activates the heating mechanism through a relay module. Once the required temperature is restored, the controller switches off the heating mechanism.

This automatic feedback-based control approach eliminates the need for continuous user intervention and helps maintain the beverage at a desirable temperature.

## 3. Temperature Sensing and Display

A temperature sensor is integrated into the system to continuously monitor the beverage temperature. The measured temperature is supplied to the Arduino Nano, which processes the sensor readings and determines the appropriate heating response.

A seven-segment display is incorporated to provide real-time temperature information to the user. This allows users to monitor the beverage temperature conveniently and understand the current heating condition.

The temperature-monitoring functionality is central to the system because it enables intelligent heating based on actual beverage conditions rather than operating the heater continuously.

## 4. Heating Mechanism and Power Management

A Peltier module is employed as the primary thermal component, with a relay module controlling its operation based on the temperature feedback received by the microcontroller.

The system is designed around a 12 V DC power architecture with a maximum current rating of 6 A. A rechargeable 12 V, 6 A-rated battery with an integrated Battery Management System (BMS) provides portable power. An external power adapter and switch are also included in the design.

The power system is intended to provide a stable energy supply while maintaining compact dimensions, manageable weight, and portability.

## 5. Product Design and User Safety

The mechanical assembly incorporates a conducting tumbler and mug structure to facilitate thermal interaction between the heating arrangement and the beverage container. Particular attention is given to compactness, aesthetics, portability, affordability, and ease of handling.

An important design objective is to deactivate the heating mechanism while a person is drinking, improving the intended user experience and reducing unnecessary heating during consumption.

The system also aims to achieve a beverage temperature of approximately 80°C, subject to the beverage's initial temperature and operating conditions.

## 6. Applications and Future Scope

The Smart Self-Heating Mug combines embedded C programming, temperature sensing, relay-based switching, thermal control, and portable power management into a single consumer-oriented product.

Future enhancements could include wireless temperature monitoring, mobile application connectivity, rechargeable USB-C power, improved battery optimization, and more advanced temperature-control algorithms.

Overall, the project demonstrates the practical application of embedded systems and closed-loop temperature control in everyday consumer products. It provides an intelligent solution for maintaining beverage temperature while emphasizing portability, convenience, energy management, and user safety.
