<style>
    p{
        text-align: justify;
    }
    .pic{
        text-align: center;
    }
</style>


NAMA : NURHALIZA
NIM : 2110131120007

### KOMPONEN SISTEM OPERASI, LAYANAN SISTEM OPERASI DAN SYSTEM CALL PADA WINDOWS 10

#### KOMPONEN SISTEM OPERASI
**A. Manajemen Sistem**

<p>   
Sistem operasi dapat melakukan manajemen proses seperti membuat dan menghapus proses pengguna dan sistem proses, serta dapat menunda dan menutup proses suatu program. Salah satu contoh nya yaitu ketika ada aplikasi atau software yang tidak merespon atau not responding sehingga mengakibatkan proses yang di jalankan sistem operasi menjadi meningkat dan menghambat proses proses lain yang berjalan. Manajemen proses dapat menutup paksa program tersebut dengan  END TASK. Kita dapat menggunakan end task dengan cara sebagai berikut:

1. Buka task manager, bisa dengan menekan tombol Ctrl+Alt+Del lalu pilih Task Manager atau dengan cara klik kanan pada Task Bar lalu pilih Task Manager.
<p class="pic">
    <img src="contoh/KA1.png" style="width: 400px;">
</p>

2. Klik more details
   <p class="pic">
    <img src="contoh/KA2.png" style="width: 400px;">
</p>

3. temukan program yang mengalami not responding tersebut
<p class="pic">
    <img src="contoh/KA3.png" style="width: 400px;">
</p>

4. klik kanan lalu pilih end task
5. selesai

**B. Manjemen Sistem Berkas**

Sistem operasi mengimplementasikan konsep abstrak dari berkas dan mengatur media penyimpanan massa. Akitvitas yang di lakukan berhubungan dengan manajemen berkas seperti pembuatan dan penghapusan berkas, pembuatan dan penghapusan direktori, manipulasi berkas dan direktori, pemetaan berkas ke secondary storage, serta back up ke media penyimpanan non-volatile. Salah satu contoh nya yaitu pembuatan folder pada file explorer. Berikut caranya:

1. Klik ikon folder pada taskbar atau dengan cara tekan tombol logo Windows + e
<p class="pic">
    <img src="contoh/KB1.png" style="width: 500px;">
</p>

2. pilih tempat untuk membuat folder baru, kemudian klik new folder pada bagian atas
<p class="pic">
    <img src="contoh/KB2.png" style="width: 400px;">
</p>

3. ketikkan nama folder kemudian tekan enter
<p class="pic">
    <img src="contoh/KB3.png" style="width: 400px;">
</p>

4. untuk menyimpan file ke folder baru , silahkan klik save kemudian telusuri folder baru yang ingin di gunakan

**C. Command Intrepreter System**

Sistem Operasi menunggu instruksi dari pengguna (command driven). Program yang membaca instruksi dan mengartikan control statements umumnya disebut: control-card interpreter, command-line interpreter dan terkadang dikenal sebagai shell.  Salah satu contohnya adalah ketika kita ingin mematikan laptop dengan command prompt (admin). Berikut caranya:

1. tekan Windows + R pada keyboard
2. ketik cmd kemudian tekan enter
<p class="pic">
    <img src="contoh/KC1.png" style="width: 400px;">
</p>


3. ketik shutdown –s kemudian tekan enter
<p class="pic">
    <img src="contoh/KC3.png" style="width: 500px;">
</p>

4. laptop akan mati kurang dari satu menit


#### LAYANAN SISTEM OPERASI

**A. Layanan Pembuatan Program**

Layanan pembuatan program adalah fasilitas yang membantu programer menulis program pada sebuah editor. Editor yang di sediakan oleh windows 10 salah satunya adalah Notepad. Berikut contoh cara menggunakan Notepad:

1. buka aplikasi notepad
<p class="pic">
    <img src="contoh/LA1.png" style="width: 500px;">
</p>

2. tuliskan kode program pada notepad
<p class="pic">
    <img src="contoh/LA2.png" style="width: 500px;">
</p>

3. jika sudah selesai, silahkan simpan file dengan membuka tab file pada bagian kiri atas kemudian klik save as
<p class="pic">
    <img src="contoh/LA3.png" style="width: 500px;">
</p>

