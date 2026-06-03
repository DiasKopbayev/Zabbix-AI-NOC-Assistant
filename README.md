## Zabbix-AI-NOC-Assistant
AI-powered alert analysis and incident summarization for Zabbix.

## Features

- Zabbix Webhook integration
- Local LLM inference via Ollama
- Telegram notifications
- Context-aware alert analysis
- SQLite event history
- Incident summarization
- Fully self-hosted

## Stack

- Python
- FastAPI
- Ollama
- Qwen
- Docker
- Telegram Bot API
- Zabbix
  
## Architecture

Zabbix
  ↓
FastAPI Webhook
  ↓
Ollama
  ↓
Telegram

## Example

Input:
Problem: VPN Tunnel down
Host: Fortigate
Severity: Average

The VPN tunnel on the FortiGate device became unavailable. This may affect connectivity between remote sites or services using this tunnel. Similar events should be monitored for recurrence to identify potential network instability or configuration issues.




