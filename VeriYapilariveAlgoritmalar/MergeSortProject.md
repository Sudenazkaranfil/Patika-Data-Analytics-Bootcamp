## 📌 Proje 2: Merge Sort Aşamaları

### 1. Adım: Diziyi ikiye bölerek parçalayalım  
[16, 21, 11] ve [8, 12, 22]

---

### 2. Adım: Her parçayı tekrar böl  
[16, 21, 11] → [16], [21], [11]  
[8, 12, 22] → [8], [12], [22]

---

### 3. Adım: Alt dizileri kendi aralarında sıralı şekilde birleştir  
- [16] ve [21] → [16, 21], sonra bu ikili ile [11]:  
  → Merge: [11, 16, 21]

- [8] ve [12] → [8, 12], sonra bu ikili ile [22]:  
  → Merge: [8, 12, 22]

---

### 4. Adım: İki ana parçayı birleştir  
[11, 16, 21] ve [8, 12, 22]
→ Merge:  
[8, 11, 12, 16, 21, 22]

---

Sonuç: [8, 11, 12, 16, 21, 22]

---

## Merge Sort Big-O Gösterimi

- **Best Case:** O(n log n)
- **Average Case:** O(n log n)  
- **Worst Case:** O(n log n)

> Merge Sort her durumda `O(n log n)` karmaşıklığına sahiptir çünkü her zaman diziyi ikiye böler ve birleştirirken tüm elemanları karşılaştırır.
