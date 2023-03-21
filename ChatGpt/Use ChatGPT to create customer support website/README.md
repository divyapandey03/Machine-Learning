# Introduction:

![chatgpt](https://user-images.githubusercontent.com/23255126/226502504-8ae61391-eea2-4db3-a1f0-e3c955023d39.jpg)

ChatGPT is an AI language model developed by OpenAI that uses transformer architecture for text generation. It was trained on a massive dataset of text and can comprehend contextual information to generate accurate responses. It has multiple use cases and can be customized for specific requirements. Its API can be integrated into applications for text generation.

![01_asking-chatgpt-to-create-an-outline-for-a-sales-presentation](https://user-images.githubusercontent.com/23255126/226496017-2e51b86e-a463-47d7-ad60-eb3ebee68d04.png)



## Installation Steps:

- Setup Google Cloud Environment:
<img width="948" alt="image" src="https://user-images.githubusercontent.com/23255126/226478784-e59a99fd-c85f-4475-bc65-4c8d307404c5.png">


- Ubuntu:
  - python3 -m venv venv
  - . ./venv/bin/activate
  -  pip install -r requirements.txt

- Create .env hidden file and add your OpenAI API key to the file.

   OPENAI_API_KEY=<<YOUR_API_KEY>>      # You just need to fill in your API key from https://beta.openai.com/account/api-keys

- Edit chatgpt.py and replace <<PUT THE PROMPT HERE>> with your prompt:

e.g. Create a simple AI Health assistant

INSTRUCTIONS = """You are an AI assistant that is an expert in Health and wellness.
You know about nutrition, exercise, stress management , sleep, mental health, substance use, and prevention.
You can advise on nutrition, exercise, stress management, sleep, mental health, substance use, and prevention.
If you cannot answer a question, please respond with the phrase, " I'm just a simple Health and Wellness; I can't help with that."
Do not use any external URLS in your answers. Do not refer to any blogs in your answers.
Format any lists on individual lines with a dash and a space in front of each item."""
  
  - Execute the Code:
    - ./venv/bin/activate
     - python chatgpy.py
   
   
  <img width="422" alt="a2" src="https://user-images.githubusercontent.com/23255126/226488040-996c9fa3-07f6-4f29-a8a0-dfc912c43276.png">
   
## Output:
   
   
<img width="960" alt="a1" src="https://user-images.githubusercontent.com/23255126/226487984-7fada395-a754-4d91-bf55-04d966d7740f.png">
   
   
   
<img width="674" alt="g7" src="https://user-images.githubusercontent.com/23255126/226488503-5777a1c9-2dfd-46f6-8de4-87f29fcdfaad.png">

# Google Drive Link: https://docs.google.com/presentation/d/17QmLqcvDQTzKf4MKjmaXi9qBL-po_j--/edit#slide=id.p1
