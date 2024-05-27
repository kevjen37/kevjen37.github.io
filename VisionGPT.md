## Introducing BrowPrompt for Hands-Free Information Access


__link to YouTube demo: [BrowPrompt](https://youtu.be/3vlb6Qc-xBE)__

__The Problem: Why I Built BrowPrompt__

Like many knowledge workers, I frequently prompt language models to answer questions throughout my day. However, I have not found an effective way to access these tools without constantly navigating to a web app or having my microphone always on and listening. This gap inspired me to develop BrowPrompt, a solution designed to streamline this process with a unique approach.

__The Solution: BrowPrompt's Value Proposition__

BrowPrompt is an application that leverages computer vision to monitor facial cues as a mechanism to initiate voice-to-text prompting with GPT-4o. Here’s how it works:

- Facial Cue Detection: BrowPrompt continuously monitors your face for a specific cue – an eyebrow raise. This ensures that the microphone activates only when you intend to use it.
- Voice-to-Text Auomation: Upon detecting the eyebrow raise, BrowPrompt turns on your microphone to capture your query, eliminating the need to navigate through menus or manually activate voice commands. Captured audio is then passed through Google's Web Speech API to be converted to text.
- Prompting GPT-4o: The converted text is fed directly to GPT-4o via OpenAI's API, which returns the model's response both in text and through OpenAI's text-to-speech (TTS-1) model.

__User Benefits:__ 

- Hands-Free Operation: Easily prompt GPT-4 with just an eyebrow raise, keeping your hands free for other tasks.
- Enhanced Privacy: By monitoring facial cues instead of always listening, BrowPrompt respects your privacy while remaining readily accessible.
- Low Overhead: BrowPrompt can run in the background, providing quick access to information without the need for constant manual input.
