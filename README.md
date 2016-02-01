# Parallax-scrolling-using-CSS
Parallax scrolling using CSS

Parallax scrolling is handled with Javascripts, jQuery and more, it's implemented badly with the worst offenders listening for the scroll event and modifying the DOM directly in the handler, trigger and always update DOM.

Parallax scrolling effect to use CSS, removes all these issues and allows all the browser. The result is consistent frame rates and perfectly smooth scrolling. You can also combine the effect with other CSS features such as media queries and more.

##How to use:

###Step 1: (Create CSS Classes)

####Create parallax class for parallax scrolling-

```HTML
.parallax {
width: 100%;
height: 500px;
background-color: #fff;
background-position: center center;
background-repeat: no-repeat;
background-size: cover;
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;
background-attachment: fixed;
}
```

####Create image classes for setup background image-

```HTML
.parallax-img1 {
background-image: url("images/parallax-img1.jpg");
}
.parallax-img2 {
background-image: url("images/parallax-img2.jpg");
}
```

##Step 2: (Create content and background sections)

```HTML
<section class="parallax parallax-img1">
<h1>Background image section</h1>
</section>
<section>
<h1>Content section</h1>
</section>
<section class="parallax parallax-img2">
<h1>Background image section</h1>
</section>
```

Hope this will help!!
