# Database Schema

## Tables

### users
Stores:
- discord_id
- username
- roles
- region
- points

### projects
Stores:
- project_name
- project_owner
- project_status
- created_at

### project_members
Stores:
- user_id
- project_id
- joined_at

### reminders
Stores:
- reminder_time
- reminder_type
- target_users

### standups
Stores:
- daily_updates
- blockers
- progress_logs

### achievements
Stores:
- achievement_type
- earned_at

## Relationships
users → projects
projects → standups
users → points
projects → reminders