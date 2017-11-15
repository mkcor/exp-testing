# Loading, testing, and wrangling experimental data

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mkcor/exp-testing/master)

Guest Lecture at [PHYS 257](https://www.mcgill.ca/study/2017-2018/courses/phys-257)

*November 16, 2017*

## Local setup

We use cross-platform package manager [conda](https://conda.io/).
We recommend using the [Miniconda](https://conda.io/miniconda.html)
distribution. Once you have downloaded your Miniconda installer, run
the following command (adapt if necessary):

    $ bash ~/Downloads/Miniconda3-latest-Linux-x86_64.sh

and follow the installation steps. Now create a sandboxed environment
for this project:

    $ conda env create -f environment.yml
    $ source activate advanced-pandas
    $ jupyter notebook

If you edit file `environment.yml` (to add or update a dependency), then
run:

    $ conda env update -f environment.yml

## Remote setup

Check out this
[draft](https://www.authorea.com/users/153798/articles/213273-deploying-computing-environments).

## References

* [PyData 101 slides](https://speakerdeck.com/jakevdp/pydata-101)
by Jake VanderPlas
* [Tidy Data article](https://www.jstatsoft.org/article/view/v059i10/)
by Hadley Wickham
