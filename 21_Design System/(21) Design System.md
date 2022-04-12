# Introducing Design System
-------------------------------------------------------

## Design System itu apa?
=======================================================

Design System adalah sebuah standarisasi yang mengatur setiap elemen desain untuk mengurangi redudansi.

Design System adalah kumpulan prinsip dan praktik bersama yang membantu menginformasikan pekerjaan designer, product manager, dan developer, serta sales dan marketing.

## Kenapa harus Design System?
=======================================================

Saat kalian pertama kali mulai membuat entah product atau project, pekerjaan berlangsung cepat dan mungkin bisa jadi seru.

Masalah yang kalian solve menjadi lebih jelas saat kalian mendapatkan pemahaman yang lebih baik tentang user base. Saat pemahaman kalian tumbuh, ide dan solusi terbentuk. 

Setiap anggota tim memiliki bagian yang dimainkan untuk menyusun produk pengalaman pengguna (user experience).

### 1. Si Designer

    - Mereka punya file design, tapi tidak bisa diakses dengan mudah oleh Si Front-end Developer sama Si Product Manager
    - Screenshot dan artboard di share bolak balik, dan adanya perubahan yang konstan
    - Karena tidak ada guideline di pekerjaan, mereka akhirnya mempertahankan pilihan dan solusi yang sama secara terus menerus

### 2. Si Front-end Developer

    - Mereka banyak menghabiskan waktu dengan develop kodingan yang sama terus, tetapi dengan konteks yang berbeda
    - Mereka juga tidak mendapatkan akses file design dan akhirnya tidak dapat insight kenapa atau bagaimana keputusan dari Si Designer ini dibuat
    - Akhirnya mereka notice, adanya ketidak konsisten di teks, warna, dan spacing di beberapa mockup mereka, dan akhirnya kodingannya jadi berantakan

### 3. Si Product Manager

    - Dapat banyak tekanan dari user dan stackholder yang dibawa. karena road map produknya panjang, dan resource nya juga kecil
    - Merasa resource designer sama developer itu kurang karena harus meng-handle semua pekerjaannya
    - Banyak masalah minor yang ingin mereka solve sendiri, tetapi tidak mau melangkahi mereka

## Perbedaan Style Guide / UI Kit, Component Library, dan Design System
=======================================================

### Style Guide / UI Kit

Dokumentasi yang masih bersifat statis.

Jadi, masih menyingkup color, typography, iconography dan masih banyak lagi.

### Component Library

Dokumentasi kumpulan style dan component yang bisa digunakan dan dibagikan ke tim. Ini bisa jadi memasukkan dokumentasi koding dari setiap component.

Contoh component nya seperti button, text field, checkbox dan yang lainnya.

### Design System

Dokumentasi kumpulan element, component, dan regions yang sudah ditentukan, termasuk guideline-nya  Designer dan Front-end Developer.

Contohnya, kapan button ini digunakan, kenapa pakai warna ini (ada alasan di setiap component).

## Kapan membutuhkan Design System?
=======================================================

Ada 3 poin yang diutamakan :

- Umur dari perusahaan

Karena setiap tahun perusahaan selalu berkembang, otomatis kebutuhan mereka juga bertambah.

- Ukuran tim

Coba cek resource timnya dulu. Jika kalian merasa timnya bakal berkembang kedepannya, maka saat itulah memikirkan untuk memakai Design System.

- Beban Pekerjaan

Kerja sebagai UI / UX Designer seringkali bergantian antara brand yang di desain sama kebutuhan user.

Karena pekerjaan mereka itu tidak ada iterasinya, dan UI / UX Designer tidak terlalu melihat adanya kesempatan untuk mengembangkan user experience.

Tetapi, Design System bisa digunakan sebagai starting point untuk membuat brand.

## Tujuan adanya Design System
=======================================================

Ada 3 poin yang didapatkan :

    - Brand bisa konsisten
    - Menjadi company identity
    - Mempunyai nilai yang sama antar pegawai

## Bagaimana caranya membangun sebuah Design System?
=======================================================

Akan terbagi menjadi 2 bagian

    - Atomic methodology
    - Best practice to build a design system

## Atomic Methodology
=======================================================

