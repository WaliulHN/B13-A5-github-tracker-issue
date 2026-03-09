# Assignment-05: GitHub Issues Tracker


1️⃣ What is the difference between var, let, and const?

Ans - Var is the old way of declaring variables and it's function-scoped, which means it can leak outside of blocks like loops or if statements and cause bugs. Honestly, I don't use it much anymore. Let and const are block-scoped, so they stay contained where you define them. The main choice between those two is whether the value changes. If I'm reassigning the variable later, I use let. If it's staying the same, I stick with const to prevent accidental changes.


2️⃣ What is the spread operator (...)?

Ans - It's those three dots you see all over the place now. Basically, it lets you unpack an iterable like an array or object into individual elements. I use it most often to copy arrays without mutating the original one or to merge objects together. It's also handy for passing arguments into functions if you already have them stored in a list.

3️⃣ What is the difference between map(), filter(), and forEach()?

Ans - They all loop through arrays, but they have different jobs. Map is for transforming data—it runs a function on every item and returns a new array with the results. Filter is for selecting data—it checks a condition and returns a new array with only the items that passed. Foreach is just for executing code on each item, like logging something, but it doesn't return anything useful so you can't chain methods off it.

4️⃣ What is an arrow function?

Ans - It's a shorter syntax for writing functions using the fat arrow => instead of the function keyword. They're cleaner for callbacks and one-liners. The tricky part is that they don't have their own this context, so they inherit it from the surrounding code. That's great for most things, but you have to be careful if you're using them inside object methods where you need this to refer to the object itself.

5️⃣ What are template literals?

Ans - These are strings defined with backticks instead of single or double quotes. The biggest advantage is interpolation, where you can embed variables directly inside the string using ${variable} without worrying about concatenation. It also makes multi-line strings way easier since you don't need to add \n characters everywhere.


