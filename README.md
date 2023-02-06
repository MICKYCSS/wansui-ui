# wansui-ui
# 初始化项目
## 代码规范
 ```
 npm i @umijs/fabric --dev
 npm i prettier --dev // 因为@umijs/fabric没有将prettier作为依赖 所以我们需要手动安装
 npm i husky lint-staged --dev
 ```
## commit message检测
```
npm i @commitlint/cli @commitlint/config-conventional commitizen cz-conventional-changelog --dev
```

## TypeScript
```
npm i typescript --dev
```
新建tsconfg.json

## 测试
新建alert文件夹测试
```
npm i react react-dom @types/react @types/react-dom --dev
npm i prop-types
```

# 开发与调试
## docz预览
```
npm i docz --dev
npm i rimraf --dev //清空目录的一个辅助库
npm i less gatsby-plugin-less --dev
```

# 组件库打包
## 导出类型文件声明
```
build:types: tsc -p tsconfig.build.json && cpr lib esm,
```

## 导出 Commonjs 模块
安装babel
```
npm i @babel/core @babel/preset-env @babel/preset-react @babel/preset-typescript @babel/plugin-proposal-class-properties  @babel/plugin-transform-runtime --dev
npm i @babel/runtime-corejs3
```

参考链接:https://segmentfault.com/a/1190000022650381