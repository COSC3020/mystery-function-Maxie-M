# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

# My Answer, Maxie M.
## What `mystery()` function does 
- The purpose of this function is to find the **maximum** value in an array
## How it works
- The function will return the element (base case), if the array has only one element
- The fucntion will recursivelt call *mystery* on the rest of the array
- Will compare the first element with the **maximum** of the rest and will return the larger value
## Example
- **input:** [3, 5, 2, 9, 1]
- **output:** 9
# Plagiarism Statement:
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
