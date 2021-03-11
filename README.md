# 概率论与数理统计教程
使用 2004 年版本

# 分工

+ 第一章（曹甄强）
+ 第二章（酸奶）
+ 第三章（徐澳进，何骏炜）
+ 第四章（啸行）
+ 第五章（向禹）
+ 第六章（汤）
+ 第七章（八一）
+ 第八章（东升）

# 数学排版约定

1. **中英文之间一定要加空格！！！**
2. 标点符号全部使用英文符号，文本模式中，**标点符号后需要加空格**
    1. 示例：`中文 English $x$ 难道不是这样写的么? 根据韦达定理, 平方和 $x^2$ 和另外 $y^2$, 我也不知道我在写什么.`
3. 不要用直立积分符号
4. 行内数学模式内，分数用 `\tfrac` 或者 `/`，行间公式用 `\frac` 或者 `\dfrac`
5. 使用 `\leqslant` 和 `\leq` 均可
6. 自然对数底定义新命令 `\newcommand{\ee}{\mathrm e}`
  在指数形式比较复杂时，用 `\exp` 表示自然对数底
7. 行内分式不需要用 `\displaystyle`
8. 关键词用 `\textbf{关键词}`，然后建立索引 `\index{G!关键词}`
  `G` 表示名词首字母用于排序，`!` 后面的就是关键词的名字
9. 积分里面的微分符号 `d` 定义为`\newcommand{\dd}{\,d}`
  输入的时候就输入 `\dd`，这样即便有必要改为正体也容易
10. 数学公式中，使用 `\ldots` 进行罗列，如果两边是操作符，用 `\cdots`
11. 交叉引用-标签
     + 公式（equation）：`\label{eq:3.1.2}`
     + 表格（table）：`\label{tab:3.1.2}`
     + 图（figure）：`\label{fig:3.1.2}`
     + 章节（chapter）：`\label{cha:3.1.2}`
     + 小节（section）：`\label{sec:3.1.2}`
     + 小小节（subsection）：`\label{ssec:3.1.2}`
     + 示例（example）：`\label{exam:3.1.2}`
     + 练习（exercise）：`\label{exer:3.1.2}`
     + **其他定理环境交叉引用，请参考 ElegantBook 说明文档**。
12. 交叉引用-引用
     + 使用`~\ref{label}` 进行引用，注意空格，示例：`在表~\ref{tab:3.1.2} 中...`
13. 表格推荐使用 table+tabular 环境结合三线表：`\toprule`，`\midrule`，`\bottomrule` 制作。
14. 公式里面距离，一般距离用 `\;`，然后大距离用 `\quad` 或者 `\qquad`（基本用 `\quad`）
15. 习题用settings里面定义的xiti环境\begin{xiti}blablabla\end{xiti}，内层问题列表用enumerate环境


```tex
\let\leq\leqslant
```

# 其他

+ 排版时建立索引
+ 图片注意命名规范，可以直接用书中得命名方式，避免冲突
+ 编译文件需使用**汉仪大宋简字体**，该字体可在[汉仪字库](http://www.hanyi.com.cn/font-list)下载，按网站流程注册后即可
