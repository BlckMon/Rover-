# Rover-
Autonomous Rover Project
The Autonomous Rover is a modular, sensor‑driven robotic platform built on an ESP32 microcontroller. It combines motor control, obstacle detection, environmental sensing, and onboard navigation logic into a compact rover capable of autonomous movement and real‑time decision‑making.

This repository contains the firmware, wiring documentation, navigation logic, and system architecture for the rover.
🚀 Features
ESP32‑based control system

Dual‑core processing

Wi‑Fi for telemetry

Real‑time sensor polling

Motor & Movement System

Dual DC motors

L298N or TB6612 motor driver

PWM speed control

Directional steering logic

Sensor Suite

Ultrasonic sensor for obstacle detection

Infrared sensors for edge detection (optional)

Environmental sensors (BMP280, BME280, MQ gas sensor)

IMU (optional) for orientation

Navigation Logic

Obstacle avoidance

Forward/turn decision tree

Speed modulation

Fail‑safe stop conditions

Power System

2‑cell Li‑ion or LiPo battery

5V buck converter

Motor driver power isolation

Modular Firmware

Separate drivers for motors, sensors, navigation

Clean, expandable architecture

Debug logging over Serial/Wi‑Fi

📁 Project Structure
/src
  main.cpp
  motors.cpp
  navigation.cpp
  ultrasonic.cpp
  env_sensors.cpp
  mq_sensor.cpp

/include
  motors.h
  navigation.h
  ultrasonic.h
  env_sensors.h
  mq_sensor.h

/docs
  wiring_diagram.png
  power_distribution.png
  rover_architecture.png

platformio.ini
README.md

