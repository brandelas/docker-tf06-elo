# Docker TF06

## 📌 Descrição
Projeto utilizando Docker Compose para orquestrar um servidor Nginx e um cache Redis.

---

## 🚀 Subindo o ambiente

```bash
docker-compose up -d



[+] Running 2/2
 ✔ Container lab_compose_tf06-cache-1  Running                                                               0.0s 
 ✔ Container lab_compose_tf06-web-1    Running                                                               0.0s 
PS C:\Users\Administrador\lab_compose_tf06> 

    PORTS
lab_compose_tf06-cache-1   redis:alpine           "docker-entrypoint.s…"   cache     41 minutes ago   Up 41 minutes   6379/tcp
lab_compose_tf06-web-1     lab_compose_tf06-web   "/docker-entrypoint.…"   web       41 minutes ago   Up 41 minutes   0.0.0.0:8080->80/tcp, [::]:8080->80/tcp


ping cache
PING cache (172.20.0.2): 56 data bytes
64 bytes from 172.20.0.2: seq=0 ttl=64 time=1.383 ms
64 bytes from 172.20.0.2: seq=1 ttl=64 time=0.242 ms
64 bytes from 172.20.0.2: seq=2 ttl=64 time=0.182 ms
64 bytes from 172.20.0.2: seq=3 ttl=64 time=0.220 ms
64 bytes from 172.20.0.2: seq=4 ttl=64 time=0.268 ms
64 bytes from 172.20.0.2: seq=5 ttl=64 time=0.278 ms
64 bytes from 172.20.0.2: seq=6 ttl=64 time=0.147 ms
64 bytes from 172.20.0.2: seq=7 ttl=64 time=0.146 ms
64 bytes from 172.20.0.2: seq=8 ttl=64 time=0.232 ms
64 bytes from 172.20.0.2: seq=9 ttl=64 time=0.157 ms
64 bytes from 172.20.0.2: seq=10 ttl=64 time=0.237 ms
64 bytes from 172.20.0.2: seq=11 ttl=64 time=0.223 ms
64 bytes from 172.20.0.2: seq=12 ttl=64 time=0.091 ms
64 bytes from 172.20.0.2: seq=13 ttl=64 time=0.099 ms
64 bytes from 172.20.0.2: seq=14 ttl=64 time=0.108 ms
64 bytes from 172.20.0.2: seq=15 ttl=64 time=0.088 ms
64 bytes from 172.20.0.2: seq=16 ttl=64 time=0.149 ms
64 bytes from 172.20.0.2: seq=17 ttl=64 time=0.171 ms
64 bytes from 172.20.0.2: seq=18 ttl=64 time=0.321 ms
64 bytes from 172.20.0.2: seq=19 ttl=64 time=0.088 ms
64 bytes from 172.20.0.2: seq=20 ttl=64 time=0.108 ms
64 bytes from 172.20.0.2: seq=21 ttl=64 time=0.144 ms
64 bytes from 172.20.0.2: seq=22 ttl=64 time=0.147 ms
64 bytes from 172.20.0.2: seq=23 ttl=64 time=0.084 ms
64 bytes from 172.20.0.2: seq=24 ttl=64 time=0.133 ms
64 bytes from 172.20.0.2: seq=25 ttl=64 time=0.092 ms
64 bytes from 172.20.0.2: seq=26 ttl=64 time=0.167 ms
64 bytes from 172.20.0.2: seq=27 ttl=64 time=0.117 ms
64 bytes from 172.20.0.2: seq=28 ttl=64 time=0.100 ms
64 bytes from 172.20.0.2: seq=29 ttl=64 time=0.085 ms
64 bytes from 172.20.0.2: seq=30 ttl=64 time=0.111 ms
64 bytes from 172.20.0.2: seq=31 ttl=64 time=0.087 ms
64 bytes from 172.20.0.2: seq=32 ttl=64 time=0.250 ms
64 bytes from 172.20.0.2: seq=33 ttl=64 time=0.085 ms
64 bytes from 172.20.0.2: seq=34 ttl=64 time=0.111 ms
64 bytes from 172.20.0.2: seq=35 ttl=64 time=0.091 ms
64 bytes from 172.20.0.2: seq=36 ttl=64 time=0.086 ms
64 bytes from 172.20.0.2: seq=37 ttl=64 time=0.089 ms
64 bytes from 172.20.0.2: seq=38 ttl=64 time=0.138 ms
64 bytes from 172.20.0.2: seq=39 ttl=64 time=0.200 ms
64 bytes from 172.20.0.2: seq=40 ttl=64 time=0.209 ms
64 bytes from 172.20.0.2: seq=41 ttl=64 time=0.151 ms
64 bytes from 172.20.0.2: seq=42 ttl=64 time=0.251 ms
64 bytes from 172.20.0.2: seq=43 ttl=64 time=0.139 ms
64 bytes from 172.20.0.2: seq=44 ttl=64 time=0.153 ms