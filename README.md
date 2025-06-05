# Transcript-Meeting-WhisperX (Indonesia)
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
