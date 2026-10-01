# BIOS 640 Assignment 4

This repository contains NHANES reports, figures, and a dashboard for BIOS 640 Assignment 4.

## Repository contents

- `data/`: cleaned NHANES data and the supporting diet dataset.
- `figures/`: figures created for Assignment 3.
- `reports/`: the original Assignment 3 R Markdown report and PDF.
- `exercise_2/`: the updated interactive R Markdown report and its HTML output.
- `exercise_3/`: the flexdashboard source and its HTML output.
- `exercise_4/`: the NHANES summary-table report, bibliography, and PDF output.

## Reproducing the outputs

Clone the repository and open it in RStudio. Install the R packages used in each `.Rmd` file; rendering the PDFs also requires a LaTeX installation such as TinyTeX. From the repository's root folder, run:

```r
rmarkdown::render("reports/assignment_3.Rmd")
rmarkdown::render("exercise_2/markdown_for_html.Rmd")
rmarkdown::render("exercise_3/nhanes_dashboard.Rmd")
rmarkdown::render("exercise_4/nhanes_dataset_description.Rmd")
```

The rendered HTML and PDF files are already included alongside their source files.
