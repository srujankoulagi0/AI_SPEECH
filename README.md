## AI Smart Speech Automation using n8n

Developed an **AI-powered text-to-speech automation system using n8n** that converts a given topic into audio. Users can enter a topic or text in the terminal using a PowerShell command, which sends the input to an n8n webhook through an HTTP POST request. The workflow processes the text and generates speech, providing a URL to access the final audio output.

**Key Features**
- Text input through Windows PowerShell or terminal.
- Automated workflow using n8n webhooks.
- AI-powered text-to-speech generation.
- Automatic audio URL output for the requested topic.
- Reduces manual effort through workflow automation.

**Technologies Used:** n8n, AI Text-to-Speech, Webhooks, HTTP POST Requests, JSON, PowerShell.

**Project Goal:** To simplify audio content creation by automatically converting any given topic into speech using AI and workflow automation.
Invoke-WebRequest -Uri "http://localhost:5678/webhook-test/8d670971-d06b-4d12-8d30-26e9e71e6892" -Method POST -ContentType "application/json" -Body '{"text":"     "}'    RUN THIS IN THE TERMINL OR WINDOWS POWER CELL.   YOU WILL GET THE AUDIO OF THAT WHAT YOU WANT ABOUT THE TOPIC
