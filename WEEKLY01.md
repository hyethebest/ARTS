# ARTS punch in the first week

## A|Algorithm

```class Solution {
class Solution {
   public int[] twoSum(int[] nums, int target) {
    for (int i = 0; i < nums.length; i++) {
        for (int j = i + 1; j < nums.length; j++) {
            if (nums[j] == target - nums[i]) {
                return new int[] { i, j };
            }
        }
    }
    throw new IllegalArgumentException("No solution");
    }
}
```

[^tips]:The brute force approach is simple. Loop through each element x*x* and find if there is another value that equals to target - x*t**a**r**g**e**t*−*x*. 

- Time complexity : O(n^2)*O*(*n*2). For each element, we try to find its complement by looping through the rest of array which takes O(n)*O*(*n*) time. Therefore, the time complexity is O(n^2)*O*(*n*2).
- Space complexity : O(1)*O*(1).

## R|Review

```《What are some of the most basic things every programmer should know?》```

answer:

1. If it's not tested,it doesn't work.
2. Don't reinvent the wheel,library code is there to help.
3. Code that's hard to understand is hard to maintain.
4. Code that's hard to maintain is next to useless.
5.  Fewer features for better code is always the right answer in the end. 
6.  You will spend more time thinking than coding. 
7.  Bad architecture causes more problems than bad code. 
8.  Code reviews by your peers will make all of you better. 
9.  Always know how your business makes money, that determines who gets paid what. 
10.  If you want to feel important as a software developer, work at a tech company. 



## T|TIPS

- Multiline pattern space

Sed {N;P;D}

N: Next;P: Print;D: Delete 

[^tips]:The delete command (d ) deletes the contents of the pattern space and causes a new line of input to be read with editing resuming at the top of the script. The Delete command (D ) works slightly differently: it deletes a portion of the pattern space, up to the first embedded newline. It does not cause a new line of input to be read;

## S|SHARE

```English
How Elasticsearch sets up heap memory in production environment?
```

[References]:https://www.elastic.co/cn/blog/a-heap-of-trouble

