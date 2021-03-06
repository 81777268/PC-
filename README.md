# 一款基于Vue全家桶实现的云播放网站

版权声明：本项目为本人原创，未经本人允许可以随便转载，反正我也不会介意，注明出处就行。

---

## 技术选定

- 后台依赖 node.js
- 前端框架使用了vue全家桶
- 项目主要包含：   
	- 基础库: vue.js 、 vue-router 、 vuex 、 whatwg-fetch
	- 编译/打包工具： webpack 、 babel 、 node-sass
	- 本地服务器： express
	- 增加一个 build server 来预览 build 结果页面
	
## 项目介绍

1.后台服务器搭建使用了node.js和express，数据库使用mysql，部分数据云储存在七牛云，全部在```myapp```文件夹中，包括一套后台登录页面，云音乐的上传歌曲信息的操作系统页面。   

2.前端使用了vue全家桶对云音乐进行重构，在```appbs```中，基本功能如下：

		登录   
		获取用户歌单   
		获取歌曲详情   
		获取音乐 url   
		搜索音乐   
		获取歌词   
		获取评论   
		获取歌手专辑   
		获取每日推荐歌单   
		获取每日推荐歌曲   
		喜欢歌曲   
		签到   
		各排行榜   
		歌曲详情   
		
PS:部分接口使用python爬的某度音乐😜所以部分童鞋可能请求不回来，需要写个跨域或是浏览器下个插件哦

## 4.27
附带了一个自己写的初级vuex的md

##展示图
![Aaron Swartz](https://raw.githubusercontent.com/81777268/Using-the-vue-163music/master/jp/FireShot%20Capture%202%20-%20%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%20-%20http___localhost_8080_%23_.png)   
![Aaron Swartz](https://raw.githubusercontent.com/81777268/Using-the-vue-163music/master/jp/FireShot%20Capture%203%20-%20%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%20-%20http___localhost_8080_%23_Navban.png)   
![Aaron Swartz](https://github.com/81777268/Using-the-vue-163music/blob/master/jp/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202017-04-27%20%E4%B8%8A%E5%8D%8811.02.19.png)   
![Aaron Swartz](https://raw.githubusercontent.com/81777268/Using-the-vue-163music/master/jp/FireShot%20Capture%204%20-%20%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%20-%20http___localhost_8080_%23_VipMusic.png)















