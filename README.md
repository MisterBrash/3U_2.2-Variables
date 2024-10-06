# 2.2 - Variables

##### ICS3 - Mr. Brash 🐿️

### If you missed the live demonstration in class, read below. Otherwise you can go straight to [your task](./YOUR_TASK.md).

<br>

---

<br>

Giving output is fairly easy with `console.log( )`. But what if we want to **_hold a value_** to be used later or for calculations?
Perhaps we want to hold a _lot_ of values like phone numbers, the locations of items in a 3D space, a list of colours, or financials.

> Don't feel like reading? [Watch this video](https://youtu.be/hmIxMwTBsO4).

_Variables_ hold numbers or text directly in the memory in the computer. We reserve a block of memory space by asking for one. Here's an example from math class:

> Let <b>w</b> represent the number of watermelons<br>
> Let <b>apple</b> represent the number of apples<br>
> w = 2<br>
> apples = 7<br>
> Let shopping_list = w + apples

### 🤔 In the example above, what is the value of `shopping_list`?

Variables in JavaScript are very similar:
```JS
let w = 2;
let apples = 7;
let my_list = w + apples;  // sets the variable 'myList' to 9
console.log(my_list);      // output the value of 'myList'
```

**Note** - you might see the keyword `var` being used online instead of `let`. You should _always_ use `let` when creating a variable. If I see `var` in your work, I will probably assume you plagiarized / cheated.

After being _declared_, the variable can be used as much as you want. Think of it like a box, a bucket, or envelope.

### 🗒️ Quick Recap:
- To declare variables, we will use the **`let`** statement (similar to math class).
- We use the '**assignment**' operator (a single =) to _assign_ or _change_ the value.
- It is _**not**_ like algebra where left equals right, it is a _statement_ "x become 5"
- Variables can be reused, manipulated, and destroyed.

---

For example, if we want to change the value of `w` to 4 and then add 3:
```JS
let w = 2;
w = 4;
w = w + 3;
```

☝️ We did not use the keyword `let` every time, only when _declaring_ the variable.

📝 **Note:** You can declare a variable without giving it a value.


## 💻 Try it:
- Go to [the code file](./main.js)
- Create a variable called `age` and make it equal to _your age in years_
- Output your age to the console
- Preview the page and check the console to see if it worked
---

### Variables can be different _types_ of data:
```JS
let myNumber = -45;
let myString = "Some text, in quotes";
let myBoolean = true;   // or false
```

### Text or Words (called "Strings")
Strings can be combined (concatenated) using the `+` operator
```JS
let myString = "This is text";
myString = "This " + "and " + "that";    //  the value is now 'This and that'
```

Strings _cannot_ be subtracted!
```JS
myString = "This and that" - "that";   //  not possible
```

## 💻 Try it:
- Go back to [the code file](./main.js)
- Change your output line to this: `console.log("I am " + age + " years old.")`
- Go to the console to see the output.

<hr>

### Booleans (true or false)
Not very helpful _right now_ but a variable can be TRUE or FALSE to help with logic
```JS
let sample = true;   // 1 or true
let sample0 = false; // 0 or false
let sample1 = 5;     // considered true
let sample3;         // considered false
```

Need more help on variables?
([Tutorial on variables](https://javascript.info/variables)) ([w3schools reference](https://www.w3schools.com/js/js_variables.asp))


---

### Follow the instuctions in [your task](./YOUR_TASK.md) to practice variables and math.

<br><br>

🐿️
