---
id: doc2.1
title: 第二章 API治理
---

> 嘿,规则就是规则,让我们面对它,没有规则就有混乱.
> 
> 科斯莫 克莱默(Cosmo Kramer)

治理不是让人们兴奋的事情.这也是带有一些情歌包袱的话题.毕竟,很少人愿意被治理,而且大多数人都有糟糕治理策略和无意义的规则的经历.糟糕的治理(如"糟糕的设计")让生活更加艰难.但是在我们的经验中,对于API管理我们很难只说不做.

事实上,我们甚至会说:没有API治理,你就不可能去管理你的API.

有时,API治理虽然发生在你的公司,但是你从来没有使用过"治理"术语.这是一个好现象.命名确实很重要,但是在一些组织,治理往往按时这高度集中化和命令式的期望.这可能与去中心化和权利下放的文化背道而驰,所以在那些地方,治理是个贬义词是有道理的.无论管它叫什么,即使在这种去中心化的文化中,某种形式的决策治理正在发生,但是它看起来可能与传统的自上而上的组织的治理系统完全不同.

对于"你应该治理API吗?"这样的问题,有点乏味.因为在我们的观念里,答案总是肯定的.相反,问你:"哪些决策需要被治理?",以及"哪里需要被治理",决定这些问题的答案是设计治理系统的工作.不同的治理风格会产生非常不同的工作文化,生产率,产品质量和战略价值.你选哟设计一个适合你的系统.本章的目标是为你提供实现此目的的构建区.

我们将首先探讨良好API治理的三个基本元素:决策,治理和复杂性.有了这种理解,我们将进一步研究如何将决策分配到你的公司,以及它们是如何影响你的工作的.这意味着要进一步研究集权,分权和做出决策的要素.最后,我们将看一下构建治理系统的影响,并了解三种治理风格.

治理是API管理的核心部分,它将贯穿本书的其他部分.所以,API治理的实际含义和它如何帮助你构建更好的API管理系统值得你去花时间理解.

- 理解API治理

事实上,大部分需要做出的决策都是技术活.一些决策是及其重要的,但是其他则是微不足道的.所有这些决策使得技术团队的工作是有技术含量的.一个好开发的核心技能是一遍又一遍的做出许多高质量的决策.这个相当明显的观点,但在管理API时总是很容易被人遗忘.

无论你引进哪种技术,如何进行架构设计或者选择哪家公司去合作,决定你生意命运的都是每个人的决策能力.这也是为什么治理重要的原因.你需要用有利于实现组织目标的方式制定所有的决策.

听起来容易,做起来难.你需要深入的理解治理的基本概念,以及他们之间的相互关系,才能加大成功的可能.让我们从快速查看API决策开始.

- 决策

你和大多数人主要的工作就是决策.这也是为什么治理如此重要的原因.总的来说,如果你能做出一个好的决策,就会有一个好的结果.但是决策并不仅仅是技术选型.你还需要在API领域上做出更广泛的决策.API团队可能会面对如下的选择:

1. 我们API的URI应该是/payments还是/PaymentCollection格式?

2. 我们应该将API托管给哪个云服务商?

3. 我们有两个客户信息应该舍弃哪个?

4. 如何选择开发团队成员?

5. 我应该如何命名java变量?

从上面这些问题中,我们可以得出一些简单的结论.第一,API管理的决策涉及复杂的人和关系,做出这些决策需要人和团队之间的密切合作.第二,人做出的不同选择有不同的影响,云服务商的选择对于API管理决策的影响远远大于对于Java变量的命名.第三,量变会引起质变.如果有10000个命名奇葩的Java变量,会极大的影响API实现的可维护性.

所有这些跨领域的选择,都是在大量的协调下做出,需要结合在一起才能产生好的结果.这是个繁复的工作.在本章的后面,我们将针对这个问题,给你一些适合你决策系统的指导.但是首先,让我们进一步了解这些决策治理的含义,以及为什么治理如此重要.

- 决策治理

如果你曾经独立完成过一些小项目,你会知道这些工作的成功与否完全取决于你.如果你坚定的做出好的决策,你可以得到好的结果.一个大神可以让你惊讶.但是这样的工作方式无法很好的推广.当你开发的东西上线,新功能和新需求也将不断增加.这就意味着你需要短时间内做出许多决策,即你需要更多的决策者.这样的规模式决策需要谨慎.参与决策的人越多,你越无法保证决策的质量.

这就是治理的来由.治理是管理决策制定和执行的过程.注意,我们并不是说控制和权力就是治理.治理与权利无关.它是提高人决策质量的方式.在API领域,高质量的治理往往意味着构建的API有利于组织取得成功.这个过程你可能需要一些控制级别和权力去实现,但这并不是目的.

在API中应用治理有很多方式.例如,你可以提出一种策略,要求公司中所有团队必须使用标准的技术栈.或者要求所有API在发布前必须要通过一系列标准质量检测.策略可能有松紧,但是殊途同归.实际中,你将同时管理大量不同类型的决策,同时你的治理系统将混合许多不同的约束,奖励,政策和流程.

应当谨记治理是有成本的.它需要沟通,强制和维持才能形成约束.对于遵守的决策行为的奖励需要保值,并且有吸引力.标准,政策和流程需要记录,教导,并持续更新.除此之外,还需要研究这些信息对于系统的影响.你甚至需要雇佣更多人维护治理成果.

