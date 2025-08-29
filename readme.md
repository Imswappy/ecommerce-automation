# 🛒 E-Commerce Website Automation (Selenium + Python)

## 📌 Overview
This project is an **end-to-end automation script** for an e-commerce demo website built using **Selenium WebDriver with Python**.  
The script simulates a **real customer journey** on [TutorialsNinja E-commerce Demo](http://tutorialsninja.com/demo/):

- Browsing product categories (Phones, Laptops & Notebooks)  
- Viewing product images and saving screenshots  
- Adding multiple products to the cart  
- Filling checkout form as a **guest user**  
- Completing the checkout process  
- Printing the final order price and success message  

This project is based on the tutorial: *E-Commerce Website Automation with Selenium + Python*.  

---

## 🛠️ Tech Stack
- **Python 3.x**  
- **Selenium WebDriver**  
- **Google Chrome** + **ChromeDriver**  
- **ActionChains & Select** (Selenium APIs for advanced interactions)  

---

## 📂 Project Structure
```
ECOMMERCE-AUTOMATION/
│
├── automate.py     # Main automation script
├── screenshots/        # Folder to save captured screenshots
└── README.md
```

---

## 🚀 Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Ecom-Automation.git
cd Ecom-Automation
```

### 2️⃣ Install Selenium
```
```
### 3️⃣ Download ChromeDriver
- Download the correct version of **ChromeDriver** matching your Google Chrome browser:  
  👉 https://chromedriver.chromium.org/downloads  
- Place it in a folder (e.g., `C:/bin/chromedriver.exe`) and update the script path accordingly.

---

## ▶️ Run the Script
```bash
python automate.py
```

---

## 📸 Features Demonstrated
- Open website and maximize window  
- Navigate through categories (Phones, Laptops & Notebooks)  
- Open product details and browse images  
- Capture and save **randomized screenshots**  
- Add products with custom **quantity selection**  
- Select delivery date using **calendar widget**  
- Add products to cart and proceed to checkout  
- Enter guest details (name, email, address, etc.)  
- Agree to terms and confirm order  
- Print **final price** and **order success message**  

![alt text](ecom_1.PNG) ![alt text](ecom_2.PNG) ![alt text](ecom_3.PNG)
---

## 🧾 Example Output
```
The final price of both products is $241.00
Your order has been placed!
```

---

## 📌 Notes
- This script is designed for **educational/demo purposes** on the [TutorialsNinja](http://tutorialsninja.com/demo/) site.  
- The website and data reset periodically, so values (like product availability or prices) may vary.  
- Screenshots are saved in the working directory by default.  

---

