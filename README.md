docker-jupyter-notebook
=======================
### Install package
- Conda
  ```
  import sys
  !conda install --yes --prefix {sys.prefix} numpy
  ```
- pip
  ```
  import sys
  !{sys.executable} -m pip install numpy
  ```
- Reference
  - https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/
