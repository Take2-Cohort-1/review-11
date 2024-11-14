# React Review 1

## Answer 1 Create a Simple Component

```js
// Write your code here
function Intro() {
  return (<h1>Intro to React!</h1>);
}
```

## Answer 2 Create a Bigger Component

```js
// Write your code here
function Ciao() {
  return <>
    <p>Ciao</p>
    <p>Mundo</p>
  </>;
}
```

## Answer 3 Create an Image Component

```js
// Write your code here
function LoginButton() {
  return <div>
    <img src="../assets/images/profile-picture.jpg" />
    <button>Sign out</button>
  </div>;
```

## Answer 4 Create a Component that Uses Variables

```js
const username = "john_doe";
const xp = 737451;

// Write your code here
function Profile() {
  return <>
    <div>{username}</div>
    <div>{xp}</div>
  </>
};
```

## Answer 5 Is the Code Correct? Components
Components need to start with an uppercase letter.


## Answer 6 Export a Component

```js
// Modify the code below

const ChapterList = () => {
  return (
    <div>
      <h2>Table of Contents</h2>
      <ul>
        <li>Introduction to Biking</li>
        <li>Chapter 1: Choosing the Right Bike</li>
        <li>Chapter 2: Essential Bike Gear</li>
        <li>Chapter 3: Basic Riding Techniques</li>
        <li>Chapter 4: Maintaining Your Bike</li>
        <li>Conclusion: Enjoying Your Ride</li>
      </ul>
    </div>
  );
};

export default ChapterList;
```

## Answer 7 Import a Component

```js
// This is the App.jsx file
import Gallery from './components/Gallery.jsx'
```

## Answer 8 Is the Code Correct? JSX
Cannot return two sibling root tags. Needs a fragment tag.

## Answer 9 Fix the JSX Bugs

```js
// Modify the code below

const Summary = () => {
  return (
    <>
      <div className="title">
        <h1>My Site!</h1>
      </div>
      <p className="description">
        You can find my thoughts here
        <br/>
        <b>And <i>I</i></b> have plenty of them!
      </p>
    </>
  );
}
```

## Answer 10 Create a Component with a Prop

```js
// Write your code here
let Greeting = (props) => {
  const { name } = props;

  return (
    <>
      <p>Hello</p>
      <Name name={props.name} />
      <Name name={name} />
      <Name ...props />
    </>
  )
}
```

## Answer 11 Pass a Prop to a Component

```js
let Greeting = (props) => {
  const { name } = props;

  return (
    <>
      <p>Hello</p>
      <Name name={props.name} />
      <Name name={name} />
      <Name ...props />
    </>
  )
}

const App = () => {
  // Add your Greeting component here
  return (<Greeting name="Jonno"/>)
};
```

## Answer 12 Denise's chat


