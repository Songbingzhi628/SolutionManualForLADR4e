- Switch to [English](#english-version)

<p lang="zh">

# 关于该仓库的声明：

我上传这些资料，旨在和广大学习者自由交流讨论。该库文件中：至少包括**SolusMan-LADR4e.pdf**和**SourceCode**目录下的**png, jpg, ggb**文件，除去‘by-nc-sa.png’，都是在**CC0**协议下的。至少包括**SourceCode**目录下的**SolusMan-LADR4e.tex**、**Ch123.tex**、**Ch45.tex**、**Settings.tex**，是在**CC BY NC SA**条款约束下的，仅允许非商业用途的修改、复制、转发、衍生等，并且需要为副本/衍生作品使用与原作相同的协议（传染性）。这是因为原作LADR4e是在**CC BY NC**下发布的。所以其衍生作品允许（哪怕是一点点）商用是非法的，其许可证也是无效的。

> 该仓库的许可证曾在24年12月30日有过一次大变更。此次变更之前的版本对用户的(A)GPLv3/GFDL的授权，因为违背了被衍生作品即原作LADR4e的NonCommerical条款，所以在可商用性方面是无效的。
> 
> 该仓库是GitHub与Gitee双向同步的；这是因为对国人来说，访问Gitee比访问GitHub容易。


---

# 关于库中文件的说明：

### **SourceCode**文件夹

这个文件夹包含ttf和otf字体文件、tex源代码、调用的sty头文件、引用的png、jpg图片、.ggb文件。这些文件用于生成**SolusMan-LADR4e.pdf**。主要就是，用**TeXstudio**, **Texmaker**或者其他IDE，亦或者编译器，编译**SolusMan-LADR4e.tex**，输出PDF二进制版本。

> 该目录下的.ttf和.otf字体文件在(L)GPL条款下。该目录下**Headers**文件夹中**extrarrows.sty**在LGPL条款下。

为了更高的实时编译效率，我将代码架构为 **Settings**（Settings.tex）、**Chxxx**（Ch123.tex、Ch45.tex）、**Main**（SolusMan-LADR4e.tex）。

### **SolusMan-LADR4e.pdf**

##### Licensed under CC BY NC SA 4.0

这是我整理的*Linear Algebra Done Right, 4th/3rd E* 的习题答案和课文补注。范围覆盖所有第三版和第四版的课文和习题（除了第一章A节、极少数结合上下文太过显而易见的习题、没有任何日后反复推敲价值的“当堂习题”和方法套路过于雷同的习题）。
- 习题答案中，有我完全独立思考得出的，有抄 <https://linearalgebras.com/> 的, 有抄 <https://math.stackexchange.com/> 的, 有抄*LADR2eSolutions（By Axler）.pdf*，有抄最新的*LADR4eSolutions经典最全（By Axler？）.pdf*，还有请教别人，乃至请教AI得出来的。
> 上面这些文档的许可证件，除 *LADR4eSolutions经典最全（By Axler？）.pdf* 找不到/没有指明外，都允许分发/复制/引用。
- 课文补注中，除了我独立思考总结出的易错误区和技巧、难点之外，还（因为我想要兼容那些使用LADR第三版纸质书的读者，包括我在内）把LADR4e中对课文定理等等的修改也（作了简化和提炼）摘录上去。
- 题目标号为正常数字**N**的，为第三版某章某节第**N**题（有个别题是第四版又删去的，这里，或直接摘录，或合并简化，仍然作保留；还有个别题是第四版增添条件、设问的，也一并写在第**N**题下）。
- 题目标号为实心黑点的，为第四版。因为要面向以第三版为主要教材的学习者，所以为了避免混淆，故而将题号（部分题目的实心黑点后有标注具体第四版的数字标号）、甚至章节略去（一些变动过大的章节除外）。
- 题目顺序会有调换，在每章大标题处会交代清楚。
- **除了原书第四版新加入的章节外，均使用原书第三版的索引。这也许对第四版的使用者很不友好，我在此欢迎有心人士将我的作品修改后在同样的CC BY NC SA条款下发布。**

欢迎邮件<13012057210@163.com>和我交流；或者在这里提出一份Issue，再或者去 *bilibili* 找一位叫 **H-U_O** 的用户，私信或者在相关动态中评论。

### **LADR2eSolutions（By Axler）.pdf**

这个文件与我无关，也不受这里**LICENSE**的限制，我仅仅是从<https://epdf.tips/queue/linear-algebra-done-right-solutions-manual.html>（还有很多网站可以下载，搜索关键词'*linear algebra done right solutions manual*'就行）上下载过来改了文件名又传到这里。内有指明版权，允许修改、概述和分发。

### **LADR4eSolutions经典最全（By Axler？）.pdf**

所见即所得，我认为这本答案中的思路和方法非常经典、非常贴合原书，与 *LADR2eSolutions（By Axler）.pdf* 的答案风格非常相近，这两本答案都比<https://linearalgebras.com/>上的答案更胜一筹。
这个文件与我无关，也不受这里**LICENSE**的限制，我仅仅是从<https://lew98.github.io>那里下载过来改了下文件名又传到这里；疑似是 Sheldon Axler 教授所作，或者是他的学生所作，亦或者是共同完成，尽管这份文件没有在<https://linear.axler.net>上。
然而里面没有明确版权，默认为**Public Domain**。

> 这份习题答案中，截止目前，我发现的错误有：
> - 第3章F节22题(b)问，
> - 第4章14题(a)问，
> 
> - ······

---

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

---

###### 我为什么要设一个LICENSE？这只是一个“防御性条款”。毕竟，我可不想在我拿着我亲手写出来的东西「尽管题解中大部分不是我原创，但我摘录的内容本身就是可随意摘录的；这里“亲手写”意思是我亲手排版、编撰、修正」分享到网上并和别人自由讨论时，被一个不知道哪里冒出来的人指控我盗取了他的东西，并设法让我摊上麻烦。

##### 额外地，我希望每个有能力修改再分发我编撰的资料的人都能遵守/延续这里的条款。我在此不鼓励任何人在修改/重排这些资料后将修改/重排的版本闭源或专用性商用（尽管我不会追究；但相关的潜在法律风险也和我无关），从而阻碍别人自由使用/分享/再修改。
> 
---

</p>

# English Version

<p lang="en">

> I am a Chinese, and I am not good at English. Thus I must first apologize, for words below may be awkward. You can contact me via Email to let me know where I made mistakes, or even, if you wish, to suggest me a better example.

# About this repo:

The purpose of me uploading these materials, is to communicate with as many learners, teachers, scholars, etc. as possible. The files in this repo, at least containing **SolusMan-LADR4e.pdf** and **.png, .jpg, .gbb** files under the **SourceCode** directory, except for `by-nc-sa.png', are all licensed under **CC0**; files at least containing **SolusMan-LADR4e.tex**, **Ch123.tex**, **Ch45.tex**, **Settings.tex** in the **SourceCode** directory, are licensed under **CC BY NC SA**.

You are free to (re)distribute, modify, or copy any part or whole of those files, as long as in non-commerical use, and as long as you release your Derivative Work under the same License. See **LICENSE** for more details.

> The license of this repo had a major change on December 30, 2024. The version prior to this change, in terms of the (A)GPLv3/GFDL authorization for users, was invalid in terms of commercial usability because it violated the NonCommerical clause of the original work LADR4e from which it was derived.

---

# About the files:

### The **SourceCode** directory

Including font files in .ttf, .otf, source files in .tex, header files in .sty, pictures in .png, .jpg, .ggb files. These files are used in generating **SolusMan-LADR4e.pdf**, by **TeXstudio**, or **Texmaker** or other IDE, or simply a compiler.

> The .ttf, .otf font files are licensed under (L)GPL. **extrarrows.sty** in the **Headers** directory is licensed under LGPL.

In order to reduce compile time during coding and testing, I seperate my source code into parts including **Settings**(Settings.tex), **Chxxx**(Ch123.tex, Ch45.tex), **Main**(SolusMan-LADR4e.tex).

### **SolusMan-LADR4e.pdf**

##### Licensed under CC BY NC SA 4.0

This is my notes and solutions for *Linear Algebra Done Right, 4th/3rd E*. All exercises in two versions of the textbook, are in my range, except for Section A in Chapter 1 and all other exercises that are too easy to solve.

- The solutions are not all originally written by me. Many of those are copied or abridged from <https://linearalgebras.com/>, <https://math.stackexchange.com/>, *LADR2eSolutions（By Axler）.pdf* , *LADR4eSolutions经典最全（By Axler？）.pdf*. And some of those solutions, are adaptions/implementations of the results of chatting with other people informally, or even with AI.
> The copyright notices of the documents mentioned above, except for that of *LADR4eSolutions经典最全（By Axler？）.pdf* ( not specified/found ), permit distributing and copying.

- The notes for the textbook include efficient tools, misconceptions, and error-prone points. For the sake of compatibility with the 3rd Edition, I copied/abridged/adapted the new results appeared in the 4th Edition in my notes.
- The plain number tags for Exercises are the same in the 3rd Edition. Some Exercises in 3rd Edition are disappeared/modified ( with some conditions or questions added or removed ) in the 4th Edition. I saved them in my manual by copying directly, or merging ( all remain in the original number tags, but may not remain in the original position ).
- Because **I use indices of the 3rd Edition**, so in order to avoid confusion, the Exercises in bullet point tags are for 4th Edition, ( some of them are modified by me, )  and some of them are followed by number tags in 4th Edition. Except for great changes in whole chapter in 4th Edition.
- The order of Exercises for each chapter may not be the same with the textbook. I note that clearly after the big chapter title.
- For theorems/facts/definitions/..., I use indices in 3rd Edition. Except for those in  entirely new chapter in 4th Edition.

Contact me via Email: <13012057210@163.com>. Or propose an Issue here.

### **LADR2eSolutions（By Axler）.pdf**

This file, is absolutely in no relation with me, in any ways, so it is not limitted under **LICENSE**. I just downloaded it from <https://epdf.tips/queue/linear-algebra-done-right-solutions-manual.html>, then renamed it, and then uploaded it here.

There are many other sites for downloading this file, just type '*linear algebra done right solutions manual*' in your Search Engine.

The copyright notice in this file permits modifying, abridging, distributing, and of course copying and adapting (at least a small part).

### **LADR4eSolutions经典最全（By Axler？）.pdf**

WYSIWYG. I think the methods and ideas in this manual, is specifically the same with the textbook. Maybe the author is Axler himself! Especially because of *LADR2eSolutions（By Axler）.pdf*, which is in the same style with this manual. Although both manuals are not on this page: <https://linear.axler.net>.

I think the answers given in the two manuals above are better than those of <https://linearalgebras.com/>.

What I must say, is that this file, is absolutely in no relation with me, in any ways, so it is not limitted under **LICENSE**. I just downloaded it from <https://lew98.github.io>, then renamed it, and then uploaded it here.

There is no copyright notice, so I suppose it is **Public Domain**. If it has, I assume that I have the perimission to copy, abridge any part of the document.

> Up to now, I find that there are some wrong answers in this manual:
> - Chapter 3 Section F Exercise 22 (b),
> - Chapter 4 Exercise 14 (a),
> 
> - ······

---

### **MyConfigures**

My personal configures for **TeXstudio**.

#### How to configure your LaTex by Terminal under the Trisquel/Ubuntu system ? Just type:

> sudo apt install texlive
> 
> sudo apt install texlive-xetex
> 
> (optional) sudo apt install texlive-lang-chinese
> 
> sudo apt install texstudio

---


</p>
