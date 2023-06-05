<center>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/20674439/158480514-a529b310-bc19-46a5-ac95-fddcfa4776ee.png" width="150"/>&nbsp;
    <img src="https://icon-library.com/images/php-icon/php-icon-8.jpg"  width="150" />
  </p>  
  <h1 align="center">🚀 Microserviço: API Catálogo de Vídeos com PHP/Laravel</h1>
  <p align="center">
    Microserviço API de Catálogo de Vídeos, com PHP <br />
    Projeto com TDD, Clean Arch, DDD e etc;
  </p>
</center>

### Como rodar?

Clone the repository

```sh
git clone https://github.com/igorbrum/client-video-api.git
```

```sh
cd client-video-api
```

Create the .env file

```sh
cp .env.example .env
```

Launch the projects containers

```sh
docker compose up -d
```

Access the container app

```sh
docker-compose exec app bash
```

Install the project dependencies

```sh
composer install
```

Generate the Laravel project key

```sh
php artisan key:generate
```

Access the project
[http://localhost:81](http://localhost:81)
