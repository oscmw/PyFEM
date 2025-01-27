Installation
============

Below, instructions are given how to access PyFEM and install it on windows using Git Bash. 

The original code can be downloaded from the website that accompanies the book.

  http://www.wiley.com/go/deborst
  
The latest development version is available on Github:

  https://github.com/jjcremmers/PyFEM

This version of the PyFEM is written to work properly in combination with 
Python version 3.x. In addition, the code uses the modules numpy, scipy and
matplotlib. Installation guidelines are given for various operating systems.

Linux
-----

The Python compiler and the modules ``numpy``, ``scipy``, and ``matplotlib`` are included in 
most common distributions of Linux and can be installed without any problems. In many cases, 
different versions of ``python`` are offered. Please make sure that ``python`` version 3.6 or 
higher is installed. In addition, the modules ``meshio``, ``pickle``, and ``h5py`` can be 
installed for additional functionality.

Execute the file ``install.py`` in the root directory ``pyfem``. In a terminal, one can type:

.. code-block:: bash

   ./install

This script will check if the correct versions of Python and the various modules are available. 
If not, it will ask your permission to install the correct modules for you.

The main executables are created. In commandline you can run PyFEM by typing

.. code-block:: bash
    <relative_path_to_this_directory>/pyfem.sh inputFile.pro

The Graphical User Interface of the code (currently under development) can be exectuted
by typing from any directory:

.. code-block:: bash
    <relative_path_to_this_directory>/pyfem_gui.exe

It is advised to create aliases. When using a bash shell, please 
add the following lines to the file ``~/.bashrc``:

.. code-block:: bash
    alias pyfem='python3 /home/joris/Git/pyfem_github/PyFEM/PyFEM.py'
    alias pyfem_gui = '/home/joris/Git/pyfem_github/PyFEM/pyfem_gui.x'

You can then run PyFEM in commandline from any directory by typing:

.. code-block:: bash
    pyfem inputFile.pro

You can start the gui by typing:

.. code-block:: bash
    pyfem_gui
    
Windows
-------

Under construction

MacOS
-----

Under construction  
