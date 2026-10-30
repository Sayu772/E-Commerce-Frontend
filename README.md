# E-Commerce-Frontend
A modern organic grocery e-commerce frontend layout built with HTML5, CSS3, and JavaScript, featuring a live currency converter using a dynamic exchange rate API.
# FreshCart | Organic Produce E-Commerce Frontend Layout

A modern, minimalist frontend layout developed for an organic grocery store. This project features clean structure, responsive typography, and an interactive **Live Currency Converter** that communicates with a third-party exchange rate API.

## 🚀 Features

- **Dynamic Navigation Bar:** Clean header design structured for seamless user experience.
- **Unified Currency Converter:** Reusable JavaScript logic (`convertCurrency`) that fetches dynamic exchange rates instantly using `async/await` and `fetch` API.
- **Modern UI Cards:** Organized grid/flex layout with automated image scaling using CSS `object-fit`.
- **Typographic System:** Styled using modern web fonts for an enhanced professional appearance.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Flexbox, Grid)
- **Scripting:** JavaScript (ES6+, Async/Await, Fetch API)
- **API Integration:** Fawaz Ahmed's Open-Source Currency API (`@fawazahmed0/currency-api`)

## 📂 Project Structure

```text
├── index.html       # Semantic web layout and UI components
├── style.css        # Responsive styling and card layouts
└── script.js        # Dynamic API logic and UI data updates
```

## 💡 Key Architectural Concepts

Instead of using repetitive code blocks for separate components, this layout implements an architecture based on **code reusability**. The main JavaScript utility takes a unique identifier (`cardId`) as a generic parameter, managing data processing and UI rendering workflows for multiple product modules through a single logic wrapper.

## ⚙️ Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Open `index.html` directly in any standard browser to view the application.
