1.用队列实现栈<br/>
leetcode第225题<br/>
链接地址：https://leetcode-cn.com/problems/implement-stack-using-queues/<br/>

使用队列实现栈的下列操作：<br/>
push(x) -- 元素 x 入栈<br/>
pop() -- 移除栈顶元素<br/>
top() -- 获取栈顶元素<br/>
empty() -- 返回栈是否为空<br/>

注意:<br/>
1.你只能使用队列的基本操作-- 也就是 push to back, peek/pop from front, size, 和 is empty 这些操作是合法的。<br/>
2.你所使用的语言也许不支持队列。 你可以使用 list 或者 deque（双端队列）来模拟一个队列 , 只要是标准的队列操作即可。<br/>
3.你可以假设所有操作都是有效的（例如, 对一个空的栈不会调用 pop 或者 top 操作）。<br/>


---------------------------------分割线------------------------------------------<br/>

2.用栈实现队列<br/>
leetcode第232题<br/>
链接地址：https://leetcode-cn.com/problems/implement-queue-using-stacks/<br/>

使用栈实现队列的下列操作：<br/>

push(x) -- 将一个元素放入队列的尾部。<br/>
pop() -- 从队列首部移除元素。<br/>
peek() -- 返回队列首部的元素。<br/>
empty() -- 返回队列是否为空。<br/>

示例:<br/>
MyQueue queue = new MyQueue();<br/>

queue.push(1);<br/>
queue.push(2);  <br/>
queue.peek();  // 返回 1<br/>
queue.pop();   // 返回 1<br/>
queue.empty(); // 返回 false<br/>
说明:<br/>

1.你只能使用标准的栈操作 -- 也就是只有 push to top, peek/pop from top, size, 和 is empty 操作是合法的。<br/>
2.你所使用的语言也许不支持栈。你可以使用 list 或者 deque（双端队列）来模拟一个栈，只要是标准的栈操作即可。<br/>
3.假设所有操作都是有效的 （例如，一个空的队列不会调用 pop 或者 peek 操作）。<br/>

