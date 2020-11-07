FROM python:3.8-slim-buster

LABEL maintainer="mingshi cai <i@unoiou.com>"
LABEL description="python development envrionment"

RUN apt update && apt install vim tmux git fish -y
RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
RUN pip install poetry virtualenv 

CMD ["fish"]

