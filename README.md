
<h1>《正则表达式库》</h1>

**更新于20200810**

## 欢迎大家提交项目中用到的正则表达式。

## 常用
* 手机号: ^1[3456789]\d{9}或者^1(3|4|5|6|7|8|9)\d{9}
* 邮箱：\w+([-+.]\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*
* IP地址：(\d+)\.(\d+)\.(\d+)\.(\d+)
* 电话号码： ^(\(\d{3,4}\)|\d{3,4}-|\s)?\d{7,14}
* 身份证号码 15位 ^[1-9]\d{7}((0\d)|(1[0-2]))(([0|1|2]\d)|3[0-1])\d{3}$  18位 ^[1-9]\d{5}[1-9]\d{3}((0\d)|(1[0-2]))(([0|1|2]\d)|3[0-1])\d{4}$ 合并 (^\d{15}$)|(^\d{17}([0-9]|X)$)
* 网络链接:(h|H)(r|R)(e|E)(f|F) *= *('|")?(\w|\\|\/|\.)+('|"| *|>)?
* 图片链接:(s|S)(r|R)(c|C) *= *('|")?(\w|\\|\/|\.)+('|"| *|>)?
* 邮政编码:[1-9]{1}(\d+){5}
* 整数：\d+
* 浮点数（即小数）：(-?\d*)\.?\d+
* 任何数字 ：(-?\d*)(\.\d+)?
* 中文字符串：[\u4e00-\u9fa5]*
* 双字节字符串 (汉字)：[^\x00-\xff]*

## 时间
* ^[1-9]\d{3}-(0[1-9]|1[0-2])-(0[1-9]|[1-2][0-9]|3[0-1])$  格式为：2014-01-01
![license](https://github.com/z503951608/RegEx/blob/master/%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81.jpg?raw=true)
