React Js Interview Question
● What is React js


● What is difference between virtual dom and shallow
dom, dom in React js
https://www.geeksforgeeks.org/what-is-the-difference-between-shadowdom-and-virtualdom/


● What is controlled and uncontrolled component in
React js
In a controlled component, form data is handled by a React component. The alternative is uncontrolled components, where form data is handled by the DOM itself. To write an uncontrolled component, instead of writing an event handler for every state update, you can use a ref to get form values from the DOM.

https://medium.com/fasal-engineering/controlled-and-uncontrolled-components-in-react-js-c3111ee0a864#:~:text=In%20a%20controlled%20component%2C%20form,must%20use%20Refs%20in%20it.

● What is hooks in React js
● What is jsx, babel, webpack
● What is Redux
● What is reducer, action, store in Redux
● What is middleware in Redux
● Explain data flow in Redux
● What is Redux-Thunk
● What is Redux-Saga, Difference between
Redux-thunk and Redux-saga
● Difference between class component and function
component
● How can we implement componentWillUnmount in
function component
● useEffect,UseState, useMemo.useCallback hooks in
Details
● Explain lifecycle method in React js
● What is difference between export default and export
in React js
● What is portal in React js
● What is reconciliation in React js
● What is useRef in React js
● What is server side render in React js
● What is useStrict in React js
● What is fragment in React js
● What is react router in React js
● What is node module in React js
● What is the default localhost server port in react js.
how can we change the local server port
● What is high order component in React js
● What is pure component in React js
● What is difference state and props in React js
● How to optimize React js app
● What is difference between React js and Angular js
● What is prop drilling in React js how to overcome it
● What is context api in React js
● What is super, constructor, render function in React js


Interviewer: Explain Redux vs 𝐑𝐞𝐝𝐮𝐱 𝐓𝐨𝐨𝐥𝐤𝐢𝐭?
 
The Redux store setup and the basic configuration to use in an application are similar. It is a waste of time matter to write the same script for different applications. Sometimes it’s a possibility to make mistakes. In a bigger application, there may be other packages needed to configure the Redux. Considering these matters, the needed packages and the basic configuration for the Redux setup are extracted and build a new package, which is Redux Toolkit.

Redux Toolkit is a set of tools that helps simplify Redux development. If I configure something through redux, as hard as it will be, but the same task we can perform it easily with the redux toolkit.

𝐑𝐞𝐝𝐮𝐱 𝐕𝐒 𝐑𝐞𝐝𝐮𝐱 𝐓𝐨𝐨𝐥𝐤𝐢𝐭:
👉 In Redux you must configure Devtools but in the Redux toolkit, you don't have to configure. Because it already has.
👉 In Redux for asynchronous performance you need to add Redux Thunk, But in the Redux toolkit, it's already built-in.
👉 Redux requires too much boilerplate code but the Redux toolkit doesn't.

*𝐓𝐡𝐞 𝐩𝐮𝐫𝐩𝐨𝐬𝐞 𝐨𝐟 𝐑𝐞𝐝𝐮𝐱 𝐓𝐨𝐨𝐥𝐤𝐢𝐭 *
The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:
👉"Configuring a Redux store is too complicated"
👉"I have to add a lot of packages to get Redux to do anything useful"
👉"Redux requires too much boilerplate code"


Q. prototype chaining definiation
The prototype is itself an object, so the prototype will have its own prototype, making what's called a prototype chain. The chain ends when we reach a prototype that has null for its own prototype. Note: The property of an object that points to its prototype is not called prototype