FROM python:3.8-alpine

LABEL maintainer="mingshi cai <i@unoiou.com>"
LABEL description="python development envrionment"

RUN apk add gcc musl-dev libc-dev libffi-dev openssl-dev
RUN apk add vim tmux git fish
RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
RUN pip install poetry virtualenv

CMD ["fish"]

