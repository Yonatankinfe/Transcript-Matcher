# Transcript - Matcher

A Python tool for finding matching segments in video transcripts using semantic similarity txt file only and a script txt file

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

# Requirements
```txt
pip install sentence-transformers
pip install webvtt-py
pip install torch
```
Transcript Formats
WebVTT (.vtt): Standard subtitle format

# Input file Text (.txt):
```bash
text
<00:01:23.456> This is a sample transcript
<00:01:45.789> With custom timestamps
```
# Output
```bash
=== Top Matches ===

1. video1
   00:05:10 → 00:05:15  (score: 0.8723)
   "This is the matching segment text"
...
```
# License


