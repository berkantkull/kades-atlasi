# Kadeş Atlası

**II. Ramses'in MÖ ~1274 Kadeş Seferi — Etkileşimli Dijital Harita (Prototip v0.1)**

Kadeş Atlası, tarihi dijital teknolojilerle buluşturan bir **dijital beşeriyat** (digital humanities) projesidir: Mısır kaynaklarının (Pentaur Şiiri, Rapor ve tapınak kabartmaları) izdiğiği Kadeş sefer güzergâhını etkileşimli bir harita üzerinde sunar.

Proje üç modül olarak tasarlanmıştır; bu depo **1. Modül — Etkileşimli Sefer Haritası**'nın prototipini içerir:

1. **Etkileşimli sefer haritası + zaman çizelgesi** (bu depo)
2. Kaynak veri tabanı — çeviriler, kişi/yer/kavram etiketleri *(planlanan)*
3. Geç Tunç Çağı diplomasi ağının görselleştirilmesi *(planlanan)*

## Çalıştırma

Kurulum gerektirmez: `index.html` dosyasını çift tıklayıp tarayıcıda açın.
(Yalnızca Leaflet kütüphanesi ve harita karoları CDN'den geldiği için internet bağlantısı gerekir.)

## v0.1 Özellikleri

- **9 sefer etabı**: Pi-Ramesses → Tjaru/Sile → Sina kuyuları → Gazze → Yafa → Sayda → Bekaa → Şabtuna → Kadeş; her etapda açıklama balonu
- **Muharebe günü katmanı**: sahte istihbarat, Hitit taarruzu (2.500 savaş arabası), Ramses'in karşı taarruzu, Ne'arin birliklerinin varışı, Halep yanılgısı
- **Siyasi harita katmanı**: Mısır ve Hitit etki alanları (şematik), Amurru çekişme bölgesi, başkentler (Pi-Ramesses, Hattuşaş)
- **3 altyapı seçeneği**: uydu / arazi / sokak haritası
- Kenar çubuğundan etaba tıklayınca haritaya uçuş ve balon açma

## Teknoloji

Tek dosyalık statik uygulama: Leaflet 1.9.4 (CDN), vanilla HTML/CSS/JS. Kurulum, derleme veya sunucu yok.

## Kaynaklar

- Pentaur Şiiri (*Poem of Pentaur*), Rapor (*Bulletin*) ve Kadeş kabartmaları: Ebu Simbel, Karnak, Luksor, Ramesseum, Abydos
- J. H. Breasted, *Ancient Records of Egypt*, Cilt II (Chicago, 1906) — telifsiz çeviri tabanı
- Ayrıntılı akademik kaynakça, proje ilerledikçe eklenecektir.

## Bilimsel Not

Koordinatlar **temsilîdir**; Gazze'nin kuzeyindeki güzergâh, kaynaklardaki etap adlarından hareketle yapılan akademik **rekonstrüksiyondur** (kıyı hattı + Bekaa Vadisi). "≈ yaklaşık konum" etiketli noktalar, konumu özellikle tartışmalı olanlardır. Siyasi alanlar (Mısır, Hatti, Amurru) kesin sınır değil, yaklaşık **etki alanlarıdır**. Güzergâh doğrulaması danışman hocayla birlikte yürütülmektedir.

## Yol Haritası

- [ ] v0.2 — Zaman kaydırıcısı (Shemu 1/9 → 3/9 sefer takvimi animasyonu)
- [ ] v0.2 — Kaynak metin balonları (Pentaur Şiiri pasajları)
- [ ] Modül 2 — Kaynak veri tabanı (etiketli çeviriler)
- [ ] Modül 3 — Diplomasi ağı görselleştirmesi

## Lisans

Belirlenecek (öneri: kod için MIT, içerik için CC BY 4.0).
