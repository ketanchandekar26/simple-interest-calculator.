# Simple Interest Calculator

A simple, lightweight calculator that computes simple interest based on the principal amount, annual interest rate, and time period.

## 📌 About

This project provides an easy way to calculate simple interest using the standard formula:

```
SI = (P × R × T) / 100
```

Where:
- **P** = Principal amount (initial investment/loan)
- **R** = Annual interest rate (in %)
- **T** = Time period (in years)

The **total amount** payable/receivable is calculated as:

```
A = P + SI
```

## ✨ Features

- 🔢 Calculate simple interest instantly
- 💰 Displays total amount (principal + interest)
- ✅ Input validation for positive numbers
- 📱 Responsive and clean UI
- 🧮 Supports decimal values for accuracy

## 🚀 Demo

```bash
# Example
Principal: ₹10,000
Rate: 5%
Time: 3 years

Simple Interest = (10000 × 5 × 3) / 100 = ₹1,500
Total Amount    = ₹11,500
```

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)

*(If you're using Python, replace the above with: Python 3 / Flask, etc.)*

## 📂 Project Structure

```
simple-interest-calculator/
│
├── index.html       # Main UI
├── style.css        # Styling
├── script.js        # Calculator logic
└── README.md        # Documentation
```

## ⚙️ Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/simple-interest-calculator.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd simple-interest-calculator
   ```

3. **Open `index.html` in your browser**

   Or serve it locally:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## 🧪 Test Cases

| Principal | Rate (%) | Time (yrs) | Simple Interest | Total Amount |
|-----------|----------|------------|-----------------|--------------|
| 1000      | 5        | 2          | 100             | 1100         |
| 5000      | 10       | 1          | 500             | 5500         |
| 10000     | 7.5      | 3          | 2250            | 12250        |

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@ketanchandekar26](https://github.com/ketanchandekar26)
- Email: ketanchandekar26@gmail.com

## 🙏 Acknowledgements

- Formula reference: [Simple Interest – Wikipedia](https://en.wikipedia.org/wiki/Interest#Simple_interest)
- Inspiration: Beginner-friendly finance tools

---

⭐ If you found this project helpful, please give it a star!
