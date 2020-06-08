Collection of personal ML projects I worked on.

1) AntiRacist OpenAI
This project was borne from messing around with OpenAI's GPT-2 NLP model that focuses on predictive text analysis.
Out of curiosity I built it as it was trained and released, asked it a series of socially-divisive questions, and confirmed my belief
that it's training material has left the AI very, very racist/bias.

So I created additional training material in the form of famous african-american poets and authors to see A) if it had an effect and 
B) if so, how much data/retraining does it take to see a change.

Enclosed is the scripting I used to train and run the model, some sample output after 100 epochs of training, and the dataset used to retrain.


2) ML_Trading
ML_Trading was just a curiosity project that looked at using LSTM/other advanced ML models to predict the stock market in 
various increments. The intention is to hook it up through a robinhood API to automate trading. 

Some models came away very accurate, others not so much.
