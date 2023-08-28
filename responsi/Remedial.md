##Cara Create Data  Dengan Docker
1. Install Docker
2. tarik gambar Docker PostgreSQL atau denga perintah **docker pull postgres**
![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/acb50510-cd94-4dd9-9119-ff78c29d0ee4)


4. jalankan kontainer PostgreSQL dengan perintah:
   *docker run --name my-postgres-container -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres*
   Ganti my-postgres-containerdengan nama penampung Anda, dan mysecretpassworddengan kata sandi yang diinginkan untuk pengguna super 
5. Hubungkan ke Kontainer PostgreSQL : Anda dapat terhubung ke kontainer PostgreSQL menggunakan alat klien PostgreSQL seperti psqlatau alat GUI seperti pgAdmin. Untuk terhubung menggunakan psql
![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/840d3389-145c-477c-91f8-c2f7be37193e)

6. membuat tabel dengan perintah berikut:
![image](https://github.com/isnizuliani/tekn-cloud-computing/assets/127279123/9c80409c-7193-4d2b-8b7b-b3c9029e6ca6)

8. Kemudian Keluar dari Prompt PostgreSQL : Untuk keluar dari prompt PostgreSQL, Anda dapat mengetik \q.

 
