# Tugas 1

Cara membuat LiveTemplate

## Daftar Isi Tugas 1
1. [Instalasi](#instalasi)
2. [Cara Menggunakan](#cara-menggunakan)
3. [Kontribusi](#kontribusi)


## Instalasi

Bagaimana cara instalasi atau cara membuat LiveTemplate?  
![alt text](https://github.com/Adriyan1604/DocumentationPractice/blob/main/readme.png?raw=true)  
- Gambar diatas adalah sebagai patokan, jadi untuk menginstal LiveTemplate anda perlu tekan ctrl+alt+s
untuk shortcut ke settings  
- Setelah berada pada settings klik ">" pada Editor maka menu Editor akan expand  
- Lalu tekan Live template dan pilihlah pada program apakah harusnya live template ini bekerja  
- Pada kasus saya, saya taruh Livetemplate di program java
- Langkah selanjutnya klik ikon "+" pada pojok kiri atas
- Rename "Abbreviation" sesuai singkatan yang anda mau  
- Masukkan deskripsi untuk apakah program ini (opsional)
- Template text ini adalah inti dari Livetemplate dimana anda harus memasukkan program yang harus berjalan jika anda mengetikkan Abbrevation pada kasus saya, saya menggunakan rumus aritmatika dan switch case untuk menjadi template text saya
- Selanjutnya tekan tulisan "Change" dan checklist pada bagian "Everywhere"
- Tekan Apply dan OK






## Cara Menggunakan

Cara pengimplementasian LiveTemplate ini cukup mudah yaitu  
  
- Cukup buat proyek java baru atau yang sudah ada tidak masalah
- Ketikkan Abbrevation yang sudah anda buat tadi  
- Dalam kasus saya, saya menggunakan Abbrevation "opr"
  ![alt text](https://github.com/Adriyan1604/DocumentationPractice/blob/main/readme.png?raw=true)
- Lalu akan muncul popup seperti ini
  ![alt text](https://github.com/Adriyan1604/DocumentationPractice/blob/main/opr.png?raw=true)
- Tekan Enter/Tab dan maka Template text yang anda buat tadi akan muncul pada project anda
- Seperti Switch Case punya saya
<pre>
switch (operator) {
                    case '+':
                        hasil = angka1 + angka2;
                        break;
                    case '-':
                        hasil = angka1 - angka2;
                        break;
                    case '*':
                        hasil = angka1 * angka2;
                        break;
                    case '/':
                        if (angka2 != 0) {
                            hasil = angka1 / angka2;
                        } else {
                            System.out.println("Error: Pembagian oleh nol.");
                            System.exit(1);
                        }
                        break;
                    default:
                        System.out.println("Operator tidak valid.");
                        System.exit(1);
                }
</pre>


## Kontribusi

- Untuk apakah fitur Livetemplate ini dibuat?  
Yaitu untuk memudahkan para programmer dalam mengetik program, juga tentunya menghemat waktu dan meminimalisir Sintax Error seperti salah ketik, kurang titik koma dll.  
- Untuk apakah file readme ini saya buat?  
Yaitu tentunya untuk tugas demo dan selebihnya untuk menunjukkan cara langkah demi langkah membuat live template dengan format bahasa yang lebih fleksibel
