### Get Image

    docker pull postgres

### Create & Run Container

    docker run --name postgres -e POSTGRES_PASSWORD='thirumal' -d -p 5432:5432 postgres

### Connect to PostgreSQL container

    docker exec -it postgres /bin/bash
