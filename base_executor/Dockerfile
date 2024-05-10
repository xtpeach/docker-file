FROM openjdk:8-jdk

# 安装 Python 3 和相关依赖
RUN apt-get update && apt-get install -y python3 python3-pip

# 安装 FFmpeg
RUN apt-get install -y ffmpeg

# 安装You-Get
RUN pip install you-get

# 替换You-Get中的bilibili.py文件
COPY bilibili.py /usr/local/lib/python3.9/dist-packages/you_get/extractors/bilibili.py