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

I needed to change const to let for the global variable array "allProducts" which makes sense so that all the blocks of code could use it and change the variable, whereas with `const` the variable would be set and couldn't be changed.

This principle regarding global variables and their reassignment also held true for the totalClicks counter

Additionally, changing `const` to `let` for the for loops is needed for the same reason (to acces and change the variable "i" as the loop progresses) 

_I also found I had accidentially changed a DOM command from `const` to `let` uneceesaryily during this review, so I changed it back to `const`_

The similarities across these three cases noted above is that in each case a change to the variable was needed for a function to work and therefore the variable needed to have the ability to be redefined, which `const` doesn't allow for, but `let` does. 

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

It was really easy and yes, I can see the advantages of template literal notation for sure!
