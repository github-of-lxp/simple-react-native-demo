# simple react native demo 
#### 模仿今日头条界面 

#### 技术栈 
React和Redux

#### 数据 
[今日头条推荐页面实时API](http://ic.snssdk.com/2/article/v25/stream/?count=20&min_behot_time=1504621638&bd_latitude=4.9E-324&bd_longitude=4.9E-324&bd_loc_time=1504622133&loc_mode=5&loc_time=1504564532&latitude=35.00125&longitude=113.56358166666665&city=%E7%84%A6%E4%BD%9C&lac=34197&cid=23201&iid=14534335953&device_id=38818211465&ac=wifi&channel=baidu&aid=13&app_name=news_article&version_code=460&device_platform=android&device_type=SM-E7000&os_api=19&os_version=4.4.2&uuid=357698010742401&openudid=74f06d2f9d8c9664) 

#### 插件 
[React Native Navigation](https://reactnavigation.org/docs/getting-started/) 主要用作页面之间的跳转，分为stack、tab、和draw三种navigation方式  
[React Native Vector Icons](https://www.npmjs.com/package/react-native-vector-icons) 主要使用字体库中的各种icon  
[React Native Swiper](https://www.npmjs.com/package/react-native-swiper) 页面之间的滑动插件  

####  代码就不上了，最基本的React和View、StyleSheet布局，说一下遇到的几个小问题  
- 使用React Native Navigation的时候，一定要记得把import 'react-native-gesture-handler';这行放到index.js文件的**最上边，最上边，最上边**，重要的事说三遍
- 使用React Native Vector Icons时，因为我自己是MacBook+iOS,所以只讨论Xcode上的配置过程，下载好npm包后，用xcode打开ios文件夹,**然后一定要把Fonts文件夹拖到Xcode项目下边，必须拖进去，然后一定要选择add target**，然后在info.list里边添加字体，最后在终端中yarn ios重启项目  

#### 功能方面只写了一个暗黑模式的实现，下面上图   
![](https://github.com/github-of-lxp/-simple-react-native-demo/blob/main/toutiao.gif)







