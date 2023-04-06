# Chatbot-Using-BERT-Pytorch

In this chatbot, we have used 5 intents: name, age, date, greeting, and goodbye. We have used the training set that has utterances belonging to each of these intents. When the user enters any input, the intent will be recognized by the bot.

Within this intents JSON file, alongside each intents tag, there are responses. For our chatbot, once the intent is recognized the response will be randomly selected from the static set of responses associated with each intent.

# used a dictionary to represent an intents JSON file
data = {"intents": [
{"tag": "greeting",
 "responses": ["Howdy Partner!", "Hello", "How are you doing?",   "Greetings!", "How do you do?"]},
{"tag": "age",
 "responses": ["I am 25 years old", "I was born in 1998", "My birthday is July 3rd and I was born in 1998", "03/07/1998"]},
{"tag": "date",
 "responses": ["I am available all week", "I don't have any plans",  "I am not busy"]},
{"tag": "name",
 "responses": ["My name is James", "I'm James", "James"]},
{"tag": "goodbye",
 "responses": ["It was nice speaking to you", "See you later", "Speak soon!"]}
]}
