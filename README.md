
## Proje : Yakıt Tüketim Tahmini

Bu Proje, araçların yakıt tüketimini ve karbon emisyonlarını etkileyen faktörleri analiz etmek ve tahmin modelleri oluşturmak amacıyla gerçekleştirilen bir çalışmayı kapsamaktadır. Projenin detayları, veri seti analizi, modelleme ve sonuçlarla birlikte açıklanmıştır.

![image](https://github.com/user-attachments/assets/602c9892-7e66-42e8-9694-26b13898560e)


Bu proje, **Random Forest** algoritmasını kullanarak araçların yakıt tüketimini tahmin etmek için geliştirilmiş bir makine öğrenimi modelini içerir. Projede, araç özelliklerini (örneğin, motor hacmi, ağırlık, yakıt türü) kullanarak tahmini yakıt tüketimi hesaplanır.

## Özellikler
- **Makine Öğrenimi Modeli:** Random Forest Regressor kullanılmıştır.
- **Veri Analizi ve Görselleştirme:** Verilerin incelenmesi ve analiz edilmesi için Python kütüphaneleri kullanılmıştır.
- **Kullanıcı Dostu Yapı:** Kod, kolay anlaşılabilir ve tekrarlanabilir bir yapıda tasarlanmıştır.
- **Modelin eğitimi sırasında** gereksiz sütunlar elenmiş, kategorik değişkenler **OneHotEncoder** ile dönüştürülmüş, sayısal değişkenler ise **StandardScaler** ile ölçeklendirilmiştir.

![image](https://github.com/user-attachments/assets/965a62a1-935a-4d59-b503-a58aeebb0cca)

![image](https://github.com/user-attachments/assets/16360e6c-c4c1-4d90-8126-145d5a957552)


## Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki araç ve kütüphanelerin yüklü olması gerekir:

- Python 3.8 veya üstü
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook (opsiyonel)
