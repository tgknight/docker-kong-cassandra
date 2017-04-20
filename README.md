# docker-kong-cassandra
Docker for Kong with Cassandra, with exposed database directory

## Prerequisite
- Docker
- [Docker-compose](https://docs.docker.com/compose/install/)

## Usage
### Start the service
```
cd docker-kong-cassandra
docker-compose up -d
```
Wait for the initialization process to finish ~30 seconds

### Endpoints
There is one predefined endpoints: `localhost:8000`. The endpoint will redirect a user to `http://httpbin.org`.  
All requests available to the site are available via the endpoint as well.

More info on kong endpoints at [kong documentation](https://getkong.org/docs/0.10.x/admin-api/#api-object).
