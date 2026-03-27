<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f4c35,50:1a7a52,100:27ae60&height=200&section=header&text=MedCost%20Predictor&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Medical%20Insurance%20Cost%20Prediction%20%7C%20Linear%20Regression&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

<br/>


![Python](https://img.shields.io/badge/Python_3.10+-white?style=flat-square&logo=python&logoColor=0f4c35&labelColor=d4edda&color=0f4c35)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-white?style=flat-square&logo=jupyter&logoColor=6a0dad&labelColor=e8d5f5&color=6a0dad)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-white?style=flat-square&logo=scikitlearn&logoColor=b8860b&labelColor=fff8dc&color=b8860b)
![Pandas](https://img.shields.io/badge/Pandas-white?style=flat-square&logo=pandas&logoColor=0f4c35&labelColor=d4edda&color=0f4c35)
![NumPy](https://img.shields.io/badge/NumPy-white?style=flat-square&logo=numpy&logoColor=6a0dad&labelColor=e8d5f5&color=6a0dad)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-white?style=flat-square&logoColor=b8860b&labelColor=fff8dc&color=b8860b)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plots-white?style=flat-square&logoColor=0f4c35&labelColor=d4edda&color=0f4c35)
![License](https://img.shields.io/badge/License-MIT-white?style=flat-square&logoColor=6a0dad&labelColor=e8d5f5&color=6a0dad)

<br/>

![R2 Train](https://img.shields.io/badge/🏋️_Train_R²-0.7515-0f4c35?style=for-the-badge&labelColor=145a32)
![R2 Test](https://img.shields.io/badge/🧪_Test_R²-0.7447-6a0dad?style=for-the-badge&labelColor=4a0080)
![Rows](https://img.shields.io/badge/📦_Dataset-1338_Rows-b8860b?style=for-the-badge&labelColor=7d5a00)
![Features](https://img.shields.io/badge/🔢_Features-6_+_1_Target-0f4c35?style=for-the-badge&labelColor=145a32)

<br/>

> ### 🩺 *Predict annual medical insurance charges using patient health & demographic data*
> #### Linear Regression · Full EDA Pipeline · Real-time Predictive System · Zero Overfitting

<br/>

[![About](https://img.shields.io/badge/◈_ABOUT-0f4c35?style=for-the-badge)](#-about-the-project)&nbsp;
[![Demo](https://img.shields.io/badge/◈_DEMO-6a0dad?style=for-the-badge)](#-demo)&nbsp;
[![Stack](https://img.shields.io/badge/◈_TECH_STACK-b8860b?style=for-the-badge)](#️-tech-stack)&nbsp;
[![Features](https://img.shields.io/badge/◈_FEATURES-0f4c35?style=for-the-badge)](#-features)&nbsp;
[![Dataset](https://img.shields.io/badge/◈_DATASET-6a0dad?style=for-the-badge)](#-dataset)&nbsp;
[![Start](https://img.shields.io/badge/◈_GET_STARTED-b8860b?style=for-the-badge)](#-getting-started)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f4c35,100:27ae60&height=3&section=header" width="100%"/>

<br/>

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Demo](#-demo)
- [Tech Stack](#️-tech-stack)
- [Features](#-features)
- [Dataset](#-dataset)
- [How It Works](#️-how-it-works)
- [Project Structure](#️-project-structure)
- [Getting Started](#-getting-started)
- [Contributing](#-contributing)
- [License](#️-license)

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6a0dad,100:9b59b6&height=3" width="100%"/>

## 🧠 About the Project

<table>
<tr>
<td>

**🏥 Medical Insurance Cost Prediction** is an end-to-end Machine Learning project that uses **Linear Regression** to predict the annual medical insurance charges billed to a patient — based on their personal health and demographic attributes.

Built inside the 🏗️ **[Medcost_Prediction_Linear_Regression](https://github.com/Medcost_Prediction_Linear_Regression)** repository, this project walks through the **complete ML lifecycle**:

| 🔢 | 📌 Stage | 💬 Description |
|:---:|:---|:---|
| `01` | 🔍 **EDA** | Understand distributions, correlations, and outliers |
| `02` | 🧹 **Preprocessing** | Handle duplicates, encode categoricals, split data |
| `03` | 🤖 **Model Training** | Fit Linear Regression using Scikit-Learn |
| `04` | 📊 **Evaluation** | R² score on training and test sets |
| `05` | 🔮 **Prediction** | Input patient data → instant cost estimate |

> Whether you're a student 🎓 learning ML fundamentals, a data scientist 🧑‍💻 exploring healthcare analytics, or just curious how insurance premiums work 🤔 — this is your clean, well-documented, beginner-friendly reference! 💪

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:b8860b,100:f1c40f&height=3" width="100%"/>

## 🎬 Demo

### 🔮 Predictive System — Live Output

```python
╔══════════════════════════════════════════════════════════════╗
║  🩺  PATIENT INPUT                                           ║
║  ─────────────────────────────────────────────────────────── ║
║  Age: 31  │  Sex: Female  │  BMI: 25.74                      ║
║  Children: 0  │  Smoker: No  │  Region: Southeast            ║
╠══════════════════════════════════════════════════════════════╣
║  💰  PREDICTED INSURANCE COST  →  $ 3,760.08                 ║
╚══════════════════════════════════════════════════════════════╝
```

### 📊 Model Performance Scorecard

<div align="center">

|  | 🏋️ Training Set | 🧪 Test Set | ✅ Status |
|:---:|:---:|:---:|:---:|
| 📈 **R² Score** | `0.7515` | `0.7447` | Healthy Gap |
| 💬 **Variance Explained** | 75.15% | 74.47% | Consistent |
| 🧠 **Overfitting** | — | ❌ None | Well-Generalized |

</div>

> 💡 **Insight:** The near-identical R² on train vs test confirms the model **generalizes well** — it's neither overfitting nor underfitting! 🎉

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f4c35,100:27ae60&height=3" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

| 🟢 Layer | 🔵 Technology | 🟡 Role |
|:---:|:---:|:---|
| 🤖 **ML Model** | `sklearn.linear_model.LinearRegression` | Core regression — training & prediction |
| 🐍 **Language** | Python 3.10+ | Runtime environment |
| 📓 **Notebook** | Jupyter Notebook | Interactive development & EDA |
| 🗃️ **Data** | Pandas DataFrame | Data loading, cleaning, encoding |
| 🔢 **Arrays** | NumPy | Reshaping, input formatting |
| 📊 **Plots** | Matplotlib + Seaborn | Scatter, heatmap, distribution charts |
| 📐 **Metrics** | `sklearn.metrics` | R² score computation |

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6a0dad,100:9b59b6&height=3" width="100%"/>

## ✨ Features

<details open>
<summary><b>🟢 &nbsp; Exploratory Data Analysis (EDA)</b></summary>
<br/>

- 📋 **Dataset overview** — `.shape`, `.dtypes`, `.info()`, `.head()`, `.tail()`, `.describe()`
- 🕵️ **Missing value detection** — `isnull()`, `notnull()`, `isnull().sum()` — ✅ zero nulls confirmed!
- 🔁 **Duplicate handling** — 1 duplicate row detected & dropped (`1338 → 1337` rows)
- 📊 **Statistical summary** — mean, std, min/max for all numerical features
- 🔥 **Correlation heatmap** — identify which features drive insurance charges the most
- 📈 **Scatter plots** — `Age vs Charges`, `BMI vs Charges` visual relationships
- 📦 **Distribution plots** — understand feature spread and skewness

</details>

<details open>
<summary><b>🔵 &nbsp; Data Preprocessing</b></summary>
<br/>

- 🔤 **Label Encoding** — categorical columns (`sex`, `smoker`, `region`) → clean integer values
- 🏷️ **Feature-Target split** — `X` (6 features) and `Y` (`charges`) clearly separated
- ✂️ **Train-Test split** — clean 80/20 split via `sklearn.model_selection.train_test_split`

</details>

<details open>
<summary><b>🟡 &nbsp; Model Training & Evaluation</b></summary>
<br/>

- 📐 **Linear Regression** — fitted via `sklearn.linear_model.LinearRegression`
- 📊 **R² Score** — computed on both training (`0.7515`) and test (`0.7447`) sets
- ✅ **Generalization confirmed** — close train/test scores → zero overfitting

</details>

<details open>
<summary><b>🟣 &nbsp; Predictive System</b></summary>
<br/>

- 🩺 **Real-time prediction** — input patient attributes → instant predicted cost
- 🔢 **NumPy pipeline** — input → `np.asarray()` → `.reshape(1,-1)` → `regressor.predict()` → 💰

</details>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:b8860b,100:f1c40f&height=3" width="100%"/>

## 📦 Dataset

<div align="center">

### 📥 [`insurance.csv`](./insurance.csv) — Patient Insurance Records

</div>

<div align="center">

| 📏 Rows | 🗂️ Columns | 🚫 Nulls | 🔁 Duplicates | 🎯 Target |
|:---:|:---:|:---:|:---:|:---:|
| `1,338` → `1,337` | `7` | `0 ✅` | `1 removed` | `charges` (USD 💵) |

</div>

### 🏷️ Column Descriptions

| # | 📋 Column | 🗂️ Type | 📝 Description |
|:---:|:---:|:---:|:---|
| `1` | `age` | 🟢 Numerical | Patient age — older patients typically incur higher costs |
| `2` | `sex` | 🔵 Categorical | Gender — `male` / `female` |
| `3` | `bmi` | 🟢 Numerical | Body Mass Index — height-to-weight health ratio |
| `4` | `children` | 🟢 Numerical | Number of dependents — family size effect on premiums |
| `5` | `smoker` | 🔵 Categorical | 🚨 **Most influential!** — `yes` / `no` |
| `6` | `region` | 🔵 Categorical | US area — `southeast`, `southwest`, `northeast`, `northwest` |
| `🎯` | `charges` | 🟡 **Target** | Annual medical insurance cost billed (continuous, USD) |

### 🔄 Label Encoding Reference

<div align="center">

| 🏷️ Column | 🔤 Original | 🔢 Encoded |
|:---:|:---:|:---:|
| `sex` | `male` / `female` | `0` / `1` |
| `smoker` | `yes` / `no` | `0` / `1` |
| `region` | `southeast` / `southwest` / `northeast` / `northwest` | `0` / `1` / `2` / `3` |

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f4c35,100:27ae60&height=3" width="100%"/>

## ⚙️ How It Works

```
╔══════════════════════════════════════════╗
║  📥  insurance.csv  (1338 rows × 7 cols) ║
╚══════════════════╤═══════════════════════╝
                   │
                   ▼
         ┌─────────────────────┐
         │  🔍  EDA             │  shape · info · nulls
         │                     │  duplicates · plots
         └──────────┬──────────┘  heatmap · describe
                    │
                    ▼
         ┌─────────────────────┐
         │  🧹  PREPROCESSING   │  drop duplicate
         │                     │  label encode
         └──────────┬──────────┘  X / Y split · 80/20
                    │
                    ▼
         ┌─────────────────────┐
         │  🤖  TRAINING        │  LinearRegression()
         │                     │  regressor.fit(
         └──────────┬──────────┘    X_train, Y_train)
                    │
                    ▼
         ┌─────────────────────┐
         │  📊  EVALUATION      │  Train R²: 0.7515
         │                     │  Test  R²: 0.7447
         └──────────┬──────────┘  ✅ No overfitting
                    │
                    ▼
         ┌─────────────────────┐
         │  🔮  PREDICTION      │  input → numpy array
         │                     │  reshape → predict()
         └─────────────────────┘  💰 Cost Estimated!
```

### 🗂️ Notebook Sections at a Glance

| 🟢 | 📓 Section | 🎯 What Happens |
|:---:|:---|:---|
| `01` | 📥 **Data Loading** | Read `insurance.csv` into Pandas DataFrame |
| `02` | 🏷️ **Column Descriptions** | Understand each feature — type, role, importance |
| `03` | 🔍 **EDA** | Shape, dtypes, null checks, duplicates, stats, plots |
| `04` | 🧹 **Preprocessing** | Drop duplicates, label encode, feature-target split |
| `05` | ✂️ **Train-Test Split** | 80% training / 20% testing |
| `06` | 🤖 **Model Training** | Fit `LinearRegression` on training data |
| `07` | 📊 **Model Evaluation** | R² score on both train and test sets |
| `08` | 🔮 **Predictive System** | Predict cost for any new patient input |

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6a0dad,100:9b59b6&height=3" width="100%"/>

## 📁 Project Structure

```
🏗️  Medcost_Prediction_Linear_Regression/
│
└── 📂  Linear Regression Project - Medical Insurance Cost Prediction/
    │
    ├── 📓  Linear_Regression_Project_-_Medical_Insurance_Cost_Prediction
    │       -checkpoint.ipynb
    │       └──► 🧠 Main Jupyter Notebook — complete ML pipeline
    │
    ├── 🗃️  insurance.csv
    │       └──► 📦 Dataset — 1,338 patient records · 7 columns
    │
    └── 📄  README.md
            └──► 📖 You are here!
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:b8860b,100:f1c40f&height=3" width="100%"/>

## 🚀 Getting Started

### 🛒 Prerequisites

<div align="center">

| 🔩 Tool | 📋 Requirement |
|:---:|:---|
| 🐍 **Python** | 3.10 or higher |
| 📓 **Jupyter** | Notebook or JupyterLab |
| 📦 **pip** | Latest version recommended |

</div>

### 📥 Step 1 — Clone the Repository

```bash
# 🌀 Clone
git clone https://github.com/Medcost_Prediction_Linear_Regression.git

# 📂 Enter project folder
cd "Linear Regression Project - Medical Insurance Cost Prediction"
```

### 📦 Step 2 — Install Dependencies

```bash
# 🟢 Install everything in one command
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 📓 Step 3 — Launch the Notebook

```bash
# 🚀 Start Jupyter
jupyter notebook
```

Open 👇 in the browser tab that appears:

```
📓  Linear_Regression_Project_-_Medical_Insurance_Cost_Prediction-checkpoint.ipynb
```

Click **▶️ Kernel → Restart & Run All** to execute the complete pipeline!

### 🔮 Step 4 — Run Your Own Prediction

```python
# ══════════════════════════════════════════════════════
#  🩺  PATIENT DATA INPUT
#  Encoding: sex → male=0 / female=1
#            smoker → yes=0 / no=1
#            region → SE=0 / SW=1 / NE=2 / NW=3
# ══════════════════════════════════════════════════════

input_data = (31, 1, 25.74, 0, 1, 0)

# 🔢  Pipeline: input → numpy → reshape → predict
input_data_as_numpy_array = np.asarray(input_data)
input_data_reshaped = input_data_as_numpy_array.reshape(1, -1)
prediction = regressor.predict(input_data_reshaped)

print("💰 Predicted Insurance Cost: $", round(prediction[0], 2))
# ✅  Output → 💰 Predicted Insurance Cost: $ 3760.08
```

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f4c35,100:27ae60&height=3" width="100%"/>

## 🤝 Contributing

🎉 Contributions, ideas, and improvements are always welcome! Whether it's a bug fix 🐛, a new visualization 📊, or a model upgrade 🤖 — every PR makes this better. 💪

### 🔀 Steps to Contribute

```bash
# 1️⃣  Fork the repository
# 2️⃣  Create your feature branch
git checkout -b feature/YourAmazingFeature

# 3️⃣  Commit your changes
git commit -m "✨ Add YourAmazingFeature"

# 4️⃣  Push to your branch
git push origin feature/YourAmazingFeature

# 5️⃣  Open a Pull Request 🎉
```

### 💡 Roadmap & Ideas

<div align="center">

| 🎖️ Priority | 💡 Idea |
|:---:|:---|
| 🟢 **High** | 🌐 Gradio / Streamlit web app for live predictions |
| 🟢 **High** | 🌲 Ridge · Lasso · Random Forest comparison |
| 🔵 **Medium** | 📊 SHAP values for feature importance explainability |
| 🔵 **Medium** | 🔢 Polynomial features for non-linear patterns |
| 🟡 **Low** | 📉 Add MAE and RMSE alongside R² |
| 🟡 **Low** | 🐳 Docker container for one-command deployment |
| 🟡 **Low** | 📱 Deploy on Hugging Face Spaces or Render |

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6a0dad,100:9b59b6&height=3" width="100%"/>

## ⚖️ License

Distributed under the **MIT License** — free to use, modify, and distribute with attribution.
See [`LICENSE`](./LICENSE) for full details.

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f4c35,50:6a0dad,100:b8860b&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=24&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%"/>

### 🌟 Found this useful? Drop a ⭐ star — it keeps the project alive! 🙏

🏥 Built with 💚 &nbsp;·&nbsp; 🤖 Powered by Scikit-Learn &nbsp;·&nbsp; 📊 Visualized with Seaborn &nbsp;·&nbsp; 📓 Developed in Jupyter

**Part of the [Medcost_Prediction_Linear_Regression](https://github.com/Medcost_Prediction_Linear_Regression) Repository**

<br/>

[![GitHub Stars](https://img.shields.io/github/stars/Medcost_Prediction_Linear_Regression?style=for-the-badge&color=0f4c35&labelColor=145a32&logo=github)](https://github.com/Medcost_Prediction_Linear_Regression/stargazers)
&nbsp;
[![GitHub Forks](https://img.shields.io/github/forks/Medcost_Prediction_Linear_Regression?style=for-the-badge&color=6a0dad&labelColor=4a0080&logo=github)](https://github.com/Medcost_Prediction_Linear_Regression/network/members)
&nbsp;
[![GitHub Issues](https://img.shields.io/github/issues/Medcost_Prediction_Linear_Regression?style=for-the-badge&color=b8860b&labelColor=7d5a00&logo=github)](https://github.com/Medcost_Prediction_Linear_Regression/issues)

</div>
