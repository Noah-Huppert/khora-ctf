# Stenography Instructions
To create the embedded image:

```
outguess -d msg.txt cute-cat.jpg cute-cat-embedded.jpg
```


To extract this data:

```
outguess -r cute-cat-embedded.jpg decoded.txt
```

Then copy this image to `./reverse-proxy/www/acme-company/images/cute-cat.jpg`.
