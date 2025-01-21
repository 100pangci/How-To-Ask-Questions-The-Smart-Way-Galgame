# 提问的智慧-Galgame版
> **How To Ask Questions The Smart Way**
>
> Copyright © 2001,2006,2014 Eric S. Raymond, Rick Moen
>
> 本指南英文版版权为 Eric S. Raymond, Rick Moen 所有。
>
> 原文网址：[http://www.catb.org/~esr/faqs/smart-questions.html](http://www.catb.org/~esr/faqs/smart-questions.html)
>
> Copyleft 2001 by D.H.Grand(nOBODY/Ginux), 2010 by Gasolin, 2015 by Ryan Wu
>
> 本中文指南是基于原文 3.10 版以及 2010 年由 [Gasolin](https://github.com/gasolin) 所翻译版本的最新翻译；
>
> 协助指出翻译问题，**请[发 issue](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/issues/new)，或直接[发 pull request](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/compare) 给我。**
>
> 本文另有[繁體中文版](README.md)。
>

**上述文本为原中文翻译版本附带说明，感谢你们的翻译**

**[此项目另有PDF版本](https://github.com/100pangci/How-To-Ask-Questions-The-Smart-Way-Galgame/blob/main/%E6%8F%90%E9%97%AE%E7%9A%84%E6%99%BA%E6%85%A7-Galgame%E7%89%88.pdf)**

**原版修改参考：https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way**

**本Galgame版修改者：百分百原味胖次**



## [原文版本历史](history.md)

## 目录
  * [声明](#声明)
  * [简介](#简介)
  * [在提问之前](#在提问之前)
  * [当你提问时](#当你提问时)
    * [慎选提问的场合](#慎选提问的场合)
    * [使用有意义且描述明确的标题](#使用有意义且描述明确的标题)
    * [使用清晰、正确、精准且合乎语法的语句](#使用清晰正确精准且合乎语法的语句)
    * [精确地描述问题并言之有物](#精确地描述问题并言之有物)
    * [话不在多而在精](#话不在多而在精)
    * [低声下气不能代替你的功课](#低声下气不能代替你的功课)
    * [描述问题症状而非你的猜测](#描述问题症状而非你的猜测)
    * [按发生时间先后列出问题症状](#按发生时间先后列出问题症状)
    * [描述目标而不是过程](#描述目标而不是过程)

    * [去掉无意义的提问句](#去掉无意义的提问句)
    * [即使你很急也不要在标题写```紧急```](#即使你很急也不要在标题写紧急)
    * [礼多人不怪，而且有时还很有帮助](#礼多人不怪而且有时还很有帮助)
    * [问题解决后，加个简短的补充说明](#问题解决后加个简短的补充说明)
  * [如何解读答案](#如何解读答案)
    * [如果还是搞不懂](#如果还是搞不懂)
    * [处理无礼的回应](#处理无礼的回应)
  * [如何避免扮演失败者](#如何避免扮演失败者)
  * [不该问的问题](#不该问的问题)
  * [好问题与蠢问题](#好问题与蠢问题)
  * [如果得不到回答](#如果得不到回答)
  * [如何更好地回答问题](#如何更好地回答问题)
  * [鸣谢](#鸣谢)



## 声明

如果您甚至都**懒得读完**这篇文章，那么你不适合玩 **Galgame** ，更没有资格提出任何问题。建议您去刷**抖音，快手短视频**。
或者直接去问**GPT**，并且不要把问题贴我们的脸上。

如果你因寻求某些帮助而阅读本指南，并在离开时还觉得可以从本文作者这里得到直接帮助，那你多少不带脑子。别问我们问题，我们只会忽略你。我们在这本指南中想教你如何从 Galgame 领域大神那里取得协助，而 99% 的情况下那不会是我们。除非你确定本指南的作者之一刚好是你所遇到的问题领域的专家，否则请不要打扰我们，这样大家都会开心一点。



## 简介

本指南将教你如何正确地提问你在游玩中所产生的问题以获得你满意的答案。

现在 Galgame 游戏已经相当出圈，您通常可以从发布者那里直接获得无问题的游戏资源，这是件**好事**；和发布者相比，网络群组或论坛群组里的热心网友们往往对那些新手常遇到的问题更宽容一些。尽管如此，以我们在此推荐的方式对待这些有经验的用户通常也是从他们那里获得有用答案的最有效方式。

我们不讳言我们对那些不愿思考、或者在发问前不做他们该做的事的人的蔑视。那些人是时间杀手 —— 他们只想索取，从不付出，消耗我们可用在更值得回答的人身上的时间。我们称这样的人为 `失败者（loser）` （由于历史原因，我们有时把它拼作 `lusers`）。

我们（在很大程度上）是自愿的，从繁忙的生活中抽出时间来解答疑惑，而且时常被提问淹没。所以我们无情地滤掉一些话题，特别是拋弃那些看起来像失败者的家伙，以便更高效地利用时间来回答`赢家（winner）`的问题。

如果你厌恶我们的态度，觉得我们高高在上，或过于傲慢，不妨也设身处地想想。我们并没有要求你向我们屈服 —— 事实上，我们大多数人非常乐意与你平等地交流，只要你付出小小努力来满足基本要求，我们就会欢迎你加入我们的文化。但让我们帮助那些不愿意帮助自己的人是没有效率的。无知没有关系，但装白痴就是不行。

你不必在技术上很在行才能吸引我们的注意，但你必须表现出能引导你变得在行的特质 —— 机敏、有想法、善于观察、乐于主动参与解决问题。如果你做不到这些使你与众不同的事情，我们建议你花点钱找个导购付费，让他帮你处理；而不是要求群友和坛友个人无偿地帮助你。

如果你决定向我们求助，当然你也不希望被视为失败者，更不愿成为失败者中的一员。能立刻得到快速并有效答案的最好方法，就是像赢家那样提问 —— 聪明、自信、有解决问题的思路，只是偶尔在特定的问题上需要获得一点帮助。



## 在提问之前

在你准备要通过网络群组或论坛提出技术问题前，请先做到以下事情：

  1. 尝试上网搜索以找到答案。
  2. 尝试阅读资源发布者留下的说明信息以找到答案。
  3. 尝试自己检查或试验以找到答案。
  4. 向你身边的 Galgame 大神朋友打听以找到答案。

当你提出问题的时候，请先表明你已经做了上述的努力；这将有助于树立你并不是一个不劳而获且浪费别人的时间的提问者。如果你能一并表达在做了上述努力的过程中所**学到**的东西会更好，因为我们更乐于回答那些表现出能从答案中学习的人的问题。

运用某些策略，比如先用 哔哩哔哩 、 Google 、 Bing 、QQ群 或 百度贴吧 搜索你所遇到的各种错误信息或你所需要的教程，这样很可能直接就找到了能解决问题的线索。即使没有结果，在你所提问的群组或论坛寻求帮助时加上一句 `我在 哔哩哔哩、 Google 、 Bing 、QQ群 或 百度贴吧 中搜过下列句子但没有找到什么有用的东西` 也是件好事，即使它只是表明了搜索引擎不能提供哪些帮助。这么做（加上搜索过的字串）也让遇到相似问题的其他人能被搜索引擎引导到你的提问来。

别着急，不要指望几秒钟的搜索就能解决一个复杂的问题。在向专家求助之前，再阅读一下资源发布者留下的说明信息、放轻松、坐得舒服一些，再花点时间思考一下这个问题。相信我们，他们能从你的提问看出你做了多少阅读与思考，如果你是有备而来，将更有可能得到解答。不要将所有问题一股脑拋出，只因你的第一次搜索没有找到答案（或者找到太多答案）。

准备好你的问题，再将问题仔细地思考过一遍，因为草率的发问只能得到草率的回答，或者根本得不到任何答案。越是能表现出在寻求帮助前你为解决问题所付出的努力，你越有可能得到实质性的帮助。

小心别问错了问题。如果你的问题基于错误的假设，脾气暴躁的群友和坛友多半会一边在心里想着`傻卵问题…`，一边用无意义的字面解释来答复你，希望着你会从问题的回答（而非你想得到的答案）中汲取教训。

绝不要自以为**够格**得到答案，你没有；你并没有。毕竟你没有为这种服务支付任何报酬。你将会是自己去**挣到**一个答案，至少要提出一个能详细描述自己遇到了什么的问题。而不仅仅是被动地从他人处索取问题解决的具体方法。

另一方面，表明你愿意在找答案的过程中做点什么是一个非常好的开端。`谁能给点提示？`、`我的这个截图截全了吗？`以及`我应该检查什么地方`比`请把我需要的具体过程发给我`更容易得到答复。因为你表现出只要有人能指个正确方向，你就有完成它的能力和决心。



## 当你提问时

### 慎选提问的场合

小心选择你要提问的场合。如果你做了下述的事情，你很可能被当成傻逼（请举一反三）：

* 在二游群里提问千恋万花为什么打不开。
* 在Galgame技术群里探讨如何解压7z分卷。
* 一个问题问出来没人理你反复提问。
* 向既非熟人也没有义务解决你问题的人发送私信。
* 认为别人就应该给我回答。


因此，第一步是找到对的网络群组或论坛。再说一次，哔哩哔哩、Google 和其它搜索引擎还是你的朋友，用它们来找到与你遭遇到困难的问题最相关的网站。通常那儿都有一些相同的案例可以供你使用。

向群内陌生人私信或给论坛的私人账户发送邮件最可能是风险最大的事情。举例来说，别假设一个提供免费Galgame资源的作者会想充当你的免费顾问。不要对你的问题是否会受到欢迎做太乐观的估计 —— 如果你不确定，那就向别处发送，或者压根别发。

别像机关枪似的一次“扫射”所有的帮助渠道，这就像大喊大叫一样会使人不快。要一个一个地来。

搞清楚你的主题！如果你都让别人搞不清楚你是拿手机还是电脑玩的 Galgame ，那建议你不要提问浪费别人的时间。

可以理解的是，一些 Galgame 发布者正在接受过多的错发信息。就像那根最后压垮骆驼背的稻草一样，你的加入也有可能使情况走向极端 —— 可能让他厌倦发布本身。


### 使用有意义且描述明确的标题

在群组或论坛中，大约 50 字以内的标题是抓住别人注意力的好机会。别用喋喋不休的`有没有大神`、`在吗`、`急`（更别说`九敏！！！！`这样让人反感的话，用这种标题会被条件反射式地忽略）来浪费这个机会。不要妄想用你的痛苦程度来打动我们，而应该是在这点空间中使用极简单扼要的描述方式来提出问题。

一个好标题范例是`目标 —— 差异`式的描述，许多技术支持组织就是这样做的。在`目标`部分指出是哪一个或哪一组东西有问题，在`差异`部分则描述与期望的行为不一致的地方。


> 傻逼问题：救命啊，我的 Galgame 打不开了！

> 聪明问题：我在XX网站上下的 XX作品打不开，在手机上用XX模拟器，XX渲染器闪退

> 更聪明问题：我在XX网站上下的 XX作品打不开，在手机上用XX模拟器，XX渲染器 - 点击启动它黑屏过几秒后闪退了。

编写`目标 —— 差异` 式描述的过程有助于你组织对问题的细致思考。是什么游戏打不开？ 是因为模拟器还是因为渲染问题？是不是只在XX网站上的资源会出现这个问题？一个资深玩家只需瞄一眼就能够立即明白你你遇到的问题。

在网页论坛上，好的提问方式稍有不同，因为讨论串与特定的信息紧密结合，并且通常在讨论串外就看不到里面的内容，故通过回复提问，而非改变标题是可接受的。不是所有论坛都允许在回复中出现分离的标题，而且这样做了基本上没有人会去看。不过，通过回复提问，这本身就是暧昧的做法，因为它们只会被正在查看该标题的人读到。所以，除非你**只想**在该讨论串当前活跃的人群中提问，不然还是另起炉灶比较好。


### 使用清晰、正确、精准且合乎语法的语句

我们从经验中发现，粗心的提问者通常也会粗心地思考（我敢打包票）。回答粗心大意者的问题很不值得，我们宁愿把时间耗在别处。

正确的拼写、标点符号和大小写是很重要的。一般来说，如果你觉得这样做很麻烦，不想在乎这些，那我们也觉得麻烦，不想在乎你的提问。花点额外的精力斟酌一下字句，用不着太僵硬与正式。但它**必须很**准确，而且有迹象表明你是在思考和关注问题。

错误案例：

> 有无打捞有AB资源
> 给我一个QL呗？
> 下直装哪里？
> 解压打不开。


### 精确地描述问题并言之有物

* 仔细、清楚地描述你的问题的症状。
* 描述问题发生的环境（如，手机，电脑，系统版本）
* 描述在提问前你是怎样去研究和理解这个问题的。
* 描述在提问前为确定问题而采取的诊断步骤。
* 描述最近做过什么可能相关的硬件或软件变更。（如，更新系统，从MIUI到澎湃OS）

尽量去揣测群友和坛友会怎样反问你，在你提问之前预先将他们可能提出的问题回答一遍。

### 话不在多而在精

你需要提供精确有内容的信息。这并不是要求你简单的把成堆的出错代码或者资料完全转录到你的提问中。如果你有庞大而复杂的测试样例能重现程序挂掉的情境，尽量将它剪裁得越小越好。

这样做的用处至少有三点。
第一，表现出你为简化问题付出了努力，这可以使你得到回答的机会增加；
第二，简化问题使你更有可能得到**有用**的答案；
第三，在精炼你的报告的过程中，你很可能就自己找到了解决方法或权宜之计。


### 低声下气不能代替你的功课

有些人明白他们不该粗鲁或傲慢的提问并要求得到答复，但他们选择另一个极端 —— 低声下气：`我一个小白……啥也不懂，你让我干这个我也不清楚啊。`这既使人困扰，也没有用，尤其是伴随着与实际问题含糊不清的描述时更令人反感。

别用原始灵长类动物的把戏来浪费你我的时间。取而代之的是，尽可能清楚地描述背景条件和你的问题情况。这比低声下气更好地定位了你的位置。

有时网页论坛或群组会设有专为新手提问的版面/新群，如果你真的认为遇到了初学者的问题，到那去就是了，但一样别那么低声下气。

### 描述问题症状而非你的猜测

告诉大家你认为问题是怎样造成的并没什么帮助。（如果你的推断如此有效，还用向别人求助吗？），因此要确信你原原本本告诉了他们问题的症状，而不是你的解释和理论；让群友或坛友来推测和诊断。如果你认为陈述自己的猜测很重要，清楚地说明这只是你的猜测，并描述为什么它们不起作用。

**蠢问题**

> 我用这个密码怎么解压不了。
> 我觉得应该是你发的这个叫密码的东西，里面的网址点开里面就包含密码吧。

**聪明问题**

> 我刚才用手机尝试了群里的密码，尝试XX软件，XX软件，XX软件把密码输入进去，均提示密码错误。
> 好像密码的确错误了，请问这个密码真的正确吗？链接内的文件好像换源了。

由于以上这点似乎让许多人觉得难以配合，这里有句话可以提醒你：`所有的诊断专家都来自密苏里州。` 美国国务院的官方座右铭则是：`让我看看`（出自国会议员 Willard D. Vandiver 在 1899 年时的讲话：`我来自一个出产玉米，棉花，牛蒡和民主党人的国家，滔滔雄辩既不能说服我，也不会让我满意。我来自密苏里州，你必须让我看看。`） 针对诊断者而言，这并不是一种怀疑，而只是一种真实而有用的需求，以便让他们看到的是与你看到的原始证据尽可能一致的东西，而不是你的猜测与归纳的结论。所以，大方地展示给我们看吧！

### 按发生时间先后列出问题症状

问题发生前的一系列操作，往往就是对找出问题最有帮助的线索。因此，你的说明里应该包含你的操作步骤，以及软件的反应，直到问题发生。

如果你的说明很长（如超过四个段落），在开头简述问题，接下来再按时间顺序详述会有所帮助。这样群友和坛友在读你的记录时就知道该注意哪些内容了。

### 描述目标而不是过程

如果你想弄清楚如何做某事（而不是报告一个 Bug），在开头就描述你的目标，然后才陈述重现你所卡住的特定步骤。

经常寻求技术帮助的人在心中有个更高层次的目标，而他们在自以为能达到目标的特定道路上被卡住了，然后跑来问该怎么走，但没有意识到这条路本身就有问题。结果要费很大的劲才能搞定。

**蠢问题**
> 我该怎么在 Galgame 里自制黄油？

**聪明问题**

> 我正在尝试在 Galgame 里添加自制的剧本。
> 但我无法解包，并将文本加入到游戏中，演出效果可以像原版一样。

第二种提问法比较聪明，你可能得到像是```建议直接用其他引擎移植```之类的意见


### 去掉无意义的提问句

避免用无意义的话结束提问，例如`那大佬能帮帮我吗？`或者`那你说这怎么解决？`。

首先：如果你对问题的描述不是很好，这样问更是画蛇添足。

其次：由于这样问是画蛇添足，群友和坛友们会很厌烦你 —— 而且通常会用逻辑上正确，但毫无意义的回答来表示他们的蔑视， 例如：`不行😋`或者`您另寻高就吧`。

一般来说，避免用 `是或否`、`对或错`、`有或没有`类型的问句，除非你想得到[是或否类型的回答](https://strcat.de/questions-with-yes-or-no-answers.html)。

### 即使你很急也不要在标题写`紧急`

这是你的问题，不是我们的。宣称`紧急`极有可能事与愿违：大多数人会直接删除无礼和自私地企图即时引起关注的问题。

有半个例外的情况是，如果你是在一些很高调，会使群友或者坛友们兴奋的地方，也许值得这样去做。在这种情况下，如果你有时间压力，也很有礼貌地提到这点，人们也许会有兴趣回答快一点。

如果你觉得这点很不可思议，最好再把这份指南剩下的内容多读几遍，直到你弄懂了再发文。

### 礼多人不怪，而且有时还很有帮助

彬彬有礼，多用`请`和`谢谢`。让大家都知道你对他们花时间免费提供帮助心存感激。

坦白说，这一点并没有比使用清晰、正确、精准且合乎语法和避免使用专用格式重要（也不能取而代之）。

然而，如果你有一串的问题待解决，客气一点肯定会增加你得到有用回应的机会。

我们的建议是要么先说`先谢了`，然后事后再对回复者表示感谢，或者换种方式表达感激，譬如用`谢谢你的关注`或`谢谢你的关照`。

### 问题解决后，加个简短的补充说明

问题解决后，向所有帮助过你的人发个说明，让他们知道问题是怎样解决的，并再一次向他们表示感谢。

最理想的方式是向最初提问的话题回复此消息，并在信息中包含`已修正`，`已解决`或其它同等含义的明显标记。在人来人往的群聊或者论坛里，一个看见讨论串`问题 X`和`问题 X - 已解决`的潜在回复者就明白不用再浪费时间了（除非他个人觉得`问题 X`有趣）。

补充说明不必很长或是很深入；简单的一句`你好，原来是我的模拟器出了问题！谢谢大家。`比什么也不说要来的好。事实上，除非结论真的很有技术含量，否则简短可爱的小结比长篇大论更好。说明问题是怎样解决的，但大可不必将解决问题的过程复述一遍。

除了有礼貌和有内涵以外，这种类型的补充也有助于他人在群组/论坛中搜索到真正解决你问题的方案，让他们也从中受益。

至少，这种补充有助于让每位参与协助的人因问题的解决而从中得到满足感。如果你自己不是 Galgame领域大神 ，那就相信我们，这种感觉对于那些你向他们求助的大师或者专家而言，是非常重要的。问题悬而未决会让人灰心；群友和坛友们渴望看到问题被解决。好人有好报，满足他们的渴望，你会在下次提问时尝到甜头。

思考一下怎样才能避免他人将来也遇到类似的问题，自问写一份文件或加个常见问题（FAQ）会不会有帮助。如果是的话就将它们发给资源发布者。

这种良好的后继行动实际上比传统的礼节更为重要，也是你如何透过善待他人而赢得声誉的方式，这是非常有价值的资产。



## 如何解读答案

### 如果还是搞不懂

如果你看不懂回应，别立刻要求对方解释。像你以前试着自己解决问题时那样（利用手册，说明，网络，身边的高手），先试着去搞懂他的回应。如果你真的需要对方解释，记得表现出你已经从中学到了点什么。

比方说，如果我回答你：`看来似乎是 渲染器问题 改一下软件渲染就行了。`，然后，这是一个**很糟的**后续问题回应：`渲染器 是什么？` **好**的问法应该是这样：`嗯……请问渲染器是这里的哪一项？（并提供截图）`；`或者可以尝试自己看设置解决`

### 处理无礼的回应

很多 Galgame 圈子中看似无礼的行为并不是存心冒犯。相反，它是直截了当，一针见血式的交流风格，这种风格更注重解决问题，而不是使人感觉舒服而却模模糊糊。

如果你觉得被冒犯了，试着平静地反应。如果有人真的做了出格的事，邮件列表、新闻群组或论坛中的前辈多半会招呼他。如果这**没有**发生而你却发火了，那么你发火对象的言语可能在Galgame 圈子中看起来是正常的，而**你**将被视为有错的一方，这将伤害到你获取信息或帮助的机会。

另一方面，你偶尔真的会碰到无礼和无聊的言行。与上述相反，对真正的冒犯者狠狠地打击，用犀利的语言将其驳得体无完肤都是可以接受的。然而，在行事之前一定要非常非常的有根据。纠正无礼的言论与开始一场毫无意义的口水战仅一线之隔，群友和坛友们自己莽撞地越线的情况并不鲜见。如果你是新手或外人，避开这种莽撞的机会并不高。如果你想得到的是信息而不是消磨时光，这时最好不要把手放在键盘上以免冒险。

在下一节，我们会谈到另一个问题，当**你**行为不当时所会受到的`冒犯`。



## 如何避免扮演失败者

在Galgame 圈子中，你以本指南所描述的或类似的方式，可能会有那么几次搞砸了。而你会在公开场合中被告知你是如何搞砸的，也许攻击的言语中还会带点夹七夹八的颜色。

这种事发生以后，你能做的最糟糕的事莫过于哀嚎你的遭遇、宣称被言语攻击、要求道歉、高声尖叫、憋闷气、威胁诉诸法律、向其雇主报怨、不去关马桶盖等等。相反地，你该这么做：

熬过去，这很正常。事实上，它是有益健康且合理的。

社区的标准不会自行维持，它们是通过参与者积极而**公开地**执行来维持的。不要哭嚎所有的批评都应该通过私下的邮件传送，它不是这样运作的。当有人评论你的一个说法有误或者提出不同看法时，坚持声称受到个人攻击也毫无益处，这些都是失败者的态度。

也有其它的网络论坛或群组，受过高礼节要求的误导，禁止参与者张贴任何对别人帖子挑毛病的消息，并声称`如果你不想帮助用户就闭嘴。` 结果造成有想法的参与者纷纷离开，这么做只会使它们沦为毫无意义的唠叨与无用的地方。

夸张的讲法是：你要的是“友善”（以上述方式）还是有用？两个里面挑一个。

记着：当别人说你搞砸了，并且（无论多么刺耳）告诉你别再这样做时，他正在为关心**你**和**他的社群**而行动。对他而言，不理你并将你从他的生活中滤掉更简单。如果你无法做到感谢，至少要表现得有点尊严，别大声哀嚎，也别因为自己是个有戏剧性超级敏感的灵魂和自以为有资格的新来者，就指望别人像对待脆弱的洋娃娃那样对你。

有时候，即使你没有搞砸（或者只是在他的想像中你搞砸了），有些人也会无缘无故地攻击你本人。在这种情况下，抱怨倒是**真的**会把问题搞砸。

这些来找麻烦的人要么是毫无办法但自以为是专家的不中用家伙，要么就是测试你是否真会搞砸的心理专家。其它读者要么不理睬，要么用自己的方式对付他们。这些来找麻烦的人在给他们自己找麻烦，这点你不用操心。

也别让自己卷入口水战，最好不要理睬大多数的口水战 —— 当然，这是在你检验它们只是口水战，并且未指出你有搞砸的地方，同时也没有巧妙地将问题真正的答案藏于其后（这也是有可能的）。



## 不该问的问题

以下是几个经典蠢问题，以及我们没回答时心中所想的：

问题：[我能在哪找到 X 资源？](#q1)

问题：[RAR的游戏怎么玩？](#q2)

问题：[怎么激活？](#q3)

问题：[网盘地址在哪？](#q4)

问题：[后缀名7z一般是什么模拟器？](#q5)

问题：[用QQ浏览器解压怎么打不开啊？](#q6)

问题：[密码是中文吗？](#q7)

问题：[找不到下载路径啊？](#q8)

问题：[全年龄怎么没有H桥段？](#q9)

**以上问题均出自Q群聊天记录**

---

<a id="q1"></a>

> 问题：我能在哪找到  X 资源？

回答：（一看是千恋万花）烂大街的东西难道还有人不会搜？

<a id="q2"></a>
> 问题：RAR的游戏怎么玩？

回答：你可以尝试给RAR公司付费。

<a id="q3"></a>
>问题：怎么激活？

回答：你看来需要激活激活自己的大脑。

<a id="q4"></a>
> 问题：网盘地址在哪？

回答：在你的心里。

<a id="q5"></a>
> 问题：后缀名7z一般是什么模拟器？

回答：这TM什么问题。

<a id="q6"></a>
> 问题：用QQ浏览器解压怎么打不开啊？

回答：你用垃圾糟粕能打开就有鬼了。

<a id="q7"></a>
> 问题：密码是中文吗？

回答：其实是俄文，日文，法文，德文，就不是中文。

<a id="q8"></a>
> 问题：找不到下载路径啊？

回答：玩手机玩傻了。

<a id="q9"></a>
> 问题：全年龄怎么没有H桥段？

回答：你脑袋怎么是尖尖的。



## 好问题与蠢问题

最后，我将透过举一些例子，来说明怎样聪明的提问；同一个问题的两种问法被放在一起，一种是愚蠢的，另一种才是明智的。


**蠢问题**：

> 我可以在哪儿找到关于 千恋万花 的资料？

这种问法无非想得到 STFW （草泥马的滚去搜索引擎）这样的回答。

**聪明问题**：

> 我用 Google 搜索过 "千恋万花"，但是没找到有用的结果。谁知道上哪儿去找这个 Galgame 的资料？

这个问题已经 STFW 过了，看起来他真的遇到了麻烦。

**蠢问题**：

> 我从XX网项目找来的游戏没法打开。它怎么这么垃圾？

他觉得都是别人的错，这个傲慢自大的提问者。

**聪明问题**：

> 我从XX网找来的XXXXX电脑游戏，它在Windows XX环境下，弹出报错，显示“XXXXXXXXXXX”，我在网上搜了一下没有找到详细教程，请问是缺少了什么吗？我尝试过使用英文路径。

提问者已经指明了运行环境，也搜索过了，还列出了错误，还尝试着自己解决，并且他没有把问题的责任推到别人头上，他的问题值得被关注。


**蠢问题**：

> 怎么没人帮我解决游戏打开闪退的问题？

`好的，还需要我当你爹吗 ` 屏蔽。

**聪明问题**：

> 我在 XX网找的XXXX Winlator游戏，它在我的安卓XX手机上启动失败并且闪退，我用的模拟器版本是XXXX，渲染模式用的XXXX，手机处理器是骁龙，装了DXVK，请问有没有人可以帮我看一眼？谢谢。

这个家伙，从另一个角度来看，值得去回答他。他表现出了解决问题的能力，而不是坐等天上掉答案。

在最后一个问题中，注意`告诉我答案`和`给我启示，指出我还应该做什么诊断工作`之间微妙而又重要的区别。

通过我的提问方法，我给了别人可以咀嚼玩味的东西；我设法让人们很容易参与并且被吸引进来。我显示了自己具备和他们同等的能力，并邀请他们与我共同探讨。通过告诉他们我所走过的弯路，以避免他们再浪费时间，我也表明了对他们宝贵时间的尊重。



## 如果得不到回答

如果仍得不到回答，请不要以为我们觉得无法帮助你。有时只是看到你问题的人不知道答案罢了。没有回应不代表你被忽视，虽然不可否认这种差别很难区分。

总的来说，简单地重复说你的问题是个很糟的点子。这将被视为无意义的喧闹。有点耐心，知道你问题答案的人可能还在上夜班，可能正在睡觉，也有可能你的问题一开始就没有组织好。

你可以通过其他渠道获得帮助，这些渠道通常更适合初学者的需要。

有许多网上的以及本地的用户群组，由热情的Galgame爱好者组成。通常人们组建这样的团体来互相帮助并帮助新手。



## 如何更好地回答问题

**态度和善一点。** 问题带来的压力常使人显得无礼或愚蠢，其实并不是这样。

**对初犯者私下回复。** 对那些坦诚犯错之人没有必要当众羞辱，一个真正的新手也许连怎么搜索或在哪找常见问题都不知道。

**如果你不确定，一定要说出来！** 一个听起来权威的错误回复比没有还要糟，别因为听起来像个专家很好玩，就给别人乱指路。要谦虚和诚实，给提问者与同行都树个好榜样。

**如果帮不了忙，也别妨碍他。** 不要在实际步骤上开玩笑，那样也许会毁了提问者的设置 —— 有些可怜的呆瓜会把它当成真的指令。

**试探性的反问以引出更多的细节。** 如果你做得好，提问者可以学到点东西 —— 你也可以。试试将蠢问题转变成好问题，别忘了我们都曾是新手。

尽管对那些懒虫抱怨一声 RTFM 是正当的，但能给出文档的链接（即使只是建议个 Google 搜索关键词）会更好。

**如果你决定回答，就请给出好的答案。** 当别人正在用错误的工具或方法时别建议笨拙的权宜之计（workaround），应推荐更好的工具，重新界定问题。

**正面地回答问题！** 如果这个提问者已经很深入的研究而且也表明已经试过 X 、 Y 、 Z 、 A 、 B 、 C 但没得到结果，回答 `试试看 A 或是 B` 或者 `试试 X 、 Y 、 Z 、 A 、 B 、 C` 并附上一个链接一点用都没有。

如果你在研究一番后才作出了回答，**展现你的技巧而不是直接端出结果**。毕竟`授人以鱼不如授人以渔`。


## 鸣谢

感谢为此项目做出贡献的所有人。



## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://fredwe.info"><img src="https://avatars.githubusercontent.com/u/7354718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Fred</b></sub></a><br /><a href="#translation-FredWe" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/xgdgsc"><img src="https://avatars.githubusercontent.com/u/1189869?v=4?s=100" width="100px;" alt=""/><br /><sub><b>xgdgsc</b></sub></a><br /><a href="#translation-xgdgsc" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/fishballLin"><img src="https://avatars.githubusercontent.com/u/11352791?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Michael Lin</b></sub></a><br /><a href="#translation-fishballLin" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/cuter44"><img src="https://avatars.githubusercontent.com/u/2285039?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Galin Wu</b></sub></a><br /><a href="#translation-cuter44" title="Translation">🌍</a></td>
    <td align="center"><a href="http://blog.csdn.net/lantianjialiang/"><img src="https://avatars.githubusercontent.com/u/4327697?v=4?s=100" width="100px;" alt=""/><br /><sub><b>lantianjialiang</b></sub></a><br /><a href="#translation-lantianjialiang" title="Translation">🌍</a></td>
    <td align="center"><a href="https://linuxtoy.org"><img src="https://avatars.githubusercontent.com/u/15364?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Xiaodong Xu</b></sub></a><br /><a href="#translation-xuxiaodong" title="Translation">🌍</a></td>
    <td align="center"><a href="https://blog.clifflu.net"><img src="https://avatars.githubusercontent.com/u/1589313?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Cliff Chao-kuan Lu</b></sub></a><br /><a href="#translation-clifflu" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Fibird"><img src="https://avatars.githubusercontent.com/u/12209558?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Chaoyang Liu</b></sub></a><br /><a href="#translation-Fibird" title="Translation">🌍</a></td>
    <td align="center"><a href="https://www.rayjune.com/about"><img src="https://avatars.githubusercontent.com/u/22052875?v=4?s=100" width="100px;" alt=""/><br /><sub><b>瑞君</b></sub></a><br /><a href="#translation-RayJune" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/lvsj"><img src="https://avatars.githubusercontent.com/u/5672080?v=4?s=100" width="100px;" alt=""/><br /><sub><b>steven lyu</b></sub></a><br /><a href="#translation-lvsj" title="Translation">🌍</a></td>
    <td align="center"><a href="http://linkedin.com/in/yen-wu"><img src="https://avatars.githubusercontent.com/u/11289349?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Yan-Kuan Wu</b></sub></a><br /><a href="#translation-yan-kuan" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/Kalger"><img src="https://avatars.githubusercontent.com/u/15393585?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alger</b></sub></a><br /><a href="#translation-Kalger" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/HJ1AN"><img src="https://avatars.githubusercontent.com/u/10445159?v=4?s=100" width="100px;" alt=""/><br /><sub><b>HJ1AN</b></sub></a><br /><a href="#translation-HJ1AN" title="Translation">🌍</a></td>
    <td align="center"><a href="http://konekoya.github.io/"><img src="https://avatars.githubusercontent.com/u/12165714?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Joshua</b></sub></a><br /><a href="#translation-konekoya" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://splasky.blogspot.com/"><img src="https://avatars.githubusercontent.com/u/14876069?v=4?s=100" width="100px;" alt=""/><br /><sub><b>HY Chang(splasky)</b></sub></a><br /><a href="#translation-splasky" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/SaberPdr"><img src="https://avatars.githubusercontent.com/u/18625830?v=4?s=100" width="100px;" alt=""/><br /><sub><b>qiuqiu</b></sub></a><br /><a href="#translation-SaberPdr" title="Translation">🌍</a></td>
    <td align="center"><a href="http://a.dqwyy.moe"><img src="https://avatars.githubusercontent.com/u/20705919?v=4?s=100" width="100px;" alt=""/><br /><sub><b>dqwyy</b></sub></a><br /><a href="#translation-dqwyy" title="Translation">🌍</a></td>
    <td align="center"><a href="http://tomazwang.github.io"><img src="https://avatars.githubusercontent.com/u/7992586?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Tomaz Wang</b></sub></a><br /><a href="#translation-TomazWang" title="Translation">🌍</a></td>
    <td align="center"><a href="https://aka.ms/anduin"><img src="https://avatars.githubusercontent.com/u/19531547?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Anduin Xue</b></sub></a><br /><a href="#translation-Anduin2017" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/Pancongwen"><img src="https://avatars.githubusercontent.com/u/25834392?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Pancongwen</b></sub></a><br /><a href="#translation-Pancongwen" title="Translation">🌍</a></td>
    <td align="center"><a href="https://cis.upenn.edu/~yishuai/"><img src="https://avatars.githubusercontent.com/u/7020805?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Yishuai Li</b></sub></a><br /><a href="#translation-liyishuai" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/FranklinYu"><img src="https://avatars.githubusercontent.com/u/3153452?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Franklin Yu</b></sub></a><br /><a href="#translation-FranklinYu" title="Translation">🌍</a></td>
    <td align="center"><a href="https://ld246.com"><img src="https://avatars.githubusercontent.com/u/873584?v=4?s=100" width="100px;" alt=""/><br /><sub><b>D</b></sub></a><br /><a href="#translation-88250" title="Translation">🌍</a></td>
    <td align="center"><a href="https://flandre.tw/github"><img src="https://avatars.githubusercontent.com/u/5981459?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Chun-Hao Lien</b></sub></a><br /><a href="#translation-FlandreDaisuki" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/hms5232"><img src="https://avatars.githubusercontent.com/u/43672033?v=4?s=100" width="100px;" alt=""/><br /><sub><b>hms5232</b></sub></a><br /><a href="#translation-hms5232" title="Translation">🌍</a></td>
    <td align="center"><a href="http://gricn.github.io"><img src="https://avatars.githubusercontent.com/u/34237589?v=4?s=100" width="100px;" alt=""/><br /><sub><b>gricn</b></sub></a><br /><a href="#translation-gricn" title="Translation">🌍</a></td>
    <td align="center"><a href="http://zoomdong.cn/"><img src="https://avatars.githubusercontent.com/u/32598811?v=4?s=100" width="100px;" alt=""/><br /><sub><b>zoomdong</b></sub></a><br /><a href="#translation-fireairforce" title="Translation">🌍</a></td>
    <td align="center"><a href="https://ladderoperator.top/"><img src="https://avatars.githubusercontent.com/u/34033754?v=4?s=100" width="100px;" alt=""/><br /><sub><b>LadderOperator</b></sub></a><br /><a href="#translation-LadderOperator" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/WuzgXY-GitHub"><img src="https://avatars.githubusercontent.com/u/62000315?v=4?s=100" width="100px;" alt=""/><br /><sub><b>WuzgXY</b></sub></a><br /><a href="#translation-WuzgXY-GitHub" title="Translation">🌍</a></td>
    <td align="center"><a href="http://baoshuo.ren"><img src="https://avatars.githubusercontent.com/u/47095648?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ren Baoshuo</b></sub></a><br /><a href="#translation-renbaoshuo" title="Translation">🌍</a></td>
    <td align="center"><a href="https://jalenchuh.cn/"><img src="https://avatars.githubusercontent.com/u/57910033?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jalen</b></sub></a><br /><a href="#translation-jalenchuh" title="Translation">🌍</a></td>
    <td align="center"><a href="http://www.libiao.vip"><img src="https://avatars.githubusercontent.com/u/8528590?v=4?s=100" width="100px;" alt=""/><br /><sub><b>BillLucky</b></sub></a><br /><a href="#translation-BillLucky" title="Translation">🌍</a></td>
    <td align="center"><a href="http://blog.mcplugin.cn"><img src="https://avatars.githubusercontent.com/u/56964531?v=4?s=100" width="100px;" alt=""/><br /><sub><b>bingchuanjuzi</b></sub></a><br /><a href="#translation-xiaopangju" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/hitjackma"><img src="https://avatars.githubusercontent.com/u/3788303?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jack M</b></sub></a><br /><a href="#translation-hitjackma" title="Translation">🌍</a></td>
    <td align="center"><a href="https://www.yidajiabei.xyz"><img src="https://avatars.githubusercontent.com/u/52186032?v=4?s=100" width="100px;" alt=""/><br /><sub><b>tianheg</b></sub></a><br /><a href="#translation-tianheg" title="Translation">🌍</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
