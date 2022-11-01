# React-Notes
1. Inside of a
   <b> VS code sde</b><br>
   Following is React App Command :npx create-react-app <i>my-app</i><br>
   Be careful to put everything in smallcase.
2. We can even include cdn link in our project:
   https://reactjs.org/docs/cdn-links.html and run the same on VS code. </br>
   To make it possible, we need to install the Live server extension and then later press on the Go Live option in the bottom-most part of the vs code interface. 
3. <b>Redux</b>
   Redux is a tool for a state management. It is used to manage the state of data and access them at different components level in the app. In redux, there are three parts as follows:Actions, Reducer & Store.<br>
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
   <i>Notes: A pure function can be made impure using by changing the shallow copy of an input argument</i>
   
