# MultiFormat-Interpreter
The MultiFormat Interpreter project involves developing a Python script to automate the extraction of content from various file types such as PDF, TXT, CSV, JSON, and XLSX. This script leverages libraries like `PyPDF2` for PDFs, `pandas` for CSV and Excel files, and `json` for JSON files to read and process the content. The user interacts with the script by providing the file path and a prompt for code generation. This uses the GPT-4All model to generate code based on the extracted content and the user’s prompt.

## GPT-4ALL
The GPT-4All model is a variant of the GPT (Generative Pre-trained Transformer) architecture designed to handle a wide range of natural language processing tasks. Developed by Anthropic, GPT-4All aims to be a versatile tool for generating text across various domains, including code generation, text completion, translation, and more. It builds upon advancements in transformer-based models and is tailored to support applications requiring nuanced understanding and generation of human-like text.
![](https://storage.googleapis.com/gweb-research2023-media/original_images/22bf59cc5a1f2256b0c458250f076d58-USP.gif)
Key features of the GPT-4All model are:
1. **Local Operation:** GPT-4All operates locally without needing API calls or GPUs, enhancing accessibility and reducing reliance on cloud services.
2. **Offline Capability:** Once downloaded, GPT-4All works offline, ensuring users can access AI-powered text generation tools even without internet connectivity.
3. **Versatile Applications:** The model supports various tasks like natural language understanding, text generation, and summarization across different domains and languages.
4. **User-Friendly Interface:** Designed for ease of use, GPT-4All offers an intuitive interface for inputting prompts and receiving text outputs efficiently.
5. **Privacy and Security:** Operating locally ensures data privacy and security compliance, crucial for handling sensitive information.
6. **Customization:** Users can customize GPT-4All for specific tasks, enhancing its adaptability to different applications.
7. **Continual Updates:** Anthropic provides regular updates and support, ensuring ongoing improvements for enhanced performance and usability.

Dowmload GPT_4ALL: [click here](https://github.com/nomic-ai/gpt4all?tab=readme-ov-file)

To know about Llama.cpp: [click here](https://github.com/ggerganov/llama.cpp)

## Objectives:
File Content Extraction: The script should be able to read and extract text content from various file formats including PDF, TXT, CSV, JSON, and XLSX.
Code Generation: Using the extracted content and a user-provided prompt, the script should generate code utilizing the GPT-4All model.

## Features:
1. __File Type Support:__
  
    - PDF: Extracts text from PDF documents using the PyPDF2 library.
    - TXT: Reads text files directly.
    - CSV: Reads and converts CSV file content to a string format using the pandas library.
    - JSON: Reads and pretty-prints JSON data.
    - XLSX: Reads and converts Excel file content to a string format using the pandas library.

2. __User Interaction:__
  
    - Prompts the user to enter the path to the file they wish to process.
    - Displays the content of the selected file.
    - Asks the user for a prompt to guide the code generation.

3. __Code Generation:__
  
    - Uses the GPT-4All model to generate code based on the combined input of file content and user prompt.
    - Outputs the generated code for the user.

## Workflow:
1. __User Input:__
    - The user provides the path to a file.
    - The user inputs a prompt for code generation.
2. __Content Reading:__
    - The script reads the file content based on its type.
    - The content is displayed to the user.
3. __Prompt Handling:__
    - The script combines the file content with the user prompt to create a comprehensive input for the GPT model.
4. __Code Generation:__
    - The GPT-4All model processes the input and generates relevant code.
    - The generated code is displayed to the user.
  
## Prerequisites:
- Python 3.x
- Required libraries: PyPDF2, pandas, json, gpt4all

## Installation:
- Clone the repository:

      git clone https://github.com/Ayushverma135/MultiFormat-Interpreter.git
      cd MultiFormat-Interpreter

- Install required Python libraries:

  - Ensure that the required libraries (PyPDF2, pandas, gpt4all) are imported at the beginning of the notebook.
  - If not already installed, install the libraries directly in a code cell at the beginning of the notebook:

        !pip install PyPDF2 pandas gpt4all
## Usage:
- Open and Run the Notebook:
  - Open the Google Colab notebook `MultiFormat Interpreter.ipynb ` in your browser.
  - Run each cell sequentially to execute the script.

## Contributing
Contributions to enhance or fix issues in the Google Colab notebook are welcome! Please fork the repository and submit pull requests for any improvements.
