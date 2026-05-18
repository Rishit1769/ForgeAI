# AI System

## Features
- paper summarization
- roadmap generation
- repository explanation
- research idea generation

## Processing Pipeline

PDF
↓
Text Extraction
↓
Chunking
↓
LLM Summaries
↓
Final Summary

## Queue System
Uses:
- Redis
- Celery

## Rate Limiting
Prevents API abuse.

## Caching
Stores repeated summaries.