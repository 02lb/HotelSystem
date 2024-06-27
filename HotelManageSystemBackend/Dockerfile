# 使用官方Python基础镜像
FROM python:3.8-slim

# 设置工作目录
WORKDIR /app

# 复制后端项目文件
COPY . .

# 安装依赖
RUN pip install --no-cache-dir -r requirements.txt

# 暴露Django默认端口
EXPOSE 8000

# 运行Django服务器
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
