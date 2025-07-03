# STM32-ESP32-MQTT-Controlled-Trigger-and-Alarm-System

# Description

# Software Architecture

# Components Used

STM32F0DISC

ESP32 WROOM 32D

Sound Sensor

PIR Sensor

Active Buzzer

Jumper Cables

# Pin Configuration

Figure 3 : Pin Configuration on the STM32CubeIDE

<img src="https://github.com/ssenanb/STM32-ESP32-MQTT-Controlled-Trigger-and-Alarm-System/blob/main/configuration.png" alt="System Configuration" width="500"/>

PA0 -> GPIO_EXTI0 -> Sound Sensor

PA1 -> GPIO_EXTI1 -> PIR Sensor

PA9 -> USART1_TX (with Interrupt)

PA10 -> USART1_RX (with Interrupt)

PC9 -> GPIO_Output -> Active Buzzer

