# Virtual env creation
python -m venv env

# Virtual env starting
.\env\Scripts\activate

# Virtual env stop
deactivate

# Saving dependencies in txt file
pip freeze > requiremenst.txt

# Load dependencies from txt file
pip install -r requirements.txt
