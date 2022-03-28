---
title: Schedule
toc: true
---



## Course Books
Each of the below links to the full book. Icons in the schedule link to specific chapters.

{{< course-books >}}


 ## Week 1 
 {{< schedule >}}

{{< week-odd "03-28" >}}
  {{< description "Introduction & data tyes" "Weekly schedule of topics and an overview of the course requirements. We will discuss the four basic data types in depth and how coercion occurs. We will also discuss attributes, introduce lists, and discuss subsetting for lists versus atomic vectors." >}}
  {{< wrap >}}
{{< slides "w1" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "assignments/#final-project" "Final" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< readings "adv-r" "fp.html" "" >}}
{{< readings "adv-r" "vectors-chap.html" "3" >}}
{{< readings "adv-r" "control-flow.html#loops" "5.3" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
 ## Week 2 
 {{< schedule >}}

{{< week-even "04-04" >}}
  {{< description "Intro to iterations & Lab 1" "This lecture will focus on base R methods for looping, specifically with `for` loops and the `*apply` family of loops. Our first lab will ask you to extract elements from deeply nested lists while also using base R loops to conduct basic operations." >}}
  {{< wrap >}}
{{< slides "w2" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "lab-1" "Lab 1" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< readings "adv-r" "functionals.html" "9.1-9.3" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-even >}}

{{< /schedule >}}
 ## Week 3 
 {{< schedule >}}

{{< week-odd "04-11" >}}
  {{< description "Iterations 2 & Lab 2" "Our second lecture on iteration will introduce [**{purrr}**](https://purrr.tidyverse.org) and contrast these functions with the base R versions. The concept of functional programming will also be discussed more explicitly. The second lab will get us using [**{purrr}**](https://purrr.tidyverse.org) in an applied way. We'll fit multiple models, iterate through nested lists, and make some real-world API calls." >}}
  {{< wrap >}}
{{< slides "w3" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "lab-2" "Lab 2" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< due "lab-1" "Lab 1" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "r4ds" "many-models.html" "25" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
 ## Week 4 
 {{< schedule >}}

{{< week-even "04-18" >}}
  {{< description "Batch load data & list columns" "We will introduce `purrr::map_df()` and discuss how it can be used for batch loading data in combination with some functions from the [**{fs}**](https://fs.r-lib.org) package. This will include parsing data (as columns) from the file names. The concept of list columns will be introduced and contrasted with `base::split()`. By the end of this lecture you should be able to fluently nest and unnest data frames and understand why this is such a powerful framework. The last 20 minutes will be devoted to an \\"in-class\\" quiz." >}}
  {{< wrap >}}
{{< slides "w4" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "take-home-midterm" "Midterm" >}}
{{< assigned "assignments/#quiz" "Quiz" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< due "lab-2" "Lab 2" >}}
{{< due "assignments/#outline" "Outline" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "other" "https://www.tidyverse.org/articles/2018/01/fs-1.0.0/" "1" >}}
{{< readings "adv-r" "functionals.html" "9.4-9.6" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-even >}}

{{< /schedule >}}
 ## Week 5 
 {{< schedule >}}

{{< week-odd "04-25" >}}
  {{< description "Parallel iterations & looping variants" "We will introduce parallel iterations (`purrr::map2()` and `purrr::pmap()`) and apply them within the context of list columns. We'll discuss the differences betweeen`purrr::map()` and `purrr::modify()` while introducing new functions, including `purrr::safely()`, and `purrr::walk()`. We will also discuss different types of loops, focusing mostly on `purrr::reduce()` (and noting the similarities with `base::Reduce()`)." >}}
  {{< wrap >}}
{{< slides "w5" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< readings "NA" "NA" "NA" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
 ## Week 6 
 {{< schedule >}}

{{< week-even "05-02" >}}
  {{< description "**REMOTE ONLY** Writing functions 1 & 2" "The first part of this lecture will focus on the very basics of functions - understanding that everything in R is a function, the components of a function, when to write a function, and how to go about it (e.g., development and informal testing). We will then extend this discussion toward making the internals of a function more complicated, while still keeping functions as simple as possible. Functions within functions!" >}}
  {{< wrap >}}
{{< slides "w6" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< due "take-home-midterm" "Midterm" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "other" "https://swcarpentry.github.io/r-novice-inflammation/02-func-R/" "" >}}
{{< readings "adv-r" "functions.html" "6.1-6.4" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-even >}}

{{< /schedule >}}
 ## Week 7 
 {{< schedule >}}

{{< week-odd "05-09" >}}
  {{< description "Writing functions 3 & Lab 3" "Our final lecture on functions, we will discuss what makes a function \\"good\\" and what makes them fragile. In this spirit, we will create many small functions that build toward a single function. Additionally, we will discuss the concept of **non-standard evaluation**, which is used prevalently throughout the tidyverse and can make programming with the tidyverse a bit more difficult. We will also have our final lab for the class, which will ask you to create and apply functions." >}}
  {{< wrap >}}
{{< slides "" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "lab-3" "Lab 3" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< readings "adv-r" "functions.html" "6.5-6.8" >}}
{{< readings "other" "https://shiny.rstudio.com/articles/basics.html" "6.5-6.8" >}}
{{< readings "other" "https://shiny.rstudio.com/articles/build.html" "6.5-6.8" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
 ## Week 8 
 {{< schedule >}}

{{< week-even "05-16" >}}
  {{< description "Shiny 1 & 2" "We will start by introducing the very basics of shiny - the user interface (UI) and the server. We will work together to create a basic shiny application, modifying the default template to use ggplot2. Shiny dashboards and different layout options will also be discussed." >}}
  {{< wrap >}}
{{< slides "" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< assigned "assignments/#peer-review" "PR" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< due "lab-3" "Lab 3" >}}
{{< due "assignments/#draft" "Draft" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "shiny" "basic-app.html" "1" >}}
{{< readings "shiny" "basic-reactivity.html" "3" >}}
{{< readings "shiny" "action-workflow.html" "5" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-even >}}

{{< /schedule >}}
 ## Week 9 
 {{< schedule >}}

{{< week-odd "05-23" >}}
  {{< description "Shiny 3 & review" "Our final lecture on shiny will focus on workflows and organization. We will discuss writing functions to help with organization. Additionally, shiny applications are somewhat notorious for being slow. If time allows, we will also discuss methods to profile your code and identify bottlenecks. This is a built-in day for review and to make sure we have covered the primary topics of shiny. We will also review the basics of functions. Students will be allowed to request topics for review before class." >}}
  {{< wrap >}}
{{< slides "" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< due "assignments/#peer-review" "PR" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "shiny" "best-practices.html" "17" >}}
{{< readings "other" "https://r-pkgs.org/whole-game.html" "2" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
 ## Week 10 
 {{< schedule >}}

{{< week-even "05-30" >}}
  {{< description "Memorial day" "No class - if you feel so inclined, you can watch last year's lecture introducing package development" >}}
  {{< wrap >}}
{{< slides "" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< readings "NA" "NA" "NA" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "https://youtu.be/85kQBw7um50" >}}
{{< /wrap >}}
{{< /week-even >}}

{{< /schedule >}}
 ## Week 11 
 {{< schedule >}}

{{< week-odd "06-06" >}}
  {{< description "Finals Week" "Your final project is due before midnight." >}}
  {{< wrap >}}
{{< slides "" >}}
{{< /wrap >}}
  {{< wrap >}}

{{< /wrap >}}
  {{< wrap >}}
{{< due "assignments/#final-project" "Product" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< readings "NA" "NA" "NA" >}}
{{< /wrap >}}
  {{< wrap >}}
{{< lecture "" >}}
{{< /wrap >}}
{{< /week-odd >}}

{{< /schedule >}}