除了这些维护治理机制的常规成本外,还有一些隐形成本.这些是当你开始在系统中进行治理时产生的成本.例如,如果你强制统一技术栈,那么在这期间技术创新的组织成本又是多少?同样,员工幸福感的代价又是多少?它是否会加大吸引人才的难度?

事实证明,这种成本很难预测.因为现实中,你治理的是由人,流程和技术组成的复杂系统.为了API系统治理,你首先要学习通常管理复杂系统需要什么.

- 治理复杂系统

好消息是,在组织内获取良好的治理结果并不需要你控制每一个决策.坏消息是,为了好的结果,你需要指出哪些决策你需要控制.这个问题比较难,并且在本书中你也无法找到确切答案.因为不可能有针对特殊情景和目标的通用答案.

如果你只想烤一个枣糕,我们给你十分确切的配方.我们会告诉你需要多长时间,多少鸡蛋,烤箱的温度是多少.甚至可以告诉你如何检查蛋糕是否做好.那是因为现代烘培几乎没有变化.无论你从哪购买,配料都基本相同.烤炉也被设计成在特定,标准温度下烘培.最重要的是,目标是一致的--获取指定的类型的蛋糕.

但你不是在做蛋糕,也没有所谓的食谱.你需要处理大量的可变性.例如,你公司里的人决策能力参差不齐.你所在的行业和地区特有的监管约束.还有就是你服务的不断变化的消费市场,有它自己消费文化.最重要的是,你的组织目标和策略对你来说是完全独特的.

这些可变性使得很难给API治理开出一个通用的"配方".同时小问题的连锁反应,加剧了它的实现难度.当你每次引入规则,创建新标准或者应用任何形式的治理,都需要处理它意外的后果.这是因为组织的各个部分都是相互联系的.例如,为了保证API代码的一致性和质量,你可以引入标准技术栈.随着程序员开始添加更多的库和框架,新技术栈可能产生更大的代码包.同时它还可能造成部署流程的改变,因为现存的系统无法支持更大的部署包.

有了正确的信息,你可能预测和预防这种结果.但是你不可能每次都能这样,尤其在适当的时间内.相反,你需要面对这个事实--你正在处理一个复杂的自适应系统.事实证明,它是一种特性,而不是漏洞.你只需要弄清楚如何利用它使你获益.

- 复杂的自适应系统

当你我们说你的组织是一个复杂的自适应系统时,我们的意思是:

- - 它有许多相互依赖的部分(如:人员,技术,流程,文化).

- - 这些部分可以改变自我行为,并且适应系统变化(如:当引入容器化时,改变部署惯例).

宇宙中充满了这样的系统,复杂性研究已成为一个已设立的科学学科.甚至你自己也是一个复杂的自适应系统.你可能认为自己是一个单独的个体--自我,但是"自我"只是一种抽象.实际上,你是一个有机细胞的集合,虽然只是一组细胞,但它具有令人惊叹的壮举:作为一个自然的整体"人"去思考,移动,感觉和对外部事件做出反应.在细胞层面,每个细胞各司其职,老的,濒临死亡细胞被替换,同时细胞群在你的身体里一起工作以产生具大的影响.这个复杂的生物系统使你身体具有高度的弹性和适应能力.你可能无法长生,但是你能平等的承受大量的环境变化,甚至身体的损害,这要归功于你复杂度生物系统.

通常,当我们在技术上说到"系统",我们关注的是软件系统和网络基础架构.这些类型的系统确实会变的复杂.如:web是一个系统级复杂性和突发性的完美例子.我们将单独运行的服务器相互依赖和互联后形成的自然整体称为"web".但是大多数软件并不是真正的自适应.

你曾经编写的API软件现在相当愚蠢.并不意味着你的代码质量不高或者它无法完成设计功能.事实恰恰相反.大多数你实现的API将完全按照它们应该做的去做.这恰恰是问题所在,你可以让API足够智能,以适应不断变化的交易模型和越来越多的错误,但是还无法做到让API在没有人为干预的情况下增加新功能,正确的自我修复漏洞,更新文档使其更易于学习.

在未来一切都可能改变.但是就目前而言,还是人为驱动软件系统.好消息是人的适应性很强(尤其和软件相比).你的API组织是一个复杂的适应性系统.组织内的所有人都会许多(有时集体,有时单独的)局部决策.当这些决策在量和时间上越来越多时,一个系统就产生了.就像你的身体,这个系统能够适应很多变化.

但是处理复杂系统要求一种特殊的方法.当你修改一部分时,可能造成另一部分意外的结果,使得很难预测复杂系统变化的影响.这是因为组织内的人在不断适应环境的变化.如:禁止使用"容器"部署软件将产生广泛的影响:它会影响软件的设计,人员,发布流程,以及文化.

所有这些都说明:你无法通过实现大的更改,以及等待结果的方式从系统中获取所需的输出.相反,你需要通过小的修改和评估它们的影响来慢慢"推动"系统的发展.它需要一种不断跳转和改进的方法,就像照料花园一样,修建枝条,播种,浇水,同时不断观察和调整你的方法.在第5章,我们将更详细地探讨持续改进的概念.

- 决策治理

在最后一节,我们介绍了复杂系统内决策治理的概念.希望它有助于你理解API治理的基本规则:如果你想有效的治理系统,你需要更好的管理决策.我们它最好的实现方式是关注决策在哪发生以及由谁来做决定.事实证明,没有一种最好的方法能够将这些决策制定出来.如:思考如何在以下两个虚构的公司中进行API设计治理:

