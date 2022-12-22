# ETL-with-Airbyte

```
mkdir airbyte && cd airbyte
wget https://raw.githubusercontent.com/airbytehq/airbyte/master/{.env,docker-compose.yaml}
mv docker-compose.yaml airbyte.yml
set -a; . ./.env; set +a
docker stack deploy -c airbyte.yml airbyte
docker-compose up -d
```


```
git clone https://github.com/airbytehq/airbyte.git
cd airbyte
docker-compose up
```


```
BASIC_AUTH_USERNAME=airbyte
BASIC_AUTH_PASSWORD=password
```
