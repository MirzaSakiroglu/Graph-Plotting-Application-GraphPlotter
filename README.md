# GraphPlotter - Grafik Oluşturma Uygulaması

**GraphPlotter**, matematiksel fonksiyonları görselleştirmek ve analiz etmek için geliştirilmiş, Python tabanlı bir masaüstü uygulamasıdır. Kullanıcı dostu arayüzü sayesinde karmaşık denklemleri saniyeler içinde 2D grafiklere dönüştürür.

---

##  Proje Hakkında
Bu proje, öğrencilerin, mühendislerin ve matematik meraklılarının fonksiyonların davranışlarını görsel olarak incelemelerine olanak tanır. Python'un güçlü kütüphanelerini kullanarak hızlı, doğru ve etkileşimli grafikler sunar.

##  Temel Özellikler

* **Dinamik Fonksiyon Çizimi:** `x**2`, `sin(x)`, `exp(x)` gibi matematiksel ifadeleri destekler.
* **İnteraktif Grafikler:** Grafikler üzerinde yakınlaştırma (zoom), kaydırma (pan) ve ev görünümüne dönme özellikleri.
* **Özelleştirilebilir Aralıklar:** X ve Y eksenleri için başlangıç ve bitiş değerlerini manuel olarak belirleyebilme.
* **Kayıt İmkanı:** Oluşturulan grafikleri PNG veya diğer formatlarda bilgisayarınıza kaydedebilme.
* **Hata Yönetimi:** Hatalı fonksiyon girişlerinde kullanıcıyı bilgilendiren uyarı mekanizması.

## 🛠️ Kullanılan Teknolojiler

Bu proje aşağıdaki açık kaynaklı Python kütüphaneleri ile geliştirilmiştir:

* **[Python 3.x](https://www.python.org/):** Ana programlama dili.
* **[Tkinter](https://docs.python.org/3/library/tkinter.html):** Grafiksel kullanıcı arayüzü (GUI).
* **[Matplotlib](https://matplotlib.org/):** Veri görselleştirme ve grafik çizim motoru.
* **[NumPy](https://numpy.org/):** Yüksek performanslı matematiksel hesaplamalar.

## ⚙️ Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  **Depoyu Klonlayın**
    ```bash
    git clone [https://github.com/MirzaSakiroglu/Grafik-Olusturma-Uygulamasi-GraphPlotter.git](https://github.com/MirzaSakiroglu/Grafik-Olusturma-Uygulamasi-GraphPlotter.git)
    cd Grafik-Olusturma-Uygulamasi-GraphPlotter
    ```

2.  **Gerekli Kütüphaneleri Yükleyin**
    ```bash
    pip install matplotlib numpy
    ```

3.  **Uygulamayı Başlatın**
    ```bash
    python main.py
    ```

## 📖 Kullanım Kılavuzu

1.  Uygulamayı açın.
2.  **"Fonksiyon"** alanına çizdirmek istediğiniz denklemi girin (Örn: `x**2 + 2*x - 5`).
    * *Not: Çarpma işlemi için `*`, üs alma işlemi için `**` kullanın.*
3.  **X Ekseni** için minimum ve maksimum değerleri girin.
4.  **"Grafiği Çiz"** butonuna tıklayın.
5.  Grafik penceresindeki araç çubuğunu kullanarak grafiği inceleyin veya kaydedin.

## 🤝 Katkıda Bulunma

Projeye katkıda bulunmak isterseniz, lütfen şu adımları takip edin:

1.  Projeyi Fork'layın.
2.  Yeni bir Branch oluşturun (`git checkout -b feature/YeniOzellik`).
3.  Değişikliklerinizi Commit'leyin (`git commit -m 'Yeni özellik eklendi'`).
4.  Branch'inizi Push'layın (`git push origin feature/YeniOzellik`).
5.  Bir Pull Request (Çekme İsteği) oluşturun.

---

**Geliştiriciler:** [Mirza Şakiroğlu](https://github.com/MirzaSakiroglu) ve [İsa Mirza Sincap](https://github.com/Sqortle)
