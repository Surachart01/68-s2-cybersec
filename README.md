# Cyber Security


## Infomation
- Surachart Limrattanaphun (สุรชาติ ลิ้มรัตนพันธ์)
- 6702041510164
- email : s6702041510164@email.kmutnb.ac.th

## Environment
```sh
cp env.example .env
```

## Running service

### Database

```sh
docker compose -f db.yaml up -d
```

### Admin
```sh
docker compose -f admin.yaml up -d
```

### Application
```sh
docker compose -f app.yaml up -d
```


