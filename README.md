#  CSS3 Button Hover Effects
Pure CSS3 button hover effects with FontAwesome

## Demo
[Check Demo Here](http://codepen.io/fox_hover/pen/bqZxLa)

## How to use:

1. Create a link with `<a></a>` tag. Add to it class 'effect' and special effect class, like 'effect-1' or 'effect-4', depends on the number of picked effect.

```html
<a class="effect effect-1" href="#" title="Learn More">Learn More</a>
```

2. You need to add link to FontAwesome to your `<head></head>` tag. You can find [here](http://fontawesome.io/get-started/) more about putting FontAwesome on your website.

```html
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css">
</head>
```

3.  Then you need to work with CSS file (or with SCSS file if you want to). In both ways you need to add styles.css to your html file, in the `<head></head>` tag after FontAwesome:

```html
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css">
  <link rel="stylesheet" href="css/styles.css" />
</head>
```

4. Then in both ways you need:

- open file (CSS or SCSS) and delete all the content between **common styles !!!YOU DON'T NEED THEM** comment and **button styles !!!YOU NEED THEM** comment. All these styles were created to make codepen demo more beautiful, if you keep these styles they can make mess in your website appearance.  

- in common effect styles uncomment line with `background-color`, remove my text and add your own background-color. 

- also add your own `font-family` and remove my comment.

```scss
.effect {
  text-align: center;
  display: inline-block;
  position: relative;
  text-decoration: none;
  color: $link-text-color;
  text-transform: capitalize;
  /* background-color: - add your own background-color */
  font: {
    family: 'Roboto', sans-serif; /* put your font-family */
    size: 18px;
  }
  padding: 20px 0px;
  width: 150px;
  border-radius: $border-radius;
  overflow: hidden;
}
```

Now it's ready and you have a button with hover effect on your page =)
