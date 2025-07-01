# first-take
Belajar Deploy Github Pages

DEPLOY FILE HTML VIA GITHUB PAGES
1. Download VScode
https://code.visualstudio.com/

2. Buat akun github (siapkan username dan email)
https://github.com/

3. Download Git scm
https://git-scm.com/

4. Konfigurasi git lewat terminal VScode 

git config --global user.name "username github kamu"

git config --global user.email "email github kamu"

git config --list

5. Buka vscode, liat pojok kiri bawah, icon orang, klik pilih sign in untuk auto integrasi login dengan GitHub account 

6. Buka akun github, buat new repository, copy  URL repository untuk clone via HTTPS (belakangnya ada .git)

7. Buka terminal vscode, arahkan ke directory Desktop. Jalankan command ini

git clone URL_repo

8. Buka folder Desktop tadi, saat ini sudah ada folder baru yang berhasil di-clone dari repo, namun masih kosong belum ada isinya. 

9. Siapkan file html yang mau di-deploy. Bisa pake output hasil tugas pertama yg python, misal peta.html. Ubah namanya menjadi index.html. Simpan file tsb di dalam folder repo di Desktop tadi (poin 8).

10. Ketikkan command ini untuk push file index.html kita ke github

git add .

git commit -m "keterangan"

git push


11. Buka akun github, bila berhasil push, maka file index.html tadi sudah berhasil muncul di repository kita.

12. Selanjutnya klik icon setting di repo, lalu klik  pages di sidebar, lalu deploy pilih main---> save

13. Klik setting, atur link URL yang ingin kita deploy nantinya. biasanya formatnya username.github.io/namarepo
Contoh: https://digitradiart.github.io/peta-jaringan-peralatan-observasi-iklim/

14. Halaman website berhasil di-deploy via github pages




DEPLOY  APLIKASI STREAMLIT VIA GITHUB
(Streamlit Community Cloud).

Langkah-langkahnya: 
1. Buat akun di Streamlit Community Cloud.

2. Buat repository baru di GitHub untuk aplikasi Streamlit. Pastikan repository ini publik.

3. Di Streamlit Community Cloud, hubungkan akun GitHub kita.

4. Ikuti petunjuk otentikasi GitHub yang diberikan. Ini akan memberikan akses ke repository publik.

5. Push semua file kode aplikasi Streamlit ke repository GitHub yang baru dibuat. Pake command ini di terminal. Ketik satu2, lalu tekan enter.

git add .

git commit -m "keterangan"

git push

6. Deploy Aplikasi. Di Streamlit Community Cloud, klik "New app".

7. Isi informasi repositori (URL repositori, cabang, dan jalur file). Tambahkan informasi lainnya jika diperlukan (misalnya, versi Python, koneksi data).

8. URL web app streamlit siap di-share.
Sebagai contoh: https://indonesia-microclimate-dashboard.streamlit.app/

13. Klik setting, atur link URL yang ingin kita deploy nantinya. biasanya formatnya username.github.io/namarepo
Contoh: https://digitradiart.github.io/peta-jaringan-peralatan-observasi-iklim/

14. Halaman website berhasil di-deploy via github pages
