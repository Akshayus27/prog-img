### Instructions

1. Go to the root folder and run

```bash
npm install
```

2. Install docker and docker-compose (optional)

    [docker] https://docs.docker.com/engine/install/

    [docker-compose] https://docs.docker.com/compose/install/

3. Install redis and mongodb to your system and start the services 


4. Optional to run redis commader and view redis cache

```bash
npm install -g redis-commander
```
5. Update env

```.env
PORT
MONGODB_URI
REDIS_URL
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_BUCKET_NAME
```
6. Start the node server

```bash
npm start
```
7. Instead you can run all the service by doing(requires docker),

```bash
docker-compose up
```
