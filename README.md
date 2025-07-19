<h1>🌤️ Daily Weather Email Notification Workflow (n8n) </h1>
<h3>📌 Description </h3>
This workflow fetches the daily weather forecast for Ghar El Melh (Tunisia) every morning at 7:00 AM, formats it into a human-readable message, and automatically sends it to your Gmail inbox.

It's built with n8n, using:

Open-Meteo API for real-time weather data

A custom JavaScript Code node to process the forecast

Gmail integration to deliver the message

⚙️ Features
⏰ Scheduled to run every morning at 7:00 AM (or manually triggered)

🌡️ Extracts today's high and low temperatures from Open-Meteo

📬 Sends the report via Gmail with a clean summary

🔐 Built with privacy in mind (no third-party backend)
<img width="1269" height="606" alt="Capture d'écran 2025-07-19 020230" src="https://github.com/user-attachments/assets/54d31591-69a0-4348-a155-6e8e46430054" />
🧩 Nodes Used
<h4> Trigger: </h4> Manual + Cron (7 AM)

<h4> HTTP Request: </h4> https://api.open-meteo.com/v1/forecast?latitude=37.16&longitude=10.18&hourly=temperature_2m&timezone=GMT

<h4> Code: </h4> Extracts high and low temps for today from hourly data

<h4> Gmail: </h4> Sends the message to inbox

📧 Sample Output
📅 2025-07-19
In Ghar El Melh, the high today is 36.1°C and the low is 22.1°C.
<img width="1269" height="606" alt="Capture d'écran 2025-07-19 020230" src="https://github.com/user-attachments/assets/895456ab-ce5d-49e7-868f-65a05c520094" />

