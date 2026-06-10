# Test Cases

## TC-001: Homepage açılmasının yoxlanılması

**Precondition:**

* İstifadəçinin internet bağlantısı var.
* Brauzer açıqdır.

**Steps:**

1. Brauzeri aç.
2. AcademyBugs saytına daxil ol.
3. Homepage-in tam yüklənməsini yoxla.

**Expected Result:**

* Homepage düzgün açılmalıdır.
* Saytın əsas elementləri görünməlidir.

---

## TC-002: Product detail page açılmasının yoxlanılması

**Precondition:**

* AcademyBugs saytı açıqdır.

**Steps:**

1. Homepage-də hər hansı məhsulu seç.
2. Məhsulun üzərinə kliklə.
3. Product detail page-in açılmasını yoxla.

**Expected Result:**

* Product detail page düzgün açılmalıdır.
* Məhsulun adı, şəkli, qiyməti və description hissəsi görünməlidir.

---

## TC-003: Product image-in yoxlanılması

**Precondition:**

* Product detail page açıqdır.

**Steps:**

1. Məhsul səhifəsinə keç.
2. Məhsul şəklinə bax.
3. Şəklin tam görünüb-görünmədiyini yoxla.

**Expected Result:**

* Məhsul şəkli tam və düzgün görünməlidir.

---

## TC-004: Product description-un dilinin yoxlanılması

**Precondition:**

* Product detail page açıqdır.

**Steps:**

1. Məhsul səhifəsinə keç.
2. Product description hissəsini yoxla.
3. Mətnin dilinə diqqət et.

**Expected Result:**

* Product description ingilis dilində olmalıdır.

---

## TC-005: Add to cart funksiyasının yoxlanılması

**Precondition:**

* Product detail page açıqdır.

**Steps:**

1. “Add to Cart” düyməsinə kliklə.
2. Məhsulun səbətə əlavə olunmasını yoxla.

**Expected Result:**

* Məhsul səbətə əlavə olunmalıdır.
* Cart icon və ya cart page yenilənməlidir.
