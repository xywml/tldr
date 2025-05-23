# git am

> 应用补丁文件并创建提交。在通过电子邮件接收提交时非常有用。
> 可参考 `git format-patch`，该命令可以生成补丁文件。
> 更多信息：<https://git-scm.com/docs/git-am>.

- 应用并提交本地补丁文件的更改：

`git am {{path/to/file.patch}}`

- 应用并提交远程补丁文件的更改：

`curl {{[-L|--location]}} {{https://example.com/file.patch}} | git apply`

- 中止应用补丁文件的过程：

`git am --abort`

- 尽可能多地应用补丁文件，将失败的部分保存到拒绝文件中：

`git am --reject {{path/to/file.patch}}`
