# **AI-based Lunch Box Planner**

An intelligent tool to plan your weekly shopping by scraping ICA's website for weekly offers, generating a shopping list with OpenAI, and sending it via SMS using Twilio.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## **Table of Contents**

1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)

---

## **About the Project**

The AI-based Lunch Box Planner simplifies weekly shopping by automating key tasks:
- 🛒 Scrapes the ICA website for weekly offers using `Selenium` and `BeautifulSoup`.
- 🧠 Uses OpenAI's API to generate a tailored shopping list based on available offers.
- 📩 Sends the final shopping list via SMS using Twilio.

---

## **Getting Started**

Follow these instructions to get a copy of the project up and running.

### **Prerequisites**

You will need:
- Python 3.10 or later
- `pip` to manage Python packages

### **Installation**

To set up the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/alphagreen84/AI_lunch_box_recommender_system.git

# Navigate to the project directory
cd AI_lunch_box_recommender_system

# Install dependencies
pip install -r requirements.txt
