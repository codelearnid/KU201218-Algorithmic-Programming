# Modul Kuliah Minggu Ke 2 - Konsep Dasar Algoritma dan Pemrograman

Dosen Pengampu : **Arif Wicaksono Septyanto**<br>

Tujuan Belajar :
- Mahasiswa mampu menggunakan algoritme, diagram alir, dan pseudocode
 I/O yang melibatkan variabel dan ekspresi dan mengimplementasikannya dengan Python.

## 1. Pengertian dan Sejarah Algoritma

Algoritma adalah urutan instruksi logis dan matematis yang dirancang untuk menyelesaikan suatu masalah atau tugas secara efektif dan efisien. Algoritma seringkali diwakili dalam bentuk diagram alir atau pseudocode.

Sejarah algoritma dapat dilacak kembali ke awal peradaban manusia ketika mereka mengembangkan cara untuk memecahkan masalah dan menjalankan tugas tertentu. Misalnya, bangsa Mesir Kuno menggunakan algoritma untuk membangun piramida, sedangkan bangsa Yunani Kuno menggunakan algoritma untuk menyelesaikan masalah geometri.

Kata "algoritma" sendiri berasal dari nama seorang matematikawan Muslim terkenal dari abad ke-9, Muhammad ibn Musa al-Khwarizmi, yang dikenal sebagai "Bapak Aljabar". Al-Khwarizmi dikenal karena karyanya dalam mengembangkan sistem bilangan Hindu-Arab dan memperkenalkan algoritma dalam matematika.

Pengertian algoritma adalah prosedur sistematis dan terstruktur yang digunakan untuk menyelesaikan suatu masalah atau tugas tertentu. Algoritma umumnya dibuat dengan menggunakan bahasa pemrograman atau notasi matematika, dan dapat diimplementasikan dalam berbagai jenis aplikasi dan program.

Kemampuan untuk membuat dan memahami algoritma sangat penting dalam dunia komputasi dan teknologi informasi, karena algoritma merupakan dasar dari semua program dan sistem komputer yang digunakan di seluruh dunia. Dalam dunia bisnis, algoritma digunakan dalam analisis data dan pengambilan keputusan, sementara dalam ilmu pengetahuan dan teknik, algoritma digunakan untuk memodelkan dan memecahkan masalah yang kompleks.

berikut adalah contoh sederhana algoritma tanpa menggunakan bahasa pemrograman, tetapi menggunakan langkah-langkah dalam bentuk instruksi berdasarkan masalah yang dihadapi:


Algoritma Membuat Mie Instan 

1. Siapkan mie instan, panci/wajan, mangkok, sendok dan garpu, dan air secukupnya. 
2. Masukkan air ke panci atau wajan. 
3. Nyalakan kompor dan didihkan air.
4. Sambil menunggu air mendidih, buka bungkus mie, buka bungkus bumbu dan tuangkan ke mangkok. 
5. Jika air sudah mendidih, masukkan mie. 
6. Tunggu mie hingga berubah tekstur menjadi kenyal. 
7. Sesekali diaduk. 
8. Jika mie sudah kenyal, matikan kompor dan tuang mie ke mangkok. 
9. Aduk mie hingga bumbu merata. 
10. Mie siap disantap. 

<div align="center">
  <img src="gambar/flowchar%20mie.webp" alt="Deskripsi Gambar" width="600" height="">
  <p><strong>Gambar 1. Flowchart Membuat Mie</strong></p>
</div>

Penjelasan Flowchart :

