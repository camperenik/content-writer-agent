# Content Writer Agent

This repository contains an AI-based content writer application built using Python. The application leverages the power of [LangChain](https://github.com/hwchase17/langchain) and [LangGraph](https://github.com/langgraph/langgraph) frameworks, with a locally hosted AI model using [Ollama](https://ollama.com/) to generate high-quality content.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Automated Content Generation**: Generate blog posts, articles, and other content based on prompts and guidelines.
- **Local AI Model**: Uses a locally hosted AI model via Ollama for content generation, ensuring data privacy and control.
- **Framework Integration**: Built with LangChain for managing prompts and interactions, and LangGraph for visualizing the language model's decision process.
- **Customizable**: Easily configure prompts, tone, style, and content structure to meet specific requirements.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ai-content-writer.git
   cd ai-content-writer
   ```

2. **Set up a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
   
   Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
4. **Set up Ollama:**

   - Download and install the Ollama AI model locally following the instructions on the [Ollama website](https://ollama.com/).
   - Ensure the Ollama server is running before starting the application.
   
## Usage

1. **Run the application:**
   
   ```bash
   python main.py
   ```
   
2. **Generate Content:**
   
   - The application will prompt you to enter the content guidelines, such as the topic, tone, style, and length.
   - Once the input is provided, the AI model will generate the content based on the given parameters.

3. **View and Edit:**
   
   Review the generated content directly in the terminal or export it to a text file for further editing.

## Configuration

- Prompt Configuration: Modify the prompt templates in `config/prompts.yaml` to customize how the AI generates content.
- Model Settings: Adjust the model parameters in the `config/model_config.yaml` file to fine-tune the AI's output.

## Contributing
   
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

