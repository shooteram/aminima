# Aminima

A personal CSS library made using Stylus as its preprocessor

## Description

This library is made to be easily configured from CSS variables.  
It ships with a clear theme but, if you'd want a darker one, you could easily define the colors to your taste:

```css
:root {
  --background-color: black;
  --default-color: white;
  --primary-color: chartreuse;
  --info-color: aqua;
  --danger-color: crimson;
}
```

Just don't forget to append an `!important` at the end of each variables since they're already defined.  
All of the variables can be found inside [this object](https://github.com/shooteram/aminima/blob/master/src/variables.styl#L1).

# Demo

<p align="center">
  <img src="https://i.imgur.com/RMkZ5Xc.png" alt="demo"/>
</p>
