# **Writing and Presentation Week 1**
## Unix Commad Line 
- ### CLI (Command Line Interface)
  <div align="justify">CLI merupakn sebuah program atau mekanisme interaksi dengan perangkat lunak komputer dengan memasukkan perintah untuk melakukan tugas tertentu. Macam CLI (CLI bawaan sistem operasi seperti cmd.exe milik Windows atau bash dan zsh di sistem operasi mirip dengan Unix).
- ### Shell
  <div align="justify">Shell merupkan program yang digunakan untuk berkomunikasi atau memerintah sistem untuk dieksekusi, agar bisa terhubung dengan komputer maka user memerlukan penerjemah yang mana itu dapat menggunakan shell. 
- ### Terminal
  <div align="justify">Terminal merupakan aplikasi untuk mengakses CLI, dalam terminal sendiri user dan komputer dapat saling terhubung dimana user dapat mengetikan perintah di dalam terminal dan dapat menjalankan shell.
- ### File System Structure
  <div align="justify">File System Structure merupakan structure yang mengatur bagaimana suatu data disimpa didalam sistem. Contoh File System Structure adalah sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree. 
  &nbsp;
- ### Command Navigasi
  - pwd (Print working directory), Command untuk melihat current working directory atau untuk mengetahui direktori mana yang saat ini sedang dibuka.
  - ls (list), Command untuk melihat isi file yang ada di sebuah direktori.
  - cd (change directory), Command untuk berpindah direktori.
  - touch, Command untuk membuat sebuah file direktori. 
  - mkdir (Make directory), Command untuk membuat sebuah direktori.
  - head and tail, Command untuk melihat beberapa line awal dari sebuah file text.
  - cat, Command untuk melihat isi sebuah file.
  - cp (copy), Command untuk mengcopy files atau directory.
  - mv (move), Command untuk memindahkan files atau directory. Bisa juga digunakan untuk rename.
  - rm (remove), Command untuk menghapus file atau directory.
## GIT & GitHub
- ### Pengertian GIT dan GitHub
  - GIT 
    <div align="justify">GIT adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file. Git biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif. File -file yg disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah.
    
  - GitHub 
    <div align="justify">GitHub merupakan layanan hosting berbasis web sebagai repositori git. Didalam github kita bisa mengupload file,membuat file yang mana filenya bisa kita kelola dengan version control system.
&nbsp; 
- ### Kenapa GIT dan Github tools wajib digunakan?
  <div align="justify">Dengan menggunakan GIT & Github tentunya akan memudahkan programmer untuk bisa bekerja sama dalam sebuah tim atau dapat melakukan kolaborasi karena sepandai apapun programar tidak akan bisa bekerja sedirian selamanya, dan juga dapat mempermudah programer dalam melacak perubahan pada kode software atau website. Menggunakan GIT dan GitHub tidak perlu menunggu rekan dalam satu tim menyelesaikan suatu program dahulu untuk berkolaborasi. Kita bisa membuat file didalam projek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.
- ### Perbedaan GIT dan GitHub
  <div align="justify">Developer yang menggunakan GIT dapat menggunakan command-line tool, yaitu pengubah kode dan dapat digabungkan menuju perangkat lokal. Sedangkan, GitHub menyediakan interface grafis berbasis cloud sebagai tempat untuk melakukan seluruh tugas.
- ### Alur kerja GIT dan GitHub
  <div align="justify">GIT sebagai Version Control System. Version Control System tugasnya adalah mencatat setiap perubahan pada File (termasuk code yang kita buat) pada suatu proyek baik dikerjakan secara individu maupun tim.
    <div align="justify">- SetUp Awal
      <div align="justify">git config --global user.name "Anak Milenial"
      <div align="justify">git config --global user.email contohanakmilenial@gmail.com
    <div align="justify">- Cek apakah setup berhasil
       <div align="justify">git config --list
- ### Repository GIT
  <div align="justify">Repository adalah direktori proyek yang kita buat. 1 Repo =  1 Proyek = 1 Direktori. 
- ### Command didalam GIT dan GitHub
  - Membuat Repository Baru
    <div align="justify">git init <nama_proyek> contoh git init proyek-01
  - Melakukan Commit pada GIT
    <div align="justify">Git commit berfungsi untuk melakukan commit atau menyimpan perubahan pada version control pada git. Dan kita bisa menambahkan pesan untuk memberikan checkout pada setiap perbuahan. contohnya "git commit -m "pesan checkout" (Perubahan Pertama)
  - Mempublish Aplikasi 
    <div align="justify">Untuk mempublish file atau aplikasi ke github dapat menggunakan git push origin
  - Melakukan Cloning
    <div align="justify">Untuk melakukan cloning dari github ke komputer atau local dapet menggunakan git clone
