# In memory storage

### JavaScript Call Stack

**What is a ‘call’?**  
> a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).


**How many ‘calls’ can happen at once?**  
> one

**What does LIFO mean?**  
> last in, first out.

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**  
```
function sum (a, b) { return a + b; } function avg(a, b) { return sum (a, b) / 2; } let average = avg(10, 20);
```

**What causes a Stack Overflow?**  
> A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.



### JavaScript error messages



**What is a ‘refrence error’?**  
> Reference errors Called a variable will not defined.

**What is a ‘syntax error’?**  
> when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

**What is a ‘range error’?**  
> The RangeError object indicates an error when a value is not in the set or range of allowed values.

**What is a ‘tyep error’?**  
> when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

**What is a breakpoint?**   
> The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.

**What does the word ‘debugger’ do in your code?**  
> when running the code above you can see the “history” before reaching that breakpoint.