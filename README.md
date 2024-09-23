Project: Automatic Code Generation using GPT-2 Transformers

Description:
This Python script implements a simple code generation tool where users can input natural language prompts,
and the model will output relevant code based on the description. The script uses the GPT-2 model from the 
HuggingFace Transformers library. It includes a basic user interface built with IPython widgets to allow 
interactive input and display of the generated code.

Technologies:
- Transformers library for working with pre-trained language models
- GPT-2 model for code generation
- IPython widgets for creating an interactive input/output interface in Google Colab
- PyTorch for handling tensor operations and model inference

Key Features:
#1. User-friendly input box to enter natural language descriptions of the code (e.g., "Create a function to add two numbers").
2. GPT-2 generates Python code based on the prompt, with special handling for attention masks and padding.
3. Ensures the model doesn't repeat tokens or produce overly long responses with early stopping and `no_repeat_ngram_size`.
4. Automatically handles padding and truncation for variable-length input sequences.
#5. The generated code is displayed in a clean output box for easy copy-pasting or further modifications.

Usage:
1. Run the script in a Google Colab notebook.
2. Input a natural language prompt in the text box (e.g., "Create a Python function to reverse a string").
3. View the generated Python code in the output section.
Note:
The script uses the GPT-2 model, which is a general-purpose language model. You can experiment with other models
from HuggingFace's model hub, such as specialized models for code generation like Codex or CodeGen.

Save this code to GitHub for future collaboration and version control.
To save the file, use the following command in the terminal:
 git add <filename>.py
  git commit -m "Initial commit: Added code generation tool using GPT-2"
 git push origin main
