**O(1) 时间插入、删除和获取随机元素 - 允许重复<br/>
leetcode第381题<br/>
地址：https://leetcode-cn.com/problems/insert-delete-getrandom-o1-duplicates-allowed/<br/>

设计一个支持在平均 时间复杂度 O(1) 下， 执行以下操作的数据结构。<br/>
注意: 允许出现重复元素。<br/>

insert(val)：向集合中插入元素 val。<br/>
remove(val)：当 val 存在时，从集合中移除一个 val。<br/>
getRandom：从现有集合中随机获取一个元素。每个元素被返回的概率应该与其在集合中的数量呈线性相关。<br/>

示例:<br/>

// 初始化一个空的集合。<br/>
RandomizedCollection collection = new RandomizedCollection();<br/>

// 向集合中插入 1 。返回 true 表示集合不包含 1 。<br/>
collection.insert(1);<br/>

// 向集合中插入另一个 1 。返回 false 表示集合包含 1 。集合现在包含 [1,1] 。<br/>
collection.insert(1);<br/>

// 向集合中插入 2 ，返回 true 。集合现在包含 [1,1,2] 。<br/>
collection.insert(2);<br/>

// getRandom 应当有 2/3 的概率返回 1 ，1/3 的概率返回 2 。<br/>
collection.getRandom();<br/>

// 从集合中删除 1 ，返回 true 。集合现在包含 [1,2] 。<br/>
collection.remove(1);<br/>

// getRandom 应有相同概率返回 1 和 2 。<br/>
collection.getRandom();<br/>


