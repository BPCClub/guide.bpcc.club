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

需要执行的指令等使用代码框并加注 *sh* 表示：

\`\`\`sh
guide -sample
\`\`\`

参数等内容使用代码片段 \`sample\`。


### 文本格式（WIP）
<!--TODO
粗体
斜体
删除线
……
-->