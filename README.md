# Exercise 3: Designing Research Visually

Part of the workshop **Data Visualization With AI**. Prompts are on the workshop page.

## Open the project

- **RStudio:** open the `.Rproj` file.
- **Positron or VS Code:** open this folder.
- **Claude Code or Codex:** start the tool from a terminal in this folder.

You need R with **tidyverse**, **here**, and **rmarkdown**, plus **dagitty**, and Quarto (bundled with RStudio).

## What's here

| Notebook | Use |
|---|---|
| `notebooks/01_dag.qmd` | Write a design as a DAG and get its adjustment set |
| `notebooks/02_simulate.qmd` | Simulate from the DAG and plot which models recover the true effect |
| `notebooks/03_mermaid.qmd` | Diagram the study flow with Mermaid |

`docs/reference/simulate-from-dag.qmd` is a complete example: a confounder and a collider, 500 simulations, and one plot that shows which adjustment set works.

## About the folders

This project was created from a [Framework](https://framework.pub) blueprint, so it has the layout of a real analysis project: data in `inputs/raw/` (codebooks in `inputs/raw/codebooks/`), your notebooks in `notebooks/`, and results in `outputs/`. `docs/reference/` holds worked reference notebooks from Erik's data visualization course; compare them with what your assistant produces. You don't need the framework R package.
