# ECNUThesis-Undergraduate

> Forked from [JJAYCHEN1e/ECNUThesis-Undergraduate](https://github.com/JJAYCHEN1e/ECNUThesis-Undergraduate).

### 华东师范大学本科生学士学位论文模版

本模板在原项目的基础上进行如下修改：

1. 诚信承诺书改为独立项，加入 `\cleardoublepage`

2. 正文、参考文献、致谢、附录全部不需要双面打印

    略影响美观，可以根据具体要求将注释掉的 `\cleardoublepage` 还原成独立项

3. 摘要换页及页码问题
    
    最新的论文规范要求摘要双面打印，因此需要使用 `\clearpage` 而不是 `\cleardoublepage`

    （原来的代码直接注释掉了整行）

4. 将XITS字体修改为STIX字体（部分），更符合常见习惯，例如 $\mathcal{G}$ 和 $\sum$

本项目仅作参考。