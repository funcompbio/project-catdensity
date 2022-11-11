[![FCB-project-autograding](../../actions/workflows/fcb_autograding.yml/badge.svg)](../../actions?query=workflow%3AFCB-project-autograding)

# Project COVID19 Catalonia population density - FCB 2022

## Summary

In this project you should analyse data to attempt answering the following question:

> Do COVID19 spread is affected by population density in Catalonia?

## Data

You should use the following two datasets:

1. Cases of COVID-19 in Catalonia, broken by sex and municipality, at the
[Dades Obertes de Catalunya](http://governobert.gencat.cat/ca/dades_obertes) data portal.
You should download the CSV file by going to this
[link](https://analisi.transparenciacatalunya.cat/ca/Salut/Registre-de-casos-de-COVID-19-realitzats-a-Catalun/jj6z-iyrp), clicking on 'Exporta' and then on 'CSV'.

2. Land indicators of Catalonia, including population density by municipality, at the
[Dades Obertes de Catalunya](http://governobert.gencat.cat/ca/dades_obertes) data portal.
You should download the CSV file by going to this
[link](https://analisi.transparenciacatalunya.cat/Urbanisme-infraestructures/Indicadors-territorials-de-l-Observatori-del-Terri/b9cr-32i4), clicking on 'Exporta' and then on 'CSV'.

## Deliverables

The GitHub repo for this project should contain, at least, the following files:

  * `index.Rmd`: R Markdown script with the R code doing the analysis of the data
    and the corresponding text explaining those analysis steps.
  * `index.html`: Resulting HTML output from processing (_knitting_) the file
    `index.Rmd`. This file (`index.html`) and other web-related files may also be
    located in a subdirectory called `docs`, when publishing it with GitHub pages,
    but this `docs` subdirectory **cannot** have `.R` or `.Rmd` files.
  * The CSV files employed during the analysis.
  * This `README.md` file.

Object names in the R code in `.Rmd` and `.R` files **should not** contain
non-english characters such as `ç` or `ñ` or accents such as `à`, `é`, etc.
The analysis of the data described in the HTML file should contain the following
sections:

  * **Front matter:** This is the basic information of the project that should
    appear at the beginning and should consist of the following items: title of
    the project including at the end or as subtitle "FCB 2022", names of the
    authors and date. Here the words _Front Matter_ **should not** be included
    as section name.
  * **Abstract:** Summary of the question and the findings (max. 200 words).
  * **Introduction:** Description of the question and the data employed to
    answer it. Description of any steps taken, if any, previous to this R
    Markdown document, to prepare the data that is being analyzed.
  * **Results:** R code interspersed with text, descriping the analysis steps
    and the display items with the results, which should consist, **at least**,
    of one table and one plot.
  * **Conclusions:** summary of the findings, limitations of the study, ways in
    which this type of study could be improved in the future.
  * **References:** bibliographic references.

## Methodology

The analysis of the data should be carried out at least using R, but you can
also use shell or Python scripts to transform or prepare the data for the
analysis with R. If those prior steps using shell or Python scripts are
included, they should be described in the introduction section of the R
Markdown document and, ideally, made readily reproducible using a Makefile.

## Submission procedure

This assignment has to be submitted using GitHub Classroom. This
means that you should have cloned the GitHub repo of this assignment from
the organization account for FCB in the academic year 2022-23 at
[https://github.com/funcompbio2022](https://github.com/funcompbio2022)
using the submission link provided at the FCB Moodle site.

To complete your submission (see rubric below) one team member should fill up a
Google form provided at the FCB Moodle site before the deadline and **agree to
the following academic integrity statement**, by editing this README file and
placing the letter `X` between the squared brackets preceding the statement:

- [] The work here submitted has been entirely developed by the members of
  our team and it is the result of our own work.

## Evaluation rubric

The rubric to evaluate this project consists of the following items:

1. Have all members of the group agreed to the academic integrity statement?
   Have all members of the group made a sizeable number of commits to the
   GitHub repo?

2. Does the GitHub repo contain at least the analysed CSV files along with the
   `index.Rmd` file and the resulting `index.html`?

3. Does the R Markdown file `index.Rmd`, and any other additional code, run the
   analysis without errors and generates the expected `index.html` file?

4. Does the analysis described in the resulting `index.html` file conform to
   the requested sectioning.

5. Does the introduction explain clearly what is the question addressed, the
   data employed and the number of observations and variables involved?

6. Do the plots show some meaningful summary of the data? Are axes in plots
   labeled in plain language and large enough to read?

7. Does the R Markdown file `index.Rmd`, and any other additional R Markdown
   file, consists of R code interspersed with Markdown text? Is the code easy
   to read? Do the code instructions have a specific purpose?

8. Is the `index.html` and any other file forming the resulting website
   hosted in a private URL with GitHub Pages?

9. Does the GitHub repo include a _Makefile_ that automatizes the entire
   analysis pipeline and generation of the final report in the `index.html`
   file?

10. Does the project as whole make an overall good impression?
