# rtl_sdr

> RTL-SDR 接收器的原始数据记录工具。
> 使用 I/Q 采样（又称正交采样）编码数据。
> 更多信息：<https://osmocom.org/projects/rtl-sdr/wiki/Rtl-sdr>。

- 从指定频率（以 Hz 为单位）保存 RAW 数据到文件：

`rtl_sdr -f {{100000000}} {{path/to/file}}`

- 将数据管道传输到另一个程序：

`rtl_sdr -f {{100000000}} - | {{aplay}}`

- 读取指定数量的样本：

`rtl_sdr -f {{100000000}} -n {{20}} -`

- 指定采样率（范围：225001-300000 和 900001-3200000）：

`rtl_sdr -f {{100000000}} -s {{2400000}} -`

- 通过索引指定设备：

`rtl_sdr -f {{100000000}} -d {{0}} -`

- 指定增益：

`rtl_sdr -f {{100000000}} -g {{20}} -`

- 指定输出块大小：

`rtl_sdr -f {{100000000}} -b {{9999999}} -`

- 使用同步输出：

`rtl_sdr -f {{100000000}} -S -`
