# Image Classification with CIFAR-10 Dataset

Ini adalah Project Klasifikasi Gambar dengan dataset CIFAR-10 menggunakan **MobileNetV2**. Model dilatih untuk mengenali dan mengklasifikasikan gambar ke dalam sepuluh kategori. Selain itu, model yang telah dilatih dikonversi ke berbagai format seperti **SavedModel**, **TensorFlow Lite (TFLite)**, dan **TensorFlow.js** untuk memudahkan deployment di berbagai platform. 

## Fitur
- Dataset yang digunakan adalah [berikut](https://www.tensorflow.org/datasets/catalog/cifar10).
- Klasifikasi gambar menjadi 10 kelas: 
  - airplane
  - automobile
  - bird
  - cat
  - deer
  - dog
  - frog
  - horse
  - ship
  - truck
- Arsitektur MobileNetV2.
- Menyimpan model dalam berbagai format, yaitu:
  - SavedModel
  - TFLite
  - TensorFlow.js
- Terdapat script Jupyter Notebook (`notebook.ipynb`) dan file Python biasa (`notebook.py`).

## Struktur Folder
```
|   notebook.ipynb
|   notebook.py
|   best_model.h5
|   bird.jpg
|   requirements.txt
|   
+---saved_model
|   |   fingerprint.pb
|   |   saved_model.pb
|   |   
|   \---variables
|           variables.data-00000-of-00001
|           variables.index
|           
+---tfjs_model
|       group1-shard1of3.bin
|       group1-shard2of3.bin
|       group1-shard3of3.bin
|       model.json
|       
\---tflite
        label.txt
        model.tflite
```

## Requirement
Install requirements sebelum menjalankan program:
```bash
pip install -r requirements.txt
```