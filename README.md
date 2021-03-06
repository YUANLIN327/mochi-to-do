# Mochi To Do

![Mochi](http://www.feathersnfurshoppe.com/images/smallanimaldocs/Hamster.gif)

这是在波士顿「燎原」办公室举办的于 2016 年 5 月开始的 **「燎原」全栈工程师加速班** 系列活动使用的示例项目。它目前使用 [AngularJS](https://thinkster.io/a-better-way-to-learn-angularjs) 和 [Node.js](https://nodejs.org/en/download/) 完成了如下功能：

1. 当有待办事项存在时，我希望能看到待办事项列表。
2. 当我输入文字并使用回车确认时，我希望新输入的待办事项项目显示在列表中。
3. 当我点击待办事项左侧的 Checkbox 时，待办事项应该标示为已完成。
4. 当我点击已完成待办事项左侧的 Checkbox 时，待办事项应该标示为未完成。
5. 当我点击待办事项右侧的「&times;」按钮时，待办事项应当被删除。
6. 当我在不同的浏览器打开应用时，应该看到相同的待办事项。

要运行这个项目，请确保本地成功安装了 [Node.js](https://nodejs.org/en/download/)、[NPM](https://docs.npmjs.com/getting-started/installing-node) 和 [Bower](https://www.npmjs.com/package/bower#install)。然后：

    git clone https://github.com/liaoyuan-io/mochi-to-do
    cd mochi-to-do/server
    npm install
    node index.js
    cd ../web
    bower install
    open index.html

然后你就可以在浏览器中运行本项目了。


## 有什么联系方式吗？

有。扫描以下二维码入群，和其他参与者交流。后续活动安排也会在群内优先发布。

![二维码](qr.png?raw=true)


## 这一系列活动的安排是怎样的？

本系列活动是帮助具备一定编程基础的计算机相关专业学生、爱好者接触现今流行的全栈开发技术，探索开源社区的入门导引。暂定每两周一次，持续约 3 个月。


#### 目前已经举办过的三次内容如下：

- **2016年5月24日** HTML/CSS 基础、版本控制。本次活动以讲座形式进行。使用一个示例，介绍了 HTML 文档的基本结构，CSS 布局、优先级，SCSS 基本结构等；并以 Git/GitHub 为例演示了版本控制对软件开发的帮助。
- **2016年6月7日** Workshop：用 AngularJS 写简单的 To Do List 应用。本次活动以 Workshop 形式进行。使用 Mochi To Do 作为示例，引导参与者体验了安装 Git、Node、NPM、Bower 等工具，并一步一步使用 AngularJS 开发出项目的全过程。
- **2016年6月21日** Workshop：用 Express 搭建后端 RESTful API。本次活动以 Workshop 形式进行。使用 Mochi To Do 作为示例，引导参与者体验了 RESTful API 设计、Express 开发，以及使用 AngularJS 调用 API 的全过程。


#### 即将在7月5日举办的活动内容如下：

**Workshop：用 [React Native](https://facebook.github.io/react-native/) 打造 iOS 应用，随时随地刷 To Do！**

涉及内容包括 React Native 开发环境配置、项目生成、调试和开发等；并简要介绍 XCode、iOS Simulator 的使用；以及 Push Notification 等移动端常用模式。

*前置要求*

1. 自带电脑，最好是 Mac。
2. 在本地安装好 Git、NodeJS、NPM。
3. 将 Mochi To Do 应用 Fork，并 Clone 至本地，且成功运行。
4. 在自己的 Mac 电脑上安装 [XCode](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)，且成功运行。

请参考 [Mochi To Do](https://github.com/liaoyuan-io/mochi-to-do) 以完成以上任务。本次活动中，我们将形成两人一组的小团队，协同完成开发任务。现场将有4名助教，更多力量手把手指导。


#### 未来的活动内容预计包括：

- Workshop：如何测试你的应用程序。需要自带电脑。
- 应用客户端及服务端部署、分发。云服务。如何 Scale。
- 其它任何你想了解的内容，请联系我们。