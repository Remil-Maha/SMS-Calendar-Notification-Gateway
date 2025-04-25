# 📲 SMS Calendar Notification Gateway

> An IoT-based SMS alert system integrated with Google Calendar, developed as a team project by 6 students.

## 📍 Location
Algiers, Algeria  
🕒 Completed in March 2025

---

## 👥 Team

This project was developed as part of a collaborative effort by a team of **six computer science students**. The system design, development, testing, and deployment were divided among team members to ensure modular and efficient development.

---

## 🛠️ Technologies Used

- Python
- Raspberry Pi OS
- Google Calendar API
- RaspiSMS
- GSM Module (e.g., SIM800L)
- Flask

---

## ⚙️ Main Features

- Real-time calendar event monitoring using the Google Calendar API
- Classification of event urgency based on keywords.
- Automated SMS notifications sent via GSM module using RaspiSMS
- Designed to run continuously  .
- Using DHT22 sensor .
- Developping real time dashboard visualisation.
- Sending data to AZURE Iot Hub.

---

## 🖼️ System Architecture (Diagram available upon request)

1. Raspberry Pi fetches and evaluates upcoming events
2. If an urgent event is detected, RaspiSMS triggers an SMS alert via the GSM module
![image](https://github.com/user-attachments/assets/666630d1-d527-4d3c-b30a-004d8ffabd90)

---

## 🚀 Deployment Steps

1. Set up RaspiSMS on Raspberry Pi and test GSM module
2. Configure OAuth 2.0 credentials for Google Calendar API access
3. Run the Python script  for event tracking
4. Automate script execution with systemd

---

## 💡 Use Case Example

> “Send an SMS to ESI student about urgent calendar event like : exam , controle intermidaire ... as reminder .”

---  
