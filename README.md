# PERMAINAN-TIC-TAC-TOE
Meningkatkan pemahaman mahasiswa terhadap code permainan tic tac toe. Selain itu, modul 6 memberikan pengetahuan tentang Object Oriented Programming menggunakan bahasa pemrograman Java terutama Java Swing dan Japplet.

6.1. Tujuan
Meningkatkan pemahaman mahasiswa terhadap code permainan tic tac toe. Selain itu, modul 6
memberikan pengetahuan tentang Object Oriented Programming menggunakan bahasa pemrograman
Java terutama Java Swing dan Japplet.
6.2. Dasar Teori
6.2.1. Permainan Tic Tac Toe
Penyelesaian masalah permainan tic tac toe dapat menggunakan algoritma heuristic untuk
mencapai solusi yang optimal. Pada modul ini memperlihatkan bagaimana membuat sebuah
permainan tic tac toe. Initial state dari permainan ini adalah puzzle ukuran 8 yang tidak berisikan apaapa. Ketika pemain pertama menekan salah satu ubin, maka ubin tersebut akan diberikan tanda
silang. Pemain kedua harus menghalangi pemain pertama untuk membuat tanda silang berjajaran baik
secara vertikal, horizontal, atau diagonal. Permainan ini akan berakhir (goal state) ketika salah
seorang pemain sudah menderetkan tanda meraka masing-masing baik secara vertikal, horizontal, atau
diagonal.
Solusi dari permasalahan ini dapat dilakukan dengan membuat topologi Tree, kemudian
setiap langkah dari pemain pertama atau kedua akan menjadikan initial state selanjutnya, kemudian
langkah tersebut akan dijadikan sebagai initial state yang baru sampai menemukan goal statenya.
Ilustrasi penyelesaian masalah permainan tic tac toe ini dapat dilihat melalui Gambar 6.1.
Gambar 6.1. Pohon Permainan Tic Tac Toe
© 2017 - Modul Praktikum Kecerdasan Buatan
6.3. Implementasi Permainan Tic Tac Toe
6.3.1. Menggunakan Graphical User Interface (GUI)
Permainan ini dibuatkan dengan menggunakan Java Swing yang terdiri dari 3 buah Java Class
dan 3 buah pendeklarasian enumaration. Ke-enam file tersebut dituliskan secara terpisah namun
disimpan pada folder yang sama (misalnya folder tic tac toe). Ke-enam file tersebut dituliskan nama
secara berurutan seperti berikut:
1. State.Java
2. Seed.Java
3. GameState.Java
4. Cell.Java
5. Board.Java
6. GameMain.Java
  
Pemberian sebuah nilai integer kepada variabel untuk membedakan status penggunaan (misalnya jika
tic tac toe sedang dimainkan, variable PLAYING diberikan nilai 0, variable DRAW = 1, dan
sebagainya) tidak begitu efektif di dalam penulisan code. Sekarang, JDK1.5 memperkenalkan fitur
baru yang dinamakan dengan enumaration, yang merupakan class spesial untuk menyimpan semua
variabel secara berurutan. Enumaration State, Seed, dan GameState didefinisikan secara file terpisah

Tuliskan semua Java Code diatas, kemudian pelajari code nya, dan ubahkan beberapa bagian untuk
melihat perubahannya.

Program yang Anda berikan adalah implementasi permainan Tic-Tac-Toe (O dan X) menggunakan Java. Program ini mencakup beberapa kelas dan komponen untuk membuat permainan ini bisa dimainkan di aplikasi desktop atau sebagai applet di halaman web.
Program ini menggunakan beberapa kelas enumerasi, seperti GameState dan Seed, untuk menggambarkan berbagai keadaan permainan dan jenis isi sel (kosong, X, O).
Kelas Cell digunakan untuk merepresentasikan setiap sel pada papan permainan. Setiap sel memiliki atribut content yang menyimpan isinya (kosong, X, atau O), serta atribut row dan col yang menyimpan baris dan kolom sel tersebut.Kelas Board adalah representasi dari papan permainan dengan sel-selnya. Ini terdiri dari array 2D dari objek Cell.
Kelas GameMain adalah kelas utama yang mengatur UI permainan menggunakan Java Swing. Pada kelas ini, pemain dapat mengklik sel untuk menempatkan X atau O. Program memeriksa apakah ada pemenang atau hasil seri setelah setiap klik, dan menampilkan pesan status pada status bar.Terdapat juga kelas AppletMain yang memungkinkan permainan ini dimainkan sebagai sebuah applet di halaman web.berdasarkan percobaan merupakan implementasi permainan Tic-Tac-Toe dengan antarmuka grafis menggunakan Java Swing. Ini memungkinkan dua pemain untuk bermain secara bergantian, dan menyediakan pesan status yang menunjukkan giliran pemain dan hasil permainan. Program ini bisa dimainkan baik sebagai aplikasi desktop atau sebagai applet di halaman web.Melalui program ini, kita dapat memahami implementasi dasar permainan Tic-Tac-Toe, manajemen tampilan grafis, dan penggunaan enumerasi untuk mengatur keadaan permainan. 
berdasarkan beberapa sumber yang diambil arti dari pemanggilan tiap perintah sebagai berikut
1. Program ini dibagi menjadi beberapa kelas, yaitu GameState, Seed, State, Cell, Board, GameMain, dan AppletMain.
2. GameState, Seed, dan State adalah enumerasi yang digunakan untuk menggambarkan berbagai keadaan permainan.
3. Cell adalah kelas yang merepresentasikan sel dalam papan permainan. Setiap sel memiliki konten (Seed) yang bisa kosong, "X", atau "O".
4. Board adalah kelas yang merepresentasikan papan permainan, terdiri dari sel-sel (Cell) dalam bentuk array 2D.
5. GameMain adalah kelas utama yang mengatur UI permainan menggunakan Java Swing. Ini adalah kelas yang menangani permainan sebenarnya.
Pada GameMain, pemain dapat mengklik sel dalam papan permainan untuk mengisi sel dengan "X" atau "O". Setelah setiap klik, permainan memeriksa apakah ada pemenang atau hasil seri. Ada juga statusBar untuk menampilkan pesan status seperti "Gantian X" atau "X Menang."

sebelumnya mohon maaf tidak dapat menambilkan hasil program dalam file github dikarenakan sudah mencoba di beberapa tugas namun extention tidak daapt terinstal dikarenakan mungkin laptop tidak support, series laptop lama terimakasih sebelumnya bapak..
