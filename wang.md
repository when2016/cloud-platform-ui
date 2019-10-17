rm -rf node_modules
rm package-lock.json
npm cache clear --force
npm install


#开发（在UI目录下）
# 安装依赖
npm install

## 若上述不行则采取下面命令
npm install --registry=https://registry.npm.taobao.org

# 本地开发 开启服务
npm run dev