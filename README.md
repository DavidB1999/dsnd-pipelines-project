# README 

# dsnd-pipelines-project

This project is part of the Udacity Data Science Nanodegree. 
The task is to create a machine learning pipeline including NLP in the fictional setting of a fashion company, predicting whether or not a customer would recommend the product based on their review.

The project demonstrates:
- Text preprocessing with spaCy
- Feature extraction using TF-IDF
- Model training and evaluation using scikit-learn pipelines
- Reproducible ML workflows

## Project structure

```
dsnd-pipelines-project/
├── starter/
│   ├── data/
│   │   └── reviews.csv          # Customer review dataset
│   ├── project.ipynb            # Main project notebook
│   └── README.md                # Subfolder documentation
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
└── LICENSE.txt                  # Udacity license
```
**starter/project.ipynb** - Main project notebook:
- Data loading
- Text preprocessing using spaCy
- Feature engineering
- Model training and evaluation
- Final results 

**data/reviews.csv** - Dataset containing customer reviews and a target variable indicating whether the product was recommended.


## Getting Started

Feel free to fork my version or the [original](https://github.com/udacity/dsnd-pipelines-project).

### Dependencies

See the list of dependencies in the [requirements.txt](requirements.txt) file.

### Installation

Step by step explanation of how to get a dev environment running.

1. Clone the repo.

```
git clone https://github.com/DavidB1999/snd-pipelines-project.git
cd dsnd-pipelines-project
```

2. Create and activate a virtual environment

```
python -m venv .venv
.venv\Scripts\activate   # Windows
```

```
python -m venv .venv
source .venv/bin/activate # macOS/Linux
```

3. Install dependencies
```
pip install -r requirements.txt
```

4. Install spaCy language model
```
python -m spacy download en_core_web_sm
```

### How to run the project
After following the steps from installation...

1. Ensure the data is located at 
```
starter/data/reviews.csv
```

2. Open the Notebook 
```
starter/project.ipynb
```

3. Run the notebook from top to bottom.


## License

Licence from Udacity <br>
--- [License](LICENSE.txt)
