# Preparation for work


## Github (one-off)
To see team collaboration:

1. Open a github account: github.com
2. Send the username to Lavinia to join the private team collabration
3. Accept the collaboration invitation


## Install software (one-off)

Get the latest version!

- R: https://www.r-project.org/
- RStudio: https://rstudio.com/products/rstudio/
- git: https://git-scm.com/


## Connect Rstudio to Github using personal token (one-off)
Details: https://happygitwithr.com/credential-caching.html


1. Enable version control in Rstudio: https://happygitwithr.com/rstudio-see-git.html
2. Create personal token on github: https://github.com/settings/tokens
3. Install package `install.packages("gitcreds")`, then call the library and paste the personal token.

```{r}
library(gitcreds)
gitcreds_set()
```

4. In Rstudio, under the terminal tab
```git
git config --global user.name 'Your name'
git config --global user.email 'Your registered email on github'

```



## Start with git project (ongoing)
To use the standard projects and packages developed by Lavinia, you will need to do the following:
1. Fork and clone at github: Part 28.1 of https://happygitwithr.com/fork-and-clone.html
2. Start project locally: Part 15.2 of https://happygitwithr.com/new-github-first.html
3. Add upstream remote (optional): https://happygitwithr.com/upstream-changes.html
4. Pull request (optional): https://happygitwithr.com/pr-extend.html


## More about git and R (For knowledge)
A well-written book by Jenny Bryan talking about git:
1. Git basics: https://happygitwithr.com/git-intro.html 
2. Full book: https://happygitwithr.com/


## Handle large file
git lfs: https://git-lfs.github.com/

