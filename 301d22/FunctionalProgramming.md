# FUNCTIONAL PROGRAMMING


**What is functional programming?**  
> Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

**What is a pure function and how do we know if something is a pure function?**  
> if  
- It returns the same result if given the same arguments (it is also referred as deterministic)  
- It does not cause any observable side effects

**What are the benefits of a pure function?**  
> The code’s definitely easier to test. We don’t need to mock anything.  
So we can unit test pure functions with different contexts

**What is immutability?**  
> Unchanging over time or unable to be changed

**What is Referential transparency?**  
> if a function consistently yields the same result for the same input, it is referentially transparent.



# Node.js


**What is a module?**  
> module is just essentially another javascript file

**What does the word ‘require’ do?**  
> it let us use another file code wherever we want

**How do we bring another module into the file the we are working in?**  
> by word require then paranthesis inside willl put a string whichgoing to be the path to the module that we are require

**What do we have to do to make a module available?**  
> specified what part of module we want it to be available to all the files which require it by :
```module.export=<here will put the part that we want it to be available>```