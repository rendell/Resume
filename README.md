# Resume

Took the example of the pagedow package and customized it. Documentation can be found on:
https://slides.yihui.org/2019-rstudio-conf-pagedown.html#1


https://pagedown.rbind.io/

I end up using the Posit cloud and having to manually install the pagedown package, because otherwise on my personal computer it will not work.

*Update:*
It works again on desktop version of Rstudio!
You might want to double check if the (potentially) required packages are available:
library(pagedown)
> install.packages("htmltools")
>install.packages('tinytex')
>
> set print to working directory. It then produces a self contained html file, which upon opening can be manually converted 'printed' into a PDF file.
>
> Voila
