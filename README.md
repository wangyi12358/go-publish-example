# Golang发布Module例子

## 如何发布Golang Module
1. 修改 `go.mod` 文件，添加 `module` 信息，例如：`module github.com/yourname/yourmodule`。
2. 使用 `git tag` 命令添加版本信息，例如：`git tag v0.0.1`。
3. 使用 `git push --tags` 命令将版本信息推送到远程仓库。

## 安装Golang Module
1. 使用 `go get` 命令安装指定版本的Module，例如：`go get github.com/yourname/yourmodule`，默认会拉取Tag最新的版本。