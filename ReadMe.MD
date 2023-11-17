# Automated Question-Answering Script

This Python script automates the process of answering questions using OpenAI's GPT-3.5 model. It reads questions from a CSV file, obtains answers, and then records both questions and their answers in a text file. Additionally, it updates the CSV file to keep track of answered questions.

## Features

- **Read Questions**: Extracts questions from a CSV file.
- **Fetch Answers**: Uses OpenAI's GPT-3.5 model to generate answers for the questions.
- **Write Q&A to Text File**: Saves the questions and their answers in a readable format in a text file.
- **Update CSV**: Marks questions as answered in the CSV file to avoid repetition.
- **User Feedback**: Provides progress updates via styled console messages.

## How to Use

1. **Set Up Your Environment**:
   - Ensure Python is installed on your system.
   - Install necessary packages: `openai`.

2. **API Key**:
   - Obtain an API key from OpenAI.
   - Set the API key in your environment variables as `OPENAI_API_KEY`.

3. **CSV File Format**:
   - Prepare your CSV file with questions. Optionally, include a second column to mark answered questions.

4. **Running the Script**:
   - Place the script in the same directory as your CSV file.
   - Run the script: `python script_name.py`.
   - The script reads questions from `q1.csv` and writes the Q&A to `questions_and_answers.txt`.

5. **Output**:
   - Check `questions_and_answers.txt` for the questions and answers.
   - The CSV file will be updated with a marker for answered questions.

## Prerequisites

- Python
- `openai` Python package
- OpenAI API key

## License

[MIT License](https://opensource.org/licenses/MIT)

## Disclaimer

This script uses OpenAI's GPT-3.5 model, which may incur costs based on usage and API key plan.

---

For more information on OpenAI and its usage policies, please visit [OpenAI's official website](https://openai.com/).
