# React Review 1

## Instructions

### 1. Create a Simple Component

Write the code for a component called `Intro` that displays the text `<h1>Intro to React!</h1>`

### 2. Create a Bigger Component

Write the code for a component called `Ciao` that displays `<p>Ciao</p>`on one line and `<p>Mundo</p>` on the next

### 3. Create an Image Component

Write the code for a component called `LoginButton`, it should:

1. Return a `<div>` element that contains:
  1. An `<img/>` element with a `src` attribute of `'../assets/images/profile-picture.jpg'`
  2. A button labelled `Sign out`

### 4. Create a Component that Uses Variables

Create a component, it should:

1. Return a `<div>` element with the value of the `username` variable
2. Return a `<div>` element with the value of the `xp` variable

Ensure that you use the variables directly in your code, **not** the values that they point to

```js
const username = "john_doe";
const xp = 737451;
```

### 5. Is the Code Correct? Components

Is the code example below written correctly?

If you think it is, explain what HTML you expect the `FoodList` component to render.

If not, explain why you think it's not written correctly.

```js
const banana = () => {
  return <li>Green Banana</li>;
};

const FoodList = () => {
  return (
    <section>
      <h1>Bananas</h1>
      <banana />
      <banana />
      <banana />
    </section>
  );
};
```

### 6. Export a Component

Write the code that would export the `ChapterList` component

### 7. Import a Component

Imagine you are writing code for a React project with a `components` directory.

The file and folder structure looks like this, with `App.jsx` inside the `src` folder,
and `Gallery.jsx` inside a `components` folder.
```
src
├── App.jsx
└── components
    └── Gallery.jsx
```

Inside `App.jsx` write the code that would import the `Gallery` component from `Gallery.jsx`

### 8. Is the Code Correct? JSX

Is the code example below written correctly?

If you think it is, explain what HTML you expect the `ShoppingList` component to render

If not, explain why you think it's not written correctly

```js
const ShoppingList = () => {
  return (
    <h2>Shopping List</h2>
    <ul>
      <li>Apples</li>
      <li>Bananas</li>
      <li>Oranges</li>
    </ul>
  );
};
```

### 9. Fix the JSX Bugs

Fix the code below so that it doesn't break any JSX rules

There are 4 bugs in the code

```js
const Summary = () => {
  return (
    <div class="title">
      <h1>My Site!</h1>
    </div>
    <p class="description">
      You can find my thoughts here
      <br>
      <b>And <i>I</b></i> have plenty of them!
    </p>
  );
}
```

### 10. Create a Component with a Prop

Write the code to create a component called `Greeting`, it should:

1. Receive a single prop called `name`
2. Render:
   - a `<p>` tag containing `Hello`, followed by
   - another component called `Name`, which gets passed the `name` prop to it

### 11. Pass a Prop to a Component

Copy the `Greeting` component you created in the previous question. Pass the `name` prop to your component with any string value you like

You will nest your `Greeting` component inside the provided `App` component

### 12. Denise Carter-Bennett

Name something you took away from Denise's chat this morning.
