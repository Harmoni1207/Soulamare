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
npm run start     # Run live server and scss
npm start         # --||--
```
### Colors:
![](static/img/pallete.png)
```scss
$color-main-1: #fdfbf7;
$color-main-2: #fff0f8;
$color-main-3: #ffc2e9;
$color-main-4: #cca2e1;
$color-main-5: #543e5c;
```
![](static/img/tpallete.png)
```scss
$color-grey-1: #adb5bd;
$color-grey-2: #868e96;
$color-grey-3: #495057;
$color-grey-4: #343a40;
$color-grey-5: #212529;
```
###### [Links]():
+ ######
