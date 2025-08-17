# WiChat


**WiChat** (Worldbank Ideas Chatbot) is a conversational AI application built with KivyMD and LangChain, designed to answer questions about the Worldbank Ideas Project. It features a chatbot UI, speech-to-text, and RAG (Retrieval-Augmented Generation) using OpenAI and HuggingFace Embedding models. It also has a version built with Gradio. 
Interact with the Gradio app [here](https://huggingface.co/spaces/PeaceUdoka/Wichat)

---

## Features

- KivyMD Design chat interface (and Gradio)
- Retrieval-Augmented Generation (RAG) with LangChain and Openai
- Speech-to-text (microphone input)
- User authentication screens (Login/Signup)
- Theme toggling and chat customization

---

## Installation

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/WiChat.git
cd WiChat
```

### 2. Create and Activate a Virtual Environment

**Windows:**
```sh
python -m venv venv
.\venv\Scripts\activate
```

**macOS/Linux:**
```sh
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

---

## Setup

1. **OpenAI API Key:**  
   Set your OpenAI API key as an environment variable:

   ```sh
   set OPENAI_API_KEY=your_openai_api_key   # Windows
   export OPENAI_API_KEY=your_openai_api_key # macOS/Linux
   ```

   Or uncomment and set it in the code (NOT RECOMMENDED):

   ```python
   # os.environ['OPENAI_API_KEY'] = "your_openai_api_key"
   ```

2. **Data Directory:**  
   Place your `.txt` documents in the scraped_data folder.  
   These documents will be used for retrieval.

3. **Assets:**  
   Ensure logo image (Wichat2.png) is present in the project root or update the path in the .py file.

---

## Running the App

```sh
python Wichat.py
```

The app will launch with a splash screen, then show the main chat interface.

---

## Usage

- **Chat:** Type or use the microphone to ask questions about the Worldbank Ideas Project.
- **Login/Signup:** Use the account button to view the authentication screens. For now, there is no actual authentication for login or signup. Just the UI interface.
- **Theme/Customization:** Use the menu to toggle theme, clear chat, or change card color.
  
View other deliverables for this project [here](https://drive.google.com/drive/folders/182DL1ZoX52TDPWfu53xujONm-OQdyT_7?usp=drive_link). Like the chatbot workflow, UI mockup designs, etc.
---


- **Missing Dependencies:**  
  Ensure all required packages are installed and your Python version is 3.8 or higher.

---

## Acknowledgements

The members of Group 2 WorldBank IDEAS AI trainees who worked hard to make this project a success.

---

**Contributions are welcome!**  
