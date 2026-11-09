# 每日一练

给孩子用的两张 A4 练习纸，纯前端单页，浏览器打开即可调参数、打印或存 PDF。所有处理都在本地完成，不上传任何数据。

- **乘法竖式练习纸** → https://ricky2036.github.io/daily-practice/mul-worksheet/
- **书法字帖** → https://ricky2036.github.io/daily-practice/calligraphy/

## 乘法竖式练习纸

两位数 / 三位数乘法竖式。每页题数（9/12/16/20）、题型、页数可调，方格按区域尺寸反推保证整格不出现半格，可附加答案页。

## 书法字帖

- 册次：统编版（部编版）1–6 年级上下册写字表，共 12 册 2488 个去重字；也可自定义文字
- 每字带**拼音**（pinyin-pro）与**逐笔笔顺**（Make Me a Hanzi 笔画路径，逐笔累积展示）
- 格子：田字格 / 米字格 / 九宫格 / 回宫格 / 方格
- 行结构：范字 + 描红 N 格（实心或空心，透明度可调）+ 空格
- 每行格数 6/8/10/12，每页行数 6–12，每字行数 1–3

## 目录

```
index.html                 入口页
mul-worksheet/index.html   乘法竖式
calligraphy/index.html     书法字帖
calligraphy/data/          生字表、笔顺笔画（按需加载）
calligraphy/vendor/        pinyin-pro
```

## 数据来源

生字表取自统编版（部编版）小学语文写字表；笔顺笔画数据来自 [Make Me a Hanzi](https://github.com/skishore/makemeahanzi)（hanzi-writer-data）；拼音由 [pinyin-pro](https://github.com/zh-lx/pinyin-pro) 生成，多音字按教材读音做了少量修正。
