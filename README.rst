About This Book
===============

This `repository <https://github.com/SystemsApproach/SDN-CN>`__
contains source for a Chinese translation of *Softwarwe-Defined
Networks: A Systems Approach*, available under terms of the `Creative
Commons (CC BY-NC-ND 4.0)
<https://creativecommons.org/licenses/by-nc-nd/4.0>`__ license. The
community is invited to contribute corrections, improvements, updates,
and new material under the same terms.

Read the Book
-------------

An online version of the book will be published once the translation
is complete.

Build the Book
--------------

To build a web-viewable version, you first need to download the source:

.. code:: shell 

   mkdir ~/SDN-CN
   cd ~/SDN-CN
   git clone https://github.com/SystemsApproach/SDN-CN.git 

The build process is stored in the Makefile and requires Python be 
installed. The Makefile will create a virtualenv (``doc_venv``) which 
installs the documentation generation toolset. 

To generate HTML in ``_build/html``,  run ``make html``.

To get a live reload in your browser (refreshes on file save), run ``make reload``.

To check the formatting of the book, run ``make lint``.

To see the other available output formats, run ``make``.

Contribute to the Book
----------------------

We hope that if you use this material, you are also willing to
contribute back to it. If you are new to open source, you might check
out this `How to Contribute to Open
Source <https://opensource.guide/how-to-contribute/>`__ guide. Among
other things, you’ll learn about posting *Issues* that you’d like to see
addressed, and issuing *Pull Requests* to merge your improvements back
into GitHub.

If you’d like to contribute and are looking for something that needs
attention, see the `wiki <https://github.com/SystemsApproach/SDN-CN/wiki>`__
for the current TODO list.
