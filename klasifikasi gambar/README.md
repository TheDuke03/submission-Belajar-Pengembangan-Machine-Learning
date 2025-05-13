# Flower Classification CNN

Model ini dikembangkan menggunakan TensorFlow dan CNN untuk klasifikasi gambar bunga menjadi beberapa kelas.

## Detail Proyek
- Arsitektur: Sequential CNN
- Ukuran Gambar Input: 180x180
- Dataset terdiri dari training, validation, dan test set
- Target akurasi minimal 85% pada training dan test set tercapai

## Format Output Model
- SavedModel (format TensorFlow)
- TFLite (.tflite)
- TensorFlow.js (TFJS)

## Cara Penggunaan (TFLite)
- Gunakan `label.txt` sebagai referensi kelas
- Lakukan inferensi menggunakan TensorFlow Lite interpreter

## Akurasi Model
- Train Accuracy: 98.56%
- Validation Accuracy: 86.31%
- Test Accuracy: 85.62%
