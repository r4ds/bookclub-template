# R4DS BOOKNAME Book Club

FIND/REPLACE BOOKABBR, BOOKNAME, BOOKURL, BOOKAUTHORS, BOOKPUBLISHER, BOOKCOPYRIGHT, BOOKISBN, BOOKDOI, BOOKDAYS, and BOOKTIMECST THEN DELETE THIS SENTENCE.

ALSO UPDATE THE MEETING TIME INFO BELOW AND DELETE THIS SENTENCE.

ALSO ADD PLACEHOLDERS FOR ALL CHAPTERS BY COPYING 01.Rmd (IDEALLY ALSO UPDATE TITLES WITHIN THE FILES), THEN DELETE THIS SENTENCE.

Welcome to the R4DS BOOKNAME Book Club!

We are working together to read [_BOOKNAME_](BOOKURL) by BOOKAUTHORS (BOOKPUBLISHER, copyright BOOKCOPYRIGHT, [BOOKISBN](BOOKDOI)).
Join the #book_club-BOOKABBR channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/BOOKABBR).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: BOOKDAYS, BOOKTIMECST CST/CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- YYYY-MM-DD: Introduction - FACILITATOR
- YYYY-MM-DD: Chapter 1 (TITLE) - Presenter TBD


<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_Happy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-BOOKABBR")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/BOOKABBR).
