# 01-install git
1. Setelah download Git, double click pada file yang di-download. Akan dimunculkan lisensi. Klik Next untuk lanjut.
![image](https://user-images.githubusercontent.com/127279123/224608749-270cb386-2f46-4b68-b518-e89eb9bde477.png)
![image](https://user-images.githubusercontent.com/127279123/224608843-65fa9176-329d-45f8-bc34-0a21220f6fdd.png)
![image](https://user-images.githubusercontent.com/127279123/224608884-f5e1d34a-a7d9-4741-836d-4053d25a648d.png)
![image](https://user-images.githubusercontent.com/127279123/224608901-29aded4a-09cc-4dd6-b5c9-3ec6590a034f.png)
![image](https://user-images.githubusercontent.com/127279123/224608929-bb879f65-dc57-4fcd-a3be-fa0210d44d72.png)
![image](https://user-images.githubusercontent.com/127279123/224608939-08fb3103-8d64-44f0-aec4-54e129312f93.png)
![image](https://user-images.githubusercontent.com/127279123/224608948-71755641-ee8c-4d78-922b-918ee29fa173.png)
![image](https://user-images.githubusercontent.com/127279123/224608954-01ac3fcf-7a86-4aff-a453-77931194d3fb.png)
![image](https://user-images.githubusercontent.com/127279123/224609011-65aa8907-05a8-4bbe-8ef5-c15d3b71d681.png)
![image](https://user-images.githubusercontent.com/127279123/224609022-c3d2b9cf-439a-4f15-a024-ba18ad615462.png)
![image](https://user-images.githubusercontent.com/127279123/224609055-b9cecaef-a709-4da7-9ba9-ab101f8425d4.png)
![image](https://user-images.githubusercontent.com/127279123/224609065-0acf79ef-2a25-48e0-9ffa-e059b6ae662d.png)
![image](https://user-images.githubusercontent.com/127279123/224609089-eb81077a-265c-4462-8f81-d5ab338f7a5f.png)
![image](https://user-images.githubusercontent.com/127279123/224609127-bfab2aab-6bb1-4366-9895-28c20bfab237.png)
![image](https://user-images.githubusercontent.com/127279123/224609112-7225adcb-e079-4c17-8313-90e52e66041a.png)

# 02-Konfigurasi Git
Bagian ini merupakan seri tulisan tentang Git. Silahkan ke README.md untuk memahami gambaran garis besar materi-materi yang dituliskan.
Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo. Di sistem operasi Linux atau sejanis (UNIX), konfigurasi ini nantinya akan disimpan di $HOME/.gitconfig. Untuk sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. Gunakan perintah berikut:
![image](https://user-images.githubusercontent.com/127279123/224610334-121b0ff7-31e8-4820-afb7-56d2d75d6eab.png)

# 03- Mengelola repo sendiri
Bagian ini merupakan seri tulisan tentang Git. Silahkan ke README.md untuk memahami gambaran garis besar materi-materi yang dituliskan.

# Langkah-langkah
Setiap orang yang telah mempunyai account di GitHub bisa membuat repo dengan. Secara umum, langkah-langkahnya adalah sebagai berikut:

Buat repo kosong di GitHub, bisa public maupun private.
Cloe repo kosong tersebut di komputer lokal
Perintah berikutnya terkait dengan perubahan repo serta sinkronisasi antara GitHub dengan lokal.
# Membuat Repo
Untuk membuat repo, gunakan langkah-langkan berikut:

1- klik tanda +pada bagian kanan atas setelah login. pilih new repository
![image](https://user-images.githubusercontent.com/127279123/224618118-ff5b5fb8-a3df-4444-9587-292a84884b1a.png)

2- Isikan nama, keterangann serta lisensi. jika dikehendaki, bisa membuat repo Privatr
![image](https://user-images.githubusercontent.com/127279123/224618296-74477de7-f650-405d-a477-2f215e59f6cd.png)

3- klik create repository
Setelah langkah-langkah tersebut, repo akan dibuat dan bisa diakses menggunakan pola https://github.com/username/reponame. Pada repo tersebut, hanya akan muncul 1 file, yaitu LICENSE. Jika memilih membuat README pada saat langkah ke 2, juga akan muncul README.md. Ada atau tidak ada README.md tidak mempunyai efek apapun pada langkah ini.

#Clone Repo
Proses clone adalah proses untuk menduplikasikan remote repo di GitHub ke komputer lokal. Untuk melakukan proses clone, gunakan perintah berikut:
![image](https://user-images.githubusercontent.com/127279123/224911982-508bc3d8-0d89-4e8e-bf76-7218c326bc51.png)
Setelah perintah ini, di direktori awesome-project akan disimpan isi repo yang sama dengan di GitHub. Perbedaannya, di komputer lokal terdapat direktori .git yang digunakan secara internal oleh Git.

#Mengelola Repo
Setelah clone ke komputer lokal, semua manipulasi konten dilakukan di komputer lokal dan hasilnya akan di-push ke remote repo di GitHub. Dengan demikian, jangan berganti-ganti remote lokal, sekali dibuat disitu, tetap berada disitu. Jika kehilangan repo lokal, clone ulang ke direktori yang bersih (kosong) setelah itu baru lakukan pengelolaan repo. Beberapa hal yang biasanya dilakukan akan diuraikan berikut ini.

#Mengubah isi - Push tanppa branching dan merging
perubahan isi bisa terjadi karena suatu atau kombinasi beberapa hal berikut
1. file di hapus
2. file diedit
3. membuat file/ direktori baru
4. menghapus direktori

untuk kasus-kasus tersebut, lakukan perubahan di komputer lokal, setlah itu push ke repo


