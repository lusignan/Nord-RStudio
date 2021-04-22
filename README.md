# Nord-RStudio
An arctic, north-bluish clean and elegant RStudio theme.

This theme is an unofficial port of [Arctic Ice Studio](https://github.com/arcticicestudio/nord)'s [Nord theme](https://www.nordtheme.com) for RStudio.
<figure>
    <img src="https://github.com/lusignan/Nord-RStudio/blob/master/nord-rstudio-preview.png"
         alt="Nord">    
</figure>

# Installation
To install, download the folder, unzip, and open RStudio. From RStudio click Preferences, Appearance, Add, and then navigate to the rstheme for the theme that you'd like to install. Click apply.

If you're comfortable installing from the console and have [Devtools](https://github.com/r-lib/devtools) installed then you can copy and run the following in your console:
```
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/nord-rstudio/master/Nord.rstheme", apply=TRUE, force=TRUE)
```
## Acknowledgements
* Theme by [Sven Greb](https://github.com/svengreb)
* RStudio port was largely built using [Garrick Aden-Buie](https://github.com/gadenbuie)'s [rsthemes package](https://github.com/gadenbuie/rsthemes)
* Sample code comes from [R for Data Science](https://r4ds.had.co.nz/)
