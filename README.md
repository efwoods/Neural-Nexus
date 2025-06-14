# Neural-Nexus
This is the landing page for the Neural Nexus Project

---

This is a MVP to allow the collection and interaction with personal data in the form of custom LLMs

---

Potential use cases:
 - Create avatars to speak to people who would normally not respond
 - Create avatars to communicate with people you haven't in a while
 - Create avatars to communicate with people based on historical data
 - Create avatars of yourself to suggest responses to a local conversation.

Avatar Management:

Create new avatars with names and descriptions
Delete existing avatars
Visual avatar selection in the sidebar

File Upload System:

Upload multiple documents and images per avatar
Automatic categorization (documents vs images)
File size display and management
Support for all file types

Chat Interface:

Real-time text messaging with each avatar
Message history preserved per avatar
Visual distinction between user, avatar, and system messages
Clean, modern chat bubble design

Voice Recording:

Microphone button for voice messages
Visual recording indicator with pulsing animation
Browser-based audio recording using MediaRecorder API
Voice messages displayed in chat with special indicators

Modern Design:

Stunning gradient backgrounds and glassmorphism effects
Responsive layout that works on different screen sizes
Smooth animations and hover effects
Professional color scheme with purple, cyan, and green tones

🎯 How to Use

Create Avatar: Click "Create Avatar" to add a new avatar with a name and description
Upload Files: Select an avatar and click "Upload Files" to add documents and images
Chat: Type messages or use the microphone button to send voice messages
Manage: Delete avatars or view their file collections in the sidebar

The app uses React state management (no browser storage) and includes proper error handling for microphone access. Each avatar maintains its own chat history and file collection, creating a personalized experience for interacting with different AI personas.

---

## Component Repositories:
 - [Database](https://github.com/efwoods/Neural-Nexus-DB)
 - [Reverse-Proxy](https://github.com/efwoods/Neural-Nexus-Reverse-Proxy)
 - [Frontend](https://github.com/efwoods/Neural-Nexus-Frontend)
 - [Audio-to-Text-API](https://github.com/efwoods/transcription-api)
 - [Thought-To-Image](https://github.com/efwoods/V1-Visual-Cortex-Visualization)
 - [Thought-To-Text](https://github.com/efwoods/Inner-Speech)
 - [Local-LLM-API](https://github.com/efwoods/Vision_LLM_API)
 - [Gaze-Tracking/Telepathy](https://github.com/efwoods/eye-tracking)
 - [Thought-to-Motion-API](https://github.com/efwoods/ecog-movement-prediction-api)
 - [Thought-to-Motion-Models](https://github.com/efwoods/CRCNS)

---

MILESTONES:
- [ ] add users
- [ ] verify logins
- [ ] transcribe audio
- [ ] stream neural-to-text & visualize
- [ ] conversation suggestions
- [ ] stream neural-to-images & visualize
- [ ] save avatars, messages, & history
- [ ] stream thought-to-motion & visualize
- [ ] audio input
- [ ] Custom LLM per avatar
