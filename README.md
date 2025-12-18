# 👗🧮 PCA Demo: Fashion-MNIST & MNIST

<!-- Badges -->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cagatayuresin/pca-demo/blob/main/pca-demo-1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cagatayuresin/pca-demo/blob/main/pca-demo-2-fashion-mnist.ipynb)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Proje Özeti

Bu proje, **Temel Bileşen Analizi (PCA)** yöntemini hem klasik MNIST hem de Fashion-MNIST veri setleri üzerinde interaktif ve görsel olarak anlatan iki kapsamlı Jupyter Notebook içerir. Amaç, yüksek boyutlu görsel verilerde boyut indirgeme ve bilgi kaybı ilişkisini hem matematiksel hem de uygulamalı olarak göstermek, PCA'nın matematiksel temelini ve gerçek dünyadaki etkisini anlaşılır kılmaktır.

## İçerik

- `pca-demo-1.ipynb`: MNIST (el yazısı rakamlar) üzerinde PCA uygulaması
- `pca-demo-2-fashion-mnist.ipynb`: Fashion-MNIST (giysi görselleri) üzerinde PCA uygulaması
- `pca-interactive-math.html`: PCA'nın matematiksel adımlarını canlı ve interaktif olarak gösteren HTML sunum aracı

## Özellikler

- 📊 **Veri Görselleştirme:** Orijinal ve indirgenmiş verilerin 2D/3D projeksiyonları
- 🎨 **Eigenfaces / Temel Bileşen Görselleştirmesi:** Her PC'nin (principal component) görsel etkisi
- 🔍 **Özellik Önemi Analizi:** Hangi pikselin/bileşenin en önemli olduğunu gösteren interaktif analiz
- 🧩 **Kümülatif Varyans & Bilgi Kaybı:** Boyut azaltma ile bilgi kaybı ilişkisi
- 🧑‍💻 **Tamamen Türkçe açıklamalar ve interaktif widget'lar**
- 🌸 **Iris ve korelasyonlu veri ile interaktif PCA matematiği** (HTML)

## Kullanım

1. Gerekli Python paketlerini yükleyin:

   ```bash
   pip install numpy matplotlib scikit-learn seaborn ipywidgets
   ```

2. Notebook'ları Jupyter veya VSCode ile açın.
3. Tüm hücreleri çalıştırın ve interaktif widget'ları kullanarak PCA'nın etkisini keşfedin.
4. `pca-interactive-math.html` dosyasını tarayıcıda açarak PCA'nın matematiksel adımlarını canlı olarak inceleyin.

## Demo Ekran Görüntüleri

- ![Fashion-MNIST PCA](docs/fashion-mnist-pca-demo.png)
- ![MNIST PCA](docs/mnist-pca-demo.png)
- ![PCA Matematiksel Sunum](docs/pca-math-html-demo.png)

## Akademik Bilgi

- **Hazırlayan:** Çağatay ÜRESİN (20250257001)
- **Kurum:** Sivas Cumhuriyet Üniversitesi, Fen Bilimleri Enstitüsü
- **Ders:** Makine Öğrenmesi (Prof. Dr. Hidayet TAKCI)
- **İletişim:** <cagatayuresin@gmail.com> | [GitHub](https://github.com/cagatayuresin) | [LinkedIn](https://linkedin.com/in/cagatayuresin)

## Kaynaklar

- [Shlens, J. (2005). "A Tutorial on Principal Component Analysis"](https://arxiv.org/abs/1404.1100)
- [Fashion-MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

---

> Sunum ve eğitim amaçlı hazırlanmıştır. Her türlü katkı ve öneriye açıktır!
