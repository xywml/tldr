# atq

> 显示由 `at` 或 `batch` 命令调度的任务。
> 更多信息：<https://manned.org/atq>。

- 显示当前用户的调度任务：

`atq`

- 显示来自 'a' [队列]（队列名称为单个字符）的任务：

`atq -q {{a}}`

- 显示所有用户的任务（以超级用户身份运行）：

`sudo atq`