&nbsp;
## HTML
- ### Pengertian HTML 
  <div align="justify">HTML adalah singkatan dari Hypertext Markup Language. HTML digunakan untuk menampilkan konten pada web. HTML dapat dianalogikan sebagai kerangka dari suatu website. HTML bersifat statis. HTML hanya bertugas menampilkan konten yang diminta oleh developer.
  <div align="justify">Contoh konten pada HTML: Text, Image, Video, Link dll
- ### Kerangka HTML Sederhana 
  Adapun tag kerangka pada HTML seperti dibawah ini:
  ```html
  <!DOCTYPE html>
  <html>
  <head>
  <title>
      Judul Website
    </title>
  <body>
      Latihan Dasar HTML
    </body>
  </html>
  ```
  <div align="justify">Pada kerangka diatas dapat dilihat pada setiap tag pembuka akan diakhiri dengan tag penutup
&nbsp;

- ### Tools HTML
  <div align="justify">Seorang programmer akan selalu menggunakan berbagai macam tools. Tools ini untuk memudahkan dan menambah produktifitas seorang programmer. Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML yaitu Browser dan Code Editor. 
- ### Menjalankan HTML dengan VScode
  - Visual Studio Code adalah code editor yang dikembangkan oleh tim engineer Microsoft. Visual Code Studio merupakan paket all in one. Kamu bisa menggunakan ini untuk bahasa pemrograman apapun.
  - HTML dapat dijalankan dengan mencari lokasi file HTML lalu membukanya via browser, klik pada bagian folder yang menyimpan file html, maka file html akan terbuka
  - Menggunakan live server yang ada pada VScode dapat mempermudah programer untuk melakukan perubahan secara otomatis. Pada halaman VScode di pojok kiri terdapat icon extension lalu cari “Live Server” dan klik install. Jika sudah selesai install “Live Server” kemudian klik kanan pada file HTML dan terdapat pilihan open with 
“Live Server” maka HTML akan auto reload.
- ### Tag HTML
  - Tag pada HTML merupakan sebauh penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut.
  - Tag pada HTML umunya terdapat dua tipe, opening tag (tag pembuka) yang ditandai dengan `<p>` lalu adapun closing tag (tag penutup) yang ditandai dengan `</p>` garis miring. HTML sendiri memiliki 3 tag utama yaitu `<html>` `<head>` `<boady>`
&nbsp

  Contoh Tag HTML
  - Tag untuk membuat tulisan miring dan tebal
  ```html
    <b>Tulisan Tebal</b> <i>Tulisan Miring</i>
    ```
  - Tag untuk membuat paragraf dan heading
  ```html
  <!DOCTYPE html>
  <html>
  <head>
  <title>
      Judul Website
    </title>
  <body>
      <h1>Latihan Dasar HTML Heading Satu</h1>
      <p>Halo Semua Disini Belajar HTML</P>
    </body>
  </html>
  ```
  - Tag untuk menambahkan link 
   ```html
    <a href="https://google.com>Google</a>
    ```
  - Tag untuk membuat daftar/list
    - Unordered List

      ```html
      <ul>
        Keperluan Dapur
        <li>Teh</li>
        <li>Kopi</li>
        <li>Susu</li>
      </ul>
      ```
    - Ordered List

      ```html
      <ol>
        Dafunda
        <li>Dafunda Tekno</li>
        <li>Dafunda Otaku</li>
        <li>Dafunda Games</li>
      </ol>
      ```
      Masing-masing lis Unordered `<ul>` ataupun Ordered `<ol>` memiliki element `<li>` untuk mendefinisikan nilai dari list
    
   - Tag untuk menambahkan gambar
   ```html
    <img src="https://bit/ly/3j6eb3B"alt="cat"></img>
    ```
   - Semantic HTML
     
     Elemen semantik adalah elemen-elemen yang menyatakan makna atau tujuan dari elemen itu sendiri. Misalnya tag `<footer>` tag ini digunakan untuk membuat elemen footer atau bagian kaki dari web. Jangan gunakan tag ini di bagian paling atas, karena maknanya sudah jelas untuk footer.
   - Deploy HTML
     <div align="justify">Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. Jika aplikasi kita HTML atau Web App kita perlu mendeploy ke server. Untuk melakukan hal tersebut kita bisa menggunakan layanan yang bernama Netlify
