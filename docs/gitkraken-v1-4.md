# GitKraken v1.4 版-新功能

> 原文：<https://www.gitkraken.com/blog/gitkraken-v1-4>

最新的 [GitKraken](https://www.gitkraken.com/) 版本包括三个功能，帮助你的界面保持整洁。这比在你妈妈宣布最后一分钟来访之前，把你所有的东西都扔在床下，把你所有的脏盘子都塞进洗碗机要好。

这种释放就像你不必折叠的干净衣物的香味一样令人耳目一新(这是一种额外的清新)。

## **命令面板:有序安全**

可以将命令调板想象成类似于模糊查找器，但是它是针对那些实际上会影响当前存储库的命令的。“有了 Fuzzy Finder，一切都是为了打开或改变视图；打开设置；正在打开文件历史记录；或者进行回购，”Axosoft 的开发人员何塞·加西亚解释道。“但是命令面板有撤销、重做、创建分支或隐藏等选项，所有这些命令都会影响您当前的项目。”

点击`⌘+ Shift + P` (Mac)或`Ctrl + Shift + P` (Windows/Linux)，命令面板就会神奇地出现，就像一群准备拖地的精灵。说“Bippity Boppity Boo”，你就能触发影响你回购的行动。

*在 GitKraken* 中看到的命令面板的动作

Garcia 和他的团队决定将模糊查找器功能和命令面板功能分开，因为当开发人员处于状态时，他们的手指打字很快。

“例如，如果我想打开一个文件名为 GitKraken 的东西，可能会有一个名称中带有 GitKraken 的‘打开’或‘签出分支’，”Garcia 继续说道。“如果我只是在打字，在浏览的时候快速地按下回车键，我可能会不小心碰到我看到的第一个选项，”他说。

> 我们明确地让使用常规模糊查找器的人知道这根本不会影响你的项目。都是安全的，会单独开一个面板。
> 
> – Jose Garcia, Developer

这项工作是 GitKraken 团队的开发人员想要着手进行的，因为他们想让 Fuzzy Finder 更加强大。“团队正在讨论是否要增加这个新选项，因为我们不希望人们意外地做错事，”Garcia 解释道。

经过多次讨论，团队简单地决定将面板分成两类:1)不会影响您当前项目的命令和 2)会影响您当前项目的命令。

“关键是要快速访问命令或页面。模糊查找器和命令面板都在旁边的一个小盒子里打开(如果你愿意，也可以是面板)。”干净、整洁、安全——和你煮完意大利面后的厨房正好相反。

## 壁球:给自己一个新的开始

壁球是一种你在室内用球拍玩的游戏，也是你弟弟用来杀虫子的一种方式。这也是一种在 Git 中清理提交的方法；该功能现已被引入 GitKraken。

Axosoft 的开发人员凯尔·史密斯(Kyle Smith)说:“Squash 把提交放在一起。你可以用它来清理你的历史，或者更简洁地描述你所做的事情，例如，在处理一个特性时，你做了许多中间提交，但是当完成时，你想把这个特性表示为一个单独的提交

他解释说，一些人的思维过程可能是，“如果这一系列的提交变成一个，我的历史会更清楚。”

*在吉克拉肯*看到的南瓜

一旦提交被压缩，GitKraken 会将这些提交压缩到当前分支的历史中。像洗窗户一样看着它，这样你就能清楚地看到里面的好东西。不再有灰尘、污垢和死苍蝇:这些东西会模糊你的视线，而且没有必要。

当你粉碎一个承诺时，最好的事情之一是没有任何风险，即使它听起来如此…永久(并且有点可怕)。不像在重建的 CB550 上跳下悬崖或不戴摩托车头盔，如果你挤压并意识到这些提交更适合作为单独的提交，你可以通过几次点击撤销按钮来实现。“所以放松点。

“很多时候，人们的工作流程会在任何功能中包含一个检查点。因此，如果他们最近搞砸了一次提交，他们可以返回到那个检查点。史密斯解释说:“一旦他们完成了工作，对工作感到满意，他们就会崩溃。”

他进一步解释说，squash 将获取 Squash 中每次提交的 diff 和 commit 消息，并将它们组合在一起，这样您仍然可以获得关于您在一段时间内所做的事情的有价值的信息。

## **无快进:按你想要的方式合并**

大多数人有不同的清洁方法。有些人只是抓起一个容器的彗星，并开始擦洗，其他人有条不紊地使用喷雾清洁剂，有擦洗泡沫，并声称在擦洗之前做的工作。

在一天结束时，这两种方法通常会给你相同的结果-一个干净的表面。这只是两种不同工作的两种方法。和 Git 里合并不快进和快进差不多。差不多了。

Axosoft 的开发人员泰勒瓦内克(Tyler Wanek)表示:“一个被大量要求的功能是不要快进。“有几种不同类型的合并，”他解释道。有快进和不快进。

在此版本之前，GitKraken 会尽可能自动快进您的合并。但是有些人发现不快进的合并是有用的。Wanek 解释说:“如果你进行快进，你只需将你的分支指针移动到从你的分支派生出来的另一个分支的顶部。

“不合并快进意味着，即使您的分支是另一个分支的父分支，当我们想要将另一个分支合并回来时，我们正在进行新的提交。不同之处在于，它保留了那些提交被合并到一个分支的时间。”

*在 GitKraken* 合并没有快进

查看我们的[发行说明](https://www.gitkraken.com/release-notes)，看看 GitKraken v1.4 版本中还有什么新内容。你的代码将是干净的、安全的，并且有希望是功能性的(但这取决于你)。