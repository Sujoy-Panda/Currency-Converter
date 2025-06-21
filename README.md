# 💱 Currency Converter

A **simple and elegant web-based currency converter** built using **HTML**, **JavaScript**, and **Tailwind CSS**. Perfect for demonstrations, learning, or basic conversion tasks.

---

## 🌟 Features

* 🔄 Instantly convert between **USD**, **EUR**, **GBP**, and **JPY**
* 💻 **Clean, responsive UI** designed with Tailwind CSS
* 🧮 Uses **fixed exchange rates** (for demo purposes)
* ⚡ No external dependencies – just open and use!

---

## 🚀 Usage

1. **Clone or download** the project.
2. Open `index.html` in your web browser.
3. Enter the **amount** you want to convert.
4. Choose the **source** and **target** currencies.
5. Click **Convert** to see the result instantly.

---

## 💹 Exchange Rates

> All conversions use the following static rates (relative to USD):

| Currency | Rate   |
| -------- | ------ |
| USD      | 1.00   |
| EUR      | 0.92   |
| GBP      | 0.78   |
| JPY      | 150.25 |

> You can change these anytime for customization.

---

## ⚙️ Customization

To **modify exchange rates** or **add more currencies**:

* Open `index.html`
* Locate the `exchangeRates` object
* Update the values or add new key-value pairs

```javascript
const exchangeRates = {
  USD: 1,
  EUR: 0.92,
  GBP: 0.78,
  JPY: 150.25
};
```

---

## ✅ Requirements

* ✅ A modern web browser (Chrome, Firefox, Edge, etc.)
* ✅ No installation or build tools required

---

## 📄 License

This project is intended for **educational and demonstration purposes only**.
No specific license has been applied.

---

## 🙌 Acknowledgments

Built with ❤️ using:

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Tailwind CSS](https://tailwindcss.com/)
