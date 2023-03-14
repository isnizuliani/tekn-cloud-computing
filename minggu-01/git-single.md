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

# Clone Repo
Proses clone adalah proses untuk menduplikasikan remote repo di GitHub ke komputer lokal. Untuk melakukan proses clone, gunakan perintah berikut:
![image](https://user-images.githubusercontent.com/127279123/224911982-508bc3d8-0d89-4e8e-bf76-7218c326bc51.png)
Setelah perintah ini, di direktori awesome-project akan disimpan isi repo yang sama dengan di GitHub. Perbedaannya, di komputer lokal terdapat direktori .git yang digunakan secara internal oleh Git.

# Mengelola Repo
Setelah clone ke komputer lokal, semua manipulasi konten dilakukan di komputer lokal dan hasilnya akan di-push ke remote repo di GitHub. Dengan demikian, jangan berganti-ganti remote lokal, sekali dibuat disitu, tetap berada disitu. Jika kehilangan repo lokal, clone ulang ke direktori yang bersih (kosong) setelah itu baru lakukan pengelolaan repo. Beberapa hal yang biasanya dilakukan akan diuraikan berikut ini.

# Mengubah isi - Push tanppa branching dan merging
perubahan isi bisa terjadi karena suatu atau kombinasi beberapa hal berikut
1. file di hapus
2. file diedit
3. membuat file/ direktori baru
4. menghapus direktori

untuk kasus-kasus tersebut, lakukan perubahan di komputer lokal, setlah itu push ke repo
![image](https://user-images.githubusercontent.com/127279123/224920775-e2b3e963-488d-419f-b09f-6bfed71e76d7.png)
Cara ini lebih mudah tetapi mempunyai resiko jika terjadi kesalahan dalam edit. Cara yang lebih aman tetapi memerlukan langkah yang lebih panjang adalah branching and merging

# Mengubah isi dengan branching and merging
Mengubah Isi dengan Branching and Merging
Dengan menggunakan cara ini, setiap kali akan melakukan perubaham, perubahan itu dilakukan di komputer lokal dengan membuat suatu cabang yang nantinya digunakan untuk menampung perubahan-perubahan tersebut. Setelah itu, cabang itu yang akan dikirim ke repo GitHub untuk dimintai review kemudian digabungkan (merge) ke master. Secara umum, repo yang dibuat biasanya sudah mempunyai satu branch yang disebut dengan master. Cara ini lebih aman, terstruktur, terkendali, dan mempunyai history yang lebih baik. Jika perubahan yang kita buat sudah terlalu kacau dan kita menyesal, maka ada cara untuk "membersihkan" repo lokal kita. Secara umum, langkahnya adalah sebagai berikut:

1. Buat branch untuk menampung perubahan-perubahan
2. Lakukan perubahan-perubahan
3. Add dan commit perubahan-perubahan tersebut ke branch
4. Kembali ke repo master
5. Buat pull request di GitHub
6. Merge pull request di GitHub
7. Merge branch untuk menampung perubahan-perubahan tersebut ke master.
8. Selesai.
9. 
![image](https://user-images.githubusercontent.com/127279123/224922362-6a91b820-6073-4df5-809c-235cc1547ef4.png)

setelah itu, kirim pill request (PR):
![image](https://user-images.githubusercontent.com/127279123/224925877-d51f1eda-a2c5-4b0f-9b3d-f8084d824b2e.png)

![image](https://user-images.githubusercontent.com/127279123/224925486-2701e411-c80a-45f5-b102-c6f682dc0151.png)

setelah membuat PR, PR tersebut bisa di-merge:
![image](https://user-images.githubusercontent.com/127279123/224925693-e97fb28e-6abd-4ccd-af70-64e616b7b6f9.png)
Setelah itu, Confirm Merge, branch yang kita kirimkan tadi sudah dimasukkan ke branch master. Setelah itu, merge di komputer lokal:
![image](https://user-images.githubusercontent.com/127279123/224926041-a6687193-96ed-454b-8743-549dd36b0358.png)

# Sinkronisasi
Suatu saat, bisa saja terjadi kita menggunakan komputer lain dan mengedit repo melalui repo lokal di komputer lain, setelah itu pindah ke kamputer lain lagi. Saat itu, kita perlu melakukan sinkronisasi ke kemputer lokal. Perintah untuk sinkronisasi adalah:
![image](https://user-images.githubusercontent.com/127279123/224926296-98b54b45-d381-4106-9ca7-68fc726869b9.png)


# Membatalkan perubahan 
Praktik yang baik adalah membuat branch pada saat kita akan melakukan perubahan-perubahan. Jika perubahan-perubahan yang kita lakukan sudah sedemikian kacaunya, maka kita bisa membuat supaya perubahan-perubahan yang kacau tersebut hilang dan kembali ke kondisi bersih seperti semula.
![image](https://user-images.githubusercontent.com/127279123/224927614-9abe1871-ce00-48e2-bd89-b1f673a6bc4f.png)

# Undo commit yang terakhir
Suatu saat, mungkin kita sudah terlanjur mem-push perubahan ke repo GitHub, setelah itu kita baru menyadari bahwa perubahan tersebut salah. Untuk itu, kita bisa melakukan git revert.
![image](https://user-images.githubusercontent.com/127279123/224929431-17b1fe8e-012b-4b84-bc19-ce3ab2e3d94d.png)
![image](https://user-images.githubusercontent.com/127279123/224929612-e1cec52e-537d-4773-94cb-d93bb19d9b9a.png)

Contoh di atas adalah contoh untuk mengubah README.md dengan beberapa commit. Setelh itu, kita akan mengembalikan ke posisi terakhir sebelum commit terakhir.

![image](https://user-images.githubusercontent.com/127279123/225103975-3533fafd-ab37-433f-8531-4f54218ba234.png)
Perintah di atas akan membuka editor. Pada editor tersebut kita bisa mengetikkan pesan revert ( = pesan commit untuk pembatalan). Setelah selesai, simpan:

[master f800ced Revert "Add: contents - 2"
 1 file changed, 1 deletion(-)
$

selanjutnya tinggal di-push ke repo GitHub
![image](https://user-images.githubusercontent.com/127279123/225104284-2f83f470-12ef-4955-97f6-560ba8ff2d76.png)
 jika commit sudah dilakukan, tetapi belum di-push ke repo GitHub (masih berada di lokal), cara membatalkannya:
 ![image](https://user-images.githubusercontent.com/127279123/225104561-d8ab290e-1ce8-4741-b1b3-78db903014ba.png)

Untuk kembali ke perubahan pada saat yang sudah lama, yang perlu dilakukan adalah melakukan git revert <posisi> kemudian mengedit secara manual kemudian push ke repo.
![image](https://user-images.githubusercontent.com/127279123/225105058-6528057e-9e0c-49d4-8bf6-9006c52650ae.png)

Setelah itu, jika dilihat pada file, akan muncul tambahan untuk memudahkan meng-edit. File ini harus di-resolve terlebih dahulu, setelah itu baru di add dan commit:
![image](https://user-images.githubusercontent.com/127279123/225105166-4cb6e503-ac61-4bc1-af38-888be7d7e339.png)
edit file tersebut, setalah itu simpan
![image](https://user-images.githubusercontent.com/127279123/225106528-f17cd935-b7c2-4149-a7ef-5b0b60ce32ee.png)

Setelah itu, lanjutkan proses revert. Saat git revert --continue isikan pesan revert.
![image](https://user-images.githubusercontent.com/127279123/225105413-96d6e1af-9cb5-443a-97d1-aff1613c946c.png)

# Mengelola repo sendiri di organisasi
Bagian ini merupakan seri tulisan tentang Git. Silahkan ke README.md untuk memahami gambaran garis besar materi-materi yang dituliskan.

Repo yang dibuat bisa diletakkan pada account kita maupun berada pada suatu organisasi. Organisasi bisa kita buat sendiri maupun kita dimasukkan menjadi anggota organisasi. Pada dasarnya, bagian ini sama dengan bagian sebelumnya, hanya saja, pada saat membuat repo Owner dari repo adalah organisasi seperti berikut ini:










