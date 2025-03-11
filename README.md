# Cyber Partners Sneakier Gophish

## Usage

Run it using Docker

```bash
docker build -t cp-gophish .
docker run -itd --name cp-gophish -p 3333:3333 -p 80:80 cp-gophish
```

Get the initial admin password from the logs:

```bash
docker logs cp-gophish | grep password
```

### Documentation

Documentation can be found [here](http://getgophish.com/documentation) (there is also documentation for the API!).
