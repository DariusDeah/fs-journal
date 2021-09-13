# Callback Hell

## what are some of the signs of Callback Hell

call back hell is a what happens when you atempt to write JS code from top to bottom
in other langues this approach may be logically but javascript works diffrently in the sense that callback functions dont follow a top to bottom aproach but instead take some time before it exceuted

---

## What Does Asynchronus mean and how do they work with callbacks

asnyc code is code that runs once it has the data needed to execute callbacks follow this same principle callbacks are functions that can be passed as arguments in other functions they dont execute untill the higer-order function calls gives it data

---

## 3 ways you can prevent callback hell

- **Keep your code shallow** by naming your functions this makes it easier to read and makes it easier to track where errors are coming from ; also have function declarations at the bottom of your file this also makes it easier

- **Modularize** instead of having one big file that does a bulk of work split the functionality into smaller bite sized chucks into diffrent modules that you can import

- **Handle all erorrs** designate the first arugent in your callback to errors so you reamember or use a lint to indicate callbacks without error handling
