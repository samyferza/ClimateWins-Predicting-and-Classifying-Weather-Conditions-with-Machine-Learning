# ClimateWins-Predicting-and-Classifying-Weather-Conditions-with-Machine-Learning
This project explores how machine learning algorithms can help predict and classify weather conditions across Europe, aiming to provide actionable insights for public safety, urban planning, and climate adaptation strategies.

# 🌍 ClimateWins: Predicting and Classifying Weather Conditions with Machine Learning

This project investigates how machine learning can support weather prediction and climate risk classification in Europe. By analyzing over 60 years of weather data, the project aims to provide actionable insights to enhance public safety, guide tourism and agriculture, and inform long-term urban planning.

---

## 🎯 Objectives

- Identify weather patterns outside regional norms.
- Predict whether a day will be pleasant or unpleasant based on climate variables.
- Classify weather conditions from satellite imagery.
- Determine the safest regions in Europe for future settlement.

---

## 🧪 Thought Experiments & ML Models

| Experiment                     | Method                        | Purpose                                                  |
|-------------------------------|-------------------------------|----------------------------------------------------------|
| 1. Predict Pleasant Conditions | `Random Forest`               | Forecast stable weather days using temperature, humidity, and wind. |
| 2. Detect Anomalies            | `Convolutional Neural Network (CNN)` | Classify visual weather data from satellite/radar images. |
| 3. Cluster Safe Regions        | `K-Means Clustering + PCA`    | Identify long-term climate-safe zones across Europe.     |

---

## 🧠 Key Results

### ✅ Random Forest (Thought Experiment #1)
- **Accuracy**: > 85%
- **Top Features**: Humidity and wind speed
- **Insight**: Effective for planning tourism, agriculture, and outdoor activities.

### 🌦️ CNN (Thought Experiment #2)
- **Accuracy**: ~ 90%
- **Performance**: Strong distinction between cloudy and sunny conditions.
- **Potential**: Can be scaled for real-time anomaly detection with more image data.

### 🗺️ K-Means + PCA (Thought Experiment #3)
- **Clusters**: 3–4 region types by climate behavior
- **Key Insight**: Cluster 1 represents the most stable zones for living.
- **Use Case**: Urban development and migration policy planning.

---

## 📈 Recommendations

- ✅ Deploy the Random Forest model for daily weather planning.
- 🧪 Enhance the CNN with GANs to simulate future weather conditions.
- 🧭 Use K-Means clusters to prioritize infrastructure investment in safer areas.

---

## 📁 Project Structure