1. "Mulai" (Simbol Terminator). Menunjukkan awal dari Flowchart. 
2. "Siapkan mie instan, panci/wajan, mangkok, sendok dan garpu, dan air secukupnya." (Simbol Preparation). Menyatakan langkah persiapan untuk melakukan langkah berikutnya. Disini semua alat dan bahan disiapkan sebelum melakukan langkah berikutnya yaitu merebus mie. 
3. "Masukkan Air" (Simbol Input/Output). Ini menyatakan langkah dimana kita melakukan input/masukkan. Di sini yang kita input adalah air. 
4. "Nyalakan Kompor dan Didihkan Air" (Simbol Process). Menyatakan langkah yang berisi aksi dan proses. Aksi disini adalah menyalakan kompor dan proses disini yaitu mendidihkan air.
5. "Kemudian Tunggu Mendidih" (Simbol Delay). Menyatakan waktu tunggu atau delay. Di sini waktu tunggu yang dimaksud adalah menunggu air mendidih. 
6. Kemudian "Buka Bungkus Mie...mangkok" (Simbol Process). Saya hubungkan dengan garis putus-putus yang menandakan langkah ini bisa dilakukan sambil menunggu waktu delay. Di sini kita lakukan sambil menunggu air mendidih. 
7. Kemudian Simbol Decision dengan teks "Mendidih?". Digunakan untuk mengecek kondisi apakah air sudah mendidih. 
8. Jika air mendidih, "Masukkan Mie ke Panci" (Simbol Input/Output). Menandakan langkah yang memerlukan input. Di sini kita input mie ke panci.
9. Kemudian "Tunggu..." (Simbol Delay). Ini menyatakan kita harus menunggu sampai mie menjadi kenyal. 
10. "Sesekali diaduk" (Simbol Process). Berisi aksi berupa mengaduk. 
11. Simbol Decision lagi untuk mengecek apakah "Mie Sudah Kenyal?". Jika mie sudah kenyal, matikan kompor dan tuang ke mangkok. Jika belum, kembali menunggu dan sesekali diaduk. 
12. Selanjutnya Simbol Process "Aduk mie hingga bumbu merata". Menyatakan aksi mengaduk mie. 
13. Lalu Simbol Input/Output. Disini kita nyatakan output dari proses memasak mie yaitu "Mie siap santap". 
14. "Selesai" (Simbol Terminator). Menyatakan akhir dari proses atau algoritma.


<div align="center">
  <img src="gambar/mie.png" alt="Deskripsi Gambar" width="300" height="200">
  <p><strong>Gambar 2. Algoritma Pada Mie Goreng</strong></p>
</div>


*Berikut adalah beberapa ciri-ciri algoritma yang baik:*

- Input yang Jelas: Algoritma harus memiliki langkah-langkah yang jelas untuk memahami input yang diberikan. Input harus didefinisikan dengan baik sehingga algoritma dapat menghasilkan hasil yang diharapkan.
- Langkah-langkah Terstruktur: Algoritma harus terdiri dari langkah-langkah yang terstruktur dan terorganisir dengan baik. Setiap langkah harus mengikuti secara logis dari langkah sebelumnya dan mengarah ke langkah berikutnya.
- Tinjauan Umum yang Jelas: Algoritma harus memiliki pandangan umum tentang apa yang ingin dicapai. Ini membantu untuk memahami tujuan dan tujuan dari algoritma.
- Efisiensi: Algoritma yang baik harus efisien dalam penggunaan sumber daya seperti waktu dan memori. Ini berarti algoritma dapat menyelesaikan tugas dengan cepat dan menggunakan jumlah sumber daya yang wajar.
- Mudah Dipahami: Algoritma harus mudah dipahami oleh orang lain yang membaca atau memeriksa kode. Langkah-langkah harus ditulis dengan jelas dan dapat dimengerti tanpa ambigu.
- Solusi yang Benar: Algoritma harus menghasilkan hasil yang benar dan akurat sesuai dengan masalah yang harus dipecahkan. Algoritma yang menghasilkan hasil yang salah atau tidak konsisten tidak efektif.
- Teruji dan Terbukti: Algoritma yang baik harus telah diuji secara menyeluruh untuk memastikan bahwa ia berfungsi sesuai yang diharapkan dalam berbagai situasi.
- Modularitas: Algoritma yang baik dapat dibagi menjadi bagian-bagian yang lebih kecil atau modul yang dapat dikelola secara terpisah. Ini memudahkan perawatan, pengembangan, dan perbaikan di masa mendatang.
- Dokumentasi yang Baik: Algoritma harus dijelaskan dengan baik melalui komentar atau dokumentasi yang menjelaskan tujuan, langkah-langkah, dan bagaimana algoritma bekerja.
- Fleksibilitas: Algoritma yang baik harus dapat digunakan untuk berbagai kasus dan dapat dengan mudah diadaptasi untuk menyelesaikan masalah yang serupa.
- Sederhana dan Elegan: Algoritma yang baik cenderung lebih sederhana dan elegan. Ini menghindari kebingungan dan meningkatkan kemampuan untuk memahami serta mengelola algoritma.

