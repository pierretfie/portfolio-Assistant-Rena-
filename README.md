# Integrating Rena (AIAS) into a Portfolio

Adding an AI assistant to a website helps visitors:
- Get more out of the page
- Understand products and services better
- Find answers to common questions about the owner or company

This integration uses an n8n workflow featuring **Rena**, a digital AI assistant, embedded in a personal professional portfolio.

## Features
- Guide visitors through the site
- Provide more information about the owner
- Push chats or communications to a personal email inbox

## How It Works
- The portfolio triggers an n8n workflow.
- The workflow routes messages to Rena (AIAS) and returns responses to the site.
- Selected conversations can be forwarded to email.
 <img width="1046" height="511" alt="Screenshot From 2025-08-29 07-33-05" src="https://github.com/user-attachments/assets/d6be610b-3581-4f8a-ae76-9cfb30fc3077" />

## Prerequisites (if you want to replicate)
- n8n instance (self-hosted or cloud)
- API keys/credentials for your LLM/provider
- Deployment target for the portfolio (e.g., Vercel)

## Setup (high level)
1. Configure your n8n workflow for message intake, AI response, and email forwarding.
2. Expose an endpoint (or webhook) from n8n.
3. Connect the portfolio front end to the n8n endpoint.
4. Deploy and test end-to-end.

## Privacy & Data
- User messages may be processed by third-party AI services.
- Do not include sensitive personal information in chats.
- Review and comply with your data retention and provider policies.

## Live Demo
Visit the portfolio to interact with the integration:
- [portfolio with AIAS integration](https://shadow-slick-portfolio.vercel.app/)
