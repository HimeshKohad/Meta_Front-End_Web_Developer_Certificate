### ***Improve your Bio page with Bootstrap***
***Solution:***

<hr>

***index.html***

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Bio Page</title>
    <link href="bootstrap.min.css" rel="stylesheet" />
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div id="bio" class="col-12 col-lg-6 text-center">
          <h1>Joan</h1>
          <img src="photo.jpg" class="img-fluid" />
        </div>
        <div id="more" class="col-12 col-lg-6">
          <h2>Favorite Music Artists</h2>
          <ul>
            <li>Imagine Dragons</li>
            <li>Twenty One Pilots</li>
            <li>OneRepublic</li>
            <li>Coldplay</li>
            <li>Linkin Park</li>
          </ul>
          <h2>Favorite Films</h2>
          <ol>
            <li>Saw</li>
            <li>Jigsaw</li>
            <li>The Conjuring</li>
            <li>Annabelle</li>
            <li>The Nun</li>
          </ol>
          <a
            href="https://www.facebook.com/joanskenderi"
            class="btn btn-primary"
            >My Meta Profile</a
          >
        </div>
      </div>
    </div>
    <script src="bootstrap.bundle.min.js"></script>
  </body>
</html>
```
