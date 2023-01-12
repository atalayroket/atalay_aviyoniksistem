# Aviyonik Sistem

<br>

> **Ticari Aviyonik Sistem**

Takımımızın kendi imkanlarıyla ürettiği roket motoru ile uçurulan [ISPAT 01](https://www.instagram.com/p/CeEz-f6FkrU/) ve [ISPAT 02](https://www.instagram.com/p/CmLr6XANZut/) roketlerimizin aviyonik sistemi olarak kullanılmış ve başarılı bir şekilde roketin paraşütlerini açarak roketlerimizi sağlam şekilde yere indirmiştir. 

<details>
<summary>Özellikleri</summary>
 
- STM32F103C8T6 işlemci ile MS5611 ve BMP280 basınç sensörleri kullanılmaktadır.
- 3 adet programlanabilir gerekli akım spesifikasyonlarına karşı çıkış bulunmaktadır.
- Fünye hattındaki ya da sistemdeki hata ve uyarıları buzzer ile ikaz ediyor.
- Sistem M2 konnektöre sahip kompoakt ve başka sistemlere entegre olabilir ya da tek başına kullanılabilir yapıdadır.
- Diğer sistemlere UART hattı ile üzerinden veri besleme yapabiliyor.
- Otomatik apogee tespi algoritması bulunmaktadır.
</details>

| Ateşleme | Haberleşme | Montaj |
| ------------ | ------------- | ------------- | 
| <img src="https://user-images.githubusercontent.com/104703949/210207518-d1f72f2a-654a-430a-b381-8498977c4e05.png" width="150"> | <img src="https://user-images.githubusercontent.com/104703949/210207470-2fee4fe9-a169-4ef1-832e-4a7ab2e6fdf0.png" width="133"> | <img src="https://user-images.githubusercontent.com/104703949/210205524-735d3b4d-4665-4cad-9ce4-8d2363b6011f.gif" width="500"> | 

<br>
<br>

> **Yarışma Aviyonik Sistem**

Teknofest Roket Yarışması için hazırlanılmıştır. 

<details>
<summary>Özellikleri</summary>
- Aviyonik sistemimiz 4 uçuş bilgisayarı ve 1 yer istasyonudan oluşmaktadır.
- Kartlarımızın arka yüzünde STM32F103RB işlemci olup olup ön yüzünde ise kullanacağımız sensörler, gps, haberleşme, ateşleme devresi ve voltaj regülatörü bulunuyor. 
- Kartımız 7-12V ile beslenmekte ve üzerinde güç ledi bulunmaktadır. 
- Voltaj regülatörü 3.3V 1.5A çıkış vermektedir.
- Ateşleme devresi için mosfet ile optoptokuplör kullanılmıştır.
- Sensör için BME280 basınç sensörü ile ADXL345 ivme sensörü, gps modülü olarak NEO6M, yer istasyonu ile haberleşmek için LORA iletişim modülü kullanılmıştır. 
- Senörler için I2C, gps ve iletişim modülü için UART protokolü kullanılmıştır.
- Ana ve Yedek Sistem kartındaki verileri, Haberleşme kartına SPI haberleşmesi ile aktarılmaktadır.
- Sensör verileri Kalman Filtresinden geçirilmektedir. 
- İletişim modülümüz 433MHz çalışma frekansında 8 km mesafede veri alışverişi yapabilmektedir.
- Yer İstasyonu kartımızdan, Roket ve Görev Yükü bilgileri seri port ile arayüzde gösterilmiş ve Excel ile kaydetme işlemi yapılmıştır. Ayrıca gelen veriler seri port üzerinden başka bir bilgisayara gönderebilmektedir.
</details>

| Ana Sistem | Yedek Sistem | Haberleşme | Görev Yükü |
| ------------ | ------------- | ------------- | ------------- |
| <img src="https://user-images.githubusercontent.com/104703949/178975971-cedd0c6c-6338-451e-ba90-f94a9db79941.JPG" width="250"> | <img src="https://user-images.githubusercontent.com/104703949/178975949-c73ea188-78ee-422f-ae1e-443e428f9f21.JPG" width="250"> | <img src="https://user-images.githubusercontent.com/104703949/178976015-2aa9b74b-eeaf-49ca-b19e-2ab924a77f52.JPG" width="240"> | <img src="https://user-images.githubusercontent.com/104703949/178975987-bcb0d98b-03aa-4c32-86b0-55a938d579de.JPG" width="250">|