公司A: Pendant Software
> 在Pendant Software中,所有API团队都可以访问"Pendant API设计指南"电子书.这些指南由Pendant启卓API中心(公司内的API专家工作的小团队)每季度发布一次.这些指南包含了API设计中高度的规范性和非常具体的规则.所有团队都要遵守这些指南,并且在发布API之前进行自动化一致性测试.
> 由于这些政策,Pendant已经能够发布一组行业领先,高度一致,有利于开发的API.这些API已经帮助Pendant从同市场上的对手中脱颖而出.

公司B: Vandelay Insurance
> 在Vandelay中,给API团队设立了API产品的公司业绩目标和期望结果.这些目标和结果由执行团队定义并定期更新.每个API团队都可以自由地选择执行方式处理总业绩目标,并且多个团队可以设立相同的目标.API团队可以根据自己的喜好设计和实现API,但是每个产品必须遵守Vandelay的企业测量和监控标准.这些标准由Vandelay系统公社定义,这个公社由来自于各个API团队的自愿加入的人组成,并定义大家都需要遵守的一系列标准.

> 由于这些政策,Vandelay已经能够构建高度创新的,自适应API架构.这个API系统使得Vandelay在它的技术平台,可以通过快速交付的创新业务实践在竞争中更胜一筹.

通过上面的虚构案例可以发现,Pendant和Vandelay都很成功的管理了决策.但是它们治理的方式却完全不同.Pendant的成功取决于高度集中化,军事化的方法,但是Vandelay倾向于面向结果的方式.两种方式虽然都称不上"正确",但它们的治理方式都有可取之处.

为了有效的治理决策,你需要解决三个关键问题:

1. 哪些决策需要被管理?

2. 需要在哪里(以及由谁)做出这些决策?

3. 你的决策管理策略将如何影响系统?

我们在本书的后面再深入讨论"哪些决策需要被管理"和"这些决策对于系统的影响".现在,我们先看第二个问题:系统中最重要的决策需要在哪做出.为了帮助你解决决策分配的问题,我们将深入研究决策治理的主题.我们将权衡集中式决策和分散化决策,更仔细的研究分配决策的含义.

- 中心化和去中心化

在前面,我们以人体为例介绍了复杂自适应系统的概念.这种类型的系统在自然界非常多,可以说你的周围都是这种系统.如:小池塘里的生态系统就可以被认为是一个复杂自适应系统.生活在里面的动植物的活动和相互依赖,给予了池塘持续的活力.由于这里的生物的局部决策,赋予了生态系统适应环境变化的能力.

但是池塘没有管理者,也没有证据证明青蛙,蛇和鱼会每季度举办管理会议.相反,这个系统里的每一个代理都单独做决策,以及展示独立的习性.这些独立的决策和行为整合在一起形成了一个共同的,自然的整体,使得这个整体即使在部分系统变化或者随着时间兴衰交替仍然可以生存.与大多数自然世界一样,池塘系统的成功取决于分散的系统级决策.

正如我们之前确定的,你的组织也是一个复杂自适应系统.它是所有员工做出个人决策后的共同产物.就行人体和池塘生态系统,如果你赋予员工完全的自由和自主,整个组织将变得更有弹性和适应性.由于员工的个人决策,这个无领导,去中心的组织可以发现自己的路.(见图 2-1).

![](../img/2/capi_0201.png "每个人都在做决策")
<center>图 2-1. 一个去中心化组织</center>

你可以像上面那样做,但是你可能会遇到一些问题.主要是因为复制自然界复杂系统成功的方式很难应用在自由市场的组织中.池塘的生物系统是自然选择的结果.系统中的每个生物都为了种族延续而进化.它们的系统级目标只是活着.除此之外,在自然中,系统故障是正常现象.如:如果引入外来物种,整个池塘系统可能会被摧毁.在自然界中,这是可以的,因为外来生物会取代原来生物的位置--对于系统来说依旧富有弹性.

然而,企业领导不希望这种不确定和失控的局面出现.你需要将系统引导到的特定目标,这可能超越了生存的目的.而且,你可能不愿意为了让更好的公司取代你而冒着让公司倒闭的风险.你完全希望降低因个人的错误决策而毁掉整个公司的风险.这意味着你需要约束个体决策制定的自由,并引入一些职责.一种实现方式就是决策中心化.(图 2-2).

![](../img/2/capi_0202.png "一个人做出所有决策")
<center>图 2-2. 一个中心化组织</center>

由上可知:做出决策的往往是你组织内的部分人或团队.中心化团队做出的决策公司其他人都要遵守.去中心化恰恰相反:自己遵守自己做出的决策.

事实上,没有纯粹的中心化或者去中心化组织.相反,在组织内不同类型的决策会被分配不同的实现方式--一些更集中,一些则更分散.你需要决定如何分配对你系统影响最大的决策.那么,哪些应该更集中,哪些又应该更分散那?

记住,决策治理的主要目的是帮助你的组织成功,并活下去.这意味着什么,完全取决于你的业务背景,但是通常来说,它意味着:决策需要足够及时,以实现业务的敏捷性,需要具备足够的质量来改进业务(或至少避免损害业务).影响决策能力的因素有三个:

