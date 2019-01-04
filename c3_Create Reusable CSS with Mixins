<style type='text/sass'>
  @mixin border-radius($radius){
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  -ms-border-radius: $radius;
  border-radius: $radius;
  }
  #awesome {
    width: 150px;
    height: 150px;
    background-color: green;
    @include border-radius(15px);
  }
</style>

<div id="awesome"></div>

//Sass has something called a 'mixin' which is like a function for CSS rules
//You write it using the '@mixin' declaration, with an identifier and an optional paramter, followed by the function bracket
//These are useful because new features in CSS aren't always adopted quickly and sometimes we need the vendor handle to make features work
//In cases like this, we can include every possible vendor handle for a CSS rule/feature and then place it wherever we need in the code
//This saves a LOT of retyping of these vendor handles and makes your code more readable
