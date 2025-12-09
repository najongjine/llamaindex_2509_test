py -3.10 -m uv venv venv

.\venv\Scripts\Activate.ps1

uv pip install -r requirements.txt

uv run python llamaindex_test.py
