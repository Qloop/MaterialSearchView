# MaterialSearchView
Adnroid MaterialDesign规范的SearchView

好吧，其实我不是很理解MD规范到底有什么标准，我写的这个可能不是你理解的MD规范，不要喷……

###说明:
这只是一个小demo,包括UI和逻辑框架。注意：网络请求和数据解析部分被我注释掉了，注释部分用的xutils和gson，你可以根据自己的情况来写。
整体逻辑就是 输入搜索内容，在用户输入的同时进行搜索操作（也就是网络请求或者是本地搜索），但是考虑到用户流量问题，所以我延时了1s 大家
根据自己的需求调整。  搜索结果由listview负责展示，缓存搜索历史 使用的是SharePreference  我提供了一个缓存工具类。又本地缓存读取搜索历史来展示。  当然，当网络异常和搜索没有结果时  都有对应的提示页面(被我注释了……)

类似效果看这里: http://blog.csdn.net/CodeNoodles/article/details/51418773