信息的可用性和准确性
> 如果根据错误或者残缺的信息,很难做出好的决策.这可能意味着误解决策目标或背景,也可能意味着决策会对系统造成意外的影响.大多数情况,相对于决策者,我们负责收集决策制定信息.但是为了决策分配,我们还需要思考集中或分散决策是如何影响可用的信息的.

决策人才
> 通常来讲,如果决策者擅长做出高质量的决策,那么决策的质量也会提高.简单来说,就是老油条的牛人会比没经验的菜鸟做出更好的决策.当涉及分配决策时,难点在于如何进行最有效的人才分配.

协调成本
> 复杂决策无法及时做出,除非你分散决策.但是当你分散决策工作时,你将发生协调成本.如果协调成本太高,你就无法快速的做出决策.决策的集中和分散会对协调成本产生很大的影响.

根据这些因素来考虑决策,有助于你判断决策应该集中还分散.为了帮你理解时如何做到这一点的,我们将从两个角度分析它:优化范围和运营规模.让我先从规模和它与决策信息关系开始.

- 优化范围

中心化决策和去中心化决策最大的不同与它们的规模有关.当你做出中心化决策时,你是在为整个组织做决策.所以,你的决策范围涵盖了整个系统,你的目标是做出改进系统的决策.换句话说,就是你所做的决策是为了优化系统范围.如:一个中心化团队可能决定整个公司的开发方法.它还可以决定系统中哪些API应该停用.这两项决策的目的都是为系统做出最好的事情.

相反的,去中心化决策的主要特征是它针对局部范围进行优化.当你进行本地优化时,你将做出改善本地环境(一组只与本地情况相关的信息)的决策,虽然决策可能对更广泛的系统产生影响,但是你的目标只是改善本地成果.如:API团队可以做出使用瀑布流开发流程的决策,因为他们正在和其他已经使用它的公司共同工作.

分散决策的好处是它可以帮你从整体业务的效率,创新和敏捷性方面获得巨大收益.这是因为去中心化的决策者可以把信息范围限制在他们理解的本地环境中.这意味着他们可以根据问题范围内的准确信息做出决策,从而帮助他们做出更好的决策.对于任何想通过敏捷性和创新的方式获取成功的现代企业,去中心化决策方式应该是默认的选择.

但是,只专注于优化局部范围做出的决策是有问题的,尤其是当这些决策对系统有潜在的不可逆转的负面影响时.亚马逊CEO杰夫·贝佐斯在谈到决策的影响时,将其分为两类:一类是错误的决策很容易被推翻,另一类是几乎是不可能恢复的决策.如:许多大公司在API安全配置上选择中心化决策,以防止本地优化造成的系统漏洞.

除了对系统的危害之外,有时系统间的一致性比局部优化更有价值.如:单个团队可能会选择对问题领域内最有意义的API风格.但是如果每个API团队都有自己的API风格,由于缺少一致性,学习去使用每个API将变得更加困难,尤其是当多个API需要公共完成一件事时.在这种情况下,优化系统范围上的API风格决策可能更好.

当你规划应该在哪里进行决策时,你需要仔细考虑优化范围.如果决策对你的系统有潜在的不可逆转的影响,那么首先对它进行中心化决策,以便它在系统范围进行优化.如果局部环境信息有利于提高决策质量,那么应该先对它进行去中心化决策.如果去中心化决策在系统层面会造成不可接受的不一致性,那么考虑中心化决策.

- 运营规模

如果你有无限的资源支持做出好决策,那么你只需要考虑做出决策的范围.但是你没有.所以,除了范围之外,你还需要考虑做出决策的规模.这是因为如果这是更大的决策需求,你的决策人才供应将面临更大的压力,协调成本的压力也将会增大.如果你想API工作随着组织的发展而发展,则需要仔细的规划决策分配模型.

当你大规模经营时,去中心化决策会产生巨大的人才需求.当分散一个决策时,你会将它分配到多个团队.如果你想所有决策都是高质量的,你将需要每个团队都充满有才干的决策者.如果你无法承担这些,那么你最终会做出很多错误的决策.所以,在你的公司里,为每个决策职位雇佣最好的决策者是值得的.

不幸地,招聘优秀人才并不是行业秘密.可供选择的有才能并且有经验的人是有限的,同时还有大量公司在抢着雇佣他们.还有一些公司不惜代价去确保可以获取这些顶尖人才.如果你足够幸运在这种情况下得到他们,你可以尽可能的分散你的决策,因为你有牛人去做出它.相反,你需要在决策分配上更加务实.

如果你可提供的顶级决策人才有限,你可以选择将这些人才集中在一起,并由这些人做出最重要的决策.这样,你就有更多的机会更快地做出更好的决策.但是决策需求规模的增加,还会对这个模型造成破坏.因为随着决策需求的增加,中心化团队的规模也需要跟着增加.随着团队的扩大,决策的协调成本也将会增加.无论员工多么有才,随着人员的增加,决策协调成本也会增加.最终会到一个决策无法承担的数字.

所有这些都意味着,决策分配会涉及许多的权衡.如果决策像杰夫·贝佐斯"类一"描述的那样有效,你将需要将它中心化,并以低决策吞吐量为代价.相反,如果速度和局部优化更重要,你可分散决策,要么招聘更优秀的人或者接受决策质量的下降.

也就是说,有一种方法可以更细致,更灵活处理这种权衡.它涉及到分配决策的各个部分,而不在决策之间,这也是我们下一节将重点谈论的内容.

- 决策元素

