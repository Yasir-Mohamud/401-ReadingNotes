EXCEPTION HANDLING AND DEBUGGING
--------------------------------
- When debugging there are some tips to follow ;-
1.Clarify the problem - what you expected vs what happened instead.
2.Examining your assumptions - making sure you did the correct steps in the correct way.
3.Run code through debugger - This helps to identify the point in which the errors appear.


- If you are unsure that your code will throw exceptions using the try\catch block will catch the exception and run any code in the catch statement block.``Each exception must be written with a new catch block``.
- The CLR (Common Language Runtime) catches exceptions that are not caught by the catch block.

- Some Exception handling statments are ;-
1.throw
2.try-catch
3.try-finally
4.try-catch-finally

- the catch clause specifies which type of exception to catch where as the finally-block executes regardless if a exception is thrown.
- Debugging is not only a skill every dev should have but it can help save live as the Therac-25 caused deaths due to false radiation reading caused by bugs in the software.
