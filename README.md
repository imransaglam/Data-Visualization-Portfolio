Portfolyo-1

İstanbul Büyükşehir Belediyesi Açık Veri Portalı'nda (https://data.ibb.gov.tr/dataset) bulunan "İsmek'ten Eğitim Alan Vatandaş Verisi" veri setini kullanarak Looker Studio'da bir rapor oluşturdum. Bu rapor, 2019-2023 yılları arasında İSMEK'e kesin kayıt yaptıran kursiyerlerin tercih ettikleri eğitim alanlarını, bu alanlardaki hangi programları tercih ettiklerini, kursiyerlerin eğitim ve çalışma durumlarını, ayrıca hangi dönem aralığında kesin kayıt yaptıran kursiyer sayısını incelemektedir.Raporu daha ayrıntılı incelemek https://lookerstudio.google.com/reporting/2f52011c-7601-4bcf-bb6c-69a21d1b510b
 için  linkten ulaşabilirsiniz. 
 
![image](https://github.com/imransaglam/Portfolio/assets/108897583/8e999a4e-2927-44b4-ac47-d41a35846cf3)

Portfolyo -2

BigQuery kullanarak "USA Names" adlı veri kümesini incelendim. Bu veri kümesi, 1910 ile 2013 yılları arasında Amerika Birleşik Devletleri'nde doğan bebeklerin isimlerini içermekteydi. SQL tabanlı sorgular yazarak veri setini analiz ettik.

Bu süreçte aşağıdaki adımları takip ettim:
-Bir veri kümesini sorgulama
-Özel bir tablo oluşturma
-Verileri bir tabloya yükleme
-Bir tabloyu sorgulama

Bu adımları başarıyla tamamlayarak elde ettiğim veriyi, Looker Data Studio platformunda görselleştirdim. Bu portfolio’nun amacı; BigQuery kullanımı, veri analizi ve görselleştirme konularında yeteneklerimizi geliştirmemi sağladı.

 ![image](https://github.com/imransaglam/Portfolio/assets/108897583/cd64ef70-3c40-4f44-a8c7-5d8f021897fa)
 ![image](https://github.com/imransaglam/Portfolio/assets/108897583/b5385da6-6143-42af-a5dc-23a67d217ad8)
 ![image](https://github.com/imransaglam/Portfolio/assets/108897583/2668481c-2793-437d-9f29-401119ab66c8)
 ![image](https://github.com/imransaglam/Portfolio/assets/108897583/798d7198-4d26-40a8-bf61-1fce30220248)

 Portfolyo -3
 
BigQuery ve SQL konularında yeteneklerimi arttırarak, veri temizleme ,veri dönüştürme ve daha iyi veri görselleştirme nasıl yapılabilir konularına odaklandım.Bu kapsamda portfolyo çalışması için Big Query ile eccomerce tablosuna veri seti oluşturdum ardından Data Prep ile aşağıda belirtilen düzeltmeleri yaparak, yeni bir tablo oluşturdum. 

-Change productSKU type to String

-Delete itemQuantity

-Delete itemRevenue 

-Remove duplicate rows

-Delete rows where ISMISSINGtotalTransactionRevenue 

-Keep rows where type == ' PAGE ' 

-Keep rows 8 

-Concatenate fullVisitorid, visitId

-Create eCommerceAction_label from 9 case conditions on eCommerceAction_type

![image](https://github.com/imransaglam/Portfolio/assets/108897583/ed1eae36-6058-45c6-b9b5-050464ab5c0a)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/074075e4-01bb-4cf4-b877-946697890051)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/a64ca7f5-bbfd-4d25-83f3-b54e2f7b610d)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/e16eaf7e-db18-4525-9688-b89c0bc35cc8)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/2cb099ee-f315-4241-a617-8e2cd4da5c55)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/7b2b10a5-d9d9-4954-ba24-6c9bd7b49eb8)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/70e8e877-3daa-40dc-a34d-1eaa3c85f96b)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/da56c252-6d8d-4b9c-a156-302810ab8ba6)
![image](https://github.com/imransaglam/Portfolio/assets/108897583/bf360673-f2e5-4aa0-b18f-7d1f630b7064)

Portfolyo-4

https://www.kaggle.com/ adresinden aldığım "120 years of Olympic history: athletes and results" veri seti doğrultusunda olimpiyat tarihi boyunca elde edilen verileri inceledim. Looker Studio kullanarak bu verilerden dashboard oluşturdum.
Kullanılan veri seti: https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results
Looker Studio'da oluşturduğum dashboard: https://lookerstudio.google.com/reporting/2c515ece-84d9-4192-889e-28a3d5d94d23/page/p_rtt6ho9bed
![image](https://github.com/imransaglam/Portfolio/assets/108897583/b779fa69-35e6-49dd-a966-4f148fab730d)














 
  

