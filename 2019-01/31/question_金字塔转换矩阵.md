金字塔转换矩阵<br/>
leetcode第756题<br/>
地址：https://leetcode-cn.com/problems/pyramid-transition-matrix/<br/>

现在，我们用一些方块来堆砌一个金字塔。 每个方块用仅包含一个字母的字符串表示，例如 “Z”。<br/>

使用三元组表示金字塔的堆砌规则如下：<br/>

(A, B, C) 表示，“C”为顶层方块，方块“A”、“B”分别作为方块“C”下一层的的左、右子块。当且仅当(A, B, C)是被允许的三元组，我们才可以将其堆砌上。<br/>

初始时，给定金字塔的基层 bottom，用一个字符串表示。一个允许的三元组列表 allowed，每个三元组用一个长度为 3 的字符串表示。<br/>

如果可以由基层一直堆到塔尖返回true，否则返回false。<br/>

示例 1:<br/>
输入: bottom = "XYZ", allowed = ["XYD", "YZE", "DEA", "FFF"]<br/>
输出: true<br/>
解析:<br/>
可以堆砌成这样的金字塔:<br/>

![img](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2019-01/31/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20190129103412.png?raw=true)

因为符合('X', 'Y', 'D'), ('Y', 'Z', 'E') 和 ('D', 'E', 'A') 三种规则。<br/>

示例 2:<br/>
输入: bottom = "XXYX", allowed = ["XXX", "XXY", "XYX", "XYY", "YXZ"]<br/>
输出: false<br/>
解析:<br/>
无法一直堆到塔尖。<br/>
注意, 允许存在三元组(A, B, C)和 (A, B, D) ，其中 C != D.<br/>
注意：<br/>
bottom 的长度范围在 [2, 8]。<br/>
allowed 的长度范围在[0, 200]。<br/>
方块的标记字母范围为{'A', 'B', 'C', 'D', 'E', 'F', 'G'}。<br/>
