---
title: "Task Manager"
description: "A web app for managing tasks with categories, priorities and a calendar view, plus AI brainstorming and daily planning powered by a local Ollama model."
pubDate: 2026-10-25
tags: ["React", "Flask", "Python", "Ollama", "AI"]
repoUrl: "https://github.com/catalindragusanu/Task_Manager"
featured: true
---

## Overview

Task Manager is a web application for organising work, with AI features that suggest tasks from your goals and build a daily schedule from your priorities. The AI runs locally on Ollama, so there are no API costs and your data stays private.

## Key Features

- **Task management** - create, edit, delete and organise tasks by category
- **AI brainstorming** - generate task ideas from a goal
- **Daily planning** - an AI-optimised schedule based on task priorities
- **Calendar view** - see tasks by date
- **Filtering and sorting** - by category, search text and other criteria
- **Priority and status** - High/Medium/Low priority and Todo/In Progress/Done status
- **No account needed** - data is stored in the browser

## Tech Stack

- **Frontend**: React, Axios, date-fns, react-calendar
- **Backend**: Flask, Flask-CORS
- **AI**: Ollama running llama3.2 locally
