# Koleksiyoner-ve-Nadir-Eser-Pazaryeri

# Koleksiyoner ve Nadir Eser Pazaryeri Otomasyonu

Antika ve koleksiyon ürünlerinin satıcılarla alıcıları buluşturduğu çevrimiçi bir pazaryeri otomasyonu. Üniversite dersi için hazırlanan bir ekip projesidir.

> Marka adı henüz kesin değil (adaylar: **Bedesten**, **Nadide**).

## Özellikler

- Ürün arama, filtreleme ve detay görüntüleme
- Sepet ve sipariş takibi
- **Nadir eser:** Satıcı ürünü nadir eser olarak işaretler; ürün kartının sağ üst köşesinde yıldız rozeti görünür. Nadir eserler menşe, sertifika ve tahmini değer gibi ek bilgiler taşır.
- Üç kullanıcı rolü: alıcı, satıcı, yönetici

## Ekranlar

1. Giriş / Kayıt
2. Ana sayfa
3. Ürün listesi
4. Ürün detay
5. Sepet ve ödeme
6. Siparişlerim / Profil
7. Satıcı paneli
8. Yönetici paneli

## Tasarım

- **Renkler:** Espresso `#3B2A20`, Krem `#F6EFE3`, Kemik `#FFFBF3`, Zümrüt yeşili `#2F5D50`, Antik altın `#B8893B`, Nadir altın `#D4A017`
- **Yazı tipleri:** Playfair Display (başlıklar), Inter (gövde)

## Veri Yapısı (öneri)

Tüm ürünler `Urun` tablosunda tutulur. Nadir eserler, `Urun` tablosuna bağlı ayrı bir `NadirEser` tablosunda ek bilgileriyle saklanır.

## Durum

Arayüz tasarım aşaması. Sonraki adımlar: ekran çizimleri (wireframe), veri tabanı ve yazılım tasarımı.

## Ekip

- İbrahim Kerim Tatar
- Tuana Civil
- Çağdaş Doğan
