# Web-statis-docker
Berikut adalah tutorial untuk membangun Web Statis menggunakan Docker, salah satu cara mudah adalah memanfaatkan suatu file yakni Dockerfile untuk membuat template images yang kita inginkan.

1. Install terlebih dahulu packages Docker menggunakan command
   apt install docker.io

2. Buat Dockerfile nya dengan isi yang berada di direktori ini

3. Buat index.html nya pada direktori yang sama, dengan isi sesuai dengan keinginan

4. Setelah selesai membuat file-file di atas, jalankan command berikut: docker build -t biodata-web .

5. docker run -d -p 3017:80 biodata-web

6. Masuk ke Browser dan cari iplocal:port yang telah dibuat sebelumnya
