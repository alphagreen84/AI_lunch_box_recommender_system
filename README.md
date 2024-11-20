# **AI-based Lunch Box Planner**
Scrapes data from the ICA website, fetches weekly offers, and uses OpenAI to create a shopping list! The shopping list can be sent via SMS using Twilio.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## **Table of Contents**
1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)

---

## **About the Project**
This project helps you plan your weekly shopping:
- 🛒 **Data Scraping**: Scrapes weekly offers from the ICA website using `Selenium` and `BeautifulSoup`.
- 🧠 **AI Integration**: Uses OpenAI's API to generate a tailored shopping list based on the scraped offers.
- 📩 **Notifications**: Sends the shopping list via SMS using `Twilio`.

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following installed:
- Python 3.10 or later
- `pip` for package management

### **Installation**
Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alphagreen84/AI_lunch_box_recommender_system.git
