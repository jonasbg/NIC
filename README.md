# NodeRed + InfluxDb + Chronograf (NIC)
---
This project is a starter for NIC

Please change username and password for InfluxDb, DO NOT USE `admin`!!!

## How to get started:
```bash
git clone https://github.com/jonasbg/NIC.git
cd NIC
docker-compose up -d
docker-compose logs
```

This will create `./volumes/` folder where the data from all of these instances is saved. Backup this folder if you need the data.
