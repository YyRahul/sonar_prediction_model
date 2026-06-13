# Sonar Rock vs Mine Prediction

A machine learning model that classifies underwater sonar signals as either 
a **Rock (R)** or a **Mine (M)** using Logistic Regression.

## About the Dataset
- 208 sonar signal samples
- 60 frequency features per sample representing sonar echo energy
- Binary labels: M (Mine) and R (Rock)
- Source: UCI Machine Learning Repository

## How It Works
A sonar device sends sound pulses underwater and records how they bounce back.
The echo is split into 60 frequency bands. This model analyzes those 60 values
and predicts whether the object is a dangerous mine or a harmless rock.

## Model
- Algorithm: Logistic Regression
- Training set: 90% (187 samples)
- Test set: 10% (21 samples)

## Results
| Dataset | Accuracy |
|---------|----------|
| Training | ~83% |
| Testing | ~76% |

## Tech Stack
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Clone the repo
2. Create a virtual environment
3. Install dependencies
4. Open and run `sonar.ipynb`
