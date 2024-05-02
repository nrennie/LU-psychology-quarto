# Introduction to Quarto for Research

Date: May 9, 2024

Tutor: Nicola Rennie ([n.rennie@lancaster.ac.uk](mailto:n.rennie@lancaster.ac.uk))

## Session overview

### Part 1 (morning)

* Introduction to Quarto
  * What is Quarto?
  * Why is Quarto good for reproducible research?
  * How does Quarto compare to alternatives?
* Making your first Quarto document
  * Output types
  * YAML options (document properties)
  * Document rendering
  * Quarto in RStudio
* Document content
  * External image files
  * Tables
  * Links
  * Markdown syntax: Bullet points, lists, bold text
* Code blocks (maybe afternoon depending on time)
  * Plots
  * Tables

### Part 2 (afternoon)

* Referencing
  * Inline code and referencing results
  * Results references in figure captions
  * Figure and table references
  * Cross references
  * Citations
* Formatting
  * Journal templates (e.g. APA style)
  * Output formats (Word, LaTeX)
  * Manuscript format
* Collaborating with Quarto
  * GitHub
  * {trackdown}
  * VSCode Live Share
* Discussion
  * Nice features
  * Tricky things
  * Quarto and R versions
  * {targets}
  * Converting from R Markdown

## Prerequisites

### Quarto

* You should have a working installation of Quarto.
  * If you have installed a recent version of RStudio IDE (after Jul 2022), you should already have Quarto installed.
  * If you click on the **Terminal** tab in RStudio (next to the **Console**) and run `quarto --version` this will tell you if Quarto is installed and what version you have.
  * You can also install a more recent version if required. See [quarto.org/docs/get-started](https://quarto.org/docs/get-started/) to download Quarto. 
  * You should also have access to a text editor or IDE (e.g. RStudio, VSCode, Emacs). RStudio is recommended for this workshop.
  * If you have any issues installing R, RStudio, or Quarto, you may wish to use [posit.cloud](https://posit.cloud/) for the session.

### R

* You should have a working installation of R.
* You do **not** need to be experienced in R for this workshop. Code examples will be provided.
* Packages used: 
  * {psych} (for `bfi` data only). This can be read in with `bfi <- read.csv("https://vincentarelbundock.github.io/Rdatasets/csv/psych/bfi.csv")` instead.

### Other

* You may wish to bring a laptop charger as the workshop will run for most of the day.

