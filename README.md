# 关于该仓库的声明：

我上传这些资料，旨在和广大学习者自由交流讨论。
该库文件中，至少包括**SolusMan-LADR4e.pdf**文件和**SourceCode**目录下的所有文件，是在**GNU AGPLv3**条款约束下的：严禁任何人，以任何名义，妨碍任何人，自由 使用、修改、复制、上传、发布这些内容。具体见**LICENSE**。

##### 该仓库是GitHub与Gitee双向同步的；这是因为对国人来说，访问Gitee比访问GitHub容易。
##### 关于LICENSE选用：之前用过GPL，所以不能转成GFDL。又考虑到一些人仍然可以通过云端网络内嵌的方式让我提供的东西变得不自由，我使用AGPL；但我必须试图说服我自己，该仓库的（除**LADR2eSolutions（By Axler）.pdf**和**LADR4eSolutions经典最全（By Axler？）.pdf**，这些只能是文档，不受这里LICENSE的约束）文件，要么是源码，要么是二进制程序。例如.ggb文件可视作一个在Geogebra系统中运行并开发的小程序，根据.ggb开发出的.png也算是一个衍生程序，而不是文档；SolusMan-LADR4e.pdf可视作在一个二进制发布，而不是文档。

---

# 关于库中文件的说明：

### **SourceCode**文件夹

这个文件夹包含ttf和otf字体文件、tex源代码、引用的png、jpg图片、.ggb文件。这些文件用于生成**SolusMan-LADR4e.pdf**。主要就是，用**TeXstudio**, **Texmaker**或者其他IDE，亦或者编译器，编译**SolusMan-LADR4e.tex**，输出PDF二进制版本。

为了更高的实时编译效率，我将代码架构为 **Settings**（Settings.tex）、**Chxxx**（Ch123.tex、Ch45.tex）、**Main**（SolusMan-LADR4e.tex）。

### **SolusMan-LADR4e.pdf**

这是我整理的*Linear Algebra Done Right, 4th/3rd E* 的习题答案和课文补注。范围覆盖所有第三版和第四版的课文和习题（除了第一章A节、极少数结合上下文太过显而易见的习题、没有任何日后反复推敲价值的“当堂习题”和方法套路过于雷同的习题）。
- 习题答案中，有我完全独立思考得出的，有抄 <https://linearalgebras.com/> 的, 有抄 <https://math.stackexchange.com/> 的, 有抄*LADR2eSolutions（By Axler）.pdf*，有抄最新的*LADR4eSolutions经典最全（By Axler？）.pdf*，还有请教别人，乃至请教AI得出来的。
> 上面这些文档的许可证件，除*LADR4eSolutions经典最全（By Axler？）.pdf*找不到/没有指明外，都是允许分发和复制。
- 课文补注中，除了我独立思考总结出的易错误区和技巧、难点之外，还（因为我想要兼容那些用LADR第三版的读者，包括我在内）把LADR4e中对课文定理等等的修改也（作了简化和提炼）摘录上去。
- 题目标号为正常数字**N**的，为第三版某章某节第**N**题（有个别题是第四版又删去的，这里，或直接摘录，或合并简化，仍然作保留；还有个别题是第四版增添条件、设问的，也一并写在第**N**题下）。
- 题目标号为实心黑圈的，为第四版。因为要面向以第三版为主要教材的学习者，所以为了避免混淆，故而将题号、甚至章节略去（一些变动过大的章节除外）。
- 题目顺序会有调换，在每章大标题处会交代清楚。

欢迎邮件<13012057210@163.com>和我交流，或者在这里提出一份Issue，又或者去 *bilibili* 找一位叫 **H-U_O** 的用户，私信或者在相关动态中评论。

### **LADR2eSolutions（By Axler）.pdf**

这个文件与我无关，也不受这里**LICENSE**的限制，我仅仅是从<https://epdf.tips/queue/linear-algebra-done-right-solutions-manual.html>（还有很多网站可以下载，搜索关键词'*linear algebra done right solutions manual*'就行）上下载过来改了文件名又传到这里。内有指明版权，允许修改、概述和分发。

### **LADR4eSolutions经典最全（By Axler？）.pdf**

所见即所得，我认为这本答案中的思路和方法非常经典、非常贴合原书，与*LADR2eSolutions（By Axler）.pdf*的答案风格非常相近，这两本答案都比<https://linearalgebras.com/>上的答案更胜一筹。
这个文件与我无关，也不受这里**LICENSE**的限制，我仅仅是从<https://lew98.github.io>那里下载过来改了下文件名又传到这里；疑似是 Sheldon Axler 教授所作，或者是他的学生所作，亦或者是共同完成，尽管这份文件没有在<https://linear.axler.net>上。
然而里面没有明确版权，默认为**Public Domain**。

> 这份习题答案中，截止目前，我发现的错误有：
> - 第4章14题第(a)问，
> 
> - ······

### **MyConfigures**

这是我个人编写LaTeX代码时使用的**TeXstudio**配置。

### 「附：如何配置LaTex」 Trisquel/Ubuntu系统Terminal下

> sudo apt install texlive
> 
> sudo apt install texlive-xetex
> 
> sudo apt install texlive-lang-chinese
> 
> sudo apt install texstudio

即可。其他系统下，差不多也就 texlive、xetex、中文语言包、texstudio 这些。
