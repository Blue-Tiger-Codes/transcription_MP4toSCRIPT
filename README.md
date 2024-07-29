# transcription_MP4toSCRIPT
 # MP4 to Transcript Converter

This project provides a Python script to convert MP4 video files into text transcripts using speech recognition. It leverages the capabilities of the `SpeechRecognition` library and `moviepy` for audio extraction.

## Features

- Convert MP4 video files to audio format.
- Transcribe audio to text using speech recognition.
- Save the transcript to a text file.

## Requirements

Before running the script, ensure you have the following dependencies installed:

- Python 3.x
- `moviepy`
- `SpeechRecognition`
- `pydub` (optional, for audio format handling)
- `ffmpeg` (required for audio processing)

You can install the required Python libraries using pip:

```bash
pip install moviepy SpeechRecognition pydub
