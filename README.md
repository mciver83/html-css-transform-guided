## Project Summary

In this project, we will learn how to use css transform to allow us to make different transformations on our html elements

## Steps

After each step, use git to add and commit the changes you have made to the project!

### Step 1.

Fork this repository to create your own copy.

### Step 2.

Make `index.html` and `style.css` files. Use HTML:5 snippet and link the style sheet to the html. We will also want to link the `reset.css` file that is included in the repo. Make sure to link `reset.css` before `style.css` so that the reset styled are applied first.

In this step, let's also go ahead and change the title for our website. You can make it whatever you want.

<details>
<summary>index.html</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Tranform</title>
  </head>
</html>
```

</details>

### Step 3.

Let's create a simple square and circle on our website

<details>
<summary>index.html</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Transform</title>
  </head>
  <body>
    <div class="square"></div>
    <div class="circle"></div>
  </body>
</html>
```

</details>

<details>
<summary>style.css</summary>

```css
.square {
  background-color: aqua;
  height: 200px;
  margin: 50px;
  width: 200px;
}

.circle {
  background-color: violet;
  border-radius: 50%;
  height: 200px;
  margin: 50px;
  width: 200px;
}
```

</details>

### Step 4.

Let's use the transform css property to rotate the square by 45 degrees.

<details>
<summary>index.html</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Transform</title>
  </head>
  <body>
    <div class="square"></div>
    <div class="circle"></div>
  </body>
</html>
```

</details>

<details>
<summary>style.css</summary>

```css
.square {
  background-color: aqua;
  height: 200px;
  margin: 50px;
  width: 200px;

  transform: rotate(45deg);
}

.circle {
  background-color: violet;
  border-radius: 50%;
  height: 200px;
  margin: 50px;
  width: 200px;
}
```

</details>

### Step 5.

Let's use the transform property to makse the circle 2 times bigger and move it horizontally and viertically.

<details>
<summary>index.html</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Transform</title>
  </head>
  <body>
    <div class="square"></div>
    <div class="circle"></div>
  </body>
</html>
```

</details>

<details>
<summary>style.css</summary>

```css
.square {
  background-color: aqua;
  height: 200px;
  margin: 50px;
  width: 200px;

  transform: rotate(45deg);
}

.circle {
  background-color: violet;
  border-radius: 50%;
  height: 200px;
  margin: 50px;
  width: 200px;

  transform: scale(2) translateX(100px) translateY(200px);
}
```

</details>

### Step 6.

using the transorm propert, let's make the sqaure go off of the page.

<details>
<summary>index.html</summary>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>Transform</title>
  </head>
  <body>
    <div class="square"></div>
    <div class="circle"></div>
  </body>
</html>
```

</details>

<details>
<summary>style.css</summary>

```css
.square {
  background-color: aqua;
  height: 200px;
  margin: 50px;
  width: 200px;

  transform: translateX(100vw);
}

.circle {
  background-color: violet;
  border-radius: 50%;
  height: 200px;
  margin: 50px;
  width: 200px;
}
```

</details>

### Step 7.

Now it's time to just have fun with it. Keep on practicing and creating :)

## Submit project

This project was just to practice using the transform property. You are not required to turn in this assignment, but I still recommend pushing it up to your github account so you can reference it in the future.
