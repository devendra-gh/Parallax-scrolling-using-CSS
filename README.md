# Parallax-scrolling-using-CSS
Parallax scrolling using CSS

Parallax is a scrolling technique used in background images move slowly with content and background images. It is handled with Javascript, jQuery and more but it’s implemented badly with browsers and when scroll event is modifying, trigger and updates the DOM.

So here, I’m using by CSS and it’s also compatible all browser and devices. Using css parallax make scrolling perfect and smooth with background images. You can also combine the effect with other CSS features such as media queries and more.

To create parallax, there are using CSS element “background-attachment : fixed“. The role of these element to fixed background images in body and shows only that particular section.

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