Atomic Design merupakan metodologi perancangan yang mengambil inspirasi dari bagaimana sebuah elemen atom membentuk molekul yang lebih kompleks hingga membentuk suatu organisme, dan ini analogikan ke setiap antarmuka halaman situs atau aplikasi

### Elemen dalam Atomic Design

Metode ini kamu dituntut mendesain dari komponen terkecil. Uniknya, nama komponennya diambil dari istilah-istilah kimia.

- Atom

Komponen terkecil atomic design adalah “atom”. Bentuknya berupa tombol, input, label, dan lain-lain.

Ciri komponen ini adalah tidak bisa dipecah lagi. Jika diurai, fungsi dan maknanya akan rusak dan berbeda.

Salah satu contohnya adalah tombol search. Jika kamu membongkarnya menjadi tombol dan tulisan “search”, tentu makna keduanya akan berbeda.

- Molekul

Jika beberapa atom dikumpulkan, mereka akan membentuk sebuah molekul. Nah, molekul ini punya fungsi khusus yang lebih lebar dari atom.

Misalnya, kamu menggabung atom tombol search dan input search. Semua itu akan membentuk fitur pencarian yang utuh.

- Organisme

Organisme adalah kumpulan dari molekul. Misalnya, molekul fitur search bar kamu tempel di header.

Selain itu, ada tombol navigasi dan logo di sana. Inilah yang membentuk suatu organisme.

Ia bukanlah hasil desain sempurna. Akan tetapi, kombinasi semuanya bisa digunakan ulang di banyak halaman.

- Template

Dalam atomic design, template adalah gabungan dari beberapa organisme. Seperti namanya, ia merupakan “blueprint” dari sebuah halaman web.

Blueprint ini tentu bisa dimodifikasi. Ia sangat mirip dengan wireframe, ditampilkan berupa elemen dan belum punya data nyata.

- Pages (Halaman)

Halaman merupakan produk akhir dari desain atomis. Ia merupakan template yang diisi dengan data nyata.

## Best practice to build a design system
=======================================================

3 Langkah Membangun Desain Sistem

- Evaluasi inventaris UI kamu saat ini dan catat inkonsistensi pada desain yang kamu buat

Telusuri produk kamu dan tinjau semua elemen desain yang sudah dibuat. Dari sana, kamu dapat membuat katalog komponen UI dan elemen visual yang akan membentuk fondasi sistem desain kamu. Selain itu, kamu dapat mengidentifikasi inkonsistensi yang mungkin muncul dan membuat keputusan desain yang tepat di masa depan.

- Bangun sebuah pattern library dari berbagai elemen desain yang sama

Pattern library adalah kumpulan komponen UI yang dapat digunakan kembali yang kemudian akan memudahkan pekerjaan desain di masa mendatang.

Ada dua jenis pola utama

    - Fungsional
    - Persepsi;

yang bekerja bersama untuk membentuk blok pembangun desain kamu. 

Menurut VIA Studio, “pola fungsional menentukan struktur desain kamu, seperti tata letak sebuah dashboard, sementara pola persepsi menentukan visual seperti tipografi, spasi, interaksi, dll.” Bersama-sama, pola-pola ini membentuk library yang baik secara struktural dan menggugah emosi dan estetika merek yang tepat.

- Dokumentasikan aturan desain kamu, lalu atur juga bagaimana dan kapan elemen-elemen desain itu dapat digunakan

Tanpa panduan yang jelas tentang bagaimana dan kapan menggunakan elemen desain, kamu tidak memiliki desain desain yang sebenarnya, melainkan, kamu hanya memiliki kumpulan elemen dan UI library. 

Saat kamu membuat desain sistem, pastikan untuk mendokumentasikan tentang bagaimana sebuah tim dapat menggunakan dan memeliharanya secara efektif.

Pedoman utama untuk dimasukkan ke dalam dokumentasi kamu mencakup petunjuk tentang:

    - Bagaimana anggota tim dapat berkontribusi pada desain sistem
    - Bagaimana melaporkan jika ada sebuah masalah dengan desain sistem
    - Bagaimana sebuah tim berencana untuk mengatasi masalah yang sedang berlangsung
    - Bagaimana kamu akan mengatur konsistensi antara sisi desain dan sisi kode, 
    - dst…

Pedoman dan rekomendasi yang jelas memungkinkan tim untuk segera bekerja lebih cepat dan efisien.

