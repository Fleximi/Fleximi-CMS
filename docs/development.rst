Getting Started
===============

Depenencies
------------

* `DotNet Core 2.1 <https://dotnet.microsoft.com/download/dotnet-core/2.1>`_ 

.. note::
    DotNet Core recommended version 2.1.403

- `Node.js <https://nodejs.org/en/>`_  and follow `nvm installation guide <https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/>`_ 
- `Bower <https://bower.io/>`_

Tools
-----

* `Visual Studio Code <https://code.visualstudio.com/>`_

Database
--------

* `MySQL <https://dev.mysql.com/downloads/mysql/>`_

Setting up Visual Studio Code
-----------------------------

Setting up Visual Studio Code environment Fleximi development

.. note::
    You can copy `Visual Studio Code Extensions <https://gist.github.com/gerardvidamo/40ce95df4022acb2bd0e7ae8ffbd017d> by Gerard Vidamo`_ 

Run and clone Fleximi
---------------------

Clone the repository somewhere on your disk and enter to the repository:

    git clone https://github.com/gerardvidamo/Fleximi.git
    cd Fleximi

Next, restore and build solution. Open terminal and cd into Fleximi repo

.. note::
    You may require ubuntu bash if you are using Windows Operating system. Follow this guide `How to Install and Use the Linux Bash Shell on Windows 10 by Chris Hoffman <https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/>`_ 

Restore and build::

    sh ./scripts/development.sh --restore
    sh ./scripts/development.sh --build

Now let's install packages and compile css for the UX/UI of Fleximi::

    sh ./scripts/development.sh --install-packages
    sh ./scripts/development.sh --rebuild-packages

This command will run the solution::

    sh ./scripts/development.sh --run

    





