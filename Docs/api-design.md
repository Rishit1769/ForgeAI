# API Design

## Base Architecture
FastAPI backend handles:
- AI requests
- authentication
- project metadata
- queue management

## Core Endpoints

POST /projects/create
POST /projects/archive
GET /projects/{id}

POST /ai/summarize
POST /ai/roadmap
POST /ai/research-ideas

POST /standups/create
POST /standups/submit

GET /leaderboards

## Authentication
- Discord OAuth2
- GitHub OAuth

## Rate Limiting
Implemented using Redis.