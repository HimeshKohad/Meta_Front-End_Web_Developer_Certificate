### ***Programming Assignment: Styling a Page***

<hr>

_Solutions:_

***HTML File***

```html

<!DOCTYPE html>
<html>
<head>
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>
        <img src="logo.png" id="logo">
    </div>
    <div class="center-text">
        <h1>Our Menu</h1>
        <h2>Falafel <span>NEW</span></h2>
        <p>Chickpea, herbs, spices.</p>
        <h2>Pasta Salad</h2>
        <p>Pasta, vegetables, mozzarella.</p>
        <h2>Fried Calamari</h2>
        <p>Squid, buttermilk.</p>
    </div>
    <div class="center-text">
        <p id="copyright">
            Copyright Little Lemon
        </p>
    </div>
</body>
</html>

```

<br>

***CSS File***

```css

body {
    background-color: #e0e0e2;
}

h1 {
    color: #721817;
}

h2 {
    color: #721817;
}

h2 > span {
    color: #FA9F42;
    font-size: 0.75em;
}

.center-text {
    text-align: center;
}

#logo {
    margin-left: auto;
    margin-right: auto;
    display: block;
}

#copyright {
    font-size: 0.75em;
    padding-top: 12px;
}

```
