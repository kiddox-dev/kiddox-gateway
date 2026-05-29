# kiddox-gateway

API Gateway ??Kong/Envoy routing, rate limiting, auth passthrough.

## Tech Stack

- Python 3.11+
- FastAPI + Uvicorn
- Pydantic v2 + pydantic-settings
- Supabase Python client
- structlog for structured logging
- Prometheus client for metrics

## Quick Start

`ash
pip install -e ".[dev]"
uvicorn app.main:app --reload --port 8000
`

## License

Proprietary ??Kiddox Limited
