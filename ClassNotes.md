3 ways to add css to our projects 
- Inline styling, is when you add css directly into our html elements

```html
    <h1 style="color:blue; font-size: 116px;">CSS is really cool!</h1>
```

- Another example 
```html
<h1 style="color:blue; font-size: 116px;">CSS is really cool!</h1>
    <p style="color: red">this is a p tag with inline styling</p>
    <div style="color: green;">
        <ul>
            <li>do laundry</li>
            <li>cook dinner</li>
            <li style="color: red;">work out maybe</li>
        </ul>
    </div>

```

- Internal styling, is when we use the style tag in our head element to create css
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Day1</title>
    <style>
        /* element we are looking for */
        h1 {
            /*rules we want to apply to those elements  */
            color: blue;
            background-color: rgb(7, 183, 124);
            font-size: 90px;
        }

    </style>
</head>

```

- the last way to add css to our projects is by External style sheets, we move all of our internal styling in to a `styles.css` file, and link it to our `index.html`
- >html:
```html
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Day1</title>
    <link rel="stylesheet" href="styles.css">
</head>

```
  >css file

```css
    #p1 {
      color: blue;
  }

  /* class css selector */
  .example {
      color: green;
      background-color: beige;
  }

  /* element we are looking for */
  h1 {
      /*rules we want to apply to those elements  */
      color: blue;
      background-color: rgb(7, 183, 124);
      font-size: 90px;
  }

  p {
      color: red;
      font-size: 10px;
  }

```

- css selectors can be created with element tags, classes, and ids:
```css 
/* id */
        #p1 {
            color: blue;
        }
/* class */
        .example{
            color: green;
            background-color:beige;
        }
/* element tag */
        h1 {
            /*rules we want to apply to those elements  */
            color: blue;
            background-color: rgb(7, 183, 124);
            font-size: 90px;
        }

```


