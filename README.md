# Demo of HashiCorp Vault KMIP secrets Engine with Oracle Enterprise TDE

Note: This notebook is still not fully functioning as we are missing the ARM64 pluging for this to work. Work in progress.

This is using a Jupyter notebook to execute the steps required.
It also assumes that you have HashiCorp Vault installed and configured on your side.

This will also require an ADP KMIP license.

You can use Visual Studio Code to run the notebook by:
- Installing "Jupyter" extension. Ref: https://www.alphr.com/vs-code-open-jupyter-notebook/
- Install the jupyter kernel for bash. Ref: https://pypi.org/project/bash_kernel/
```shell
pip install bash_kernel
python -m bash_kernel.install
```
