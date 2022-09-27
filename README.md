# **Writing and Presentation**
## Day 1 Unix Commad Line & GIT/GitHub
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
## Day 1 GIT & GitHub
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
## Day 2 HTML
- ### Pengertian HTML 
  <div align="justify">HTML adalah singkatan dari Hypertext Markup Language. HTML digunakan untuk menampilkan konten pada web. HTML dapat dianalogikan sebagai kerangka dari suatu website. HTML bersifat statis. HTML hanya bertugas menampilkan konten yang diminta oleh developer.
  <div align="justify">Contoh konten pada HTML: Text, Image, Video, Link dll
- ### Kerangka HTML 
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
  <div align="justify">Seorang programmer akan selalu menggunakan berbagai macam tools. Tools ini untuk memudahkan dan menambah produktifitas seorang programmer. Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML yaitu Browser dan Code Editor
  Visual Studio Code: Visual Studio Code adalah code editor yang dikembangkan oleh tim engineer Microsoft. Visual Code Studio merupakan paket all in one. Kamu bisa menggunakan ini untuk bahasa pemrograman apapun.