Memiliki algoritma yang memenuhi ciri-ciri ini akan membantu dalam mengembangkan solusi yang efektif dan efisien untuk masalah yang dihadapi.

## 2. Penyajian Algoritma

Penyajian algoritma adalah cara untuk mengkomunikasikan langkah-langkah yang diperlukan untuk menyelesaikan suatu tugas atau masalah secara jelas dan terstruktur. Ada beberapa cara untuk menyajikan algoritma, tergantung pada konteks dan audiens yang dituju. Berikut beberapa cara umum untuk menyajikan algoritma:

### 2.1 Pseudocode (Pseudokode)

Pseudocode adalah suatu metode untuk merencanakan dan menggambarkan algoritma menggunakan bahasa yang mirip dengan kode pemrograman, tetapi tidak bergantung pada sintaks tertentu dari bahasa pemrograman tertentu. Pseudocode digunakan untuk memberikan panduan dan pemahaman yang lebih mudah dipahami mengenai langkah-langkah yang diperlukan dalam suatu algoritma.

Berikut adalah beberapa poin penting mengenai pseudocode:

  1. Bebas Sintaks Tertentu: Pseudocode tidak terikat oleh sintaks tertentu dari bahasa pemrograman. Ini memungkinkan penulis untuk fokus pada konsep algoritma tanpa harus khawatir tentang cara penulisan kode yang benar.
  2. Deskriptif: Pseudocode seharusnya lebih deskriptif daripada kode sebenarnya. Ia harus menjelaskan langkah-langkah algoritma dengan jelas dan singkat.
  3. Sederhana: Pseudocode menggunakan kata-kata umum, operator matematika, dan struktur kontrol sederhana seperti "if," "else," "for," dan "while."
  4. Tidak Spesifik pada Bahasa Pemrograman: Pseudocode seharusnya dapat dengan mudah diterjemahkan ke dalam bahasa pemrograman apa pun. Ini memungkinkan programmer untuk mengimplementasikan algoritma dalam bahasa yang mereka pahami.
  5. Tidak Memperhatikan Detil Implementasi: Pseudocode fokus pada langkah-langkah konseptual algoritma tanpa memperhatikan implementasi nyata seperti variabel, tipe data, atau perincian teknis lainnya.

Contoh pseudocode yang menggambarkan algoritma sederhana untuk mengecek apakah suatu bilangan adalah bilangan genap atau ganjil menggunakan bahasa pseudocode dan juga implementasinya dalam bahasa pemrograman Python:

Pseudocode:

```sql{.line-numbers}
START
   INPUT bilangan
   IF bilangan MOD 2 EQUALS 0 THEN
      OUTPUT "Bilangan genap"
   ELSE
      OUTPUT "Bilangan ganjil"
   END IF
END
```
Implementasi dalam Python:

```python
bilangan = int(input("Masukkan sebuah bilangan: "))
if bilangan % 2 == 0:
    print("Bilangan genap")
else:
    print("Bilangan ganjil")

```
Implementasi dalam PHP:

```php
<?php
$bilangan = intval(readline("Masukkan sebuah bilangan: "));
if ($bilangan % 2 == 0) {
    echo "Bilangan genap";
} else {
    echo "Bilangan ganjil";
}
?>
```

