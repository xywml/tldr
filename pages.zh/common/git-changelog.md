# git changelog

> 从仓库的提交记录和标签生成变更日志报告。
> 属于 `git-extras` 的一部分。
> 更多信息：<https://github.com/tj/git-extras/blob/master/Commands.md#git-changelog>.

- 更新现有文件或创建一个包含自最新 Git 标签以来的提交消息的新 `History.md` 文件：

`git changelog`

- 列出当前版本的提交记录：

`git changelog --list`

- 列出从名为 `2.1.0` 的标签到现在的提交记录范围：

`git changelog --list --start-tag {{2.1.0}}`

- 列出标签 `0.5.0` 和标签 `1.0.0` 之间的漂亮格式化的提交记录范围：

`git changelog --start-tag {{0.5.0}} --final-tag {{1.0.0}}`

- 列出提交 `0b97430` 和标签 `1.0.0` 之间的漂亮格式化的提交记录范围：

`git changelog --start-commit {{0b97430}} --final-tag {{1.0.0}}`

- 指定 `CHANGELOG.md` 作为输出文件：

`git changelog {{CHANGELOG.md}}`

- 完全替换当前变更日志文件的内容：

`git changelog --prune-old`
