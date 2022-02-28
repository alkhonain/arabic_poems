# Arabic Poems
This repository for implementing [ML Olympiad - Arabic_Poems](https://www.kaggle.com/c/ml-olympiad-arabic-poems/submissions?group=successful&page=1&pageSize=100)  one of Community Prediction Competition

The project idea is find the pattern of poet and then predict who write a poem from the model by taking the poem as input and get the poet as an output.


## Dataset
Arabic poetry is the oldest and the most prominent form of Arabic literature today. Ancient Arabic poetry is probably the primary source for describing the social, political and intellectual life in the Arab world. Modern poetry has gone through major changes and shifts both in the form and in the topics.<br><br>
The dataset contains over 58K poems that extend from the 6th century to the present day. Along with each poem, poem metadata have also been scrapped such as poet name, the poem, and its category. The data were scraped from adab.com


## Model
To solve this issue first the dataset must be cleaned to do that, by applying the techniques to clean the dataset such as removing stop words, null values and punctuations after the cleaning the data, i implemented the NLP process starting from Normalized to Lemmatized using [Farasa](http://farasa.qcri.org) model to Lemmatize the arabic words.<br>
then apply feature extraction techniques to convert text to number and finally apply it to the model.<br>
i created two models one using [TensorFlow]() and the other using [Sklearn]() and it got very high result such as 67% accuracy and 71% validation.


## Tools

- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for plotting
- Sklearn and TensorFlow for Modling

