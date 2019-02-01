---
layout: post
title: Swift - Leetcode - 02 - Add Two Number
date: 2019-01-30 10:20:20.000000000 +09:00
---

  

**题目描述：**

给出两个**非空**的链表用来表示两个非负的整数。其中，它们各自的位数是按照**逆序**的方式存储的，并且它们的每个节点只能存储 一位 数字。

如果，我们将这两个数相加起来，则会返回一个新的链表来表示它们的和。

您可以假设除了数字 0 之外，这两个数都不会以 0 开头。

**示例:**
输入： (2 -> 4 -> 3) + (5 -> 6 -> 4)
输出： 7 -> 0 -> 8
原因： 342 + 465 = 807

---

**Swift实现**



`思路`

将当前结点初始化为返回列表的哑结点。
将进位 carrycarry 初始化为 00。
将 pp 和 qq 分别初始化为列表 l1l1 和 l2l2 的头部。
遍历列表 l1l1 和 l2l2 直至到达它们的尾端。
将 xx 设为结点 pp 的值。如果 pp 已经到达 l1l1 的末尾，则将其值设置为 00。
将 yy 设为结点 qq 的值。如果 qq 已经到达 l2l2 的末尾，则将其值设置为 00。
设定 sum = x + y + carrysum=x+y+carry。
更新进位的值，carry = sum / 10carry=sum/10。
创建一个数值为 (sum \bmod 10)(summod10) 的新结点，并将其设置为当前结点的下一个结点，然后将当前结点前进到下一个结点。
同时，将 pp 和 qq 前进到下一个结点。
检查 carry = 1carry=1 是否成立，如果成立，则向返回列表追加一个含有数字 11 的新结点。
返回哑结点的下一个结点。

`官方题解Swift实现`

{% highlight ruby %}
func addTwoNumbers(_ l1: ListNode?, _ l2: ListNode?) -> ListNode? {
    let dummyHead: ListNode = ListNode.init(0)
    var p: ListNode? = l1
    var q: ListNode? = l2
    var curr: ListNode = dummyHead
    var carry = 0
    while (p != nil || q != nil) {
        let x = p?.val ?? 0
        let y = q?.val ?? 0
        let sum = x + y + carry
        carry = sum / 10
        curr.next = ListNode.init(sum % 10)
        curr = curr.next!
        if (p != nil) {
            p = p?.next
        }
        if (q != nil) {
            q = q?.next
        }
    }
    if carry > 0 {
        curr.next = ListNode.init(1)
    }
    return dummyHead.next
}
{% endhighlight %}


