### - 关于该仓储库的声明：

我上传这些资料，旨在和广大学习者自由交流讨论。
严禁任何人，以任何名义，妨碍任何人，自由复制、下载、转发、修改，我在此上传的所有资料，至少包括我编撰的“SolusMan-LADR4e.tex/pdf”。

===

### - 关于库中文件的说明：

##### **SourceCode**文件夹

这个文件夹包含'.ttf'和'.oft'字体文件、'.tex'源代码、引用的'.png'图片。这些文件用于生成**SolusMan-LADR4e.pdf**。主要就是，用TeXstudio或者其他IDE，亦或者编译器，编译**SolusMan-LADR4e.tex**，输出PDF。

##### **SolusMan-LADR4e.pdf**

这是我整理的Linear Algebra Done Right (4e/3e) 的习题答案和课文补注。范围覆盖所有第三版和第四版的课文和习题（除了第一章A节、极少数结合上下文太过显而易见的习题、没有任何日后反复推敲价值的“当堂习题”和方法套路过于雷同的习题）。
- 习题答案中，有我完全独立思考得出的，有抄 linearalgebras.com 的, 有抄 math.stackexchange.com 的, 有抄 Axler的 linear-algebra-done-right-solutions-manual.pdf的，有抄最新Axler经典答案的，还有请教别人，乃至请教AI得出来的。
- 课文补注中，除了我独立思考总结出的易错误区和技巧、难点之外，还（因为我想要兼容那些用LADR第三版的读者，包括我在内）把LADR第四版中对课文定理等等的修改也（作了简化和提炼）摘录上去。

- 题目标号为正常数字N的，为第三版某章某节第N题（有个别题是第四版又删去的，这里，或直接摘录，或合并简化，仍然作保留；还有个别题是第四版增添条件、设问的，也一并写在第N题下）。
- 题目标号为实心黑圈的，为第四版。因为要面向以第三版为主要教材的学习者，所以为了避免混淆，故而将题号、甚至章节略去（一些变动过大的章节除外）。
- 题目顺序会有调换，在每章大标题处会交代清楚。

- 使用者如遇问题，可邮件<13012057210@163.com>和我交流.

##### **LADR4eSolutions经典最全（By Axler）.pdf**

所见即所得，我认为这本的答案最经典，解法和思想最贴合原书。
这个文件与我无关，我仅仅是从<https://lew98.github.io>那里下载过来改了下文件名又传到这里；疑似是 Sheldon Axler 教授所作，或者是他的学生所作，亦或者是共同完成。

- 其中“LADR4eSolutions经典最全（By Axler）.pdf”习题答案中，截止目前，我发现的错误有：
> 第4章14题第(a)问，
> ······

##### **LADR4e中文版（By 吴俊达 何阳）.pdf**

这个文件与我无关，也不受这里**LICENSE**的限制，我仅仅是从<https://github.com/OliverWu515/LADR4e-PDF>那里下载过来改了下文件名又传到这里，这份文件受<https://github.com/OliverWu515/LADR4e-PDF>下**LICENSE**的限制。

##### **MyConfigures**

这是我个人编写LaTeX代码时使用的**TeXstudio**配置。

##### 「附：如何配置LaTex」 Trisquel/Ubuntu系统Terminal下

> sudo apt install texlive
> sudo apt install texlive-xetex
> sudo apt install texlive-lang-chinese
> sudo apt install texstudio

即可。

