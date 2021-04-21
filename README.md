# basic-docker-commands
belajar docker


## DOCKER IMAGE

Mendapatkan daftar image pada lokal
> docker image ls

Mengambil image dari registry
> docker pull <namaImage>

Menghapus image
> docker image rm <namaImage>


## Docker container

Mendapatkan daftar container pada lokal yang runnning
> docker container ls
> --all ,untuk melihat beserta yang tidak running

Membuat container
> docker container create <namaImages>
> --name <namaCustomContaienr> ,untuk memberi nama container
> -p luar:dalam, untuk pengaturan port.
> -e ,menambahkan environment variable

Menjalankan container
> docker container start <namaContainer>

Menghapus container
> docker container rm <namaContainer>

Stop menjalankan container
> docker container stop <namaContainer>


## BUILD DOCKER IMAGES

Membuat image dari Dockerfile
> docker build -t <namaImage> .

Menjalankan kontainer dari image yang dibuat
> docker run <namaImage>
> -t ,untuk mengaktifkan akses terminal
> -d ,untuk menjalankan pada background
> -p ,menentukan port container
> --name ,nama container


## Docker Network



## Lainnya

> docker ps -a

> docker exec -it <namaContainer>


