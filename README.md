# DIT Coder Dojo Web Development

## Week2
What we will cover this week:
1. Css Design
2. Image resizing

## Starting with CSS
insert the following line of code at the top of your html file
```html
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
```
What does this mean?
The ```<head>``` tag is the settings of your page. By adding the style tag inside the head you are setting up how you want the web page to look! 

### Understanding CSS
everytome you write CSS you tell it exactly what you want to design. For example:
```css
h1   {color: blue;}
```
This tells html that where-ever it sees the ```<h1>``` tag, colour the text blue!

Lets try changing the text font aswell!
to do this we use ```font-family: verdana;``` in our css. This will change the font to verdana
For example:
```css
p {
    font-family: verdana;
    font-size: 20px;
}
```
Font-size will also change the size of text. you will see px beside a number, this stands for pixels which is how CSS understands how much you want something to grow or shrink by.

Some excercise to do:
1. Change your h1 text color to blue
2. Change your ```<p>``` text colour to black
3. Change the font of your h1 to anything you want. Here is a link of some fonts to try out: https://websitesetup.org/web-safe-fonts-html-css/

Next we will look into how to change the size of an image.
This again will use CSS and and img tag
for example
```css
img{
    width:100px; /* you can use % */
    height: auto;
}
```
This will re-size your image to 100 pixels. For this you can also use percentage %. For example width: 50% which means scale the image by half!.

Try messing around with this.
If you are stuck, call over a mentor to help you out :)

#### Challenge!
If you have time left, from what you have learned today, add some design to your website you made last week!


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
