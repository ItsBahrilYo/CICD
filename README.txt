<!-- Headings -->
# Hi there!
## Task CICD with Cloudflare Pages

## 1. Cloudflare Pages
<p>
Merupakan tempat untuk frontend developer mendeploy sebuah aplikasi frontend.
</p>

## 2. Fork repository ke akun github


* Masuk ke akun github anda lalu,
* Buka tab browser baru dan kunjungi https://github.com/dumbwaysdev/wayshub-frontend/tree/main/src lalu klik icon+tulisan fork di pojok kanan atas tampilan github 
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/Screenshot%20from%202022-08-31%2022-16-02.png?raw=true)

* Masuk ke terminal lalu clone project yang telah anda fork di repository anda
<!-- Code Blocks -->
```bash
  git clone <ssh-link repository anda>

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/12.png?raw=true)



## 3. Deploy aplikasi yang sudah difork menggunakan Cloudflare

* Masuk ke akun Cloudflare Pages anda lalu klik pada pages di sebelah kiri dasboard
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/1.png?raw=true)

* Klik connect to Git untuk mengkoneksikan git akun anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/2.png?raw=true)

* Pilih akun github anda dan pilih repository yang akan dikoneksikan
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/3.png?raw=true)

* Isi project name sesuai selera, dan pilih production branch anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/4.png?raw=true)

* Pilih framework dari aplikasi yang ingin dideploy, pilih build command lalu pilih directory dimana anda ingin menyimpan hasil build. Lalu save & deploy

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/5.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/6.png?raw=true)

* Hasil konfigurasi build & deployment setting

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/7.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/8.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/9.png?raw=true)

* Ini merupakan website yang telah berhasil dijalankan ke server Cloudflare Pages
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/11.png?raw=true)
* Sekarang kita akan melakukan percobaan untuk proses CICD dengan mengubah nama title page. Buka terminal dan pergi ke /wayshub-frontend/public lalu buka file dengan nama index.html denga text editor nano
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/13.png?raw=true)

* Pada kolom title, rubah title sesuai dengan keinginan anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/Screenshot%20from%202022-08-31%2023-39-47.png?raw=true)

* Lalu add, commit dan push perubahan ke github anda 
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/15.png?raw=true)

* Cek pada akun cloudflare anda apakah pages project anda berproses terhadap perubahan yang anda lakukan. Seperti yang anda lihat pada pojok kanan bawah pages production anda terlihat 'in progress' ini menandakan bahwa proses CICD telah tercapai.
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/17.png?raw=true)


## Manage Server with Terminal

## 1. Terminal
<p> 
Sebuah command prompt dimana kita bisa mengatur bagaimana suatu sistem komputer berjalan mulai dari management folder, menjalankan dan memberhentikan program serta memonitoring bagaimana sistem komputer berjalan.
</p>

## 2. Keuntungan menguasai terminal

<p> Dengan menguasai bahasa terminal kita bisa mengoperasikan suatu sistem operasi dengan efektif dan effisien
menjalankan, menginstall, menguninstall, memberhentkan cukup di terminal </p>

## 3. Membuat file sederhana untuk update & upgrade sistem

* Buka terminal lalu buat file menggunakan perintah di bawah
<!-- Code Blocks -->
```bash
nano update_upgrade.sh 

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu1.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu2.png?raw=true)

