# 6-Agent Paper Trading System

A complete, production-ready paper trading system implementing the 6-agent architecture:

```
🔍 Scanner → 🛡️ Rug Checker → 📊 Position Sizer → ⚡ Executor → 📝 Trade Logger → 📈 Equity Tracker
```

## Features

- **Full agent pipeline** with message bus communication
- **Real-time dashboard** with WebSocket updates
- **Paper trading only** - no real money at risk
- **Configurable risk parameters**
- **Trade audit trail** with JSONL logging
- **REST API** + WebSocket for dashboard integration
- **CLI interface** for interactive monitoring

## Quick Start

```bash
pip install -r requirements.txt
python main.py
```

Run with dashboard:
```bash
python run.py both
```
Then open http://localhost:8080 in your browser.
