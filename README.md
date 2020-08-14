# PyCharam Cookbook 

# 前言

**PyCharm**是一个用于计算机编程的集成开发环境（IDE），主要用于Python语言开发，由捷克公司 JetBrains开发，提供代码分析、图形化调试器，集成测试器、集成版本控制系统，并支持使用Django进行网页开发。

PyCharm是一个跨平台开发环境，拥有[Microsoft Windows](https://zh.wikipedia.org/wiki/Microsoft_Windows)、[macOS](https://zh.wikipedia.org/wiki/MacOS)和[Linux](https://zh.wikipedia.org/wiki/Linux)版本。社区版在[Apache许可证](https://zh.wikipedia.org/wiki/Apache许可证)下发布[[3\]](https://zh.wikipedia.org/wiki/PyCharm#cite_note-community-3) ，另外还有专业版在专用许可证下发布，其拥有许多额外功能。

本文档是我个人多年的 PyCharm 使用经验的总结。不仅包含了面向初学者的零基础的入门使用，更提供了大量的案例讲解那些能够大大提高工作效率的 PyCharm 使用技巧。

# 第一章：安装与运行

## 1.1 多个版本的介绍与选择

Jetbrain 公司是一家专业的 IDE 生产商，只要是市面上主流的编程语言，Jetbrain 都有相应的产品。

比如：Python 对应 PyCharm ，Golang 对应 Goland，Java 对应 IntelliJ IDEA，C 语言对应 Clion 等等。

在这些众多的 IDE 中，有一些提供了多种版本：`教育版`、`社区版` 和  `专业版`。

>PyCharm Edu is based on PyCharm Community Edition and comprises all its features, making it just perfectly suitable for writing professional projects with Python.

教育版：教育版是免费的，具备社区版的所有功能，除此之外，还提供有一个教学功能，因此它更适合学生。老师可以用它创建教学，学生可以通过他完成教学任务。

社区版：就是阉割版的专业版，它也是免费的，如果你并不需要使用专业版才有那些功能，可以选择社区版。

专业版：提供所有 PyCharm 的功能，虽然是收费的，但是可以试用一个月。

社区版和专业版在功能上有哪些区别呢？你可以看下面这个表格。

可以看出专业版比社区版多了 `科学工具`、`WEB 开发`、`Python Web 框架`、`Python 代码分析`、`远程开发调试`、`数据库支持`。

![](http://image.python-online.cn/20190506150523.png)

## 1.2 申请使用免费专业版

有一种邮箱，叫做教育邮箱，这东西在这个互联网的世界有很大的优惠及特权，在 Jetbrain 这里，如果你有教育邮箱(`.edu.cn` 后缀的邮箱)但很多学生、甚至老师都未必有。

没有教育邮箱的我就在，你只要能提供能证明你的学生或者老师身份的证明，比如学生证、教师证等，Jetbrain 也可以让你免费一定期限（申请地址：https://www.jetbrains.com/student/），学生证有效期是一年，每年都要复审一次，老师的话就是长期的了。

## 1.3 使用专业版的几种方法

若你有需要使用到专业版的功能，但是你既不是学生，也不是老师，更没有所谓的教育邮箱，那怎么办呢？

对此，一般有几种方法：

1. 有钱的就是大爷，付费购买咯
2. 穷人自有穷活法，每次试用一个月，试用期到，卸载干净，再来一次。
3. 用一些 `非寻常手段` （也就是破解）来实现。

破解的方法，其实还分很多种：

1. 可以使用注册服务器的方式，优点是非常方便，缺点是过一段时间就有可能失效，不稳定。
2. 还可以使用破解补丁的方式，优点是永久破解（使用期限到 2099 或者 2100年，某种意义上算是永久了），缺点是对于最新版的 PyCharm 你可能找不到相应的破解补丁。如果要使用这种方法，就意味着你得使用旧版的 PyCharm 。

## 1.4 Windows 安装 PyCharm



## 1.5 macOS 安装 PyCharm



## 1.6 Linux 安装 PyCharm

## 1.7 一次破解，永久激活

经过我个人亲测，以下破解jar包，Windows 中在 2017.1.5 版本中有效，Mac OS 在2018.2.4 版本中有效。如果你在自己的版本中尝试无效，可以尝试切换至我的版本。

以下将分别以 Mac OS  和  Windows两个主流系统做演示。

**第一步**：

下载jar包： 此jar包的目的就是让截获截止时间并骗过 PyCharm;

[Windows 点此下载](https://pan.baidu.com/s/1dwhT6ptvi3j45i4sSZLvVA)  密码:lvyv

[Mac  OS 点此下载](https://pan.baidu.com/s/1dwhT6ptvi3j45i4sSZLvVA)，密码:5o4s

**第二步**：

若是 Windows 系统，请找到并进入你的 PyCharm 安装启动目录（以我的为例）：E:\Program Files\JetBrains\PyCharm 2017.1.5\bin

将第一步下载的 jar 包放入这个目录，并打开如下两个以 `vmoptions` 后缀结尾的文件：

![](http://image.python-online.cn/20190506150010.png)

添加如下这一行（请根据你的实际安装目录自行调整）

![](http://image.python-online.cn/20190506150100.png)

若是 Mac OS 系统，请找到并进入你的 Pycharm 安装启动目录（以我的为例）

将第一步下载的 jar 包放入这个目录

![](http://image.python-online.cn/20190507000850.png)

并打开如下一个以 `vmoptions` 后缀结尾的文件：

![](http://image.python-online.cn/20190507001025.png)



**第三步**：

随意填写个激活码，如果此前已经有写过，这步可直接跳过到第四步，如果没有写过，你就填这个吧。

点击：Help -> Register -> Activation Code

```
BIG3CLIK6F-eyJsaWNlbnNlSWQiOiJCSUczQ0xJSzZGIiwibGljZW5zZWVOYW1lIjoibGFuIHl1IiwiYXNzaWduZWVOYW1lIjoiIiwiYXNzaWduZWVFbWFpbCI6IiIsImxpY2Vuc2VSZXN0cmljdGlvbiI6IkZvciBlZHVjYXRpb25hbCB1c2Ugb25seSIsImNoZWNrQ29uY3VycmVudFVzZSI6ZmFsc2UsInByb2R1Y3RzIjpbeyJjb2RlIjoiQUMiLCJwYWlkVXBUbyI6IjIwMTctMTEtMjMifSx7ImNvZGUiOiJETSIsInBhaWRVcFRvIjoiMjAxNy0xMS0yMyJ9LHsiY29kZSI6IklJIiwicGFpZFVwVG8iOiIyMDE3LTExLTIzIn0seyJjb2RlIjoiUlMwIiwicGFpZFVwVG8iOiIyMDE3LTExLTIzIn0seyJjb2RlIjoiV1MiLCJwYWlkVXBUbyI6IjIwMTctMTEtMjMifSx7ImNvZGUiOiJEUE4iLCJwYWlkVXBUbyI6IjIwMTctMTEtMjMifSx7ImNvZGUiOiJSQyIsInBhaWRVcFRvIjoiMjAxNy0xMS0yMyJ9LHsiY29kZSI6IlBTIiwicGFpZFVwVG8iOiIyMDE3LTExLTIzIn0seyJjb2RlIjoiREMiLCJwYWlkVXBUbyI6IjIwMTctMTEtMjMifSx7ImNvZGUiOiJEQiIsInBhaWRVcFRvIjoiMjAxNy0xMS0yMyJ9LHsiY29kZSI6IlJNIiwicGFpZFVwVG8iOiIyMDE3LTExLTIzIn0seyJjb2RlIjoiUEMiLCJwYWlkVXBUbyI6IjIwMTctMTEtMjMifSx7ImNvZGUiOiJDTCIsInBhaWRVcFRvIjoiMjAxNy0xMS0yMyJ9XSwiaGFzaCI6IjQ3NzU1MTcvMCIsImdyYWNlUGVyaW9kRGF5cyI6MCwiYXV0b1Byb2xvbmdhdGVkIjpmYWxzZSwiaXNBdXRvUHJvbG9uZ2F0ZWQiOmZhbHNlfQ==-iygsIMXTVeSyYkUxAqpHmymrgwN5InkOfeRhhPIPa88FO9FRuZosIBTY18tflChACznk3qferT7iMGKm7pumDTR4FbVVlK/3n1ER0eMKu2NcaXb7m10xT6kLW1Xb3LtuZEnuis5pYuEwT1zR7GskeNWdYZ0dAJpNDLFrqPyAPo5s1KLDHKpw+VfVd4uf7RMjOIzuJhAAYAG+amyivQt61I9aYiwpHQvUphvTwi0X0qL/oDJHAQbIv4Qwscyo4aYZJBKutYioZH9rgOP6Yw/sCltpoPWlJtDOcw/iEWYiCVG1pH9AWjCYXZ9AbbEBOWV71IQr5VWrsqFZ7cg7hLEJ3A==-MIIEPjCCAiagAwIBAgIBBTANBgkqhkiG9w0BAQsFADAYMRYwFAYDVQQDDA1KZXRQcm9maWxlIENBMB4XDTE1MTEwMjA4MjE0OFoXDTE4MTEwMTA4MjE0OFowETEPMA0GA1UEAwwGcHJvZDN5MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAxcQkq+zdxlR2mmRYBPzGbUNdMN6OaXiXzxIWtMEkrJMO/5oUfQJbLLuMSMK0QHFmaI37WShyxZcfRCidwXjot4zmNBKnlyHodDij/78TmVqFl8nOeD5+07B8VEaIu7c3E1N+e1doC6wht4I4+IEmtsPAdoaj5WCQVQbrI8KeT8M9VcBIWX7fD0fhexfg3ZRt0xqwMcXGNp3DdJHiO0rCdU+Itv7EmtnSVq9jBG1usMSFvMowR25mju2JcPFp1+I4ZI+FqgR8gyG8oiNDyNEoAbsR3lOpI7grUYSvkB/xVy/VoklPCK2h0f0GJxFjnye8NT1PAywoyl7RmiAVRE/EKwIDAQABo4GZMIGWMAkGA1UdEwQCMAAwHQYDVR0OBBYEFGEpG9oZGcfLMGNBkY7SgHiMGgTcMEgGA1UdIwRBMD+AFKOetkhnQhI2Qb1t4Lm0oFKLl/GzoRykGjAYMRYwFAYDVQQDDA1KZXRQcm9
```



**第四步**：

若是 Windows 系统，重启 PyCharm 后，查看激活信息：Help -> About

![](http://image.python-online.cn/20190507001422.png)

如果是 Mac  OS 系统，重启 PyCharm 后，查看激活信息：PyCharm -> About PyCharm

![](http://image.python-online.cn/20190507001350.png)

另外，以上仅做交流和个人学习使用，请勿商用，有能力的朋友还是希望多支持正版！

# 第二章：界面与排版

##  2.1 关闭烦人的灯泡提示

本来没有想写这个的，但是知乎上有一位朋友有这个需求，那我研究了下。

![](http://image.python-online.cn/FhkX5Ko3LVZL_p7YfitDsTDxvHmL)

先来说下这个灯泡提示是什么，有什么用？

当我们在代码里面有语法错误，或者代码编写不符合 pep8 代码规范时，鼠标选择有问题的代码，就会自动弹出小灯泡，这个灯泡是有颜色之分的，如果是红灯泡，一般都是语法问题，如果不处理会影响代码运行。而如果是黄灯泡，就只是一个提示，提示你代码不规范等，并不会影响程序的运行。

虽然这个灯泡，是出于善意之举，但我认为它确实有点多余（可能是我个人没有使用它的习惯），要是语法错误会有红色波浪线提示。你可能会说灯泡不仅起到提示的作用，它还可以自动纠正代码，我个人感觉并没有人工校正来得效率，来得精准。

基于有时还会像知乎上这个朋友说的这样，会挡住我们的代码，会经常误点，这确实也是一个烦恼。

我研究了下，Pycharm （2018版本）里是有开关按钮的，将下图中的这个选项（`Show intention bulb`）取消勾选，就可以关闭这个功能。

![](http://image.python-online.cn/FuSSVa-aMqkfCaf62sbUoX2PLaYM)

## 2.2 关闭碍眼的波浪线

下面我先给出了一小段代码示例，思考一下，为什么name，my_name 不会有波浪线，而 myname 和 wangbm 会有波浪线呢？

![](http://image.python-online.cn/FtFPI89AOKmPLNpNxf-jdkn1BDLW)

Pycharm 本身会实时地对变量名进行检查，如果变量名不是一个已存在的英文单词，就会出现一条波浪线，当一个变量里有多个单词时，Python 推荐的写法是用下划线来分隔（其他语言可能会习惯使用`驼峰式命名法` ，但 Python 是使用下划线），所以在 Pycharm 看来  my_name 是规范的，而 myname 会被当成是一个单词对待，由于它在单词库里并没有它，所以 myname 是不规范的。

每个人的变量命名习惯不一样，如何你在项目里大量使用了 myname 这种风格的变量命名方法，像下面这样（随便找了一段 cloudinit 的代码），是让人挺不舒服的，总有一种代码有 bug 的错觉。

![](http://image.python-online.cn/FiKyU6tjQauWXfaVfKLhwi3NkXBf)

那么如何关闭这个非语法级别的波浪线呢？很简单，它的开关就在你的右下角那个像 人头像 一样的按钮

![](http://image.python-online.cn/FsAM-8HyzSrLWZJ_lg3ofw84_ibf)

然后选择 `Syntax` 级别的即可。同样一段代码，效果如下，干净了很多。

![](http://image.python-online.cn/FgJCtNYkjPfBaTbRxwb3Z6icHqkf)

## 2.3 代码排版，自动PEP8

`pep8` 是Python 语言的一个代码编写规范。如若你是新手，目前只想快速掌握基础，而不想过多去注重代码的的编写风格（虽然这很重要），那你可以尝试一下这个工具 - `autopep8`

首先在全局环境中（不要在虚拟环境中安装），安装一下这个工具。

```bash
sudo pip install autopep8
```

然后在 Pycharm 里导入这个工具。

```
Name: AutoPep8
Description: autopep8 your code
Program: autopep8
Arguments: --in-place --aggressive --aggressive $FilePath$
Working directory: $ProjectFileDir$
Output filters: $FILE_PATH$\:$LINE$\:$COLUMN$\:.*
```

![](http://image.python-online.cn/20190323164120.png)

我随意写了一段不符合 pep8 规范的代码。

![](http://image.python-online.cn/20190323211635.png)

点击右键，选择 `External Tools` -> `AutoPep8`

![](http://image.python-online.cn/20190323211301.png)

看一下效果，还是挺明显的。

![](http://image.python-online.cn/20190324111603.png)

你可能会说，Pycharm 本身就自带这个功能了呀，快捷键 `Command`+`Option`+`L` ，就可以实现一键pep8了。你可以对比一下，Pycharm 自带的代码 pep8 化功能 并没有像这个`autopep8` 来得彻底。 我相信你最终的选择肯定是后者。

## 2.4 保护眼睛，从PyCharm开始

记得刚毕业时，进入的第一家公司，有一个小姐姐，她把自己的电脑中对保护眼睛有用的配置都研究了一番。

其中就有程序的护眼色，什么word，excel，文件管理器，浏览器，能更改背景色的，全部设置个遍。

不能不说，合理的背景色，确实对保护眼睛有一定的作用，但个人觉得最重要的还是合理适时的休息。

这里就教大家如何设置 PyCharm 的背景色为护眼色，方法如下：

![](http://image.python-online.cn/20190721143450.png)

设置护眼色，会降低 PyCharm 的顔值，这需要你从中取一个取舍。



## 2.5 多行标签页，一览无余

PyCharm 打开一个文件，就占用一个标签面。

你有没有发现，不知不觉地，打开的文件越来越多，多到一行标签都装不下，装不下的标签页 PyCharm 会将其隐藏起来，并以数字的形式告诉你隐藏了几个文件。

![](http://image.python-online.cn/20190629223534.png)

点击数字5，你才可以查看隐藏了哪些文件。

这时你肯定会说，一行装不下 PyCharm 为什么不能多行显示呢？

答案是，不是不能，而是需要你设置。

如下图，将单行显示取消勾选即可。

![](http://image.python-online.cn/20190629224229.png)

设置完后，有哪些文件就非常清晰了。

![](http://image.python-online.cn/20190629224430.png)


## 2.6 轻松实现 json 格式化

如下是一个未经美化的 json 文件，当一个 json 文件的内容很多时，若不经过工具重新美化，想要从中提取出有效的信息是一件很困难的事情。

```json
{"profile":{"name":"明哥", "gender": "male", "age": 18, "公众号": "Python编程时光", "msg": "欢迎大家关注我的公众号！"}}
```

以前我经常使用一些在线的网站，比如：https://tool.oschina.net/codeformat/json

![](http://image.python-online.cn/20191211211309.png)

如果你的电脑无法连网，或者不喜欢多记一个网址，完全可以使用 PyCharnm 来解决这一诉求

没有经过美化是这样的：

![](http://image.python-online.cn/20191211211334.png)

按住 `Ctrl+Alt+L`经过美化后是这样的

![](http://image.python-online.cn/20191211211626.png)


# 第三章：快捷与效率

## 3.1 复杂操作，录制成宏

如果你在使用PyCharm 的时候，遇到有一些操作是比较复杂（步骤多），且使用频率特别高。

那可以考虑一下，使用其自带的宏录制工具。

它会将你的一连串操作，录制下来。等你想用的时候，直接调用就行了。

这边，我以录制一个 `删除函数` 的宏为例：先按上面的方法折叠函数，再按 Command+y 删除该行，就删除了该函数。

做录制方法如下：

![](https://i.loli.net/2019/06/29/5d176e9ba92e916696.gif)

(GIF动态只播放两次，重播请刷新页面)

录制好后，你可以先定位到你要删除的函数处，点菜单栏 Edit - Macro 然后选择我们刚刚录制的宏，就可以播放宏了。

这样播放宏显得有点繁琐，个人建议你为这个宏定义一个快捷键，这样会更方便播放宏。

![](http://image.python-online.cn/20190629221224.png)

设置快捷键时，注意不要和已有的快捷键冲突。

设置好后，查看 Macro，发现PyCharm已经将这个快捷键绑定给这个宏。

![](http://image.python-online.cn/20190629221547.png)

之后你就可以使用这个快捷键删除一个函数（其实这只是删除一个代码块，但是这里只讨论设置方法）。

## 3.2 源码文档，快速预览

Ctrl + 鼠标左键 （Mac 上是：Command + 鼠标左键），可以实现函数跳转查看源码， 这几乎是每一个 PyCharmer 都会的一个惯用技巧。

这里再另外介绍两个类似的小技巧，快速 `查看函数文档` 和 `预览源代码` 。

在函数的开头处，使用三个引号 ` "` 包含的内容，叫做函数文档 （DocString）。

在编写代码时，顺便写好函数的接口文档，是一个很好的编码习惯。它介绍了该函数的参数类型及说明，返回值类型及范例，写得好一点的还会写出 几个简单的 Example Usage 有助于理解使用。在这一点上，Flask 可以说做得相当好。这边随便截一个 Werkzeug 的例子。

![](http://image.python-online.cn/20190507152911.png)

假如我们在使用这个类的时候，忘记了这个用法，可以按住 Ctrl + q（Mac暂时未找到对应快捷键），在当前页面就可以快速预览 LocalStack 的接口文档。

![](http://image.python-online.cn/20190507152840.png)

同样的，如果你对这个类或者函数的代码逻辑感兴趣，也可以使用快速预览的方式在当前页面展示源代码。快捷键是：Ctrl + shift + i （Mac：Command + shift + i）。效果如下

![](http://image.python-online.cn/20190507153847.png)

如果 PyCharm 检测到的同名函数有多个，可以点这里进行选择查看

![](http://image.python-online.cn/20190507154027.png)

这两个快捷键比起使用 Ctrl + 鼠标左键 跳进源代码来说，更加方便，，就像微信小程序一样，用完即焚，不会新产生一个标签页，也不需要来回跳转页面。

## 3.3 快速定位到错误行

前几天打开 PyCharm，发现在导航栏这里出现了很多波浪线，有过 PyCharm 使用经验的同学，就会知道，这是代码中出现了错误。

![](http://image.python-online.cn/20190613154147.png)

顺着波浪线，我一层一层地展开目录树，终于找到了那个包含错误的文件。由于是手误，我也不知道我改动了哪一行，看了下这个文件，有将近8000行的代码，难道一行一行地去找？

不，这绝对不是使用 IDE 正确的方式。

遇到问题，就应该尝试去寻找快捷方法，有没有办法，可以一下子定位到错误代码呢？

这时候，我想起了PyCharm 有提供给我们一个 Keymap 的面板，可以很方便的设置、查询快捷键。说不定我在那里可以找到我想要的答案

我在搜索框输入 Error，就找到了快速定位到错误位置的快捷键 `F2` 和 `Shift+F2` 可以快速的定位到错误行。

![](http://image.python-online.cn/20190613154401.png)

使用快捷键 F2 查看了下原来是这里缩进有问题。

![](http://image.python-online.cn/20190613160905.png)

## 3.4 快速查看最近的修改

上面为了恢复因为手误造成的语法错误，我使用了快捷键来定位错误行，虽然解决了问题，但总有种绕了几个弯的感觉。

假如有种方法，可以项目查看最近的修改记录的话（没有git做版本控制的情况下），那就太好了。

太巧的是，今天我打开 PyCharm ，就给我推了这条 tip，（在Mac上）使用 option+shift+C 可以快速查看最近修改的内容（windows 上应该是alt+shift+c吧）

![](http://image.python-online.cn/20190614235120.png)

## 3.5 快速输入自定义代码片段

在 PyCharm 中有一个功能叫 Live Template，它可以用来自定义一些常用的代码片段。

比如下面这段，几乎是写 Python 脚本必备的

```python
if __name__ == '__main__':
```

当你在PyCharm 中编码 python 代码时，只要输入 main ，PyCharm 就会在 Live Template 里找到定义过的代码片段，然后只要直接键入回车，就可以生成这段代码。

再比如说，我通常会定义简单的装饰器代码

![](http://image.iswbm.com/20200723161209.png)

这样当我要定义一个最简单的装饰器时，只要输入 `deco` 再直接敲入回车就行啦。

![](http://image.iswbm.com/20200723161307.png)



## 3.6 代码模板，效率编码

Pycharm 提供的这个代码模板，可以说是相当实用的一个功能了。它可以在你新建一个文件时，按照你预设的模板给你生成一段内容，比如解释器路径，编码方法，作者详细信息等

![](http://image.python-online.cn/20190323225704.png)

按照上图模板，生成的效果如下。

![](http://image.python-online.cn/20190323225631.png)

除了新建文件时可以初始化文件，在开发编写代码时，也同样使用 Pycharm 中自带的实用的代码模板，提高你的编码效率。

当你在键盘中敲入 `Command` + `J` 时，就可以调出一个面板，从下图可以看出里面有许多预设的模板。

![](http://image.python-online.cn/20190323232017.png)

如果我们想选择最后一个 main ，可以继续键入 main，然后就可以直接生成如下这段平时都要手动敲入的代码。

![](https://i.loli.net/2019/03/23/5c965275bf0d7.gif)

这里再举个例子，for 循环 可以这样写。

![](https://i.loli.net/2019/03/23/5c9653e1b757a.gif)



# 第四章：调试与运行

## 4.1 神一样的调试技巧

假如我们在一个爬虫的项目中，会使用到 正则表达式 来匹配我们想要抓取的内容。正则这种东西，有几个人能够一步到位的呢，通常都需要经过很多次的调试才能按预期匹配。在我们改了一次正则后，运行了下，需要重新向网站抓取请求，才能发现没有匹配上，然后又改了一版，再次运行同样需要发起请求，结果还是发现还是没有匹配上，往往复复，正则不好的同学可能要进行几十次的尝试。

（上面这个例子可能不太贴切，毕竟是有很多种方法实现不用重新发请求，只是列举了一种很笨拙且低效的调试过程，你看看就好了）

而我们在这几十次的调试中，向同一网站发起请求都是没有意义的重复工作。如果在 Pycharm 中可以像  IPython Shell  和 Jupyter Notebook 那样，可以记住运行后所有的变量信息，可以在不需要重新运行项目或脚本，就可以通过执行命令表达式，来调整我们的代码，进行我们的正则调试。

答案当然是有。

假如我在调试如下几行简单的代码。在第 3 行处打了个断点。然后点击图示位置 `Show Python Prompt` 按钮。

![](http://image.python-online.cn/Fi3N02x9OeOPatGdaReam_icn9G_)

就进入了 `Python Shell` 的界面，这个Shell 环境和我们当前运行的程序环境是打通的，变量之间可以互相访问，这下你可以轻松地进行调试了。

![](http://image.python-online.cn/Fj1W53Txj0iFs5eYhFYh_dHlPtIL)

上面我们打了个断点，是为了方便说明这个效果。并不是说一定要打断点。如果不打断点，在脚本执行完成后，也仍然可以在这个界面查看并操作所有变量。

![](http://image.python-online.cn/FlMsB7B1x6ET9mLOgydTWuTEXuOe)

现在我们已经可以满足我们的调试的需求，但是每次运行脚本，都要手动点击 `Show Python Prompt` ，有点麻烦。嗯？其实这个有地方可以设置默认打开的。这个开关还比较隐秘，一般人还真发现不了。

你需要点击图示位置 `Edit Configurations` 处。

![](http://image.python-online.cn/FmfL3r0iWx_srT_xMASBEp1ZaaId)

然后在这里打勾选中。

![](http://image.python-online.cn/FiNCYpVlI93gk1zhOdQn4c0A8FMX)

设置上之后，之后你每次运行后脚本后，都会默认为你存储所有变量的值，并为你打开 console 命令行调试界面。

除了上面这种方法，其实还有一种方法可以在调试过程中，执行命令表达式，而这种大家可能比较熟悉了，这边也提一下，就当是汇总一下。但是从功能上来说，是没有上面这种方法来得方便易用的。因为这种方法，必须要求你使用 debug 模式运行项目，并打断点。

使用方法就是，在你打了断点后，在图示位置处，点击右键使用 `Evaluate Expression`

![](http://image.python-online.cn/FrAq1tVRM7Bz948wRqZFzU2PQnI0)

就弹出了一个 `Evaluate Expression` 窗口，这里 可以运行命令表达式，直接操作变量。

![](http://image.python-online.cn/Fo2aEraqbj_2KqDt44EzJTVe8pEf)

## 4.2 调试远程服务器的代码

一般情况下，我们开发调试都是在个人PC上完成，遇到问题，开一下 `Pycharm` 的调试器，很快就能找到问题所在。

可有些时候，项目代码的运行会对运行环境有依赖，必须在部署了相关依赖组件的服务器上才可以运行，这就直接导致了我们不能在本地进行调试。

对于这种特殊的场景，就我所知，有如下两种解决方案：

- pdb
- 远程调试

关于 pdb，之前也写过专门的文章介绍使用方法，你可以点此查看：[无图形界面的代码调试方法 - pdb](https://mp.weixin.qq.com/s/tDufSUBrBBNfMEr5_dxM0g)

而远程调试呢，是让我们可以在我们在 PC 上用 Pycharm 的图形化界面来进行调试远方服务器上代码，它和本地调试没有太大的区别，原来怎么调试的现在还是怎么调试。

区别就在于，本地调试不需要事前配置，只要你的代码准备好了，随时可以开始 Debug ，而远程调试需要不少前置步骤。

而这些配置步骤还挺多的，我专门写了一篇文章介绍设置过程，你可以点此查看：[图文教程｜不能不会的远程调试技巧](https://mp.weixin.qq.com/s/ECWCJMQ6oEDaY1x1JfGfkg)



## 4.3 指定参数执行脚本

你在 Pycharm 运行你的项目，通常是怎么执行的？我的做法是，右键，然后点击 `Run`，或者使用快捷键 `Shift + F10` 。

有时候，在运行/调试脚本的时候，我们需要指定一些参数，这在命令行中，直接指定即可。

假设在命令行中，运行脚本的命令是这样

```shell
python main.py init --local
```

对于刚使用 Pycharm 的同学，可能并不知道 Pycharm 也是可以指定参数的。点击下图位置

![](http://image.python-online.cn/FmfL3r0iWx_srT_xMASBEp1ZaaId)

进入设置面板，在 `Script parameters` 中填入参数即可。

![](http://image.python-online.cn/FujczKwTUPa8l5EEmS0eoh-zL1Nk)

同时在上图的底部，你可以看到，这里可以很方便的切换 解释器，比你跑到这边来要容易得多吧

![](http://image.python-online.cn/Fq60WOdcRJopqV6MVoRcIuZclYKx)




# 第五章：插件与工具

## 5.1 TODO 解救“中年痴呆”

一个程序员，如果能够一天都只和代码打交道，是一件多么难得的事情。

可能外行人不知道，做为同样是程序员的你，是不是和我有一样的烦恼。

代码写着写着，测试突然就喊道：小明，你的代码有bug，ug，g（回声）。。

代码写着写着，运维突然一个弹窗：小明，这个线上问题赶紧排查一下。。

代码写着写着，产品突然就跳出来：小明，能做一个根据手机壳颜色自动改变app主题的app不？？

这样的噩梦每天都在重复不间断地上演着，或许我知道了为什么程序员要在深夜里码代码了，因为那是白日里得不到的宁静。

所以 王建硕 在<< [入静和入世](http://blog.jobbole.com/24682/) >>一文中写道：

> “当看到一个程序员冥思苦想的时候，不要过去打扰，甚至在极端的情况下，一句友好的问候都是多余的。 ”  

为了避免这个情况，我通常在别人打断我的时候，请对方给我一分钟的时间，使用PyCharn 的 TODO 功能快速记录下当前的思绪状态，以及下一步要做的事情。

使用方法跟注释差不多，只要固定要以 TODO 开头。然后，你要查看全局项目中的所有 TODO 事项的时候，可以使用快捷键调出 TODO 面板。如果你是 Mac， 快捷键 是Command + 6，而 Windows 是 Alt+6。

![](http://image.python-online.cn/20190616231649.png)

另外，我还使用这个来记录下个版本要优化的代码逻辑，要添加的功能。

如果是比较紧急的 BUG，可以使用类似 TODO 的标记 — `FIXME` 来区分紧急程度。

![](http://image.python-online.cn/20190616232527.png)

## 5.2 随处折叠，实现代码自由

PyCharm 里代码块的折叠功能，相当的显眼，在代码编辑框的左侧，你可以发现有 `+` 也有 `-`，很容易理解 `+` 代表代码块被折叠了可以点此展开，而 `-` 代表这个代码块处于展开状态可以点此折叠。

如果你和我一样是个键盘党，你可以使用快捷（Mac：按住Command键，再按`+`或者`-` ，Windows：按住Ctrl键，再按`+`或者`-` ）进行快速反折叠/折叠。

![](http://image.python-online.cn/20190629183430.png)

代码块的折叠和反折叠，应该是一个代码编辑器的基本功能。在这一点上， PyCharm 做为一个 IDE，在这一点上势必要做得更出色，事实证明，它做到了。

从上面，我们知道只有代码块才支持缩放，那什么样的代码PyCharm才会认为是一个代码块呢？其严格地定义我没有找到，从经验来看，一个类，一个函数，一个for循环，一个while循环，一个多行注释等都是代码块。都可以进行折叠、反折叠。

有时候，我们并不希望整块代码进行折叠，而只想对其他一大段暂时对我们无用的代码进行折叠。那能做到吗？

答案是可以的。

只要你先选中你想折叠的代码，再按住 Command 紧接着按住 `.` 就可以了。效果如下：

![](https://i.loli.net/2019/06/29/5d17589c1603755790.gif)

(GIF动态只播放两次，重播请刷新页面)

## 5.3 重构操作，一步到位

最近有一位同事走了，由我来接手他的全部工作。

可能由于我有代码洁癖，我花了一个星期对其代码进行了大量的重构。

重构代码，免不了要对变量进行重命名。

如果一个一个改，显然不太智能，要知道我们是在用IDE，你也许会说，用搜索全部替换不就行了？还真不行。

比如下面这段代码，我只想改myfun 里的的test_name，而对于全局下的同名变量是不应该修改的。如果你全局替换，就会有误伤。

![](http://image.python-online.cn/20190629211910.png)

这时候，我们如何做呢？

可以使用 PyCharm 的 Refactor 功能，它会自动匹配作用域，既做到批量更改，也做到不误伤。

操作方法很简单，先选中你的变量，然后使用快捷键 Shift+F6，就可以直接重命名了。

![](https://i.loli.net/2019/06/29/5d1764b94d11128912.gif)

(GIF动态只播放两次，重播请刷新页面)



## 5.4 Tab轻松转空格

在团队协作中，你难免会动到别人编辑的文件，有的人喜欢做tab做缩进，有的人喜欢用四个空格做缩进。

但是在同一个Python文件模块里，tab 和 四个空格缩进两种风格是不能共存的。这就需要你按照该文件原来的缩进风格来进行编码，在 Pycharm 里，可以设置自动检测原文件的缩进风格来决定当你使用tab键缩进的时候，是TAB还是四个空格。

在图示位置打勾即可开启自动检测。

![](http://image.python-online.cn/20190423162328.png)

上面是对一个旧的 Python 模块进行修改时，如何决定当前编辑的缩进方式。

而对于新建模块，默认的缩进方式，是如何确定的？

如下图，若在 `Use tab character` 打上勾，则你新建一个 Python 后，就会使用 TAB 进行缩进，反之，则使用四个空格进行缩进。

![](http://image.python-online.cn/20190423163341.png)



## 5.5 以列为单位的块编辑

先给你出道小题，像下面这段代码，如果在不影响代码的情况下，快速删除后面代码后面的注释呢？

![](http://image.python-online.cn/20190721132238.png)

我能想到的有两种方法，如果像如上这种有规律的注释，可以使用 `正则匹配` + `替换` 来实现。

![](http://image.python-online.cn/20190721133403.png)

对于这个场景我想到了可以用 vim来轻松的解决，vim 支持块编辑，可以以列为单位选择区域然后进行操作，这在vim中是很常用的一个取消注释的操作。

同样回到 PyCharm 中来，你会发现它也支持块编辑。

当你按住 alt（windows）或者option（mac），然后使用鼠标进行选择，你会发现这样一件神奇的事情。

![](https://i.loli.net/2019/07/21/5d3401410087b61815.gif)

##  5.6 智能补全，忽略大小写

智能搜索补全，是IDE的最吸引人的功能之一。

当你的对象是以大写字母开头时，而你使用小写字母编写代码时，是不能查找到该函数的，你必须得先切换成大写再输入一遍。

![](http://image.python-online.cn/20190721141327.png)

如何避免这种尴尬的情况？

只要在配置中关闭大小写匹配即可。

![](http://image.python-online.cn/20190721141653.png)

效果如下：

![](http://image.python-online.cn/20190721141751.png)




## 5.7 记录过去的专属剪切板

在 Windows 上有一个剪切板神器 - `Ditto` ，它可以将你间经复制粘贴过的内容都保存下来，以便你重复使用。

当然在 Mac 上的 Alfred 也有类似的功能。

前段时间，偶然在电脑上偶然发现 PyCharm 也有类似的功能，只要你按住 `Ctrl + Shift + V` 就可以调出像下面这样的剪切板。

这里我提前准备了几种编程语言的 Hello World ，效果如下：

![](http://image.python-online.cn/20191211210012.png)





## 5.8 在Windows上使用 Linux 命令

在 Windows 上的 cmd 命令和 Linux 命令有不少的差异，比如要列出当前目录下的所有文件，Windows 上是用 `dir` ，而 Linux 上则是用 `ls -l` 。

对于像我这样熟悉 Linux 的开发者来说，Windows 的 那些 CMD 命令带来的糟糕体验是无法忍受的。

![](http://image.python-online.cn/20191211212546.png)

在弹出的 Bash 窗口，你可以敲入你想使用的 Linux 命令，是不是舒服多了。

![](http://image.python-online.cn/20191222143741.png)



## 5.9 快速进行代码封装的技巧

当一个主函数的代码行数越来越多时，代码的可读性会变得越来越差。通常的做法，是按照功能将代码进行封装成多个函数。

这个过程无非是

1. 在合适的位置定义一个新的函数
2. 将原有的代码拷贝至该函数中
3. 并将原的代码替换成该函数的调用

倘若你的重构的工作量不是很大，完全可以手工来完成这些事。

但当你是在重构一个项目代码时，你可能需要一个更高效的封装技巧。

在 PyCharm 中，提供了多种形式的代码重构快捷方法，大家比较常见的可能是重构变量名：shift+F6，而今天要给大家介绍的是方法的重构，也即代码快速封装的技巧。

假如，我现在有如下一段代码，红框标出的代码放在主函数中，有些不太合适，况且这段代码不能让人一眼就看出它是在做什么事情。如何将其进行封装，对我们理清整个主程序的逻辑会有帮助。

![](http://image.python-online.cn/20191222141905.png)



选中你要封装的代码，然后按住 `Ctrl`+`Alt`+`M` 后，会跳出如下界面，根据自己的需要，修改函数名，选择参数和返回值

![](http://image.python-online.cn/20191222141955.png)

一切就绪点击 `OK`，PyCharm 会自动在合适的位置为你定义一个函数名，并将你选中的代码放到里面，其中参数名和返回值也都是按照你的要求，效果如下：

![](http://image.python-online.cn/20191222142223.png)



## 5.10 拥抱Vim，远离鼠标

在大多数场景之下，使用鼠标的效率和精准度，是远不如键盘快捷键的（前提是你已经相当熟练的掌握了快捷键），这个你得承认吧。

Vi 可以满足你对文本操作的所有需求，比可视化界面更加效率，更加 geek。如果你和我一样，是忠实的 vim 粉。在安装完 Pycharm 完后，肯定会第一时间将 `ideaVim` 这个插件也装上，它可以让我们在 Pycharm 中 使用 vim 来编辑代码。

安装方法如下，安装完后需要重启 Pycharm 生效。

![](http://image.python-online.cn/20190323214545.png)



## 5.11 一键进行代码性能分析

在 Python 中有许多模块可以帮助你分析并找出你的项目中哪里出现了性能问题。

比如，常用的模块有 cProfile，在某些框架中，也内置了中间件帮助你进行性能分析，比如 Django ，WSGI。

做为Python 的第一 IDE， PyCharm 本身就支持了这项功能。而且使用非常方便，小白。

假设现在要分析如下这段代码的性能损耗情况，找出到底哪个函数耗时最多

```python
import time

def fun1():
    time.sleep(1)

def fun2():
    time.sleep(1)

def fun3():
    time.sleep(2)

def fun4():
    time.sleep(1)

def fun5():
    time.sleep(1)
    fun4()

fun1()
fun2()
fun3()
fun5()
```

点击 Run -> Profile '程序' ，即可进行性能分析。

![](http://image.python-online.cn/20190507222856.png)

运行完毕后，会自动跳出一个性能统计界面。

![](http://image.python-online.cn/20190507222119.png)

性能统计界面由Name、Call Count、Time(ms)、Own Time(ms) ，4列组成一个表格，见下图。

1. 表头Name显示被调用的模块或者函数；Call Count显示被调用的次数；Time(ms)显示运行时间和时间百分比，时间单位为毫秒（ms）。
2. 点击表头上的小三角可以升序或降序排列表格。
3. 在Name这一个列中双击某一行可以跳转到对应的代码。
4. 以fun4这一行举例：fun4被调用了一次，运行时间为1000ms，占整个运行时间的16.7%

点击 Call Graph（调用关系图）界面直观展示了各函数直接的调用关系、运行时间和时间百分比，见下图。

![](http://image.python-online.cn/20190507223313.png)

右上角的4个按钮表示放大、缩小、真实大小、合适大小；

1. 箭头表示调用关系，由调用者指向被调用者；
2. 矩形的左上角显示模块或者函数的名称，右上角显示被调用的次数；
3. 矩形中间显示运行时间和时间百分比；
4. 矩形的颜色表示运行时间或者时间百分比大小的趋势：红色 > 黄绿色 > 绿色，由图可以看出fun3的矩形为黄绿色，fun1为绿色，所有fun3运行时间比fun1长。
5. 从图中可以看出Test.py直接调用了fun3、fun1、fun2和fun5函数；fun5函数直接调用了fun4函数；fun1、fun2、fun3、fun4和fun5都直接调用了print以及sleep函数；整个测试代码运行的总时间为6006ms，其中fun3的运行时间为1999ms，所占的时间百分比为33.3%，也就是 1999ms /  6006ms = 33.3%。



## 5.12 静态代码分析检查

对于编译型的语言，如 Java，需要将代码编译成机器可识别的语言才可运行，在编译过程中，就可以通过分析或检查源程序的语法、结构、过程、接口等来检查程序的正确性，找出代码隐藏的错误和缺陷。这个过程叫做静态代码分析检查。

那对于 Python 这种解释型的语言来说，代码是边运行边翻译的，不需要经过编译这个过程。很多肉眼无法一下子看出的错误，通常都是跑一下（反正跑一下这么方便）才能发现。

由于Python 运行是如此的方便，以至于我们都不太需要关注静态分析工具。 

但也不是说，静态分析工具完全没有用武之地，我认为还是有。

如果你的编码能力还没有很成熟，代码中可以有许许多多的隐藏bug，由于 Python 是运行到的时候才解释，导致一次运行只能发现一个错误，要发现100个bug，要运行100次，数字有点夸大，其实就是想说，如果这么多的错误都能通过一次静态检查发现就立马修改，开发调试的效率就可以有所提升。当然啦，并不是说所有的错误静态分析都能提前发现，这点希望你不要误解。

做为 Python 最强 IDE，PyCharm本身内置了这个功能，不需要你安装任何插件。

你只需要像下面这样点击项目文件夹，然后右键，选择 `Inspect Code`，就可以开启静态检查。

![](http://image.python-online.cn/20190616211359.png)

我对开源组件 nova 的静态检查发现，其有不规范的地方有数千处。

![](http://image.python-online.cn/20190616214310.png)


## 5.13 误删文件，一秒找回

上周，由于自己的误操作，在没有任何备份的情况下，将一个自己写了两个星期的项目给删除了。待我回头神来的时候，我甚至都记不起是何时进行的删除操作。

做为一名老司机，当然是临危不惧地打开了回收站，进行一番搜寻，几个月没有清理过的回收站，真是一片狼藉，什么 jpg，avi 都有，不堪入目呀。

我用一分钟快速浏览了一下，没有发现我要找的那几个 py 文件，我心想，应该是文件太多了，看叉掉了。由于项目是最近写的，文件名我还清楚地记得，既然有文件名，那就利用windows 自带的搜索功能，结果还是没有，这下我才开始意识到事态的严重性，文件可能真的「没了」。

我已经很久没有清理过回收站了，为什么回收站里会没有我的文件呢？

我想这可能是一次非同寻常的 delete，会不会是在 Pycharm 里的 发起删除操作，不会往回收站里丢呢？经过一番测试，在回收站还真的找不着，但是这次尝试也无意中发现了 Pycharm 的隐藏的一个功能 `Local History`，它会保存你对文件的所有操作记录。

就拿我的刚刚测试的文件来举例，我先是新建了一个文件，然后对在这个文件里添加了几行代码。最后我将这个文件删除了。

此时你可以在你的项目目录里，点击右键，有个 `Local History` 的选项，再点击子选项 `Show History`，你可以看到这里有个记录板。如果你想恢复删除的文件，就在删除的记录项点击右键，选择 `Revert` 即可恢复。

![](http://image.python-online.cn/20190323153643.png)




# 第六章：搜索与查找

## 6.1 应用搜索，阅读源码必备

你平时若有阅读框架源码的需求或习惯，那你一定要来掌握这个技能。

在阅读源码时，代码的入口、流程、走向特别重要。

假设你现在知道了一个特别关键的类，你特别想知道是哪里调用了这个类，你想知道源头，知道整个调用流程。

这个时候你使用全局搜索，就会有很多的干扰信息。

这个时候，你急需有一种方法，可以快速给你列出有哪些地方调用了这个类。

快捷键：Mac：Command+Option+F7 ，Windows：Ctrl+Alt+F7

如下图所示，按下快捷键后可以很轻松地看见调用列表。

![](http://image.python-online.cn/20190629231322.png)

如果你嫌这快捷键太长了，可以使用 `鼠标中键` 点击这个类，可以达到同样的效果。


## 6.2 使用书签，快速定位

都我在看框架的源代码时，最常使用的是 `Command` + `B` （也就是 command + 鼠标左键 ）一层一层地往里深入，但是当源代码比较多，可能一整个事件过程涉及十几文件，函数调用错综复杂，对于一个庞大的项目来说，有用的可能就几个关键函数，每次要找到这几个函数，都要重头从源函数再一层一层的找下去，这样实在太麻烦了，我常常因此把自己给看晕了。

直到后来我发现了 Pycharm 这个书签功能。

使用书签功能，我可以在在关键的位置打上书签，想看的时候，调用书签，快速定位即可。

使用它，你需要记住下面下两个快捷键

```
Command + F11    打上书签
Shift + F11      展示所有书签

在windows上可以使用
F11              删除书签
Ctrl + Shift + 1  添加“1”序号的标签
```

在你要打书签的位置，按下 `Command` + `F11` ，你可以给这个位置加个序号，可以是数字也可以是字母，假如在下面这个位置 加了 `1` 这个序号，下次你就可以使用 `Control` + `1` 直接跳转到这个位置。

![](http://image.python-online.cn/20190324111429.png)

当然你也可以不加，不加的话就是匿名书签了。你可以使用 `Shift` + `F11` 展示所有的书签，再进行跳转。




## 6.3 全方位无死角精准定位

一直觉得使用鼠标是一种非常低效的习惯。

我热衷于使用各种键盘快捷键来提高操作的精准度，在编辑器上我可以相当熟练的使用 vim 指令完成我各种需求，因此我给 PyCharm 装上了ideaVim，给 Chrome 装上了 Vimium。

同样地阅读框架代码，我也都是使用全键盘进行操作。因为我有长期阅读 OpenStack 源码的需求，其代码量是数百万级别的。如果没有使用精准定位来快速跳转，这种极差的体验将很难使我坚持下来。

这里暂时先介绍几种我最常用的精准定位方法，主要可以定位跳转到如下三种

- 精准定位到文件：Windows（Ctrl+Shift+N），Mac（Command+ shift +N）

![](http://image.python-online.cn/20190616221620.png)

- 精准定位到类：Windows（Ctrl+N），Mac（Command+N）

![](http://image.python-online.cn/20190616232746.png)

- 精准定位到符号：类的所有成员（函数、变量等）都可以称之为符号，Windows（Ctrl+Alt+Shift+N），Mac（Option+Shift+Command+N）

![](http://image.python-online.cn/20190616233827.png)

- 精准定位到文件结构：文件结构包括类、函数、变量，这说明上面定位到类和定位到符号的方法，你都可以用这个来代替。

  Windows：Ctrl+F12，Mac：Command+F12，如果和我一样是Mac是带touchbar的，键盘上是没有F12的，那你应该先按住 Command + fn，这时 touchbar 上会出现 F12，再按F12即可。

![](http://image.python-online.cn/20190616235007.png)

- 精准定位到某行：Windows（Ctrl+G），Mac（Command+G），如下图定位到第510行第9个字符处。

![](http://image.python-online.cn/20190616234038.png)


##  6.4 搜索时过滤测试文件

接下来，介绍一个，我看框架源码的时的一个小技巧，可能只适用一小部分人吧。

我平时会看的框架是 OpenStack ，我不知道其他框架是怎样的，但在 OpenStack 里面带有大量（真的很多）的单元测试文件。这给我在使用 `Find in Path`  时带来了不小的困扰，你可以从下图的搜索结果中感受一下，搜索一个函数，test 文件里的结果比 正常文件要多很多。

![](http://image.python-online.cn/FlXynbyxh8tTrCpc4tVLqycL7JQm)

这些测试文件的搜索结果，对于我们看源代码不仅没有任何帮助的，更重要的是还干扰视线。于是我就研究了一下，从文件名入手，只要在 `File mask` 里填写 `!test*` 可以将这些test文件过滤掉。搜索结果一下子清晰很多。

![](http://image.python-online.cn/FiD91PR1hUu0Ruc6cmZ7EGNM6Be_)


# 第七章：版本与管理

## 7.1 使用 Git 进行版本管理

点击 `VCS` -> `Git` -> `Clone`

![](http://image.python-online.cn/20191211100048.png)

填写git仓库相关信息

![](http://image.python-online.cn/20191211100657.png)

点击 `Test`，会尝试连接 git 服务器，中间会让你输入登陆的帐号和密码。

![](http://image.python-online.cn/20191211101706.png)

点击`OK` 后，若一切正常会提示连接成功。

![](http://image.python-online.cn/20191211101845.png)

点击 `OK` 后，PyCharm 需要你选择如何打开这个 Git 仓库目录，是在当前窗口中打开，还是新建一个窗口？

由于我在一个 PyCharm 下会有多个 Git 仓库，为了方便，我选择在当前窗口中打开（注意勾选 `Add to currently opened projects`）。

![](http://image.python-online.cn/20191211102501.png)

至此，Git 配置完成。

此时你可以 `VCS` -> `Git` 查看，发现之前这些灰色不可用的按钮都可以使用了。

![](http://image.python-online.cn/20191211102826.png)

本篇重在讲解 PyCharm 的配置，关于Git 的操作，不属于本篇重点，就不再展开讲了。

若你想对已配置的Git仓库进行修改，可点击 `File` -> `Setting` -> `Version Control` 调出如下界面。

![](http://image.python-online.cn/20191211133836.png)

不得不说 PyCharm 的这 UI 做得可以，随便改了个东西提交一下

![](http://image.python-online.cn/20191211143510.png)



## 7.2 快速查看 Git 的修改

如果你的项目在 git 的管理之下，在你修改了文件后，你会有很多种方法来查看自己到底修改了什么？

第一种当然是使用 git diff

![](http://image.iswbm.com/20200420085524.png)

第二种是使用之前写的 show history

![](http://image.iswbm.com/20200420090117.png)

第三种，也是今天要介绍的，是最简便，也是直接的方法。

在有文本变动的位置，PyCharm 会有提示，如下红色箭头标识处，点击它就可以直接查看，还可以快速回滚。

![](http://image.iswbm.com/20200420090428.png)


## 7.3 使用Git做版本控制

按照如下提示点击 Git 仓库配置

![](http://image.python-online.cn/20190507215525.png)

接着输入仓库地址

![](http://image.python-online.cn/20190507220101.png)

点击 Test，测试连通性，会要求输入密码

![](http://image.python-online.cn/20190419152120.png)

若一切顺利，则会看到如下界面

![](http://image.python-online.cn/20190419152145.png)

测试连接成功后，点击 Clone 就可以克隆下来了。

对于以前使用 Git 命令来管理的，现在可以直接使用 PyCharm 的菜单栏来操作，这些功能已经可以满足大多数人的日常需求了，应该是够用了。

![](http://image.python-online.cn/20190507220740.png)



## 7.4 文件差异，轻松比对

程序开发必备神器中，beyond compare 绝对可以排一号。

虽说好用，但这东西，是收费的。

如果是简单的单个文件的比对，其实可以使用PyCharm里自带的。

点击源文件，再点击`View` -> `Compare With …`  -> 选择目标文件

对比示例，可以查看下面这张图，UI做的还是挺好看的。

![](http://image.python-online.cn/20190721125739.png)



[PyCharm 使用技巧](https://blog.csdn.net/xiemanr/category_6928127.html)




# 附录

- [PyCharm 快捷键 Mac 版 ](https://resources.jetbrains.com/storage/products/pycharm/docs/PyCharm_ReferenceCard_mac.pdf)
- [PyCharm 快捷键 Win 版](https://resources.jetbrains.com/storage/products/pycharm/docs/PyCharm_ReferenceCard.pdf)
- [PyCharm Lanyu 注册码](http://idea.lanyus.com/)

---

![](http://image.iswbm.com/20200607174235.png)