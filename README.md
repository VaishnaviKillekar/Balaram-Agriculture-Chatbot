# Balaram-Agriculture-Chatbot
Balaram is an agriculture-based chatbot which answers questions related to farming practices.

Balaram is an interactive chatbot which is trained using agriculture data of India. It uses its own custom-made dataset.
It can accept both text and speech input. 
It is planned to be also incorporate Hindi as an alternate language.

Balaram uses a simple Neural Network to identify intent of the user question.

After the intent is identified, the entities are extracted using a training dataset which Balaram uses to identify cutom entities definde in the dataset.

Based on the intent, Balaram checks if all the necessary entities are provided by the user, if not, then Balaram prompts the user for
additional necessary information to answer the question.

The answer is then fetched from the database using the information provided by the user and is displayed to the user.
