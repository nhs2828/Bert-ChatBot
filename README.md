# Bert-ChatBot
A start to learn about Fine-tuning, this is a simple ChatBot implementation using pretrained Bert on [Chatbots: Intent Recognition Dataset](https://www.kaggle.com/datasets/elvinagammed/chatbots-intent-recognition-dataset).
We use pretrained Bert to know the language, and few MLPs to do the classification job (classes are intents).
After getting the predicted intent, responses will be randomly selected in the responses pool.

The result after 30 epochs is good, learning time is quite short even on CPU.
![Capture d’écran 2023-11-25 à 23 17 54](https://github.com/nhs2828/Bert-ChatBot/assets/78078713/f60353fe-8094-44e4-8c34-f73ece3d06c9)
