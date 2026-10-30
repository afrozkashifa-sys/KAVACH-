# KAVACH: Low-Cost Mine Subsidence Monitoring System

Team Neural Nomads | hackFront India, Open Source & Innovation

KAVACH is a low-cost IoT and AI based system for early warning of ground subsidence in underground coal mines. Solar-powered ESP32 sensor nodes measure tilt, vibration, displacement and cracks, send data over LoRa and ESP-NOW to a gateway with SD card logging, and a live dashboard shows risk using a rate-of-change model.

## Problem
Mine safety officers and communities near underground coal mines face the risk of sudden ground subsidence. Monitoring today relies on periodic surveys, so rapid ground change at a specific site may not be seen quickly.

## What works today
- ESP32 sensor nodes (tilt, vibration, displacement, crack sensor)
- Node to Gateway LoRa link
- ESP-NOW node communication
- SD card data logging at the gateway
- AI risk model (rate-of-change based)
- Real-time dashboard with Firebase

## In progress / not done yet
- SIM800L GSM SMS alerts: not yet tested end-to-end on hardware
- Physical mine model
- Field testing and calibration

## Tech stack
ESP32, MPU6050, SW-420, VL53L0X, copper-tape crack sensor, SX1278 LoRa, SD card module, SIM800L, React + Vite + TypeScript, Firebase Realtime Database.

## Run the dashboard
1. Install Node.js
2. `npm install`
3. Copy `.env.example` to `.env` and fill in your Firebase values
4. `npm run dev`
5. Open http://localhost:3000

## Team
Neural Nomads. Team lead: Kashifa Afroz
