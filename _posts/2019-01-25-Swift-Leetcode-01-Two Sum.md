
---


layout: post

title: Swift - Leetcode - 01 - Two Sum

date:  2019-01-25 17：20：44.000000000 +09：00

---

  

**题目描述：**

给定一个整数数组  `nums` 和一个目标值  `target`，请你在该数组中找出和为目标值的那 **两个** 整数，并返回他们的数组下标。
你可以假设每种输入只会对应一个答案。但是，你不能重复利用这个数组中同样的元素。

**示例:**

给定 nums = [2, 7, 11, 15], target = 9

因为 nums[**0**] + nums[**1**] = 2 + 7 = 9所以返回 [**0, 1**]


---

**Swift实现**



`一、暴力法`

```angelscript
func twoSum(_ nums: [Int], _ target: Int) -> [Int] {
    var array = [0 ,0]
    for x in 0..<nums.count {
        for y in x+1..<nums.count {
            if nums[x] + nums[y] == target {
                array[0] = x
                array[1] = y
                return array
            }
        }
    }
    return array
}

```

`二、两遍哈希表`

```smali
func twoSum(_ nums: [Int], _ target: Int) -> [Int] {
    var dic1 = [Int:Int]()
    for x in 0..<nums.count {
        dic1[nums[x]] = x
    }
    for x in 0..<nums.count {
        let answer = target - nums[x]
        if (dic1.keys.contains(answer) && dic1[answer] != x) {
            let array = [x, dic1[answer]]
            return array as! [Int]
        }
    }
    let array = [0, 0]
    return array
}

```

`三、一遍哈希表`

```smali
func twoSum(_ nums: [Int], _ target: Int) -> [Int] {
    var dic1 = [Int:Int]()
    for x in 0..<nums.count {
        let answer = target - nums[x]
        if (dic1.keys.contains(answer) && dic1[answer] != x) {
            let array = [dic1[answer], x]
            return array as! [Int]
        }
        dic1[nums[x]] = x
    }
    let array = [0, 0]
    return array
}
```

