# JPStats data backups

This repository contains daily and monthly backup files for my language-learning data. The backups are automatically generated and stored here to ensure that I can rebuild the database if needed or backdate new visualizations in the future.

The backups are created using a **cron job** running on a Linux server and include:
- Daily snapshots of data pulled from various study platforms.
- Monthly full backups of the MongoDB database.

This is a temporary solution, and the backups will eventually be migrated to a cloud storage service for long-term storage.

