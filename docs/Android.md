


# Android
Android Tools


## Android Studio

[下载](https://developer.android.com/studio/index.html), [国内下载](http://www.androiddevtools.cn/index.html) 

[Android Studio NDK使用(CMake方式)](https://developer.android.com/studio/projects/add-native-code.html)

### 快捷键/Keymap 


|	Win.Keymap						|	Mac.Keymap						|	Des.						|
|----------------------				|----------------------				|--------------------------		|
|	<kbd>Ctrl+/</kbd>              	|	<kbd>Cmd+/</kbd>              	|   快速添加注释					|
|	<kbd>Ctrl+Shift+/</kbd>         |	<kbd>Cmd+Option+/</kbd>         |   快速添加注释    			|
|	<kbd>Ctrl+Y</kbd>              	|	<kbd>Cmd+Backspace</kbd>       	|   删除当前行					|
|	<kbd>Ctrl+D</kbd>              	|	<kbd>Cmd+D</kbd>       			|   复制当前行					|
|	<kbd>Ctrl+E</kbd>              	|	<kbd>Cmd+E</kbd>       			|   显示最近打开文件窗口			|
|	<kbd>Ctrl+Shift+E</kbd>        	|	<kbd>Cmd+Shift+E</kbd>  		|   显示最近编辑文件窗口			|
|	<kbd>Ctrl+G</kbd>              	|	<kbd>Cmd+G</kbd>              	|   定位到当前编辑器的某一行		|
|	<kbd>Ctrl+B</kbd>              	|	<kbd>Cmd+B</kbd>              	|   定位到Definition 			|
|	<kbd>Ctrl+Shift+A</kbd>        	|	<kbd>Cmd+Shift+A</kbd>        	|   快速查找Actions				|
|	<kbd>Ctrl+Shift+N</kbd>        	|	<kbd>Cmd+Shift+N</kbd>        	|   快速查找文件					|
|	<kbd>Ctrl+Shift+F</kbd>        	|	<kbd>Cmd+Shift+F</kbd>  		    |   Find In Path			|
|	<kbd>Ctrl+N</kbd>        		|	<kbd>Cmd+N</kbd>        		        |   快速查找类					|
|	<kbd>Shift+Shift</kbd>        	|	<kbd>Shift+Shift</kbd>        	|   Search Everywhere			|
|	<kbd>Alt+Enter</kbd>        	|	<kbd>Opt+Enter</kbd>        	          |   Quick Fix 					   |
|	<kbd>Ctrl+O</kbd>              	    |	<kbd>Cmd+O</kbd>              	  |   显示类中方法和属性的大纲	|
|	<kbd>Ctrl+F12</kbd>              	  |	<kbd>Cmd+F12</kbd>              	  |   显示Members	|
|	<kbd>Alt+7</kbd>              	    |	<kbd>Cmd+7</kbd>              	  |   显示Structure	|
|	<kbd>Alt+Ctrl+L</kbd>        	      |	<kbd>Cmd+Opt+L</kbd>        	    |   格式化代码Format				  |
|	<kbd>Ctrl+Plus/Minus</kbd>        	|	<kbd>Cmd+Plus/Minus</kbd>        	|   展开/折叠代码块				  |
|	<kbd>Ctrl+Shift+Plus/Minus</kbd>    |	<kbd>Cmd+Shift+Plus/Minus</kbd>   |   展开/折叠全部代码块		  |
|	<kbd>Ctrl+Tab</kbd>    |	<kbd>Cmd + Tab</kbd>   |   窗口切换（关闭某个窗口，在上面按BackSpace即可）		  |

exp：    
- 快捷键不起作用，可能是与搜狗输入法冲突，关闭搜狗所有快捷键

### 实用设置

- 黑色主题：  Settings –> Appearance –> Theme -> Darcula 
- 护眼设置：  Settings –> Editor –> General -> Text -> Defaul Text -> RGB值分别为199 237 204
- 快速Import： Setting -> Editor -> General -> Auto Import
- 显示行号： Settings –> Editor –> Appearance -> 勾选 Show line numbers
- Ctrl+Mouse 字体缩放： Settings –> Editor –> General -> 勾选 Change font size with ** 
- Properties unicode转码: Setting > File Encoding > 勾选 Transparent native-to-ascii convesion   

> 实用技巧 

- for循环代码快速生成技巧

| 使用           		   | 说明     							|
| -----------------------  | ------------	  					|
| 对象.for		     	   | 迭代循环遍历 						|
| 对象.fori		     	   | 正向for循环(int) 					|
| 对象.forr		     	   | 反向for循环						|
| 数字.for		     	   | 生成int型size为"数字值"的for循环 	|

- 判空代码快速生成技巧  

| 使用           		   | 说明     							|
| -----------------------  | ------------	  					|
| 对象.null		     	   | 判空代码快速生成 					|
| 对象.notnull			   | 判非空代码快速生成 				|
| 对象.nn		     	   | 判非空代码快速生成					|

- if代码快速生成技巧  

| 使用           		   | 说明     							|
| -----------------------  | ------------	  					|
| 语句.if		     	   | if代码快速生成 					|
| 对象.instance			   | instance代码快速生成 				|


### 实用工具

- [Genymotion](https://plugins.jetbrains.com/plugin/7269-genymotion) 老牌模拟器，快！

- [NimbleDroid](https://nimbledroid.com/) 测试App内存泄漏和严重问题工具

- [LeakCanary](https://github.com/square/leakcanary) 内存泄漏检测

- [BlockCanary](https://github.com/markzhai/AndroidPerformanceMonitor) 性能监测库

- [Takt](https://github.com/wasabeef/Takt) 检查App FPS的小巧工具


### 实用插件

- [GsonFormat](https://plugins.jetbrains.com/plugin/7654-gsonformat) 快速生成Gson

- [Android Code Generator](https://plugins.jetbrains.com/plugin/7595-android-code-generator)  快速生成Activity，Fragment，Adapter，Menu

- [Android Parcelable code generator](https://plugins.jetbrains.com/plugin/7332-android-parcelable-code-generator) 快速生成Parcelable

- [Android Styler](https://plugins.jetbrains.com/plugin/7972-android-styler) 根据xml快速生成style代码

- [AndroidProguardPlugin](https://github.com/zhonghanwen/AndroidProguardPlugin) 一键生成项目混淆代码插件

- [FindViewByMe](https://github.com/laobie/FindViewByMe) 一键生成findViewById

- [Material Design Icon Generator](https://github.com/konifar/android-material-design-icon-generator-plugin) 自动生成 Material Design图标的Android Studio插件

- [GradleDependenciesHelperPlugin](https://github.com/siosio/GradleDependenciesHelperPlugin) maven gradle 依赖支持自动补全

- [Android Methods Count](https://plugins.jetbrains.com/plugin/8076-android-methods-count) 显示依赖库中得方法数

- [findBugs-IDEA](https://plugins.jetbrains.com/plugin/3847-findbugs-idea) 老牌查找bug的插件

- [ADB WIFI](https://plugins.jetbrains.com/plugin/7856-adb-wifi) wifi无线调试App，无需root权限

- [ADB IDEA](https://github.com/pbreault/adb-idea) IDE中实现app重启，杀死，清理数据，卸载插件

- [Key Promoter](https://plugins.jetbrains.com/plugin/4455-key-promoter) 高效快捷键插件

- [Codota](https://www.codota.com/ide-plugin) IDE中寻找代码示例插件

- [JsonOnlineViewer](https://plugins.jetbrains.com/plugin/7838-jsononlineviewer) 请求、调试接口

- [Sexy Editor](https://plugins.jetbrains.com/plugin/1833-sexy-editor) 让你的Android Studio性感起来(编辑区的背景图片)

- [Android Methods Count](http://www.methodscount.com/plugins)  三方库方法统计 [methodscount](http://www.methodscount.com)

- [svgtoandroid](https://github.com/misakuo/svgtoandroid) 矢量化图片转换插件

- [SQLScout (SQLite Support)](https://plugins.jetbrains.com/plugin/8322-sqlscout-sqlite-support-) SQLite 辅助工具(收费)

- [Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) 开源SQLite 辅助工具

> Refs  

- [awesome-androidstudio-plugins](https://github.com/jiang111/awesome-androidstudio-plugins)

- [Android-Studio插件整理](https://ydmmocoo.github.io/2016/06/28/Android-Studio插件整理/)

- [Android-Studio-Plugins](https://github.com/balsikandar/Android-Studio-Plugins)

## IntelliJ

- [Alibaba Java Coding Guidelines pmd implements and IDE plugin ](https://github.com/alibaba/p3c)    

- [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox/) 配合版本控制工具git使用    

- [GsonFormat](https://plugins.jetbrains.com/plugin/7654-gsonformat/) 一键生成对应实体对象    

- [iBATIS/MyBatis plugin](https://plugins.jetbrains.com/plugin/6725-ibatis-mybatis-mini-plugin/)mybatis插件    

## Eclipse 


### 快捷键/Keymap 

|	Win.Keymap						|	Des.						|
|----------------------				|--------------------------		|
|	<kbd>Ctrl+O</kbd>              	|   显示类中方法和属性的大纲		|
|	<kbd>Ctrl+/</kbd>              	|   快速添加注释					|
|	<kbd>Ctrl+D</kbd>              	|   删除当前行					|
|	<kbd>Ctrl+M</kbd>              	|   窗口最大化和还原				|
|	<kbd>Ctrl+L</kbd>              	|   定位到当前编辑器的某一行		|
|	<kbd>Ctrl+H</kbd>              	|   Find In Path		|
|	<kbd>Ctrl+Shift+T</kbd>        	|   快速查找类					|
|	<kbd>Ctrl+Shift+R</kbd>        	|   快速查找文件					|
|	<kbd>Ctrl+Shift+G</kbd>        	|   查找类、方法和属性的引用		|
|	<kbd>Ctrl+Shift+F</kbd>        	|   格式化代码					|
|	<kbd>Ctrl+K/Ctrl++Shift+K</kbd>	|   快速向下和向上查找选定的内容	|
|	<kbd>Ctrl+Shift+O</kbd>        	|   快速生成import				|
|	<kbd>Alt+Shift+J</kbd>        	|   快速生成JavaDoc注释			|
  


## Gradle

- [Android Gradle Plugin DSL 在线文档](http://google.github.io/android-gradle-dsl/)  

- [Gradle Dependencies Configuration Generator](http://gradleplease.appspot.com/)


## 实用参考  

- [Code like a pro: 31 tools for Android app developers](https://techbeacon.com/code-pro-31-tools-android-app-developers)
