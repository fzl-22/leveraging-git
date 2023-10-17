# Leveraging Git as Your Version Control System

Repositori ini dibuat untuk mendemonstrasikan penggunaan Git dan GitHub untuk acara pengenalan Google Developer Student Clubs Institut Teknologi Telkom Surabaya.

## 1. Cara Menginstall Git


### 1.1 Install Git di Windows

1. Kunjungi [git-scm.org](https://git-scm.org). Pilih "**Download for Windows**".

    ![](./assets/1.%20Kunjungi%20web%20git-scm.com.png)

2. Pilih "**Standalone Installer**" yang 64 bit. Tunggu hingga download selesai.

    ![](./assets/2.%20Pilih%20standalone%20installer%2064-bit.png)

3. Klik 2x pada installer, maka akan muncul halaman lisensi. Klik "**Next**".

    ![](./assets/3.%20Klik%20installer,%20maka%20akan%20muncul%20halaman%20lisensi.png)

4. Pilih lokasi instalasi Git, biarkan default di `C:\Program Files\Git`. Klik "**Next**".

    ![](./assets/4.%20Pilih%20lokasi%20instalasi%20Git.png)

5. Pilih komponen yang ingin di-install. Centang "**Add a Git Bash Profile to Windows Terminal**" agar bisa menjalankan Git di terminal Windows (CMD dan Powershell). Jika ingin ada shortcut di Desktop, centang "**Additional icons**". Klik "**Next**".

    ![](./assets/5.%20Pilih%20komponen%20yang%20akan%20diinstall.png)

6. Pilih nama folder Start Menu, biarkan default. Klik "**Next**".

    ![](./assets/6.%20Pilih%20nama%20shortcut.png)

7. Pilih code editor default untuk Git. Secara default, opsinya adalah menggunakan Vim. Karena Vim sulit digunakan, pilih code editor lain seperti Visual Studio Code melalui dropdown. Pastikan VSCode telah terinstall dahulu. Klik "**Next**".

    ![](./assets/7.%20Pilih%20default%20code%20editor.png)

8. Pilih nama branch default. Pilih "**Let Git decide**" agar default branch tetap bernama `master`. Klik "**Next**".

    ![](./assets/8.%20Pilih%20nama%20branch%20default.png)

9. Pilih konfigurasi PATH. Pilih "**Git from the command line and also from 3rd-party software**" agar Git bisa dijalankan juga di luar Git Bash. Klik "**Next**".

    ![](./assets/9.%20Pilih%20konfigurasi%20PATH.png)

10. Pilih program SSH yang digunakan Git, biarkan default. Klik "**Next**".

    ![](./assets/10.%20Pilih%20bundled%20SSH.png)

11. Pilih SSL library yang digunakan Git, biarkan default. Klik "**Next**".

    ![](./assets/11.%20Pilih%20OpenSSL%20library.png)

12. Pilih konfigurasi konversi *line ending*, biarkan default. Klik "**Next**".

    ![](./assets/12.%20Pilih%20checkout%20Windows-style.png)

13. Pilih terminal emulator untuk Git Bash, biarkan default. Klik "**Next**".

    ![](./assets/13.%20Pilih%20MinTTY%20sebagai%20terminal%20emulator.png)

14. Pilih perilaku default untuk `git pull`, biarkan default. Klik "**Next**".

    ![](./assets/14.%20Pilih%20default%20behaviour%20untuk%20git%20pull.png)

15. Pilih credential helper, biarkan default. Klik "**Next**".

    ![](./assets/15.%20Pilih%20Git%20Credential%20Manager.png)

16. Atur konfigurasi tambahan, centang "**Enable file system caching**". Klik "**Next**".

    ![](./assets/16.%20Pilih%20enable%20file%20system%20caching.png)

17. Atur konfigurasi experimental, jangan pilih apapun. Setelah itu, klik "**Install**" untuk memulai instalasi. Tunggu hingga selesai.

    ![](./assets/17.%20Jangan%20pilih%20fitur%20experimental.png)

18. Instalasi selesai, klik "**Finish**".

    ![](./assets/18.%20Instalasi%20telah%20selesai.png)

19. Klik aplikasi "**Git Bash**", maka akan muncul terminal emulator MSYS2 yang dapat digunakan untuk menjalankan Git. Git juga dapat dijalankan di luar "**Git Bash**", misalnya Command Prompt dan Powershell. Periksa instalasi dengan menjalankan perintah berikut: `git --version`. 

    ![](./assets/19.%20Git%20bisa%20diakses%20di%20MSYS2%20maupun%20terminal%20bawaan%20Windows.png)

### 2.1 Install Git di Linux

Biasanya, Git sudah terinstall secara bawaan di sistem operasi berbasis Linux. Jika tidak, maka Git dapat diinstall menggunakan package manager setiap distro Linux.

#### 2.1.1 Debian-based

```bash
sudo apt install git
```

#### 2.1.2 RPM-based

```bash
sudo dnf install git
```

#### 2.1.3 Arch-based

```bash
sudo pacman -S git
```



