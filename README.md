# Iris-Flower-Classification<br>
## Iris Species in the Dataset<br>
Setosa<br>
Versicolor<br>
Virginica<br>
Total Instances: 150 flowers (50 per class)<br>

🔧 Step-by-Step Approach with Code<br>

✅ Step 1: Import Libraries<br>
import numpy as np
import pandas as pd
import seaborn as sns<br>

✅ Step 2: Load Dataset<br>
iris = load_iris()
df = pd.DataFrame(data=iris.data, columns=iris.feature_names)<br>

✅ Step 3: Exploratory Data Analysis (EDA)<br>
.describe() gives summary stats.

pairplot() helps visualize relationships between features colored by species.<br>

✅ Step 4: Prepare Features and Target<br>

✅ Step 5: Split the Dataset<br>
Split into 80% training and 20% test data.<br>

✅ Step 6: Feature Scaling (Optional for tree-based models, but good practice)<br>
We use a Random Forest classifier, which is robust and handles classification tasks well.<br>

✅ Step 8: Make Predictions<br>

Accuracy: Should be around 95%–100% due to the simplicity of the dataset.

Classification Report: Shows precision, recall, and f1-score for each class.

Confusion Matrix: Visualizes model performance per class.


