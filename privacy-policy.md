# Privacy Policy — HK Health App

_Last updated: 12 May 2026_

HK Health ("the app", "we") is a wellness companion that helps you log meals, water, walks and short habits through a chat interface. This policy explains what we collect, how we use it, and the rights you have.

We are designed for **wellness**, not medical care. We do not diagnose, treat, or manage any disease. If you need medical advice, please consult a qualified clinician.

## 1. What we collect

### a) Account data
- An **anonymous user ID** automatically generated on first launch (no email, name or phone required).
- An **assistant name** ("Ada" by default) and your **language preference**.
- Optional: email address only if you choose to link an account.

### b) Profile data you give us
- Goal (e.g. lose / maintain / gain weight), height, weight, age, sex.
- Activity level, daily calorie goal.
- Diet restrictions, allergies, food preferences.

### c) Activity & meal data
- **Meals you log** (name, calories, macros, time eaten).
- **Micro-actions** (water glasses, walks, snacks, sleep markers).
- **Photos** you take of meals, **voice recordings** describing meals (held only as long as needed; see retention).

### d) Health Connect / Apple Health (optional)
If you connect a health platform from Settings, we read **only**:
- Daily steps
- Active calories burned
- Distance walked
- Active minutes / exercise sessions

We **never** read heart-rate, sleep stages, blood-pressure, glucose, weight, or any data you have not explicitly granted.

### e) Approximate location (optional, on-demand only)
- **Only** when you tap "Share my location" after asking the assistant to recommend a nearby place.
- We request **approximate** location (city/neighbourhood level), round it to ~110 m, and send it **once** with that one chat message so the assistant can name real places near you.
- We **do not** store your location in any database, we **do not** track you in the background, and we **do not** keep a history of where you've been. After that single reply it is discarded.
- You can decline; the assistant will still help using general knowledge.

### f) Diagnostics
- App version, platform (iOS / Android), anonymous error logs.
- Used solely to fix bugs; never sold or shared.

## 2. How we use your data

- **Personalize the assistant** — show macros, calorie progress, daily streaks.
- **Generate replies** — send your message + relevant context to **Google's Gemini API** (current model: gemini-3.1-flash-lite). Google processes the request and returns text. We have configured the request so Google **does not retain** prompts for model training.
- **Find nearby places** — when (and only when) you share your location, the approximate coordinates are included in that single Gemini request, which may use Google's web-search grounding to surface real venues near you. The coordinates are not stored.
- **Local notifications** — water + evening check-in reminders, scheduled on-device.
- **Improve reliability** — anonymous error reporting.

We do **not**:
- Sell your data to third parties.
- Show ads.
- Share your data with any party other than the strictly necessary processors listed below.

## 3. Where your data lives

- **Supabase** (database & authentication) — region: Singapore. EU-style data protection.
- **Google Gemini API** — processed in Google Cloud. Configured for **zero-data-retention** for model training. Transit is HTTPS / TLS 1.3.
- **Photos and voice clips** — stored on Supabase Storage, retention as below.

## 4. Retention

| Data | Retention |
|---|---|
| Anonymous account, profile, meals | Until you delete your account |
| Photos of meals | 90 days, then auto-deleted |
| Voice recordings | 30 days, then auto-deleted |
| Error logs | 30 days |
| Local device cache (notifications, offline queue) | Until you uninstall the app |

## 5. Your rights (PDPO Hong Kong, GDPR-aligned)

You have the right to:
- **Access** all data we hold about you (in-app: Settings → "Edit profile" / "Sign out").
- **Correct** any inaccurate data (in-app, anytime).
- **Delete** your account and all associated data (in-app: Settings → "Delete account"). This is irreversible.
- **Export** your data in a machine-readable format (email us; see contact).
- **Opt out** of any non-essential processing.

## 6. Children

The app is **not intended for users under 18**. We do not knowingly collect data from minors. If we learn we have, we will delete it immediately.

## 7. Changes to this policy

We may update this policy. Material changes will be communicated in-app at least 14 days before they take effect.

## 8. Contact

For privacy questions or to exercise any of the above rights:

📧 **tureli.tunc@gmail.com**

---

# Gizlilik Politikası — HK Health App

_Son güncelleme: 12 Mayıs 2026_

HK Health ("uygulama", "biz"), sohbet üzerinden öğün, su, yürüyüş ve kısa alışkanlık kayıtlarını destekleyen bir wellness asistanıdır. Bu politika, hangi verileri topladığımızı, nasıl kullandığımızı ve sahip olduğun hakları açıklar.

Uygulama **wellness** odaklıdır; tıbbi bakım sağlamaz. Tanı koymaz, tedavi etmez, hastalık yönetmez. Tıbbi tavsiye için lütfen bir hekime danış.

## 1. Topladığımız veriler

### a) Hesap verisi
- İlk açılışta otomatik üretilen **anonim kullanıcı ID**'si (e-posta, isim, telefon yok).
- **Asistan ismi** ("Ada" varsayılan) ve **dil tercihi**.
- İsteğe bağlı: hesabını bağlarsan e-posta adresi.

