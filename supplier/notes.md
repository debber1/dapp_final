# Production database

server name: supdb
host: supdb.mysql.database.azure.com
Location: France Central
administrator login: dapp
pw: Niet dom doen, je weet goed genoeg welk wachtwoord we hier pakke

# RGBeast

rgb store db: dapp_rgbeast
host: rgbeast.francecentral.cloudapp.azure.com
user: dapp
pw: Niet dom doen, je weet goed genoeg welk wachtwoord we hier pakke


test command: 
```
curl -H 'x-api-key: fa3b2c9c-a96d-48a8-82ad-0cb775dd3e5d' -X POST https://rgbeast.francecentral.cloudapp.azure.com/RGBeast/list_products | jq
```

Certbot with let's encrypt is running
Nginx web server

# Crank Wankers

bike store db: dapp_crank_wankers
host: crank-wankers.francecentral.cloudapp.azure.com
user: dapp
pw: Niet dom doen, je weet goed genoeg welk wachtwoord we hier pakke

test command: 
```
curl -H 'x-api-key: fa3b2c9c-a96d-48a8-82ad-0cb775dd3e5d' -X POST https://crank-wankers.francecentral.cloudapp.azure.com/Crank-Wankers/list_products | jq
```

# Crank Wankers

battery store db: dapp_battery_bastards
host: battery-bastards.francecentral.cloudapp.azure.com
user: dapp
pw: Niet dom doen, je weet goed genoeg welk wachtwoord we hier pakke

test command: 
```
curl -H 'x-api-key: fa3b2c9c-a96d-48a8-82ad-0cb775dd3e5d' -X POST https://battery-bastards.francecentral.cloudapp.azure.com/Battery-Bastards/list_products | jq
```
