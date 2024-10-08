# helloWorld

helloWorld package was created to exemplify GitHub and R Studio Integration.

### Note

Please consult this [link](https://docs.github.com/en/get-started/writing-on-github/getting-started-%20with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for more information about formatting. To install a GitHub Package in R you may need *devtools*. If so, please run the following code:

``` r
if (!requireNamespace("devtools", quietly = TRUE))
  install.packages("devtools") 
```

You can install an R package that is publicly available in GitHub by using the following code (replacing **GitHubName/repo** with the correct information):

``` r
devtools::install_github('GitHubName/repo') 
```

You can also create links to files in your repository, for example the script ["hello.R"](R/hello.R) in the R folder
