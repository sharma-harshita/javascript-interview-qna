# javascript-interview-qna


**Question : What is JS engine?**

**Answer :** JS engine is a program which gets used to execute the JS code. All the browsers have their own JS engine. But out of all the most famous one is V8 engine provided by Google chrome.
Internet Explorer has Chakra
Mozilla Firefox has Spider Monkey

Every code that has to be executed firstly gets converted into machine level language which is a combination of 0 and 1. This code is understandable by machine and then it finally gets executed. Now this complete process is known as compilation and it can be done by either compiler or interpreter. 

In case of compiler the complete code gets converted into machine level in a single shot and it creates a file which finally gets used in execution. whereas in case of interpreter the code gets converted into machine level line by line and it does not create any file. 

Javascript is a combination of both compiler and interpreter and it works on the concept of JIT (Just in time compilation). In this the whole code gets compiled in one single shot and then directly it goes for execution , no file gets generated.

Javascript is a -
1. Synchronous lanaguage means the complete code will be executed line by line
2. Single Threaded language means once the error occurs then the execution will stop at that line itself.
3. Dynamic Programming Language means when you are creating a variable and assigning it some value then this value type can be changed throughout the whole code execution which is not applicable in other programming languages.

