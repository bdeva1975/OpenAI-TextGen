```markdown
# OpenAI Chat Response Generator

This Python script interacts with the OpenAI API to generate text responses based on user input. It utilizes the `openai` package and supports environment variable management via `dotenv`.

## Prerequisites

- Python 3.6 or higher
- `openai` library
- `python-dotenv` library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required packages:

   ```bash
   pip install openai python-dotenv
   ```

3. Create a `.env` file in the root directory and add your OpenAI API key:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage

To run the script, use the following command:

```bash
python temperature.py "Your input text here" temperature_value
```
- Replace `"Your input text here"` with the text you want to send to the OpenAI model.
- Replace `temperature_value` with a float value that controls the randomness of the output (e.g., `0.7`).

### Example

```bash
python temperature.py "What is the capital of France?" 0.7
```

This will generate a response regarding the capital of France with a temperature of `0.7`.

## Code Explanation

- **Environment Variables**: The script uses the `dotenv` package to load the OpenAI API key from a `.env` file.
- **Functionality**: The `get_text_response` function communicates with the OpenAI API to generate a response based on the input content.
- **Execution**: The script executes the function three times and prints the responses.

## Contributing

Feel free to submit pull requests or raise issues if you encounter any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