### b) Profil bilgisi (sen verirsin)
- Hedef (kilo verme/koruma/alma), boy, kilo, yaş, cinsiyet.
- Aktivite seviyesi, günlük kalori hedefi.
- Diyet kısıtlamaları, alerjiler, yemek tercihleri.

### c) Aktivite & öğün verisi
- **Logladığın öğünler** (isim, kalori, makrolar, yenme zamanı).
- **Mikro-aksiyonlar** (su, yürüyüş, atıştırmalık, uyku).
- **Yemek fotoğrafları**, **sesli mesajlar** (gerektiği süre tutulur; saklama bölümüne bak).

### d) Health Connect / Apple Health (opsiyonel)
Ayarlar'dan bağlarsan **yalnızca**:
- Günlük adım
- Yakılan aktif kalori
- Mesafe
- Aktif dakika / egzersiz oturumları

okunur. Kalp atış, uyku evreleri, tansiyon, kan şekeri, kilo veya açıkça izin vermediğin **HİÇBİR** veri okunmaz.

### e) Yaklaşık konum (opsiyonel, sadece talep üzerine)
- **Yalnızca** asistandan yakındaki bir yer önermesini istedikten sonra "Konumumu paylaş" butonuna bastığında.
- **Yaklaşık** konum (semt/şehir seviyesi) alır, ~110 m'ye yuvarlar ve **tek bir** chat mesajıyla birlikte yollarız ki asistan yakınındaki gerçek yerleri söyleyebilsin.
- Konumunu **hiçbir veritabanında saklamayız**, arka planda **takip etmeyiz**, nerede olduğunun **geçmişini tutmayız**. O tek cevaptan sonra silinir.
- Reddedebilirsin; asistan genel bilgisiyle yine yardımcı olur.

### f) Hata kayıtları
- Uygulama sürümü, platform (iOS / Android), anonim hata günlükleri.
- Sadece bug fix için; satılmaz, paylaşılmaz.

## 2. Verini nasıl kullanırız

- **Asistanı kişiselleştirme** — makro, kalori ilerlemesi, günlük seri gösterme.
- **Yanıt üretme** — mesajını + ilgili bağlamı **Google Gemini API**'ye iletiriz (model: gemini-2.5-flash / gemini-2.5-pro). Google istek üzerine yanıt döner. İstekleri **Google'ın model eğitimi için saklamayacak şekilde** yapılandırdık.
- **Lokal bildirimler** — su + akşam check-in hatırlatıcıları, cihazda planlanır.
- **Sağlamlık iyileştirmesi** — anonim hata raporu.

**Yapmadıklarımız**:
- Verini üçüncü taraflara satmak.
- Reklam göstermek.
- Aşağıda listelenen zorunlu işleyiciler dışında veriyi kimseyle paylaşmak.

## 3. Verin nerede tutulur

- **Supabase** (veritabanı + kimlik doğrulama) — bölge: Singapur. AB-tarzı veri koruması.
- **Google Gemini API** — Google Cloud'da işlenir. Model eğitimi için **sıfır-veri-tutma (zero-data-retention)** yapılandırması aktif. Aktarım HTTPS / TLS 1.3.
- **Fotoğraf ve ses** — Supabase Storage'da tutulur, saklama süresi aşağıdaki gibidir.

## 4. Saklama süreleri

| Veri | Saklama |
|---|---|
| Anonim hesap, profil, öğünler | Hesabını silene kadar |
| Yemek fotoğrafları | 90 gün, sonra otomatik silinir |
| Ses kayıtları | 30 gün, sonra otomatik silinir |
| Hata kayıtları | 30 gün |
| Lokal cihaz cache'i | Uygulamayı kaldırana kadar |

## 5. Hakların (PDPO Hong Kong, GDPR-uyumlu)

Sahip olduğun haklar:
- **Erişim** — sana ait verilere uygulama içinden ulaşma (Ayarlar → "Profili düzenle" / "Çıkış yap").
- **Düzeltme** — yanlış verileri uygulama içinde dilediğin zaman düzenle.
- **Silme** — hesabını ve tüm ilgili veriyi sil (Ayarlar → "Hesabı sil"). Geri alınamaz.
- **Dışa aktarma** — verini makine-okur formatta talep et (iletişim bölümüne bak).
- **İşlemeyi reddetme** — gerekli olmayan işlemleri reddetme hakkın var.

## 6. Çocuklar

Uygulama **18 yaş altı için tasarlanmamıştır**. Bilerek küçük yaş verisi toplamayız. Toplanmış olduğunu öğrenirsek derhal sileriz.

## 7. Politika değişiklikleri

Bu politika güncellenebilir. Önemli değişiklikler en az 14 gün önceden uygulama içinden duyurulur.

## 8. İletişim

Gizlilik soruları veya yukarıdaki haklarını kullanmak için:

📧 **tureli.tunc@gmail.com**
