# 🎮 Credit Card Checker – HackedDigits Edition 💳✨

**A lightweight, standalone tool to validate credit card numbers using the Luhn algorithm.**  
Detects invalid numbers and traces them back to their issuers – all in a simple, plug-and-play setup.  

## 🛠️ Features

- **Luhn Algorithm Validation** – Checks if a credit card number is legit.
- **Fraud Detection** – Identifies invalid credit cards in bulk.
- **Issuer Tracking** – Finds out which companies issued the faulty cards.
- **Minimal & Efficient** – No unnecessary complexity, just clean and functional code.

---

## 🚀 How It Works

1️⃣ **validateCred(arr)** – Validates a single credit card number.  
   - Input: An array of digits.  
   - Output: `true` (valid) / `false` (invalid).  

2️⃣ **findInvalidCards(cards)** – Scans multiple cards for invalid numbers.  
   - Input: A nested array of credit card numbers.  
   - Output: A nested array of invalid numbers.  

3️⃣ **idInvalidCardCompanies(invalidBatch)** – Identifies issuers of invalid cards.  
   - Input: A list of invalid card numbers.  
   - Output: A list of companies responsible.  

---

## 📌 Usage Example

```javascript
console.log(validateCred(valid1)); // true or false  
console.log(findInvalidCards(batch)); // Array of invalid card numbers  
console.log(idInvalidCardCompanies(findInvalidCards(batch))); // Array of companies  
