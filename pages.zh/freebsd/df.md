# df

> 显示文件系统的磁盘空间使用情况概览。
> 更多信息：<https://man.freebsd.org/cgi/man.cgi?df>。

- 以 512 字节为单位显示所有文件系统的磁盘使用情况：

`df`

- 使用易读单位（基于 1024 的幂）并显示总计：

`df -h -c`

- 使用易读单位（基于 1000 的幂）：

`df -{{-si|H}}`

- 显示给定文件或目录所在文件系统的磁盘使用情况：

`df {{path/to/file_or_directory}}`

- 包括自由和已用 [i]节点的统计信息以及文件系统 [T]类型：

`df -iT`

- 以 1024 字节为单位显示空间数据：

`df -k`

- 以可移植的方式显示信息：

`df -P`
