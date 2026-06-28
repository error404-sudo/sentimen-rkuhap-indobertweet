# Analisis Sentimen RKUHAP Menggunakan IndoBERTweet

Repository ini berisi notebook eksperimen analisis sentimen pengguna aplikasi X terhadap pengesahan RKUHAP menggunakan model IndoBERTweet.

Penelitian ini membandingkan empat skenario eksperimen, yaitu baseline, class weight, Random Oversampling, dan focal loss. Perbandingan dilakukan untuk melihat performa masing-masing skenario dalam menangani ketidakseimbangan data pada klasifikasi sentimen.

## Skenario Eksperimen

1. **Baseline**  
   Model IndoBERTweet tanpa penanganan ketidakseimbangan data.

2. **Class Weight**  
   Model IndoBERTweet dengan pemberian bobot berbeda pada setiap kelas.

3. **Random Oversampling (ROS)**  
   Model IndoBERTweet dengan penambahan data pada kelas minoritas melalui teknik oversampling.

4. **Focal Loss**  
   Model IndoBERTweet dengan fungsi loss yang memberi perhatian lebih pada sampel yang sulit diklasifikasikan.

## Struktur File

## Struktur File

```text
Notebook/
├── 01_Baseline.ipynb
├── 02_ClassWeight.ipynb
├── 03_ROS.ipynb
└── 04_FocalLoss.ipynb

Dataset/
└── dataset_rkuhap_labeled.csv
