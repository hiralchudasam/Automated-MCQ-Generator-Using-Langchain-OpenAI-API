# Automated MCQ Generator Using Langchain & OpenAI API

This project is an **Automated Multiple Choice Question (MCQ) Generator** that leverages the power of [Langchain](https://github.com/hwchase17/langchain) and the [OpenAI API](https://platform.openai.com/docs/api-reference) to generate high-quality MCQs from any input text. The solution includes a simple and interactive [Streamlit](https://streamlit.io/) web application for user-friendly operation.

---

## Features

- 📝 **Automatic MCQ Generation:** Instantly generate MCQs from any text input.  
- 🤖 **Powered by OpenAI & Langchain:** Utilizes advanced language models for question creation.  
- 🌐 **Streamlit Web App:** Easy-to-use interface for uploading text and viewing generated MCQs.  
- 📦 **Modular Codebase:** Organized for easy extension and integration.

---



## Getting Started

### Prerequisites

- Python 3.8 or higher  
- An [OpenAI API key](https://platform.openai.com/account/api-keys)

### Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/hiralchudasam/Automated-MCQ-Generator-Using-Langchain-OpenAI-API.git
    cd Automated-MCQ-Generator-Using-Langchain-OpenAI-API
    ```

2. **Install dependencies:**

    ```
    pip install -r requirements.txt
    ```

3. **Set up your OpenAI API key:**

    - Export your API key as an environment variable:

      ```
      export OPENAI_API_KEY='your-api-key-here'
      ```

    - Or add it in your code where required.

---

## Demo
![Screenshot (1013)](https://github.com/user-attachments/assets/9e86e4b4-b046-4720-b164-368dcb224782)

![Screenshot (1014)](https://github.com/user-attachments/assets/12e422e6-5920-4ae0-bac4-ae26a0b5df76)

![Screenshot (1023)](https://github.com/user-attachments/assets/806ca507-c27b-4fd3-9818-a3ba68165208)

![Screenshot (1025)](https://github.com/user-attachments/assets/114031d3-6c08-4daa-9fd3-5e3dc3976b9f)

![Screenshot (1026)](https://github.com/user-attachments/assets/ba49f62f-d297-410e-bf48-abf4f8f6c39b)

---

## Usage

### Run the Streamlit App


- Open your browser and go to the local URL provided by Streamlit (typically `http://localhost:8501`).  
- Upload or paste your input text.  
- Click the button to generate MCQs and view the results instantly.

---

## Project Structure

Automated-MCQ-Generator-Using-Langchain-OpenAI-API

- `experiment/` - Experimental scripts and notebooks  
- `logs/` - Log files  
- `mcqgenrator.egg-info/` - Python package metadata  
- `src/` - Source code for MCQ generation  
- `.gitignore` - Git ignore file  
- `README.md` - Project documentation  
- `Response.json` - Sample output data  
- `StreamlitAPP.py` - Streamlit web application  
- `data.txt` - Sample input text  
- `requirements.txt` - Python dependencies  
- `setup.py` - Setup script for packaging  
- `test.py` - Test scripts  



---

## Customization

- **Change the input text:** Edit `data.txt` or use the Streamlit app to input your own text.  
- **Modify MCQ generation logic:** Update code in the `src/` directory to customize how questions are generated.  
- **Switch models or prompts:** Adjust the Langchain or OpenAI API parameters as needed.

---

## Contributing

Contributions are welcome!  
Feel free to open issues or submit pull requests for improvements, new features, or bug fixes.

---

