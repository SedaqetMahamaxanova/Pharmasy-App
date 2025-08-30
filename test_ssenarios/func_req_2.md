# Test Scenarios for FR2 – İstifadəçilər yaratmaq (Depo Meneceri / Filial İşçisi)

---

## FR2_TS1 – Depo Meneceri istifadəçisi yaratmaq
**Məqsəd:** Admin depo meneceri istifadəçisini uğurla yarada bilməlidir.  
 
**Gözlənilən Nəticə:**
- Yeni depo meneceri uğurla yaradılır.  
- Sistem təsdiq mesajı göstərir: *“İstifadəçi uğurla yaradıldı”*.  
- Depo meneceri login səhifəsindən uğurla daxil ola bilir.  

---

## FR2_TS2 – Filial İşçisi istifadəçisi yaratmaq
**Məqsəd:** Admin filial işçisi istifadəçisini uğurla yarada bilməlidir.  


**Gözlənilən Nəticə:**
- Yeni filial işçisi uğurla yaradılır.  
- Sistem təsdiq mesajı göstərir.  
- Filial işçisi yalnız öz roluna aid menyu və funksiyaları görə bilir.  

---

## FR2_TS3– Yanlış məlumatlarla istifadəçi yaratmaq
**Məqsəd:** Sistem yalnış və ya natamam məlumat daxil edildikdə istifadəçi yaratmamalıdır.  
  
**Gözlənilən Nəticə:**
- Sistem səhv mesajları göstərir:  
  - “Email düzgün formatda olmalıdır”  
  - “Şifrə minimum 6 simvol olmalıdır”  
  - “Rol seçilməlidir”  
- İstifadəçi yaradılmır.  


