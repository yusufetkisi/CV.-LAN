# Yapay Zeka Ödev 2

Bu repo, Yapay Zeka dersi 2. ödevi için metin benzerliği hesaplama ve model değerlendirme kodlarını içerir.

## Çalıştırma Talimatları

1. Gerekli kütüphaneleri yükleyin:
```bash
pip install pandas numpy gensim
```

2. Verileri ve kodları indirin:
   - Veriler: `CVs.csv`, `Job Postings.csv`, `TF-IDF Results.csv`, `word2vec_similarity_results.csv`
   - Kodlar: `tfidf_top5.py`, `word2vec_top5.py`, vb.

3. Kodları sırayla çalıştırın:
```bash
python tfidf_top5.py
python tfidf_stemmed_top5.py
python word2vec_top5.py
python word2vec_other_models.py
python semantic_evaluation.py
python jaccard_matrix.py
```

4. Çıktılar:
   - `tfidf_lemmatized_top5.csv`: TF-IDF lemmatized en iyi 5 eşleşme
   - `word2vec_*.csv`: Word2Vec modelleri için en iyi 5 eşleşme
   - `semantic_evaluation.csv`: Anlamsal değerlendirme
   - `jaccard_matrix.csv`: Jaccard benzerlik matrisi

5. Rapor:
   - `Odev2_Rapor.tex` dosyasını LaTeX ile derleyin (örneğin, Overleaf).

## Notlar
- Word2Vec model dosyaları eksikse, `word2vec_similarity_results.csv`’den sonuçlar kullanıldı.
- Gerçek model dosyaları için `word2vec_other_models.py`’yi güncelleyin.