# Predicting The News Category

This project aims to classify news articles into their respective genres or categories using Natural Language Processing (NLP) techniques. The challenge is to predict the section (category) a given news story belongs to based on its content. This was accomplished as part of a hackathon.

## Problem Statement

Since the inception of printed newspapers, news has been categorized into specific sections. This tradition continues in digital formats today. The task is to use NLP to automatically predict the category of a news story. The categories are:
- Politics: 0
- Technology: 1
- Entertainment: 2
- Business: 3

## Dataset

The dataset consists of a training set with 7,628 records and a test set with 2,748 records. Each record contains:
- `STORY`: Part of the main content of the article.
- `SECTION`: The genre/category the story falls into.

## Files

- `Data_Train.xlsx`: Contains the training data.
- `Data_Test.xlsx`: Contains the test data.
- `Notebook.ipynb`: Jupyter notebook with the data preprocessing, model training, and evaluation.
- `Predictions.xlsx`: Contains the predicted categories for the test set.

## Hackathon Rules

1. **One Account Per Participant**: Each participant must use only one account. Submissions from multiple accounts will result in disqualification.
2. **No Private Sharing**: Sharing code or data privately outside of teams is not permitted. Sharing code on public forums for all participants is allowed.
3. **Submission Limits**: Each participant can make up to 10 submissions per day. Additional submissions will not be evaluated.
4. **Eligibility**: All registered users are eligible to participate in the hackathon.

## Evaluation

The leaderboard is evaluated based on the standard `accuracy_score` metric from `sklearn`.

## Results

- **Rank**: 456
- **Score**: 0.94214
- **Profile**: [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6)

## Getting Started

1. **Clone the Repository**: 
   ```sh
   git clone <repository-url>
   ```
2. **Install Dependencies**: 
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**: 
   Open `Notebook.ipynb` in Jupyter and execute the cells to preprocess the data, train the model, and make predictions.

## Conclusion

This project demonstrates how NLP can be used to classify news articles into their respective categories, automating a task traditionally done manually. The solution achieves a high accuracy score and provides a solid foundation for further improvements and experimentation.

## Contact

For any queries or suggestions, please contact [Gandharv Kulkarni](https://machinehack.com/user/65dd51b822401c0019068cb6).

---

Feel free to modify the content as per your requirements.
