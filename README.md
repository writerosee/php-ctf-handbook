# PHP CTF Handbook

CTF Web 线下赛用的 PHP 速查手册，断网可用。

内容分三块：PHP 官方中文手册的全量索引、196 条 CTF 技巧（附 990 段 payload）、一个在本地跑的工具箱。赛前还能联网拉一次 CVE。

![主界面](docs/01-list.png)

## 快速开始

下载 `php-ctf-handbook.html`，双击。Windows、macOS、Linux 都一样，浏览器打开即可。

**Important**：Windows Defender 会把这个文件当可疑程序删掉——13 MB 的单页 HTML 里塞了大量 PHP 代码，容易触发启发式扫描。

## 仓库内容

```
php-ctf-handbook.html   成品，双击打开
README.md               这份说明
LICENSE                 MIT
docs/                   截图
```

## 搜索

`k:ctf` 按类型筛，`pl:base64` 只搜 payload，`-redis` 排除，`"精确短语"` 精确匹配。`Ctrl+K` 是命令面板，跳条目、切视图、导出都在里面。

![命令面板](docs/04-cmd.png)

## 技巧

196 条 CTF 技巧，覆盖文件包含与伪协议、反序列化、SSTI 与框架、各类过滤绕过、XXE/JWT/SSRF、后渗透。

![条目详情](docs/02-detail.png)

## 工具箱

序列化 payload 生成、反弹 Shell、JWT 拆解、哈希识别、编码器。

![工具箱](docs/03-toolbox.png)

## CVE

接了 OSV。赛前拉一遍最近的漏洞，本地打法库会给它补上中文的判断方法和利用思路。

## 本地修改

收藏、笔记、最近查看都有。条目也能在页面里直接改，改动存在浏览器本地；导出 JSON 可以备份，换机器时再导入。

## 说明

仅用于 CTF 竞赛与授权渗透测试。手册文本索引自 PHP 官方中文手册，版权归 PHP Documentation Group；其余内容与代码 MIT。
