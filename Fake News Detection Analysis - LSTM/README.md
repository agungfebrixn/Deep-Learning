# Informasi Dataset

Lahitan ini bertujuan untuk membangun program pembelajaran mendalam yang mampu mengidentifikasi apakah sebuah artikel merupakan berita palsu atau tidak.

### Atribut Dataset
- **id**: ID unik untuk setiap artikel berita
- **title**: Judul artikel berita
- **author**: Penulis artikel berita
- **text**: Isi teks artikel (dapat saja tidak lengkap)
- **label**: Label yang menunjukkan tingkat keandalan artikel
    - **1**: Tidak dapat diandalkan
    - **0**: Dapat diandalkan

**Dataset:** https://www.kaggle.com/c/fake-news/data

**Glove Embedding link:** https://www.kaggle.com/anindya2906/glove6b?select=glove.6B.100d.txt

# Pustaka yang Digunakan
- pandas
- matplotlib
- keras
- tensorflow
- scikit-learn
- nltk

# Neural Network
- **LSTM Network**
**Tingkat Akurasi:** 95.00% (dengan pelatihan lebih dari 50 epoch)
