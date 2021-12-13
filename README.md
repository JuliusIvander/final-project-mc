# TUGAS AKHIR MICROCREDENTIAL ASSOCIATE DATA SCIENTIST

## Tentang Repositori

Repositori ini berisi proyek tugas akhir microcredential assosiate data scientist yang digunakan untuk melakukan proses pengumpulan dan pre-processing dataset, visualisasi dataset, serta pelatihan, evaluasi, dan ekstraksi model.

Proyek ini dikembangkan oleh **kelompok 1 UGM-03** yang terdiri dari 3 anggota, yakni:

1. Arwendy Melyndra
2. Julius Ivander Massie
3. Samuel Goesniady

## Struktur Proyek

Berikut adalah struktur proyek dari repositori:

```
Project
|   README.md
|   .gitignore
|
|___addson
|   |___labelImg
|
|___dataset
|   |___images
|   |___labels
|
|___model
|   |___yolov5
|
|___hasil_akhir
|
|___notebook
|      index.ipynb
|      1. Scraping image.ipynb
|      2. Data Preparation.ipynb
|   |___assets
```

Keterangan folder:
| Syntax | Description |
| ----------- | ----------- |
| addson | Menyimpan library penunjang proyek |
| dataset | Menyimpan data yang diperlukan untuk proses pelatihan dan evaluasi model |
| model | Menyimpan pre-trained model proyek |
| hasil_akhir | Menyimpan hasil pelatihan dan evaluasi model, serta ekstraksi model |
| notebook | Menyimpan source code untuk memenuhi proses yang diperlukan hingga membentuk sebuah model |

## Getting Started

Berdasarkan struktur folder diatas, kami menggunakan [LabelImg](https://github.com/tzutalin/labelImg) untuk melakukan proses pelabelan dan menggunakan [YoloV5](https://github.com/ultralytics/yolov5) for pre-trained model. Proses instalasi dapat dilihat dari link yang telah diberikan (teks berwarna biru)

Seluruh proses dari pengumpulan dataset hingga ekstraksi model dapat ditemukan pada folder notebook dengan nama file `index.ipynb`

Hasil akhir dari dataset kemudian di deploy melalui web [https://micro-ds-deployed.herokuapp.com/ ](https://micro-ds-deployed.herokuapp.com/)
