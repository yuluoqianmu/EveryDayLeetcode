##二叉树的最近公共祖先<br/>
leecode第236题<br/>
地址：https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/<br/>

给定一个二叉树, 找到该树中两个指定节点的最近公共祖先。<br/>

百度百科中最近公共祖先的定义为：“对于有根树 T 的两个结点 p、q，最近公共祖先表示为一个结点 x，<br/>
满足 x 是 p、q 的祖先且 x 的深度尽可能大（一个节点也可以是它自己的祖先）。”<br/>

例如，给定如下二叉树:  root = [3,5,1,6,2,0,8,null,null,7,4]<br/>

![img](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2019-01/09/binarytree.png?raw=true)
示例 1:<br/>
输入: root = [3,5,1,6,2,0,8,null,null,7,4], p = 5, q = 1<br/>
输出: 3<br/>
解释: 节点 5 和节点 1 的最近公共祖先是节点 3。<br/>

示例 2:<br/>
输入: root = [3,5,1,6,2,0,8,null,null,7,4], p = 5, q = 4<br/>
输出: 5<br/>
解释: 节点 5 和节点 4 的最近公共祖先是节点 5。因为根据定义最近公共祖先节点可以为节点本身。<br/>
 

说明:<br/>
所有节点的值都是唯一的。<br/>
p、q 为不同节点且均存在于给定的二叉树中。<br/>
