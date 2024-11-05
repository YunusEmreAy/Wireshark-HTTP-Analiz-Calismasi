# Wireshark HTTP Analiz Çalışması

Bu proje, HTTP trafiğini analiz etmek amacıyla Wireshark kullanılarak gerçekleştirilen çeşitli paket yakalama işlemlerini içerir. Amaç, HTTP protokolünün detaylarını incelemek ve sunucu-istemci etkileşimini analiz etmektir.

## İçerik

- **21100011016_Odev2.pdf**: HTTP trafiğine dair yapılan analizlerin ve bulguların yer aldığı rapor.
- **21100011016_Odev2_1.pcapng**: Birinci HTTP paket yakalama işleminin verilerini içeren dosya.
- **21100011016_Odev2_2.pcapng**: İkinci HTTP paket yakalama işleminin verilerini içeren dosya.
- **21100011016_Odev2_3.pcapng**: Üçüncü HTTP paket yakalama işleminin verilerini içeren dosya.
- **21100011016_Odev2_4.pcapng**: Dördüncü HTTP paket yakalama işleminin verilerini içeren dosya.

## Projede Yapılan Çalışmalar

1. **HTTP 1.1 Protokol Kullanımı**: İlk analizde tarayıcının HTTP 1.1 sürümünü kullandığı belirlendi.
2. **IP Adresleri**: Bilgisayarın ve wireshark.grydeske.net sunucusunun IP adresleri tespit edildi.
3. **GET İstekleri**: Farklı dosyalarda, tarayıcı tarafından yapılan GET isteklerinin sayısı ve sunucu tarafından verilen yanıtlar analiz edildi.
4. **İçerik Boyutları**: Sunucudan tarayıcıya gönderilen içeriklerin byte cinsinden boyutları belirlendi.
5. **Paralel İndirme**: İki resim dosyasının paralel olarak indirildiği gözlemlendi.
6. **Yetkilendirme Yanıtı**: İlk GET isteğine sunucunun "401 Unauthorized" yanıtı döndürmesi ve sonraki istekte kullanıcı adı ve şifre ile başarılı bir erişim sağlanması incelendi.

## Kullanılan Araçlar

- **Wireshark**: HTTP trafiğini yakalama ve analiz etme aracı. [Wireshark'ı indirin](https://www.wireshark.org/)
- **Kaynaklar**: Veriler, [wireshark.grydeske.net](http://wireshark.grydeske.net) üzerinden sağlanan web sayfaları kullanılarak yakalanmıştır.

## Nasıl Kullanılır?

1. **Wireshark Dosyalarını Açın**: `21100011016_Odev2_1.pcapng`, `21100011016_Odev2_2.pcapng`, `21100011016_Odev2_3.pcapng` ve `21100011016_Odev2_4.pcapng` dosyalarını Wireshark ile açarak analiz yapabilirsiniz.
2. **PDF Raporunu İnceleyin**: `21100011016_Odev2.pdf` dosyasında, analiz sonuçları ve detaylı açıklamalar yer almaktadır.

---

Bu çalışma, HTTP protokolü üzerinden gerçekleştirilen paket alışverişlerinin incelenmesini amaçlar. Sunucu-istemci etkileşimlerinin detaylarını anlamak ve analiz becerilerini geliştirmek için hazırlanmıştır.

