## ROADMAP TO A GOOD CPP USER
原本想写的题目是 *roadmap to cpp master*
> cpp的学习, 不仅仅是语言的学习, 更重要的是培养用编程语言描述问题，解决问题的思维

# 0. Tools
一定要装一个Linux操作系统, 大家都在Linux上coding的
一个虚拟化软件: [VirtualBox](https://www.virtualbox.org/), 国外的站点, 访问可能有点慢  
不过可以在清华的开源镜像站上下载: [VirtualBox](https://mirrors.tuna.tsinghua.edu.cn/virtualbox/)  
直接用最新的即可[for windows](https://mirrors.tuna.tsinghua.edu.cn/virtualbox/virtualbox-Win-latest.exe)
安装啥的稍微注意下即可(注意在bios中应开启virtualization, VT类似的字眼, 一般是默认开启的)  
现在可以安装最好的Linux发行版: [Arch Linux](https://archlinux.org)了 :)  
Arch Linux: *A simple, lightweight distribution*  
官方的[wiki](https://wiki.archlinux.org/), 几乎所有的问题都能在这里找到答案  
推荐一个安装的[blog](https://www.viseator.com/2017/05/17/arch_install/), 当时我就是按照这篇博客来的  
熟悉Linux的最好办法就是先去用命令行安装它, Arch给了你尽可能多的机会去客制化自己的系统. 在Arch的社区 (Arch wiki, Arch forum, Telegram, QQ group, IRC...)
都会有非常多的热心的社区伙伴来解答新人的问题, 不要觉得自己的问题很愚蠢而不敢大声说出自己的疑惑.  
当然在提问之前, 需要自己想过, 查阅过相关资料, 推荐一本告诉读者如何正确的提问的书: [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md)

经历过一番折磨之后, 你终于安装好了Arch Linux, 美化之类的工作可以当作娱乐  
如何用好Linux?  
**鸟哥的Linux私房菜**: 非常全的一本书, 文风也非常有趣. 不过也不必抱着书从头到尾读, 太厚了. 闲暇之余当作读物来读读就非常棒了.  
这时候可以用一些最简单的程序, 比如
- ls    列出当前目录中的文件(list)
- cd    改变当前目录(change directory)
- touch 生成一个文件
- lscpu 查看cpu信息
- lspci 查看pci设备
- gcc   大名鼎鼎的编译器gcc, 输入源文件, 生成可执行文件(ELF)
- g++  其实是gcc的一部分
- make 一个脚本, 常见于Linux下的编译工作中
- ......

在c++ primer第0章中有提到如何通过g++来编译我们的源文件, 可以参考一下
______________________
# 1. Language
当然首先，工具咱得把它用熟, 用好.  
入门的书比较推荐**Cpp Primer the fifth edition**,  第5版的中文版就好了, 我也是看的中文版。  
共有4个部分:
1. *C++基础* 主要介绍了cpp中的变量类型，表达式，语句，函数和类，这一部分应该是比较熟悉，我们在学校里学的基础肯定有, 所以这一部分刚开始可能有点小小的困难，但是两天之后就很轻松了。
2. *C++标准库* 主要介绍了cpp的一些非常常用的标准模板库(Standard Template Library, STL), 比如IO库，容器，算法, 智能指针. 用cpp去解决问题的时候，你就会发现，wow标准库太好用了，不用自己去从底层写起. 标准库我们可以自己去实现，但是标准库里的code经过千锤百炼，经过业界的严苛检验, 质量肯定比我们手搓的好。所以非常有必要熟练用好标准库，甚至是背下来(其实用多了也就记住了). 这一部分的重点：容器 > IO > 智能指针 > 算法.
3. *类设计者的工具* 主要介绍了类的构造，重载，模板等cpp与c最大的不同，这也是cpp较c更现代的部分, 体现了cpp封装，继承，多态的特性, 这非常重要，在工程中会发现类无处不在，类与类之间的关系错综复杂.
4. *高级主题* 要是看到这一部分, 那就不用我介绍了, 因为我也没看到这里 :) 不过你已经学了80%的内容了, 这边你肯定知道怎么去学习了.

最后再关注一下cpp的新特性, 平时要经常去用, 也是面试常考题.  
大家都说好的cpp相关网站:
- [cppreference](https://en.cppreference.com/w/)  
  标准库的定义, 用法, 样例代码都有, 简直太棒了, 工作中也会经常查阅
- ......

我们可以写一个HTTP服务器了!  
[A C++ High Performance Web Server](https://github.com/linyacool/WebServer)  
现在你已经很厉害了, 不过在学习cpp的过程中，肯定会遇到计算机其它领域的问题，这时候就可以开始新领域了
____________________________________________________
# 2. Network
语言学得太枯燥了, 还是计算机网络好玩, 在写HTTP服务器时, 肯定会对网络相关的知识感兴趣  
_______________________________________________

# 3. Data Struct & Algorithm
可以说是最重要的一门课了  
_______________________________________________

# 4. Operating System
一个CS工程师必须要熟悉的领域  
_______________________________________________
