# exp-testing
Demo for reading and testing experimental data.

## Setup

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

## References

* [PyData 101 slides](https://speakerdeck.com/jakevdp/pydata-101)
by Jake VanderPlas
