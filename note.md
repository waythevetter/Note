

```c
in:language java

in:description 断点续传 language:java

in:readme grpc server language:java
in:readme kubernetes进阶实战

in:name spring boot
in:name spring-boot stars:>10000
in:name spring-boot forks:>10000
in:name spring-boot pushed:>2021-03-12
in:name spring-boot size:>100
```

```c
awesome xxx //令人惊叹的xxx项目
stars:>xxx // stars数大于xxx
stars:xxx..yyy // stars数在xxx和yyy之间的
forks:>xxx // forks数大于xxx
language:xxx // 编程语言是xxx
in:name xxx 或xxx in:name // 按照项目名搜索
in:readme xxx 或xxx  in:readme  // 按照README搜索
in:description xxx 或xxx  in:description // 按照description搜索
pushed:>YYYY-MM-DD // 最后更新时间大于YYYY-MM-DD
location:xxx //开发者位置在xxx，比如china，beijing，chengdu
user:xxx //查找某开发者下的所有仓库
followers:>=xxx //粉丝数大于xxx的开发者

```
**冒号两侧不能有空格；
不区分大小写；
不能将以下通配符用作搜索查询的一部分，搜索将忽略这些符号：. , : ; / \ ` ’ " = * ! ? # $ & + ^ | ~ < > ( ) { } [ ]；
搜索默认为master分支。**




|搜索条件  | 备注 |
|--|--|
|Awesome + keyword|关键字 Awesome,帮忙找到优秀的工具列表| 
in:name example	in:name springboot,|匹配项目名中包含 springboot关键词的项目
in:readme example	|in:readme springboot,匹配readme中包含 springboot关键词的项目
in:description example	|in:description springboot,匹配描述中包含 springboot关键词的项目
stars:|	stars:>=1000,匹配收藏数量超过 1000 的项目
forks:	|forks:>=1000,匹配分支数量超过 1000 的项目
pushed:	|pushed:>2019-05-06,匹配在2019年5月6号后有更新的项目
language:	|language:java,匹配以 java 作为开发语言的项目



![在这里插入图片描述](https://img-blog.csdnimg.cn/e73b9053ac6344519bb9a08949e5ff7c.png)


[参考文章](https://blog.csdn.net/m0_61392261/article/details/120236937)
