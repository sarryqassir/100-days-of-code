# 100 Days Of Code - Log

### Day 0: January 23, 2022, Sunday

**Today's Progress**:
Finished up [basic algorithim scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) and started on [OOP](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#object-oriented-programming). I forgot to save any of my solutions and FCC doesn't save anything after submission, so no examples from there.

**Concepts**: Went over big O notation basics again, I'll be keeping it in mind in some of my solutions.

**Leet Code**: [Detect Capital🟢](https://leetcode.com/problems/detect-capital/) This problem was easy but took me a long time. Writing pseudo-code would have helped a lot, lesson learned. I will also be timing myself in the future.

### Day 1: January 24, 2022, Monday

**Progress**: Finished FCC OOP

**Thoughts**: React used class components for a long time, and is still popular in documentation and code bases. Knowing what OOP is like in other languages furthers my knowledge about the concept as a whole. 

**Leet Code**: [Roman to Integer🟢](https://leetcode.com/problems/roman-to-integer/) Time: ~40 Minutes | Language: JS | I used an object with the roman numerals as keys and their respective numeric values as values. I split the string and iterated through it, subtracting from the total if the previous value < the next value, and adding otherwise.


### Day 2: January 25, 2022, Tuesday

**Progress**: Finished FCC [Functional Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#functional-programming) section

**Thoughts**: The challenges were mostly based on standard array functions like map/filter/reduce, which I already understood, but the concept of functional programming is still important to consider, so going over the concepts such as pure functions and best practices will likely still help me.

**Leet Code**: Was busy with school/irl, will make up for it tomorrow.


### Day 3: January 26, 2022, Wednesday

**Progress**: Got started on FCC [Intermediate algorithim scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#intermediate-algorithm-scripting)

**Thoughts**: Considering taking a course on data structures and algorithims, since that is what I'm working with when doing leetcode questions, and what I'll need in a lot of interviews in the future.

**Leet Code**: 
[Valid Mountain Array🟢](https://leetcode.com/problems/valid-mountain-array/) Time: ~45 Minutes | Language: Python | Fun problem, I could have used two while loops, but instead I used a flag. <details><summary>See Solution</summary>
```py
class Solution:
    def validMountainArray(self, arr: List[int]) -> bool:
        # Avoid reevaluating len more than once
        N = len(arr);
        
        # Validate array
        if N < 3 or arr[0] > arr[1]:
            return False;
        
        # Flag for change from increasing to decreasing
        peaked = False;
        
        for i in range(N-1):
            # Not strictly inc/ dec
            if arr[i] == arr[i+1]:
                return False;
            
            if not peaked:
                # Looks for change from inc to dec
                if arr[i] > arr[i+1]:
                    peaked = True;
            # Make sure elements are decreasing if peaked
            elif arr[i] < arr[i+1]:
                return False;
        
        # After valid checks, true if array peaked
        return peaked;
```
</details>

### Day 4: January 27, 2022, Thursday
  
<!--
- [Valid Parentheses 🟢](https://leetcode.com/problems/valid-parentheses/)
🔴🟠🟡🟢🔵🟣🟤⚫⚪🔘🛑⭕
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)

### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) -->
