# Usage of docker-compose-create-nuxt-app

git clone git@github.com:sonatine726/docker-compose-create-nuxt-app.git .

docker compose up

cd .\docker_start_nuxt\

cp * ..\nuxtapp\

cd ..

rm -d docker_start_nuxt

cd .\nuxtapp\

docker compose up -d

* VSCode Dev Container can be use in nuxtapp directory. For using Dev Container, nuxt service should be rebuiled from VSCode.
