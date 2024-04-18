# gotips Go语言编程技巧
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Go tips from [Phuong Le](https://twitter.com/func25). 

翻译后的站点: [Go语言编程技巧](https://colobu.com/gotips/) (自动生成)

## 翻译规范

1. 创建一个认领issue,认领标题中注明tip号和标题。不允许一人同时认领多个任务。翻译完一项任务后才能认领下一个任务。
2. 任务请搜索 Phuong Le 的Twitter账号，找到对应的tip，然后翻译成中文。(可能有的tip作者已经删除，经咨询，作者反馈内容会有增删，所以如果某个tip不存在，请空一个，寻找下一个tip)
3. fork 本项目，然后在 fork 后的项目中进行翻译认领的一个tip,翻译完成后提交pull request
4. 任务请在一周内完成，未完成的任务将被释放，其他人可以认领。

- 项目自动统计贡献者
- 翻译请保持语句通顺，可以使用AI协助翻译，但是一定要避免生硬和机翻的感觉

> **怎么提交Pull Request? **
> 
> 如果大家以前没有提交过 Pull Request,可以探索下。
> 首先点击项目右上角的 Fork 按钮，将项目 Fork 到自己的仓库。
> 在github浏览你fork的项目，你会看到一个 "Create pull request" 按钮，点击它
> 填写相关的内容提交即可。
> 后续等待项目的维护者合并你的PR即可。


## 翻译模板

```markdown
# Tip #76 函数调用的结果回传

>  原始链接：[Golang Tip #76: Result forwarding in function call](https://twitter.com/func25/status/1779128931586850890)
>

当我刚开始使用go语言的时候，我发现有一个概念比较棘手：函数调用结果的回传。

....
```

- 在src下创建翻译文件: `xxx.md`, 内容模板如上
- 图片放入 `src/images` 文件夹中
- 在 `src/SUMMARY.md` 文件中加入你翻译的一项
- 在 `README` 文件中**翻译任务认领表格** 填写你翻译的项目

## 翻译任务认领表格

| tip序号 | 标题 | 译者        | 状态 |
| --- | --- |-----------| --- |
| 1 | Measure the execution time of a function in just one line of code. | smallnest |
| 2 | Multistage defer | smallnest |
| 3 | Pre-allocate slices for performance | smallnest |
| 4 | Parse an Array into a Slice | smallnest | 
| 5 |  |           | 
| 6 | Underscore Import | icyfire   | 
| 7 |  |           | 
| 8 |  |           | 
| 9 | Compile-Time Interface Verification | icyfire   | 
| 10 |  |           | 
| 11 |  |           | 
| 12 |  |           | 
| 13 |  |           | 
| 14 |  |           | 
| 15 |  |           | 
| 16 |  |           | 
| 17 |  |           | 
| 18 |  |           | 
| 19 |  |           | 
| 20 |  |           | 
| 21 |  |           | 
| 22 |  |           | 
| 23 |  |           | 
| 24 |  |           | 
| 25 |  |           | 
| 26 |  |           | 
| 27 |  |           | 
| 28 |  |           | 
| 29 |  |           | 
| 30 |  |           | 
| 31 |  |           | 
| 32 |  |           | 
| 33 |  |           | 
| 34 |  |           | 
| 35 |  |           | 
| 36 |  |           | 
| 37 |  |           | 
| 38 |  |           | 
| 39 |  |           | 
| 40 |  |           | 
| 41 |  |           | 
| 42 |  |           | 
| 43 |  |           | 
| 44 |  |           | 
| 45 |  |           | 
| 46 |  |           | 
| 47 |  |           | 
| 48 |  |           | 
| 49 |  |           | 
| 50 |  |           | 
| 51 |  |           | 
| 52 |  |           | 
| 53 |  |           | 
| 54 |  |           | 
| 55 |  |           | 
| 56 |  |           | 
| 57 |  |           | 
| 58 |  |           | 
| 59 |  |           | 
| 60 |  |           | 
| 61 |  |           | 
| 62 |  |           | 
| 63 |  |           | 
| 64 |  |           | 
| 65 |  |           | 
| 66 |  |           | 
| 67 |  |           | 
| 68 |  |           | 
| 69 |  |           | 
| 70 |  |           | 
| 71 |  |           | 
| 72 |  |           | 
| 73 |  |           | 
| 74 |  |           | 
| 75 |  |           | 
| 76 |  Result forwarding in function calls | syjs10    | 
| 77 |  Buffered channels as semaphores to limit goroutine execution | QingyaFan | 
| 78 | Non-blocking channel send trick | hxzhouh   |
| 79 |  |           | 
| 80 |  |           | 
| 81 |  |           | 
| 82 |  |           | 
| 83 |  |           | 
| 84 |  |           | 
| 85 |  |           | 
| 86 |  |           | 
| 87 |  |           | 
| 88 |  |           | 
| 89 |  |           | 
| 90 |  |           | 
| 91 |  |           | 
| 92 |  |           | 
| 93 |  |           | 
| 94 |  |           | 
| 95 |  |           | 
| 96 |  |           | 
| 97 |  |           | 
| 98 |  |           | 
| 99 |  |           | 
| 100 |  |           | 

## 生成文档

安装`mdbook`和`mdbook-pdf`工具。

### 本地预览
在本地`mdbook serve`可以生成本地网站访问。

http://localhost:3000

### 生成静态网站
`mdbook build` 生成网站到`book`目录下。





## 贡献者 ✨

感谢贡献者 ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://colobu.com/"><img src="https://avatars.githubusercontent.com/u/865763?v=4?s=100" width="100px;" alt="smallnest"/><br /><sub><b>smallnest</b></sub></a><br /><a href="https://github.com/smallnest/gotips/commits?author=smallnest" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/hxzhouh"><img src="https://avatars.githubusercontent.com/u/25883521?v=4?s=100" width="100px;" alt="hxzhouh"/><br /><sub><b>hxzhouh</b></sub></a><br /><a href="https://github.com/smallnest/gotips/commits?author=hxzhouh" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/icyfire"><img src="https://avatars.githubusercontent.com/u/1171180?v=4?s=100" width="100px;" alt="icyfire"/><br /><sub><b>icyfire</b></sub></a><br /><a href="https://github.com/smallnest/gotips/commits?author=icyfire" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/syjs10"><img src="https://avatars.githubusercontent.com/u/15065304?v=4?s=100" width="100px;" alt="JS"/><br /><sub><b>JS</b></sub></a><br /><a href="https://github.com/smallnest/gotips/commits?author=syjs10" title="Code">💻</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

