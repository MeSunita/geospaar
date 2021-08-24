# Geospatial Analysis with R

This is the repository for Clark University's Geospatial Analysis with R course (GEOG 246/346). The course materials are provided as an `R` package (`geospaar`), with the course material provided in the package vignettes, and, thanks to @LLeiSong, through the [course website](https://agroimpacts.github.io/geospaar/).

Although these materials were designed for a course taught at Clark University, the two modules it provides may be useful to anyone interested in learning `R` programming and basic geospatial analysis.

This course draws from a number of other `R` courses and materials that are online (e.g. blogs, tweets, etc). We have tried to give credit to those materials wherever we draw on those. If you find that we have missed giving credit where it is due, please let us know by submitting an issue (ideally with blame assigned to the specific location) and we will remedy it.

## Installation

#### 1. Get the `devtools` package

If you have a Windows machine and don't already have Rtools installed, you will first need to download that and install it from [here](https://cran.r-project.org/bin/windows/Rtools/). Run the next lines below after that installs. (if you are on Mac or Linux, then skip `Rtools`). 

```R
install.packages("devtools")
library(devtools)
```

Add these ones as well, while you are at it:
```R  
install.packages(c("knitr", "kableExtra", "readthedown"))
```

#### 3. install the `geospaar` package

Note that the code below is a bit outdated, as the `remotes` package is the newer version for installs from remote repositories. However, the `devtools` version still works. 
```R
library(devtools)
install_github("agroimpacts/geospaar@fall2021", build_vignettes = TRUE)
```

#### 4. Browse the course materials

As package vignettes:
```R
browseVignettes("geospaar")
```

On the web:
Thanks to @LLeiSong, the materials are also available through the [course website](https://agroimpacts.github.io/geospaar/).

## For Clark students

Get a [personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) for GitHub, which is necessary for undertaking assignments (which will be on submitted on private repos).

- Go into your GitHub account, and click settings, and then (on the left)  developer settings 
- Select personal access tokens
- Generate a new token, name it something meaningful, and check the "repo" box

<p align="center">
  <img width="793" height="328" src="vignettes/fig/pat4.png">
</p>

- Copy the token and paste it somewhere safe (e.g. a secure password manager) 


