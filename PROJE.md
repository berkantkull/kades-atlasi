# Kadeş Atlası — Proje Tanımı

> Bu belge, projenin yazılım dışı çerçevesini tanımlar: amacı, araştırma
> sorularını, yöntemini ve planlanan çıktıları. Danışman hocayla birlikte
> geliştirilecek yaşayan bir metindir.

**Çalışma adı (öneri):** *Kadeş Atlası: Kadeş Savaşı (MÖ ~1274) ve Doğu
Akdeniz Siyasi Coğrafyasının Dijital Beşeriyat Yöntemleriyle Yeniden İnşası*

## Proje ne değildir?

Yalnızca bir harita yazılımı değildir. Yazılım ve bu depo, aşağıdaki araştırma
sorularına hizmet eden **araç ve çıktılardır**. Projenin özü, kaynak eleştirisine
dayanan bir **araştırma**dır.

## Amaç

Mısır ve Hitit kaynaklarının anlattığı Kadeş Savaşı'nı ve MÖ 13. yüzyıl başının
Doğu Akdeniz siyasi coğrafyasını; mekân, metin ve aktörleri birbirine bağlayan,
kaynak referanslı, açık erişimli bir dijital platform üzerinden yeniden inşa
etmek ve belirsizlikleri şeffaf biçimde görünür kılmak.

## Araştırma Soruları

1. **Güzergâh doğrulama:** Mısır kaynaklarının (Pentaur Şiiri, Rapor/Bulletin,
   tapınak kabartmaları) aktardığı sefer güzergâhı, günümüz coğrafi ve
   arkeolojik verileriyle ne ölçüde uyumludur; hangi noktalar kesin, hangileri
   rekonstrüksiyondur?
2. **Siyasi coğrafya:** Mısır–Hatti rekabetinin çatışma hattı (Amurru) ve iki
   devletin etki alanları, mevcut akademik konsensüs temelinde nasıl haritalanabilir?
3. **Sistem okuması:** Metin–mekân–aktör ilişkileri dijital olarak birbirine
   bağlandığında, Kadeş tek bir muharebe olarak değil bir uluslararası diploması
   sisteminin kilit taşı olarak nasıl okunabilir?

## Yöntem

- **Kaynak eleştirisi:** Şiir, Rapor ve kabartmaların karşılaştırmalı okuması;
  Breasted (1906, kamu malı) çeviri tabanı üzerinde danışman gözetiminde Türkçe
  aktarımlar.
- **Referans veri kümeleri:** Pleiades (CC BY) yer adları gazetayeri; sınır
  gösterimlerinde güncel akademik atıflar (ör. AWMC).
- **Belirsizliğin görselleştirilmesi:** Her veri öğesi üç kademeli kesinlik
  etiketi taşır: kesin / büyük ölçüde kabul gören / rekonstrüksiyon.
- **GIS ve ağ analizi:** güzergâh ve arazi ilişkisi (QGIS); Geç Tunç Çağı
  diplomasi ağının görselleştirilmesi (Modül 3).

## Modüller

| Modül | İçerik | Araştırmadaki işlevi | Durum |
|---|---|---|---|
| 1 | Etkileşimli sefer haritası ve siyasi coğrafya | Mekânsal yeniden inşa | Prototip v0.2 yayında |
| 2 | Kaynak veri tabanı (çeviriler; kişi-yer-kavram etiketleri) | Metin-mekân-aktör bağlantısı | Planlanan |
| 3 | Diplomasi ağı görselleştirmesi | Sistem okuması | Planlanan |

## Planlanan Çıktılar

1. Açık erişimli platform (GitHub Pages)
2. Açık veri kümesi (GeoJSON/JSON, atıflı)
3. Lisans/bitirme tezi
4. TÜBİTAK 2209-A başvuru dosyası
5. Makale ve/veya konferans bildirisi hedefi

## Bilimsel Dürüstlük Notları

- Antik devletlerde modern anlamda kesin sınır yoktur; siyasi alanlar "yaklaşık
  etki alanı" olarak gösterilir ve kaynaklarla gerekçelendirilir.
- Güzergâhın Gazze'nin kuzeyi rekonstrüksiyondur; alternatif hipotezler ayrı
  katman olarak gösterilecektir.
- Üçüncü taraf veri ve çevirilerde lisans/atıf koşullarına uyulur (Pleiades:
  CC BY; Breasted 1906: kamu malı).

---
*Sürüm: 0.1 (17 Eylül 2026) — danışman hocanın görüşleriyle güncellenecektir.*
