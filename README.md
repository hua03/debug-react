# React18 源码调试

[中文](./README.md) | [English](./README.en.md)

这是一个React18的基准调试环境，fork项目后使用主分支就可以开始调试React。

## 注意事项

### 使用稳定React分支

如果想自己从0搭建调试环境，下载react仓库的稳定分支。主分支由于开发人员经常在提交代码，代码不稳定，搭建过程如果遇到问题很难排查。

```shell
git clone git@github.com:facebook/react.git --depth 1 --branch v18.2.0
```

### 关掉各种lint检查（可选）

React由于使用Flow语法，VSCode 和 WebStorm 如果不配置相应的解析器，会报各种错误，建议在调试React的源码的时候关闭编辑器的lint检查。
