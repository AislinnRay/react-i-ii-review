### Remember

Answer these on your own, then compare answers as a group

1.  What is React? 
  -js library of code, manages DOM, could be called a framework

2.  What is create-react-app? 
  -package from npm. handles all of the boiler plate setup of React so that we can start building right away

3.  What is Component Based Architecture?
  - code is spilt into chunks called components. makes code highly reuseable and easy to debug. 

4.  What is JSX?
  - javascript expression looks like a blend of js and html and creates elements

5.  What is the virtual DOM?
 - light-weight copy of dom and reconsiles between them wiht updates are more fast

6.  What is unidirectional (one-way) data flow?
 - things come down from parent to child but not the other way around can only pass props from parent to child/ 
 - method lives on parent and can be passed down from parent to child. 

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
