# IoT Sensor QA 

A **redacted, generic** example of how to test an IoT sensor end‑to‑end (LoRaWAN/MQTT style) without exposing any company IP or customer data.

> This template demonstrates **process and skill** only. All device names, topics, payloads, and URLs are **dummy**.

## What this shows recruiters
- Test plan & KPIs for an IoT device
- MQTT data logging + schema validation
- Simulated device publisher
- Basic automation tests (pytest)
- Clean repo hygiene (.gitignore, MIT license, docs)

## Quick start
```bash
pip install -r requirements.txt
# Terminal 1: run a dummy publisher
python scripts/mqtt_simulator.py

# Terminal 2: run validator tests
pytest -q
```

## Repo structure
```
docs/                # redaction policy, test plan, KPIs
scripts/             # MQTT simulator + validators
tests/               # pytest-based checks
data/                # example payloads (dummy)
```

## Notes
- Default broker is a **public test broker** (HiveMQ). Change it via env vars if needed.
- Replace `DUMMY_*` fields with your own generic names if you want.
