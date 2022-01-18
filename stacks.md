<h1>Stacks</h1>
<p>A stack is a linear data structure. It stores items in a list and can be acces from the last end.
<br>
<br>
<img src ='IMAGE 14.png' width="1000" alt="https://scoutapm.com/blog/how-to-create-a-python-stack"></p>
<br>
<p>This is refered to as (LIFO) Last in first out a queue which is the same principle except it is accessed as (FILO) first in last out.</p> 
<p><img src ="stack1.png" width="1000" alt="https://scoutapm.com/blog/how-to-create-a-python-stack"></p>
<br>
<p>A real world metaphore for a stack would be a stack of pankakes. You stack them up and usually eat the first one on the top of the stack. The one on the top of the stack is the first one out of the stack. </p>
<img src="pancake.jpg" alt="https://www.redbubble.com/i/poster/What-s-Your-Stack-Web-Developer-Pancakes-by-offbeige/48513133.LVTDI" width="1000">
<h2>Stack vs Queue</h2>
<p>When to use a queue vs a stack. An example would be a line of customers. Whoever is first should be the first out of line. The difference between the two is how you acces the stack or queue. Last in First out, or First in Tirst out.</p>
<h2>Functions</h2>
<p>There are built in functions for the stack that you can use to manipulate the data within or add and take away data.</p>
<ul>
<li>empty()</li>
<li>size()</li>
<li>top()</li>
<li>push(a)</li>
<li>pop()</li>
</ul></p> 

<h3>Push(value)</h3>
<hr>
Appends an item to the end of a stack.<br>
Time O(1)

    list = []
    list.append(1)
    list.append(2)
    list.append(3)
    print(list)

    [1, 2, 3]
<h3>Empty()</h3>
<hr>
Returns weather the stack is empty or not.<br> Time O(1)

    if len(list) == 0:
        print(list)

    []
<h3>Size()</h3>
<hr>
Returns the size of the stack<br>
Time O(1)

    length = len(list)
    print(length)

    3
<h3>Pop()</h3>
<hr>
deletes the topmost element of a stack<br>
Time O(1)

    list.pop()
    print(list)

    [1,2]
<h2>Time</h2>
<p>Notice all of the runtimes for each of the functions is the best possible O(1). This means that regardless of the size of data it will be close to instantanious. </p>
<h2>Practice</h2>
<hr>
<p>Push three numbers to the stack and get rid of the last number added</p>

    stack = []

<details>
  <summary>Answer</summary>
    
    stack = []
    stack.append(0)
    stack.append(1)
    stack.append(2)
    stack.pop()
    print(stack)

    [0,1]
</details>
<p>Get the size of your previous stack and add that number to the stack</p>
<details>
  <summary>Answer</summary>
    
    stack = []
    stack.append(0)
    stack.append(1)
    stack.append(2)
    stack.append(5)
    stack.pop()
    length = len(stack)
    stack.append(length)
    print(stack)

    [0,1,2,3]
</details>

























































