# Lyric-artist Predictor by NLP and web scraped

This project is a Natural Language Processing (NLP) and web scraping project that aims to predict an artist from a given set of lyrics. The project includes two scripts with command line interfaces, one for web scraping lyrics of any artist from [lyrics](https://www.lyrics.com/) website using Beautiful Soup and regular expressions and another for creating fancy word clouds from the scraped lyrics.

## Technologies Used
**Plotting**: Seaborn, Matplotlib
**Web Scraping**: Requests, Time, BeautifulSoup
**Operating System Management**: os
**Regular Expressions**: re
**Split Data**: train_test_split, GridSearchCV
**Feature Extraction**: CountVectorizer, TfidfVectorizer, SelectKBest, f_classif, make_pipeline
**Feature Engineering**: ColumnTransformer
**Model**: DummyClassifier, LogisticRegression, DecisionTreeClassifier, RandomForestClassifier
**Model Evaluation**: metrics, classification_report, r2_score, mean_squared_error, mean_absolute_error, mean_squared_log_error, confusion_matrix
**Model Saving**: joblib

## Future Improvements
This project can be improved in several ways, such as:

* Adding more artists' lyrics for training the model to increase its accuracy
* Implementing more advanced NLP techniques such as sentiment analysis
* Developing a web application for easy accessibility and better user experience.
## License
This project is licensed under the MIT license. Feel free to use and modify the code for your own purposes.
