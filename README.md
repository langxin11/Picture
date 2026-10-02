# Picture

本仓库是个人博客 [langxin11.github.io](https://langxin11.github.io) 的**图片托管仓库（图床）**，不含可执行代码。

博客文章通过 `raw.githubusercontent.com` 直接外链本仓库文件，例如：

```
https://raw.githubusercontent.com/langxin11/Picture/main/blog/砖块掉落仿真.gif
```

## 目录说明

| 目录 | 用途 |
|---|---|
| `blog/` | 博客文章用图，被 `langxin11.github.io/src/content/posts/*.md` 外链引用（当前 4 篇文章引用 40 个文件） |
| `test/` | 早期上传测试，未被任何文章引用 |

## ⚠️ 维护约定

- **不要移动或重命名 `blog/` 下的文件。** 博客文章按固定路径外链，改名会使线上图片立刻 404。
- 新增图片请放入 `blog/`，并沿用现有命名习惯（Typora 导出的 `image-<时间戳>.png` 等）。
- 如需清理，先确认文件没有被 `langxin11.github.io` 仓库中的文章引用。