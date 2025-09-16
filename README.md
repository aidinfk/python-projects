# ☕ Coffee Machine Application

A console-based coffee machine simulator built with **Python 3.11**.

---

## 📌 Project Overview
This application simulates a coffee machine that allows users to:
- Order **Latte**, **Espresso**, or **Cappuccino**  
- Pay using virtual coins (quarters, dimes, nickels, pennies)  
- Receive change when applicable  
- Automatically update available ingredients after each transaction  

---

## 🚀 Main Features
- Three available drinks: `latte`, `espresso`, `cappuccino`  
- **Payment system** with coin input & automatic change calculation  
- **Resource tracking** for water, milk, coffee, and money collected  
- **Manager commands**:
  - `off` → turns off the machine  
  - `report` → prints current resources and profit report  

**Sample Report Output**:
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5


---

## ⚙️ Classes & Workflow
The project is structured into **three classes**:

1. `Menu` – handles the drink options and menu display  
2. `CoffeeMaker` – manages ingredients and coffee preparation  
3. `MoneyMachine` – handles payments, change, and transactions  

**Workflow**:
1. User is asked: *“What would you like? (latte/espresso/cappuccino)”*  
2. App checks ingredient availability  
3. User deposits coins  
4. App verifies sufficient funds & resources  
5. Coffee is dispensed ☕ → *“Enjoy your drink!”*  

---

## 🖥️ Usage & Requirements
- Written in **Python 3.11**  
- No external libraries required  
- Runs directly in the Python console  

---

## ▶️ Getting Started
Clone this repository and open it in your IDE:

```bash
git clone git@github.com:your-username/coffee-machine.git
cd coffee-machine

Run the application in your Python console:
python main.py

