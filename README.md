# Social Media Editing Pipeline — Quick Start

Free guide. For the full production workflow, see the advanced pack.

## What it does
Turns a raw video or audio file into a platform-ready short-form clip. The basic flow is clean, captioned, and formatted for TikTok, Reels, or Shorts.

## Requirements
- ffmpeg with a few common filters
- faster-whisper
- Python 3.11

## Basic flow
1. Clean the audio with ffmpeg.
2. Transcribe the audio into captions.
3. Remove ellipsis and obvious filler sounds from captions.
4. Burn captions back into the video.
5. Resize to vertical and export.

## Caption style
Keep it plain. No animation, no ellipsis, no fake filler removal that cuts real words. The captions should match what was actually said.

## Resize pattern
Reframe to vertical with a blurred background instead of chopping the sides off the original clip.
