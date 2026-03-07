# Sistem Operasi

Owner: Erov
Last edited time: November 13, 2025 12:36 PM

### Pengertian Sistem Operasi

Definisi formal yang disediakan oleh sumber-sumber ini adalah:

**Sistem Operasi adalah perangkat lunak yang mengelola seluruh sumber daya komputer dan menghubungkan antara pengguna dengan perangkat keras.**

Dari definisi ini, kita dapat memahami posisi sentral Sistem Operasi dalam arsitektur komputasi:

1. **Jenis Komponen**: Sistem Operasi didefinisikan sebagai **perangkat lunak** (software).
2. **Posisi Sentral**: Secara hierarkis, Sistem Operasi digambarkan berada di antara **HARDWARE** dan lapisan atas, yaitu **APLIKASI** serta **PENGGUNA**.
3. **Fungsi Kunci**: Fungsi utamanya ada dua:
    - **Pengelolaan Sumber Daya**: Sistem Operasi bertugas **mengelola seluruh sumber daya komputer**.
    - **Penghubung**: Sistem Operasi berfungsi **menghubungkan antara pengguna dengan perangkat keras**.

### Keterkaitan Pengertian dengan Peran

Definisi Sistem Operasi secara langsung menjabarkan perannya, yang dalam sumber disebut sebagai Penghubung, Manajer Proses, dan Penyedia Antarmuka.

1. **Realisasi Penghubung**: Fungsi "menghubungkan pengguna dengan perangkat keras" dalam definisi diimplementasikan melalui peran sebagai **Penghubung**, di mana Sistem Operasi memungkinkan *hardware* komputer yang tersedia dapat diakses oleh pengguna.
2. **Realisasi Manajemen Sumber Daya**: Fungsi "mengelola seluruh sumber daya komputer" diimplementasikan melalui peran sebagai **Manajer Proses** (Manajemen Sumber Daya), di mana Sistem Operasi mengatur bagaimana setiap bagian utama komputer digunakan secara **efisien dan adil** oleh berbagai program yang berjalan.
3. **Realisasi Interaksi**: Selain menghubungkan pengguna ke *hardware*, Sistem Operasi juga berperan sebagai **Penyedia Antarmuka**, menyediakan cara bagi pengguna untuk berinteraksi dengan komputer.

Oleh karena itu, dalam konteks *Informatika Pertemuan 7*, Pengertian Sistem Operasi tidak hanya sekadar definisi, tetapi juga dasar untuk memahami mengapa Sistem Operasi dikelompokkan ke dalam berbagai jenis (seperti *Single User*, *Multi User*, *Time Sharing*, atau *Real-Time*) dan bagaimana ia memenuhi tujuan pembelajaran untuk memahami dinamika I-P-O dalam komputer Von Neumann.

Pembahasan mengenai **Peran Sistem Operasi** merupakan komponen kunci dari materi *Sistem Operasi (Informatika Pertemuan 7)*. Memahami peran ini adalah salah satu **Tujuan Pembelajaran** eksplisit dalam pertemuan tersebut.

Peran Sistem Operasi menjabarkan bagaimana perangkat lunak ini bertindak sebagai jembatan yang penting antara pengguna, aplikasi, dan perangkat keras komputer (*hardware*).

Berdasarkan sumber-sumber yang diberikan, peran Sistem Operasi diklasifikasikan menjadi tiga fungsi utama:

### 1. Penghubung (*Connector*)

Sistem Operasi menjalankan peran sebagai **Penghubung**. Peran ini berfokus pada aksesibilitas *hardware*:

- **Sistem Operasi memungkinkan *hardware* komputer yang tersedia dapat diakses oleh pengguna**.
- Fungsi ini memastikan bahwa pengguna dapat memanfaatkan sumber daya fisik komputer, seperti CPU, memori, dan perangkat *input/output*, karena Sistem Operasi yang menjembataninya.

### 2. Manajer Proses (*Process Manager*)

Sistem Operasi berfungsi sebagai **Manajer Proses** yang bertanggung jawab atas pengelolaan sumber daya secara internal. Peran manajemen ini berfokus pada efisiensi dan keadilan:

- **Sistem Operasi mengatur bagaimana setiap bagian utama komputer digunakan**.
- Penggunaan sumber daya harus diatur **secara efisien dan adil** oleh berbagai program yang berjalan secara simultan.
- Peran ini sangat penting untuk memastikan sistem tetap stabil dan responsif meskipun banyak program (proses) berjalan pada saat yang sama.

### 3. Penyedia Antarmuka (*Interface Provider*)

Sistem Operasi juga berperan sebagai **Penyedia Antarmuka**. Antarmuka ini adalah sarana interaksi antara manusia dan mesin:

- **Sistem Operasi menyediakan cara bagi kita (pengguna) untuk berinteraksi dengan komputer**.
- Antarmuka ini bisa berbentuk grafis (GUI) atau teks (*command line*) yang memungkinkan pengguna memberikan perintah dan menerima *output* dari sistem.

### Konteks yang Lebih Besar

