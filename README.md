# Neural-Nexus
This is the landing page for the Neural Nexus Project

---

This is a MVP to allow the collection and interaction with personal data in the form of custom LLMs & the use of neural data in the form of vision, inner thought (silent reading), and movement for novel purposes.

---

Potential use cases:
 - Create avatars to speak to people who would normally not respond
 - Create avatars to communicate with people you haven't in a while
 - Create avatars to communicate with people based on historical data
 - Create avatars of yourself to suggest responses to a local conversation.
 - Reconstruct images in the V1 visual cortext to see what a person is seeing, communicate what a person is dreaming at night, and visualize imagination
 - Reconstruct text to allow for hyper-fast communication, and communication for those with ALS or other disabilities to unlock their beautiful mind and communicate with high fidelity to the world ***
 - Reconstruct movement to allow for control of external robotic devices, exosuits, and the physical body to create hyper-performant athletes, give the disabled the ability to function normally, and allow the prediction & visualization of future movements for the general public and the historical recording and replaying of these movements.
 - Allow for the custom LLM of an avatar, the motions of the individual, the inner thoughts, and the visualization of the individual to be uploaded to an embodied robot to persist in the physical world.

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
 - [API Gateway](https://github.com/efwoods/Neural-Nexus-API-Gateway)
 - [Frontend](https://github.com/efwoods/Neural-Nexus-Frontend)
 - [Audio-to-Text-API](https://github.com/efwoods/transcription-api)
 - [Thought-To-Image-Model](https://github.com/efwoods/V1-Visual-Cortex-Visualization)
 - [Thought-To-Image-Simulation-API](https://github.com/efwoods/Thought-To-Image-Simulation-API)
 - [Thought-To-Text](TBD)
 - [Local-LLM-API](https://github.com/efwoods/Vision_LLM_API)
 - [Thought-to-Motion-API](TBD)
 - [Thought-to-Motion-Models](https://github.com/efwoods/CRCNS)

---

MILESTONES:
- [x] add users
- [ ] verify logins
- [x] transcribe audio (This needs to be improved)
- [ ] stream neural-to-text & visualize (needs a model)
- [ ] conversation suggestions (placeholders, need a real suggestion based on dialogue)
- [ ] stream neural-to-images & visualize (showing images is not present)
- [ ] save avatars, messages, & history (needs a modal to CRUD avatars and Avatar Documents and Train Custom LLMs)
- [ ] stream thought-to-motion & visualize (needs a visualization, the model has been defined)
- [ ] audio input (push-to-talk function needs to be implemented)
- [ ] Custom LLM per avatar (not yet defined)

Future Work:
Highest Priority

- [ ]  The conversations need to be saved to the db per avatar
- [ ]  speaker diarization needs to identify who is speaking
- [ ]  the conversations need to be added to a custom language model for suggestions
- [ ]  suggestions need to be sent to the frontend
- [ ]  images need to be presented in the frontend
- [ ]  images need to be reconstructed
- [ ]  thought-to-text api models need to be created based upon a dataset
- [ ]  need to integrate the thought to motion prediction into a 3.js visualization

Secondary Priority

- [ ]  need to add the ability to communicate with other users of the application
- [ ]  add chat rooms
- [ ]  add face-to-face communication
- [ ]  add api for the trained avatars to interface with other social media applications
- [ ]  add the ability to link social media to the main account to train the avatar
- [ ]  use youtube transcription links to train avatars
- [ ]  create an option setting to view, delete, and upload uploaded avatar documents and alter the avatar name
