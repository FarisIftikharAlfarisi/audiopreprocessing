
<h1 align="center"> Audio Feature Engineering: Analisis Lagu "Everything You Are" - Hindia</h1>
<p align="center"> Faris Iftikhar Alfarisi/p>

## Deskripsi Proyek
Notebook ini mendokumentasikan proses ekstraksi dan analisis fitur audio dari cuplikan 60 detik lagu "Everything You Are" karya Hindia. Proyek ini bertujuan untuk memahami karakteristik audio melalui berbagai teknik feature engineering.

## Tahapan Utama
1. **Pemuatan dan Visualisasi Audio**  
   Memuat file audio dan menampilkan waveform untuk analisis awal

2. **Analisis Spectral Leakage**  
   Memeriksa efek spectral leakage dengan berbagai teknik windowing

3. **Ekstraksi Fitur Audio**  
   Mengekstraksi fitur-fitur penting meliputi:
   - Root Mean Square (RMS) Energy
   - Zero Crossing Rate (ZCR)
   - Mel-Frequency Cepstral Coefficients (MFCC)
   - Spektrogram
   - Tempo dan Beat

4. **Normalisasi Audio**  
   Implementasi dua metode normalisasi:
   - Peak Normalization
   - Loudness Normalization (LUFS)

5. **Analisis Hasil**  
   Visualisasi perbandingan waveform dan spektrogram sebelum/sesudah normalisasi

## Teknologi yang Digunakan
- **Python Libraries**:
  - librosa (analisis audio)
  - pyloudnorm (normalisasi LUFS)
  - pydub (manipulasi audio)
  - matplotlib/seaborn (visualisasi)
  - scipy (pemrosesan sinyal)

- **File Audio**:
  `everything_u_are_hindia_60scd.mp3`

## Cara Menjalankan
1. Install dependencies:
```bash
pip install librosa matplotlib pyloudnorm pydub seaborn
```
