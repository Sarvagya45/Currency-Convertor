# Currency-Convertor
# 🌍 Currency Converter Web App

A responsive, real-time **Currency Converter** web application built using **HTML, CSS, and JavaScript**. It fetches live currency exchange rates via the [Fawaz Ahmed Currency API](https://github.com/fawazahmed0/currency-api) and dynamically updates conversion results based on user input.

## 🔧 Features

- 🔁 Convert between **multiple international currencies**
- 🌐 Uses a **public API** for real-time exchange rates
- 🎌 Displays **national flags** alongside currency codes
- ⚡ Instant feedback with DOM updates (no page reload)
- 💡 Default conversion from USD to INR
- 📱 Responsive and mobile-friendly layout

## 🚀 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **APIs**:
  - [Fawaz Ahmed Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api)
  - [Flags API](https://flagsapi.com)

## 📁 Project Structure
├── index.html # Main HTML structure
├── style.css # Styles and layout
├── app.js # Core logic for conversion and event handling
├── codes.js # Currency to country code mapping

## 🖼️ Demo UI

> User enters an amount and selects currencies to convert. Flags are auto-updated. Clicking "Get Exchange Rate" shows the latest rate instantly.

## ⚙️ How It Works

1. On page load, currency dropdowns are dynamically populated using a predefined list (`codes.js`).
2. Users can select currencies and enter an amount.
3. On clicking the button, `fetch()` retrieves the latest exchange rate.
4. The result is displayed dynamically without page refresh.

## 🛠️ Setup Instructions

1. Clone the repository  
   ```bash
   git clone https://github.com/Sarvagya45/currency-converter.git
2. Open index.html in your browser
That’s it! No build tools required

📚 Future Enhancements
Add currency chart history

Add dark/light theme switcher

Option to favorite/save frequent conversions

👨‍💻 Author
Your Name –Sarvagya45
