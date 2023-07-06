# CHATBOT-WITH--GUI-




CHAT BOT  


ChatterBot is a machine-learning based conversational dialog engine build in Python which makes it possible to generate responses based on collections of known conversations. The language independent design of ChatterBot allows it to be trained to speak any language


How it works
An untrained instance of ChatterBot starts off with no knowledge of how to communicate. Each time a user enters a statement, the library saves the text that they entered and the text that the statement was in response to. As ChatterBot receives more input the number of responses that it can reply and the accuracy of each response in relation to the input statement increase. The program selects the closest matching response by searching for the closest matching known statement that matches the input, it then returns the most likely response to that statement based on how frequently each response is issued by the people the bot communicates with.






Installation
This package can be installed from PyPi by running:
pip install chatterbot
Basic Usage
from chatterbot import ChatBot
from chatterbot.trainers import ChatterBotCorpusTrainer
time.clock = time.time
chatbot = ChatBot('Ron Obvious')
# Create a new trainer for the chatbot
trainer = ChatterBotCorpusTrainer(chatbot)
# Train the chatbot based on the english corpus
trainer.train("chatterbot.corpus.english")
# Get a response to an input statement
chatbot.get_response("Hello, how are you today?")






# TRAINING SETS FOR THE CHATBOT
trainer.train("chatterbot.corpus.english")
Training ai.yml:         [####################] 100%<br>
Training botprofile.yml: [####################] 100%
Training computers.yml:   [####################] 100%
Training conversations.yml: [####################] 100%
Training emotion.yml:       [####################] 100%
Training food.yml:          [####################] 100%
Training gossip.yml:        [####################] 100%
Training greetings.yml:     [####################] 100%
Training health.yml:        [####################] 100%
Training history.yml: 	      [####################] 100%
Training humor.yml:           [####################] 100%
Training literature.yml:     [####################] 100%
Training money.yml:           [####################] 100%
Training movies.yml: [####################] 100%
Training politics.yml: [####################] 100%
Training psychology.yml: [####################] 100%
Training science.yml: [####################] 100%
Training sports.yml: [####################] 100%
Training trivia.yml: [####################] 100


