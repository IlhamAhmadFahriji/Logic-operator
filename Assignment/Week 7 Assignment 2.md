 # Assignment 02

**Group members**
- Aditya Laksamana P Butar Butar (10231006) (Problem #4)
- Cantika Ade Qutnindra Maharani (10231024) (Problem #1)
- Ilham Ahmad Fahriji (10231042) (Problem #5)
- Muhammad Ayash Az-Dzikri (10231060) (Problem #3)
- Ranaya Chintya Mahitsa (10231078) (Problem #2)

## Problem 1
Tentukan pernyataan berikut apakah bernilai benar atau salah, dan jelaskan 
mengapa bernilai benar atau bernilai salah
1. $`\{\,\} \in \{ \{\,\} \}`$   
2. $`\{\{\,\}\} \in \{ \{\,\}\}`$
3. $`\{\{\,\}\} \subset \{ \{\,\}, \{ \{\,\} \} \}`$
4. $`\{\{ \{\,\}\}\} \subset \{\{\{\,\}\}, \{\{\,\}\}\}`$
5. $`\{\,\} \in \{\{\,\}, \{\{\,\}\}\}`$
6. $`\{\{\,\}\} \in \{\{\{\,\}\}\}`$
7. $`\{\{\{\,\}\}\} \subset \{\{\,\}, \{\{\,\}\}\}`$

### Answer

1. pernyataan dinyatakan benar, dikarenakan himpunan kosong ({ }) merupakan bagian dari anggota himpunan kosong ({{ }}) yang mana berisikan himpunan itu sendiri.
2. pernyataan dinyatakan salah, hal tersebut dikarenakan himpunan tersebut sama dan tidak memiliki hubungan antar anggota-anggota.
3. pernyataan dinyatakan benar, dikarenakan himpunan yang berisikan himpunan kosong {{ }} merupakan bagian dari himpunan yang berisikan himpunan kosong itu sendiri {{ },{{ }}}
4. pernyataan tersebut dinyatakan benar, dikarenakan himpunan ({{{ }}}) berada pada salah satu dari kedua buah himpunan ({{{ }}, {{ }}})
5. pernyataan tersebut salah, dikarenakan himpunan kosong ({ }) bukan merupakan bagian dari dua himpunan kosong dari ({{ }, {{ }}})
6. pernyataan dinyatakan  salah, hal tersebut dikarenakan himpunan kosong ({{ }}) bukan merupakan bagian dari himpunan ({{{ }}})
7. pernyataan dinyatakan benar, dikarenakan himpunan ({{{ }}}) ada berada pada salah satu dari dua himpunan kosong ({{ }, {{ }}})

## Problem 2
Diberikan dua buah himpunan $A$ dan $B$, operasi **selisih simetrik**
yang dinotasikan $A \oplus B$ adalah himpunan yang memuat elemen-elemen
yang berada di $A$ atau di $B$ namun yang tidak berada bersamaan di 
$A$ dan $B$.
1. Carilah selisih simetrik dari dua himpunan berikut: $\{1, 3, 5\}$
   dan $\{1, 2, 3\}$
2. Carilah selisih simetrik dari himpunan mahasiswa SI yang mengambil 
   kelas Matematika diskrit dan himpunan mahasiswa SI yang mengambil 
   kelas Kalkulus 1
3. Gambarkan diagram Venn untuk operasi selisih simetrik dari dua 
   himpunan $A$ dan $B$.

### Answer

1. untuk selisih simetrik dari dua himpunan $\{1, 3, 5\}$ dan $\{1, 2, 3\}$ adalah :

   $A \oplus B$ = ($A ∪ B$) - ($A ∩ B$) 
   
   $A ∪ B$ = {1, 2, 3, 5} (Gabungan kedua himpunan)

   $A ∩ B$ = {1, 3} (Irisan kedua himpunan)
    
   Menjadi {2, 5}

2. Untuk mencari selisih simetrik antara himpunan mahasiswa SI yang mengambil kelas Matematika diskrit (misalnya, A) dan himpunan mahasiswa SI yang mengambil kelas Kalkulus 1 (misalnya, B), Anda perlu tahu data konkretnya. Mari asumsikan:

   A = {Mahasiswa SI yang mengambil Matematika Diskrit}
   B = {Mahasiswa SI yang mengambil Kalkulus 1}

   Selisih simetrik $A \oplus B$ akan menjadi mahasiswa yang mengambil salah satu mata kuliah, tetapi tidak mengambil keduanya.

3. Untuk diagram Venn untuk operasi selisih simetrik dari dua 
   himpunan $A$ dan $B$ dapat digambarkan sebagai berikut : 
   ![diagram_venn_selisish_simbolik](<Diagram Venn Selisih Simetrik.jpeg>)

## Problem 3
Diberikan empat buah fungsi yang memetakan dari himpunan mahasiswa-mahasiswi
yang mengambil kelas Matematika Diskrit ke:
1. nomor telepon
2. nomor induk mahasiswa
3. nilai akhir kelas Matematika Diskrit
4. alamat rumah

Untuk setiap fungsi di atas, batasan apakah yang harus diterapkan supaya 
masing-masing ke-empat fungsi di atas adalah fungsi injektif (fungsi 
satu-satu)?
### Answer

kita memiliki empat fungsi yang berbeda yang memetakan mahasiswa yang mengambil kelas Matematika Diskrit ke empat hal berbeda: nomor telepon, nomor induk mahasiswa, nilai akhir kelas Matematika Diskrit, dan alamat rumah. Untuk masing-masing fungsi ini agar injektif, ada batasan yang harus diterapkan:
1. **Fungsi nomor telepon**: Agar fungsi ini injektif, setiap mahasiswa harus memiliki nomor telepon yang berbeda. Artinya, tidak ada dua mahasiswa yang memiliki nomor telepon yang sama. Ini bisa dijamin dengan mengharuskan setiap nomor telepon dalam domain (himpunan mahasiswa) harus unik.
2. **Fungsi nomor induk mahasiswa**: Untuk menjadikan fungsi nomor induk mahasiswa injektif, setiap mahasiswa harus memiliki nomor induk yang berbeda. Ini seharusnya sudah terpenuhi karena nomor induk mahasiswa biasanya sudah unik dan diberikan oleh institusi pendidikan.
3. **Fungsi nilai akhir kelas Matematika Diskrit**: Untuk fungsi ini menjadi injektif, setiap mahasiswa harus memiliki nilai akhir yang berbeda dalam kelas Matematika Diskrit. Ini mungkin sulit dicapai dalam praktiknya karena beberapa mahasiswa bisa saja mendapatkan nilai yang sama, tetapi jika Anda memiliki kontrol penuh atas penilaian dan setiap mahasiswa memiliki nilai yang unik, maka fungsi ini akan menjadi injektif.
4. **Fungsi alamat rumah**: Agar fungsi ini menjadi injektif, setiap mahasiswa harus tinggal di alamat yang berbeda. Ini bisa sulit dicapai dalam praktiknya karena beberapa mahasiswa mungkin tinggal di alamat yang sama (misalnya, dalam asrama atau daerah perumahan yang sama). Oleh karena itu, fungsi ini mungkin tidak bisa dijamin menjadi injektif dalam situasi dunia nyata.

## Problem 4
Diberikan operator Boolean $\oplus$ yang disebut XOR operator dengan 
tabel perhitungan berikut
| $x$ | $y$ | $x \oplus y$ |
|-----|-----|--------------|
| 1   | 1   | 0            |
| 1   | 0   | 1            |
| 0   | 1   | 1            |
| 0   | 0   | 0            |

Tunjukkan bahwa dua identitas berikut berlaku
1. $x \oplus y = (x + y)\overline{xy}$
2. $x \oplus y = (x\overline{y}) + (\overline{x} y)$

### Answer

1. Identitas yang pertama adalah $x \oplus y = (x + y)\overline{xy}$ berikut adalah tabel untuk menunjukkan identitas yang berlaku dari $x \oplus y = (x + y)\overline{xy}$ menggunakan Hukum De Morgan

| $x$ | $y$ | $x \oplus y$ | $x + y$ | $xy$ | $\overline{xy}$ | $(x + y)\overline{xy}$ |
| --- | --- | ------------ | ------- | ---- | --------------- | ---------------------- |
| 1   | 1   | 0            | 1       | 1    | 0               | 0                      |
| 1   | 0   | 1            | 1       | 0    | 1               | 1                      |
| 0   | 1   | 1            | 1       | 0    | 1               | 1                      |
| 0   | 0   | 0            | 0       | 0    | 1               | 0                      |

2. Identitas yang pertama adalah $x \oplus y = (x\overline{y}) + (\overline{x} y)$ berikut adalah tabel untuk menunjukkan identitas yang berlaku dari $x \oplus y = (x\overline{y}) + (\overline{x} y)$ menggunakan Hukum De Morgan

| $x$ | $y$ | $x \oplus y$ | $\overline{x}$ | $\overline{y}$ | $x\overline{y}$ | $\overline{x}y$ | $(x\overline{y}) + (\overline{x} y)$ |
| --- | --- | ------------ | -------------- | -------------- | --------------- | --------------- | ------------------------------------ |
| 1   | 1   | 0            | 0              | 0              | 0               | 0               | 0                                    |
| 1   | 0   | 1            | 0              | 1              | 1               | 0               | 1                                    |
| 0   | 1   | 1            | 1              | 0              | 0               | 1               | 1                                    |
| 0   | 0   | 0            | 1              | 1              | 0               | 0               | 0                                    |

## Problem 5   
Carilah cara untuk menyatakan komplement, Boolean sum, 
dan Boolean product dengan hanya menggunakan NOR operator

### Answer

Logic NOR function is a combination two separate logic operators, the Not Functions and the Or Functions is combined to one form single logic functions NOR (NOT-OR)

Truth Table NOR
| $x$ | $y$ | $x \downarrow y$ |
|-----|-----|--------------|
| 0   | 0   | 1            |
| 0   | 1   | 0            |
| 1   | 0   | 0            |
| 1   | 1   | 0            |

complement $ \bar x$ = ($x \downarrow x$)
complement $ \bar y$ = ($y \downarrow y$)

Boolean products = (($x \downarrow x$) $\downarrow$ ($y \downarrow y$))
Boolean Sum      = ($\bar x \downarrow \bar y$) = ($x \downarrow y$)

Truth table complement, Boolean sum and Boolean Products with NOR
| $x$ | $y$ | $x \downarrow x$ | $y \downarrow y$ | $x \downarrow y$ | ($x \downarrow x$) $\downarrow$ ($y \downarrow y$) |
|-----|-----|------------------|------------------|------------------|----------------------------------------------------|
| 0   | 0   | 1                | 1                | 1                | 0                                                  |
| 0   | 1   | 1                | 0                | 0                | 0                                                  |
| 1   | 0   | 0                | 1                | 0                | 0                                                  |
| 1   | 1   | 0                | 0                | 0                | 1                                                  |



