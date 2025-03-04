# Math 201 Course Material

Welcome to the GitHub repository for Math 201 Elementary Statistics. It contains lecture material (either quarto files or jupyter notebooks).
Additionally, it contains the files necessary for the course. This is an R-based statistics course.


## R Packages

### `csucistats`

The course uses the R package `csucistats`, which contains custom functions designed to better teach statistics with R. You can look at the R package's [website](https://www.inqs.info/csucistats/) for more information. You can install the R package with the following code:

```r
install.packages('csucistats', 
                 repos = c('https://inqs909.r-universe.dev', 
                           'https://cloud.r-project.org'))
```

### `ggplot2`

The course uses `ggplot2` for creating plots. You can learn more information about `ggplot2` from its [website](https://ggplot2.tidyverse.org/).

```r
install.packages("tidyverse")
```

Use the following code to install visualization packages:

```r
csucistats::install_plots()
csucistats::install_themes()
```


### Other Packages

The course materials lightly uses [tidyverse](https://www.tidyverse.org/) packages for a few data manipulation techniques. Other packages used are [coursekata](https://github.com/coursekata/coursekata-r), [openintro](https://github.com/OpenIntroStat/openintro), [dsbox](https://github.com/tidyverse/dsbox), [palmerpenguins](https://allisonhorst.github.io/palmerpenguins/), [DT](https://rstudio.github.io/DT/), [taylor](https://taylor.wjakethompson.com/), and [patchwork](https://patchwork.data-imaginist.com/articles/patchwork.html).

## Navigation

The main folders that have course material are `lectures`, `notebooks` and `hw`. The `lectures` folder contains quarto files used to generate lectures. THe `hw` and `notebooks` folders contains jupyter notebooks used in class. 