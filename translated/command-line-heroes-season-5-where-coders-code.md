[#]: collector: (bestony)
[#]: translator: (JonnieWayy)
[#]: reviewer: (windgeek)
[#]: publisher: ( )
[#]: url: ( )
[#]: subject: (Command Line Heroes: Season 5 : Where Coders Code)
[#]: via: (https://www.redhat.com/en/command-line-heroes/season-5/where-coders-code)
[#]: author: (RedHat https://www.redhat.com/en/command-line-heroes)

<!-- Command Line Heroes: Season 5 : Where Coders Code -->
《代码英雄》第5季：程序员写代码的地方
======
**00:02** - _Saron Yitbarek_

你们好，欢迎来到《<ruby>代码英雄<rt>Command Line Heroes</rt></ruby>》，一档<ruby>红帽<rt>Red Hat</rt></ruby>的原创播客节目。这是我们有关程序员工作生活的迷你特别季的第 2 集。从开发人员到系统管理员，以及架构师、工程师、程序员。我是你们的主持人 Saron Yitbarek，和我一起参与到这一季的是 Clive Thompson，他是记者、技术向作家以及《 Coders 》一书的作者。你好， Clive。  

**00:30** - _Clive Thompson_

你好 Saron。很高兴回来。  

**00:31** - _Saron Yitbarek_

感谢你加入我们， Clive。在这一集里，让我们谈谈到目前为止，我们当中很多人（不仅仅是技术人员）非常熟悉的一些东西，因为我们大多数人自从 2020 年 3 月以来就不得不这么做 —— 远程工作。现在，你可能认为远程工作在我们的行业里是相对较新的现象。随着技术的进步，在家中工作变得更为容易。先再想一下，让我们来听听这位开发人员的故事。  

**01:00** - _Mary Allen Wilkes_

嗯，我的名字叫 Mary Allen Wilkes。1959 年到 1972 年间，我做了十二三年的计算机程序员。  

**01:14** - _Saron Yitbarek_

Mary Allen 已经 82 岁了。在她青少年时期，她迷上了法律，想当一名律师，但是在 50 年代这对一名女性而言并不是一个明智的职业选择。导师劝阻了她，并告诉她这会有很多艰难困苦。偶然的一次机会，她的一位老师为她描绘了另一条路线。  

**01:36** - _Mary Allen Wilkes_

我在读八年级的时候，某天在上一个地理老师的课，显然我给他讲述了自己对某件事情的论点，而他只是停了下来，并看着我说：“ Mary Allen，你长大以后应该成为一名计算机程序员。” 好吧，我不知道他在说什么。多年以后，我很想知道他是否清楚他当时正在说的是什么。他教授地理和法语，没有人教计算机编程。但是我永远都忘不了他的话。而且我认为让我多年难以忘怀这个目标的一个原因是，一个成年人告诉我长大以后我可以做一件积极的事情。  

**02:22** - _Saron Yitbarek_

当 Mary Allen 从大学毕业并且开始求职时，唯一有职位提供给计算机程序员的地方是 MIT。没有人接受过计算机编程方面的任何训练。她的主要资格条件是她在大学里上过的两门逻辑学课程，但这已经比她在 MIT 的同事多了。  

**02:41** - _Mary Allen Wilkes_

我开始在位于<ruby>马萨诸塞<rt>Massachusetts</rt></ruby>州<ruby>列克星敦<rt>Lexington</rt></ruby>市的 Lincoln 实验室工作，这是由国防部资助的一个大型 MIT 研究机构。我们谈论的是 1959 年，我首先了解到的是他们正在使用这些形如庞然大物的计算机，这些大家伙占据了整个房间。这是我最初学习编程的机器。它们是 IBM 计算机。你用汇编语言逐行编写好你的程序，然后把这些纸交给打孔卡操作员，后者负责对每行代码进行打孔。然后你将其带到计算机室，交给计算机操作员。  

**03:29** - _Saron Yitbarek_

1961 年， Mary Allen 被分配到一个小组，在一款实验室仪器通用微型计算机 Link 计算机上工作。它是第一批真正的交互式计算机之一，与当今的台式计算机有些相似。  

**03:44** - _Mary Allen Wilkes_

Link 有一块显示屏。我们称之为“<ruby>示波器<rt>the scope</rt></ruby>”因为它事实上就是一个实验室示波器。它有四个可以放在桌面上的盒子、一个装着这台示波器的盒子、一个装有两个袖珍大小的小型磁带装置的盒子。如果可以的话，这基本上就是你的永久存储器和硬盘驱动器。那是你存储和读入你的程序的地方。另一个盒子被称为控制台盒子。你可以用开关来加载某些代码（比如某些引导代码）到 Link 的内存里。它也有个键盘。因此，你拥有你现如今会有的基本交互式配置，包括键盘和屏幕以及一些形式的永久存储器。然后当然还有所有的电子设备，它们都被装载一个大约和一台冰箱差不多大小的大箱子里。  

**04:43** - _Saron Yitbarek_

1964 年， Link 小组做了一个艰难的决定，从 MIT 迁至<ruby>密苏里<rt>Missouri</rt></ruby>州<ruby>圣路易斯<rt>St. Louis</rt></ruby> 的华盛顿大学，但是 Mary Allen 不想去。  

**04:54** - _Mary Allen Wilkes_

我不想立马就搬到圣路易斯。我一点儿都不确定我是否想搬去那里。我想要做的是为 Link 写一个合适的操作系统，因为到当时位置，我们所拥有的只是我在 1962 和 1963 年所编写的非常小的汇编程序。我说：“我可以做到。我可以在家里写它。”   

**05:20** - _Saron Yitbarek_

Wesley Clark， Link 小组的负责人认为这是个很棒的主意。  

**05:25** - _Mary Allen Wilkes_

我对他说：“我想要写这个操作系统。”我可能是当时唯一一个能够写这个操作系统的人。因此， Wesley 只是说：“好吧，没问题。为们会给你送来一台 Link。你可以在家里使用它。”这就是它的来历。一天，我们实验室的几个家伙开着一辆小型搬运货车来了，并带来了四个不同的箱子、那四个模块和装着电子设备与存储器的冰箱大小的东西以及其他一些东西。他们把这些东西运到了我父母在 Baltimore 的客厅。他们可能不得不为此开发了 20 安培的电路，但除此之外，你只需要将其插入墙上的插座即可。  

**06:10** - _Saron Yitbarek_

她的父母对家里这个硕大的新入侵者作何看法？  

**06:15** - _Mary Allen Wilkes_

我的父亲是主教神职人员。他会告诉它见过的每一个人：“我敢打赌，你的客厅里没有电脑。”这至少可以说是很新奇的事情，相当新奇。  

**06:30** - _Saron Yitbarek_

Mary Allen 的父母整天都不在家，因此她能够集中注意力。她直接在 Link 上写操作系统，不需要打孔卡，所以她可以更快地进行调试。她通过电话或老式的<ruby>蜗牛邮件<rt>snail mail</rt></ruby>和她的团队交流，并在必要的时候前往圣路易斯。仅仅在不到一年的时间里，她就完成了这个操作系统并编写了编程手册。  

**06:55** - _Mary Allen Wilkes_

我从未感到被孤立，也从未感到过沮丧。我感到充满了挑战。我认为编程对于内向的人、与世隔绝工作的人、独立工作的人、不需要大量支持或是与他人交互的人而言是一项基本的工作。  

**07:15** - _Saron Yitbarek_

多年以来， Mary Allen 从事过其他工作，这些工作需要她在办公室里工作。但是她所偏好的是在家工作。  

**07:23** - _Mary Allen Wilkes_

自从 2001 年辞去我的全日制工作以来，我如今已经在家里工作了好几年。因此，我是一个在家工作的人。而且事实上，在我离职那天，我对自己说，我将继续工作，但我不想去办公室，也不想坐在办公桌前。但是在那时，当然我们有了笔记本电脑，所以我能够坐在安乐椅上工作。  

**07:53** - _Saron Yitbarek_

因此， Clive， Mary Allen 的故事如此精彩，你得为程序员们去采访她。她不仅仅是计算机编程的先驱，而且还是远程工作的先驱，不是吗？  

**08:03** - _Clive Thompson_

是的。我的意思是，据我所知，她是第一个有一台能让她在家工作的个人计算机的人。网上有一张令人惊叹的她的照片，照片上她正坐在她父母的楼梯脚下。他们把所有这些部件放在顶层的楼下，这是她放一张小桌子坐着工作的地方。而且这是对未来的一瞥，对吗？我是说，那时候她正在做的事情要花费 30、 40 年时间才能够整体实现，因为她完全领先于自己所处的时代。  

**08:36** - _Saron Yitbarek_

编程是一项很理想的可以远程来做的工作。甚至我自己的自我隔离经历也是我意识到我已经做这个很多年了。因此当你和程序员交谈的时候，有多少人喜欢这种工作方式？它变得有多流行？  

**08:52** - _Clive Thompson_

好吧，这很流行，而这是因为程序员们喜欢在家工作。绝大多数的程序员如果能够选择的话，他们会说，是的，我会一直在家工作。之所以会这样，是因为这提供了他们一个安静而又能够专注的地方，而且不会因为在隔间里因为有人拍他们的肩膀而被打扰。如果你要对他们说：“嘿，伙计们，各位，你们更愿意在哪里工作？”他们全都会更倾向于在家里工作。  

**09:26** - _Saron Yitbarek_

Basecamp 是一家大力提倡远程工作的技术公司。他们已经存在 20 年了，而他们从最初就进行远程工作，甚至在它流行之前。他们的员工在世界各地的家中工作。让我们来听听 David Heinemeier Hansson 怎么说。他和 Jason Fried 共同创立了 Basecamp。他也是 Ruby on Rails 的创造者。  

**09:49** - _David Heinemeier Hansson_

事实上，在我开始和 Jason 共事后的前六个月，我们只是通过电子邮件和 Imed 进行联系。我们甚至都没有打过电话。因此我想是过了六个月时间我们才通了第一次点换，并且花了一年多时间我们才见面。所以很长的一段时间里，这都不是传统观点。我们接触到了庞大的人才库，这些人意识到自己不想住在<ruby>旧金山<rt>San Francisco</rt></ruby>。他们不想去纽约生活，他们也不想去西雅图生活，他们不想在这些大型技术中心里的任何一个地方生活，然而他们确实是精通而且合格的人才。因此， Basecamp 允许他们这么远程工作，对于我们的招聘策略和维系策略都至关重要。  

**10:31** - _David Heinemeier Hansson_

2012 年，我与其他企业家进行了一系列对话，向他们询问他们的工作实践，我们谈论了远程工作，而对于为什么远程工作行不通，他们只给了我这些陈旧的辩驳。"哦，你们没法合作。魔法只会发生在白板周围。"而我想，什么，人们还是这样想的？这怎么可能？白板在 Basecamp 基本上不存在。我们拥有的第一工具是编写。它是异步的，你自己编写并发布，让时间过去。当富有创造力的人们有时间和空间去进行深度思考并且将深度思考编辑成深度写作时，就会产生良好的协作。深度写作当时并不包含单个聊天行，而是组成完整的句子，从而形成段落，进而形成完整的论点。  

**11:29** - _David Heinemeier Hansson_

然后，你可以利用时间的优势和平静来考虑这些观点。 90% 被认为是写作，然后 5% 是聊天，然后可能 5%，我不知道，是 Zoom 还是 Tubal 或者一些其他的视频连接屏幕共享之类的协作。  

**11:49** - _Saron Yitbarek_

因此， Clive， David 在这里提出了一些非常有趣的观点。有些我从来都没想过。还有程序员正在使用的能使远程工作成功的其他工作方式吗？  

**12:00** - _Clive Thompson_

是的，绝对是的。在知道将要和人进行联络，甚至可能是面对面联络时，他们会安排时间。因此，确实有一些我交谈过的公司会说：“好吧，我们知道我们的开发人员不在这儿的时候能把他们的工作做到最好，但是我们希望他们有时能够在这里，我们想开一些面对面的会议。”他们仍然相信这一点。因此，他们会有比如像是这样的日程安排，好吧，在周二和周四的下午 1 点到 5 点，我们需要所有人都在办公室里，以便我们能够有时间进行交谈。剩下的时间，你可以去你想去的任何地方。如果你想的话，你可以在办公室里工作，你可以在任何你喜欢的地方工作。可以是在星巴克，也可以是在家里。因此，这种有趣的新安排是一件行之有效的事情。  

**12:44** - _Clive Thompson_

我认为另外一件相当有效的事情是弄清楚每个人最喜欢的聊天或者交流模式是什么样的。就 David 而言，他喜欢的，以及他的团队所喜欢的，是长格式的电子邮件对话。我肯定已经和喜欢这种交流模式的人交谈过了，但是其他人，他们事实上真的很喜欢 Slack，或者他们真的很喜欢老式的 IRC，对吗？像是黑色背景上的绿色文字。但是他们弄清楚了它们的共存形式是什么，因为有过这样的现象，被谈论在线交流的心理学家们描述为<ruby>环境感知<rt>ambient awareness</rt></ruby>，这是一种当你人没有和他们在一起时去知晓其他人正在思考什么或是做些什么的能力。有很多技术可以使我们做到这一点。而最好的远程团队仔细考虑了他们的环境感知方法是什么，然后锁定并使用它。  

**13:39** - _Saron Yitbarek_

在我自己的远程工作经历中，有一件我发现确实很有用的事情是通过 Hangout 或 Zoom 会话来进行协同工作，只是让流运行并且让连接一直打开着。这确实是一种减少孤独感的绝妙方式，一定意义上有了相互陪伴的感觉，除了每个人仍然还在做着自己的事情，但是这提供了拍某人肩膀的机会，因为我可以说：“嘿，我被这个功能难住了。你介意我耽搁你接下来的 5 分钟 10 分钟吗？你能和我配对，帮助我摆脱困境吗？”因此，这成了一种着实很有用的方式，能让你获得某种形式的社交互动并在需要的时候有机会得到帮助。  

**14:21** - _Clive Thompson_

这完全有道理。我是说，我认为很多人都试图找到某种方法来与有经验的人这么做，或者甚至坦率地讲，甚至和同龄人这么做，因为你能够得到很多，及时某人并不比你高级，但仅仅只是有个不同的大脑。  

**14:37** - _Saron Yitbarek_

是的，绝对是这样。我认为这是一种不同的交流形式，但我不认为这是一种较低质量的交流。  

**14:44** - _Clive Thompson_

一点也不。这就像是心理学家所谓的<ruby>元认知<rt>metacognition</rt></ruby>，有关思考的思考。确实，当前的任务是 —— 今天我想要尝试的是哪一种思维方式？是和某人面对面交流还是与他们在线聊天更有助于思考呢？  

**15:01** - _Saron Yitbarek_

因此，既然我们所有人都被迫在家工作，各家公司都意识到他们仍然能够完成工作。态度已经转变成远程工作将成为主流了吗？  

**15:12** - _Clive Thompson_

这是真的是一个大问题，而我认为我们目前并没有答案。我认为即将要发生的事情是，那里有很多的工人，包括从未在家或者被允许在家工作的开发人员，我要说超过 50 %，他们将会要求使其成为半永久性的。他们将发现自己的工作效率要高得多，并且希望更频繁地这样做，而且这些会议中有一些是不必要的，并且打断了他们在工作区中的工作流程。  

**15:47** - _Saron Yitbarek_

因此，如果远程工作是提高生产效率的好方法，随着时间的推移，它变得越来越流行，尤其是对于编程人员而言这是这么好的用于完成工作的方法，它可以使工作变得便捷得多，而我们的工作形式确实意味着在家里工作，那么为什么这些大型科技公司要继续建造如此大的工场供其员工工作呢？  

**16:06** - _Clive Thompson_

这有一部分是基于他们的想法或者关注点，即人们只有在面对面并且相互之间有着意想不到的联系的时候，才会有创造性思维产生。而这是基于一些实际的科学的。我的意思是，有大量研究表明，当公司中的可能互相根本不认识的人们相遇时，会产生某种特定类型的交流和松散的协作与念头。我时说，这是精炼的<ruby>水冷却器效应<rt>water cooler effect</rt></ruby>。 3M，一家大型的纸业公司，以发明了<ruby>便利贴<rt>Post-it Notes</rt></ruby>而闻名，一项价值数十亿美元的发明，只是因为发明了这种粘性物质的一个人遇到了另一个正在找寻一种能把纸张固定在适当位置的方法的一个人。而正是因为这个遇见彼此的机会，他们创造了该公司最具标志性的产品之一。  

**17:05** - _Clive Thompson_

Steve Jobs 确实创建了 Apple 总部，以最大程度地提升人们不在一起工作的机会，但他们会在一些地方进行聚集以迸发出创意的火花。  

**17:20** - _Saron Yitbarek_

因此，我进行远程工作已经很多年了，我只是为自己工作，然后有一次我有了一个团队，和几个人一起工作，但是我在远程工作方面的经历里最多是和四个人共事，他们来自各个地方。我们中有人在洛杉矶，有人在布鲁克林，也有人在芝加哥，但是我想知道的是 —— 远程工作真的只有对于像那样的小型团队以及像 Basecamp 那样的小型公司才能取得成功吗？  

**17:44** - _Clive Thompson_

是的，这是个很棒的问题。我已经看到的是当开发团队在启动阶段很小，只有 5 到 6 个人的情况下，远程工作开展得最为成功了，而且事实上，他们之所以能够获得所需的人才，是因为他们说：“好的，你在俄罗斯。我在多伦多。我们其他人在田纳西，而我们将一起工作。”因此，你会看到很多某一类型的初创团队，他们拥有他们所需的特定技能，并且需要得到他们认为最好的人才，但他们不会要求这些人搬家。这是小型团队。  

**18:22** - _Clive Thompson_

我觉得管理通信要更加容易一些，因为你基本上可以将这视为一组节点之间的通信，并且随着节点的整张，需要通信的人数急剧增长。因此，只有 4 个或 5 个人的时候团队运转良好，到了比如 50 个人，这变得着实很困难，再到 150 个人，哦，我的天哪。对于一家有着 10000 个人的公司而言，弄清楚他们将如何做到这一点变得更为困难。  

**18:47** - _Saron Yitbarek_

让我们来听听有关远程工作的另一种观点。 Dave West 是 scrum.org 的首席执行官。在这家公司工作的基础是《<ruby>敏捷宣言<rt>Agile Manifesto</rt></ruby>》的第一条规则、个人以及流程与工具之上的交互。这里是 Dave。  

**19:05** - _Dave West_

我认为现实是，如果你真的想要以极快的速度构建一个项目，以一种真正有效的方式协同工作，面对面可能仍然是最好的形式。这并不意味着它是唯一的方法，也不意味着你以其他的形式交流和分配就不能像从前那样行之有效。但是，最好和最容易的形式是面对面交流。时至今日，我仍然相信我曾经从事过的最令人愉快的软件项目，以及我曾经参与过的开发项目和团队都位于同一地点，位于同一个办公室里。而这是有许多原因的。这是因为周五晚上出去喝点儿啤酒，能够在发生可能影响他们工作的问题时对某个人有一个更加深刻的认识，比如他们宠物狗的逝去或是其他类似的事情。  

**20:04** - _Dave West_

你能够获得想从分散的团队那里更难获得的东西。但是另一方面，我认为不是所有最出色的软件工程师都居住在硅谷。所以我感到很矛盾，我觉得位于同一地点的团队有着巨大的价值，但是我也认为好处，尤其是分散在不同地点的人们所带来的好处，也是巨大的。因此，你必须找寻到一个平衡点，而这相当相当困难。我所知道的是如果你打算分散你的团队，那么你必须特别注意促进并使得环境尽可能实际复制位于同一地点的团队所处的环境。这意味着经常让他们见面。因此，你们要进行大量的屏幕共享，并且花时间在一起，可能需要发起一个 Google Hangout 并使之持续运行并进行共享。这些事情变得非常非常重要。  

**21:10** - _Saron Yitbarek_

因此， Clive，开源项目是建立在协作和团队合作之上的。所以说远程工作会阻碍这一点吗？远程工作对真正的协作能有多大帮助？  

**21:22** - _Clive Thompson_

好吧，这个问题有关开源的的第一部分很容易回答，我认为实际上开源领域的大部分巨大成就都是在极端远程的情况下取得的，因为从定义上说，开源项目的魔法在于一个开发者：“嘿，我有一个我正在开发的代码库。有人有什么主意吗？”与其只是询问你公司里的 50 个人，你可以在网上询问数以百万计的人。因为实际上只有 1% 的 1% 的 1% 的 1% 的人会给你提供一个好主意。在你拥有 50 个人的组织里，可能没有人会在意你正在构建的奇怪的小库，而在整个星球的范围内，你将挥发小有 9 个人有着令人难以置信的热情并且有兴趣帮助你开发这个东西。因此，从某种意义来讲，开源从定义上说通过协作大力促进了远程工作。  

**22:18** - _Clive Thompson_

不过，它也受到了挑战，因为刚才 Dave 所谈及的所有这类事情都是真实的 —— 没有面对面接触的话，所有能够帮助组织运转的社会粘合剂真的很容易分崩离析。而你会在开源项目中看到这一点。它们真的能够转变成网络上反社会行为的噩梦，因为人们并不擅长去阅读彼此的语气。他们会认为自己只是直截了当，而其他人则会认为他们是在进行令人难以置信的羞辱。在面对面社交互动的情况下能在可能是短短 30 秒的时间内就能够化解的误会，能够撕裂开源社区，并已经撕裂了网络上的一些开源社区。  

**23:07** - _Saron Yitbarek_

Maude Mensah Simpson 是一名前端开发人员，她在居家工作的同时还是两个年幼孩子的母亲。她解释了在有了她第二个孩子以后，在远程工作方面所遇到的早期挑战之一。  

**23:18** - _Maude Mensah Simpson_

在我有我第二个孩子的时候，我还是刚刚第一年成为一名开发人员。因此，当其他所有人都在办公室而就你不在的时候，你会想念太多太多东西。其中之一是人们有关工作的一般性交谈。比我高级的开发人员会在我写代码的时候从我身后走过，然后他会看到我正在做的东西，并且会说：“哦，是的，我喜欢你的做法。”或者，“你在做什么呢？”他刚才经过我工作空间时候的举动给了他机会和我谈论有关写代码以及如何正确地做事情。远程工作可能只依赖于你的个人自信，因为当你不在办公室里工作时，你会错过一些教学与指导。  

**24:10** - _Saron Yitbarek_

Clive，我想知道一名经验丰富的程序员和一名处于生涯起步阶段的程序员相比，远程工作的经验是不是会有所不同，因为我能够想象一个经验丰富的程序员，已经习惯于在办公室环境中工作，然后不得不转到远程工作。这变化可能并不是太糟糕，这可能并不是太具有挑战性。但是对一个处于生涯初期的程序员而言，我能看到他们真正受益于处在导师身边，这些人拥有更多地经验，能够拍拍他们的肩膀然后问他们问题。因此，处于生涯初期的程序员会因为不在其他程序员身边而有所损失吗？  

**24:43** - _Clive Thompson_

我觉得他们会的。是的。我认为这是一个很合理的担忧，而且我肯定已经听过老开发人员们的意见，他们一直以来进行面对面合作并且知道，通过和一名更高级的程序员进行一次 30 秒的面对面交谈，他们可以学到很多东西，并觉得茅塞顿开。因此， Jeff Dean 是 Google 的一名高级工程经理。我从许多和他共事过的人那里听说，他就是一个非常有用的高级资源，因为人们会带着问题去找他，而他能够字面上通过它直接看到向量，不出 20 秒后，“哦 …… ”他不会直接给出答案，但是他会告诉他们他所认为的问题所在，从而他们会茅塞顿开地回去，并变得令人难以置信得富有生产力。  

**25:36** - _Clive Thompson_

因此，新人们能够从像那样的交互当中受益匪浅。我不是说你永远都没法使他们远程工作，只是会更难实行。然后还有代码审查。因此，在一家管理良好的优秀公司里，你将会需要代码审查，你的同辈以及围绕某一问题有段时间的资深人士（如果条件比较理想的话）正在查看你的代码，坐下来讨论它，并问你是如何实现以及为什么要这么做。而这个往复的过程会涉及到许多你可能会作出的模糊的决定，并使其清晰化，这对与学习而言相当有价值。能够理解你为什么要做自己所做的事情，将其具象化给其他人，是十分有价值的。  

**26:20** - _Saron Yitbarek_

我所听说过的有关远程工作的问题之一在于有关混合的想法，当你开始工作然后已经到了 6 点钟，是时候停止工作了，但是你在工作过程中感到舒适，你将再额外地工作一两个小时，最终会因为远程工作而过度劳累。是这样吗？然后有点儿与之相反的是，你能够在远程工作的时候马马虎虎吗？  

**26:43** - _Clive Thompson_

你可能会马马虎虎工作，但是我在对开发人员及其经历的全部访谈过程中从来都没有听说过这种情况。事实上恰恰相反。我倾向于听到的是经理们担心人们永远不休息，永远都不离开工作。我也从开发人员那里听说过，这很困难。对于开发人员而言，总是很难停止去思考问题。当你居家工作的时候，你会花费 8 个小时的沉浸式时间，然后你会完成许多工作，但是由于你实际上并没有去到其他地方，你的身体没法帮着让你的思维进入关闭状态。就像你离开了办公室，坐上了汽车、公交车、踏板车或是步行回家，你实际上就从一个地方到了另一个地方，而这种物理信号会帮助你的大脑自我复位。  

**27:35** - _Clive Thompson_

这里涉及到了很多很多的科学。我是说，从字面上看，实际上的从一个地方去到另一个地方能够帮助你的大脑进行自我复位。当你没有能力这么做时，当你居家工作，与象棋相似的编码问题的自然思维空间很难去告诉你的大脑停止进行这项工作。因此，诸多原因导致了居家工作的人们继续以自己明知道不健康的方式去工作，却难以停下来。  

**28:03** - _Saron Yitbarek_

David Heinemeier Hansson。

**28:05** - _David Heinemeier Hansson_

随着时间的推移，我们对于 Basecamp 的人们如何处理这一问题有过一些有趣的轶事。我们过去有一位数据分析师，他有两双拖鞋。他会在走进办公室的时候穿上他的工作拖鞋，然后你会拿到他的居家拖鞋。它们都只是一双拖鞋而已，它们只是将工作与家庭分隔开来。而我认为这一分隔尤为重要。我觉得对许多使用他们的家来工作的人而言，能够分出家里的一个房间用于工作，然后当你离开那间屋子时，你就不再工作了，这也不失为一种健康的行为。  

**28:41** - _Saron Yitbarek_

我喜欢这个脱鞋的点子，就像 Rogers 先生那样。这里又是 Maude。经过在家和孩子一起工作了几年后，她想出了自己的配方，使得居家工作行得通。  

**28:53** - _Maude Mensah Simpson_

很容易对时间失去控制。你可能会坐在那里好几个小时，却并不知道自己已经在家写了多久代码，因为你在家里。我的解决方法是，我有一个 Pomodoro 计时器，我会确保大概每小时都会有专门的休息时间。然后就是能够喜欢将家和工作分隔开来。我在家里有一个办公室，我不会允许我的家庭生活进入到这间办公室里，以保证将其二者分隔。因此，每当我走出去时，我可以是妈妈或是我不工作时候的任何人，但是当我走进了办公室以后，这是上班时间，而这使得进入工作流程更为容易。我每天都回进行一次快速的状态更新。早上，我会让他们知道这是我今天要做的工作，然后到了夜晚，我会让他们知道我做到了什么程度。我认为在进行远程工作的时候不存在类似于过度交流之类的事情。所以是的，只是交流，交流。  

**30:02** - _Saron Yitbarek_

因此， Clive，有没有其他建议或是窍门来远程管理员工，或者甚至是成为一名远程工作者？  

**30:08** - _Clive Thompson_

当然，如果一家公司想要拥有一种严肃的远程文化，那么重要的一点是，高层管理者也应当远程工作，这样就不会有产生一种远程工作是一种次级状态，而重大决定是有重要任务面对面作出的，远程工作人员并不参与其中的感觉。我在研究书籍时所遇到的一个问题是，当我与 Postlight 的一些工程师交谈时遇到的，后者是纽约市一家很了不起的公司。他们主要为媒体行业开发应用程序。工程负责人进行着远程工作，他工作于 Nashville 以南的树林里。当我和他交谈时，他说：“这确实是非常重要的一件事情，因为我们有许多远程工作的工程师，他们喜欢知道我在领导工程师团队，而我自己是远程工作的。”这意味着公司里的每一个人都非常谨慎地考虑着如何使得远程工作行得通，因为在该部分里运行着这场演出的人们自己也都在远程工作。  

**31:09** - _Saron Yitbarek_

自从 2020 年 3 月以来，我们大多数人都不得不彻底改变工作方式 —— 居家工作，无论我们过去是否以及是这么做的。而当我们居家工作时，这就取决于我们个人的工作风格，并且确保无论我们从事的是什么项目，无论工作于什么公司，无论在管理什么人或是被什么人管理，我们的个人喜好能够得到尊重，我们可以灵活地以我们最好的方式工作。让人们关注过程并非仅仅是《敏捷宣言》的第一条规则，它是开源的方式，而且它是能够产生最好结果的方式。请访问 [redhat.com/commandlineheroes](//www.redhat.com/en/commandlineheroes) 以获取这一集的更多研究结果。下一次，在我们有关职业生涯的这一迷你季的最后一集中， Clive 将会回来和我们一起解决“你会成为什么样的程序员”这一问题。非常感谢你加入我们， Clive。  

**32:07** - _Clive Thompson_

谢谢， Saron。  

**32:08** - _Saron Yitbarek_

您正在收听的是《代码英雄》，来自红帽的一档原创播客节目。我是 Saron Yitbarek。  

**32:15** - _Clive Thompson_

我是 Clive Thompson。  

**32:16** - _Saron Yitbarek_

好的。我们要这么做这个比较好呢？  

**32:18** - _Clive Thompson_

哦我的天哪。我们能最后一次说“继续写代码吧”吗？  

**32:23** - _Saron Yitbarek_

继续写代码吧。  

**32:25** - _Clive Thompson_

继续写代码吧。  


--------------------------------------------------------------------------------

via: https://www.redhat.com/en/command-line-heroes/season-5/where-coders-code

作者：[Red Hat][a]
选题：[bestony][b]
译者：[JonnieWayy](https://github.com/JonnieWayy)
校对：[windgeek](https://github.com/windgeek)

本文由 [LCRH](https://github.com/LCTT/LCRH) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://www.redhat.com/en/command-line-heroes
[b]: https://github.com/bestony