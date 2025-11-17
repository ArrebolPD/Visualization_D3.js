## 📊 Visualization_D3.js

This repository contains various **interactive data visualizations** created using the powerful JavaScript library **D3.js (Data-Driven Documents)**. The project focuses on visualizing **sales data** to provide insights into performance, trends, and patterns.

### 🌟 Project Overview

This project serves as a showcase of utilizing D3.js to transform raw sales data into compelling and easy-to-understand visual stories. It demonstrates various common visualization types essential for business analytics.

### ✨ Key Features

* **Interactive Charts:** All visualizations are highly interactive, allowing users to hover, zoom, and filter data points for deeper exploration.
* **Diverse Visualization Types:** The project implements a wide range of chart types crucial for sales and business analytics:
    * **Bar Charts (Horizontal & Vertical):** Used extensively for comparing metrics, such as:
        * Sales Revenue by **Individual Item**.
        * Sales Revenue by **Product Group**.
        * Total Sales Revenue by **Month**.
        * Average Sales Revenue by **Day of the Week** and **Day of the Month**.
        * Average Sales Revenue by **Time Slot (Hourly)**.
    * **Distribution/Frequency Histograms:** Used to illustrate how data points are spread, specifically:
        * Distribution of **Customer Purchase Count**.
        * Distribution of **Customer Spending Brackets**.
    * **Line Charts:** Used for tracking **trends and changes over time**, specifically to show the **Sales Probability** of different product groups and items across the months of the year.
    * **Probability Bar Charts:** Used to display the **Sales Probability** (or conversion rate) of different **Product Groups** and **Items** within those groups.

* **Data-Driven:** All visual elements are dynamically bound to the underlying sales dataset.
* **Responsive Design:** Visualizations are designed to adapt to different screen sizes.

### 🛠️ Technologies Used

* **D3.js (vX.x.x):** The core library for data manipulation and visualization rendering.
* **HTML5/CSS3:** For structure and styling.
* **JavaScript (ES6+):** For interactivity and logic.

### 🚀 Getting Started

To view and run the visualizations locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ArrebolPD/Visualization_D3.js.git](https://github.com/ArrebolPD/Visualization_D3.js.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Visualization_D3.js
    ```
3.  **Run with a Local Server:** Simply opening the HTML files directly may cause issues due to D3.js security policies and data loading. It is highly recommended to run this project through a local server (e.g., using the **Live Server** extension in VS Code, or a simple Python HTTP server: `python -m http.server`).

### 📂 Repository Structure

The visualizations are organized into individual JavaScript files (Q1 through Q12) corresponding to specific analysis questions:
```
Visualization_D3.js/
├── data             # Main data source file 
├── index.html       # The main entry file to view or navigate the visualizations
├── style.css        # CSS file for styling
├── Q1.js            # Visualization for Sales Revenue by Item
├── Q2.js            # Visualization for Sales Revenue by Product Group
├── Q3.js            # Visualization for Monthly Sales Revenue
├── Q4.js            # Visualization for Average Daily Sales (Weekly)
├── Q5.js            # Visualization for Average Daily Sales (Monthly)
├── Q6.js            # Visualization for Average Sales Revenue by Time Slot
├── Q7.js            # Visualization for Sales Probability by Product Group
├── Q8.js            # Visualization for Sales Probability of Item by Group
├── Q9.js            # Visualization for Monthly Sales Probability by Product Group
├── Q10.js           # Visualization for Monthly Sales Probability of Item by Group
├── Q11.js           # Visualization for Distribution of Purchase Count
└── Q12.js           # Visualization for Distribution of Customer Spending
```
### 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ArrebolPD/Visualization_D3.js/issues) or submit a pull request.

### 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

### 📬 Contact

Project Link: [https://github.com/ArrebolPD/Visualization_D3.js](https://github.com/ArrebolPD/Visualization_D3.js)
