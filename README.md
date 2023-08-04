## Components with many state updates spread across many event handlers can get overwhelming. For these cases, you can consolidate all the state update logic outside your component in a single function, called a reducer.
## A reducer function is where you put state logic. It takes two arguments, the current state and the action object, and it returns the next state: 
## function exampleReducer(state, action) {
##  // return next state for React to set
## }
## App.js
![image](https://github.com/JoeSchmitt-2/reducer/assets/84737443/aaae2026-8aad-4df7-b66e-68191986d02f)
## tasksReducer.js
![image](https://github.com/JoeSchmitt-2/reducer/assets/84737443/f6fad655-8f69-492b-acf3-120d9282e1a4)
![image](https://github.com/JoeSchmitt-2/reducer/assets/84737443/a5aa7dc7-dae4-4cfb-a23b-c99d3b587efe)

