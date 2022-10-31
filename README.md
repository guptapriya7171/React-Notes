# React-Notes
1. In a <b> VS code sde</b>
   Create React App Command :npx create-react-app <i>my-app</i><br>
   Be careful to put everything in smallcase.
2. We can even include cdn link in our project:
   https://reactjs.org/docs/cdn-links.html and run the same on Vs code. </br>
   To make it possible, we need to install the Live server extension and then later press on the Go Live option in the bottom-most part of the vs code interface. 
3. <b>Redux</b>
   Redux is a tool for a state management. In react application, we have several components with their respective states. So for managing and passing those data we can take the help of redux.
   <h3>React Features</h3>
   1. Redux is predictable<br>
         -- we do know from where the state is changing, why it is changing and who it is changing.<br>
   2. Easier to maintain<br>
        -- Easier to maintain because of a predefined properties.<br>
   3. Persistence of storage <br>
       -- we can prefill data in our local storage<br>
       
   <h3>Lifecycle of a Redux</h3>   
   <p>Actions only describe what happened, but don't describe how the application's state changes. Actions always move in uniderectional way that is in clockwise direction. Reducers are pure functions. It will specifies how the application's state changes in response to actions sent to the store.<p>
![reactArchitecture](https://user-images.githubusercontent.com/96413187/198951659-9a73bceb-d901-42d1-b518-ac6659cc4e38.png)
