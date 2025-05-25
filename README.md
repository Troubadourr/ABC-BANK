# ABC Bank Arayüz Uygulaması

Bu uygulama, kullanıcıların sanal bir banka arayüzü üzerinden döviz işlemleri, para yatırma/çekme, havale ve işlem geçmişini yönetmelerini sağlar.

## Gereksinimler

- Python
- İnternet bağlantısı (döviz kuru için API kullanımı)
- Aşağıdaki Python kütüphaneleri:


## Kullanılan Kütüphaneler

- tkinter
- requests
- pillow


## Özellikler

- Hesap oluşturma ve giriş yapma
- Şifre sıfırlama
- Döviz dönüştürme
- Havale işlemleri
- İşlem geçmişi görüntüleme ve silme

## Notlar ( ÖNEMLİ !!! )

- `kullanicilar.json` veritabanı dosyası otomatik olarak oluşur.
- Logo olarak ".ico" ve ".png" dosyalarını da aynı şekilde sizin bilgisayarınızda dosyalar neredeyse oranın yolunu kopyalayıp yol kısmına yapıştırmanız gereklidir.Aksi takdirde sistem hata verir ve çöker.
- Örnek olarak "C:\Users\aarda\Desktop\ADVANCED PHYTON PROJESİ\c_abc_bank_logo.png" şeklinde kendi yolunuzu koda kopyalayıp o şekilde çalıştırmanız gerekmektedir.

## Dosya Hazırlığı

- Uygulama.py dosyasını çalıştıracağın klasöre koy.
- Şu ikon ve resim dosyaları doğru konumda olmalı:

b_abc_bank_logo.ico
c_abc_bank_logo.png

## Çalıştırma

- Komut satırını aç:
- python Uygulama.py yaz.

## Ana Ekran Butonları

- Hesap Oluştur: Yeni kullanıcı oluştur.
- Giriş Yap: Var olan kullanıcıyla giriş.
- Çıkış: Uygulamayı kapat.

## Hesap Oluştur

- Kullanıcı ID (en az 6 rakam)
- Kart bilgileri (doğru formatta)
- Şifre (büyük harf + özel karakter + rakam)

## Giriş Yap

- Kullanıcı ID + Şifre gir.
- “Şifremi Unuttum” varsa → isim + kart son 4 hane ile yenile.

## Banka Paneli Özellikleri

- Para İşlemleri: Yatır / Çek (TRY, USD, EUR)
- Döviz İşlemleri: Döviz çevir.(API kullanır.)
- Havale: Başka kullanıcıya para gönder.
- İşlem Geçmişi: Son 20 işlem görüntüle / sil
- Çıkış: Panelden çık.

## Veri Kaydı
- Tüm bilgiler kullanicilar.json dosyasında kaydediliyor.