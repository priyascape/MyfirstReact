# MyfirstReact

What did we do here? 
We created a new method (using arrow notation) that returns a new React Element. 
Note that there are three different arguments provided to the React.createElement method. 
First, we have a string that contains h1. This tells React which element we want to create, in this case it is an h1 html element. 
Next, we have empty curly braces where we will pass props. We do not need to worry about this for the time being, but we will learn more about them later. 

Lastly, we send in the children. 
This is what we want to create within our h1 tag. 
This could be a list of many different children, but for now we are just sending in a string.

After we define the App method, we call ReactDOM.render. 
We are telling React to display our App component within the element that has an id of root.

We have just written our first React project. 
\If you open your index.html, you should briefly see "First React page rendering..." before seeing "Our First React page has rendered". 
Our browser will first show the html we have written. 
