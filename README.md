# AICoverLetter
An AI Cover Letter Generator that saves hours with fast job specific cover letters exported as .pdf files.

# Setup
1. You will need to add in your own OpenAI API key to connect to the AI model. This can be found at https://platform.openai.com/account/api-keys.
2. This project pulls from two .txt files that hold the resume and job description. Make sure the .txt files are in the same directory as the code and labelled correctly.
3. Last (optional) step, I included a hard coded header to the cover letter inside the create_word_document function. You can either fill in your contact information within the "ADD A CUSTOM HEADER HERE", or modify the function to add only the AI cover letter to the .docx file.

# Usage Cost
This project is using OpenAI's "DaVinci" fine-tuned model which cost $0.12 per every 1,000 tokens used. The average token usage per cover letter is 1200 tokens due to the length of the input including the resume and job description. I looked into cheaper OpenAI models but the DaVinci model gave the best ouptut for this type of task. If you are looking to make this project more cost effective, I would suggest looking into the other models and thier pricing at https://openai.com/pricing. The GPT-3.5 Turbo model would be my suggestion for a somewhat cheaper model, but the closest in output comparison. You can change the model within the code at line 16. Check out https://platform.openai.com/docs/models/model-endpoint-compatibility for more information about the models.

# Future Improvements
I am looking to improve this project to make the workflow faster and easier. The biggest improvement I'll be working towards is querying the AI with notes to modify the cover letter it generated initially.
