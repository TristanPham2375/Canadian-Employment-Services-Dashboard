# 🇨🇦 Canada Employment & Essential Services Dashboard

This interactive Dash application visualizes employment statistics and essential services across Canadian provinces and territories. Developed as part of a data-driven education toolkit focused on the **UN Sustainable Development Goal: Zero Hunger**, this dashboard helps users critically analyze the distribution of key occupations and resources relevant to food security and sustainable development.

---

## 🔍 Project Overview

This project consists of **four separate Dash apps**, each focusing on a unique analytical question. All visualizations are based on real Canadian census and labor data, supporting data-driven decision-making and learning.

The four key tasks are:

1. **Essential Services Choropleth Map**
2. **Gender Distribution by Occupation**
3. **EV Production Manpower by Engineering Field**
4. **Natural Science Graduate Composition**

Each Dash app runs independently and provides interactive features such as dropdown filters and dynamic charts.

---

## 📊 Features

### 1. **Task 1: Essential Services Choropleth**
Visualizes the ratio of Nurses, Police, Firefighters, and Total essential workers to population by province.

![Dashboard_1](https://github.com/user-attachments/assets/bd8cbcd3-d135-47eb-97ec-74841b697b08)
- **Type**: Choropleth Map
- **Interaction**: Dropdown to select service type
- **Tool**: `plotly.express.choropleth`

### 2. **Task 2: Gender Distribution by Occupation**
Displays a grouped bar chart comparing male and female representation across various occupations for each province/territory.

![Dashboard_2](https://github.com/user-attachments/assets/f7d90384-e1c6-4cc5-817b-d912dab5c14f)
- **Type**: Grouped Bar Chart
- **Interaction**: Dropdown to select province
- **Tool**: `plotly.express.bar`

### 3. **Task 3: EV Manpower by Engineering Discipline**
Analyzes the availability of Computer, Electrical, and Mechanical engineers in each province—relevant to EV industry growth.

![Dashboard_3](https://github.com/user-attachments/assets/f771422f-94d0-4140-84e8-ed17fea234b7)
- **Type**: Bar Chart
- **Interaction**: Dropdown to select province
- **Tool**: `plotly.express.bar`

### 4. **Task 4: Natural Science Graduates**
Displays the distribution of graduates in Physics, Biology, Geography, and Math by gender and province.

![Dashboard_4](https://github.com/user-attachments/assets/6ac4aa42-6105-42ff-a1d8-20e4745bb35f)
- **Type**: Stacked Bar Chart
- **Interaction**: Dropdown to filter by gender
- **Tool**: `plotly.express.bar`

---

## 🛠️ Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/your-username/canada-dash-employment.git
   cd canada-dash-employment

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

