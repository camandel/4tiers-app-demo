# 4 tiers appliction demo for docker-compose
Application demo composed by:
- 4 services (db, api server, fe server, reverse-proxy)
- 3 networks
- 1 volume
## Usege
- add new records in `sql-scripts/init.sql` file (optional)
- start containers with docker-compose:
```
docker-compose up -d
curl http://localhost:8001
```
## Directories structure
```
├── api
│   ├── Dockerfile
│   ├── index.js
│   └── package.json
├── docker-compose.yaml
├── reverse-proxy
│   ├── default.conf
│   └── Dockerfile
├── sql-scripts
│   └── init.sql
└── webapp
    ├── Dockerfile
    ├── index.js
    └── package.json
```

