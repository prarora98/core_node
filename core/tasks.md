1. Explain Node and V8 in your own words ?
   '''
   Node.js = Runtime Environment ➕ #javascript Library
   -> Node is a runtime environment for executing js code🖥️.
   -> Node application is async by default👿.
   -> Node uses a single-threaded🧬 model with event looping♻️.
   '''

2. Explain steps in REPL(here) and command to start REPL ?

   ```
   REPL stants for `read eval print loop`
   Read :- Read take the input from the user.
   eval :- eval Process on the read data and process on it.
   Print:- Print show the result thats comes from eval process.
   Loop :- it's an continues process untills program can't terminates or end.
   ```

3. Run `index.js` in the same directory as script writer using `node FILE_NAME.js` and output result of console here.

4. Require fs module and read `theory.md` using fs.readFile method in index.js file.

5. Explain Buffer and different methods to create a buffer ?

6. What is blocking code ? How is it different from non-blocking/async codes ? Correct blocking code in index.js to run asynchronously ?

   ```
   As we all know js is an single thread lanuague. so it can handle one execution at a time.
   so untill the last can't resolve engine is point to that process.
   once previous one is completed its move to the next execution.
   thats blocking on engine untill once is not completed is known as `blocking code`.
   it's different because non-blocking or async code can't wait for previous one to complete.
   In javascript its process task is assign to the thread and multiple task are having multiple thread. so when one thread task completed or data ready its push it to `event queue`. and event loop always check in the event queue for completed task. if task found its process on thats.
   ```

7. Request from browser `https://altcampus.io` and copy request, response and general headers into answer.js.

8. Parse the URL `http://localhost:3000/api/v3?token=8372fcb8y2874b2t478t6t48cbtbc72t4` using `url` module's parse method and write output in answer.js

9. parse the query object as well from above url using `url.parse(url, true)` and output result in answer.js

10. create a file `math.js`
11. Export variables and functions
    - define a const pie = 3.14
    - define functions to add and multiply 2 numbers
    - export it from math.js
    - require in index.js and console the output by executing it there.

```js
// math.js
const pie = 3.14;
function sum() {}
function multiply() {}
// export it from math.js
```

2. Define above const and functions as properties and methods on module.exports object.
   - require in index.js and execute it.

```js
module.exports = {
  pie: 3.14,
  add: () => {}
};
```

3. Define above using exports

```js
exports.sum = () => {};
```
