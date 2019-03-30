eslint-config-mofengkeji
===========================


墨锋科技前端组ESLint共享配置规则

## 安装

```
$ npm install --save-dev eslint eslint-plugin-vue eslint-config-mofengkeji
```


## 使用
通过在项目根目录下添加 [.eslintrc.js]((http://eslint.org/docs/user-guide/configuring)) 中的字段extends中使用它

```js
{
  "extends": ["mofengkeji"],
  "rules": {
    // Additional, per-project rules...
  }
}
```

记得同时添加 .eslintconfig
```
build/*.js
config/*.js
src/assets
test/**/*.js
```


## 如何贡献

1. 从目前已经存在的issue或者提出一个新的issue去讨论新的特性或者存在的bug.
2. 在Github上Fork [仓库](https://github.com/mofengkeji/eslint-config-mofengkeji)，然后在master或者其它分支上开始进行您的修改.
3. 编写测试用力表明某个bug被修复掉了或者新的特性可以正常工作.
4. 提交PR直到它被merge或者发布出去了. :) 记得把您添加进 [AUTHORS](AUTHORS).

## 版本日志

[版本日志](CHANGELOG.md)

## 许可证

Apache-2 © mofengkeji