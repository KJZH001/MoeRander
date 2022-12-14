<div align="center">
  
  <img src="https://img.cdn.loliloli.net/images/2022/12/26/ZhhH.png" alt="樱夜天惠" width="20%" />
  &ensp;
  <img src="https://img.cdn.loliloli.net/images/2022/12/26/Zbsx.png" alt="空梦logo" width="36%" />
  <br>
  <br>
   
<img src="https://img.cdn.loliloli.net/images/2022/12/26/Z4BT.png" alt="made-with-html5" width="20%" />
&ensp;
<img src="https://img.cdn.loliloli.net/images/2022/12/26/ZmXG.png" alt="cc-MIT+" width="36%" />
&ensp;
<img src="https://img.cdn.loliloli.net/images/2022/12/26/ZpYz.png" alt="chat-晓空blog" width="20%" />

---

<p>全开源 轻量级 响应式</p>
<p>一个简易的摇号抽奖程序</p>
<h3>†</h3>
<p>在这介于虚幻于现实之间，而又万物皆可萌的世界之中</p>
<p>彼此的相遇，又会带来怎样的奇迹呢</p>
<p>♢</p>

</div>

# MoeRander
> 你如果能看到这个Readme的话就不用去看'说明.txt'了2333

这是一个简单的摇号程序，使用html5进行编写，设计之初是作为一个云应用而存在的

原先是一个用于为自己学校班级开发的简易且美观实用的摇号程序，后由于学校的网络条件并不稳定，并且老师希望能够增加自定义班级成员内容的功能

因此转为同时支持离线打开，并且开始计划支持自定义摇号内容

另外，虽然这是一个摇号程序，但是实际上对于能摇的玩意没什么限制，如果你想的话用来当成抽奖机也并不是不行|ू･ω･` )

## 预览图片
![https://img.cdn.loliloli.net/images/2022/12/26/ZAJ4.png](https://img.cdn.loliloli.net/images/2022/12/26/ZAJ4.png)

## 在线DEMO
v1 [https://api.moeworld.top/MoeRand/v1](https://api.moeworld.top/MoeRand/v1) （已存档）

v2 [https://api.moeworld.top/MoeRand/v2](https://api.moeworld.top/MoeRand/v2) （请访问这个）

## 特性
- 支持自定内容
- 支持离线部署，必要时可脱离host环境独立运行于浏览器上
- 支持部署完为云应用运行（需要host环境）
- 美观！

# 许可协议
在使用本项目时，你需要遵守以下几点
1. 保留所有我们的署名，不论是否会显示在页面中，同时你也不可以将它刻意隐藏起来，但是如果你认为有必要的话，你可以将你的名字加到其他人的署名的后面去
2. 不允许一切商业行为上的使用，除非你征得了我的同意
3. 在本项目的基础上开发的项目或者使用到了本项目的部分代码的项目，必须完全开源且在项目的明显位置注明本仓库的地址（不论是否发布）
4. 对于在本项目上二次开发的衍生项目，项目名称或代号必须和本项目有关，且不得和本项目重名
5. 如果产生争议，则优先按照此处声明为准，对于未在此处声明的部分，则按照MIT协议为准
6. 我保留最终的解释权利

# 如何部署？

## 方法1 [最简单]下载完整仓库或Release
1. 在页面靠近右侧上面的地方有个绿色的Code按钮
2. 点击后展开的菜单中选择 Download ZIP
3. 下载后找个位置解压
或者你也可以
1. 来到[https://github.com/KJZH001/MoeRander/releases](https://github.com/KJZH001/MoeRander/releases)这个页面
2. 找到最顶上Assets中的Source code(zip)
3. 下载后找个位置解压

4. 请阅读下方的配置说明

## 方法2 [推荐]使用git bash进行快速部署
如果你连命令行或者git bash是什么都不知道的话就直接用上面的那个方法吧

在你希望部署的位置输入以下命令
```
git clone https://github.com/KJZH001/MoeRander/
```

## [重要]如何进行配置
你得到的文件中有一个名为config.js的东西，打开它

（请使用notepad++等专业编辑器，如果没有一定要用记事本的话请右键编辑打开）

里面有着很详细的说明，**请认真阅读并且修改，不要破坏原有的格式**

## 后续如何更新？
### 方法1安装的
备份config.js，然后重新执行方法1，将原有的config.js中的相应内容替换为你备份后的内容

请不要直接覆盖文件，因为后续更新可能会对部分内容产生结构性的修改

### 方法2安装的
```
cd MoeRander
git pull origin master
```
然后请自行合并代码冲突

# 怎么启动？（程序的入口在哪里）
部署目录下的'index.html'，使用你的浏览器打开即可

你也可以用它来部署在你的服务器上

# 自定义配置

## 如何修改背景图片？
修改'index.html'中的第33行（后续可能会发生改变）

格式为 'background: url(图片地址);'

图片地址可以是一个本地的图片的路径，或者是一个来自网络的图片直链

里面也内置了三个早期版本的背景图片

或者，你也可以选择直接替换static/background.png这个图片文件

支持什么格式的图片取决于你使用时的浏览器，通常 webp,png,jpg 都是可用的

*默认背景为天气之子*

## 修改标题
标题分别位于'index.html'中的13，45,46行（后续可能会发生改变）

修改时请注意保留我们和其他作者的署名

# 作者

晓空 [https://blog.moeworld.tech](https://blog.moeworld.tech)

Magma岩浆块 [https://magma.ink/](https://magma.ink/)

# 项目地址

[https://github.com/KJZH001/MoeRander](https://github.com/KJZH001/MoeRander)

#  鸣谢
Magma岩浆块提供的帮助

MDUI前端开发框架
