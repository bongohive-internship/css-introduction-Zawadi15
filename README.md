# **Introduction to css**

# prerequisites

- ## Not giving up easily

- ## Basic understanding of HTML

- ## GitHub and git

### Before we start

## Wait what's is CSS

### Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

### Because of the heading we will only be covering CSS

## Download and Install

### In order to make changes in the following files, you need a code editor. Pick any from the list below

### Atom
https://atom.io/

### Vscode
https://code.visualstudio.com/download

### Sublime Text 3
https://www.sublimetext.com/3

#### Why do I need a code editor

Editors have built-in knowledge of the programming languages and processes commonly used by programmers, which is intended to increase the productivity of the programmers.

##  After the installation of the above.

### We can start making changes on the following files and see your CSS and HTML page come to life

### Keep in mind the HTML, CSS will keep changing as you keep progressing For each lesson As we will cover different topics.

```

index.html
/css/main.css
/images/

```
### Code challenge 1

Open your 

```
index.html
```
### Adding the following text in-between the 

```
<body>   </body>
```

```


<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper.</p> 

<p class="medium ">Aenean ultricies mi vitae est. 
Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. 
Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi. Aenean fermentum, 
elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. </p>
    
<p class="large">Donec non enim in turpis pulvinar facilisis. Ut felis.
Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, 
eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi,
tincidunt quis, accumsan porttitor, facilisis luctus, metus</p>

```
## Save changes and open your index.html file in the browser


### nicely done time to effect change with CSS 
 
## HTML/CSS linking
### notice how your page shows up as just plan text!! This means your CSS in not linked to your HTML


# Linking HTML/CSS 
#### We know we have a folder and a file called main.css that HTML needs to know about  


### This can easily be achieved through the use of the HTML link element, but it can be hard to get your head around at first. In the header section, add in:

```
<head>

<link rel="stylesheet" type="css/main.css">.

</head>

```
### refresh your page and your background should be blue


## Classes
 Classes are reusable styles that can be added to HTML elements. I took the liberty of adding in  

``` <p class="medium ">
 and 
  <p class="large ">
```
In your css add in
 
 ```
 .medium {
  width: 600px;
  margin: 0 auto;
  font-family: "Helvetica Neue", "Arial", sans-serif;
  font-style: italic;
  font-weight: 100;
  font-variant-ligatures: normal;
  font-size: 2rem;
  letter-spacing: 1px;

 }
 
 .large {
 text-align: center;
 font-size: 300%;    
 }
 
 ```
 ### Just from these few lines lives are changed feel free to add back ground colors and more.

# conclusion

### You are now able to link files and make reference to them. 

## Next class



# resources

### - https://www.freecodecamp.org/

### - https://www.w3schools.com/whatis/whatis_css.asp

### - https://www.w3schools.com/css/css_howto.asp

### - https://www.w3schools.com/cssref/sel_class.asp