Dalam konteks *Informatika Pertemuan 7*, pemahaman mengenai peran ini sangat krusial karena:

1. **Mendukung Tujuan Pembelajaran**: Memahami peran sistem operasi secara langsung memenuhi tujuan pembelajaran pertemuan ini.
2. **Memahami Dinamika I-P-O**: Peran Manajer Proses khususnya sangat berkaitan dengan tujuan pembelajaran lain, yaitu "Mampu memahami model dan menyimulasikan dinamika **Input-Process-Output** dalam sebuah komputer Von Neumann". Sistem Operasi, sebagai manajer, adalah yang mengatur proses *processing* tersebut, memastikan *input* diolah dan *output* dihasilkan dengan efisien.
3. **Justifikasi Keberadaan OS**: Peran-peran ini menjawab pertanyaan pemantik, "Pernahkah kalian menggunakan perangkat (komputer/handphone) yang bisa digunakan tanpa ada operasi didalamnya?". Jawabannya adalah tidak, karena tanpa peran *Penghubung*, *Manajer Proses*, dan *Penyedia Antarmuka*, *hardware* tidak akan dapat diakses, dikelola secara efisien, atau dioperasikan oleh pengguna.

Diskusi mengenai **Komponen Utama Interaksi** adalah inti dari pemahaman Sistem Operasi, sesuai dengan ruang lingkup materi pada *Informatika Pertemuan 7*. Sumber-sumber yang tersedia secara eksplisit mendefinisikan dan menempatkan komponen-komponen yang terlibat dalam interaksi di dalam sistem komputer, di mana Sistem Operasi berperan sebagai mediator sentral.

Berikut adalah komponen-komponen utama yang terlibat dalam interaksi dan peran Sistem Operasi sebagai penghubungnya:

### 1. Empat Komponen Hierarkis

Berdasarkan definisi dan ilustrasi struktural yang disajikan, empat komponen utama yang berinteraksi di dalam sistem komputasi adalah:

- **Perangkat Keras (*Hardware*)**: Ini adalah fondasi fisik dari sistem.
- **Sistem Operasi (OS)**: Perangkat lunak yang berada di atas *hardware*.
- **Aplikasi (APLIKASI)**: Perangkat lunak yang digunakan oleh pengguna untuk melakukan tugas tertentu, yang berada di atas Sistem Operasi.
- **Pengguna (PENGGUNA)**: Individu yang menggunakan sistem dan berada di lapisan teratas interaksi.

Dalam interaksi, Sistem Operasi berada di antara *hardware* dan lapisan atas, yaitu APLIKASI dan PENGGUNA.

### 2. Peran Sistem Operasi dalam Interaksi

Sistem Operasi adalah perangkat lunak yang **menghubungkan antara pengguna dengan perangkat keras**. Peran ini dipecah menjadi dua fungsi interaksi utama:

### A. Penghubung (*Connector*)

Sebagai Penghubung, Sistem Operasi memungkinkan **perangkat keras komputer yang tersedia dapat diakses oleh pengguna**. Ini berarti interaksi fungsional antara pengguna (yang ingin menggunakan sistem) dan *hardware* (yang melakukan pekerjaan) dimediasi sepenuhnya oleh OS.

### B. Penyedia Antarmuka (*Interface Provider*)

Fungsi interaksi yang paling terlihat oleh pengguna adalah melalui antarmuka:

- **Sistem Operasi menyediakan cara bagi kita untuk berinteraksi dengan komputer**.
- Dalam kategorisasi perannya, Sistem Operasi secara spesifik disebut sebagai **Penyedia Antarmuka**.

### C. Manajer Proses (Interaksi Program)

Meskipun tidak berinteraksi langsung dengan pengguna, Sistem Operasi juga mengatur interaksi antara berbagai **program yang berjalan** (Aplikasi) dengan sumber daya *hardware*. Peran sebagai **Manajer Proses** ini memastikan bahwa sumber daya digunakan secara **efisien dan adil**, yang pada akhirnya mempengaruhi kualitas interaksi pengguna dengan aplikasi.

### 3. Interaksi Non-Langsung (Implikasi Jenis OS)

Sumber juga menyebutkan jenis-jenis Sistem Operasi yang menunjukkan variasi dalam mekanisme interaksi:

- **Sistem *Batch Processing*** Program dijalankan **tanpa interaksi langsung** (*batch*). Hal ini menekankan bahwa, meskipun OS dapat memfasilitasi interaksi langsung (melalui antarmuka), ada pula skenario (terutama pada komputer generasi lama) di mana interaksi pengguna dihapus dari proses eksekusi program.
- **Sistem *Time Sharing*** Dalam sistem *time sharing*, interaksi melibatkan pembagian waktu di CPU, di mana **setiap pengguna mendapat waktu bergantian untuk memakai CPU**. Ini adalah mekanisme interaksi yang memungkinkan *Multi User* berinteraksi seolah-olah mereka adalah satu-satunya pengguna pada sistem.

### Konteks *Informatika Pertemuan 7*

