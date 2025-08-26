# Biznes Tələblər Sənədi (BRD)

**Layihə Adı:** Aptek İdarəetmə Sistemi  
**Versiya:** 1.0  
**Tarix:** 2025-08-02  
**Hazırlayan:** Mehin

---

## 1. Layihə Haqqında Ümumi Məlumat
**Sənədin Məqsədi:**  
Aptek və filiallar arasında dərman inventarının idarə olunmasını asanlaşdırmaq və rəqəmsallaşdırmaq.

---

## 2. Maraqlı Tərəflər və Rollar

| Rol             | Təsviri                        | İcazələr / Funksiyalar |
|-----------------|--------------------------------|-----------------------|
| Admin           | Aptek və filial səviyyəsində idarəçi | Aptekə filiallar əlavə etmək, istifadəçilər yaratmaq, bütün məlumatlara baxış və hesabatlar |
| Depo Meneceri   | Dərman və təchizatların idarə olunması | Dərman və təchizatçı əlavə etmək, batch-ları depo/filiallara əlavə etmək, sorğuları təsdiqləmək/rədd etmək |
| Filial İşçisi   | Filialda dərman stokunu idarə edən | Dərman batch-ları tələb etmək, filial stoklarını izləmək |

---

## 3. MVP Tətbiq Sahəsi
- Aptek daxili filial hesablarının yaradılması  
- Dərman və təchizatçıların əlavə və idarə olunması  
- Depo və filiallar arasında dərman batch-larının tələb və təsdiqi  
- Filiallararası daxili tələblər sistemi  
- Təsdiq/rədd funksiyaları və şərh əlavə olunması  
- Admin üçün bütün məlumatlara görünüş və nəzarət  
- Süni intellekt və maşın öyrənmə funksiyaları MVP-də yoxdur  

---

## 4. Funksional Tələblər (FR)

| ID   | Funksional Tələb                                | Rol                   |
|------|-------------------------------------------------|----------------------|
| FR1  | Aptekə maksimum 10 filial əlavə edə bilmək     | Admin                |
| FR2  | İstifadəçilər yaratmaq (depo meneceri/filial işçisi) | Admin           |
| FR3  | Dərman və təchizatçı əlavə etmək və idarə etmək | Depo Meneceri        |
| FR4  | Dərman batch-larını depo və filiallara əlavə etmək | Depo Meneceri      |
| FR5  | Batch-ları depo/filiallardan tələb etmək       | Filial İşçisi        |
| FR6  | Sorğuları təsdiqləmək/rədd etmək və şərh əlavə etmək | Depo Meneceri    |
| FR7  | Bütün məlumatlara baxış və hesabatlar          | Admin                |

---

## 5. Funksional Olmayan Tələblər (NFR)

| ID   | Tələb |
|------|---------------------------------------------|
| NFR1 | Eyni vaxtda çox istifadəçi üçün performans itkisiz işləmək |
| NFR2 | Rol əsaslı giriş nəzarəti tətbiq etmək |
| NFR3 | Məlumatları sənaye standartlarına uyğun şifrələmək |
| NFR4 | Desktop və tablet brauzerlərdə cavabdeh dizayn |
| NFR5 | Əsas əməliyyatlar üçün audit qeydiyyatı (məs: dərman əlavə etmə, sorğu təsdiqi) |

---

## 6. Fərziyyələr və Məhdudiyyətlər

**Fərziyyələr:**  
- Hər aptek yalnız bir depo menecerinə malikdir, maksimum 10 filial ola bilər.  
- Hər filial yalnız bir işçi ilə işləyir.  
- MVP-də dərman satış xüsusiyyətləri yoxdur.  
- AI/ML funksiyaları MVP çərçivəsinə daxil deyil.  

**Məhdudiyyətlər:**  
- POS və xarici satış sistemləri ilə inteqrasiya yoxdur.  
- Süni intellekt və maşın öyrənmə modulları yoxdur.  

---

## 7. Uğur Ölçüləri
- Bütün dərman batch-larının mənşəyi və təyinatı izlənə biləcək.  
- Sistem eyni anda 100 tələbi 2 saniyə ərzində cavablandıra biləcək.  
- Bütün inventar hərəkətləri üçün audit izi təmin olunacaq.  
