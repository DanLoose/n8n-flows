# n8n-flows
Repository for storing n8n flows

## Overview
This repository contains two independent projects that leverage n8n workflows for automation:

1. [Personal Assistant](flows/personal_assistant/README.md)
   - An AI-powered personal assistant system that handles various tasks through Telegram
   - Integrates email, calendar, and content creation capabilities
   - Uses GPT-4 for intelligent request processing
   - Maintains conversation context for natural interactions

2. [Shorts Generator](flows/shorts_generator/README.md)
   - An automated content generation system for creating short-form videos
   - Combines AI image generation, video creation, and publishing
   - Uses multiple AI services (Midjourney, Kling AI, etc.)
   - Includes automated YouTube publishing and content tracking

## Repository Structure
```
flows/
├── personal_assistant/
│   ├── images/
│   ├── personal_assistant.json
│   ├── gmail_agent.json
│   ├── calendar_agent.json
│   └── content_creator_agent.json
└── shorts_generator/
    ├── images/
    ├── generate_shorts.json
    ├── generate_ai_video.json
    └── generate_ai_image.json
```

## Getting Started
Each project has its own detailed documentation and setup instructions. Please refer to the specific README files:

- [Personal Assistant Documentation](flows/personal_assistant/README.md)
- [Shorts Generator Documentation](flows/shorts_generator/README.md)

## Contributing
Feel free to submit issues and enhancement requests for any of the projects!

