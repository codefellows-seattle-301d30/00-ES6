# 1-ES6-practice

## Feature Tasks

Follow these instructions carefully and in order.

1. Open the HTML file in the browser to ensure that it works.
2. Turn all `var` variable declarations into `let`.
3. After you do, there will be one error. Find that line in the code, delete that line and respond to the adjacent TODO item.
4. Return to the browser to ensure that the code works again.
5. **Save the code, and do a Git "add" and "commit".**
6. Now, in the code, convert all `let` variable declarations into `const`.
7. Bugs will erupt everywhere. Debug by using the error messages in the browser console, turning `const` declarations back into `let` where necessary. Expect there to be some back-and-forth between your code editor and your browser.
8. When you think you have things working, clear local storage and reload the page to ensure that the code still works when starting from a totally clean state.
9. **Save the code, and do a Git "add" and "commit".**
10. Now find all concatenations in the code and convert them into template literal notation.
11. Reload the browser to ensure that the code works as expected.
12. **Save the code, and do a Git "add" and "commit".**
13. Answer the following questions:

---

##### Investigate how `let` and `const` are now used in the code. Where did you need to convert `const` into `let` to make the code work? Can you identify any patterns/similarities?

Const needed to become let if somewhere in the code, it was being reassigned or it's value was being augmented (an array that was being pushed to, the previously var i in for loops). It did **not** need to be changed from a const into a let if the variable was being assigned the value of a function (which can change as in the 'rando' number function).

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

I liked it most in that it allows you to write naturally with regard to spaces in text. You can really use variables as variables. Before you had to accomodate them with plus signs and quotes, which made me annoyed enough to try and work somewhat were I wouldn't have to use them. What I'm working now is that should I actually ever you string quotes. Like in document.getElementByID can I now just say (`button`) instead of ('button')?
