# sph

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

mock:使用步骤
1.在项目中src文件夹中创建mock文件夹
2.第二步准备json数据（mock文件夹中准备相应的json文件）---- 格式化一下，不能有空格，会跑步起来
3.把mock数据需要的图片放置到public文件夹中（public文件夹在打包的时候，会把相应的资源原封不动打包到dist文件夹
4.mockServe.js文件在入口文件夹中引入（至少需要执行一次，才能模拟数据）