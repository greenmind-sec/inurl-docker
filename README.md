# Imagem do Google Inurl Docker
Imagem testada na amazon e funcionando perfeitamente.

# criando imagem
```sh
sudo docker build -t inurlbr:0.1 .
```

# usando a imagem
```sh
sudo docker run -it --rm inurl-docker:0.1 -h
```

# Compartilhando volumes
Caso queira compartilhar volumes.
```sh
sudo docker run -it --rm -v /SCANNER-INURLBR/output/:$(pwd) inurl-docker:0.1 -h
```
