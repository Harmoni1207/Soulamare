Frontend
========
**Note:** Soulamare frontend

![](image.png)

### Venv: 
###### python3.9
```
python -m venv .venv && \
source .venv/bin/activate && \
pip install -U pip && \
pip install -r requirements.txt
```
### Run:
```
source .venv/bin/activate && \
export QUART_APP=app:app && \
export QUART_ENV=development && \
quart run -h "127.0.0.1" -p 5000
```
### Docker:
```
docker build -t app . && \
docker run -it --rm -p 5000:5000 app && \
docker rmi app --force
```
### Dev:
```
npm run compile:sass
```
### Colors:
![](static/img/pallete.png)
```pallete
#fdfbf7
#fff0f8
#ffc2e9
#cca2e1
#543e5c
```
![](static/img/tpallete.png)
```text
#adb5bd
#868e96
#495057
#343a40
#212529
```
###### [Links]():
+ ######
