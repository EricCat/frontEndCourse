老码农的web前端开发培训
==


一、总体思路
--

   地球人儿都知道，web前端入门容易，精通难。虽然比后端逻辑的抽象程度小一些，但很多细节也不简单，而且新技术的出现比后端来得更猛。

   以老码农的体会来说，近几年因为HTML5，CSS3的出现并逐渐占据主流位置，web前端开发的整体格局已经有了一个巨大的变化。比如说原先要通过jQuery渲染的一些动画效果，现在用CSS3 animation就轻松搞定了，Drag & Drop这类功能也成为了HTML5的标配。
   
   总体趋势是JS的角色要往后退，主要承担前端逻辑控制和与后端交互的作用，CSS成为前端渲染效果的核心。最近出现的一些前端MVC框架，比如angularJS，就已经体现了这一趋势。

   另外，HTML5的功能十分强大，已经拥有了几乎所有的硬件资源（文件系统、内嵌数据库、摄像头、音频视频、语音合成、地理位置...），这都是从事web前端开发的码农们不能不注意到的。理论上，除了需要蓝牙的应用，其他类型的移动app都可以做成浏览器版本了。

   其实还有一件大事。2012年IETF一声炮响，给码农们带来了HTTP 2.0。 要是真如江湖传说那样，明年主流的浏览器会开始支持它的话，那老码农还真的为做本地app的兄弟们捏一把汗呢。

   所以说，世界变化这么快，身为一个高大上的前端码农，学会了点东西就一直吃老本是不行的，要拥有持续学习的能力才能保证在技术上不落伍。

   怎么学呢？老码农水平有限，不敢提“30天精通前端开发”之类的说法。再说了，授人以鱼不如授人以渔嘛。所以，老码农这门课的总体思路就是，以web前端开发作为一个载体，通过短短一个月的学习，最核心的是培养分析问题和持续学习的能力。具备了这种能力，甭管下次出来的是HTTP 3.0还是HTML8，你都能分分钟上手，麻麻再也不用担心你被一些蹩脚的培训课程骗钱了，咳咳。


二、前提条件
--

   本课程需要学员对HTML、CSS、JS有一定经验，能够独立制作带有动画效果的网页，熟练掌握JS编程，最好能了解树形数据结构。经验越充分，学习效果越好。零基础的同学就先不要报名了，纯粹浪费钱。
   
   如果你担心自己基础不够扎实，推荐去www.w3schools.com系统地学习一遍，其实也用不了多少时间。不推荐去那个中文版的，英语的看起来可能会慢，但是阅读的这个坎必须迈过去，才能更上一层楼。
   
   课程开始前的准备工作就一项：电脑必须能翻墙，不然你很难看到最新的技术。不会翻墙的同学自己想办法，总之不会翻墙这门课你是没法上的。也不要来问我怎么翻，这点小事自己都搞不定，做码农还有什么前途！ 
   
   <b>“不会翻墙的码农不是好码农。”  -- 莎士比亚</b>
   

   翻墙之后，推荐注册一个Google+账号，加入一些主题group，比如HTML5, CSS3, AngularJS、Google IO之类的，每天都看看有什么新技术出来，随时跟上前沿的发展趋势。这样不管碰到水平多高的人，你都能和他谈笑风生。当然了，talk is cheap, 最重要的还是把掌握的发展趋势落实到你的code上，这样才是真牛。


三、课程范围
--

所谓范围，说白了就是包括什么，不包括什么。一个月时间几十个课时，不可能面面俱到对吧？所以重点必须明确，思路必须清晰，不然就会浪费时间。

课程包括的核心内容有：

<b>1. 基础：英语阅读、stackoverflow、github、编码规范</b>

为啥把英语阅读作为头一个基础呢？因为，平生不识English，纵使翻了墙也枉然。作为码农，每天翻墙出去光是看中文社区的那些不靠谱的政治八卦有什么意思？有这闲工夫不如去stackoverflow上攒几K reputation，或者在github上挣几百个star，最不济也得把时间花在Google+上和硅谷那些大牛们侃大山啊，这才是你作为码农最有用的资本。

可要做到这一点谈何容易？必须大量地学习最新的技术才行，而最新技术基本上没有像样的中文文档，只能靠英语水平硬啃。对很多码农来说，什么是制约他成长最大的瓶颈？我看英语是很大的一个因素。

<b>2. 架构：现代web前端开发中HTML+CSS+JS各自的定位和配合</b>

