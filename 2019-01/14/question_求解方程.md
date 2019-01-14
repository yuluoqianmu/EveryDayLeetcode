##求解方程<br/>
leetcode第640题<br/>
地址：https://leetcode-cn.com/problems/solve-the-equation/<br/>

求解一个给定的方程，将x以字符串"x=#value"的形式返回。该方程仅包含'+'，' - '操作，变量 x 和其对应系数。<br/>

如果方程没有解，请返回“No solution”。<br/>

如果方程有无限解，则返回“Infinite solutions”。<br/>

如果方程中只有一个解，要保证返回值 x 是一个整数。<br/>

示例 1：<br/>
输入: "x+5-3+x=6+x-2"<br/>
输出: "x=2"<br/>

示例 2:<br/>
输入: "x=x"<br/>
输出: "Infinite solutions"<br/>


示例 3:<br/>
输入: "2x=x"<br/>
输出: "x=0"<br/>

示例 4:<br/>
输入: "2x+3x-6x=x+2"<br/>
输出: "x=-1"<br/>

示例 5:<br/>
输入: "x=x+2"<br/>
输出: "No solution"<br/>