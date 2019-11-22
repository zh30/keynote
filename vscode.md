# VS Code 基础

`张赫`

---

# 「快捷键」

---

## 启动 vscode
`code . or path`

---

## 设置 vscode
`cmd + ,`
```json
{
  editor.fontSize: 14,
  editor.fontFamily: 'Fira Code',
  editor.tabSize: 2,
}
```

[![FiraCode](./images/firacode.png)](https://github.com/tonsky/FiraCode)

---

## 显示命令行面板
`shift + cmd + p or F1`

---

## 快速打开，进入文件
`cmd + p or control + tab`

---

## 移动一行
`option + up/down`

---

## 复制一行
`shift + option + up/down`

---

## 批量替换
`cmd + F2`

---

## 跳转到定义
`cmd + Click`

---

## 多行编辑
`option(shift) + Click`

---

## 关闭当前窗口
`cmd + w`

---

## 删除一行
`cmd + shift + k`

---

## 插入一空行
`cmd(shift) + enter`

---

## 搜索
`cmd(shift) + f`

---

## Tasks 应用
`shift + cmd + p => task `

---

# 用户代码片段

---

## 自定义属于自己的代码片段
### User Snippets

`Code > Preferences > User Snippets`

---

eg:
```json
"Array map return": {
  "prefix": [
    "mapr",
    "arrayMapReturn"
  ],
  "body": [
    "const ${1:name} = ${2:array}.map(${3:element} => {",
    "\t${4}",
    "\t",
    "\treturn ${5:element}",
    "})"
  ],
  "description": "map()方法创建一个新数组，其结果是该数组中的每个元素都调用一个提供的函数后返回的结果。"
}
```

---

> MagicCode extension
[![scan me](./images/url.png)](https://github.com/hertzZhang/magiccode)

---

# 题外工具篇

---

## MAC 窗口整理工具 

---

## [spectacleapp](https://www.spectacleapp.com/)

---

## 快捷键助手

---

## [CheatSheet](https://www.macupdate.com/app/mac/43222/cheatsheet)

---

## 适合程序员写PPT的工具

---

## [reveal-md](https://github.com/webpro/reveal-md)
```bash
yarn global add reveal-md
reveal-md ***.md
reveal-md ***.md --print ***.pdf
```

---

### 本次ppt源码都在我的 [GitHub](https://zhanghe.org/powerpoint/) 里
>  大家共同进步提升

---

# 谢谢🙏