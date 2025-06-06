# neato

> 从 `graphviz` 文件中渲染 `线性无向` 网络图的图像。
> 布局方式：`dot`, `neato`, `twopi`, `circo`, `fdp`, `sfdp`, `osage` 和 `patchwork`。
> 更多信息：<https://graphviz.org/doc/info/command.html>.

- 根据输入文件名和输出格式（大写 -O）渲染 PNG 图像：

`neato -T {{png}} -O {{path/to/input.gv}}`

- 使用指定的输出文件名（小写 -o）渲染 SVG 图像：

`neato -T {{svg}} -o {{path/to/image.svg}} {{path/to/input.gv}}`

- 以 PS、PDF、SVG、Fig、PNG、GIF、JPEG、JSON 或 DOT 格式渲染输出：

`neato -T {{format}} -O {{path/to/input.gv}}`

- 使用 `stdin` 和 `stdout` 渲染 GIF 图像：

`echo "{{graph {this -- that} }}" | neato -T {{gif}} > {{path/to/image.gif}}`

- 显示帮助：

`neato -?`
