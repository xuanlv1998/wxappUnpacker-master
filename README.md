# wxappUnpacker-master

## 环境准备
npm install esprima css-tree cssbeautify vm2 uglify-es js-beautify escodegen

2019小程序解包 解决$gwx报错问题

分包解法

- node wuWxapkg.js -d  D:\Unpacker\_1357420259_6.wxapkg (如果这里错误,建议先执行-o 纯解包 再按下面步骤一个一个来)

- node wuWxss.js D:\Unpacker\_1357420259_6\component

- node wuWxml.js D:\Unpacker\_1357420259_6\component\page-frame.js

- node wuJs.js D:/Unpacker/_1357420259_6/component/app-service.js

若解分包报错可以根据报错修改$gwx的处理



