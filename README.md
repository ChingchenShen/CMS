# v3cms 功能介绍

## 配置功能
### 已完成：
1. npm run prettier 可以美化代码
2. npx cz 格式化 git 提交信息
3. 使用 husky 在 git commit 时，会进行 eslint 检测（但我不想要这个功能，eslint 目前使用太占用我的时间，所以目前做了改变执行 husky 执行的是 npm run prettier）
### 计划完成：
1. 在代码commit之前，eslint的检测功能应当开启；
2. 在代码commit时， commit的简短信息即message检测功能应当开启；










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
