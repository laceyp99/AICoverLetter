# AICoverLetter
An AI Cover Letter Generator that saves hours with fast job specific cover letters exported as PDF files. With the new version of the script, there is now a multiple revision functionality. So that way, any issues with formatting or topic focus can be dealt with while running the script and not post-generation. You are able to choose if you would like to revise the generated cover letter with an easy yes or no question prompt after every AI model response. If the user replies yes, the past interactions with the AI (including its response) stays archived in the message list that will be sent to the AI alongside the new revisional prompt inputted by the user. Once the user has specified that they don't have any more revisions, the script will take the most recent version of the cover letter, and export it to a PDF file with a user specified file name.

## Prerequisites

Before running the script, make sure you have the following prerequisites installed:

- Python 3.x
- OpenAI Python library
- `pywin32` (for Windows users)
- `reportlab` (for non-Windows users)

You can install the required Python libraries using pip:

```bash
pip install openai pywin32 reportlab
```

## Getting Started

1. Clone or download the repository to your local machine.

  ```bash
  git clone https://github.com/laceyp99/AICoverLetter.git
  ```
2. Create an OpenAI API key and set it as an environment variable named OPENAI_API_KEY. You can obtain an API key by signing up on the OpenAI platform.
  
3. Prepare your job description and resume text files (job_description.txt and resume.txt) in the project directory.

4. Open a terminal and navigate to the project directory.

5. Run the coverlettergenerator.py script:

  ```bash
  python generate_cover_letter.py
  ```

6. Follow the on-screen instructions to interact with the Cover Letter Generator.

## Pricing
This updated script uses the 'gpt-3.5-turbo' model instead of the original 'text-davinci-003' model. This choice was made to reduce the price rate. Especially since this version archives past prompt and responses to build a conversation that the AI can look back on in order to revise the cover letter, each individual revision requires more tokens than the past. The difference of the models didn't seem to be worth the 10x price rate of tokens.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
This project utilizes the GPT-3.5 Turbo model provided by OpenAI.
It was inspired by the need for automated cover letter generation in job applications.
