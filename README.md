# Render App Monitor

This repository monitors a Flask application deployed on Render (Free Tier).

## What it does
- Periodically sends an HTTP request to the Render app
- Checks if the app is responding (HTTP 200)
- Sends an email alert if the app is DOWN

## Monitored URL
https://flask-crud-sqlite-supabase-mxs2.onrender.com
