# 🏨 Data Analysis for Hotel Booking  

🚀 **By Mulkesh Sharma**  

This project analyzes hotel booking data to **find relationships between bookings, cancellations, and other factors**. Using **data visualization and statistical analysis**, we uncover key trends that affect hotel reservations. 📊📉  

## 📌 Objective  
- Understand **booking trends** and **cancellation patterns**.  
- Find insights on **customer behavior** and seasonal demand.  
- Identify factors affecting **hotel occupancy rates**.  

## 🔧 Technologies Used  
- 🐍 **Python**  
- 📊 **NumPy** – Numerical data operations  
- 🏷️ **Pandas** – Data manipulation and analysis  
- 🎨 **Seaborn** – Statistical data visualization  
- 📉 **Matplotlib** – Graph plotting  

## 📂 Dataset  
The dataset includes details like:  
- **Booking dates, customer types, room preferences**  
- **Cancellation status, lead time, special requests**  
- **Market segments, pricing trends, and more!**  

## 🔍 Exploratory Data Analysis (EDA)  
- ✅ **Checking missing values** and cleaning data  
- ✅ **Analyzing booking trends** across seasons  
- ✅ **Finding correlation between cancellations & other factors**  
- ✅ **Visualizing occupancy rates & revenue patterns**  

## 📊 Sample Code  
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("hotel_booking_data.csv")

# Display first 5 rows
print(df.head())

# Visualizing cancellations vs. bookings
sns.countplot(x=df["is_canceled"])
plt.title("Booking vs. Cancellations")
plt.show()
```

## 🎯 Key Insights  
- 📅 **Seasonal impact on bookings** (peak & off-seasons).  
- 💰 **Pricing trends & revenue analysis**.  
- 📌 **Customer preferences & behavior patterns**.  
- ❌ **Common reasons for cancellations**.  

## 💡 How to Use  
1. Clone the repository:  
   ```sh
   git clone <your-repo-url>
   cd Hotel_Booking_Analysis
   ```  
2. Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```  
3. Run the Jupyter Notebook:  
   ```sh
   jupyter notebook
   ```  

## 👨‍💻 Author  
### **Mulkesh Sharma**  

---
