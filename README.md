# React-Notes
React is a library that helps to create a single page application. A <b>single page application</b> is a kind of application that loads at a single time and other dynamic functions is carried out by the javascript framework. It is maintained by the facebook organization and is very popular nowadays. 

Before starting with redux, it is really important one must know the basics of javascript. So to know more on javascript please carry the reference of the given link as follows: https://www.w3schools.com/js/
React js Doc : https://reactjs.org/

1. Inside of a
   <b> VS code sde</b><br>
   Following is React App Command : npx create-react-app <i>my-app</i><br> OR
   npm create-react-app <i>my-app</i>(this will install whole packages)<br>
   Be careful to put everything in smallcase.<br>
   Shortcut to replace a bunch of words or open a replace tab : ctrl + shift +h
2. We can even include cdn link in our project:
   https://reactjs.org/docs/cdn-links.html and run the same on VS code. </br>
   To make it possible, we need to install the Live server extension and then later press on the Go Live option in the bottom-most part of the vs code interface. <br>
3. <b>Redux</b>
   Redux is a tool for a state management. It is used to manage the state of data and access them at different components level in the app. In redux, there are three parts as follows: Actions, Reducer & Store.<br>
   <h3>React Features</h3>
   i. Redux is predictable<br>
         -- we do know from where the state is changing, why it is changing and who it is changing.<br>
   ii. Easier to maintain<br>
        -- Easier to maintain because of a predefined properties.<br>
   iii. Persistence of storage <br>
       -- we can prefill data in our local storage<br>
 
   <h3>Lifecycle of a Redux</h3>   
   <p>Actions only describe what happened, but don't describe how the application's state changes. Actions always move in uniderectional way that is in clockwise direction. <p>
   

![reactArchitecture](https://user-images.githubusercontent.com/96413187/198951659-9a73bceb-d901-42d1-b518-ac6659cc4e38.png)

   4. <b>Reducers</b><br/>
      Reducers are pure functions. It will specifies how the application's state changes in response to actions sent to the store. For a functions to be pure functions, it's need to satisfy three principles.<br/>
   i.<b> Same Input, Same Output</b>: For the same input, the output must be same.<br/>
   ii.<b> Scope of the variable </b>: The function must rely on the input within the function.<br/>
   iii.<b> Cannot create any side effects</b> :  We cannot manipulate dom inside of it or called an ajax function.<br/>
   <i>Notes: A pure function can be made impure using by changing the shallow copy of an input argument</i><br/>

   5. <b>Store</b><br/>
    It is an object which provides the state of the application. This object is accessible with help of the provider in the files of the project. The only way to change the state inside it is to dispatch an action on it.<br/>
   
   6. To create a router, follow up the offcial documentation: https://v5.reactrouter.com/web/guides/quick-start
      Please make changes as per the version changes.
       
   
