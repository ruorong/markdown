# markdown读书笔记
>学习markdown的一些语法

## 🌑 标题
```
# 一级标题
## 二级标题
### 三级标题

以此推类，注意在 # 后面加上一个字符的空格
```
![image](https://github.com/ruorong/markdown/raw/master/image/title.jpg)

## 🌒 列表
>列表分为有序和无序两种， 符号要和文字之间加上一个字符的空格
- 有序列表  
在文字前加`1.  2.  3.`
- 无序列表  
需要在文字前加上` -` 或 `*`   
![list](https://github.com/ruorong/markdown/raw/master/image/list.jpg)


## 🌓 引用
如果你需要引用别处的一段话，只需要在文字前使用引用符号 `> `
![quote](https://github.com/ruorong/markdown/raw/master/image/quote.jpg)

## 🌔 粗体、斜体、删除线
- 粗体  
用两个 `* `包含一段文本
- 斜体  
用一个 `*` 包含一段文本
- 删除线  
用两个 `~ `包含一段文本

![effect](https://github.com/ruorong/markdown/raw/master/image/effect.jpg)

## 🌕 插入图片、链接、URL
🚩插入图片  
- 第一种表示方法  
图片为： `！[]()`  
链接为：`[]()`
>插入图片和链接很像，区别在有没有 **！**，并且这里的 **！**是**英文模式下**的  

- 第二种表示方法  
图片为：`![love][id] `   
`[id]：www.xxxx.com  `  
链接为：`[…][…] `   
`[…]:`

🚩 插入URL  
要将URL或电子邮件地址快速转换为链接，请将其用尖括号<>括起来。  
`<https://github.com> `  
`<xxxxx@xxx.com>`
## 🌖 代码
 - 行内代码  
 只需要用两个` ` ` 把中间的代码包裹起来  
 ![code](https://github.com/ruorong/markdown/raw/master/image/code.jpg)

 - 代码块  
 代码块通过两行` ``` ` 符号框出，如果你写的代码是某种语言，那么可以在第一行末尾加上这个语言的名字，代码块内的代码就会执行对应的高亮语法，例如Java
 ## 🌗 分割线
 分割线的语法只需要三个` * `符号，效果如下
 ***
 ## 🌘 语言的对齐
 每行末加两个字符的空格，在预览中就能换行了  
  ![alignment](https://github.com/ruorong/markdown/raw/master/image/code.jpg)
## 🌝 表格
```
| Things        | Quantity      | Cost  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```
其中
- 文字默认偏右
- 符号 `-` 有一个就行
- 两边加  `：`表示文字居中
- 右边加  `：`表示文字偏右 
## 🌙 快速索引
如果你觉得看完一遍还不够的话👉[`try it`](#markdown读书笔记)