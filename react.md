## Welcome to using React & Tailwind Components inside of your Documents. 

```tsx
<react?
  <div className="dark:bg-zinc-500 p-4 rounded">
    <h1 classname='text-9xl'>Custom React Component</h1>
    <p>This is a custom React component embedded in Markdown.</p>
  </div>
react?>
```

## How to use it?

Welcome to React, A JSX/TSX component library where you an create custom components using HTML elements. 
In STS (Study Labs Script) you can opt into a react component by doing

<react? <-- This tag is to show the start. 

react?> <--- This tag is to show the closing. 

## Example one 

```jsx
<react?
  <div className="dark:bg-zinc-500 p-4 rounded"> <--  A pure html div
    <h1 classname='text-9xl'>Custom React Component</h1> <-- Html Heading
    <p>This is a custom React component embedded in Markdown.</p> <-- Html Paragraph. 
  </div>
react?>
```
### Due to pure css been a absolute bit of work, We will use tailwind - https://tailwindcss.com/ 

## Using Studylabs Graphing Engine. 

We will use study lab script mode to open a Grapher. 

```js
<sts?
  graph: {
    equation{
      y = a*x^2 + b*x + c
    }
    parameters {
      a = 1
      b = -2
      c = 1
    }
    title: "Quadratic Function Explorer"
    subtitle: "Adjust parameters to see how the graph changes"
    xRange: [-5, 5]
    yRange: [-2, 10]
  }
sts?>
```







