❤️ Heart Disease Prediction using Decision Tree with Cost-Complexity Pruning

📌 Project Overview

This project aims to predict heart disease 🫀 using a Decision Tree classifier, implementing cost-complexity pruning to optimize model performance. The dataset includes multiple medical attributes to determine whether a patient is at risk. Model accuracy is evaluated through cross-validation and visualizations to analyze the effect of ccp_alpha on pruning.

📊 Dataset

The dataset consists of medical records with attributes such as age, sex, cholesterol levels, blood pressure, and other medical indicators. The target variable is the presence (1) or absence (0) of heart disease.

🔍 Project Workflow

🏗️ Step 1: Data Preprocessing

✅ Load the dataset using pandas
✅ Handle missing values (if any)
✅ Convert categorical data into numerical form
✅ Normalize/scale features for better model performance

📊 Step 2: Exploratory Data Analysis (EDA)

📌 Generate summary statistics
📌 Visualize feature distributions
📌 Identify correlations among variables

🏋️ Step 3: Model Training and Evaluation

🛠️ Split data into training & testing sets
🛠️ Train a Decision Tree classifier
🛠️ Apply cost-complexity pruning (ccp_alpha)
🛠️ Evaluate accuracy using cross-validation
🛠️ Visualize decision tree before & after pruning

🧪 Step 4: Hyperparameter Tuning with ccp_alpha

📌 Extract effective alphas for pruning
📌 Train multiple pruned trees & compare accuracies
📌 Plot the effect of ccp_alpha on model performance

✅ Step 5: Final Model Selection

🎯 Select optimal ccp_alpha using cross-validation
🎯 Train the final pruned decision tree
🎯 Evaluate performance on the test set

📈 Results & Insights

🔹 Impact of pruning on model performance analyzed
🔹 Balanced complexity & accuracy using ccp_alpha
🔹 Pruned model generalizes better and reduces overfitting

🛠 Installation & Usage

🖥 Requirements:

⚙️ Python 3.x
⚙️ Jupyter Notebook / Google Colab
⚙️ Install required libraries:

pip install numpy pandas scikit-learn matplotlib seaborn

🚀 Running the Notebook

1️⃣ Clone the repository:

git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction

2️⃣ Open Jupyter Notebook or Google Colab and run all cells

🏁 Conclusion

This project demonstrates how cost-complexity pruning enhances decision tree performance 🏆. By tuning ccp_alpha, the model achieves an optimal trade-off between accuracy and interpretability.
