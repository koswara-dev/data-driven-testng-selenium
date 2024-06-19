### Data Driven Testing

**Data Driven Testing (DDT)** adalah teknik pengujian otomatisasi di mana data uji dipisahkan dari skrip pengujian. Dalam pendekatan ini, data uji disimpan di sumber eksternal seperti file CSV, Excel, database, atau sumber data lainnya, dan skrip pengujian membaca data dari sumber ini untuk menjalankan tes dengan berbagai set data.

Berikut adalah elemen utama dan manfaat dari Data Driven Testing:

#### Elemen Utama Data Driven Testing

1. **Sumber Data Eksternal:**
   - **File CSV:** Format sederhana yang digunakan untuk menyimpan data dalam bentuk teks yang dipisahkan oleh koma.
   - **File Excel:** Digunakan untuk menyimpan data uji dalam bentuk tabel dengan dukungan banyak lembar kerja.
   - **Database:** Digunakan untuk menyimpan dan mengelola data uji dalam skala besar.
   - **File XML/JSON:** Digunakan untuk menyimpan data dalam format yang mudah dipahami oleh manusia dan mesin.

2. **Skrip Pengujian:**
   - Skrip pengujian diimplementasikan untuk membaca data dari sumber eksternal dan menjalankan tes dengan data yang berbeda-beda. Skrip ini biasanya ditulis menggunakan bahasa pemrograman dan kerangka kerja pengujian seperti Java, Python, Selenium, TestNG, JUnit, dll.

3. **Framework Pengujian:**
   - **TestNG/JUnit:** Kerangka kerja pengujian berbasis Java yang mendukung data driven testing melalui anotasi seperti `@DataProvider`.
   - **Selenium:** Alat otomatisasi untuk pengujian web yang dapat digunakan bersama dengan TestNG atau JUnit untuk mengotomatisasi tes berbasis data.

#### Manfaat Data Driven Testing

1. **Pemeliharaan yang Lebih Mudah:**
   - Memisahkan data uji dari skrip pengujian membuat pemeliharaan lebih mudah. Perubahan pada data uji tidak mempengaruhi skrip pengujian.

2. **Pengujian yang Lebih Komprehensif:**
   - Dengan menggunakan berbagai set data, DDT memungkinkan pengujian yang lebih menyeluruh dan mendalam terhadap aplikasi.

3. **Penghematan Waktu:**
   - DDT mengurangi waktu yang dibutuhkan untuk menulis skrip pengujian terpisah untuk setiap set data. Skrip yang sama dapat digunakan dengan data yang berbeda.

4. **Skalabilitas:**
   - DDT mendukung pengujian dalam skala besar dengan data yang besar, memungkinkan pengujian berbagai skenario tanpa harus menulis ulang skrip pengujian.

Dengan pendekatan ini, Data Driven Testing memungkinkan pengujian yang lebih efisien dan efektif, memastikan bahwa aplikasi diuji dengan berbagai kondisi dan skenario yang mungkin terjadi di lingkungan nyata.
