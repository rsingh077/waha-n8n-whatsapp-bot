# WAHA + n8n WhatsApp AI Lead Agent

A WhatsApp automation starter workflow built with WAHA, n8n, MongoDB, and an AI lead parser.

This project demonstrates a production-style WhatsApp lead qualification system for agencies and service businesses.

## Features

- WhatsApp webhook intake using WAHA
- n8n workflow automation
- Menu-based service selection
- AI lead qualification
- MongoDB session and lead storage
- Admin WhatsApp lead notification
- Client auto-reply flow
- `@lid` to `@c.us` conversion support
- Reply-loop safety notes

## Use Cases

- WhatsApp lead qualification bot
- Agency service inquiry automation
- AI automation business intake
- Website development inquiry bot
- CRM/dashboard inquiry bot
- Cybersecurity audit inquiry bot
- WhatsApp bot automation demo

## Workflow

WhatsApp User  
→ WAHA  
→ n8n Webhook  
→ LID to phone conversion  
→ Session check  
→ Menu/service routing  
→ AI lead parsing  
→ MongoDB lead save  
→ Admin notification  
→ Client reply

## Files

- `workflows/whatsapp-menu-bot.example.json` — sanitized n8n workflow export
- `.env.example` — example environment variables
- `docs/security-notes.md` — safety and production notes

## Important

This repository uses placeholder values. Replace these in your own private n8n workflow:

- `YOUR_WAHA_API_KEY`
- `YOUR_SERVER_IP`
- `YOUR_CEREBRAS_API_KEY`
- `YOUR_AI_API_KEY`
- `91XXXXXXXXXX@c.us`
- `https://your-n8n-domain.com/webhook/waha-incoming`

Never commit real API keys, phone numbers, webhook URLs, or credentials.

## Author

Built by Rajveer Singh / TechExon.

GitHub: https://github.com/rsingh077  
Website: https://techexon.app
