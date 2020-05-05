just a dumb footloose setup of influxdb, timescaledb, an outflux migration host

install footloose

    footloose create
    docker network create deflux-net

    ansible-playbook all.yml

telegraf will create some data..

    ansible-playbook migrate.yml

