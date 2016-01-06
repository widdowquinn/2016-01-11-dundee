# SPEAKER_NOTES.md - R

Speaker Notes for the 2015-11-12 Software Carpentry R lesson

**TYPE ALL EXAMPLES AS YOU GO. THIS KEEPS THE SPEED SANE, AND ALLOWS YOU TO EXPLAIN EVERY STEP.**

**START SLIDES WITH `reveal-md slides.md --theme=white`**

## `R for reproducible scientific analysis`

**SLIDE** (Learning objectives)

* Welcome
* Teaching
  * Talk around slide

* **Our goal is not just to "do stuff"**
  * do it so that anyone can easily and exactly replicate our workflow and results

## Introduction to R and RStudio
  
**SLIDE** (Why `R`/`RStudio`?)
  
* Talk around slide
  
**SLIDE** (`R`/`RStudio` presentation)

* Live presentation section
* Everyone start up `RStudio`

**Summarise windows**

* Four (maybe three) subwindows:
  * Interactive `R` console
  * Editor (may be missing on startup - will appear when files are opened)
  * Environment/History
  * Files/Plots/Packages/Help
  
### Create a working directory with version control

* **We're following practices of project management**
  * We'll create a project directory, with `Git` version control
  * Helps ensure data integrity
  * Makes sharing code easier (lab-mates, publication)
  * Easier to recover after a Christmas break
  
* **Create the new directory**
  * `File->New Project`
  * `New Directory`
  * `Empty Project`
  * Enter sensible name, e.g. `swc-workshop`
  * Check box for `Create a git repository`
  * `Create project`
  
**GREEN/RED STICKY CHECK**  

* Describe contents of new folder
  * `.gitignore`
  * `.Rproj`
  
**SLIDE** (Best practices)

* Talk around slide

### Create directory structure

**SLIDE** (Creating files/directories)

* Live presentation section

* **Create subdirectory for data**
  * In `Files` tab, create `data` subdirectory
  
* **Create new `R` script**  
  * `File -> New File -> R script`
  * save in working directory with sensible name, e.g. `swc-script.R`
  
**GREEN/RED STICKY CHECK**

### Version control 

* **Show Git tab on right**

* **Stage files**
  * Three files shown (including `.gitignore` and the new script file)
  * Yellow status markers mean they're not in the repository
  * Click check-boxes to stage them
  * Note that **we don't version disposable output**

* **Commit files**
  * Click `Commit`
  * Describe new dialogue window
  * Show contents/changes to files
  * Add commit message ("Initialised repository")
  * Commit
  * Show commit summary
  * Exit
  
**GREEN/RED STICKY CHECK**  

**SLIDE** (Challenge 1)

Run through challenge (5min?) - hint about editing `.gitignore`

* Create `graphs` subdirectory in `Files` tab
* Edit `.gitignore` to add `graphs/` folder and save
* Stage `.gitignore` in Git tab
* Commit in Git tab, and add appropriate commit message

**SLIDE** (`R` as a calculator)

### Interacting with `R`

* **Two ways**
  * Type commands in the console
  * Use the script editor and save the script
  
* **Console**
  * Good for experimentation
  * Commands 'forgotten' when you close a session
  
* **Script**
  * Keeps record of whay you did
  * Easier to reproduce and share
  

