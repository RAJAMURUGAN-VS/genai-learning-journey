# genai-learning-journey

A concise, hands-on collection of notebooks and experiments exploring Generative AI with Python — focused on Google Gemini API, Groq API, retrieval-augmented generation (RAG), LangChain workflows, and integrations for learning and prototyping.

**Overview**
- **Goal:** Document practical examples, patterns, and small projects that help learn and prototype GenAI ideas quickly.
- **Audience:** Python developers, ML practitioners, and learners who want runnable examples and notebook-based experiments.

**Contents**
- `01-gemini-api/` – Notebooks demonstrating usage of the Gemini API and simple study-assistant prototypes:
  - [01-gemini-api/01_gemini_api_basics.ipynb](01-gemini-api/01_gemini_api_basics.ipynb) — Gemini API basics, request/response examples.
  - [01-gemini-api/02_personality_based_study_assistant.ipynb](01-gemini-api/02_personality_based_study_assistant.ipynb) — Build a personality-driven study assistant.
  - [01-gemini-api/03_gradio_study_assistant.ipynb](01-gemini-api/03_gradio_study_assistant.ipynb) — Interactive Gradio front-end for the assistant.
  - [01-gemini-api/04_gradio_study_assistant_deployment.ipynb](01-gemini-api/04_gradio_study_assistant_deployment.ipynb) — Deployment notes and examples for the Gradio app.
- `02-groq-api/` – Notebooks demonstrating Groq API usage, tool calling, and a weather agent workflow:
  - [02-groq-api/01_groq_llama_basics.ipynb](02-groq-api/01_groq_llama_basics.ipynb) — Groq and Llama model basics with example requests.
  - [02-groq-api/02_weather_api_tool.ipynb](02-groq-api/02_weather_api_tool.ipynb) — Build a weather API tool for agent workflows.
  - [02-groq-api/03_function_calling_weather_assistant.ipynb](02-groq-api/03_function_calling_weather_assistant.ipynb) — Add function calling to a weather assistant.
  - [02-groq-api/04_complete_function_calling_workflow.ipynb](02-groq-api/04_complete_function_calling_workflow.ipynb) — End-to-end function-calling workflow for the weather assistant.
  - [02-groq-api/05_gradio_weather_agent.ipynb](02-groq-api/05_gradio_weather_agent.ipynb) — Gradio-based weather agent interface.

**Prerequisites**
- Python 3.9+ recommended.
- Install Jupyter or JupyterLab to run the notebooks.
- If you plan to run Gemini API examples, obtain the appropriate API credentials and set them as environment variables (e.g. `GOOGLE_API_KEY`, `GOOGLE_APPLICATION_CREDENTIALS`, or other keys depending on the library used).
- If you plan to run Groq API examples, obtain your Groq API key and set it as an environment variable such as `GROQ_API_KEY`.

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
