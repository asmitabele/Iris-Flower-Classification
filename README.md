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
✅ Step 3: Exploratory Data Analysis (EDA)
