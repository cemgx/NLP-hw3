# Reddit'teki bir konu başlığını baz alarak içerisindeki cümleleri duygu analizi yapıp sınıflandıran kod.

### İlk önce kütüphaneleri import ederek başladım.

![1](https://github.com/cemgx/ddi-odev-3/assets/95704587/bef31d08-e454-49b5-b641-49fd1968fd36)

<br/><br/>

### Sonrasında "https://www.reddit.com/prefs/apps" sayfasından id ve secret kodumu oluşturup koda yazdım.

![3](https://user-images.githubusercontent.com/95704587/211209184-5f53fa6e-c870-4dd6-b1f5-bef7df0cd959.png)
![2](https://user-images.githubusercontent.com/95704587/211209187-bd9abd76-98d5-4aac-8865-67bad4c1f8ec.png)
<br/><br/>

### Reddit'te "sports" başlığı altında bütün başlıkları çekip kaç adet olduğunu ekrana yazdırdım. Ardından "basliklar.csv" dosyasına bütün başlıkları yazdırdım.

![4](https://user-images.githubusercontent.com/95704587/211210789-b04b2c5d-aae0-4cd4-8100-e12bd7ed39e5.png)
<br/><br/>

### nltk kütüphanesini import edip duygu analizi yapılabilebilmesi için vader_lexicon'u indirdim ve nltk.sentiment.vader'in içerisinden SentimentIntensityAnalyzer'i (duygu yoğunluğunu analiz eder) import edip ilk 3 başlığın duygu analizini ekrana yazdırdım.

![5](https://user-images.githubusercontent.com/95704587/211211543-0980ea3a-0cbc-43ef-9c90-765ff66e576c.png)
<br/><br/>

### Sonrasında ekrana compound edilmiş veriyi yazdırdım.

![6](https://user-images.githubusercontent.com/95704587/211211644-fd4691c5-843c-484b-aab4-e33cd33229f8.png)
<br/><br/>

### Verilerde compound sayısı 0.2'den büyük olanları "1", -0.2'den küçük olanları "-1", diğerlerini ise "0" olarak label başlığı altında yazdırdım.

![7](https://user-images.githubusercontent.com/95704587/211211783-30ef8098-5637-40e0-8d2b-c335e804b0ec.png)
<br/><br/>

### Son verileri de "reddit_basliklar_labels.csv" dosyasına yazdırdım.

![8](https://user-images.githubusercontent.com/95704587/211211817-0523da02-4527-4c5b-a354-15b12970b85e.png)
<br/><br/>

### -1, 0, 1 verilerinden kaç adet olduğunu ekrana yazdırıp baktım.

![9](https://user-images.githubusercontent.com/95704587/211211888-23329a59-c2c2-49e0-9546-dfcf581690f3.png)
<br/><br/>

### Pozitif ve negatif başlıklar adı altında iki kategori için de ilk 5 veriyi yazdırdım.

![10](https://user-images.githubusercontent.com/95704587/211211937-683e8972-cd8c-4904-96d5-4a9c45f75b27.png)
<br/><br/>

### En son olarak da bütün verileri grafik tablosu oluşturarak ekrana yazdırdım.

![11](https://user-images.githubusercontent.com/95704587/211212040-70659ac2-c7fc-4093-beff-47fb10d6d27c.png)
<br/><br/>

# Bu ödevi Cem GÖL ve Kerem AYLANÇ olarak ortak yaptık.
