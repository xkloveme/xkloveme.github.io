# 我的博客

个人成长记录 [Hexo].

![](https://cdn.jsdelivr.net/gh/xkloveme/oss@master/images/1627479150168-1627479149928.png)

- [预览](http://www.jixiaokang.com/)
- [管理平台](https://hexo.jixiaokang.com/)

## 新建笔记

``` bash
bun new
```


## 关注我

- [github](http://www.github.com/xkloveme)

## 使用 Bun

如果你想用 `bun` 管理依赖并运行脚本：

1. 安装 Bun：参见 https://bun.sh
2. 在项目根目录运行：

```bash
bun install
```

这会生成 `bun.lockb`。随后可以使用与 `package.json` 中相同的脚本名称：

```bash
bun run dev    # 本地预览
bun run build  # 生成站点
```

如果你希望切换默认包管理器，可以删除 `pnpm-lock.yaml`，并在团队内通知其他协作者。