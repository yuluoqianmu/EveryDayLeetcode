相交链表<br/>
leetcode第160题<br/>
链接地址：https://leetcode-cn.com/problems/intersection-of-two-linked-lists/<br/>

编写一个程序，找到两个单链表相交的起始节点。<br/>
如下面的两个链表：<br/>
![example_1](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2018-12-21/example_1.png?raw=true)

在节点 c1 开始相交。<br/>

示例 1：<br/>

![example_2](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2018-12-21/example_2.png?raw=true)

输入：intersectVal = 8, listA = [4,1,8,4,5], listB = [5,0,1,8,4,5], skipA = 2, skipB = 3<br/>
输出：Reference of the node with value = 8<br/>
输入解释：相交节点的值为 8 （注意，如果两个列表相交则不能为 0）。<br/>
从各自的表头开始算起，链表 A 为 [4,1,8,4,5]，链表 B 为 [5,0,1,8,4,5]。在 A 中，相交节点前有 2 个节点；在 B 中，相交节点前有 3 个节点。<br/>
 

示例 2：<br/>

![example_3](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2018-12-21/example_3.png?raw=true)

输入：intersectVal = 2, listA = [0,9,1,2,4], listB = [3,2,4], skipA = 3, skipB = 1<br/>
输出：Reference of the node with value = 2<br/>
输入解释：相交节点的值为 2 （注意，如果两个列表相交则不能为 0）。<br/>
从各自的表头开始算起，链表 A 为 [0,9,1,2,4]，链表 B 为 [3,2,4]。在 A 中，相交节点前有 3 个节点；在 B 中，相交节点前有 1 个节点。<br/>
 

示例 3：<br/>

![example_4](https://github.com/yuluoqianmu/EveryDayLeetcode/blob/master/2018-12-21/example_4.png?raw=true)

输入：intersectVal = 0, listA = [2,6,4], listB = [1,5], skipA = 3, skipB = 2<br/>
输出：null<br/>
输入解释：从各自的表头开始算起，链表 A 为 [2,6,4]，链表 B 为 [1,5]。<br/>
由于这两个链表不相交，所以 intersectVal 必须为 0，而 skipA 和 skipB 可以是任意值。<br/>
解释：这两个链表不相交，因此返回 null。<br/>
 
注意：<br/>
如果两个链表没有交点，返回 null.<br/>
在返回结果后，两个链表仍须保持原有的结构。<br/>
可假定整个链表结构中没有循环。<br/>
程序尽量满足 O(n) 时间复杂度，且仅用 O(1) 内存。<br/>
