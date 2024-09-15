# AI Daily Productivity Planner

## Problem

Staying productive and managing time can be difficult without proper planning. Individuals often struggle to organize their tasks efficiently, leading to wasted time and decreased productivity.

## Solution

The AI Daily Productivity Planner is an intelligent tool designed to assist users in creating a daily schedule by analyzing tasks and the time available. It can suggest optimal times for breaks, prioritize tasks, and even recommend periods for exercise.

## Features

- **Audio Transcription:** Converts spoken audio into text using the Whisper model.
- **Date Extraction:** Extracts start and end times from the input text.
- **Google Calendar Integration:** Adds events to Google Calendar with the extracted times.
- **User Interface:** User-friendly interface for uploading audio files or entering text.

## Installation

To set up the project, install the required packages by running the following commands:

```bash
pip install gradio whisper gtts google-api-python-client google-auth-httplib2 google-auth-oauthlib
pip install requests
pip install openai-whisper groq
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib whisper gradio
