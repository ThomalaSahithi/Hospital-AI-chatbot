# Hospital AI Chatbot

## Project Overview
Hospital AI Chatbot is a web-based chatbot built using n8n and AI to handle general hospital enquiries. It provides users with information and support through a simple website interface.

## Features
- **Appointment Enquiries:** Provides general appointment information.
- **Doctor Information:** Displays sample doctor details and specialties.
- **Billing Enquiries:** Provides sample billing information and fees.
- **Technical Support:** Offers guidance for website and login issues.
- **Human Assistance:** Guides users on contacting hospital support.
- **General Questions:** Responds to general user enquiries.
- **Emergency Keyword Check:** Uses an IF node to identify selected emergency-related phrases.
- **AI-Based Routing:** Uses an AI model to classify enquiries and a Switch node to route them.
- **Data Filtering:** Uses a Filter node to exclude inactive sample doctor records.
- **Website Integration:** Connects the chatbot to a website using the n8n Chat Trigger.

## Technologies Used
- n8n
- OpenAI Chat Model
- HTML
- CSS
- JavaScript
- GitHub
- Vercel

## Workflow
The n8n workflow uses Chat Trigger, Edit Fields, IF, Basic LLM Chain, OpenAI Chat Model, Switch, Filter, and Code nodes to process enquiries and generate responses.

## Website
https://hospital-ai-chatbot-beta.vercel.app/

## Note
This project uses fictional sample doctor information and billing fees for demonstration purposes. It does not provide medical advice or connect to real hospital booking or billing systems.
