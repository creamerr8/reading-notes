1. Error Handling and Debugging
   - The JS interpreter processes one line of code at a time, when a statement needs data from anotther functiom, it stacks the new function on top
   - each time the script enters a new execution context, there are two phases of activity(prepare and execute)
   - prepare: the new scope is created, variables functions and arguments are created, the values of this keyword is determind
   - exectute: now it can assign valuues to variables, referance functions and run their code, execute statments
   - in the interpreter, each executon context has its own variables object
   - if a JS statement throws an error, then it throws an exception, at that point the interpreter stops and and looks for exceotion handling code
   - error objects can help you find where your mistakes are and browsers have tools to help you read them
   - debugging is about deduction, eliminating potential causes of an error
   - the JS console will tell you when there is a problem with the script, where to look for the problems, and what kind of issue it seems to have
   - the JS console is one of the many dev tools that are found in all modern browsers
   - the console will show you when there is an error and is displays the line where it became a problem for the interpreter
   - you can type code in the console and it will show you a result
   - browsers that have a console have a console object, which has several methods that your script can use to display data in the console
   - you can pause the execution of a script on any line using breakpoints, then you can check the values stored in the variables at that point in time
   - if you set multiple breakpoints you can step through them one by one to see where values change and aproblem might occure
   - you can indicate that a breakpoint should be triggered only if a condition is met
   - if you know your code might fail use try, catch, and finally each one is givin its own code block
   
