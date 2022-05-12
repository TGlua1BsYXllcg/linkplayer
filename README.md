# LinkPlayer
这是一个基于Link底层分布式服务的播放器, 纯粹基于个人爱好, 本意就是我希望有一个可以能让我愉快看片子的播放器.  
我们都怀念互联网开源分享的时代,我们无私分享着各种资源, 我们分享美剧学英文, 分享着各种优秀的海外电影, 同时当然也分享着各种老师的神秘号码,这是BT时代最后的余晖.  
直到资本的出现, 把地圈起来告诉大家, 我们应当为版权付费, 一开始我很认同, 每个月几十块的订阅费我也付了, 结果得到的是各种粗制滥造, 优秀的内容也没有得到引进.  
我们看到BT被各种封禁, 快播倒了, 各种资源分享也式微了, 互联网的共享精神终归成了资本圈地的绊脚石.  
我以个人微薄之力, 弄了一个为少数人服务的项目, 希望有这么个播放器可以像原来一样, 给大家分享各种资源.

## Link底层分布式服务
Link是一个基于分布式的底层分发存储服务, 采用类似BT的数据分发形式, LinkPlayer的底层数据都来自于Link服务, 就是说每个播放器同时也会作为一个Link的节点为其他播放器提供数据分发服务.  

## LinkPlayer链接格式
LinkPlayer有自己的链接格式, 类似于磁力链接的magnet:?xt=urn:btih:  
LinkPlayer链接格式:  
最近比较火的电视剧《开端》第一集的link链接:linknodes://m/bafybeiaymusprc6o5f7qu5vfkflmsu3tunulaqyvwbis3winx2nvdtkleu  
bafybeiaymusprc6o5f7qu5vfkflmsu3tunulaqyvwbis3winx2nvdtkleu为该资源在Link服务中的hash地址

## Android版本
Android版本是我主要维护的版本, 缺乏UI支持, 还比较简陋.  
点More resource可以看到当前网络上大家分享出来的资源.  

0.2.16版去除了敏感内容, 同时优化了节点速度:
https://github.com/TGlua1BsYXllcg/linkplayer/releases/tag/v0.2.16



## Windows版本
Windows版本还处于比较初期, 但至少是一个可用的状态, 后面会继续改进增加例如上传资源、分享资源等功能.  
https://github.com/TGlua1BsYXllcg/linkplayer/releases/tag/v0.2.15


如果有小伙伴觉得还不错, 愿意支持这个项目, 可以捐赠到以下地址。 

Donate:
ETH:0x7487E3fF5787d30D35Eac71A1eb087f1494643EA
