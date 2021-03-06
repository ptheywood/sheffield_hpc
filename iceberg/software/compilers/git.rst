.. include:: ../../../iceberg-eol.rst 

git
===

.. sidebar:: git

   :Latest version: 2.5
   :Dependancies: gcc 5.2
   :URL: https://git-scm.com/

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Usage
-----
An old version of git is installed as part of the system's opertaing system. As such, it is available everywhere, including on the log-in nodes: ::

    $ git --version
    git version 1.7.1

This was released in April 2010. We recommend that you load the most up to date version using modules - something that can only be done after starting an interactive ``qrshx`` or ``qsh`` session: ::

    module load apps/gcc/5.2/git/2.5

Installation notes
------------------
Version 2.5 of git was installed using gcc 5.2 using the following install script and module file:

* :download:`install_git_2.5.sh </iceberg/software/install_scripts/apps/git/install_git_2.5.sh>`
* :download:`git 2.5 modulefile </iceberg/software/modulefiles/apps/git/2.5>` located on the system at ``/usr/local/modulefiles/compilers/git/2.5``
