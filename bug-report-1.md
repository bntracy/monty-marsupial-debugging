# Bug Report!

## Describe

**What is happening? What do you see?**

Error in Postico when we attempt to populate the database

**What _should_ be happening? What do you want to see?**

We want to see a successful insert message

## Isolate

**Is this problem client side? Server side? Elsewhere? How do you know?**

It's obviously in the database or the query we're using to populate it

**What line of code is the error happening on?**

Paste the relevant code here:
```js
```

And describe what it's doing wrong:

Invalid input syntax for type integer: "Red"

**What tools did you use to isolate the error?**

- [ ] `console.log()`
- [ ] Chrome debugger (_Sources_ panel)
- [ ] VSCode debugger
- [ ] Chrome Network Panel
- [ ] Postman
- [X] Postico

<!-- Briefly describe how the tool helped you, and how you used it -->


## Fix

❗ Don't try to fix before first **describing** and **isolating!**

Briefly describe your fix:

Change the type of the name column to varchar

**What tools did you use?**

- [ ] Fix one line of code. Then test using the debugger or `console.log()`s.
- [ ] Google search
- [ ] Ask a pod mate for help
- [ ] Escalate

**Results**

Success, values inserted

<!-- Go back to your original description. Is the app behaving how you want it to, now? Describe the bug, technically: what was your code doing wrong, and how did you fix it. -->