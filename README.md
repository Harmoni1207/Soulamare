![](frontend/static/img/favicon_32.png) Soulamare
=========
### It depends on everyone ...


**Note:** 
Soulamare is a website dedicated to helping lost souls get better:
Family life, friendships, spiritual side ...
We are also open to learning from you ... 

### Run:
```bash
git clone https://github.com/Martin1403/Soulamare.git && \
cd Soulamare && \
docker-compose up --build && \
docker-compose down && \
docker rmi $(docker images --format="{{.ID}}" soulamare_*) --force && \
docker volume prune
```
###### Ctrl+C to exit.

**Note:** In development ...