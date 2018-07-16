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

Variable scope is straight forward. let is a huge improvement over var to the point where I'd say it's
a bad practice to even use var. const on the other hand, is still a little squishy. It's also got a tight scope
like let, but it partially prevents value changes. You can't re-assign, but you can update its values (squishy).
Use const except where you need reassign it. Then use let. And define them both in the narrowest scope (in a block)

---

##### How did it go with making the adaptation from concatenations to template literal notation? Do you think you'll mostly use template literal notation from now on?

Tough call. It's one of those things that is less clear if you know the core JavaScript languge, and then learn
template literals. I find the former syntax easy to read. I think template literals add a lot of noise, to save
a few characters. I probably would have recommended it never be developed. It's added another way to do simple
task with different syntax. But - if it becomes dominant to the point where 80% of developers do it that way,
and maybe there are some standards and practices bodies that decide its a best practice, then I'd follow that
trend. I expect if I wrote it enough times, the complexity of the syntax would become more internalized.
