Getting Started
===============

Tools and Depenencies
---------------------
.. note::
    * Setting up `Visual Studio Code <https://code.visualstudio.com/>`_ environment Fleximi development. 
    * (Optional) You can copy `Cloud Settings by Gerard Vidamo <https://gist.github.com/gerardvidamo/40ce95df4022acb2bd0e7ae8ffbd017d>`_ 


.. note::
    * Use `DotNet Core 2.1 <https://dotnet.microsoft.com/download/dotnet-core/2.1>`_ stable version for Fleximi.
    * DotNet Core recommended version 2.1.403

- Use `Node.js <https://nodejs.org/en/>`_  and follow `nvm installation guide <https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/>`_, this is required for compiling front-end developments.
- `Bower <https://bower.io/>`_ is for getting all the packages for front-end developments.
- `Git <https://git-scm.com/>`_ is for getting the latest Fleximi branches and for developments.

Run and clone Fleximi
---------------------

.. note::
    You might need to install ubuntu bash if you are using Windows Operating system. Follow this guide `How to Install and Use the Linux Bash Shell on Windows 10 by Chris Hoffman <https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/>`_. 


Clone the repository somewhere on your disk and enter to the repository.:

    git clone https://github.com/gerardvidamo/Fleximi.git
    cd Fleximi

Next, restore and build solution. Open terminal and cd into Fleximi repo.:

    sh ./scripts/development.sh --restore
    sh ./scripts/development.sh --build

Now let's install packages and compile css for the UX/UI of Fleximi.:

    sh ./scripts/development.sh --install-packages
    sh ./scripts/development.sh --rebuild-packages

This command will run the solution::

    sh ./scripts/development.sh --run

    





