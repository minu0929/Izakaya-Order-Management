# Izakaya Order Management System 🍺

## 1. Overview
This project stems from my real-world experience working part-time as a server at an Izakaya. During rush hours, when orders flooded in simultaneously, it was instantly challenging to prioritize which beverages should be served first. To solve this bottleneck, I implemented a Python-based system that **automatically sorts the beverage serving sequence based on preparation difficulty**.

## 2. Key Features
- **Order Input & Quantity Management**
- **Beverage Prioritization (Sorted by Preparation Difficulty):**
  - **1st Priority:** Fruit Soju (Ready to serve immediately)
  - **2nd Priority:** Draft Beer (Requires pouring from the tap)
  - **3rd Priority:** Highball (Requires mixing/preparation)
  - **4th Priority:** Makgeolli (Complex preparation and handling)
- **Appetizers/Food:** Processed and output strictly in chronological order of receipt (Handled by the kitchen team).

## 3. Usage
To run the system, execute the following command in your terminal:
```bash
python order.py
