# Generating of personal SSL

```
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

# Downloading of package

```
npm install
```

# Starting server

```
npm start
```