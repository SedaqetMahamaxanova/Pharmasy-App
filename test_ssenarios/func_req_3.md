# Test Scenarios for FR3 – Dərman və Təchizatçı əlavə etmək və idarə etmək (Depo Meneceri)

---

## FR3_TS1 – Yeni dərman əlavə etmək
**Məqsəd:** Depo meneceri uğurla yeni dərman əlavə edə bilməlidir.  
  

**Gözlənilən nəticə:**
- Yeni dərman uğurla əlavə olunur.  
- Sistem təsdiq mesajı göstərir: *“Dərman uğurla əlavə edildi”*.  
- Dərman siyahısında yeni dərman görünür.  

---

## FR3_TS2– Mövcud dərmanı redaktə etmək
**Məqsəd:** Depo meneceri mövcud dərmanın məlumatlarını redaktə edə bilməlidir.  
  


**Gözlənilən nəticə:**
- Dərmanın məlumatları uğurla yenilənir.  
- Sistem təsdiq mesajı göstərir.  
- Siyahıda yeni məlumat əks olunur.  

---

## FR3_TS3– Təchizatçı əlavə etmək
**Məqsəd:** Depo meneceri uğurla yeni təchizatçı əlavə edə bilməlidir.  

 
**Gözlənilən nəticə:**
- Yeni təchizatçı uğurla əlavə olunur.  
- Sistem təsdiq mesajı göstərir.  
- Təchizatçı siyahısında yeni təchizatçı görünür.  

---

## FR3_TS4 – Yanlış məlumatlarla dərman/təchizatçı əlavə etmək
**Məqsəd:** Sistem səhv və ya natamam məlumatla dərman və ya təchizatçı əlavə edilməsinə icazə verməməlidir.  

**Gözlənilən nəticə:**
- Sistem xəbərdarlıq mesajı göstərir:  
  - “Dərman adı boş ola bilməz”  
  - “Təchizatçı məlumatları tam daxil edilməlidir”  
- Heç bir məlumat bazaya əlavə olunmur.  

