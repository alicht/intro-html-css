# Objectives 
-  Github
-  HTML
-  CSS
-  about.me page

## 1. GitHub

### Why Git?
Git is a form of Version Control. 
Version Control is the process of storing multiple versions of a single project, allowing each version to be recalled at a later date. (Ex: backing up your iPhone before you get it repaired).

As developers our code is our livelihood so it's important
that we safely and frequently store our work.  Not only that, we want to track our
changes as we make them.  If we make a feature that ends up breaking the rest of
our app we want to be able to go back to a point when our app was last working.

### But... who cares why would we need this?
Using version control is useful because we can easily rollback to a previous version of our application, saving us a ton of extra work and time.
There are a lot of advantages to version control. 
-  it's a great way to keep a backup of your work
-  it facilitates collaboration
-  it gives us the freedom to experiment and try new things without messing up the code base.

#### let's make a local repository and create the files we'll be using for today

### connecting to Github

## Introducing GitHub!

So we have a local repository, but now let's use GitHub to create our remote repository. Why use
GitHub? So we can backup our code online. It also has an stellar graphical interface and useful collaboration features.

If you work by yourself, you don't really need remotes. However, we want to work with others! Thus let's talk about remotes.


## Let's create a remote repository on GitHub

-  let's go to GitHub, click the BIG plus sign in the menubar and select New repository. 
-  let's enter a name for our repository in the repository name field. We'll enter the same name we did for our local version `mean-girls` 


## Lets connect our local repo and our remote repo

![mg1](https://user-images.githubusercontent.com/6153182/33035113-09f033dc-cdf8-11e7-8f7a-24fda5b84a2c.png)

-  since we already have a repo we'll follow step 2
-  go to terminal 
-  lets add the URL we copied to 
-  `git remote add`
-  `git remote push`

### Connected!

 
## 2. HTML 
used for inputting and arranging all the visible contetn on a website. 

-  building blocks of HTML are elements
-  <tag-name>content</tag-name>
-  tags can create headings, paragraphs, links
-  HTML5 just means the most up to date features of HTMl that incorporates new properties such as ________
-  < h1> to < h6> tags

### lets create an index.html file

here's the boilerplate HTML code we'll want to enter in our HTML file:

```html
<!DOCTYPE html>
<html>
  
  <head>
    <link rel="stylesheet" type="css" href="style.css" />
    <title>Title Goes Here</title>
  </head>
  
  <body>
  
  </body>
  
</html>
```
## Add some content and then open in browser

## let's add a couple of hyperlinks
-  I love `<a href="espn.com"> sports </a>`.

Anchor Elements create links. In order to make a working link, we need to add more information to the anchor tag using an (href) attribute that detemines the link's destination.

```<a href="http://www.generalassemb.ly"> This would make this whole sentence a link to General Assembly's home page.</a>```

### Semantic elements in HTML
https://www.w3schools.com/html/html5_semantic_elements.asp

## 3. CSS 

![screen shot 2017-12-06 at 12 33 04 am](https://user-images.githubusercontent.com/6153182/33646360-12a6dcca-da1d-11e7-9301-c05fa9afbebe.png)

what would this do to our HTML code on our page?
```css
h1 {
  color: blue;
  background-color-yellow;
}
```

### Box Model 

[much more intricate CSS](http://www.mezzoblue.com/zengarden/alldesigns/)

http://www.mezzoblue.com/zengarden/alldesigns/

-  can select hex colors to color image
-  

## fonts and text
-  can use these too

## classes and IDs
What's the difference between the two? In short, using classes allows you to select and style groups of elements with a particular style, while using an ID only allows for an individual element to be styled. Using classes and IDs allows you to have flexibility in how you control the design of individual elements and groups of elements on the page.

In the CSS, a class selector is a name preceded by a full stop (“.”) and an ID selector is a name preceded by a hash character (“#”). The difference between an ID and a class is that an ID can be used to identify one element, whereas a class can be used to identify more than one.

![screen shot 2017-12-06 at 12 42 14 am](https://user-images.githubusercontent.com/6153182/33646592-599a2636-da1e-11e7-8f7b-71edb8f27436.png)

## images
<!img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">


## Elk Web Design 
[let's take a look at this JSbin sample of HTML & CSS](http://jsbin.com/cojeke/embed?html,css,output)

### What is Responsive Web Design?
Responsive web design makes your web page look good on all devices.

Responsive web design uses only HTML and CSS.

### Setting The Viewport

HTML5 introduced a method to let web designers take control over the viewport, through the <meta> tag.

You should include the following <meta> viewport element in all your web pages:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
A <meta> viewport element gives the browser instructions on how to control the page's dimensions and scaling.

The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

![screen shot 2017-12-06 at 7 09 55 am](https://user-images.githubusercontent.com/6153182/33661134-894efd80-da54-11e7-8be7-1890faf5c142.png)

[here's an example of what it would look like in action](https://www.w3schools.com/css/example_withviewport.htm)


### Media Query

[excellent explanation of media queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)


## 4. About Me Page

see attached code







