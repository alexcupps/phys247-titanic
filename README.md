# phys247-titanic

Titanic Machine Learning Data Trainer
- In this notebook, we will analyze the test data and attempt to predict the outcomes for the missing people. Given the data we have, can we accurately predict whether the rest of the people lived or died?
- First, we will want to do manual research on the data we have. Are there any trends (gender, ticket class, age, etc.) that represent a strong-ish correlation with survival rate?

Data Information

(1) train.csv
- train.csv contains the details of a subset of the passengers on board (891 passengers, to be exact -- where each passenger gets a different row in the table).

- The values in the second column ("Survived") can be used to determine whether each passenger survived or not:
- if it's a "1", the passenger survived.
- if it's a "0", the passenger died.

(2) test.csv
- Using the patterns you find in train.csv, you have to predict whether the other 418 passengers on board (in test.csv) survived.

- Note that test.csv does not have a "Survived" column - this information is hidden from you, and how well you do at predicting these hidden values will determine how highly you score in the competition!

(3) gender_submission.csv
- The gender_submission.csv file is provided as an example that shows how you should structure your predictions. It predicts that all female passengers survived, and all male passengers died. Your hypotheses regarding survival will probably be different, which will lead to a different submission file. But, just like this file, your submission should have:

- a "PassengerId" column containing the IDs of each passenger from test.csv.
- a "Survived" column (that you will create!) with a "1" for the rows where you think the passenger survived, and a "0" where you predict that the passenger died.

