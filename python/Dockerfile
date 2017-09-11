FROM python:3.6

MAINTAINER dockerzsm zhangshimiande@gmail.com

# 安装PIL
RUN pip install Pillow \
    && pip install pymysql \
    && pip install Scrapy \
    && apt-get update \
    && apt-get install tesseract-ocr |
    && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime