# Example Docker Compose project for Ddos protection tests

## Run Example
```bash
$ docker-compose up
$ docker-compose run kali bash
$ apt-get install hping3 siege
$ hping3 --rand-source -2 --fast -V -D -c 100 protected
$ siege -b  -c100 -v -t30s protected
```

### Grafana
- URL: http://localhost:3000 
- User: admin 
- Password: admin 
