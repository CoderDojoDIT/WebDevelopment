# DIT Coder Dojo Web Development

## Week 1
What we will cover this week:

1. Html Tags
2. Css Design
3. Making our First website!

### Html tags
1. To add a big heading use the h tag with the number of size. For example
```html
<h1>I am a big text! </h1>
```

2. To write a paragraph use the p tag
```html
<p> I am a paragraph </p>
```

3. To add a space use the br tag
```html
<br>
```

4. To add a link to another page use the a tag
for example 
a href="secondPage.html"
make sure to add something in the middle to be able to click the link!
for example 
```html
<a href="secondPage.html"> Click me!</a>
```

5. To add an image to your website, go to google images, find a picture you want.
Right click on the picture and click on the 'copy image address' option.
then paste the text you copied into the source option just like below.
To paste, right click on the screen and seect the paste option! :) 

For example
```html
<img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&h=350" alt="">
```

6. To add a list to your website use the ul tag (which means unordered list) and the li tag inside (which means list)

for example
```html
    <ul>
      <li>I am object1</li>
      <li>I am object2</li>
      <li>I am object3</li>
    </ul>
```

7. To add a button and a tex field (to write)
 use the form tag, the input tag and the button tag.

 for example 
 ```html
    <form>
      <input type="text" name="" value="">
      <button type="button" name="button">I am a button</button>
    </form>
 ```

 ## Challenge on HTML
 Make a website about yourself!
 1. Add a big text with your name on the website.
 1. Write a small paragraph about you. 
 1. Add a list of your favourite things to do.
 1. Add two images your favourite animal.

### CSS
CSS stands for Cascading style sheets. Sounds like a scary name but it is used to make your website cool by adding colours and deseigns. We will go through some designs that you may want to add to your website!

The quick way of adding style is to use the style keyword
for example, to change your text to a different colour
(note colour in CSS is spelled in the American way- color)
```html
<h1 style="color:blue;">This is a Blue Heading</h1>
```

Or you can add a style tag inside the head tag you have for the html
for example:
```html
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
```