&nbsp;
## CSS
- ### Pengertian CSS 
  <div align="justify">CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mendesain halaman website. Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya. Jika dianalogikan CSS merupakan baju dari sebuah website yang dapat membuat website terlihat lebih menarik
- ### Menyisipkan CSS ke dalam HTML dan Styling CSS
  a. Inline Style adalah menambahkan CSS pada attribute element HTML
     ```html
     <p style="color:brown">Tulisan ini berwarna coklat</p>
     ```
  b. Internal CSS menggunakan element/tag `<style>` untuk menyisipkan kode CSS. element/tag `<style>` diletakkan di dalam element `<head>`
  
     ```html
     <!DOCTYPE html>
     <html>
       <head>
         <title>Website Pemula</title>
         <style>
           body {
             background-color: blue;
           }
           h1 {
             color: white;
           }
           p {
             color: yellow;
           }
         </style>
       </head>
       <body>
         <h1>Website Pemula</h1>
         <p>Hallo World</p>
       </body>
     </html>
     ```
  c. Eksternal CSS
     <div align="justify">Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML. Menyisipkan kode CSS dengan cara membuat file CSS terpisah, dan lalu menyambungkannya dengan file HTML dengan menggunakan element <link>. Element <link> tersebut diletakkan di dalam element <head>
     
     Contoh:
     <div align="justify">Terdapat index.html untuk menaruh file HTML dan style.css untuk menaruh file CSS.
     
     ```html
     <!-- File index.html -->

     <!DOCTYPE html>
     <html>
       <head>
         <title>Website Pemula</title>
         <link rel="stylesheet" href="styles.css" />
       </head>
       <body>
         <h1>Website Pemula</h1>
         <p>Welcome World</p>
       </body>
     </html>
     ```
     
     ```css
     /* File styles.css */
     body {
       background-color: blue;
     }
     h1 {
       color: yellow;
     }
     p {
       color: red;
     }
     ```
- ### CSS Sintaks
  <div align="justify">CSS Syntax merupakan syntax yang digunakan untuk menunjuk atau memilih HTML element mana yang ingin diberi style (dihias). CSS syntax terdiri dari selector, property, dan value.

  Contoh syntaxnya seperti ini:

  ```css
  p {
    color: yellow;
  }
  ```
  
  Penjelasan :

  - p

    merupakan sebuah selector berupa element HTML yang akan/ingin diubah

  - color

    <div align="justify">Adalah sebuah properti berupa bagian mana dari element HTML yang akan diubah. Contoh diatas kita akan mengubah warna dari teks yang ada di element p

  - yellow

    merupakan value yaitu nilai/hiasan berupa warna kuning pada teks p
  
    - Selector yaitu benda (HTML element, misal paragraf) mana yang akan dihias.
    - Property adalah bagian dalam HTML misal, setiap huruf dari paragraf yang akan dihias.
    - Value adalah warna, yaitu nilai atau hiasan 'berupa apa' yang akan diberikan.

