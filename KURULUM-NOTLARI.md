# Mente Web — kurulum notları

## Klasör yapısı

```
index.html            → www.mente.com.tr
favicon.ico           → sekme ikonu
assets/               → logo, ikonlar, paylaşım görseli
honingcalc/index.html → www.mente.com.tr/honingcalc   (EKLENECEK)
tascalc/index.html    → www.mente.com.tr/tascalc       (EKLENECEK)
.nojekyll             → GitHub Pages dosyaları olduğu gibi yayınlasın diye
```

## Yayına alma (GitHub Pages)

1. github.com → yeni repo: `mente-web`, **Public**
2. Bu klasörün içindekileri repo'ya yükle (Add file → Upload files)
3. Settings → Pages → Source: `Deploy from a branch`, branch `main`, klasör `/ (root)`
4. `kullaniciadin.github.io/mente-web` adresinde test et

## METUnic DNS kayıtları

MX ve TXT kayıtlarına DOKUNMA — e-posta onlara bağlı.

Eski Google Sites A / CNAME kayıtlarını sil, bunları ekle:

| Tip   | İsim | Değer                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | kullaniciadin.github.io  |

Sonra: Settings → Pages → Custom domain → `www.mente.com.tr` → Save
Sertifika gelince **Enforce HTTPS** kutusunu işaretle.

## Yayından önce doldurulacaklar

- [ ] İş ortakları bölümü — 4 firma adı ve birer cümle açıklama
      (sadece adının kullanılmasına onay verdiğin firmalar)
- [ ] İletişim → telefon numarası
- [ ] Footer → ticaret sicil no / vergi dairesi
- [ ] Araçlar bölümündeki linkler (/honingcalc, /tascalc) doğru mu

## Kontrol listesi

- [ ] https://www.mente.com.tr açılıyor, kilit yeşil
- [ ] mente.com.tr → www'ye yönleniyor
- [ ] /honingcalc çalışıyor
- [ ] info@mente.com.tr'ye dışarıdan test maili geldi
- [ ] Telefonda düzgün, EN düğmesi çalışıyor
- [ ] WhatsApp'ta link önizlemesinde logo çıkıyor
