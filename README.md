# 🍽️ Restaurant Business Segmentation (Zomato Dataset)

Segmented ~900+ restaurants from Indian metropolitan areas using clustering techniques to uncover business categories relevant to POS and food-tech platforms.

## 🎯 Data & Features
- **Dataset**: Restaurants of Metropolitan cities CSV (https://www.kaggle.com/datasets/narsingraogoud/zomato-restaurants-dataset-for-metropolitan-areas)
- **Features**: Dining Rating, Delivery Rating, Dining Votes, Delivery Votes, Price for two

## 🛠️ Approach
1. Cleaned and preprocessed data (handled nulls, scaled features)
2. Applied KMeans clustering (4 clusters)
3. Used PCA for 2D visualization
4. Labeled clusters based on mean metrics

## 🧠 Resulting Segments
- **High-Volume Dine-In**: High dining votes and ratings
- **Delivery-Centric**: Very high delivery votes
- **Budget Low-Traffic**: Low cost and engagement
- **Premium All-Rounder**: High ratings across the board

![Restaurant Segment Clusters](visuals/restaurant_segments.png)

## 📈 Use Case
Helps POS or aggregator platforms design targeted service plans and pricing models tailored to each restaurant segment.

## 🛠️ Tools
Python, Pandas, Scikit-learn, Seaborn, Matplotlib, PCA

