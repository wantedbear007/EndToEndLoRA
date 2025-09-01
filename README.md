# Parameter Efficient Fine Tuning using Transformers and LoRA

# Startup 🚀
1. Startup on your machine locally by running `uv init`
2. Install all the stuff `uv sync`
3. Create samples `uv run syntheticdatageneration.py`
4. Process them `uv run preprocessing.py`
5. Improve quality `uv run dataquality`
6. Transition to RunPod and install uv `pip install uv`
7. Create uv project on RunPod `uv init` 
8. Upload server toml file to runpod `pyproject_use_this_one_on_runpod.toml` (rename it to pyproject.toml once on the server) and sync `uv sync`
9. Copy the data folder and the instructionquality file and train `uv run train.py`
10. Deploy using Ollama and Langflow - shown in vid!

# Who, When, Why?

👨🏾‍💻 Author: Nick Renotte <br />
📅 Version: 1.x<br />
📜 License: This project is licensed under the MIT License </br>
