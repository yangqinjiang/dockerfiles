FROM python:2.7
LABEL maintainer="Yangqinjiang<yangqinjiang@gmail.com>"
RUN pip install flask
COPY app.py /app/ # 注意目录 ,要带 /
WORKDIR /app
EXPOSE 5000
CMD ["python","app.py"]
