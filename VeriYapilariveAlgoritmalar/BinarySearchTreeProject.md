## 📌 Proje 3: Binary Search Tree Aşamaları

### İlk eleman BST’nin kökü (root) olur:
- **Root = 7**

---

### Sonraki elemanlar BST kurallarına göre yerleştirilir:
- **5 < 7** → `5`, 7'nin **soluna**
- **1 < 7**, **1 < 5** → `1`, 5'in **soluna**
- **8 > 7** → `8`, 7'nin **sağına**
- **3 < 7**, **3 < 5**, **3 > 1** → `3`, 1'in **sağına**
- **6 < 7**, **6 > 5** → `6`, 5'in **sağına**
- **0 < 7**, **0 < 5**, **0 < 1** → `0`, 1'in **soluna**
- **9 > 7**, **9 > 8** → `9`, 8'in **sağına**
- **4 < 7**, **4 < 5**, **4 > 1**, **4 > 3** → `4`, 3'ün **sağına**
- **2 < 7**, **2 < 5**, **2 > 1**, **2 < 3** → `2`, 3'ün **soluna**

---

## Ağaç Yapısı Açıklaması

```
        7
       / \
      5   8
     / \    \
    1   6    9
   / \
  0   3
     / \
    2   4
```

---

### Açıklamalı Örnek:

- **Root 7’dir.**
- Root’un solunda **5**, sağında **8** bulunur.
- 5’in solunda **1**, sağında **6** bulunur.
- 1’in solunda **0**, sağında **3** bulunur.
- 3’ün solunda **2**, sağında **4** bulunur.
- 8’in sağında **9** bulunur.
