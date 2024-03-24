
# yzm563 ivb519 Vize Projesi

Vize projesinde, gozetimli ogrenme metoduyla (supervised learning) iki sinifli siniflandirma yapabilen bir yapay ogrenme modelini python kodunda gelistirecegiz.

Iki opsiyondan birini secin. Iki opsiyon icin de beklentim ayni:

- Egitim (30 puan)
- Tahmin uretme (20 puan)
- Metrik hesaplama (50 puan)

## Egitim 

(30 puan)

Derste gordugumuz iki modeli veya istediginiz bir modeli train veri setinde egitin.

1) Multi-layer perceptron: sklearn.neural_network.MLPClassifier
2) Bayesian classifier: sklearn.naive_bayes.GaussianNB

## Tahmin Uretme

(20 puan)

1- Egittimiz modeli kullanarak train setinde tahminler uretin.
2- Egittimiz modeli kullanarak test setinde tahminler uretin.

## Metrik Hesaplama

(50 puan)

1- Egittigimiz modeli test verisetine uygulayip performansini degerlendirelim.
2- Her 2 grup icin hata oraninin ne oldugunu gosterin
3- En cok hatali tahmin edilen sinifin hangisi oldugunu gosterin
4- Test seti uzerindeki precision, recall, f1-score hesaplayin
5- Train seti uzerindeki precision, recall, f1-score hesaplayin


## Opsiyon 1

Kendi sececeginiz bir veri setinde ve kendi sectiginiz herhangi bir iki sinifli siniflandirma modeli ile projeyi gerceklestirebilirsiniz. Modeli egitmek, test ve train setlerinde tahmin uretmek ve performans metrik hesaplayan kodu yazmanizi bekliyorum. 

Opsiyon 2 icin verilen `vize_assignment_notebook_starter.ipynb` dosyasini referans olarak kullanabilirsiniz.


## Opsiyon 2

Kendi secmek istediginiz bir problem veya veri seti yoksa, asagida verilen verisetini derste gordugumuz kredi skoru tahmini problemi icin kullanabilirsiniz.


Kredi skoru tahmini: Poor vs Good

Veri seti: https://drive.google.com/drive/folders/1hTIzpEW8XP2Tu26xb5cSYi8qUZTTmUpT?usp=sharing 

Bu dosyadaki `vize_assignment_notebook_starter.ipynb` notebookunu baslangic olarak kullanin ve yukarda belirtilen kisimlari kodlayin.


## Proje teslimi

- Teslim tarihi: 7 Nisan 2024 23:59 TR saatiyle
- Format: butun kodunuz bir jupyter notebook icinde yukardan asagi calistirilabilir sekilde olmali.
- Teslim: ardaakdemir1@gmail.com adresine mail gonderin
    - Konu: \{Ders Kodu\} \{Isim Soyisim\} Vize Projesi
    - jupyter notebook as attachment



