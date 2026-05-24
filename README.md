# genai-learning-journey

A concise, hands-on collection of notebooks and experiments exploring Generative AI with Python — focused on Google Gemini API, retrieval-augmented generation (RAG), LangChain workflows, and integrations for learning and prototyping.

**Overview**
- **Goal:** Document practical examples, patterns, and small projects that help learn and prototype GenAI ideas quickly.
- **Audience:** Python developers, ML practitioners, and learners who want runnable examples and notebook-based experiments.

**Contents**
- `01-gemini-api/` – Notebooks demonstrating usage of the Gemini API and simple study-assistant prototypes:
  - [01-gemini-api/01_gemini_api_basics.ipynb](01-gemini-api/01_gemini_api_basics.ipynb) — Gemini API basics, request/response examples.
  - [01-gemini-api/02_personality_based_study_assistant.ipynb](01-gemini-api/02_personality_based_study_assistant.ipynb) — Build a personality-driven study assistant.
  - [01-gemini-api/03_gradio_study_assistant.ipynb](01-gemini-api/03_gradio_study_assistant.ipynb) — Interactive Gradio front-end for the assistant.
  - [01-gemini-api/04_gradio_study_assistant_deployment.ipynb](01-gemini-api/04_gradio_study_assistant_deployment.ipynb) — Deployment notes and examples for the Gradio app.

**Prerequisites**
- Python 3.9+ recommended.
- Install Jupyter or JupyterLab to run the notebooks.
- If you plan to run Gemini API examples, obtain the appropriate API credentials and set them as environment variables (e.g. `GOOGLE_API_KEY`, `GOOGLE_APPLICATION_CREDENTIALS`, or other keys depending on the library used).

**Quickstart**
1. Create and activate a virtual environment:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	```
2. Install minimal tools:
	```powershell
	pip install --upgrade pip
	pip install jupyterlab pandas requests gradio
	```
3. Start JupyterLab and open the notebooks:
	```powershell
	jupyter lab
	```

Notes: If you want a frozen dependency list, create a `requirements.txt` from your environment (`pip freeze > requirements.txt`) and share it here.

**Running the Notebooks**
- Open the notebook you want in JupyterLab and run cells sequentially.
- Provide API keys or credentials before running cells that call external services.
- For the Gradio notebooks, run the notebook cell that launches the app and follow the local URL it prints.

**Contributing**
- Improvements, additional notebooks, or corrections are welcome. Open a PR with a short description of the change.

**License**
- See the repository `LICENSE` for details.

---
*If you'd like, I can add a `requirements.txt`, example `.env` template, or a short CONTRIBUTING guide next.*
