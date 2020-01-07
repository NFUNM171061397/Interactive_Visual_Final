## 一、url链接
* [Pythonanywhere URL1](http://liwenkross.pythonanywhere.com/)

* [Pythonanywhere URL2](http://xiaohewenya.pythonanywhere.com/)

* [Github代码URL ](https://github.com/NFUNM171061397/Interactive_Visual_Final)

* 备注（上传文件-全由个人完成）：
1. 数据查找，收集，清洗
2. FLASK框架（app.py,templates,static...所有文件已上传）
3. 四份交互产品完成并嵌套
4. 交互控件（交互界面样式）
5. html表单（数据筛选）

* pythonanywhere所有页面可正常跳转，数据大可能加载较为缓慢，若跳转失败请多次尝试、刷新。

## 二、项目说明
* 数据来源：kaggle
* 数据处理：通过python将多个现有的数据库数据进行清洗，并进行整合。
* 选题说明：通过星巴克的数据，来发现其背后有趣的故事
* 交互实现：
1. 城市星巴克门店数：信息表单筛选出国家，将该国家的城市所含星巴克数量由条形图呈现出来。（plotly）
2. TOP50国家排名（门店数）：通过条形图，直观的呈现出国家含星巴克的门店数量，便于对比。（pyecharts）
3. 星巴克全球分布地图：通过地图的形式，呈现星巴克在全球的分布情况。（pyecharts）
4. 星巴克中国分布地图：内含三种地图，可进行交互。（folium）
* 交互界面：通过plotly、pyecharts、网页css样式等，对配色、字体、信息进行界面美观与得体的实现。


## 三、选题说明
### 背景
星巴克最初是一家全豆和咖啡粉，茶和香料的烘焙商和零售商，1971年在西雅图的派克市场上开设了一家商店。该公司现在在70个国家/地区拥有24,000多家零售店。

### TOP50国家排名（星巴克门店数）
毕竟是美国的品牌，美国星巴克门店数量还是远多于其他国家，其次是我们国家，总计2734家，目前应该更多了。

### 城市星巴克门店数
* 上海，拥有542家星巴克门店远远领先其他城市。
* 首尔，韩国5000W人口拥有近1000家星巴克门店。
* 西雅图，拥有较多的门店，是星巴克总部所在地，除了这个原因，也许西雅图程序员也贡献了不少营业额。

### 星巴克全球分布地图
* 故事一：门店主要还是集中在美洲，亚洲，欧洲，非洲目前只有摩洛哥，埃及和南非设有门店。
* 故事二：整个澳大利亚只有22家星巴克门店。难道是澳大利亚人不爱喝咖啡吗？其实正好相反，因为澳大利亚人太钟爱咖啡了，澳大利亚人对咖啡的讲究，就像中国人对茶的挑剔一样，对于星巴克这种过于商业化的连锁品牌有些难以生存。
* 故事三：其实除了澳大利亚其实还有一个国家更过分，只是由于面积小不容易被注意到，那就是意大利，一家星巴克也没有（查了一下新闻，星巴克似乎17年3月在意大利开设了一家）。

### 星巴克中国分布地图
* 热力图：毫无意外的最红的三个区域——长三角，珠三角和北京；中部城市以成都/武汉为首。
* 上海已经是一座被星巴克包围的城市，近700家门店，全国第一，全球第一。上海的肯德基麦当劳加在一起也只有7百多家店，星巴克1家就已经接近肯德基麦当劳门店之和。上海的消费力始终是全国最强。几十块钱一杯的咖啡肯定不算便宜，全中国也只有上海有这么巨大的消费力可以支撑起这么多的门店。任何消费品，得上海者得中国，这或许是一句真理。
