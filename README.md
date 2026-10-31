# AgentDesk backend

FastAPI backend. Cloud service entry point: `uvicorn app.cloud_main:app --host 0.0.0.0 --port $PORT`
(build: `pip install -r requirements-cloud.txt`). Secrets are set as environment variables, never committed.