目前用上面我们描述的方式很难去分配决策,因为它们都是一些极端的处理方式.开发方法的选择是团队自己决定还是你来决定?你是让团队决定他们的API什么时候停用还是你来决定?实际上,治理要求的更精细.这本节中,我们将探索一种通过决策分解来更灵活的分配他们的方法.

你可以分配部分决策,而不是整个分配.这种方式可以让你同时从系统级优化和其关联的局部优化中获得好处.决策的一部分可以集中,其他部分可以分散.为了帮你完成这种类型的决策分配,我们将API决策分解为6种你需要分配的决策元素(见图2-3).

![](../img/2/capi_0203.png "开始,生成选择,选择,授权,实现和挑战")
<center>图 2-3. 决策元素</center>

这并不是权威的,通用决策模型.相反,它是我们开发的一个模型,用来区分对系统影响最大的中心化或去中心化的决策部分.这些部分是基于业务管理领域中大量存在的五步,六步和七步决策模型.虽然我们描述的步骤可以应用于个人做出的决策,但是它应用于一群人协商做出的决策时是最有效的.

首先,让我们看一下决策的初始分配是如何影响你的系统的.

- 开始

决策的出现是因为有人认为需要做出决策.它意味着有人已经从多个可能的解决方案发现了存在的问题或机会.有时候这是显而易见的,但是大多数时,发现决策机会需要人才和专业知识.你需要考虑哪些决策可以自然出现,哪些需要特殊处理才能确保它发生.

在日常解决问题的过程中,API工作的启动决策很常见.如:对于一个典型的实现人员来说,选择用于存储持久化数据的数据库将是一个难以忽视的决策.这个决策的出现是因为没有它就无法工作.但是也会有需要强制启动的情形,这通常有两个原因:

决策惯性
> 随着时间的推移,如果团队总是做出相同的决策,那么这个决策可能会消失.也就是说,不再考虑各种可能性,而是假设工作将以它一贯的方式进行.如:如果每个API的实现都使用Java语言,其他人可能就不再考虑选择不同的语言.

决策盲区
> 有时候,团队可能错失做出有力决策的机会.这可能由于习惯,也有可能是由于信息,经验和能力的限制.如:团队可能关注选择哪一种存储数据库,但是他们并没有看出,API可以设计成不需要持久化存储的方式.

并不是每个决策都需要实施,并且当决策被错失或者文化习惯让做出的决策更含蓄时,那就再好不过了.如果错失决策会对你从API获取的结果产生负面影响,这是一个问题.但是片面的要求做出更多决策,可能对生存率产生毁灭性的影响.相反,API治理的作用是产生更多的有益决策,较少的低价值的决策.

- 生成选择

It’s hard to choose if you don’t know your options, and that’s what this element is all about. Choice generation is the work of identifying the choices to choose from.

If you’re making a decision in a domain you have a lot of experience in, generating choices can be pretty easy. But if there are lots of unknowns, you’ll need to spend more time identifying the possibilities. For example, an experienced C programmer already has a good idea of their options when they are deciding on a loop structure, but a beginner will probably need to do some investigation to learn that they can use a for loop or a while loop and the differences between the two.

Even if you know a domain fairly well, you’ll probably spend more time on choice generation if the cost and impact of the decision are very high. For example, you may have intimate knowledge of the different cloud hosting environments, but will still perform your due diligence of research when it comes time to sign a contract with one of them. Are there new vendors available that you didn’t know about? Are the prices and terms still the same as you remember?

From a governance perspective, choice generation is important because it’s where the boundaries of decision making are set. This is especially useful when the people coming up with the list of choices are not the same as the people making the selection. For example, you could standardize a list of possible API description formats, but let individual teams decide which format they like best. If you take this approach you’ll need to be careful about the quality of the “menu” you are providing. If the choices are overly restrictive or of poor quality, you’ll run into problems.

SELECTION
Selection is the act of choosing from the list of possible options. Selection is the heart of decision making and it’s the step most people focus on, but the importance of the selection element depends a lot on the scope of choices that have been made available. If that scope is very wide, then the selection process is integral to the quality of the decision. But if that scope has been constrained to safe choices with little differentiating them, the selection step can be quick and less impactful.

Let’s walk through an example of this in action. Suppose you’re responsible for configuring Transport Layer Security (TLS) for your HTTP API. Part of that work includes a decision on which cipher suites (sets of cryptography algorithms) the server should support. It’s an important decision because some cipher suites have become vulnerable with age, so picking the wrong ones can make your API less secure. Also, if you choose cipher suites that your users’ client software doesn’t understand, nobody will be able to use your API.

In one scenario, you might be given a list of all the known cipher suites and asked to select the ones that the server should support. In this case, selection would need special care. You’d probably do a lot of research and only feel comfortable making a selection once you’d gathered as much information as possible. In fact, if you didn’t have a good amount of experience securing servers, you’d probably look for someone who did and ask them to make a selection for you.

But what if instead of being given the set of all possible cipher suites, you were given a curated list of them? The list of options might also include relevant information about how well supported each cipher suite is and what the known vulnerabilities are. Armed with this information you could probably make a faster choice. Equally, you’re choice is likely to be safer because your decision scope is limited to choices that have been deemed safe enough to use. In this case, you’d make a decision based on what you know about the clients using the API and the sensitivity and business importance of the API.

