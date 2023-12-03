# reactjs-fake-database


1. Pertama Install JSON Server 

```
npm install -g json-server
```

2. Jalankan JSON Server

```bash
json-server --watch db.json --port 1234
```
Aplikasi akan bejalan pada port 1234 [http://localhost:1234]

Untuk Mengakases data contoh:


```
GET    /pengguna
GET    /pengguna/{id}
POST   /pengguna
PUT    /pengguna/{id}
PATCH  /pengguna/{id}
DELETE /pengguna/{id}
```