- ### Responsive Web 
  
  Viewport, secara umum viewport adalah daerah pada layar yang menampilkan suatu konten. Dalam konteks kita kali ini, tentu viewport adalah daerah yang menampilkan halaman web yang sedang kita akses.
  
  Untuk membuat halaman website menjadi responsif, maka kita perlu menambahkan meta data berikut ini di dalam element `<head>` di file HTML.
  
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  ```
  Meta data di atas akan mengatur viewport dari halaman website, di mana meta data tersebut akan memberikan instruksi kepada browser untuk mengatur bagaimana dimensi dan skala dari halaman website kita.
  - width=device-widthmemberitahu browser untuk mengikuti lebar layar dari perangkatnya. Sebab lebar layar tiap perangkat berbeda-beda.
  - initial-scale=1.0 memberitahu browser tingkat pembesaran (zoom level) dari halaman itu.
- ### CSS Flexbox 
  <div align="justify">Flexbox merupakan konsep pengaturan layout yang mengatur ukuran elemen Child dari suatu Container untuk beradaptasi dengan Parent/Container-nya. Flexbox umumnya digunakan pada sebuah elemen yang tidak pasti ukurannya atau berubah-ubah(dinamis). Hal ini sangat bermanfaat untuk membuat tampilan website responsif.
&nbsp;
## Algoritma dan Data Structure
- ### Definisi Algoritma
  <div align="justify">Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Dalam menyelesaikan masalah diperlukan data struktur, nah data inilah yang digunakan untuk menyelesaikan suatu masalah dengan menggunakan algoritma.
- ### Kenapa harus belajar algoritma?
  - Mempermudah pembuatan program dapat menyelesaikan masalah tertentu.
  - Data struktur digunakan untuk mengelola/manajemen sebuah data
  - Dan Algoritma yang akan menyelesaikan suatu permasalahan menggunakan data tersebut.
- ### Kualitas Algoritma
  - Input dan output harus didefinisikan terlebih dahulu dengan tepat
  - Setiap step harus benar-benar clear dan tidak ambigu
  - Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu. Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.
- ### Algoritma Sederhana
  - Contoh
    
    Menambahkan dua angka untuk pengguna
    
    a. Step 1 : Start
    
    b. Step 2 : Declare Variables num1, num2 and sum
    
    c. Step 3 : Read values num1 and num2
    
    d. Step 4 : add num1 and num2 and assign the result to sum. sum<-num1+num2
    
    c. Step 5 : Display Sum
    
    d. Step 6 : Stop
    
- ### Pseudocode
  <div align="justify">Pseudocode adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu. 
- ### Panduan menulis pseudocode
  
  - Menggunakan HURUF BESAR pada kata kunci (key commands). 
  
  CONTOH: IF number is > 10 THEN …
  
  - 1 statement =  1 baris 
  
  - Gunakan indentasi
  
  - Please please be specific
  
  - Tapi tetap simpel

  Contoh :

    ```md
    STORE "width" with any number
    STORE "height" with any nummber
    STORE "area" without any value

    CALCULATE "width" times "height"
    SET "area" value with calculation result
    DISPLAY "area"
    ```
 
- ### Pseudocode berdasarkan kondisi 

  - Procedural
  
  <div align="justify">Procedural adalah cara berpikir secara runtun. Artinya serangkaian perintah yang berurutan.
  
  Contoh :

      ```md
      STORE "width" with any number
      STORE "height" with any nummber
      STORE "area" without any value

      CALCULATE "width" times "height"
      SET "area" value with calculation result
      DISPLAY "area"
      ```
 - Conditional
 
    <div align="justify">Conditional digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi. Jika hari ini tidak hujan, maka Bob pergi ke pasar, jika tidak maka Bob dirumah aja. Jika tidak terpenuhi, maka tidak akan dijalankan.
  
  Contoh :
  
    ```md
      IF "bright"
      DO "go to the market"
      ELSE
      DO "stay at home"
      ```
 - Looping 
 
   <div align="justify">Komputer dapat melakukan sebuah proses yang sama berulang-ulang. Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.
  
  Contoh :
  
     ```md
      STORE "count" t0 1

      WHILE "count" < 11
      DISPLAY "count"
      CALCULATE "count" mod 2
      STORE "reminder" value with calculation result
      IF "reminder" equals to 0
      DISPLAY "EVEN!"
      ELSE
      DISPLAY "ODD!"
   
 - Recursive 
    <div align="justify">Recursive adalah pola pikir dalam algoritma yang memanggil method/function didalam sebuah function
  
## JavaScript Dasar
  
   - Definisi
      <div align="justify">Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript juga dapat membuat website menjadi interaktif dan dinamis
   - Menjalankan JS
      <div align="justify">Javascript dijalankan melalui browser pada device setiap user. 
   - Tipe Data
      <div align="justify">Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming. Ada 6 tipe data fundamental pada Javascript (number, string, boolean, null, undefined, object)
      
      - number: Tipe data number adalah tipe data yang mengandung semua angka termasuk angka desimal.Contoh (2, 4, 1200, 23.42)
      - string: ipe data string adalah grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya. Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “.
      - boolean: Tipe data boolean adalah tipe data yang hanya mempunyai 2 buah nilai. 2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah). Analoginya adalah seperti tombol/button ON/OFF dan juga seperti sebuah jawaban antara YES/NO.
      - null: Tipe data null adalah tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai. Null berbeda dengan string kosong. String kosong masih memiliki tipe data string.
      - undefined: Tipe data undefined adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai. Undefined berbeda dengan null.
      - object: Tipe data object adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).Tipe data object mempunyai key dan value.
&nbsp;
