# df

> 显示文件系统磁盘空间使用情况的概览。
> 更多信息：<https://man.openbsd.org/df.1>.

- 使用 512 字节单位显示所有文件系统的磁盘使用情况：

`df`

- 以人类可读的形式（基于 1024 的幂）显示所有文件系统的磁盘使用情况：

`df -h`

- 显示包含给定文件或目录的文件系统及其磁盘使用情况：

`df {{path/to/file_or_directory}}`

- 包括已用和可用[inode]数量的统计信息：

`df -i`

- 使用 1024 字节单位显示空间数字：

`df -k`

- 以可移植的方式显示信息：

`df -P`
