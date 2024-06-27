# 使用官方Node.js基础镜像
FROM node:14

# 设置工作目录
WORKDIR /app

# 复制前端项目文件
COPY . .

# 安装前端依赖
RUN npm install

# 暴露前端开发服务器端口
EXPOSE 8080

# 运行前端开发服务器
CMD ["npm", "run", "dev"]
