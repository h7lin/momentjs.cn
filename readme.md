
## 本地开发

```
npm run dev
```

## 异常问题 

项目依赖 node-sass，若是在 Windows 平台下，可能会因缺少 Visual C++ Build Tools 等其他依赖而编译失败，可以尝试淘宝已编译好的包：

```
npm install -g mirror-config-china --registry=http://registry.npm.taobao.org
npm install node-sass
```
