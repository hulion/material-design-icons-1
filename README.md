# 材料设计图标|Material design icons

材质设计图标是官方的|Material design icons are the official [icon set](http://www.google.com/design/spec/style/icons.html#icons-system-icons) 从谷歌设计的|from Google that are designed under the [material design guidelines](http://www.google.com/design/spec).

### 2.2 更新|Update

41 新增图标 |new icons!

检查出什么是新的|Check out what's new in the [material icons library](https://www.google.com/design/icons/).

## 开始|Getting Started

读|Read the [developer guide](http://google.github.io/material-design-icons/) 关于如何在项目中使用材质设计图标|on how to use the material design icons in your project.

### 使用字体集合|Using a font collection

在 `iconfont` 文件夹中包含可包含在项目中的预生成的字体文件。这是特别方便的网络，但是，它通常是更好地链接到网络字体托管在谷歌字体|
folder contains pre-generated font files that can be included in a project. This is especially convenient for the web; however, it is generally better to link to the web font hosted on Google Fonts:
已处理中国地区使用
```html'''  
<link href="https://font.c2cmalls.com/icon?family=Material+Icons"
      rel="stylesheet">
```

Read more in the [font portion](http://google.github.io/material-design-icons/#icon-font-for-the-web) of our full developer guide.

### Using symbols and sprites

The `css-sprite` and `svg-sprite` folders contain pre-generated sprite sheets, as well as svg symbols that can be `<use>`d more directly and with fewer constraints. Instructions for using them are in the [sprites documentation](https://github.com/google/material-design-icons/tree/master/sprites).

## 聚合物图标|Polymer icons

如果你想使用图标集与聚合物，我们建议通过使用|If you wish to use the icon set with Polymer, we recommend consuming them via the [`<iron-icons>`](https://github.com/polymerelements/iron-icons) 元|element ([`<core-icons>`](https://github.com/Polymer/core-icons) in v0.5).

## License

We have made these icons available for you to incorporate them into your products under the [Creative Common Attribution 4.0 International License (CC-BY 4.0)](http://creativecommons.org/licenses/by/4.0/). Feel free to remix and re-share these icons and documentation in your products.
We'd love attribution in your app's *about* screen, but it's not required.
The only thing we ask is that you not re-sell the icons themselves.
