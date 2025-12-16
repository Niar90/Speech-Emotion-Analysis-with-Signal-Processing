# Speech-Emotion-Analysis-with-Signal-Processing
Analisis emosi dari sinyal suara menggunakan teknik pengolahan sinyal dan klasifikasi rule-based berdasarkan fitur akustik.

 ## Dataset
Project ini menggunakan dua sumber data:

### 1. RAVDESS Dataset
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) digunakan sebagai **dataset utama** untuk:
- menganalisis pola statistik fitur akustik berdasarkan emosi,
- membangun aturan (rule-based) klasifikasi emosi.

Link dataset:(https://zenodo.org/record/1188976)

### 2. Rekaman Suara Pribadi
Selain dataset RAVDESS, project ini juga menggunakan **rekaman suara pribadi** sebagai:
- data uji,
- evaluasi performa sistem pada data real-world.

Rekaman ini diproses menggunakan pipeline preprocessing yang sama dengan dataset RAVDESS agar hasil analisis tetap konsisten.
