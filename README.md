# Balaram-Agriculture-Chatbot
Balaram is an agriculture-based chatbot which answers questions related to farming practices.

Balaram is interactive and is trained using agriculture data of India from various datasets. It uses its own custom-made dataset for certain questions' answers. We expect to also make it work by further extracting answers from the web, if it can't be found in its database.
It can accept both text and speech input. 
It can be further developed to also incorporate Hindi as an alternate language.

Balaram uses a simple Neural Network to identify intent of the user question.

After the intent is identified, the entities are extracted using a training dataset which Balaram uses to identify custom entities defined in the dataset.

Based on the intent, Balaram checks if all the necessary entities are provided by the user, if not, then Balaram prompts the user for additional necessary information to answer the question.

The answer is then fetched from the database using the information provided by the user and is displayed to the user.
