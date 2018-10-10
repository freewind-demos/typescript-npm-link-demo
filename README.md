TypeScript Npm Link Demo
========================

TypeScript项目的npm link跟js的基本一样：

```
cd typescript-hello
npm link
```

```
cd testing-project
npm link typescript-npm-link-demo-typescript-hello
```

然后在testing-project中，就可以使用了。如果Webstorm提示找不到类型定义，可以刷新左侧项目文件树。

运行：

```
cd testing-project
npm install
npm link typescript-npm-link-demo-typescript-hello
npm run demo
```
