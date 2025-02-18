# MemoryChatBot - Environmental Setup

1. Install python 3.8 or higher
2. Must have OpenAI API Key
3. Preferred IDEs (VSCode)
4. Create a python virtual environment
    python -m venv env

    # Activate the virtual environment
    # On Windows
    .\env\Scripts\activate

    # On macOS/Linux
    source env/bin/activate

    # Deactivate
    deactivate
5. Optional - Upgrade pip
    pip install --upgrade pip
6. Install these 3 python packages / libraries:
    pip install openai
    pip install langchain
    pip install (opt - U) langchain_community
    pip install streamlit
    **Shortcut: pip install streamlit langchain langchain-community openai
7. Import these necessary libraries to your .py file
    Include (Import os)
    **In .py file: os.environ["OPENAI_API_KEY"] = api_key
8. Optional - Using a Requirements File (to manage your project dependencies)
    pip freeze > requirements.txt
    pip install -r requirements.txt
9. Execute app command:
    streamlit run app.py
