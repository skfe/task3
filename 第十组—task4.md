






校园商品交易改造项目Web建模
简介
应用领域
   该网络平台适用于校园局域网的范围。随着现在高校的扩招与校园信息化的开展，校园网络的建设将进入一个更加高速发展的时期，发展校园电子商务的硬件环境将更加完善，建立属于高校大学生自己的交易平台问题需要迫切的予以解决。
     大学生具有相似的消费心理、共同的生活环境、生活方式，大多数交易物品都是学生自身需要的，交易商品具有共性（如：书籍、电子产品、自行车、体育用品等），使得学生之间交易的更为频繁，这是造成交易需求压力的原因之一。
     虽然校园的睿思网校园交易板块已经部分实现了校园网交易的作用，为大家提供了方便。但是我觉得这样还不够，校园交易板块的作用远远没有发挥出来，除了因其规模太小限制发展外，还有许多问题需要解决，所以，我认为应该对校园交易板块进行一次改造，事情更好的发挥作用，为大家提供更大的便利。
项目背景
   随着在校学生数量增多，大学生交易需求旺盛 。在写建议书之前，我去校园睿思网上浏览了一下，校园网交易板块的发帖总数有61W，最近的回复是在30秒前。进入转让的页面，都是以发帖的形式推销自己的东西，主要是大四学长出售一些临走前的“库存”，电风扇，轮滑鞋，ipad，运动鞋，电脑散热器，手机，充电器，书籍，甚至还有木鱼（没错，就是和尚用的，学长建议考试前敲一敲），总之是各种东西，应有尽有。还有求购的页面，有求购平板电脑，内存条，自行车，实验电路板，等等。
      大学生的消费水平大多数来源于家庭的经济支持，如果能用更少的钱，买到更实用，更物美价廉的东西，岂不是一举两得。何况校园内的交易能让大家更加放心，比网上的提货速度更是不知道快了多少倍。遇到质量问题，绝对可以找到卖家本人，权益百分百的得到保证，不过在校园网上出现交易质量问题的，少之又少，基本上不存在问题。不过，即使交易平台发挥了如此大的作用，依然难以满足大家的需求。
   现存交易平台弊端①：以发帖的方式出售东西，如果短时间没有交易出去的话，你的帖子会被大家淹没，石沉大海，当然，求购的帖子也一样。这样的话，本来有可能完成的交易，就有可能因为主观条件的限制，被扼杀在摇篮里面。

   现存交易平台弊端②：交易板块的一条帖子是一个同学所要出售的东西，但是他的东西，多而杂乱，如果有人要买的东西他手上正好有，是不是还得一条一条帖子慢慢的去浏览啊。

   现存交易平台弊端③：现在的交易平台在校园论坛中的位置太过于偏僻，也没有明显的标志，如果不是逛交易板块的常客，使用起来非常的不方便。内部界面也过于简洁，不利于交流。
目标和方法
   将交易板块独立出来，改造为一个交易平台。交易平台供大家免费注册，可以以学号为注册账号。
   在技术方面，对原有的交易板块的发帖模式进行保留，但是借鉴淘宝等大型购物网站的模式，对加入出售的商品和求购的商品建立条件搜索，并排列的方式，尤其是每个出售的商品都要附带其商品说明，价格，出售者的联系方式。
   对平台的界面进行设计，方便大家的浏览和查找
   商品的分类可以按照以下方式：
  1.电子产品：手机，MP3,MP4,MP5,音箱，电脑等等。
  2.书籍产品：专业课本，名著小说，各种考试复习材料等等
  3.生活用品：台灯，风扇，被褥，水桶，脸盆，电吹风，水壶，衣架，凉席，等等
  4．各种体育用品，交通工具，学习用品，乐器等等
  5.教育娱乐指南，面向于各种旅游团购，手机话费优惠，校园社区音乐学习班，小米购机券等等。
当然，有关键字搜索的话，可以直接找到符合你要求的物品。
关于帖子的问题，可以看做是淘宝的店家，交易平台对帖子的商品进行数据库备份和录入。当然，因为人力的关系，需要出手的人，自己上传数据库。一旦交易完成，出售者返回信息，然后系统对商品进行删除，保持商品信息的时效性。
预期结果
   新平台的建立，需要扩建学校的服务器，网站的制作工作对于学校的校园网制作团队来说只是个小case，同时需要和数据库做好链接和数据更新的工作，当然如果遇到技术困难的话，我们可以随时找老师请教，我们学校高技术的老师可是相当厉害的。
   在校园内也要进行一次大型的宣传，可以与社联协商，让大家在知道交易平台存在的同时，能够多多的去参与。将网络与跳蚤市场联合起来，在毕业季的时候，合理利用校园平台的优势，让学长可以轻松地离开学校，大家可以实惠的满载而归。