Pemahaman mengenai komponen interaksi (Pengguna-Aplikasi-OS-Hardware) ini sangat vital karena berkaitan langsung dengan **Tujuan Pembelajaran** pertemuan tersebut, yaitu:

1. **Memahami peran sistem operasi**: Peran sebagai Penghubung dan Penyedia Antarmuka menjelaskan bagaimana OS mewujudkan interaksi.
2. **Menyimulasikan dinamika *Input-Process-Output* (I-P-O)**: Interaksi pengguna (memberikan *input*) diproses melalui aplikasi dan OS (sebagai Manajer Proses) sebelum menghasilkan *output* melalui *hardware*. Seluruh model I-P-O bergantung pada interaksi antara keempat komponen utama ini.

**Jenis Sistem Operasi** merupakan komponen materi ketiga dalam ruang lingkup pembahasan *Sistem Operasi (Informatika Pertemuan 7)*. Klasifikasi ini membantu siswa memahami bagaimana peran sentral Sistem Operasi (yaitu mengelola sumber daya secara efisien dan menghubungkan pengguna dengan *hardware*) diimplementasikan pada berbagai lingkungan komputasi yang berbeda.

Sumber-sumber ini mengklasifikasikan Jenis Sistem Operasi berdasarkan empat kriteria utama:

### 1. Berdasarkan Jenis Pengguna

Kategori ini membedakan Sistem Operasi berdasarkan jumlah pengguna yang dapat mengakses sistem secara simultan:

- **Sistem Operasi *Single User***: Sistem ini dirancang hanya bisa digunakan oleh **satu pengguna dalam satu waktu**. Contoh yang diberikan meliputi MS-DOS dan Windows 10 (pada komputer pribadi).
- **Sistem Operasi *Multi User***: Sistem ini memiliki kemampuan untuk digunakan oleh **lebih dari satu pengguna secara bersamaan**. Contohnya adalah Linux Server, Unix, dan Windows Server.

### 2. Berdasarkan Jenis Perangkat

Klasifikasi ini didasarkan pada lingkungan perangkat keras tempat Sistem Operasi tersebut dipasang:

- **Sistem Operasi Komputer**: Digunakan pada PC, laptop, atau server. Contoh umum adalah Windows, macOS, dan Linux.
- **Sistem Operasi *Mobile***: Dirancang khusus untuk perangkat genggam, yaitu *smartphone* dan tablet. Contohnya termasuk Android dan iOS.
- **Sistem Operasi *Embedded***: Dipasang pada **perangkat khusus** (bukan komputer umum). Contoh penerapannya mencakup OS pada mesin cuci, TV, mobil pintar (*Car OS*), dan router.

### 3. Berdasarkan Cara Proses

Kategori ini menjelaskan mekanisme Sistem Operasi dalam menangani dan menjalankan tugas atau program (*processing*), yang sangat terkait dengan tujuan pembelajaran memahami dinamika *Input-Process-Output* (I-P-O):

- ***Batch Processing System***: Program dijalankan secara berkelompok (*batch*) **tanpa interaksi langsung** dari pengguna. Sistem ini banyak digunakan pada komputer generasi lama, seperti IBM Mainframe OS.
- ***Time Sharing System***: Mekanisme di mana setiap pengguna mendapat **waktu bergantian** untuk memakai CPU. Contohnya adalah Unix, Linux, dan Windows Server.
- ***Real-Time System***: Sistem yang digunakan ketika Sistem Operasi harus merespons **sangat cepat terhadap *input***. Penerapan pentingnya terdapat pada sistem di pesawat, robot industri, atau alat medis. Contoh Sistem Operasi spesifiknya adalah VxWorks dan RTLinux.

### 4. Berdasarkan Tujuan

Klasifikasi ini didasarkan pada arsitektur atau infrastruktur jaringan yang menjadi fokus Sistem Operasi:

- **Sistem Operasi Jaringan**: Dirancang khusus untuk **mengatur komunikasi dan sumber daya antar komputer dalam jaringan**. Contoh: Novell NetWare, Windows Server, dan Linux Ubuntu Server.
- **Sistem Operasi Terdistribusi**: Bertujuan untuk **mengatur beberapa komputer agar bekerja seolah menjadi satu sistem**. Contoh yang disebutkan adalah Amoeba OS dan Plan 9.

# Bagian

Sistem operasi secara umum terdiri dari beberapa bagian:

- Mekanisme [Boot](https://id.wikipedia.org/wiki/Booting), yaitu meletakkan kernel ke dalam memory
- [Kernel](https://id.wikipedia.org/wiki/Kernel_%5C(Ilmu_komputer%5C)), yaitu inti dari sebuah sistem operasi
- *Command Interpreter* atau *shell*, yang bertugas membaca input dari pengguna
- Pustaka-pustaka, yaitu yang menyediakan kumpulan fungsi dasar dan standar yang dapat dipanggil oleh aplikasi lain
- Driver untuk berinteraksi dengan hardware eksternal, sekaligus untuk mengontrolnya.
- Daemon adalah aplikasi latar belakang yang ada untuk kelangsungan sistem operasi itu sendiri