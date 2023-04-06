#### Title
- Toxic comments prediction, compare models BERT and TF IDF
- Training project from Yandex Practicum (INO СPE «Yandex EdTEch»), Data Scientist specialist
#### Description of the project
- Dataset: CSV with text comments and text toxicity markup
- Task: оnline store "Wikishop" launches a new service: users be able to add own product descriptions and comments. The store needs a tool that will track toxic comments.
- Classification task
- For customer was important: quality of prediction (F1 metric not less 0.75)
- Dataset with text and boolean features
#### Main tools 
- Jupiter notebook, Python and Markdown
- Markdown notes on Russian
####  Machine Learning tools  
- ML models GridSearchCV, LogisticRegression,RandomForestClassifier, DecisionTreeClassifier, LGBMClassifier
- Transformers: BertTokenizer ("unitary/toxic-bert"), AutoModel, AutoTokenizer
- For other text extraction: TfidfVectorizer, WordNetLemmatizer
- ML metrics accuracy_score, f1_score
#### Conclusions
- The project is completed
- Different Count-Based Ebbedding and Transformers Methods for features extraction were compared
- Machine learning models were trained and compared, the model with the best metric was selected
- The selected Machine learning model was tested on a test dataset
- Required metric was reached 
