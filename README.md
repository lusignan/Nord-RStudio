# Nord-RStudio
An arctic, north-bluish clean and elegant RStudio theme.

This theme is an unofficial port of [Arctic Ice Studio's](https://github.com/arcticicestudio/nord) [Nord theme](https://www.nordtheme.com) for RStudio. The font is Microsoft's [Cascadia Code](https://github.com/microsoft/cascadia-code).

![Preview](https://github.com/lusignan/Nord-RStudio/blob/master/Preview%20Nord%20RStudio.png?raw=true)

![Menu](https://github.com/lusignan/Nord-RStudio/blob/master/Menu.png?raw=true)


# Compatability
This theme is compatible with RStudio 1.2. I've uploaded a version with the conflicts from RStudio 1.3 fixed but some of the buttons have a white border/shadow that I haven't solved yet.

# Installation
To install, run the following in your RStudio console:
```
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/nord-rstudio/master/Nord.rstheme", apply=TRUE, force=TRUE)
```

If the above command fails, first run:
```
install.packages("rstudioapi")
```
