# Mid Project - Data Engineering & Cloud Course - Naya College
## Rainfall Analysis Project
### By: Niv Levi
### Lecturer: Mr. Lev Epstein
This project analyzes rainfall patterns using weather data from Australia, recorded daily between 2008 and 2017. The data includes observations like temperature, humidity, wind speed, and rainfall from various locations. The main goal was to find patterns that help predict if it will rain on the same day.

The project involved cleaning the data, fixing missing values, and converting information into usable formats. Visualizations were created to explore rainfall trends across regions and seasons. Key findings showed that humidity, especially at 9 am, is the most important factor in predicting rain.

Feature importance analysis ranked the top 20 variables influencing rainfall predictions. The highest-ranked features were Humidity9am (18.4%) and Humidity3pm (8.9%), indicating that moisture levels in the air have the strongest correlation with rainfall. Other factors like minimum temperature, pressure, and wind gust speed also play significant roles.

Interestingly, cloud cover features ranked lower, contributing about 2.4% each. This suggests that while clouds are visually associated with rain, they are less reliable predictors compared to humidity or temperature.

These insights can help improve planning in agriculture, water use, and city management by focusing on the most impactful weather features for rainfall prediction.

---

## **Steps to Run the Notebook**

### **1. Prerequisites**

Make sure you have:

- **Docker**: [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: [Install Docker Compose](https://docs.docker.com/compose/install/)

---

### **2. Clone the Repository**

Download the project files to your local machine:

```bash
git clone https://github.com/nivlevi1/Rain-Prediction-Analysis
cd Mid_Project_Naya_DE/
```

---

### **3. Start the Notebook**

Run the following command to start the Jupyter Notebook:

```bash
docker-compose up
```

Once it starts, you'll see a message with the link to access the notebook, like:

```
http://127.0.0.1:8888/?token=Naya
```

---

### **4. Open the Notebook**

1. Open your browser and go to:
   ```
   http://localhost:8888
   ```
2. Enter the token:
   ```
   Naya
   ```

---

### **5. Stop the Notebook**

To stop the notebook, press `CTRL+C` or run:

```bash
docker-compose down
```
