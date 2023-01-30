# lab2py
## LATIHAN VCS
### Tugas pertemuan ke 4 Bahasa Pemrograman

Nama : Selma Ohoira

NIM : 312210727

Kelas : TI.22.C9

Prodi : Teknik Informatika

# LANGKAH AWAL MENGGUNAKAN GIT
## CARA MENDOWNLOAD GIT
1. Langkah pertama yaitu dengan mendownload git.
   Bukalah situs resmi dari git itu sendiri yaitu git-scm.com
2. Setelah itu langsung saja mendownloadnya dengan cara memilih
   terlebih dahulu yang sesuai dengan laptop/pc yang digunakan.
   Jika itu 32bit silahkan download 32, begitu juga jika 64bit.
   Bisa langsung klik dan akan terdownload secara otomatis.
 ![Gambar 1](gambar/1.png)
3. Setelah instalisasi terbuka, bisa langsung membuka command prompt
   pada menu windows dan melakukan pengecekan versi dari git kalian
   dengan mengetik syntax: git --version
4. Jika sudah mendapat tampilan seperti gambar dibawah ini artinya git telah berhasil terinstall.
![Gambar 2](gambar/2.png)
5. Selanjutnya melakukan konfigurasi saat pertama kali menggunakan git.
   Hal ini agar tidak gagal saat melakukan commit. Dengan masukan perintah berikut :
![Gambar 3](gambar/3.png)
Masukan email dan user name Anda

## LANGKAH AWAL MENGGUNAKAN GITHUB
# Login akun Github
Buka github pada situs resminya github.com. Setelah itu pilih menu SignUp
jika memang belum mempunyai akun. Jika sudah punya akun silahkan langsung SignIn.
![Gambar 4](gambar/4.png)
Dan jika sudah berhasil regist, tampilannya akan seperti dibawah ini :
1[Gambar 5](gambar/5.png)

# Langkah membuat REPOSITORY pada GITHUB
1. Buka profile kalian, kemudian pilih dibagian start a project,
   atau bisa juga dengan menekan lambang (+) pada pojok bagian kanan atas.
2. Setelah itu tekan New Repository
![Gambar 6](gambar/6.png)
3. Ketik judul yang diinginkan dan disana bisa diatur apakah repository
   tersebut besifat privacy ataupun public
4. Jika tampilannya seperti dibawah ini, artinya repository sudah berhasil
   dan dapat membukanya pada tuisan README
![Gambar](gambar/11.png)
   Jika ingin menulis sesuatu atau mengedit sebuah teks yang sudah ada sebelumnya
   pada lembar kerja, kalian bisa menekan gambar pensil seperti digambar diatas.
   Dan tekan commit changes untuk menyimpan perubahan pada lembar kerja.
# Setelah repository selesai, selanjutnya cara me-remmote REPOSITORY pada GITBASH lokal
1. Langkah pertama, salin URL git kita yang ada pada Github. Caranya tekan Code
![Gambar](gambar/12.png)
2. Setelah link URL git tercopy, selanjutnya buka File Explorer pada windows.
   Kemudian pilih folder dimana kita mendownload Repository dari Github ke lokal
![Gambar](gambar/7.png)
3. Kemudian klik kanan dan tekan perintah Git Bash Here
![Gambar](gambar/8.png)
4. Setelahnya pop Up Command Promp (CMD) akan terbuka. Pada proses ini kita akan melakukan
   download file repository yang tadi dibuat, dengan menggunakan syntax : git clone "link URL Github"
![Gambar](gambar/13.png)
5. Setelah cloning selesai, masukan perintah syntax : cd 'n(nama folder yang tadi dicloning)/'
     untuk masuk kedalam folder yang telah dicloning.
![Gambar](gambar/14.png)
6. Selanjutnya kita bisa mengedit file README.md yang ada pada File Explorer dengan menggunakan
   Text Editor (Sublime Text, Notepad, Notepad+++, Visual Studio Code).
7. Setelah mengedit, pastikan hasil editan tersimpan.
8. Langkah selanjutnya kembali membuka App GitBash dan masukan perintah
   syntax : 'git add .'
![Gambar](gambar/15.png)
9. Selanjutnya melakukan commit yang dimana fungsi commit adalah untuk menyimpan perubahan
   yang dilakukan, tetapi tidak terjadi perubahan pada remote repository.
   Caranya masukan syntax : 'git commit "keterangan perubahan apa yang dilakukan"'.
![Gambar](gambar/16.png)
10. Setelah git commit selesai, melakukan Git Push yang dimana berfungsi untuk mengirimkan
   perubahan file yang telah dicommit ke remote repository. Caranya masukan syntax : 'git push'
![Gambar](gambar/17.png)

JIKA SEMUA PROSES DIATAS SUDAH DILAKUKAN SEMUA TANPA ADA YANG TERLEWAT,
KALIAN BISA LANGSUNG MELIHAT PERUBAHAN REPOSITORY DENGAN MEMBUKANYA
PADA LAMAN GITHUB. SEKIAN & SELAMAT MENCOBA :)