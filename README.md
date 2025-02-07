基于Java、MySQL的毕业设计，房屋租赁系统


1  绪论
1.1 房屋租赁系统的意义及必要性
在房地产投资愈演愈烈的今天，加之人们生活水平的逐渐提高，手中可以支配的钱越来越多，很多人都把眼光放在了房产投资上了，因为房子的升值空间大到让人难以想象。还有城市化进程原来越快，涌入城市的人也越来越多，他们进入城市谋生首先要解决的就是住房问题，所以租房也便成为了热点。进而，有一个房屋租售平台是很有必要的，有了这个平台人们可以很快找到自己所需要的信息，使房屋租赁不成问题。

1.2 房屋租赁系统的开发背景及现状
现在通过网络进行房屋管理还不是很热门，有很多人还不知道网上看房，网上卖房。我们经常会在各个小区看见一个专门的宣传栏，上面贴满了求租房屋或者租售房屋的打印广告纸，这不光对小区环境的影响很大，而且有需求的人很难在这些杂乱的信息中找到自己需要的信息，就算找到了也有可能信息已经失效了，所以这种宣传栏的存在起不到什么作用。还有现在存在的房屋租赁最多的形式是实体店，有需求的人们大多数会去这种实体店咨询房源或者告诉工作人员自己房子的信息。这种方式已经不能适应现在快节奏的都市生活，工作这么忙碌的人们还要抽时间专门跑去店里咨询，给客户带来了很差的体验感。最重要的一点是，这种房屋中介是以盈利为目的的，会以高于出价者的价格出售或出租，从中赚取差价，这样会增加买房或租房者的负担。

据调查，大部分想找房源租房的人都很苦恼，因为想以低价租房或者买房，每天都东奔西跑的去各个小区寻找合适的房源，耗时又费力。所以这种房租租赁的现状是很不理想的。

1.3 房屋租赁系统的研究方向和实际目标
计算机的产生，给我们的生活带来了很多的便利，现在计算机化、网络化、信息化趋势已经越来越明显，各行各业纷纷改革，以信息化和计算机化为目的，能否利用计算机进行日常运营管理也已经成为一个改革的必经之路。它的优点是我们人类手工管理无法比拟的。比如说：更高的可靠性、更大的存储量、更快的处理速度、更长的寿命、更低的成本。这一些优点都可以使我们的工作效率大大提高，解放更多人力去干别的事情。计算机技术的发展速度远比我们想象的要快的多，而且它在很多方面的应用都已经得到了普及，从科学研发到工业、农业生产，从企业管理到医疗行业，都是靠计算机技术的参与实现的。

随着房地产业的迅速发展和涌向城市的人口日也增多，房屋租赁已经成为热点。根据统计，以往的房屋租赁都是通过中介或者电话预约进行租赁，传统的租赁模式由于信息量大很容易造成信息不准确、不及时的问题，这些问题造成的严重后果是很难解决的，即这种方式已经不适用于现在这个信息化时代。

房屋租赁系统是房产与计算机技术的完美结合，使得房屋信息得到了精准化的管理。首先，对于管理者来说，可以使他们摆脱以往杂乱的数据，提高了信息处理效率，可以为用户提供更好的服务。同时，管理人员通过对自身不断充电使得自身素质不断提高，也更能适应多变的工作环境。其次，由于系统操作难度校小，用户可以通过计算机平台用户可以修改自己的信息、自己的出租信息、自己的求租信息等。再次，管理员可以对后台进行全面的管理，更好的把控用户的信息。

1.4 论文的结构
此论文分为五章，主要包含了一下内容：

第一章主要介绍了房屋租赁的背景、现状以及做这个系统的必要性。

第二章分析了系统用什么技术来开发，并在经济、技术、操作以及经济四个方面讨论了它的可行性，还有对系统的用例和模块图做了简单介绍。

第三章用表和图的形式展示了一下本系统对于数据库的相关设计。

第四章通过对系统的总体设计和实现，以系统的各个功能界面为引据，详细介绍了熊的各个功能，主要包括管理员及用户的各个界面等。

第五章对我做毕业设计以来的总结，包括对论文的总结和对收获的总结，也对未来进行了展望。

 

 

2  系统分析
系统分析是通过需求人员与客户通过交流沟通的方式得到专业知识，然后对需求进行分析，最后运用上述得出来的分析解决开发者存在的疑惑，进而得到答案。系统分析在软件开发过程中是很重要的，要着手一个项目就必须要对这个项目做需求分析，例如了解这个做这个程序的目的是什么，以及应该包含哪些功能，这样做可以减少开发过程中需求更改和无关紧要因素的影响。

2.1 系统开发功能
本系统是针对房屋出售、出租、求租、求售功能展开设计的，系统采用了两种不同的身份，一种是管理员的身份，另一种的注册用户的身份。他们所对应的功能是不同的，数据信息都保存在不对外公开的数据库中，这样可以数据防止误删或恶意删除。该网站实现的主要功能有：

用户设计
用户通过真实注册自己的相关信息，包括姓名、电话，还要给自己的账户设置一个密码，之后就可以发布自己想要出租或者出售的房屋信息，对自己房屋的信息进行删除和修改也是可以的。

