# Contextual-Chatbot-in-Pytorch
This is a chatbot designed for a local coffee shop which takes questions(Although limited ones) and returns answer to those questions.
## Training Model
- I followed a very simple yet state of the art modeling technique for Training it using 2 layered Feed Forward neural network.
- To train my model I used the following:-
    1. [Pytorch](https://pytorch.org/)
    2. [Numpy](https://numpy.org/)
    3. [JSON](https://www.json.org/json-en.html)
    4. [NLTK](https://www.nltk.org/)
### Steps
1. Firstly, I created a NeuralNet model from [Torch.nn Library](https://pytorch.org/docs/stable/nn.html).
2. Then, I created a intents.json JSON file which contains various tags like greetings,thanks,etc along with various patterns of asking questions regarding those type of tags and also response which computer should give in those cases.
3. Then, I created nltk_utils.py python file which contains methods like tokenize, stem, bag_of_words.
4. I made a train.py python file to train NeuralNet model for chatbot going through 1000 iterations.
5. Finally, a chat.py python file to interact with the user.

