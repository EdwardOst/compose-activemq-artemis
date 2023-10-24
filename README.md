# compose-activemq-artemis

Docker Hub Apache ActiveMQ [Artemis](https://hub.docker.com/r/apache/activemq-artemis) using Docker Compose

### Running

Run the artemis server

    docker compose up -d

Web console is available on http://localhost:8161/console

To run the artemis shell in attached mode

    docker compose exec artemis_server ./bin/artemis shell
