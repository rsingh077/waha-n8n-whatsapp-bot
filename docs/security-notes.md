# Security Notes

- Do not commit real WAHA API keys.
- Do not commit AI provider API keys.
- Do not commit real phone numbers.
- Do not commit n8n credentials.
- Remove `pinData` before pushing n8n workflow exports.
- Use WAHA event `message`, not `message.any`, to reduce loop risk.
- Always filter `fromMe = false` before reply nodes.
- Avoid bulk or cold outreach automation.
- For serious production systems, consider WhatsApp Cloud API.
