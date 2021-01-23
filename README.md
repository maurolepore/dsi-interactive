
This repository hosts the materials for the ds-incubator series on
building and publishing interactive tools in R. It will evolve along
with the series.

# dsi-interactive

## Introduction

**Goal.** You can build different kinds of interactive tools, and
publish them in different places. The goal of this series is to overview
the most common kinds of tools and publishing platforms, so you can
choose to learn more and use the ones that best fits your needs. Because
Shiny is in active development, you will learn about current “best
practices”, as documented in “[Mastering
shiny](https://mastering-shiny.org/)”.

**Audience.** The target audience any R user that may want to know which
interactive tools are available, and where to publish them. This
includes folks at 2DII and beyond.

**Requirements** I assume you are already familiar with R, and RStudio.
You’ll feel more conformable if you already know a bit about rmarkdown
documents, Git, and GitHub; but this is not a requirement. You don’t
need previous experience building interactive tools.

**Depth and breath.** even when I plan to cover each topic only
superficially, the range of topics will be wide and hope you’ll learn
something new in each session. I’m sure I will.

**Structure.** I’ll thrive for most meetups to show the process from end
to end. We’ll move from simpler tools and publishing options to more
complex ones. Each meetup will stand alone. It’s okay to skip meetups –
at worst you may feel a little lost but you should still get something
useful.

**Contributions.** I welcome your contributions. I’m new to most of the
technologies we’ll cover and it would be nice to have some expert cover
a specific topic more deeply, or show a use case.

**Duration.** I’m not sure yet as it depends on your interest. I think
it’s reasonable to expect between 4 and 12 meetups.

## The whole game: Learn how to create and publish a toy interactive app.

-   Create a shiny app from a template.
-   Run the app locally.
-   Publish the app on rstudio.cloud
-   Make your app private

## Parametrized rmarkdown documents and rsconnect

-   Create parametrized rmarkdown documents
-   Publish to rsconnect via bookdown.org (limited) and or to
    shinyapps.io
-   Make your app private
-   Genarate reports on a schedule
-   Navigate the history of a report

## Using widgets in your rmarkdown documents

-   DT tables
-   plotly
-   leaflet
-   See also <https://shiny.rstudio.com/gallery/>
-   2DII widgest (demo)

## Rmarkdown documents with shiny components

-   `runtime: shihy`
-   flexadashboard
-   learnr
-   Publish the app on &lt;shinyapps.io&gt;

## Building and deploying apps as packages

-   Structuring apps as packages
-   Deployment
-   See also <https://engineering-shiny.org/>

## Accesing private data from public apps

-   Environmental variables
-   Package config

## Reproducible R environments with renv

-   …

## Themes: Using third-party or custom solutions

-   bb?
-   thematic

## Docker

-   …