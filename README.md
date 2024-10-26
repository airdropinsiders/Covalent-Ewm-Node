## Join My Telegram Channel
Join Here
[**https://t.me/AirdropInsiderID**](https://t.me/AirdropInsiderID).

# Manual
```
docker stop light-client && docker rm light-client
```

```
docker system prune -a
```


```
rm -rf  ewm-das
```

# install
```
git clone https://github.com/covalenthq/ewm-das
```

```
cd ewm-das
```
```
docker build -t covalent/light-client -f Dockerfile.lc .
```
```
docker run -d --restart always --name light-client -e PRIVATE_KEY="GANTI_PRIVATE_KEY_BURNER" covalent/light-client
```
# cek logs
```
docker logs -f light-client
```