Finally, you might be given only one choice: a single cipher suite that you must use. A single-choice decision makes selection a trivial affair—the decision has been made for you. In this case, the quality of the decision is entirely dependent on the people who generated that choice. Hopefully it’s a good fit for the specific requirements you have.

So, the importance of selection depends a lot on the scope of the choices offered. There’s a bit of a trade-off at work here. If you push more of the decision-making investment into choice generation you’ll spend less time on selection, and vice-versa. That has implications for how you distribute decision elements and who should be responsible for them. Whichever decision element becomes more important will require a suitably talented decision maker to make it.

It also means you can combine system scope and local scope by distributing choice generation and choice selection. For example, you can centralize the generation of development method choices based on the system context while still allowing individual teams to choose their preferred method using their local context. This happens to be a particularly useful pattern for governing large API landscapes at scale and preserving both safety and speed of change.

AUTHORIZATION
Just because a choice has been selected doesn’t mean the decision is done. The selection needs to be authorized before it can be realized. Authorization is the work of deciding on the validity of the selected choice. Was the right selection made? Is it implementable? Is it safe? Does it make sense in the context of other decisions that have been made?

Authorization can be implicit or explicit. When authorization is explicit it means that someone or some team must expressly authorize the decision before it can go forward. It becomes an approval step in the decision-making process. We’re sure you’ve been involved in many decisions that required some kind of approval. For example, in many companies, workers can select their holiday time from a list of work dates, but it’s up to their manager to make the final approval decision on the schedule.

Implicit authorization means that authorization happens automatically when some set of criteria has been met. Examples of this are the role of the person making the selection, the cost of the selection that was made, or adherence to a specific policy. In particular, authorization can become implicit when the person making the selection is also the person authorizing the selection. In effect, they become their own approver.

Explicit authorization is useful because it can further improve the safety of the decision. But if there are lots of decisions being made and all of them are being centrally authorized, then there is likely to be a reduction in decision speed. Lots of people will end up waiting for their approvals. Implicit authorization greatly increases the speed of decision making by empowering selection, but comes with greater risk.

How authorization should be distributed will be an important decision for you to make in your governance design. You’ll need to consider the quality of decision makers, the business impact of bad decisions, and the amount of risk built into the choices offered. For highly sensitive decisions, you’ll probably want more explicit authorization. For time-sensitive, large-scale decisions you’ll need to figure out how to introduce an implicit authorization system.

IMPLEMENTATION
The decision process doesn’t end when the choice is authorized. A decision isn’t realized until someone does the work of executing or implementing the choice that has been made. Implementation is an important part of API management work. If the implementation of decisions is too slow or of poor quality, then all of your decision making is for naught.

Oftentimes a decision isn’t implemented by the people who made the selection. In these cases it’s important to understand what that means for the availability of accurate information gathering. For example, you might choose to introduce the hypermedia style of APIs into your landscape, but if the implementation of hypermedia APIs turns out to be too difficult for the designers and developers you’ll need to re-evaluate your decision. A good governance design will have to take these practicalities into account. It’s no good managing decisions in a way that makes them only theoretically better. When you are determining the quality of decision making you’ll need to include the implementability of the decision you are managing.

CHALLENGE
Decisions aren’t immutable, and each decision you make for your API management system should be open to being challenged. Oftentimes we don’t consider how the decisions we make may need to be revisited, altered, even reversed in the future. Defining a challenge element allows us to plan for continuous change at the decision-making level.

For example, if you’ve defined a “menu” of choices for API teams to choose from, it’s wise to also define a process to go “off-menu.” That way you can sustain a decent level of innovation and prevent bad decisions from being made. But if everyone can challenge the decision to constrain these choices, then there aren’t really any constraints. So, you’ll need to identify who can challenge the decision and in what circumstances.

It’s also important to allow decisions to be challenged over time. As business strategies and context change, so too should the decisions of your system. To plan for that kind of adaptability you’ll need to build the challenge function into your system. That means you’ll need to think about whom in your organization will have the ability to “pull the cord” and challenge an existing decision.

Decision Mapping
We now know that decisions are composed of a number of elements. Understanding that decisions have atomic elements allow us to distribute the pieces of a decision rather than the entire decision process. This turns out to be a powerful feature of organizational design and will allow you to exert greater influence over the balance of efficiency and thoroughness.

For example, a decision about the style a new API should have is an important one. In the clumsy, binary centralization versus decentralization discussion, the API management designer might consider whether the members of the API team should own the API style decision (decentralized) or a central body should maintain control of it (centralized). The advantage of distributing the decision-making power to the API teams is that each team can make the decision within a local context. The advantage of centralizing the decision within a single strategic team is that the variation in API styles is reduced and control over the quality of the style choice is maintained and controlled.

This is a difficult trade-off to make. But, if instead you distribute the elements of the decision, it’s possible to design an API management system that lives somewhere in between these two binary options. For example, you might decide that for an API style decision, the elements of research and choice generation should be owned by a centralized, strategic API management team, while the elements of choice selection, authorization, and implementation are owned by the API teams themselves. In this way, you choose to sacrifice some of the innovation that comes from distributing choice generation in order to gain the benefits of a known set of API styles within the company. At the same time, distribution of the API style selection and authorization elements allows the API teams to continue to operate at speed (i.e., they do not need to ask permission in order to choose a suitable style).

To get the most out of decision mapping, you’ll need to distribute decisions based on your context and goals. Let’s take a look at two fairly common decision scenarios to see how decision mapping can be a useful tool.

