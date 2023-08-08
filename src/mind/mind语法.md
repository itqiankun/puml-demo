## 举例

结果如下

![image-20230808104112757](https://itqiankun.oss-cn-beijing.aliyuncs.com/new_picture/myblog/picgo/typora/2023/08/08/2023-08-08-10-41-14-367.png)

讲解下面的语法

`+` 一个+符号表示一级等级，就是中间的那个
`[#17ADF1]` 表示颜色
`++` 表示二级等级，并且在右边显示
`--` 表示二级等级，并且在左边显示
`_` 表示最后一个等级，比如`+++_`就是在三级等级，然后没有圆圈

```java
@startmindmap
+[#17ADF1] itqiankun.com
		++[#lightgreen] 个人介绍
		+++_ mqk
		+++_ 从事it行业
		++[#1DBAAF] 网址主要内容
		+++_ java技术
		+++_ it趣事
		+++_ 开发工具
		++[#1DBAAF] java技术
		+++_ java基础
		+++_ 框架源码
		--[#lightgreen] 框架源码
		---_ rocketmq源码
		---_ fastjson源码
		---_ logback源码
		--[#yellow] 开发工具
@endmindmap
```