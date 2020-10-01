# run the code
```
python3 main.py
```
* 改用 python 3
# 如何產生 requirements.txt
```
pip3 install pandas requests
pip3 freeze > requirements.txt
```
# 如何使用 requirements.txt
```
pip3 install -r requirements.txt
```
# code original from (Python Taiwan (Telegram) project)

https://repl.it/@EmmaLi3/Emma#main.py


# dockerize
```
docker run -it --rm --name my-first-python-script -v "$PWD":/tmp python:3 python /tmp/main.py
```

# steps

## build
```
docker build -t python-app:v1 .
(-t is the tag and name in format of "name:tag")
```

## run
```
docker run -it --name my_app python-app:v1
(--name the-name-of-container, -t 在容器中建立了一個終端機，-i 建立與容器標準輸入（STDIN）的互動連結)
```