DECISION MAPPING EXAMPLE: CHOOSING A PROGRAMMING LANGUAGE
You’ve identified that the decision of which programming language to choose for API implementation is highly impactful, and you’d like to govern it. Your organization has adopted a microservices style of architecture, and freedom to choose the programming language for implementation has been raised as a requirement. But after running a few experiments, you’ve noticed that variation in programming languages makes it harder for developers to move between teams and harder for security and operations teams to support applications.

As a result, you’ve decided to try out the decision distribution in Table 2-1 for deciding on a programming language.

Table 2-1. Programming language decision map
Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
Centralized

Centralized

Decentralized

Decentralized

Decentralized

Decentralized

This way you constrain the programming languages to a set of choices that are optimized for the system as a whole, but allow the individual teams to optimize for their local contexts within those constraints. You’ve also allowed API teams to challenge the decision so that you can accommodate new language choices and changing situations.

DECISION MAPPING EXAMPLE: TOOL SELECTION
Your CTO is trying to improve the level of agility and innovation of your software platform. As part of this initiative they have decided to allow API teams to choose their own software stacks for implementations, including the use of open source software. However, your procurement and legal teams have raised concerns based on legal risks and risks to supplier relationships. To get started with this cultural transition, you’ve decided to implement the decision map in Table 2-2 for the software stack decision on a trial basis.

Table 2-2. Tool selection decision map
Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
Decentralized

Decentralized

Decentralized

Centralized

Decentralized

Centralized

Local optimization is one of the keys to your CTO’s strategy, so you chose to completely decentralize inception, choice generation, and selection. However, to reduce the system-level risk of a choice, you’ve mapped the authorization element to the centralized procurement and legal teams. This should work for now, but you are also aware that over time and at scale this has the potential to be a big bottleneck in your system, so you make a note to keep measuring the process and tune it accordingly.

Designing Your Governance System
We’ve spent a lot of time going into the details of decision distribution because we think it’s a foundational concept for a governance system. But it’s not the only thing you’ll need to pay attention to if you want to introduce effective API governance. A good API governance system should have the following features:

Decision distribution based on impact, scope, and scale

Enforcement of system constraints and validation of implementation (from centralized decisions)

Incentivization to shape decision making (for decentralized decisions)

Adaptiveness through impact measurement and continuous improvement

It’s difficult to get the advantages of decision centralization if the rest of the organization doesn’t conform to the decision. That’s why enforcement and validation needs to be a feature of an API governance system. We’ve purposefully steered away from the authoritative parts of governance so far, but ultimately you’ll need to build at least some constraints into your system. Even the most decentralized organizations have rules that need to be followed. Of course, validation and enforcement will require some level of obedience. If the centralized decision-making team has no authority, the decisions will carry no weight.

If you don’t have authority, you can use incentivization instead of enforcement. This is especially useful when you’ve decided to decentralize decisions but still want to shape the selections that are being made. For example, an architecture team could alter a deployment process so that deployment of immutable containers is made much cheaper and easier than any other type of deployment. The goal here would be to incentivize API teams who have authority over their own implementation decisions to choose containerization more often.

In truth, neither the “carrot” of incentivization nor the “stick” of enforcement is enough to steer your system on its own—you’ll need to use both. Generally speaking, if a decision’s authorization element has been decentralized, you’ll have to use incentivization if you want to shape it. If selection and authorization have been centralized and implementation is decentralized, you’ll need to make sure you’ve instituted some level of enforcement or validation. Table 2-3 highlights when you should enforce or incentivize a decision based on your decision mapping design.

Table 2-3. When to enforce and when to incentivize
Enforce or incentivize?	Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
Enforce

Centralized

Centralized or decentralized

Centralized or decentralized

Incentivize

Decentralized

Decentralized

Decentralized

No matter how you distribute your decisions or change decision-making behavior, it’s crucial that you measure the impact you are having on the system itself. Ideally, your organization should have some existing process indicators and measurements that you can use to assess the impact of your changes. If there isn’t anything like that, instituting organizational measurements should be one of your first priorities. Later, in Chapter 6, we’ll talk about product measurement patterns for APIs. Although we’ll be focusing on API product measurement specifically, you can still use that section as an introductory guide for designing governance measurements for your system.

To help tie all this together, let’s take a look at three API governance patterns. These patterns capture different approaches to API governance, but all of them use the core principles of decision distribution, enforcement, incentivization, and measurement. Keep in mind, we aren’t offering you a menu—you aren’t supposed to choose one of these to be your governance system. We are offering you these patterns as a way of illustrating how an API governance system can be implemented at a conceptual level.

For each governance pattern described, we’ll identify a few key decisions and how they are mapped, how desired behaviors are enforced and incentivized, how talent is distributed, and the costs, benefits, and measures for the approach.

Governance Pattern #1: Interface Supervision
This pattern emphasizes the importance of the interface model for an API. Interface supervision centralizes all decisions related to the design of the interface in order to ensure that all interfaces are consistent, secure, and highly usable (see Table 2-4).

Table 2-4. Decision map
Decision space	Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
API design

Centralized

Centralized

Decentralized

Centralized

Decentralized

Decentralized

API implementation

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

Centralized

API deployment

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

Centralized

Enforcement and incentivization
API implementation and deployments are reviewed by the centralized interface design team. Although teams have the freedom to make their own implementation and deployment decisions, the central team can flag and remove an API if it doesn’t conform to the interface model.

