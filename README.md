just a dumb footloose setup of influxdb, timescaledb, an outflux migration host

install footloose

    docker network create deflux-net
    footloose create

    ansible-playbook all.yml

telegraf will create some data..

    ansible-playbook migrate.yml

