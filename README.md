SecureHome is a mobile-based home security application designed to monitor security events and notify users instantly through SMS alerts.
The application focuses on reliable alert delivery, clear system status visualization, and simulation of real-world security scenarios.

This project demonstrates application-level system design, alert handling logic, and user-centric security monitoring.

Application Overview

Runs as a mobile application

Designed for real-time security awareness

Uses SMS notifications to alert users about critical events

Includes a simulation environment to test different security scenarios

Key Features
Authentication

Secure login interface

Demo credentials for quick access

Password visibility toggle for usability

Home Dashboard (Control Hub)

System state: Armed / Disarmed

Overview of active sensors and cameras

Quick-action buttons (Lock system, 3D View)

Activity feed with severity levels

Camera Monitoring

Multi-camera tile layout

Camera online/offline status

Live activity indicators

AI detection labels (simulated)

Sensor Monitoring

Motion, door, window, and glass-break sensors

Battery level indicators

Room-wise sensor grouping

Real-time alert banner

Alert & SMS Notification System (Core Feature)

Detects critical security events

Displays alerts inside the app

Sends SMS notifications to the user for high-priority events

Ensures alerts are received even when the app is not active

3D Security Visualization

Visual representation of the house layout

Highlights breached areas

Helps users quickly understand intrusion location

Simulation Center

Full home intrusion simulation

Fire and environmental hazard scenarios

Network failure and recovery simulation

Power failure and battery backup behavior

SMS Alert Flow

Security event is triggered (e.g., door breach)

Event severity is evaluated

Alert is displayed within the application

SMS notification is sent to the registered mobile number

User receives real-time security information

SMS alerts improve reliability during poor internet connectivity or when the app is closed.

Technology Stack

Platform: Mobile Application (mention Flutter / Android / React Native)

Alert System: SMS-based notification

UI: Custom-designed mobile UI

Architecture: Event-driven alert handling

Simulation: Scenario-based state management

Use Cases

Mobile home security monitoring

Alert-based safety applications

Security system simulation and testing

Academic and portfolio demonstration
