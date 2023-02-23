# Contribute Guidelines

## 文件结构

每篇教程放在以其 *英文标题* (空格使用 - 替换) 命名的文件夹下，配图在其文件夹下新建名为 pics 的子文件夹。
e.g.

```sh
src
├── Guides
│   ├── Sample-Guide1
│   │   ├── pics
│   │   │   └── A.png
│   │   └── Sample-Guide1.md
│   │
│   └── Sample-Guide2
│       ├── pics
│       │   └── B.png
│       └── Sample-Guide2.md
│   
├── pics
│
…
```


## MD格式

### Headline使用

Headline1 即 `# Sample` 仅用与指南的标题。

其余依据章节划分自行判断，对于应在同位次的子章节烦请使用相同的 *Headline*。

### 换行

- 每个 *Headline* 下换行一次，在下一个 *Headline* 前换行两次。
- 章节间请添加一次换行。
- 代码框前后添加换行。


### 代码框

需要执行的指令等使用代码框并加注 `shell` 表示：

\`\`\`shell
guide -sample
\`\`\`

参数、组合键等内容使用代码片段 \`sample\`。


### 文本格式（WIP）
<!--TODO
粗体
斜体
删除线
……
-->

## MathJax

*mdBook* 使用 [*MathJax*](https://www.mathjax.org/) 来渲染公式。

由于官方限制不能直接使用 *MathJax* 通常所用的分隔符。详情请参阅[ *mdBook* 官方文档 MathJax Support](https://rust-lang.github.io/mdBook/format/mathjax.html) 。

以下给出在此项目中 *LaTeX* 用法。


### 内联公式

使用 `\\(` 与 `\\)` 作为分隔符框出公式。

```
样例文字 \\( \int x dx = \frac{x^2}{2} + C \\) 样例文字
```

渲染结果：

样例文字 \\( \int x dx = \frac{x^2}{2} + C \\) 样例文字


### 独立公式

使用 `\\[` 与 `\\]` 作为分隔符框出公式。

```
\\[ \mu = \frac{1}{N} \sum_{i=0} x_i \\]
```

渲染结果：

\\[ \mu = \frac{1}{N} \sum_{i=0} x_i \\]