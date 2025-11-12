✈️ Airline Operations Data Analysis

📄 Project Overview

This project analyzes airline passenger data to uncover factors affecting customer satisfaction. Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the dataset was cleaned, processed, and visualized to draw actionable insights for improving airline services and passenger experience.


🎯 Objectives

- Identify key factors influencing passenger satisfaction.
- Analyze the impact of arrival and departure delays on satisfaction levels.
- Examine how online services (Wi-Fi, online booking, and boarding) 
     affect traveller experience.
- Compare satisfaction patterns between Business and Personal travellers.
- Provide insights for improving airline service quality and customer retention.


🧰 Tools & Technologies

- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Dataset: Airline passenger satisfaction dataset (from Kaggle)


🧹 Data Cleaning & Preprocessing

- Removed unnecessary columns and null values.
- Converted data types for accurate analysis.
- Applied IQR method to remove outliers in delay-related features.
- Filtered out unrealistic entries (e.g., passengers below age 16).


📊 Exploratory Data Analysis (EDA)

Performed in-depth visual and statistical analysis to find:
- Arrival delay > 5 mins significantly decreases satisfaction.
- Departure delay has minimal effect on passenger experience.
- Personal travellers are more dissatisfied with missing or poor online
     booking and boarding services.
- Business class passengers frequently report missing in-flight Wi-Fi, 
     but it doesn’t affect their satisfaction as much.
- Online amenities like Wi-Fi and booking systems have low ratings 
     (2–3 out of 5) overall.


📈 Key Insights

Insight	Observation
🕐 Arrival Delay	 |   Delays over 5 minutes sharply reduce satisfaction
🌐 Wi-Fi Service	 |   Low-rated (2–3) or unavailable in many cases
💻 Online Booking	 |   Personal travellers show high dissatisfaction
🧾 Traveller Type	 |   Business travellers tolerate service issues better
🧍‍♀️ Age Filter	    |   Passengers under 16 excluded as unrealistic raters


📍 Conclusion

- Arrival delays are the strongest negative factor in customer satisfaction.
- Digital services (Wi-Fi, online booking/boarding) play a crucial role, 
     especially for personal travellers.
- Airlines should prioritize on-time arrivals and improve digital service 
     quality to enhance satisfaction and loyalty.
