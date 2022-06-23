## JavaScript and Asynchronous Tests

Web pages do not exist on their own. They load images, iframes, content or retrieve all sorts of information from places other than their own servers. And depending on something external to your system to do something poses a problem: what if the service I depend on goes down? What if his servers are slow? What happens to my page? <br>
In normal, sequential programming logic, your page would wait for the service to return or go back online to continue. In other words, the page would be broken, or its entire load would be stopped due to a problem totally out of its control. To deal with this problem and others of a similar nature, there is a concept that is very powerful and present in JavaScript: asynchronicity. Instead of the program being loaded all in sequence, one line after another, lines that can cause this kind of problem can "keep loading" while the rest of your program runs normally. Executing that line, waiting for that service to be available, runs parallel to developing the rest of the code. It is an asynchronous execution. And that has a lot of power.<br>
Sound interesting?! Well then. Here I learned four important concepts:

- [x] Asynchronous operations;
- [x] Callbacks;
- [x] Tests with callbacks using Jest;
- [x] Setup and Teardown.