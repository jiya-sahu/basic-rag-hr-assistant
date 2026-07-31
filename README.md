# Basic RAG HR Assistant

This repository contains a simple Retrieval-Augmented Generation (RAG) proof-of-concept for HR assistance. The project includes a Jupyter notebook, environment configuration, and required Python packages.

## Project Structure

- `rag.ipynb` - Notebook for exploring RAG workflows and building the assistant.
- `rag.py` - Main Python script placeholder for the application logic.
- `requirements.txt` - Python package dependencies.
- `data/hr_policy.txt` - Example HR policy source text for retrieval.
- `basicragenv/` - Local virtual environment used for the project.

## Setup

1. Open a terminal in the project root:
   ```powershell
   cd d:\rag-hr-assistant
   ```
2. install uv package
    ```
    powershell
    pip install uv 
    ``` 
3. Create the virtual environment with `uv` (if not already created):
   ```powershell
   uv venv basicragenv
   ```

4. Activate the virtual environment:
   ```powershell
   .\basicragenv\Scripts\activate
   ```

5. Install dependencies:
   ```powershell
   uv pip install -r requirements.txt
   ```

## Requirements

- Python 3.11+ (or a compatible Python 3 version)
- `uv` for virtual environment creation
- packages listed in `requirements.txt`

## Usage

- Run the notebook:
  ```powershell
  jupyter notebook rag.ipynb
  ```

- If `rag.py` is implemented, you can run it directly:
  ```powershell
  python rag.py
  ```

## Notes

- The project currently includes the package dependencies needed for working with LangChain, FAISS, Streamlit, and Jupyter.
- Update `rag.py` and `rag.ipynb` to add your own HR retrieval and answer generation logic.

## License

This repository is provided as-is. Update the license section if you add one.
