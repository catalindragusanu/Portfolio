---
title: "Fluffy Question Buddy"
description: "A kid-friendly Q&A web app where children ask questions by text or voice and an animated mascot answers in simple, safe language using an AI model."
pubDate: 2026-10-28
tags: ["JavaScript", "Python", "Netlify", "AI", "Web Speech"]
repoUrl: "https://github.com/catalindragusanu/kids-fluffy-assistant"
featured: true
---

## Overview

Fluffy Question Buddy lets children ask anything and get an answer from Fluffy, a cuddly animated mascot. Answers come from an AI model on Ollama Cloud, written in simple, safe language.

## Key Features

- **Kid-safe answers** - kid mode is on by default
- **Voice in and out** - speech recognition for asking, speech synthesis for reading answers aloud
- **Multiple profiles** - each child has their own history, level and memories
- **Levels and badges** - a new level every 15 questions, with sticker badges as rewards
- **Themes** - customise the look of the app and of Fluffy
- **Settings page** - model, temperature, answer length, voice and a connection test

## Tech Stack

- **Frontend**: plain HTML, CSS and JavaScript, no build step
- **Backend**: a small Python server, or a Netlify function, that proxies chat requests so the API key stays on the server
- **AI**: Ollama Cloud
