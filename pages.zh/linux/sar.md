# sar

> 监控各种 Linux 子系统的性能。
> 更多信息：<https://manned.org/sar>.

- 报告物理设备的 I/O 和传输速率，每秒一次（按 `<Ctrl c>` 退出）：

`sar -b {{1}}`

- 报告总共 10 次网络设备统计信息，每 2 秒一次：

`sar -n DEV {{2}} {{10}}`

- 报告 CPU 使用情况，每 2 秒一次：

`sar -u ALL {{2}}`

- 报告总共 20 次内存使用统计信息，每秒一次：

`sar -r ALL {{1}} {{20}}`

- 报告运行队列长度和负载平均值，每秒一次：

`sar -q {{1}}`

- 报告分页统计信息，每 5 秒一次：

`sar -B {{5}}`
