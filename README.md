# TranscriptMatcher

A Python tool for finding matching segments in video transcripts using semantic similarity.

## Features
- Supports WebVTT (.vtt) and custom timestamped text (.txt) formats
- Uses `paraphrase-mpnet-base-v2` sentence transformer for accurate semantic matching
- Finds top matching segments across multiple transcript files
- Handles large transcripts efficiently

## Installation
1. Clone repository:
```bash
git clone https://github.com/yourusername/TranscriptMatcher.git
cd TranscriptMatcher
```
Transcript Formats
WebVTT (.vtt): Standard subtitle format

Text (.txt):
```bash
text
<00:01:23.456> This is a sample transcript
<00:01:45.789> With custom timestamps
```
