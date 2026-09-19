# Prediksi Darah Tinggi

Aplikasi **Streamlit** untuk memprediksi tahap hipertensi (**Normal, Prehypertension, Stage 1, Stage 2**) dari data
tekanan darah, detak jantung, dan ukuran tubuh.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

## Masukan

| Fitur | Keterangan |
|---|---|
| Sex | jenis kelamin |
| Age | usia (tahun) |
| Height | tinggi badan (cm) |
| Weight | berat badan (kg) |
| Systolic Blood Pressure | tekanan darah sistolik (mm Hg) |
| Diastolic Blood Pressure | tekanan darah diastolik (mm Hg) |
| Heart Rate | detak jantung per menit |
| BMI | indeks massa tubuh |

## Isi repositori

| File | Isi |
|---|---|
| `app.py` | aplikasi Streamlit (memuat `model_new.pkl`) |
| `model_new.pkl`, `model.pkl` | model terlatih (baru dan versi sebelumnya) |
| `Model.ipynb` | notebook pelatihan |
| `dataset_new.csv` | dataset (pemisah `;`, desimal koma) |

## Menjalankan

```bash
pip install -r requirements.txt
streamlit run app.py
```

> Proyek pembelajaran, bukan alat diagnosis medis.
