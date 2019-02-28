# vue-ts-cli3

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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### start different module
在package.json里进行设置： "alpha": "vue-cli-service build --mode alpha"
打包，会把process.env.NODE_ENV设置为步骤中‘.env.alpha’文件设置的值。
注意，这里 “--mode 名字“ 要和根目录下文件名“.env.名字”名字保持一致
