# Version 3 Beta: AI Cover Letter Generator

Welcome to Version 3 Beta of our AI Cover Letter Generator! This version utilizes the cutting-edge GPT4Turbo model along with beta OpenAI assistants and threads API.

## Features

- **GPT4Turbo Model:** This version leverages the GPT4Turbo model, offering enhanced capabilities for generating more sophisticated and context-aware cover letters.
- **Beta Assistants and Threads API:** Utilizing the beta features of the OpenAI assistants and threads API, this version explores advanced functionalities for improved performance.

## Usage

### Dependencies

Ensure you have the following dependencies installed:

- **Python Libraries:**
  - `os`
  - `json`
  - `time`
  - `re`
  - `docx`
- **OpenAI Python Package:** Install the OpenAI Python package to interact with the OpenAI API.

### Installation

1. **Clone Repository:** Clone this repository to your local machine.
2. **Install Dependencies:** Install the required Python libraries listed above.
3. **Setup OpenAI API Key:**
   - Obtain a working OpenAI API key.
   - Save the API key as an environment variable.
4. **Prepare Files:**
   - Copy the intended resume and job description into the same directory as the script.
   - Ensure to update the file names in the code to match the ones you copied.

### Running the Script

To generate a cover letter, follow these steps:

1. **Open Terminal/CMD:** Navigate to the directory containing the script.
2. **Run the Script:** Execute the script via the terminal by entering the command.
3. **Follow Instructions:** The script will prompt you for necessary inputs, such as prompts or options, to generate the cover letter.
4. **Check Output:** Once the process is complete, the generated cover letter will be available as per the script's instructions.

### Potential Issues

- **File Retrieval Challenges:** Occasionally, there might be issues with file retrieval. If the model fails to retrieve files, try prompting it again by providing a statement such as "Yes you do have the files". In many cases, this prompt re-initiates the retrieval process, resulting in the proper response.

## Important Notes

- **Beta Version:** Version 3 Beta is an experimental release using advanced AI capabilities. Expect occasional quirks or challenges.
- **Community Feedback:** Your feedback is invaluable! Feel free to report issues, share suggestions, or contribute improvements by creating pull requests or filing issues in the `v3_beta` folder.

This beta version explores the potential of GPT4Turbo and beta API features. We appreciate your participation in testing and refining this advanced cover letter generator.
