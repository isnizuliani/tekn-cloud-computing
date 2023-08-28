Buat direktori untuk proyek: mkdir composetest

Buat file yang dipanggil di direktori proyek Anda dan tempelkan kode berikut di:app.py

![img](foto8/3.png)

Buat file lain yang dipanggil di direktori proyek Anda dan Tempel kode berikut di:requirements.txt

![img](foto8/4.png)

Di direktori proyek Anda, buat file bernama dan tempelkan kode berikut di:Dockerfile

![img](foto8/5.png)

Dari direktori proyek Anda, mulai aplikasi Anda dengan menjalankan .docker compose up

![img](foto8/6.png)

login docker


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/ddd3c7ec-93dd-4c76-97a0-44e6bb3a2861)


Dari direktori proyek Anda, mulai aplikasi Anda dengan menjalankan .docker compose up

![img](foto8/8.png)

Masukkan http://localhost:8000/ di browser untuk melihat aplikasi berjalan.

Jika ini tidak teratasi, Anda juga dapat mencoba http://127.0.0.1:8000.

Anda akan melihat pesan di browser Anda yang mengatakan:

![img](foto8/9.png)

Refresh halaman.

Jumlahnya harus bertambah

![img](foto8/10.png)

Beralih ke jendela terminal lain, dan ketik untuk mencantumkan gambar lokal.docker image ls

Edit di direktori proyek Anda untuk menambahkan pemasangan pengikatan untuk layanan:docker-compose.ymlweb

![img](foto8/12.png)

Dari direktori project, ketik untuk mem-build aplikasi dengan file Compose yang diperbarui, lalu jalankan.docker compose up

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/75ff9680-1fd2-47bc-b7e8-beaa24cef0b7)

Ubah salam dan simpan. Misalnya, ubah pesan menjadi :app.pyHello World!Hello from Docker!

return 'Hello from Docker! I have been seen {} times.\n'.format(count)

![img](foto8/14.png)

Jika Anda ingin menjalankan layanan Anda di latar belakang, Anda dapat meneruskan bendera (untuk mode "terpisah") ke dan gunakan untuk Lihat apa yang sedang berjalan:-ddocker compose updocker compose ps

![img](foto8/15.png)