Implementasi dalam C++:
```cpp
#include <iostream>
using namespace std;

int main() {
    int bilangan;
    cout << "Masukkan sebuah bilangan: ";
    cin >> bilangan;
    if (bilangan % 2 == 0) {
        cout << "Bilangan genap";
    } else {
        cout << "Bilangan ganjil";
    }
    return 0;
}
```
Implementasi dalam Java:
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Masukkan sebuah bilangan: ");
        int bilangan = scanner.nextInt();
        if (bilangan % 2 == 0) {
            System.out.println("Bilangan genap");
        } else {
            System.out.println("Bilangan ganjil");
        }
    }
}
```
Implementasi dalam JavaScript:
```js
let bilangan = parseInt(prompt("Masukkan sebuah bilangan: "));
if (bilangan % 2 === 0) {
    console.log("Bilangan genap");
} else {
    console.log("Bilangan ganjil");
}
```
Implementasi dalam Go (Golang):
```go
package main

import "fmt"

func main() {
    var bilangan int
    fmt.Print("Masukkan sebuah bilangan: ")
    fmt.Scan(&bilangan)
    if bilangan%2 == 0 {
        fmt.Println("Bilangan genap")
    } else {
        fmt.Println("Bilangan ganjil")
    }
}
```

Dalam semua implementasi di atas, logika untuk mengecek bilangan genap atau ganjil sama. Implementasi dalam bahasa pemrograman mengikuti struktur dan logika yang sama dengan pseudocodehanya, hanya sintaks pemrograman yang berbeda tergantung pada bahasa pemrograman yang digunakan.
### 2.2 Diagram Alir (Flowchart)

Diagram alir adalah representasi grafis langkah-langkah algoritma dengan menggunakan bentuk-bentuk geometris dan panah untuk menggambarkan aliran logika. Diagram alir sangat bermanfaat dalam memvisualisasikan urutan langkah dan pengambilan keputusan dalam algoritma.

<div align="center">
  <img src="gambar/Simbol-flowchart.jpg" alt="Deskripsi Gambar" width="1000" height="">
  <p><strong>Gambar 3. Simbol Flowchart</strong></p>
</div>

Simbol-simbol di atas memiliki variasi jenis dan peran yang beragam. Beberapa di antaranya berperan dalam menghubungkan simbol lain, seperti simbol aliran, referensi pada halaman dan referensi di luar halaman. Selain itu, ada juga simbol yang digunakan untuk merepresentasikan proses yang sedang berlangsung. Dan yang terakhir, ada simbol yang dimaksudkan untuk menginput data dan menampilkan hasil keluaran.

Contoh Flowchart :
Agar dapat membuat diagram alur yang sederhana, kamu perlu memahami tiap simbol dan tujuannya. Di bawah ini, saya akan memberikan contoh sederhana diagram alur untuk memeriksa apakah sebuah bilangan termasuk ganjil atau genap. Berikut adalah ilustrasinya:

<div align="center">
  <img src="gambar/Contoh-flowchart.jpg" alt="Deskripsi Gambar" width="300" height="">
  <p><strong>Gambar 4. Contoh Flowchart</strong></p>
</div>

Pembahasan:

- Pertama pengguna menginput data yang berupa nilai dari bilangan bulat.
- Kemudian nilai yang dimasukan diproses dengan cara dibagi dengan angka 2.
- Jika sisa bagi sama dengan 0 berarti bilangan yang dimasukan adalah bilangan genap.
- Jika sisa bagi tidak sama dengan 0 berarti bilangan yang dimasukan adalah bilangan ganjil.
- Selesai.

### 2.3 Deskripsi Teks
Algoritma juga dapat dijelaskan dalam bentuk teks yang rinci. Ini adalah cara sederhana untuk menulis langkah-langkah algoritma secara berurutan dengan kalimat-kalimat yang jelas dan deskriptif.

contoh :
Nama Algoritma: Pencarian Linier

Tujuan: Mencari elemen tertentu dalam sebuah daftar (array) dengan cara memeriksa satu per satu elemen secara berurutan.

Langkah-langkah:

1. Mulai dari elemen pertama dalam daftar.
2. Periksa elemen tersebut apakah sama dengan elemen yang ingin dicari.
3. Jika ya, maka elemen ditemukan dan proses berakhir.
4. Jika tidak, pindah ke elemen berikutnya dalam daftar.
5. Ulangi langkah 2-4 sampai elemen yang dicari ditemukan atau seluruh daftar telah diperiksa.
6. Jika seluruh daftar telah diperiksa dan elemen tidak ditemukan, berikan pesan bahwa elemen tidak ada dalam daftar.

Contoh:
Misalkan kita memiliki daftar angka [5, 10, 25, 8, 15] dan ingin mencari angka 8.

1. Mulai dari elemen pertama, yaitu 5. Tidak sama dengan 8.
2. Pindah ke elemen berikutnya, yaitu 10. Tidak sama dengan 8.
3. Pindah lagi, yaitu 25. Tidak sama dengan 8.
4. Pindah lagi, yaitu 8. Sama dengan 8. Elemen ditemukan.
5. Jadi, algoritma pencarian linier telah berhasil menemukan angka 8 dalam daftar.

### 2.4 Model Matematika
Untuk masalah yang melibatkan komputasi matematika atau analisis numerik, seringkali algoritma dijelaskan dalam bentuk persamaan matematika atau model matematika.

### 2.5 Contoh Kode Pemrograman
Jika tujuannya adalah untuk mengimplementasikan algoritma dalam suatu bahasa pemrograman, Anda dapat menyajikan algoritma dengan memberikan contoh kode pemrograman yang mendemonstrasikan langkah-langkah algoritma.

### 2.6 Diagram Blok
Diagram blok adalah cara lain untuk memvisualisasikan algoritma dengan menggunakan blok-blok untuk mewakili langkah-langkah dan menghubungkannya dengan panah untuk mengindikasikan aliran algoritma.

### 2.7 Animasi
Dalam beberapa kasus, seperti algoritma yang berhubungan dengan komputer grafis atau simulasi, animasi dapat digunakan untuk mengilustrasikan cara algoritma bekerja secara visual.

Pilihan penyajian algoritma tergantung pada kebutuhan dan preferensi Anda, serta cara terbaik untuk mengkomunikasikan algoritma kepada audiens yang dituju. Tujuan utamanya adalah untuk membuat algoritma menjadi lebih mudah dipahami dan diikuti oleh siapa pun yang membaca atau menggunakan algoritma tersebut.


## 3. Struktur Pemrograman

Struktur pemrograman merujuk pada cara sebuah program komputer diorganisir dan diatur agar dapat dijalankan dengan benar dan efisien. Struktur pemrograman membantu dalam mengontrol alur eksekusi program dan memastikan bahwa tugas-tugas tertentu dapat diselesaikan dengan efektif. Berikut adalah tiga struktur pemrograman dasar yang umum digunakan:

1. Sekuensial (Sequential):
Struktur sekuensial mengatur eksekusi program dari awal hingga akhir, langkah demi langkah, tanpa ada percabangan atau perulangan. Setiap perintah dijalankan berurutan sesuai dengan urutan penulisan

2. Percabangan (Branching):
Struktur percabangan memungkinkan program untuk membuat keputusan berdasarkan kondisi tertentu. Biasanya menggunakan pernyataan "if", "else", dan "switch" untuk mengevaluasi kondisi dan memilih tindakan yang sesuai.

3. Perulangan (Looping):
Struktur perulangan memungkinkan program untuk menjalankan serangkaian pernyataan secara berulang sampai kondisi tertentu terpenuhi. Dalam beberapa bahasa pemrograman, struktur perulangan menggunakan pernyataan seperti "for", "while", dan "do-while".

Contoh penggunaan struktur pemrograman dalam bahasa Python:

Contoh Struktur Sekuensial:

```python
nama = input("Masukkan nama Anda: ")
umur = int(input("Masukkan umur Anda: "))
print("Halo,", nama, "! Anda berusia", umur, "tahun.")

```
Contoh Struktur Percabangan:
```python
nilai = int(input("Masukkan nilai Anda: "))
if nilai >= 70:
    print("Anda lulus.")
else:
    print("Anda tidak lulus.")
```

Contoh Struktur Perulangan:
```python
angka = 1
while angka <= 5:
    print(angka)
    angka += 1
```
Struktur pemrograman ini membantu mengatur alur logika program dan memungkinkan Anda untuk mengatasi berbagai skenario dalam pengembangan perangkat lunak.

