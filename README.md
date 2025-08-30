# EvoAstra Internship Projects

This repository hosts two exciting projects from my internship journey:

---

## 1. Used Car Market Analysis (Exploratory Data Analysis)

> **Note:** The dataset used for this project is confidential and cannot be shared publicly due to internship rules.

I delved into a used car dataset to uncover patterns and market behaviors using visualizations and statistical insights. Here's what I discovered:

- **Fuel Type Trends**: Diesel and Petrol cars dominate the listings, while CNG and Electric vehicles lag behind—reflecting the current adoption trends in the used car market.  
- **Transmission Breakdown**: Manual cars are far more prevalent than automatic ones, suggesting stronger supply or preference in that segment.  
- **Ownership Insights**: First-owner cars are the most common listings—likely because they’re perceived as better maintained and offer better resale value.  
- **Price Distribution**: Most cars lie in a mid-price range, with a “long tail” of premium, rare high-priced listings.  
- **Age vs. Price**: Prediction holds—older cars are cheaper. However, some model years show greater price variations, possibly due to condition or model type.  
- **Fuel Type & Price**: Diesel cars tend to fetch higher average prices, perhaps due to their efficiency and desirability for long drives.  
- **Mileage Patterns**: The majority of cars have moderate mileage, with high-mileage models standing out as clear exceptions.  
- **Geographical Hotspots**: A few cities account for the majority of car listings, indicating regional sales hubs.  
- **Price Drivers**: Price strongly correlates with year (newer cars cost more) and inversely with kilometers driven—newer, low-mileage cars are pricier.

---

## 2. Image Captioning Model

Here’s my deep learning project, where I built an image caption generator using a combination of CNNs and LSTM with attention—for real-time caption generation!

### Highlight Features

- **Feature Extractor**: Started with VGG16, but switched to **MobileNetV2** for better memory efficiency in resource-limited environments.
- **Model Structure**: Includes caption preprocessing, LSTM-based generator, and attention mechanism for context-aware captions.
- **Dataset Used**: Trained and evaluated on the [Flickr8k dataset](https://www.kaggle.com/adityajn105/flickr8k), which includes 8,091 images each paired with 5 descriptive captions.
- **Interactive Demo**: Deployed as a Streamlit app, enabling easy, interactive caption generation.[DEMO](evoastrainternship-img.streamlit.app/)

### Installation Steps

```bash
# Clone the project
git clone https://github.com/DEEP-222-N/EvoAstra_Internship.git
cd EvoAstra_Internship

# Install dependencies
pip install -r requirements.txt
