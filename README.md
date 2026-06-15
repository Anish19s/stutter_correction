# Speech Disfluency Correction & Neural TTS Pipeline

An end-to-end speech processing system that converts disfluent spoken audio into clean, natural speech. The pipeline uses ASR to transcribe audio, an LLM to remove disfluencies, and neural TTS to generate polished speech output.

Features
- Speech-to-text using Whisper ASR
- Disfluency removal using Gemini LLM API
- Clean transcript generation (filler word + repetition removal)
- Natural speech synthesis using Edge TTS

## Tech Stack
- Whisper (OpenAI) – Automatic Speech Recognition
- Gemini LLM API – Text correction & disfluency removal
- Edge TTS – Neural Text-to-Speech synthesis
- PyTorch / torchaudio – Audio processing
- Transformers – NLP utilities and model support

## Pipeline Overview
Input: Disfluent speech audio
Whisper ASR → raw transcript
Gemini LLM → cleaned transcript
Edge TTS → regenerated clean speech⚙️ How It Works

Disfluent Speech → Whisper ASR → Gemini LLM Cleanup → Edge TTS → Clean Speech Output
