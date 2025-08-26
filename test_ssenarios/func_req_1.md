# Test Senariləri – FR1: Maksimum 10 filial əlavə etmək
**BRD Versiyası:** 1.1

---

## FR1_TS1 – Maksimum 10 filialın əlavə olunması
**Məqsəd:**  
Admin 1–10 filial əlavə edə bilir, 11-ci əlavə edilə bilmir.

**Gözlənilən nəticə:**  
- 1–10 filial uğurla əlavə olunur.  
- 11-ci filial üçün xəbərdarlıq görünür.

---

## FR1_TS2 – 0 filial əlavə edildikdə davranış
**Məqsəd:**  
Əgər hələ heç bir filial əlavə edilməyibsə, sistem ilk filialı əlavə etməyə icazə verir.

**Gözlənilən nəticə:**  
- İlk filial uğurla əlavə olunur.

---

## FR1_TS3 – Eyni adla filial əlavə etmək
**Məqsəd:**  
İki filial eyni adla əlavə edilə bilərmi?

**Gözlənilən nəticə:**  
- Sistem ya eyni adı qəbul etməməli, ya da xəbərdarlıq göstərməlidir.

---

## FR1_TS4 – Maksimum limitə çatanda xəbərdarlıq mesajı
**Məqsəd:**  
10 filial əlavə edildikdən sonra xəbərdarlıq mesajının düzgün işlədiyini yoxlamaq.

**Gözlənilən nəticə:**  
- Admin 11-ci filialı əlavə etməyə çalışanda sistem xəbərdarlıq göstərir.

---

## FR1_TS5 – İstifadəçi roluna görə filial əlavə icazəsi
**Məqsəd:**  
Admin xaricində bir istifadəçi filial əlavə edə bilərmi?

**Gözlənilən nəticə:**  
- Yalnız Admin filial əlavə edə bilər.  
- Digər rollar üçün əməliyyat rədd edilir.
