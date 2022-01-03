# Jarvis Chat Bot 🤖💬

## What? 💻
A chat bot run through Slack via the Slack API, which allows the user to provide the chatbot with an **output** category or ACTION and then provide **input** phrases or NAMEs. The input and output data will then be placed ubti a Bot run through slack via a .py file. This training logic is all located in jarvis.py written entirely by myself and project teammate Nolan Jimmo, a University of Vermont graduate student. Jarvis.py also includes the calls to insert the data into the databases; however the actual *database code was not written by myself* - it was written entirely by project teammember *Chris O'Neil*, another UVM graduate student. I only included these files to show how the database was created and added to in the context of the chatbot logic. The jarvisDataBase.py file initializes the database and dataInsertion inserts the data typed by the user through the Slack interface.

## Why? 🤔
This was a group project assignment in STAT 287 (Data Science I) at the University of Vermont under Professor James Bagrow. Our project team was team MOUNTAINTIGER. A latter iteration of this project was done which expanded on the chatbot and included a testing mode - this allowed the user to instruct the bot to enter testing mode and then presented **input** phrases (or NAMEs as they are called in the database) wherein the bot would try to predict what category the user was referencing or talking about. This logic was also written by myself and Nolan Jimmo and may be added to this repository (or a separate one) at a later date.