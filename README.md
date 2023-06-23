# Comment_toxicity_checker

The Toxicity Checker is a program designed to analyze text comments and predict the level of toxicity present in them. It utilizes a machine learning model trained on a dataset obtained from the Jigsaw Toxic Comment Classification Challenge hosted on Kaggle.

# Dataset
The dataset used in this program is sourced from the Jigsaw Toxic Comment Classification Challenge on Kaggle. It consists of a large collection of comments from various online platforms, along with labels indicating the presence and types of toxicity in each comment. The dataset provides a valuable resource for training machine learning models to classify toxic comments accurately.

To use this program, you will need to download the dataset from the following URL: https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data

Once downloaded, extract the contents of the dataset and ensure that the necessary files are available to the program. The program expects the dataset to be in the following directory structure:

Copy code
toxicity_checker/
    ├── train.csv
    └── test.csv
    
The train.csv file contains the training data, which includes comments and their associated toxicity labels. The test.csv file contains comments for which the toxicity levels need to be predicted.

Installation and Setup
Clone the repository from GitHub:
bash
Copy code
git clone https://github.com/SouravRay17/Comment_toxicity_checker.git
Navigate to the project directory:
bash
Copy code
cd toxicity_checker
Set up a Python virtual environment (optional but recommended):
Copy code
python3 -m venv venv
Activate the virtual environment:
bash
Copy code
source venv/bin/activate
Download the dataset from the provided Kaggle URL and extract the contents.

Move the train.csv and test.csv files into the toxicity_checker directory.

Usage
Ensure that you have activated the virtual environment (if applicable) and are in the toxicity_checker directory.

Run the program:
toxicity_checker.ipynb

The program will load the training data from the train.csv file and train the toxicity classification model.

Once the model is trained, it will prompt you to enter a comment for toxicity analysis.

Input the comment and press Enter.

The program will analyze the comment and provide a toxicity prediction along with the probability scores for each toxicity category.

License
This project is licensed under the Apache License.

Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on GitHub.

Acknowledgments
The Jigsaw Toxic Comment Classification Challenge on Kaggle for providing the dataset used in this project.
Contact
For any questions or inquiries, please contact [sroy.dgp2014.com].

Thank you for using the Toxicity Checker!