4. tuliskan nama file, kemudian ubah save as type menjadi all file
<p class="pic">
    <img src="contoh/LA4.png" style="width: 500px;">
</p>

5. tuliskam ekstensi program di akhir nama file
<p class="pic">
    <img src="contoh/LA5.png" style="width: 500px;">
</p>   

6. klik enter

**B. Accounting**

Accounting adalah kegiatan merekam aktifitas pengguna, report pemakaian sumber daya. Sistem Operasi yang bagus harus mampu mengumpulkan data statistik penggunaan beragam sumber-daya dan memonitor parameter kinerja. Kita dapat melihat data statistik tersebut di bagian task manager.

1. Buka task manager, bisa dengan menekan tombol Ctrl+Alt+Del lalu pilih Task Manager atau dengan cara klik kanan pada Task Bar lalu pilih Task Manager.
<p class="pic">
    <img src="contoh/LB1.png" style="width: 500px;">
</p>

2. klik bagian Processes
<p class="pic">
    <img src="contoh/LB2.png" style="width: 500px;">
</p>


**C. Sistem Manipulasi Berkas**

Sistem manipulasi berkas adalah kemampuan program untuk operasi pada berkas (membaca, menulis, membuat, dan menghapus berkas yang berupa file atau direktori). Salah satu contohnya adalah kita akan menghapus sebuah folder yang sebelumnya sempat kita buat:

1. buka file manager lalu buka tempat folder tersebut berada
<p class="pic">
    <img src="contoh/LC1.png" style="width: 500px;">
</p>  

2. klik folder
<p class="pic">
    <img src="contoh/LC2.png" style="width: 500px;">
</p>

3. Klik kanan kemudian pilih delete
<p class="pic">
    <img src="contoh/LC3.png" style="width: 500px;">
</p>


Folder tersebut akan terhapus, namun kita masih bisa merestorasinya dengan cara membuka recycle bin, klik kanan pada file atau folder yang ingin di kembalikan kemudian pilih undo delete atau dengan menekan Ctrl+Z.

#### SYSTEM CALL

**A. Manajemen Berkas**

System calls yang berhubungan dengan berkas sangat diperlukan. Seperti ketika kita ingin membuat atau menghapus suatu berkas, atau ketika ingin membuka atau menutup suatu berkas yang telah ada, membaca berkas tersebut, dan menulis berkas itu. System calls juga diperlukan ketika kita ingin mengetahui atribut dari suatu berkas atau ketika kita juga ingin merubah atribut tersebut. Yang termasuk atribut berkas adalah nama berkas, jenis berkas, dan lain-lain. 

**B. Informasi maintenance**

Beberapa system calls disediakan untuk membantu pertukaran informasi antara pengguna dan sistem operasi. Contohnya system calls untuk meminta dan mengatur waktu dan tanggal. Atau meminta informasi tentang sistem itu sendiri, seperti jumlah pengguna, jumlah memori dan disk yang masih bisa digunakan, dan lain-lain. Ada juga system calls untuk meminta informasi tentang proses yang disimpan oleh sistem dan system calls untuk merubah ( reset ) informasi tersebut.

**C. Manajemen Direktori**

Sistem untuk mengatur suatu direktori yang berisikan file-file yang biasanya sudah dispesifikasikan tujuannya, seperti untuk user tertentu, dan untuk pemakaian secara bersama, sehingga tidak perlu banyak mengatur file-file tersebut tetapi cukup dengan mengatur direktorinya saja.

**CONTOH SYSTEM CALL**

|SYSTEM CALL|DESKRIPSI|
|    ---    |   ---   |
|CreateProcess()|A new process is created using this command|
|ExitProcess()|This system call is used to exit a process.|
|CreateFile()|A file is created or opened using this system call.|
|ReadFile()|Data is read from the file using this system call.|
|WriteFile()|Data is written into the file using this system call.|
|CloseHandle()|This system call closes the file currently in use.|
|SetTimer()|This system call sets the alarm or the timer of a process|
|CreatePipe()|A pipe is created using this system call|
|SetFileSecurity()|This system call sets the security for a particular process|
|SetConsoleMode()|This sets the input mode or output mode of the console’s input buffer or output screen buffer respectively.|
|ReadConsole()|This reads the characters from the console input buffer.|
|WriteConsole()|This writes the characters into the console output buffer.|


