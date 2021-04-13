# Coding Problems To Solve

## 1)<br />
Very simple:
React.js, JavaScript, TypeScript

DO NOT edit any code, except:
Just add little code after this line:
```typescript
let myRef = selectedDate;
```
so the year will be rendered as 2099
after 1 second timeout.

Problem:
https://codesandbox.io/s/elegant-stallman-s3guu?file=/src/App.tsx

Solution:
https://codesandbox.io/s/epic-stonebraker-po87l?file=/src/App.tsx

<br />

## 2)<br />
Let the inputs of the textareas survive after tab refresh, even for duplicated tabs, and the inputs must be independent of each other (typing in one textarea should not cause changing the input in the neighboring textareas or in the textareas of the neighboring tabs). And also, if all tabs are closed, then if one tab opens again, the input text must be the very last changed text of the textareas of the previous tabs.<br />
React.js, JavaScript, TypeScript

**DO NOT edit any code, except the body of the `useStateOfSessionAndLocalStorage` hook**<br />
Problem:
https://codesandbox.io/s/vibrant-pine-6rhsk?file=/src/App.tsx

Solution:
https://codesandbox.io/s/elated-dirac-8qxvf?file=/src/App.tsx


<br />

## 3)<br />
The countUp must count from 0 to 20000 in about 10-15 seconds.<br />
Rule 1) from 0 to 19990 countUp must be linear in time (useEasing={false}).<br />
Rule 2) from 19991 to 20000 countUp must be smoothly slowing down (non-linear) in time (useEasing={true}).<br />

First rule is already working, now make the second rule work too.

**DO NOT edit any code, except the body of the `onEnd` function. Do not write number values manually, use the variables of the component**<br />
Problem:
https://codesandbox.io/s/cranky-turing-x0pub?file=/src/App.tsx

Solution:
https://codesandbox.io/s/heuristic-flower-um6f0?file=/src/App.tsx


<br />
