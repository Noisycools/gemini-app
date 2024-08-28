Set up a Python virtual environment
Create a virtual environment on top of the existing Python installation, so that any packages installed in this environment are isolated from the packages in the base environment. When used from within a virtual environment, installation tools such as pip will install Python packages into the virtual environment.

To create the Python virtual environment, from within the gemini-app folder, run the command:
```bash
python3 -m venv gemini-streamlit
```

Activate the Python virtual environment:
```bash
source gemini-streamlit/bin/activate
```
