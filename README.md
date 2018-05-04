# Comparison of some popular frontend frameworks

- [Bootstrap4](#bootstrap4)
- [MDL by Google](#mdl-by-google)
- [Materialize CSS](#materialize-css)
- [Pure CSS](#pure-css)
- [jQuery Mobile](#jquery-mobile)
- [UI Kit](#ui-kit)

These frameworks are also popular but i haven't used them so i can't speak
- [Semantic UI](https://semantic-ui.com)
- [Foundation](https://foundation.zurb.com/)

## [Bootstrap4](https://getbootstrap.com)
This is the most popular framework. So u can find many articles and stackoverflow help. Also it's documentation is awesome.  
But its JavaScript components require dependencies 1. `jQuery` 2. `Popper` which may lead to slow load and less performance grade.  
`bootstrap.bundle.js` include popper.  
It have a good grid system. if you only want the grid system u can use `bootstrap.grid.css`.  
Bootstrap reboot the css for u. if you only want to reboot css u can use `bootstrap.reboot.css`.
Bootstrap comes with handful of components which do not lag in uses.  
But some JavaScript components are not there like parallax.  
Bootstrap gives a simple class based code. which is good that I don't want to write more HTMl or JavaScript for a simple thing.  

Bootstrap can be a perfect choice if i just want the CSS components.  
JavaScript components are fairly good but i don't like dependencies and generally I prefer to write in pure JavaScript.  
Overall it is good choice.

```
Bootstrap is good for CSS components.
JavaScript components are not too good and comes with dependencies
```

## [MDL by Google](https://getmdl.io)
By the name it look like it is the best framework. But the truth is it is not it is a below average framework.  
The First thing is its class structure the name  of classes are very long and often leads to typo.  
The second is the performance grade. Its Lighthouse audit scores comes to very low as compared to other framework.  
I am not sure about the browser compatibility but some of its components uses components which is only supported by Chrome. Also some of the component require extra plugins which will then take you to load slow.  
There are some basic components missing like Select. Extra installation is needed for those component.  
Many times i have seen that the components are not enough responsive on small screen.   
It have good colour scheme so it don't offers extra classes for theme which is good because major sites goes with 2 colour theme.  

```
MDL is not probably the choice u should make.
Go for other framework based on Material design instead
```

## [Materialize CSS](https://materializecss.com)
This is the most interesting framework i have found.  
Best thing that it don't have any dependencies. Also it have bunch of component u may use.  
It have the best grid system i have used. Also it's classes is easy.  
It have some bugs. Also its CSS is very large and JavaScript too, but it have a good performance grade.  
Best thing is its mobile components they are build well.  
Some easy classes are missing.  
It's is full pack of the thing which u can use without any custom CSS, which is missing in many framework u need to write some custom css for them but u can use materialize as it is.  
its JavaScript components are awesome and the animations too.  
Some problems are with text input.  

```
Materialize is there for u to use out of box.
Best in my Comparison but have large files.
```

## [Pure CSS](https://purecss.io)
It is good as it gives most used component in small files.  
It provides different files for different components and a master file.  
Best part is it's small package.  
Missing part is the JavaScript components. u need to write custom JavaScript if u want basic uses also.  
It grid system is little hard to understand. but it's ok.

```
Pure CSS is awesome just go for it.
But it don't have JavaScript components
```

## [jQuery Mobile](http://demos.jquerymobile.com/1.4.5)
It is part of jQuery team.  
Styles are awesome but u have to include JavaScript for css also.  
It is good but i haven't seen any version after 1.4.5. for more than a year i guess.
It Ajax Navigation & Transitions are awesome.  
Also its is not compatible with latest jQuery which is bad.  
More or less u have to write custom css.  

```
jQuery Mobile is good but currently it seems that it is not in development.
It is not compatible with latest jQuery.
Ajax Navigation & Transitions are the feature for u can use it.
```

## [UI Kit](https://getuikit.com)
it is majorly based on JavaScript which is good in some aspect and bad in some.
It is the framework which contains a large number of component and with great customisation.  
But it is hard to to overwrite its style and often i leave it for that reason.  
Also it is in beta stage. so we can expect improvements in future.  
Its browser support is awesome.  
Its icons are awesome.

```
UI Kit is not recommended for basic uses.
It packs almost any component u can think of.
If JavaScript is your first approach u can go
```

### these are my views. it need not to be 100% correct
