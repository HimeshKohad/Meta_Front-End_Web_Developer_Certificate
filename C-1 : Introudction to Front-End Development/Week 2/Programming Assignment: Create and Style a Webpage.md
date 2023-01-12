### ***Programming Assignment: Create and Style a Webpage***

<hr>

_Solutions:_

***HTML File***

```html

<!DOCTYPE html>
<html lang = "en">

<head>
    <meta charset = "utf-8">
    <meta http-equiv = "X-UA-Compatible" content = "IE=edge">
    <meta name = "viewport" content = "width = device-width, initial-scale = 1.0">
    <title>Himesh</title>
    <link rel = "stylesheet" href = styles.css>
</head>

<body>
    <div>
        <h1>Himesh Kohad</h1>
    </div>
    <div>
        <img src = "photo.jpg" alt = "random image" id = "photo">
    </div>
    <div>
        <h2 id = "Artists">Favorite Music Artists</h2>
        <ul>
            <li>Drake</li>
            <li>Chainsmokers</li>
            <li>One Direction</li>
            <li>Maroon 5</li>
            <li>Dua Lipa</li>
        </ul>
    </div>
    <div>
        <h2 id = "films">Favorite Films</h2>
        <ol>
            <li>Now You See Me</li>
            <li>Escape Room</li>
            <li>Shutter Island</li>
            <li>The Conjuring</li>
            <li>The Blind Side</li>
        </ol>
    </div>
    <div>
        <a href = "https://www.meta.com/">My Profile</a>
    </div>
</body>

</html>

```

<br>

***CSS File***

```css

h1 {
    color: blue;
}

h2 {
    color: gray;
}

div {
    margin : 4px;
}

#photo {
    border: 2px blue solid;
}

```
