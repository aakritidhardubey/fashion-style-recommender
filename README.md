#  Fashion Style Clustering

This project performs **unsupervised clustering** on fashion product data using the `styles.csv` dataset. It uses **KMeans** to group clothing items into categories based on features like gender, article type, and usage.

## 📁 Dataset
- **File Used**: `styles.csv`
- **Columns Selected**: `gender`, `masterCategory`, `subCategory`, `articleType`, `baseColour`, `season`, `year`, `usage`

##  ML Approach
- Cleaned data and dropped missing values
- Encoded categorical features using `OneHotEncoder`
- Applied **KMeans clustering** with `n_clusters=4`
- Mapped each cluster to a style label (e.g., "Streetwear", "Accessories")

##  Technologies
- Google Colab
- Python
- Pandas, Scikit-learn

## Output
A new `style` column is added to the dataset, identifying the fashion style cluster of each item.

## 🚀 Future Plans
- Integrate with a Flask backend
- Add a user interface for recommending fashion items
- Connect to a database to store user preferences

##  License
This project is licensed under the MIT License.
