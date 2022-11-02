
## Question Answering Model

Question Answering model, for one word answer to questions. I used this to illustrate how attention works in a LSTM Neural network in [this blog post](https://nextitproject.ro/2022/11/02/the-key-concepts-of-the-nlp-revolution-and-how-the-good-soldier-svejk-would-benefit-from-them/)

### Data

We have constructed a dataset with (question, one word answer) from the following public datasets

* https://www.kaggle.com/datasets/rtatman/questionanswer-dataset?select=S09_question_answer_pairs.txt
* https://www.kaggle.com/datasets/soumikrakshit/yahoo-answers-dataset?resource=download


### Code

* construct_dataset.ipynb extracts from the above datasets only the questions with one word answer and merges multiple datasets together
* question_answering.ipynb is the ML model itself. It is inspired by the Neural Machine Translation assignment from Andrew Ng's Deep Learning Specialization
