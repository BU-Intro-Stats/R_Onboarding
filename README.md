# R onboarding website for BU intro Stats courses

[Link to the website](https://yongholim.github.io/R_Onboarding)

## Render the PDF guide

To create the full guide as a single PDF book:

```sh
quarto render full-guide.qmd --to pdf
```

This creates `R-Onboarding-Guide.pdf`.

For all chapters, from the project folder: 
```
quarto render 00-Install-rstudio.qmd --to pdf
quarto render 01-rstudio.qmd --to pdf
quarto render 02-first-script.qmd --to pdf
quarto render 03-quarto-rmarkdown.qmd --to pdf
quarto render 04-running-code.qmd --to pdf
quarto render 05-files-folders.qmd --to pdf
quarto render 06-download-csv.qmd --to pdf
quarto render 07-importing-data.qmd --to pdf
quarto render 08-getting-results.qmd --to pdf
quarto render 09-common-problems.qmd --to pdf
quarto render 10-cheatsheet.qmd --to pdf
```