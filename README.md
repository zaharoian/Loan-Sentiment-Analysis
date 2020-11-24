# Loan-Sentiment-Analysis

## Abstract
Peer-to-peer (P2P) lending services, like LendingClub, are growing as an alternative to those who cannot or choose not to borrow from traditional institutions such as banks. Individuals who act as lenders fund a borrower and are self-deterministic in who they fund. It is imperative that this new class of lenders has the tools to accurately assess borrowers and their likelihood of defaulting. We tested to see if the model will see a statistically significant improvement in performance when the textual data are used in conjunction with financial data to predict loan default. A baseline model was created using Logistic Regression. The sentiment was extracted using the Bag-of-Words method with the Loughran-McDonald Word Sentiment list. This data was added to the original features and a new model was compared against the baseline model. We found that there is a significant difference when adding the sentiment analysis to the pre-existing model, given enough data. This agrees with current literature surrounding textual analysis and credit risk, though more advanced sentiment analysis may need to be used to glean a greater performance improvement.

## Github Structure
- My thesis is compiled in the PDF: Loan_Sentiment_Analysis_Final.pdf
- The code is within the two iPython Notebooks: Loan Analysis 36 month.ipynb & Loan Analysis 60 month.ipynb
