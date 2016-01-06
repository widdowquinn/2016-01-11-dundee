# 2016-01-12 SWC workshop: `R`

----

Please use the EtherPad to take communal notes:

[http://pad.software-carpentry.org/2016-01-11-dundee](http://pad.software-carpentry.org/2016-01-11-dundee)

---

## `R for reproducible scientific analysis`

----

### Learning objectives

* Fundamentals of `R`
* Best practices for organising code
* Best practices for reproducibility

---

## Introduction to `R` and `RStudio`

----

### Learning objectives

* Familiarity with the RStudio IDE
* Set up a working directory with version control
* Introduce `R` syntax
* Introduce package management

----

### Why `R`/`RStudio`?

* Open source
* Free
* Available on all platforms
* Widely used, good community
* Is a programming language: 
  - scripting
  - automation
  - reproducibility
  - sharing

----

### `R`/`RStudio` presentation

**Live Presentation**

![Vince Twitter quote](images/buffalo.png)

----

### Best practices

* No single 'best' way - only good principles
* Treat all data as read only
  * (cf. `Excel`'s interactive modification)
* Data cleaning
  * Keep 'cleaned' data in a separate folder
* All generated output should be considered disposable

----

### Creating files/directories

**Live Presentation**

----

### Challenge 1

* Download [gapminder-FiveYearData.csv]()
* Create a new subdirectory called `graphs` in your working directory
* Modify `.gitignore` so that Git does not track the `graphs/` directory
* Commit this change to the local repository

![Red/green sticky](images/red_green_sticky.png)

----

### `R` as a calculator

**Live Presentation**