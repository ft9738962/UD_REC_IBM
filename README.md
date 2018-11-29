# 1. Purpose
This project for [Udacity Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

The recommendation engine aims for make recommendation of articles from [Watson Cloud](https://dataplatform.cloud.ibm.com/) community

The project has combined useful techniques from lessons in Data Science Nanodegree to work out some solution of recommendation to different kind of users in community.

It also includes some discussion of the limit of the data to perform better result and give constructive suggestion on how to imporve.

# 2. File Description

- Data:
    - articles_community.csv: store article info including article id, status, body, description and full name
    - user-item-interactions.csv: record articles and user(based on email address) interaction info

- Recommendations_with_IBM.ipynb: Jupyter notebook show how the data explored and different recommendation method (cold start, similarity, SVD) for different type of users

- Recommendations_with_IBM.html: HTML version of the jupyter notebook

- user_item_matrix.p: store data of relationship between user and articles using 0(no interaction) and 1(has interaction)

# 3. How to Interact with the Project

Any improvement suggestion or idea is appreciated especially for the better recommendation method.

The pushed code should follow PEP-8 style.
# 4. Licensing

BSD 3-clause
# 5. Authors
[Max Qiu](https://github.com/ft9738962)
