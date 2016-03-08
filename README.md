

MEGUA package
=============

**Alpha version**

Presented at:
<a href="http://library.iated.org/view/CRUZ2013MEG" title="MEGUA PACKAGE FOR PARAMETERIZED EXERCISES">MEGUA PACKAGE FOR PARAMETERIZED EXERCISES</a>


Started in 2011, MEGUA is an external package for Sagemath for creating parametrized exercises in HTML+MathJAX or LaTeX PDF files. Software docs strings are in english but the following documentation is in [portuguese](https://pt.wikipedia.org/wiki/L%C3%ADngua_portuguesa):

- <a href="http://cms.ua.pt/megua" title="MEGUA PACKAGE FOR PARAMETERIZED EXERCISES">Management</a>: people, works, seminars, and related things.
- <a href="http://megua.readthedocs.org/pt/latest/" title="TUTORIAL DO MEGUA">MEGUA Tutorial</a>: concepts and practice.

There are two branches in this repository:

- **old_megua**: running in a non public server from november 2010 to 2015 (well 5 years...!!).
- **master**: version to be adopted for SageMathCloud use, command-line, etc. 

DEVELOP
-------

* aalib: download, gunzip, untar
* aalib: sage -python setup.py install 
* etoolbox.sty: sudo apt-get install texlive-latex-extra
* salvus: /projects/sage/sage-6.10/local/lib/python2.7/site-packages/smc_sagews
* from smc_sagews.sage_salvus import salvus #Functions: salvus.file(), salvus.html()
* sage_server.py: contains definitions of "def file()" and "def html()", see useful arguments



