# ngrok
# ngrok
this dir file is my domain build ngrokd and ngrok(linux cnetos7.2-64)


## How start ngrokd

```
cd /home/soft/ngrok/

./bin/ngrokd -tlsKey=server.key -tlsCrt=server.crt -domain="domain.com" -httpAddr=":80" -httpsAddr=":82"
```

## How start ngrok
>> like this

> cd /home/soft/ngrok/

> ./ngrok -subdomain pubs -proto=http  8082
