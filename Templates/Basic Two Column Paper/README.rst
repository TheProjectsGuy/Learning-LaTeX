============================================
LaTeX Template for a nice Two-Column Paper
============================================

Other than ``Avneesh Mishra`` (myself) all other names are not real. Other than ``Robotics Research Center, IIIT Hyderabad`` all other places (affiliations) are not real.

This is a work in progress. I keep adding things I feel is important to this template.

.. contents:: Table of contents
    :depth: 3

*********************
Cooperative Writing
*********************

The `coop-writing <cw-ctan_>`_ (`GitHub <cw-gh_>`_) package is used here.

.. _cw-ctan: https://www.ctan.org/pkg/coop-writing
.. _cw-gh: https://github.com/xexeo/coop-writing/

Download the ``sty`` file (compiled file) directly in the source folder using

.. code-block:: bash

    wget https://raw.githubusercontent.com/xexeo/coop-writing/main/coop-writing.sty

It is included in this folder as well.


*************
Conclusion
*************

Errata
=========

coop-writing using tlmgr
--------------------------

I tried installing it using ``tlmgr``, but it failed

.. code-block:: bash

    tlmgr init-usertree
    # This first failed with 'verify_checksum: -5'
    tlmgr install coop-writing
    # From https://tex.stackexchange.com/a/528635
    sudo su
    curl -fsSL https://www.tug.org/texlive/files/texlive.asc | tlmgr key add -
    # This says I should update to 2022 version (form 2019) :'(
    tlmgr install coop-writing
    # Just use the .sty from the repo ¯\_(ツ)_/¯

*************
References
*************

- A package for cooperative writing: https://www.ctan.org/pkg/coop-writing
- Lorem Ipsum generated through: https://lipsum.com/
