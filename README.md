# Selenium WebDriver & Java Interview Assignment

## 📅 Objective:
Create an automation framework using **Selenium WebDriver** and **Java** to test a basic e-commerce website such as [https://automationexercise.com/](https://automationexercise.com/) or any other demo site.

---

## 📌 Assignment Tasks

### 🔹 1. Java Concepts Demonstration
Create a Java class demonstrating:

- **OOPs Concepts**:
  - **Inheritance**: BaseTest class, BrowserSetup, etc.
  - **Encapsulation**: Getters/Setters for Page elements
  - **Polymorphism**: Method Overloading for login methods
  - **Abstraction**: Interface for common Page actions

### 🔹 2. Selenium Test Scenarios
Automate the following test cases:

#### ✅ Test Case 1: User Login
- Navigate to the site
- Click on Login
- Enter username and password
- Assert successful login (e.g., "Logged in as [name]")

#### ✅ Test Case 2: Product Search and Add to Cart
- Search for a product (e.g., "T-shirt")
- Click a product and add it to the cart
- Navigate to cart and assert the product is added

#### ✅ Test Case 3: Checkout Process
- Proceed to checkout
- Fill in dummy user details
- Assert the order is placed or simulated

---

## 🔧 Requirements
- Use **TestNG** as test framework
- Apply **Page Object Model (POM)**
- Use **WebDriverManager** for browser driver setup
- Implement **Assertions** to validate outcomes
- Add logging using **Log4j** or `System.out.println`

---

## 💡 Bonus (Optional)
- Implement **Data-Driven Testing** using Excel/CSV/JSON
- Add **Retry Mechanism** for failed tests
- Generate test reports using **Extent Reports** or **Allure Reports**

---

## 📂 Suggested Project Structure

```
src/
├── base/
│   └── BaseTest.java
├── pages/
│   ├── LoginPage.java
│   ├── ProductPage.java
│   └── CheckoutPage.java
├── tests/
│   └── ECommerceTest.java
└── utils/
    └── TestDataUtil.java
```

---

## 📢 Notes
- Keep your code modular and reusable
- Focus on clean, readable code with comments
- This assignment is meant to showcase your understanding of both **Java** and **Selenium** in an interview setting