前面说了，现在web前端开发的格局已经有了巨大的变化，开发的思路要跟上时代，不要会了点技术就死抱着不放，每天坐井观天按部就班地写出一堆过时的、难以维护的垃圾代码，这样既害人又害己，人生还有什么意义？对于新技术，老码农在课上先抛个砖，砸到一个算一个。但是技术是不断进步的，道可道非常道，掌握悟道的能力才是关键。

<b>3. 前端核心技术:</b>

HTML5：通过部分例子讲解HTML5的新特性

CSS3： 通过部分例子讲解CSS3的新特性

JS：   通过部分例子讲解原生JS的开发方法

核心的三部分就是上面的HTML5、CSS3、JS了，不过注意，老码农没时间逐条给你讲这里边的定义、语法和用法。在w3schools.com里边这些内容都有，还提供了可以尝试的例子，不会的自己先去看嘛。课程里主要是用例子告诉你它带来的变化、可能存在的坑、还有如何找到合适的学习资源，关键还在于自己动手去用它们。

SVG：通过部分例子讲解SVG的特性，它和HTML，CSS，JS如何配合使用

SVG在传统的web前端开发过程中被关注得不多，但是其功能之强大是web前端码农不应该忽略的。在深入理解了HTML、CSS、JS之后，SVG的学习也就可以触类旁通，其实并不难。一起来发现这个金矿吧！

<b>4. 后端RESTful接口和前端的配合</b>

虽然说前后端工作没有高低贵贱之分，只是革命分工的不同，但好的工程师应该是能前后端通吃的，否则将来领导想提拔你让你做架构，你又完全不懂后端，大好事可能就黄了。所以说前端工程师也需要了解后端的原理，不能两耳不闻后端事，一心只切PS图。

当然了，这次培训是针对前端的，时间有限，不可能详细地涵盖后端，但是会介绍前端一个Ajax请求发出去之后会发生的事情，构建一个简单的前后端整体环境。

<b>5. 实习：以小组为单位做一个web前端效果</b>

这个是最好玩的部分了。前面学了一些东西，虽然每次都会有练习，但不拿它做个完整的东西，所有的知识点就串不起来，还是孤立的点，就不是真正的掌握了这些技术。而且，在实际开发中会遇到很多坑，比如A和B单独用都好得很，但放在一起就出错，怎么办？

所以，要通过实际项目磨练自己分析问题和解决问题的能力，树立码对我荣、码错我死的坚定信念，掌握代码调试的技巧，才能做到培训结束后持续提高自己。还有，小组的团队合作也是很重要的。



<b>课程不包括的内容：</b>

1、不会逐条讲解HTML、CSS、JS的语法和用法，只会用到一些例子。再强调一次，这个培训假定你已经掌握了HTML、CSS、JS的基本知识，细节有记不住的可以查嘛。

（其实...真正的原因是...年龄大了记性不好，好多细节的东西我也记不住，没法细讲...）

2、不会涉及流行的库或工具，比如Jade、bootstrap、jQuery、AngularJS、LESS等，所有HTML、CSS、JS的内容都是基于原生代码。练习和实习也会要求写原生代码。

3、后端的介绍不会涉及到任何一种数据库，只会使用静态数据来模拟数据库。
 

总之，课程的重点是帮助学员形成较好的分析问题和持续学习的方法，而不是标准的知识点传授。我觉得那些去Google随便一搜就有的东西再讲一遍的意义不大。所以这个培训只能是小班课，要确保课堂的充分互动，在课外还要确保充足的练习和答疑时间。

在微博上有同学建议我做成在线视频，我觉得这个价值也不大，不能套用标准化知识讲解课程的套路。因为互动是个性化的，每个人可能遇到的问题不同，所以还是要依靠现场的交流。


四、日程安排
--

培训周期：一共4周时间

集中上课时间：每个周六、周日的9：00-16：00

自己做练习的时间：每周一至周五

小组集体讨论时间：每周三晚19：00-21：00

个人答疑和讨论时间：周一至周五9：00-16：00，需提前一天预约时间以免冲突


五、招生人数及收费
--

每次培训招收9名或12名学员（分组的人数和方式需要靠第一期试验后再确定，第一期暂定9人），培训费人民币5000元/人。

第一期因为是试讲，有些方法还需要摸索，效果也还需要经过实践来检验，因此培训费暂定7折，3500元/人。但是老码农相信，道路是曲折的，前途是光明的！


六、开课时间
--

目前老码农正在紧张地备课，做好的课件也会把文字内容开源放在这里，大家可以看到准备的进展情况。不太靠谱的估计是10天左右开放报名，九月中旬开课。谢谢关注。



版权说明
--
本项目下的所有文档都可以免费使用，但需要遵守GNU General Public License v2版权协议。 

如有用户不了解GPL v2，请参看LICENSE文件中的条款。

