# shares — 公开分享站

放**可以给别人看**的 HTML 成品。推送到这里后自动生成公网链接，直接发链接即可，无需部署服务器。

- 站点根：`https://wuyan1599-dot.github.io/shares/`
- 推送后约 1–2 分钟 Pages 自动构建生效
- 私密资料放 `my-assets` 私有仓库，不要放这里

## 链接规则（每个文件一个 URL）

GitHub Pages 把仓库里的文件路径原样映射成网址：

```
https://wuyan1599-dot.github.io/shares/<仓库内相对路径>
```

| 仓库内文件 | 对应公网链接 |
| --- | --- |
| 根目录 `index.html` | `https://wuyan1599-dot.github.io/shares/` |
| 根目录 `workbuddy-test.html` | `https://wuyan1599-dot.github.io/shares/workbuddy-test.html` |
| 子目录 `docs/intro.html` | `https://wuyan1599-dot.github.io/shares/docs/intro.html` |

> 文件名建议只用英文、数字、`-`、`_``。中文或特殊字符会被 URL 编码（如空格变 `%20`），链接不好读。

## 当前文件索引

| 文件 | 公网链接 | 说明 |
| --- | --- | --- |
| `workbuddy-test.html` | https://wuyan1599-dot.github.io/shares/workbuddy-test.html | WorkBuddy 链路测试页 |

> 新增文件后请把对应链接补进这张表，方便自己和别人直接查。

## 怎么分享

1. 把 HTML（及配套 `assets/` 目录）放进本目录或子目录
2. 推送：`cd D:\工作\my-assets-share && git add -A && git commit -m "新增 xxx" && git push`
3. 取链接：按上面的规则拼，或看本页索引表

最后更新：2026-09-09
