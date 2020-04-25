# e14dts2020
# PANDUAN GIT COLLABORATION

## 1. Clone Repository ke Local

 - Buka CMD di direktori **htdocs**
 - Ketik kode berikut
	> git clone https://github.com/yasiasiahaan/e14dts2020.git

## 2. Buat branch baru
Branch (cabang) digunakan untuk mengembangkan fitur-fitur secara terisolasi. Sehingga untuk pengembangan fitur, disarankan untuk membuat branch baru untuk masing-masing fitur yang dikembangkan. Langkah-langkah untuk membuat branch baru:
 - Masuk ke folder repository yang telah berhasil di clone dengan command:
	 > CD namafolder

 - Ketik command berikut untuk menambah branch baru:
	 > git checkout -b nama_branch

	 jadi diawal ada **feature-** sebagai penanda ini adalah branch untuk feature
## 3. Push file di local ke branch
Setelah temen-temen menambahkan fitur baru di local, hal yang perlu dilakukan selanjutnya yaitu melakukan push (upload) file dari local ke branch yang tadi di buat. Langkah-langkahnya sebagai berikut:
 - Tambah file ke antrian untuk di push: 
	> git add -A

 - Buat pesan komit/catatan perubahan yang dilakukan:
 
	> git commit -m "Pesan komit"

 - Push ke feature_branch yang dibuat tadi:
 

	> git push origin "nama_branch"

## Lakukan Merge-Request
Setelah file di push, maka langkah selanjutnya yaitu mengirim permintaan untuk dilakukan merge (penggabungan) ke repository develop.

 - Buka repository di browser.
 - Pilih branch yang dikelola
 - Klik **Pull Request**
 - Pilih branch -> **Develop**
 - Isi pesan (optional) lalu klik **Create pull request**
