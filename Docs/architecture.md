# System Architecture

## Core Stack
- Python
- discord.py
- FastAPI
- MySQL
- Redis
- Celery

## Architecture Flow

Discord Client
↓
Discord Bot Layer
↓
FastAPI Backend
↓
Redis Queue
↓
Celery Workers
↓
Gemini API
↓
MySQL Database

## Core Components
### Discord Bot
Handles:
- slash commands
- permissions
- event handling
- project workspace creation

### FastAPI Backend
Handles:
- APIs
- authentication
- background orchestration

### Redis
Handles:
- queues
- caching
- rate limiting
- temporary session data

### Celery Workers
Handles:
- AI processing
- summarization tasks
- background jobs

### MySQL
Stores:
- users
- projects
- points
- standups
- reminders
- achievements

## Future Scaling
- Docker
- Horizontal workers
- CDN
- Distributed processing