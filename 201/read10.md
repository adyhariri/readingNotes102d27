
# ERROR HANDLING AND DEBUGGING

JavaScript can be hard to learn and everyone makes mistakes when writing it. 
When you are writing JavaScript, do not expect to write it perfectly the first time.

### ORDER OF EXECUTION 

To find the source of an error, it helps to know how scripts are processed.

The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run .

### EXECUTION CONTEXTS

Every statement in a script lives in one of three execution contexts: 

 > **GLOBAL CONTEXT** :Code that is in the script, but not in a function. There is only one global context in any page.

 > **FUNCTION CONTEXT** : Code that is being run within a function. Each function has its own function context. 

 > **EVAL CONTEXT (NOT SHOWN)** : Text is executed like code in an internal function called eval ()

### VARIABLE SCOPE 

The first two execution contexts correspond with the notion of scope :

 > **GLOBAL SCOPE** : If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 

 > **FUNCTION-LEVEL SCOPE** : When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope. 

### EXECUTION CONTEXT & HOISTING 

Each time a script enters a new execution context, there are two phases of activity:

 1. **PREPARE**

   > The new scope is created 

   > Variables, functions, and arguments are created

   > The value of  this keyword is determined

 2. **EXECUTE**

   > Now it can assign values to variables 

   > Reference functions and run their code 

   > Execute statements 

### UNDERSTANDING SCOPE

In the interpreter, each execution context has its own variables object. 

It holds the variables, functions, and parameters available within it.

Each execution context can also access its parent's variables object. 

### UNDERSTANDING ERRORS 

If a JavaScript statement generates an error, then it throws an exception. 

At that point, the interpreter stops and looks for exception-handling code. 

### ERROR OBJECTS 

Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

#### ERROR OBJECTS CONTINUED

 > **Syntax Error**: This is caused by incorrect use of the rules of the language. 

 > **Eval Error** : INCORRECT USE OF eval() FUNCTION (rare to see this kind of error)

 > **Reference Error** : This is caused by a variable that is not declared or it is out of scope.  

 > **URI Error** : If these characters are not escaped in URls, they will cause an error: / ? & I : ;

 > **Type Error** : This is often caused by trying to use an object or method that does not exist.  

 > **Error** : The generic Error object is the template (orprototype) from which all other error objects are created. 

 > **Range Error**: If you call a function using numbers outside of its accepted range. like creating array with -1 item

 > **NaN** : Note: If you perform a mathematical operation using a value that is not a number, you end up with the value of NaN, not a type error

### A DEBUGGING WORKFLOW 

Debugging is about deduction: eliminating potential causes of an error. 

**BROWSER DEV TOOLS & JAVASCRIPT CONSOLE**: The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be.