Talent distribution
Interface design talent is pooled in the central team, while programming and operations talent can be decentralized.

Costs and benefits
The segregation of design and implementation teams means that there is a risk of making designs that are difficult or costly to implement. But this separation also benefits from a “pure design” perspective for the interface design team, which can produce more user-centric designs. At scale, there is a very high risk of a bottleneck due to the resource constraints of a centralized interface design team. This may especially be a problem when small changes to many interfaces are required.

Impact measurements
API usability measurements
Product and project schedule metrics
Implementation and operational issues
Governance Pattern #2: Machine-Driven Governance
Machine-driven governance uses the machinery of standardization and automation to constrain decision making. In this pattern, the centralized team tries to maximize control of the system with machinery, but limit the impact on decision-making throughput. This is done by only centralizing the decision space of API work (i.e., the choice generation element). Teams have the freedom to make decisions as long as they conform to the choices that have been codified into the standards (see Table 2-5).

Table 2-5. Decision map
Decision space	Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
API design

Decentralized

Centralized

Decentralized

Decentralized

Decentralized

Decentralized

API implementation

Decentralized

Centralized

Decentralized

Decentralized

Decentralized

Decentralized

API deployment

Decentralized

Centralized

Decentralized

Decentralized

Decentralized

Decentralized

Enforcement and incentivization
Because the choices have been implemented in a standardized way, all aspects of design, implementation, and deployment can be validated automatically with tooling. For example, API teams must document interface designs in a machine-readable language, which is validated using a “lint” tool.

Talent distribution
The central team needs to be populated with highly experienced designers, implementers, and architects to ensure that the centralized choices are the best ones. If the centralized choices have been made holistically and are of good quality, there is less of a talent requirement for designers and implementers in the decentralized teams.

Costs and benefits
Machinery is always expensive to design, create, maintain, and tune. There will be a large initial investment to create the best set of standards for this type of system and a consistent challenge in keeping the choices and tools up to date as contexts change. But the payoff comes in the form of a reduced need for distributed decisions and an improvement in decision-making throughput thanks to automation. One possible system impact of this pattern is unhappiness within API teams due to a loss of freedom—if the choices are too constrained, it may be difficult to attract good people.

Impact measurements
Product and project schedule metrics
Choice popularity (tracking when and how standardized choices are used)
API team metrics
Governance Pattern #3: Collaborative Governance
In the collaborative governance pattern, API decisions are made individually, but a shared understanding of system impacts is developed collaboratively. The goal is to create a “shared brain” in terms of the system-level view, but maintain the speed and local optimization scope of a decentralized system (see Table 2-6).

Table 2-6. Decision map
Decision space	Inception	Choice generation	Choice selection	Authorization	Implementation	Challenge
API design

Centralized

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

API implementation

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

API deployment

Decentralized

Decentralized

Decentralized

Decentralized

Decentralized

Centralized

API measurement

Centralized

Centralized

Centralized

Centralized

Decentralized

Decentralized

Enforcement and incentivization
In collaborative governance most of the decisions are completely decentralized, with the exception of an API’s inception and its measurement. This creates a “results-oriented” view of APIs in the system. It follows that enforcement is entirely results-oriented—if the API doesn’t achieve the expected result it is retired and the team may be disbanded. Although design, implementation, and deployment decisions are decentralized, those decisions are typically influenced through incentivization. For example, if a team’s decisions produce favorable results and those decisions are shared with the organization, they can be financially rewarded. The combination of a reward and transparency can influence the decisions of other teams in the organization.

Because most of the work is decentralized, collaboration between teams will need to be encouraged. That means that collaboration should be incentivized (or enforced) at the system level.

Talent distribution
A collaborative governance pattern is talent-intensive. This level of decentralization requires a suitable level of talent distributed amongst the teams. It doesn’t mean that every single worker has to be a star employee, but it does mean that each team needs enough talent to produce safe, high-quality decisions consistently.

Costs and benefits
Highly skilled decentralized teams can produce innovative APIs of high quality. The main costs to achieving this are in talent and support for collaboration. As the scale of work increases, so too will these costs.

Impact measurements
API product metrics
API team metrics
Usability metrics
Summary
In this chapter we gave you our definition of governance: managing decision making and decision implementation. From that definition, we took a closer look at what it means to make a decision and what it means to govern a decision. You learned that API decisions can be small (“What should my next line of code be?”) or big (“Which supplier should we partner with?”) and can range massively in scope. Most importantly, you learned that the system you are trying to govern is a complex adaptive system, which means it’s difficult to predict the results of any decision management strategy you apply.

Next, we took a closer look at decision distribution and compared centralization and decentralization. To help you understand the differences, we compared them in terms of the scope of optimization and scale of operation. Then we discussed how you can break decisions down into their essential elements of inception, choice generation, selection, authorization, implementation, and challenge. By putting all of these concepts together, along with some enforcement and incentivization, you can build an effective API governance system.

Governance is at the heart of API management, so it’s not a big surprise that it’s a core concept for this book. Our goal in this chapter was to introduce the major concepts and levers of governance. In the rest of the book we’ll dive deeper into the domain of API governance by tackling the specific challenges of which decisions matter the most, how to manage the people involved, and what to do as APIs mature and the scale of the APIs grows. In the next chapter, we’ll start that journey by investigating how product thinking can help you identify the API work decisions that matter the most.