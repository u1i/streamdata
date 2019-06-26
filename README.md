# Streamdata Demo

## API Management

[API Manager](https://localhost:8075/home) (apiadmin / Axway123)

[API Gateway](https://localhost:8090) (admin / changeme)

[API Portal](https://localhost/) (uli / Axway123)


## Cloud Backend API

### Endpoint

[Swagger](http://backend.yoisho.dob.jp/stockquote/swagger)

[Example Request](http://backend.yoisho.dob.jp/stockquote/current)

### Consume protected API

curl -k https://localhost:8065/stockquote/current?KeyId=a7d011b8-507c-45ab-a9e0-aaa8fcf290b6

### Consume external version of the protected API

curl https://quote.ngrok.io/stockquote/current?KeyId=a7d011b8-507c-45ab-a9e0-aaa8fcf290b6


### Consume Stream API

curl -v "https://streamdata.motwin.net/https://quote.ngrok.io/stockquote/current?X-Sd-Token=ZTdlMGZmNzgtN2UxZS00NDZhLWEzMWQtZTMxMmFmMzJlODQy"


## Backend API (Phoenix)

### Endpoint

[Swagger](http://208.67.130.150:8086/stockquote/swagger)

[Example Request](http://208.67.130.150:8086/stockquote/current)

### Consume protected API

curl -k http://localhost:8888/stockquotephx/current?KeyId=a7d011b8-507c-45ab-a9e0-aaa8fcf290b6

### Consume external version of the protected API

curl https://quote.ngrok.io/stockquotephx/current?KeyId=a7d011b8-507c-45ab-a9e0-aaa8fcf290b6

### Consume Stream API

curl -v "https://streamdata.motwin.net/https://quote.ngrok.io/stockquotephx/current?X-Sd-Token=ZTdlMGZmNzgtN2UxZS00NDZhLWEzMWQtZTMxMmFmMzJlODQy"
