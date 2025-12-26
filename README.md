# docker-nginx-practice

Docker üzerinde Nginx container ayağa kaldırma, port yönlendirmesi ve HTTP test adımları.

---

## Kullanılan Komutlar

```bash
docker run -d --name nginx-test --platform linux/amd64 -p 8080:80 nginx
docker ps
curl -I http://localhost:8080
docker stop nginx-test
docker rm nginx-test
