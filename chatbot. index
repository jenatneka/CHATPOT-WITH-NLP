import random
import nltk
from nltk.chat.util import chat, reflections 

nltk.download('punkt')
pairs =[
    [
        r"my name is (.*)",
        ["  Hello %1,nice to meet you!",]
    ],
    [
        r"What is your name?",
        ["I'm a chatbot, created by you!",]
    ],
    [
        r"how are you?",
        ["I'm an AI, so I don't have feelings, but I'm here to chat!",]
    ],
    [
        r"sorry (.*)",
        ["No problem!", "It is okay!" ,"Dont worry about it!",]
    ],
    [
        r"bye|goodbye",
        ["Goodbye!","Take care!","See you soon!"]
    ],
    [
        r"(.*)",
        ["That is interesting!","Tell me more!","I see....","Could you elaborate on that?"]

    ]

    ]

chatbot = chat(pairs,reflections)

print("Hello! I'm a chatbot. Type 'bye' to exit.")
    
