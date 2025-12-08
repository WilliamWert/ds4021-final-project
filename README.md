# ds4021-final-project

Research Question: Which socioeconomic and behavioral factors best predict student performance in Math?

By applying modern machine learning algorithms to the Student Performance dataset, this project aims to identify which socioeconomic and behavioral factors most strongly predict academic success. Understanding these patterns can help educators and policymakers recognize which students thrive despite disadvantage– resilient learners and which groups are most vulnerable to falling behind. These insights can inform targeted academic support programs, resource allocation, and interventions that not only narrow achievement gaps but also foster equitable learning environments where all students have the opportunity to succeed.

Our dataset has 316 entries, each representing a student, with 33 columns (1 target, 2 dropped). We used various models including penalized regression, SVM, gradient boosting, and a neural network to predict a student's final grade (column G3)

## Repository contents
### Software and platform:
We used jupyter notebooks on python 3.12.1. 
With packages: 
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- PyTorch

### Documentation map:
ProjectFolder/

├── NOTEBOOKS/

│   ├── EDA.ipynb

│   ├── final_test_evaluation.ipynb

│   ├── gradient_boosting.ipynb

│   ├── neural_networks.ipynb

│   ├── penalized_regression.ipynb

│   └── svm.ipynb

│

├── OUTPUT/

│   ├── Plots from ML notebooks

│   │

│   └── EDA/

│       └── Plots from EDA notebook

│

├── data/

│   └── train and test set csv files

│

└── README.md
