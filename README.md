## 今天学习了MarkDown

MarkDown是一种超文本语言，禁停啊我第一次学习了它。

` Hello MarkDown！ `

接下来我还会学习：

1. Git的基础命令
1. Hexo框架
1. Hexo更换主题

用命令行敲命令是一种**Geek**行为，我觉得还挺有趣的

`` Geek是指极客,通常被用于形容对计算机和网络技术有狂热兴趣并投入大量时间钻研的人。所以俗称发烧友或怪杰 ``

有点意思，下面这张gif可以形容我的心情：
![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)


2.3中的提交命令
1. git add -A
1. git commit -m "本次提交的备注"
1. git push
    第一次提交：git push origin master
    第二次及以后：git push
    提交到b分支：git push origin b
1. git pull
    比如本地的内容是[1,2]，线上的内容是[2,3]。这个时候我们就需要使用 "git pull" 命令来抓取远程仓库的内容，抓取之后，我们的本地内容会变成[1,2,3]，才能提交，当本地和远程内容完全一致，或彼此不是对方的真子集时不可提交
