AI Avatar Video Generator Bot

An automated Telegram bot that converts text and voice messages into AI-generated avatar videos using HeyGen's API. Built with n8n workflow automation.

Features

Multi-Input Support: Accepts both text messages and voice notes from Telegram
Voice Transcription: Automatically transcribes voice messages using OpenAI's Whisper API
AI Avatar Generation: Creates professional avatar videos using HeyGen's video generation API
Async Processing: Implements polling mechanism to check video generation status
Seamless Delivery: Automatically sends completed videos back to users via Telegram
Error Handling: Gracefully handles unsupported message types with user-friendly error messages

How It Works

1. User sends a text or voice message via Telegram
2. Voice messages are transcribed to text using OpenAI
3. Text is sent to HeyGen API to generate an AI avatar video
4. Workflow polls HeyGen API until video is ready
5. Completed video is downloaded and sent back to the user

Tech Stack

n8n: Workflow automation platform
HeyGen API: AI avatar video generation
Telegram Bot API: Messaging interface
OpenAI API: Voice-to-text transcription

Use Cases

Content creation automation
Personalized video messaging
Educational content generation
Social media automation
Customer communication

Perfect for creators, marketers, and developers looking to automate AI video generation at scale.
