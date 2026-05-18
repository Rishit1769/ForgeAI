# Workflows

## Project Creation Workflow
1. User creates project.
2. Bot creates workspace.
3. Team joins.
4. Standups configured.

## AI Summary Workflow
1. User uploads paper.
2. Task enters Redis queue.
3. Celery worker processes task.
4. Summary returned via DM.

## Daily Standup Workflow
1. Bot sends reminders.
2. Members respond.
3. Bot generates summary.