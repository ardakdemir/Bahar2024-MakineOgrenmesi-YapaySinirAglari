
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

Kendi secmek istediginiz bir problem veya veri seti yoksa, asagida verilen verisetini derste gordugumuz kredi skoru tahmini problemi icin kullanabilirsiniz. Bunun icin `pandas`, `sklearn` ve `numpy` kutuphanelerinden faydalanacagiz.


Kredi skoru tahmini: Poor vs Good

Veri seti: https://drive.google.com/drive/folders/1hTIzpEW8XP2Tu26xb5cSYi8qUZTTmUpT?usp=sharing 

Bu dosyadaki `vize_assignment_notebook_starter.ipynb` notebookunu baslangic olarak kullanin ve yukarda belirtilen kisimlari kodlayin.

### Sample data

```
Annual_Income,Num_of_Delayed_Payment,Monthly_Inhand_Salary,Credit_Score
22380.18,16.0,1385.2645393571067,Good
99166.77,7.0,8305.8975,Good
10496.255,17.0,1141.6879166666668,Poor
44438.41,2.0,3974.200833333334,Good
15330.305,19.0,1135.5254166666666,Good
80692.28,21.0,6856.356666666668,Poor
24858.67,13.0,1977.555833333333,Good
```

### Input

```
['Num_of_Delayed_Payment','Annual_Income','Monthly_Inhand_Salary']

```

### Output Column

```
Credit_Score
```

## Proje teslimi

- Teslim tarihi: 7 Nisan 2024 23:59 TR saatiyle
- Format: butun kodunuz bir jupyter notebook icinde yukardan asagi calistirilabilir sekilde olmali.
- Teslim: ardaakdemir1@gmail.com adresine mail gonderin
    - Konu: \[Ders Kodu\] \[Isim Soyisim\] Vize Projesi
    - jupyter notebook as attachment



