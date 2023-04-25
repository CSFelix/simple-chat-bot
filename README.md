<h1 align="center">💬 Simple Chat Bot 💬</h1>
<p align="center"><i>Create your first Chat Bot with Python</i></p>

<br />

----

<h2 id="problem-description">📝 Problem Description</h2>

<br />

<figure>
    <img src="https://res.cloudinary.com/dte7upwcr/image/upload/blog/blog2/chatbot-o-que-e/chatbot-o-que-e-img_header.jpg" alt="Chat Bot Image" />
    <figcaption><i>Fig. 1 - Chat Bot. <sup>©</sup><a href="https://cloudinary.com" target="_blank">Cloudinary</a></i></figcaption>
</figure>

<br /><br />

You have been hired by CUMI (*Central Unity of My Imagination*) to construct a Chat Bot model to talk with people in **English**, **Japanese** and **Portuguese**. The bot does not have a especific purpose, that is, it should just answer simple small talk questions.

You received a dataset containing more than 3k questions and answers to train the model. You can use any programming language and library, however, you have to explain each project step.

In the end, save the model in a pickle file to others be able to use it!

----

<h2 id="files-description">📁 Files Description</h2>

> **conversation.csv** - contains around 3K simple small talk questions and answers to train the model.

----

<h2 id="features">❓ Features</h2>

> **Id** - row id to identify the (*question, answer*) pair;

> **Question** - small talk question.

----

<h2 id="target-feature">🌟 Target Feature</h2>

> **Answer** - small talk answer.

----

<h2 id="metric">📏 Metric</h2>

There are inumerous metrics we can us to evaluate Chat Bot models, such as *Number of Active Users*, *Users Satisfaction Score*, *Number of Total Intections per Conversation* and *Time/Lenght of Conversation*. In this project, we will be using **Goal Completion Rate (*GCR*)**.

*GCR* measures how good the model fills its role. In our case, our model goal is to answer simple small talk questions, so, after training it, we will do some conversation tests and se how good and coherent the model answers.

----

<h2 id="limitations">🛑 Limitations</h2>

Nothing is perfect in this world and Artificial Intelligence and Data Science are not exceptions. Always there will be limitations in our projects.

The first - and most obvious - limitation we have here are the languages! Our bot will be able to understand English, Japanese and Portuguese only, so, if the model's accessibility becomes public to any person around the world, this person must now one of these three languages or use translators (like *Google Translate*) in order to interact with it.

Besides, even though our dataset contains around 3k small talk questions, it does not contain all possible questions in small talk and our model will probably not answer well some especific questions - yeah, I believe that we won't be able to ask about animes and shows spoilers. 😥

----

<h2 id="goals">🎯 Goals</h2>

> **Goal 1** - make a word cloud about the questions and other one about the answers;

> **Goal 2** - make the model answer simple  small talk questions based on our dataset;

> **Goal 3** - make the model be able to understand and answer in **English**, **Japanese** and **Portuguese**.

----

<h2 id="setup">⚙️ Setup</h2>

***Tools***

> Python Version 3.9.x+;

> Jupyter Notebook;

<br />

***Libraries***

> Pandas, Numpy, WordCloud;

> ChatterBot, NLTK, Tensorflow, Keras;

> Pickles.

----

<h2 id="acknowledgments">🎉 Acknowledgements</h2>

> Dataset by [*Kreesh Rajani*](https://www.kaggle.com/kreeshrajani) from Kaggle;

> Dataset URL: [3k Conversations Dataset for Chat Bot](https://www.kaggle.com/datasets/kreeshrajani/3k-conversations-dataset-for-chatbot).

----

<h2 id="reach-me">📫 Reach Me</h2>

> Email: csfelix08@gmail.com

> Linkedin: [linkedin.com/in/csfelix/](https://linkedin.com/in/csfelix/)

> Portfolio: [CSFelix.io](https://csfelix.github.io)
    
> Kaggle: [DSFelix](https://www.kaggle.com/dsfelix)
