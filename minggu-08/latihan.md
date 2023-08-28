Buat direktori untuk proyek: mkdir composetes

Buat file yang dipanggil di direktori proyek Anda dan tempelkan kode berikut di:app.py


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/e996f9af-efac-4629-a527-1a50e58e03fa)

Buat file lain yang dipanggil di direktori proyek Anda dan Tempel kode berikut di:requirements.txt

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/2b77f58d-7603-4f22-ac20-37a509ace1cf)


Di direktori proyek Anda, buat file bernama dan tempelkan kode berikut di:Dockerfile


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/58d6f018-cd06-43b2-bc5e-ec7f85b5dae0)


Dari direktori proyek Anda, mulai aplikasi Anda dengan menjalankan .docker compose up
login docker


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/ddd3c7ec-93dd-4c76-97a0-44e6bb3a2861)


Dari direktori proyek Anda, mulai aplikasi Anda dengan menjalankan .docker compose up

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/b82c36a5-9047-47b8-8d44-8626cd1c5316)


Masukkan http://localhost:8000/ di browser untuk melihat aplikasi berjalan.

Jika ini tidak teratasi, Anda juga dapat mencoba http://127.0.0.1:8000.

Anda akan melihat pesan di browser Anda yang mengatakan:

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/8cec90e2-3194-4974-8a2a-332310581764)


Refresh halaman.

Jumlahnya harus bertambah

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/2255b2ac-7d94-4edf-8d2b-5748f4692bfd)

Beralih ke jendela terminal lain, dan ketik untuk mencantumkan gambar lokal.docker image ls


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/41ae552b-c83f-474f-80b5-89b4c6c66dcc)


Edit di direktori proyek Anda untuk menambahkan pemasangan pengikatan untuk layanan:docker-compose.ymlweb

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/d4bb4010-c7ac-4e88-afb7-7e464f131e87)


Dari direktori project, ketik untuk mem-build aplikasi dengan file Compose yang diperbarui, lalu jalankan.docker compose up

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/75ff9680-1fd2-47bc-b7e8-beaa24cef0b7)

Ubah salam dan simpan. Misalnya, ubah pesan menjadi :app.pyHello World!Hello from Docker!

return 'Hello from Docker! I have been seen {} times.\n'.format(count)

![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/fb6e1eac-908a-4804-8c1b-c350263a561a)


Jika Anda ingin menjalankan layanan Anda di latar belakang, Anda dapat meneruskan bendera (untuk mode "terpisah") ke dan gunakan untuk Lihat apa yang sedang berjalan:-ddocker compose updocker compose ps


![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/2949abaa-f7c3-46b0-a0e7-0ee88faa7b32)



![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/7355f4d2-616d-46c3-a7dc-33585fdbdc80)





