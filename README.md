# Reddit AI Lead Assistant (Prototype)

This project is a backend automation tool designed to:

- Read publicly available Reddit posts and comments from selected subreddits
- Identify discussions where users are asking for help related to automation, workflows, CRM systems, and business operations
- Extract key context such as user intent and problem statements
- Generate AI-assisted draft responses to improve response quality
- Store structured data in Airtable for manual review

## Workflow

1. Monitor new Reddit posts and comments
2. Filter relevant discussions based on intent
3. Extract and structure useful data
4. Generate draft responses using AI
5. Human reviews and approves responses before posting

## Compliance

- No automated posting without human approval
- No unsolicited private messaging
- No spam or bulk outreach
- Only interacts with publicly available content

## Tech Stack (Planned)

- Python (FastAPI)
- OpenAI API
- Airtable
- Make.com / n8n
- Reddit API (OAuth)

## Status

This is an early-stage prototype under development.