Web应用建模
功能需求建模：
用例图：
![用例图1][1]
[1]:http://fmn.rrimg.com/fmn060/20130530/2200/original_afuW_5e2300001c091190.jpg
该用例图主要说明了系统中主要的两个对象，买家和卖家所包含的各自的用例：
对于卖家，卖家可以发帖，然后在帖中填写商品信息，最后出售商品。
对于买家，买家可以观看商品帖，或者按条件搜索商品帖，然后购买商品。
活动图：
![活动图2][2]
[2]:http://fmn.rrimg.com/fmn061/20130530/2135/original_RbI7_5d83000018e61190.jpg

活动图主要表现的是系统的整体概要运行活动，卖家会先发帖，然后填写商品帖中的信息，并发布。系统会将商品帖分类存放，并且在前台页面，提供买家观看，买家在观看后可以决定是不购买，还是购买，购买的话会形成订单，卖家可以出售商品。交易完成后，系统会自动删除商品帖。
内容建模：
类图：
![类图3][3]
[3]:http://fmn.xnpic.com/fmn057/20130530/2135/original_gkfW_4527000018f81191.jpg
该系统的类图主要有卖家、买家、用户、系统和商品类。其中，用户类泛化为卖家和买家类。而一个系统可以有多个用户和多个商品，而多个用户可以对应多个商品。这个系统类图，展示了各个类的详细属性和对应的方法，及相互关系。
状态图：
卖家状态图：
![状态图4][4]
[4]:http://fmn.rrimg.com/fmn062/20130530/2135/original_sKad_2960000018df118f.jpg
卖家状态图主要体现的是卖家的整体活动状态，卖家可以先发帖，然后填写信息，最后分类。
买家状态图：
![买家状态图5][5]
[5]:http://fmn.rrimg.com/fmn062/20130530/2135/original_MRs3_719200001657125d.jpg
买家图主要是体现买家各阶段状态，从观看帖到搜索商品帖，然后选择商品，在选择是，有可能有中意选中的也有可能不中意，如果有中意的，就选中，然后购买，不管是否选中，最后都会结束这个状态。
超文本建模：
超文本结构模型：
![超文本结构模型6][6]
[6]:http://fmn.rrimg.com/fmn060/20130530/2135/original_UNbk_5d13000018e61190.jpg
超文本是用超链结的方法，将各种不同空间的文字信息组织在一起的网状文本。超文本更是一种用户介面范式，用以显示文本及与文本之间相关的内容。现时超文本普遍以电子文档方式存在，其中的文字包含有可以链结到其他位置或者文档的连结，允许从当前阅读位置直接切换到超文本连结所指向的位置。
展示建模：
序列图：
![序列图7][7]
[7]:http://fmn.rrimg.com/fmn062/20130530/2135/original_t3q3_0ef0000018f7118c.jpg
时序图主要是体现的是该系统运行过程中的时序关系，卖家先发帖给系统，系统会反馈发帖是否成功，成功后填写信息，并在此发给系统，系统再次反馈，并且在前台展示给用户各个商品帖。买家可以搜索商品帖，然后得到系统反馈的商品信息。然后选择购买，卖家会告诉买家购买的结果。
页面布局：
![主页8][8]
[8]:http://fmn.xnpic.com/fmn057/20130530/2200/original_eQIH_0f7c00001c0c118c.jpg
![商品浏览页面9][9]
[9]:http://fmn.rrimg.com/fmn060/20130530/2200/original_4JyO_44d700001c251191.jpg
![商品浏览页面10][10]
[10]:http://fmn.rrfmn.com/fmn059/20130530/2200/original_Hbrb_440300001c321191.jpg
这个页面布局图，主要是对系统的整体布局进行架构设计，将页面进行概要布局，方便最后实现过程中，对页面的设计。
适应性建模：
![适应性建模11][11]
[11]:http://fmn.rrimg.com/fmn062/20130530/2135/original_DFnr_2950000018dd118f.jpg
适应性建模，主要是根据用户上下文特性，给用户提供合适的展示。通过两种方法：静态建模方法，不同上下文不同模型；动态建模方法， 一个模型加上适应性规则。最后产出适应性模型。