管理员设计
  首先操作人员需要输入用户名和密码，验证成功之后就可以对系统中注册的用户进行管理。

数据库设计
数据库包括用户和管理员的基本信息、出售信息、出租信息、求租信息、合同信息、新闻信息等。

2.2 可行性分析
在系统完成设计过程中，难免会受到空间或时间带来的种种束缚。就据此而言，系统的可行性就显得尤为重要，所以在这里，我从以下几个方面进行具体分析，大致包括经济上的可行性以及技术和操作上的可行性。

2.2.1 经济可行性
相对于其他的开发，网站开发成本不是很高，这样可以削减很多的精力和资源，然后能投入到其他方面开发，具有提升设计的作用。而且对计算机的配置要求也很低，中低端的服务器或者桌面PC机都可以使用。本系统采用的软件都是开源的，这样也可以使开发成本大大降低。所以满足经济的可行性。

2.2.2 法律可行性
本系统的开发完全符合国家的法律规定，不包含宗教、政治、民族等色彩问题，不添加任何虚假广告以及黄赌毒等垃圾信息 。因此在法律上完全具有可行性。

总结以上叙述，此系统在经济、技术、操作、法律上完全具有可行性。

2.2.3 技术可行性
系统利用了MyEclipse为开发平台，MySQL用来创建数据库和表以及表和表之间的关系设计，开发语言为Java，使用了SSH框架技术。之所以这样选择，是因为这种面向对象的语言对我来说容易操作，在大四实训的时候就是专门学的Java，对Java的主要知识和JavaWeb和框架技术的操作也都有所掌握。在学校里学习的UML统一建模语言也有助于我对系统的分析。据此，可行。

2.2.4 操作可行性
系统操作起来无论是对熟悉电脑的人还是第一次接触电脑的人都比较容易，且具有良好的可视性，这样既准确又省时。在输入时间的选项中会自动弹出日历控件，大大降低对操作人员的要求。可以这样说，只要用户识字并且会基本的Windows操作，操作此系统是没有问题的。因此在操作上完全具有可行性。

2.3 开发工具及技术
本房屋租赁系统使用了Tomcat作为服务器，并且还使用了JSP技术、SSH框架和JavaScript，通过MyEclipse来进行开发。

2.3.1 开发工具
1. MyEclipse

我们可以使用来进行数据库和J2EE的开发。它的功能很强大，几乎可以涵盖各种设计功能。它通过对应用程序服务器的整合，可以极大的提高运算速度。

2.Tomcat

Tomcat对我们开发人员来说是经常使用的一个服务器，不仅因为他是免费的，而且它还是一个比较小的轻量级的应用服务器，我们在进行调试时经常可以用到它。同时它也是我们的最佳选择。它有免费、性能稳定、技术先进的优点，所以既得到了Java爱好者的青睐又让很多软件开发商高度认可。在目前看来，它是最主流的Web应用服务器。

2.3.2 JSP技术
JSP是Java服务器页面，它在根本是就是一个简化的Servlet设计。JSP技术开发的Web应用是可以跨平台的，可以在不同的操作系统上运行。除了像普通Web页面使用标准标记语言的元素（比如HTML标记）之外，JSP还可以包含特殊JSP标记。由于JSP可以用于从数据库中获取数据或向数据库里写入数据，所以开发人员可以通过JSP将动态内容添加到网页中。

由于JSP具有跨平台运行、易上手、运行效率高等优点，所以我选择了它。

2.3.3 SSH框架
SSH框架实际上是一个集成框架，是由spring、 struts和hibernate构成[1~9]。表示层、数据持久层、业务逻辑层和域模块层是SSH框架在职责上所分的四层。此框架可以使开发者很快就构建高品质的Web应用程序。Struts框架模型的部分是控制业务的跳转，通过Hibernate框架为持久层提供相应支持，Spring来管理hibernate和struts，MVC的分离主要靠Struts框架。

2.3.4 JavaScript
JavaScript是一种可以在运行过程中可以逐行解释的解释型脚本语言。它可以创建对象也可以用已经存在的对象，它的操作是面向对象的。它运用弱类型变量类型，需要使用的数据类型并没有做出严格要求，是语句上类似Java的简单脚本语言。它利用事件驱动，对鼠标、键盘等的操作直接给出相应的响应，让网页和客户之际的互动更具有及时性、交互性、动态性，而且只需要浏览器的支持，不用依赖于特定的操作系统。

2.4 系统功能模块图
本系统分为管理员模块和用户模块。

用户模块包括：系统首页、新闻资讯、出租信息、求租信息、出售信息、合同模板下载、注册。

管理员模块包括：用户管理、租房信息管理、修改密码、新闻资讯管理、求租信息管理、合同信息管理。

下面是根据系统的设计画出的模块图，如图2.1所示。



图2.1 系统功能模块图
更多毕业设计、论文内容 加QQ：1184131126
# -
专业定制计算机专业毕业设计，QQ：1184131126，公众号：计算机专业毕业设计（ITJSZXG）
