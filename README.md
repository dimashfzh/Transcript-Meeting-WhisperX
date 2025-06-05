# Transcript-Meeting-WhisperX (Indonesia)
## Transcript recorded meeting with WhisperX and Pyannote in Bahasa or Indonesian Language

Proyek ini menggunakan [WhisperX](https://github.com/m-bain/whisperx) untuk melakukan transkripsi dan diarization (pemisahan pembicara) pada rekaman FGD.

## Struktur Folder

- `Transcript-Meeting-WhisperX.ipynb`: Notebook Colab utama
- `hasil_transkripsi.json`: File hasil transkrip WhisperX
- `requirements.txt`: Library yang digunakan

## Instalasi

```bash
!pip install -q git+https://github.com/m-bain/whisperx.git -q
```
```bash
!pip3 install -U huggingface_hub -q
```
```bash
!apt-get install libcudnn8
```

## Contoh Output
```bash
[00:45:00 – 00:45:23] SPEAKER 00: Selamat pagi semua, terima kasih sudah hadir.
```
