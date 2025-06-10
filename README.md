
# 🚗 CarDetect – Smart Vehicle Number Lookup Bot

**CarDetect** is an AI-ready tool that allows users to enter an Indian vehicle registration number and instantly fetch car details like make, model, fuel type, registration location, and more using a live number plate API.

> “Enter the number, get the car’s story.” – Powered by Marko AI

---

## 📱 Demo

![CarDetect Logo](./assets/CarDetect.png)

---

## 🔥 Features

- 🔍 Input Indian vehicle number (e.g., `HP33AB1234`)
- 🚘 View full vehicle info: make, model, fuel type, RTO, year
- 📡 Connected to live vehicle lookup APIs
- 🧠 Optional chatbot integration with GPT
- ⚙️ Scalable architecture for Android/Web
- 🎨 Clean UI with AI branding (`Marko`-powered)

---

## 🛠️ Tech Stack

| Layer        | Technology        |
|--------------|-------------------|
| Frontend     | Android (Java/Kotlin), Flutter, or Web (React.js) |
| Backend (opt)| Node.js or Flask |
| API          | mParivahan / RegCheck / RapidAPI vehicle lookup |
| AI (opt)     | GPT integration for chatbot-style replies |
| Logo & UI    | Designed with Canva + Figma |

---

## 📦 Folder Structure

```
CarDetect/
├── assets/
├── screens/
├── api/
├── components/
├── utils/
└── main.dart / MainActivity.java
```

---

## 📡 Sample API Usage

```http
GET https://api.regcheck.org.uk/api/reg.asmx/CheckIndia?RegistrationNumber=HP33AB1234&username=demo
```

### 🧪 Sample JSON Response:

```json
{
  "Description": "Maruti Suzuki Swift VXI",
  "RegistrationYear": "2017",
  "Location": "Mandi, Himachal Pradesh",
  "FuelType": "Petrol",
  "EngineSize": "1197 cc",
  "RegistrationNumber": "HP33AB1234"
}
```

---

## ✅ Example Usage in CarDetect App

### ▶️ Input:
```
Vehicle Number: HP33AB1234
```

### 🖥️ Output:
```
✅ Vehicle Found!
🧾 Model: Maruti Suzuki Swift VXI
🛢️ Fuel: Petrol
📅 Year: 2017
📍 Registered at: Mandi, Himachal Pradesh
🔢 Engine: 1197 cc
```

Or optionally:

> **Marko AI Says:**  
> “This is a 2017 Petrol Maruti Swift, registered in Mandi, HP. A very common family car in India.”

---

## 🚀 Getting Started

### Step 1: Clone the Project
```bash
git clone https://github.com/your-username/CarDetect.git
cd CarDetect
```

### Step 2: Configure API
Create `.env` file:
```
API_KEY=your_api_key
```

### Step 3: Run the App
- Android: Open in Android Studio → Build & Run
- React: `npm install` → `npm start`

---

## 👨‍💻 Author

**Ishan Walia**  
GitHub: [@ishanwalia7579](https://github.com/ishanwalia7579)

---

## 📄 License

MIT License

---

## 🌟 Show Support

If you find this project helpful, don’t forget to **star** ⭐ it on GitHub and share with friends!
