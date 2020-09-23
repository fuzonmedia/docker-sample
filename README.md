# docker-sample
Docker sample to spinup web infrastructure for application using nginx proxy , lets encrypt, laravel, horizon, worker node, redis 

## Operations 
`docker network create nginx-proxy` #### create external network 
`cd php-laravel-container/app` <br/>
`git clone https://github.com/laravel/laravel.git` <br/>
`docker compose up -d --build` <br/>
