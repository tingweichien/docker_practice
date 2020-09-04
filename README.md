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
```
wget https://gist.githubusercontent.com/lxz1980/e3a31c66aeac349d5fe8d3ce5f4d0efa/raw/e522fbfcc82f4fe04edbf2f3a04a048df8553de4/project1_pb.txt
mv project1_pb.txt main.py
```

# dockerize
```
docker run -it --rm --name my-first-python-script -v "$PWD":/tmp python:3 python /tmp/main.py
```
