# basic-docker-commands
belajar docker

docker <commands> --help

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

Membuat container
> docker container create <namaImages>

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


## Docker Network



## Lainnya

> docker ps -a

> docker exec -it <namaContainer>
 



