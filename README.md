# recommand-system
关于我所理解的推荐系统及其实际的应用场景
1.我所理解的推荐系统 
  1.1为什么会存在推荐系统
  1.2推荐系统能解决的问题
2.实际应用场景

1.1为什么会存在推荐系统
  首先介绍一个概念叫做信息过载。它的意思是互联网上的信息过多，我们没法一个一个去翻阅从而找到自己喜欢的东西，所以人们想把信息分类，然后人们可以通过类别去找自己想要的内容，像最初的搜狐，网易和新浪，国外的雅虎，都是最初的互联网的门户网站。
  后来人们的需求逐渐细化，人们觉得分类过的信息还是太大了，而且我们很明确地知道我们想要什么，比如我想看周星驰的喜剧电影——《功夫》，我要点“周星驰”或“喜剧”的分类，慢慢找。这时，搜索引擎应运而生，人们可以通过搜索自己想查找的东西，比如直接搜功夫，就可以搜索到这部电影，更方便，更快捷。所以，新技术大规模的推广使用的背后，必然伴随着用户体验的极大的提升，很简单，否则人们不会买单。值得一提的是，世界上使用人数最多的搜索引擎————Google开发的PageRank算法，如今几乎所有的搜索引擎都在使用。
  可是，你会不会有像这样的时刻？打开Google Chrome，看看新闻后不知道干嘛，一个一个网页不知道看哪一个，当你不知道干嘛却想干点什么的时候，推荐系统就派上用场了。
1.2推荐系统能解决的问题
  你上手了一款新游戏，不知道买什么样的装备，这时，系统出现了推荐装备。它可以按照专家的意见去实现，也可以通过统计所有人的出装，找出最流行的出装。
  你闲来无事逛淘宝，点了一个商品后，下面出现了一行“猜你喜欢”，根据你的浏览记录推荐你可能购买的一些商品。
  你想看个电影，打开了最常用的软件后发现不知道看什么，你发现系统有“猜你喜欢”类似的一块区域，它根据你观看记录推荐一些类似的商品。
  这其实都是推荐系统。它主要解决的问题在于你想干点事情，却不知道具体干什么。系统按照一定的方式推荐给你一些可能对你有帮助的方案或商品。
2.实际应用场景
  网易云音乐大家都用过，里面的年报也是刷屏了好一阵，根据个人的记录生成的汇总让很多人感叹：网易云音乐真贴心。其实它最贴心的不是年报，是它的个性推荐。音乐是一种体量巨大，时效性强，长尾分布明显（可以理解为20%的音乐被80%的人听）的物品。所以它在为你推荐的时候，会记录最重要的“听歌记录”，哪一个用户在什么时间听的哪一首歌，至少是这些信息会记录下来。然后，系统会根据你的记录推荐给你歌单或是单首音乐，时间越近的记录会被着重对待，因为近期的记录更代表你当下的喜好。
  音乐和游戏是完全不一样的东西，很多游戏甚至没有推荐系统也做的好好的。这是物品本身的属性决定的，但最多的还是非个性化推荐的应用。
  比如金融领域，推荐给你的是购买人数最多的股票或基金，甚至你买水果的时候也会这样，这个季节啊，人们都吃这个水果。我们把这个称为most-popular，就是按照最流行的规则排序，把排名靠前的物品推荐给你。
  关于游戏我个人最常玩的是LOL和炉石传说。LOL是一款即时战略游戏，主要以5V5的形式展开，以推倒基地为目的取得胜利。我所了解的，它在游戏中的推荐系统的应用在于买装备，这就回归原点了，他想买装备却不知道买什么，我们为它推荐，它潜移默化到80%的人会直接购买推荐的装备（我不是特指青铜玩家）。所以，新玩家获得了较好的用户体验，而老玩家想玩点骚套路，自己找装备，时间也不会很久，这样保证了绝大多数人能够因此获利。因为它多半按照Most-popular的模式，就是最流行的出装，它很大程度上可以代表最好用的装备，这时我们有一个潜在的意识，叫做群众的眼睛是雪亮的。
  没有推荐一方面会增加人们的探索欲望，可同时，也会让没有耐心的玩家流失掉。
  关于炉石传说，我接触的版本里还没有个性化推荐。它本身只有几个职业的卡组，其实卡组和出装有异曲同工之妙，你的卡组和你的装备可以在很大程度上理解成类似的东西。推荐的话，也是按照most—popular的模式推荐，本身自带的推荐卡组就是推荐装备，只不过这个卡组有很多很多种组合方法，而且没有最好，只有最适合。
  卡牌类游戏与即时战略的本身玩法决定了他们推荐系统应用的点并不多，而且游戏最重要的是其本身的趣味性及后续细节的创新。
  PS:（一些对于游戏的思考（炉石传说本质其实是，通过不断地与人交手，不断地更新牌组，再去不断地重复这个过程。在过程中，炉石传说的价值观也体现出来了，它本身有一定的难度，在开始的时候他给你一些框架让你去模仿借鉴，后来你发现其中的不足，自己去建新的卡组。它其实是一个学习的过程，人们会在其中不断摸索，进步。我们如果说LOL代表着并肩战斗，那炉石传说更是一个人的成长，说几句题外话，我想起了那些《恋与制作人》、《征途》，利用人性的弱点让人疯狂氪金的游戏。为什么有的游戏经久不衰，除了它本身的趣味性之外，它内涵的价值观也会潜移默化地让你觉得舒服。或许，你一直玩的游戏，其实制作人们和你是有心与心的交流的。）
