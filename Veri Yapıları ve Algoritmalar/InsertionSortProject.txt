## 📌 Proje 1: Insertion Sort ile [22,27,16,2,18,6] Dizisinin Sıralanması

### Aşamalar (Insertion Sort Adımları):

Insertion Sort her adımda bir elemanı doğru pozisyonuna yerleştirir:

- [22, 27, 16, 2, 18, 6] → Başlangıç (ilk eleman zaten sıralı kabul edilir)
- [22, 27, 16, 2, 18, 6] → 27 zaten doğru yerde (22 < 27)
- [16, 22, 27, 2, 18, 6] → 16 yerini buldu
- [2, 16, 22, 27, 18, 6] → 2 başa geçti
- [2, 16, 18, 22, 27, 6] → 18 doğru pozisyona
- [2, 6, 16, 18, 22, 27] → 6 doğru pozisyona

Sonuç: [2, 6, 16, 18, 22, 27]

---

### Big-O Gösterimi:

- Best Case: O(n) → Dizi zaten sıralıysa
- Worst Case: O(n²) → Dizi ters sıralıysa
- Average Case: O(n²)

Bu dizi için: Ortalama durumda işlemektedir → O(n²)

---

### Time Complexity (18 sayısı için):

- Sıralı dizi: [2, 6, 16, 18, 22, 27]
- 18 sayısı dizinin **ortasında** →  
  Cevap: Average Case

---

## [7,3,5,8,2,9,4,15,6] Dizisi için Selection Sort İlk 4 Adım

Selection Sort her adımda en küçük elemanı bulur ve başa koyar:

### Başlangıç:  
[7,3,5,8,2,9,4,15,6]

---

### Adım 1: En küçük = 2 → 2 ile 7 yer değiştirir  
[2,3,5,8,7,9,4,15,6]

---

### Adım 2: En küçük = 3 (zaten yerinde)  
[2,3,5,8,7,9,4,15,6]

---

### Adım 3: En küçük = 4 → 4 ile 5 yer değiştirir  
[2,3,4,8,7,9,5,15,6]

---

### Adım 4: En küçük = 5 → 5 ile 8 yer değiştirir  
[2,3,4,5,7,9,8,15,6]

---

İlk 4 adım sonucu:[2,3,4,5,7,9,8,15,6]

---
