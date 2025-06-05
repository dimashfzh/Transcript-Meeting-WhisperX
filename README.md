# Transcript-Meeting-WhisperX (Indonesia)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![Last Commit](https://img.shields.io/github/last-commit/dimashfzh/Transcript-Meeting-WhisperX)](https://github.com/dimashfzh/Transcript-Meeting-WhisperX/commits/main)
[![Stars](https://img.shields.io/github/stars/dimashfzh/Transcript-Meeting-WhisperX?style=social)](https://github.com/dimashfzh/Transcript-Meeting-WhisperX/stargazers)
[![HF Token Required](https://img.shields.io/badge/HF%20Token-required-orange)](https://huggingface.co/settings/tokens)

Transcript recorded meeting with WhisperX and Pyannote in Bahasa/Indonesian Language

This Project use [WhisperX](https://github.com/m-bain/whisperx) to do audio transcript and speaker diarization on a recorded meeting audio.

## Folder Structure

- `Transcript-Meeting-WhisperX.ipynb`: Main Colab Notebook
- `hasil_transkripsi.json`: File transcript by WhisperX
- `requirements.txt`: Library used

## Instalation

```bash
!pip install -q git+https://github.com/m-bain/whisperx.git -q
```
```bash
!pip3 install -U huggingface_hub -q
```
```bash
!apt-get install libcudnn8
```

## Output Example
```bash
[00:45:00 – 00:45:23] SPEAKER 00: Selamat pagi semua, terima kasih sudah hadir.
```
