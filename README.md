## Code You Can Bank On

Hands-on workshop covering package building, automated testing, and designing code

Amelia McNamara, University of St Thomas

Onsite at the Minneapolis Federal Reserve August 10, 11, and 17, and online.

Hosted materials available at <https://ameliamn.github.io/CodeYouCanBankOn/>

## Tentative schedule:

- August 10th
  - 9-10 am [intro, review](intro.qmd)
  - 10 am - 12 pm [package dev](package-dev.qmd)
  - 12-1 pm lunch break
  - 1-4 pm [documentation](documentation.qmd)
- August 11th
  - 9 am - 12 pm [testing](testing.qmd)
- August 17th
  - 9 am - 12 pm more [testing](testing.qmd)
  - 12-1 pm lunch break
  - 1-4 pm [design](design.qmd)

## Prereqs

1.  Ensure you have R and RStudio installed. You don't need the most recent version of either. I'm currently running R version 4.4.1 "Race for Your Life" and RStudio version 2026.07.

2.  Install (or update!) the packages we're going to use. Even if you are certain you already have all these packages on your system, it's worth running install.packages() again, just to make sure you have recent versions.

```         
install.packages(c("forecast", "fredr", "imputeTS", 
                   "rlang", "roxygen2", "styler", "testthat", 
                   "tidyverse", "usethis", "vdiffr"))
```

3.  \[Optional, but recommended\] Make sure your system is prepped to build more complex packages. We're not going to get into C/C++ packages here, but it's good to have the machinery to do more in-depth stuff. You can check your system's status with the `devtools::has_devel()` function. If you don't get a positive response from that function, Jenny Bryan has instructions for getting up to speed:

- [Windows](https://stat545.com/system-prep.html#windows-system-prep)
- [Mac](https://stat545.com/system-prep.html#macos-system-prep)
- [Linux?](https://stat545.com/system-prep.html#linux-system-prep)

## Background

I am assuming you have a baseline familiarity with

- R as a language
- Writing functions
- Markdown (RMarkdown/Quarto/plain Markdown)
- git

## Catch up

I'll do a little bit of review of each of those topics, but if they are totally new to you, here is some background reading to help you get caught up.

- R as a language
  - [What is R?](https://fg2re.sellorm.com/whatisr.html)
  - [How to use R](https://learn.r-journalism.com/en/how_to_use_r/)
  - [R cookbook](https://rc2e.com/)
- Writing functions
  - [DRY](https://www.geeksforgeeks.org/software-engineering/dont-repeat-yourselfdry-in-software-development/)
  - [Functions](https://r4ds.hadley.nz/functions.html) chapter of R for Data Science
  - [What makes a good function?](https://www.youtube.com/watch?v=Qne86lxjgtg), Hadley Wickham
  - Nick Tierney's [Practical Functions, Practically Magic](https://github.com/njtierney/talk-funfun-slc)
- Markdown
  - [RMarkdown](https://r4ds.had.co.nz/r-markdown.html) (mostly deprecated at this point)
  - [Quarto](https://r4ds.hadley.nz/quarto.html)
  - [Markdown](https://daringfireball.net/projects/markdown/syntax)
- [git](https://happygitwithr.com/big-picture)

All material is covered by a CC-BY-SA-4.0 license.

The material here is in turn based on other CC-BY products, primarily [Building tidy tools workshop](https://github.com/rstudio-conf-2022/build-tidy-tools), [uncoast::unconf day zero workshop](https://github.com/uncoast-unconf/uu-2019-day-zero), and [R packages book](https://r-pkgs.org/).
