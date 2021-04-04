<h1 align="center">Hibernate Validator 中文文档</h1>

> Hibernate Validator v7.0.1 中文翻译

---

## 在线查看

[https://yuyang.run/translate/hibernate-validator/index.html](https://yuyang.run/translate/hibernate-validator/index.html)

## 文件夹

- **asciidoc** 翻译后的文本文件
- **code** 文件中引用的演示源码
- **output-html** 输出HTML文件引用的js/css/images等静态文件
- **themes** 输出PDF所需中文字体及样式文件

## 环境

- Ruby

## 依赖安装

```sh
bundle install
```

## 编译

### HTML格式

```sh
asciidoctor asciidoc/index.asciidoc -o output-html/index.html
```

> 该过程会报**WARNING**，可以忽略


### PDF格式

```sh
asciidoctor-pdf -a pdf-style=./themes/theme.yml -a pdf-fontsdir=./themes/fonts asciidoc/index.asciidoc
```

