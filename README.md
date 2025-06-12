We chose the theme name based on our group name WebWizards, so we called the theme (Theme By Wizards).

The theme is a basic CSS framework. It has a built-in customization for headings, lists, buttons, forms, inputs, and tables. Also, it includes utility classes to style the website as you like. 



For installation:
1. Make sure you copy the repository: 
git clone https://github.com/Manz977/CustomCSSFramework.git

2. Compile SCSS: 
sass --watch src/main.scss css/themebywizards.css


## Usage instructions 

## Customization for text:

## To customize the text colour use those classes when you are applying it to a text in the html code: 

for example 

<!-- <h1 class="text-danger"> test</h1> --> will output text with the color dark pink

you can also use: 
text-primary
text-secondary 
text-danger 
text-success
text-info
text-dark
text-light


## To customize font weight:

for example 
<!-- <h2 class="fw-800">Test</h2> -->

you can also change the value from 200 all the way to 900 which is the darkest weight:  
fw-200
fw-300
fw-400
fw-500
fw-600
fw-700
fw-800
fw-900


## TO customize the font Size 

for example 
<!-- <h2 class="fs-1">Test</h2> -->

you can also change the value from 1 to 5 for a larger text size

fs-1
fs-2
fs-3
fs-4
fs-5


## To apply Margin 

for example 
<!-- <h2 class="mt-lg">Test</h2> --> this will apply margin-top of size 25px

Here is step by step instructions on how to use margins using our CSS frameworks

The avalible size are 

xs = extra small
sm = small
md = medium
lg = large 
xl = extra large

use the sizes with margins 

m-size = margin top, right, bottom, left
mt-size = margin top
mr-size = margin right
mb-size = margin bottom 
ml-size = margin left 
mx-size = margin left and right
my-size = margin top and bottom 


## To apply Padding 

for example 
<!-- <h2 class="pt-lg">Test</h2> --> this will apply padding-top of size 25px

Here is step by step instructions on how to use padding using our CSS frameworks

The avalible size are 

xs = extra small
sm = small
md = medium
lg = large 
xl = extra large

use the sizes with margins 

p-size = padding top, right, bottom, left
pt-size = padding top
pr-size = padding right
pb-size = padding bottom
pl-size = padding left 
px-size = padding left and right
py-size = padding top and bottom 



## To apply Border Radius 

For example 

<!-- <button class="rounded-sm">Press Me</button> -->

Here is step by step instructions on how to use border radius 

The avalible size are 

sm = small
md = medium
lg = large 
full = Full(%50)

use the sizes with border radius

rounded-size

## To apply Border width 

For example 

<!-- <button class="border-width-sm">Press Me</button> -->

Here is step by step instructions on how to use border width 

The avalible size are 

sm = small
md = medium
lg = large 


use the sizes with border radius

border-width-size 



## To use custom theme for Headings

To apply default theme to headings use those classes. 

<!-- <h1 class="h1"></h1> -->

You can also use those classes as well

h1,h2,h3,h4,h5,h6 to apply the default styling


## To use custom them for buttons

<!-- <button class="btn-primary">Primary</button> -->

You can also use those classes as well

btn-primary
btn-secondary
btn-danger
btn-success
btn-info

## To use custom alert messages 

<!-- <p class="alert-success">Your Email has been Successfully Sent</p> -->

You can also use those classes as well

Use .alert class to create an default alert
Use .alert-danger class to create an danger alert
Use .alert-success class to create an success alert



## To use custom theme for forms and inputs

<!-- <form class="form"></form> -->

Use .form class to create a default form



## To use custom theme for Tables

<!-- <table class="table"></table> -->

Use .form class to create a default form
