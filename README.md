# Real Time Transcription with AssemblyAI
See [this tutorial from Assembly.ai for complete details](https://www.assemblyai.com/blog/real-time-transcription-in-python/).

## Setup
1. Create a free account at [AssemblyAI](https://app.assemblyai.com/login) and get your API key.
2. We’ll need the system dependency portaudio before installing the necessary pip packages, so install it with apt install portaudio19-dev (Debian/Ubuntu) or brew install portaudio (MacOS). For other operating systems, see the [portaudio website](https://portaudio.com/docs/v19-doxydocs/tutorial_start.html?ref=assemblyai.com).
3. Copy `.env.example` to `.env` and add your API key.
