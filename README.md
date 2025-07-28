Here’s a clean and complete `README.md` file for your **Device Info Collector Web App** project:

---

### ✅ `README.md`

````markdown
# Device Info Collector Web App

A Node.js web application that displays a user's screen resolution, IP address, current webpage URL, and geolocation in the browser. The app is served using Express and made publicly accessible using Ngrok.

## 🛠️ Technologies Used

- Node.js
- Express.js
- HTML & JavaScript
- Ngrok
- IPAPI (for IP-based geolocation)
- Concurrently (to run server + tunnel)

## 🚀 How to Run

1. Install dependencies:
   ```bash
   npm install
````

2. Start the app with Ngrok tunnel:

   ```bash
   npm start
   ```

3. Open the Ngrok public URL shown in the terminal.

## 📂 Project Structure

```
device-info-app/
├── index.js           # Express server
├── package.json       # Scripts and dependencies
└── public/
    └── index.html     # Frontend UI
```

## 🌍 Features

* Collects:

  * Screen resolution
  * Browser URL
  * User IP and location (via IPAPI)
  * Geolocation (with permission)
* Exposes local server via Ngrok

## 🔒 Privacy

No user data is stored. This app is for educational and demonstration purposes only.

## 📄 License

MIT License

```

---

Let me know if you'd like to include **screenshots** or **deployment instructions**!
```
