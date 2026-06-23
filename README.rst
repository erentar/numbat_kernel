Jupyter kernel for https://github.com/sharkdp/numbat. This jupyter
kernel is based on, and almost identical to
https://github.com/takluyver/bash_kernel. The changes can be viewed at
https://github.com/takluyver/bash_kernel/compare/master…erentar:numbat_kernel:master

install it with

::

   pip install --editable .
   python -m numbat_kernel.install

the ``–editable`` flag is optional, it allows one to edit the kernel in
this folder without reinstalling it to python site-packages.
