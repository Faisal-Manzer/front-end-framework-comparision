# Comparison of some popular front-end frameworks

- [Bootstrap4](#bootstrap4)
- [MDL by Google](#mdl-by-google)
- [Materialize CSS](#materialize-css)
- [Pure CSS](#pure-css)
- [jQuery Mobile](#jquery-mobile)
- [UI Kit](#ui-kit)

These frameworks are also popular but I haven't used them so I can't speak
- [Semantic UI](https://semantic-ui.com)
- [Foundation](https://foundation.zurb.com/)

## [Bootstrap4](https://getbootstrap.com)
This is the most popular framework. So u can find many articles and StackOverflow help. Also, it's documentation is awesome.  
But its JavaScript components require dependencies 1. `jQuery` 2. `Popper` which may lead to slow load and less performance grade.  
`bootstrap.bundle.js` include popper.  
It has a good grid system. if you only want the grid system u can use `bootstrap.grid.css`.  
Bootstrap reboot the CSS for u. if you only want to reboot CSS u can use `bootstrap.reboot.css`.
Bootstrap comes with a handful of components which do not lag in uses.  
But some JavaScript components are not there like parallax.  
Bootstrap gives a simple class-based code. which is good that I don't want to write more HTML or JavaScript for a simple thing.  

Bootstrap can be a perfect choice if I just want the CSS components.  
JavaScript components are fairly good but I don't like dependencies and generally, I prefer to write in pure JavaScript.  
Overall it is a good choice.

```
Bootstrap is good for CSS components.
JavaScript components are not too good and come with dependencies
```

## [MDL by Google](https://getmdl.io)
By the name, it looks like it is the best framework. But the truth is it is not it is a below average framework.  
The First thing is its class structure the name of classes are very long and often leads to the typo.  
The second is the performance grade. Its Lighthouse audit scores come very low as compared to other frameworks.  
I am not sure about the browser compatibility but some of its components use components which are only supported by Chrome. Also, some of the components require extra plugins which will then take you to load slow.  
There are some basic components missing like Select. Extra installation is needed for those components.  
Many times I have seen that the components are not enough responsive on the small screen.   
It has the good color scheme so it doesn't offer extra classes for the theme which is good because major sites go with 2 color theme.  

```
MDL is not probably the choice u should make.
Go for other framework based on Material design instead
```

## [Materialize CSS](https://materializecss.com)
This is the most interesting framework I have found.  
The best thing that it doesn't have any dependencies. Also, it has a bunch of components u may use.  
It has the best grid system I have used. Also, it's classes is easy.  
It has some bugs. Also, its CSS is very large and JavaScript too, but it has a good performance grade.  
Best thing is its mobile components they are built well.  
Some easy classes are missing.  
It's is a full pack of the thing which u can use without any custom CSS, which is missing in many frameworks u need to write some custom CSS for them but u can use materialize as it is.  
its JavaScript components are awesome and the animations too.  
Some problems are with text input.  

```
Materialize is there for u to use out of the box.
Best in my Comparison but have large files.
```

## [Pure CSS](https://purecss.io)
It is good as it gives most used component in small files.  
It provides different files for different components and a master file.  
The best part is its small package.  
Missing part is the JavaScript components. u need to write custom JavaScript if u want basic uses also.  
It grid system is little hard to understand. but it's ok.

```
Pure CSS is awesome just go for it.
But it doesn't have JavaScript components
```

## [jQuery Mobile](http://demos.jquerymobile.com/1.4.5)
It is part of jQuery team.  
Styles are awesome but u have to include JavaScript for CSS also.  
It is good but I haven't seen any version after 1.4.5. for more than a year I guess.
It Ajax Navigation & Transitions are awesome.  
Also, it is not compatible with latest jQuery which is bad.  
More or less u have to write custom CSS.  

```
jQuery Mobile is good but currently, it seems that it is not in development.
It is not compatible with latest jQuery.
Ajax Navigation & Transitions are the features for u can use it.
```

## [UI Kit](https://getuikit.com)
it is majorly based on JavaScript which is good in some aspect and bad in some.
It is the framework which contains a large number of component and with great customization.  
But it is hard to overwrite its style and often I leave it for that reason.  
Also, it is in beta stage. so we can expect improvements in future.  
Its browser support is awesome.  
Its icons are awesome.

```
UI Kit is not recommended for basic uses.
It packs almost any component u can think of.
If JavaScript is your first approach u can go
```

### These are my views and need not to be 100% correct.
