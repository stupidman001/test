# project

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

```bash

echo '开始构建项目'
echo 'node的版本'
node -v
npm -v

echo '下载依赖'
npm install
echo '开始打包'
npm run build
echo '打包完毕'
echo '文件目录显示'
ls

echo '打包后的文件复制到云服务器的对应文件夹中'
echo '清空文件夹'
rm -rf /root/test/*
echo '开始复制'
cp -rf ./dist/* /root/test/
echo '同步完毕'

```