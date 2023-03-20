

# Installation Steps:

- Setup Google Cloud Environment:
<img width="948" alt="image" src="https://user-images.githubusercontent.com/23255126/226478784-e59a99fd-c85f-4475-bc65-4c8d307404c5.png">


- Ubuntu:
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt

- Create .env hidden file and add your OpenAI API key to the file.

   OPENAI_API_KEY=<<YOUR_API_KEY>>

- Edit chatgpt.py and replace <<PUT THE PROMPT HERE>> with your prompt:

e.g. Create a simple AI Health assistant

INSTRUCTIONS = """You are an AI assistant that is an expert in alcoholic beverages.
You know about cocktails, wines, spirits and beers.
You can provide advice on drink menus, cocktail ingredients, how to make cocktails, and anything else related to alcoholic drinks.
If you are unable to provide an answer to a question, please respond with the phrase "I'm just a simple barman, I can't help with that."
Please aim to be as helpful, creative, and friendly as possible in all of your responses.
Do not use any external URLs in your answers. Do not refer to any blogs in your answers.
Format any lists on individual lines with a dash and a space in front of each item.
  
  - Execute the Code:
    . ./venv/bin/activate
     python chatgpy.py
