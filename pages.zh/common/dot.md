# dot

> 从 `graphviz` 文件渲染一个 `线性有向` 网络图。
> 布局类型：`dot`，`neato`，`twopi`，`circo`，`fdp`，`sfdp`，`osage` 和 `patchwork`。
> 更多信息：<https://graphviz.org/doc/info/command.html>。

- 渲染 PNG 图像，输出文件名基于输入文件名和输出格式（大写 -O）：

`dot -T {{png}} -O {{path/to/input.gv}}`

- 渲染 SVG 图像，指定输出文件名（小写 -o）：

`dot -T {{svg}} -o {{path/to/image.svg}} {{path/to/input.gv}}`

- 以 PS、PDF、SVG、Fig、PNG、GIF、JPEG、JSON 或 DOT 格式渲染输出：

`dot -T {{format}} -O {{path/to/input.gv}}`

- 使用 `stdin` 和 `stdout` 渲染 GIF 图像：

`echo "{{digraph {this -> that} }}" | dot -T {{gif}} > {{path/to/image.gif}}`

- 显示帮助：

`dot -?`
