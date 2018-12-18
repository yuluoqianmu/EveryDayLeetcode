# C++ 反转链表 1 迭代
## code
```
/**
 * Definition for singly-linked list.
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */

class Solution {
public:
    ListNode* reverseList(ListNode* head) {
        ListNode* pNext = head;
        ListNode* pLast = NULL;
        
        while(pNext){
            pNext = head->next;
            head->next = pLast;
            pLast = head;
            head = pNext?pNext:head;
        }
        return head;
    }
};
```
## 说明
1. 遍历，直接换
2. O(1)空间，O(n)时间

## 截图

![img](20181218113055-HJ-way1.png)
![img](20181218120228-HJ-way1.png)

# C++ 反转链表 2 递归
## code
```
/**
 * Definition for singly-linked list.
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */

class Solution {
public:

    ListNode* reverseList(ListNode* head) {
        if(head && head->next){
            ListNode *p = head;
            head = reverseList(p->next);
            p->next->next = p;
            p ->next = NULL;
            return head;
        }else{
            return head;
            
        }
       
    }
    
};
```
## 说明
1. 如果链表节点存在至少两个；
递归处理
2.否则直接返回
3. 空间复杂度貌似也是O(1)
