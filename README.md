# HW-survivor-rubber-hackathon

## Description
This project is a Line Chat Bot utilizing the Line Messaging API. The bot retrieves the user's location and provides weather information for their area while predicting the latex (rubber) yield. The bot is designed to assist users with real-time updates and useful predictions.

## Features
- Retrieves user location via Line Messaging API.
- Fetches weather data based on the user's location.
- Predicts latex yield and displays results to the user.

---

## Installation Guide

### Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (version 14.x or later)
- npm (comes with Node.js)

### Steps to Install

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kfirm1208/HW-survivor-rubber-hackathon.git
   cd HW-survivor-rubber-hackathon
   ```

2. **Install dependencies:**
   Run the following command to install required libraries:
   ```bash
   npm install
   ```

3. **Libraries Used:**
   - [linechat-bot](https://www.npmjs.com/package/linechat-bot): For Line Messaging API integration.
   - [axios](https://www.npmjs.com/package/axios): To handle HTTP requests for fetching weather data.
   - [express](https://www.npmjs.com/package/express): To create a server for the bot.
   - [dotenv](https://www.npmjs.com/package/dotenv): For managing environment variables securely.

4. **Configure environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   LINE_CHANNEL_ACCESS_TOKEN=<Your Line Channel Access Token>
   LINE_CHANNEL_SECRET=<Your Line Channel Secret>
   WEATHER_API_KEY=<Your Weather API Key>
   ```

5. **Start the server:**
   Run the following command to start the bot:
   ```bash
   node index.js
   ```

6. **Deploy the bot:**
   Use [ngrok](https://ngrok.com/) or similar tools to expose your local server to the internet and set the webhook URL in the Line Developer Console.

---

## Usage
- Add the bot to your Line application using the QR code or Line ID.
- Share your location via the chat interface.
- Receive weather information and latex yield predictions instantly.

---

## Contributing
Feel free to open issues or create pull requests if you'd like to contribute to this project.

---
