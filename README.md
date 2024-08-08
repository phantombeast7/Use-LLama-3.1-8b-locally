# AI Chat and Document Retrieval System

This repository contains two Jupyter notebooks demonstrating different aspects of working with language models and semantic search. These notebooks are designed to be run in Google Colab.

## Notebooks

- [Chat_with_LLama_3.1_8B.ipynb](#chat-with-llama-31-8b-notebook)
- [Custom_Dataset(CSV).ipynb](#custom-datasetcsv-notebook)

## Chat_with_LLama_3.1_8B.ipynb

This notebook provides an interactive chat interface with the LLaMA 3.1 8B language model.

### Overview

- **Installation**: Installs necessary libraries (`bitsandbytes`, `accelerate`, `transformers`).
- **Authentication**: Authenticates with Hugging Face to access the model.
- **Interactive Chat**: Sets up an interactive chat where you can input messages and receive responses from the LLaMA model.

### How to Use in Colab

1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Clone the Repository**:
   - Paste the following command into a new Colab cell and run it:
     ```python
     !git clone https://github.com/phantombeast7/Use_LLama-3.1-8b-locally.git
     ```

3. **Navigate to the Notebook**:
   - On the left-hand side, click on the `Files` tab.
   - Open the `Use_LLama-3.1-8b-locally` folder that appears.
   - You will see the `Chat_with_LLama_3.1_8B.ipynb` notebook. Click on it to open.

4. **Run the Notebook**:
   - Follow the instructions within the notebook to authenticate and start the interactive chat.

## Custom_Dataset(CSV).ipynb

This notebook demonstrates integrating semantic search with the LLaMA model using a custom CSV dataset.

### Overview

- **Installation**: Installs necessary packages (`bitsandbytes`, `accelerate`, `transformers`, `sentence-transformers`).
- **Dataset**: Loads and preprocesses a CSV file containing documents.
- **Semantic Search**: Uses Sentence-BERT for semantic search to retrieve relevant documents.
- **Summarization**: Summarizes the retrieved documents.
- **Enhanced Chat**: Combines summarized documents with LLaMA model responses for a richer conversational experience.

### How to Use in Colab

1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Clone the Repository**:
   - Paste the following command into a new Colab cell and run it:
     ```python
     !git clone https://github.com/phantombeast7/Use_LLama-3.1-8b-locally.git
     ```

3. **Navigate to the Notebook**:
   - On the left-hand side, click on the `Files` tab.
   - Open the `Use_LLama-3.1-8b-locally` folder that appears.
   - You will see the `Custom_Dataset(CSV).ipynb` notebook. Click on it to open.

4. **Update Paths and Configuration**:
   - Modify the `csv_path` variable in the notebook to point to your CSV file. You can upload the file directly to Colab using the file upload option.

5. **Run the Notebook**:
   - Follow the instructions in the notebook to load the dataset, perform semantic search, and use the enhanced chat functionality.

## Notes

- **GPU Availability**: Google Colab provides free access to GPUs, which can accelerate model inference. Make sure to enable GPU support in Colab by navigating to `Runtime` > `Change runtime type` > `Hardware accelerator` and selecting `GPU`.

- **Hugging Face Authentication**: In the `Chat_with_LLama_3.1_8B.ipynb` notebook, you will be prompted to log in to Hugging Face. Follow the instructions to authenticate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute or open issues if you encounter any problems or have suggestions for improvements.
