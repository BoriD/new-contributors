
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

[![dataobservatory](https://img.shields.io/badge/ecosystem-dataobservatory.eu-3EA135.svg)](https://dataobservatory.eu/)
[![dataobservatory on
Github](https://img.shields.io/badge/github-dataobservatory.eu-6e5494.svg)](https://github.com/dataobservatory-eu/)
[![R package
iotables](https://img.shields.io/badge/R-iotables-4EC0E4.svg)](https://iotables.dataobservatory.eu)
[![R package
retroharmonize](https://img.shields.io/badge/R-retroharmonize-007CBB.svg)](https://iotables.dataobservatory.eu)
[![R package
regions](https://img.shields.io/badge/R-regions-00843A.svg)](https://regions.dataobservatory.eu)
[![R package
dataset](https://img.shields.io/badge/R-dataset-E4007F.svg)](https://dataset.dataobservatory.eu)
[![R package
spotifyr](https://img.shields.io/badge/R-spotifyr-1db954.svg)](https://www.rcharlie.com/spotifyr)
[![R package
statcodelists](https://img.shields.io/badge/R-statcodelists-lightgrey.svg)](https://statcodelists.dataobservatory.eu)
[![Contributor
Covenant](https://img.shields.io/badge/ethics-Contributor%20Covenant-680171.svg)](https://dataobservatory.eu/)

<!-- badges: end -->

## New Contributors

Welcome to our
[dataobservatory.eu](https://github.com/dataobservatory-eu/) R, hugo,
and open data ecosystem. We are very happy to guide you to the
experience of open source development and open knowledge management
regardless of your experience level with R or Github. We kindly ask you
to take the Contributor Covenant Pledge before starting our
collaboration.

“We as members, contributors, and leaders pledge to make participation
in our community a harassment-free experience for everyone, regardless
of age, body size, visible or invisible disability, ethnicity, sex
characteristics, gender identity and expression, level of experience,
education, socio-economic status, nationality, personal appearance,
race, caste, color, religion, or sexual identity and orientation.

We pledge to act and interact in ways that contribute to an open,
welcoming, diverse, inclusive, and healthy community.”

Please read the [entire covenant
here](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## A bit of housekeeping

You will need the devtools R package and the RTools extension to your
already installed R system, and you should be working with RStudio.

### Get your computer ready

-   [x] You will need the crossplatform Java programming environment on
    your computer. It is cross-platform and facilitates the use of
    Linux, BSD/Mac OX and Windows collaboration. You most probably have
    it. It is a good opportunity to check if you have the latest
    version. If not, do upgrade, both for security and functionality
    reasons, and at the same time remove the old versions. Follow this
    link <https://www.java.com/en/download/>.

### Install R and some critical components

-   [x] If you recently installed R, you most likely have the latest
    version. If not, then run `install.packages(“installr”)` and run
    `installr::check.for.updates.R()`. If there is a newer R release,
    you should upgrade. `installr::updateR()` will take you through the
    progress, including the moving of your already installed packages to
    the new R installation, however, it will not remove the old R
    environment. You should run the upgrader from the R GUI (you will
    find this somewhere on your computer, even though you may have
    forgotten about it because you always use R from RStudio.)

-   [ ] In my experience, the copying of the old R packages is not
    always successful. You can prepare for this by saving the list of
    installed packages before your I do not my reinstalling though my
    packages. It reminds me to remove detritus, and review my own
    developments.

-   [x] One package that is worth running at all new installs is
    tinytex. `tinytex::reinstall_tinytex()` or
    `tinytex::install_tinytex()`. [Tinytex](https://yihui.org/tinytex/)
    is a lightweight tex engine, and it will allow many tex libraries
    from [CTAN](https://ctan.org/?lang=en), such as fonts, formatting
    tools for TeX, and so on. This is required for an efficient creation
    of PDF files, in package documentation or elsewhere.

-   [x] Now, when you have the latest version of R, install Rtools, too.
    <https://cran.r-project.org/bin/windows/Rtools/>

-   [x] Install the `usethis` and `devtools` packages with all their
    dependencies. You should run `install.packages(“devtools”)` and see
    if all dependencies install without error. If not, you must figure
    out why some components are not installing.

### Connect to the Github collaboration platform via RStudio

-   [x] Now install [RStudio](https://www.rstudio.com/), or, if you
    already have it, check if you have the latest version. (Help Menu,
    Check for Updates.)

-   [x] If you haven’t done so yet, create an account on Github, and on
    Windows I suggest to install the Github Client. If you already have
    a Github account, but you have not used it recently, or did not
    connect RStudio to it lately, you are likely to have to do it again.

-   [ ] Github does not support password authentication since August
    13, 2021. This means that you cannot synchronize your offline and
    online repository using your *username* and *password* combination.

-   [ ] You can no longer synchronize the repository on RStudio with a
    repository URL only. For example, to synchronize
    `https://github.com/rOpenGov/retroharmonize`, you must explicitly
    state on your computer to synchronize via this URI:
    `git@github.com:rOpenGov/retroharmonize.git`, which will require the
    use of a

-   [x] [Happy Git and GitHub for the useR](https://happygitwithr.com/)
    guides you through the process on Linux, Mac OS or Windows
    platforms.

### 👋🏿 Handshake

-   [ ] Run into a problem? We use the open-source and encyrpted,
    privacy-sensitive competitor of Slack,
    [Keybase](https://keybase.io/). You can ask for help in our [Keybase
    Community](https://keybase.io/team/reprexcommunity).

-   [x] For any of our repositories that you would like to contribute to
    into your own Github profile, for example,
    <https://github.com/rOpenGov/retroharmonize/> to
    *yourusername/retroharmonize*.

-   [x] Send a pull request when you have something to commit to our
    work.
