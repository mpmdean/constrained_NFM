=======================================
Non-negative Matrix Factorization (NMF)
=======================================

Based on this paper
https://arxiv.org/abs/2104.00864

and this repo
https://github.com/bnl/pub-Maffettone_2021_04

=====
Setup
=====

    $ conda create -n nmf_env python==3.8 pip
    $ conda activate nmf_env
    $ python -m pip install --upgrade pip wheel
    $ pip install lmfit ipympl jupyterlab
    $ pip install git+https://github.com/mpmdean/pub-Maffettone_2021_04
