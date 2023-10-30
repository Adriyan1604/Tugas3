# Tugas 2

# Proyek Java KategoriNilai

Proyek ini adalah contoh aplikasi Java sederhana yang memungkinkan pengguna memasukkan skor dan menentukan kategori nilai berdasarkan skornya. Program ini mengikuti kategori nilai standar dengan rentang 0-100.


## Daftar Isi Tugas 2
1. [Cara Menjalankan Proyek](#cara-menjalankan-proyek)
2. [Contoh Penggunaan](#contoh-penggunaan)
3. [Warning Exception](#warning-exception)



## Cara Menjalankan Proyek

1. Pastikan Anda telah menginstal JDK (Java Development Kit) di komputer Anda.
2. Dan anda hanya perlu Klik "Run" maka akan keluar output

<pre>
Masukkan skor Anda: 
</pre>

3. Ikuti instruksi untuk memasukkan skor Anda, dan program akan menampilkan kategori nilai yang sesuai.

## Contoh Penggunaan

Misalkan Anda ingin menilai skor 85:

Maka output yang diharapkan adalah:

<pre>
Kategori Nilai: B
</pre>

## Warning Exception
Program tidak bisa menjalankan program jika user menginputkan huruf
<pre>
Exception in thread "main" java.util.InputMismatchException
	at java.base/java.util.Scanner.throwFor(Scanner.java:943)
	at java.base/java.util.Scanner.next(Scanner.java:1598)
	at java.base/java.util.Scanner.nextInt(Scanner.java:2263)
	at java.base/java.util.Scanner.nextInt(Scanner.java:2217)
	at Tugas2.KategoriNilai.main(KategoriNilai.java:20)
</pre>  

Dan juga angka Negatif maka akan masuk "else"

<pre>
Kategori Nilai: Skor tidak valid
</pre>  

## Javadoc

<pre>
NamaKelas: KategoriNilai
Author: M.Adriyan Maulana
StudentID: 202210370311005
method: main
Tema: Kategori Nilai
</pre>
