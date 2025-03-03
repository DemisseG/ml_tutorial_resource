# Resource for ML workshop
- To work with the notebooks, you need to setup a conda environment.
- **How To**
  -  Downlaod conda, if you don't have one from [here](https://www.anaconda.com/docs/getting-started/getting-started), and install it.
  -  Enable conda in powershell -- navigate to conda console and run the following
      ```console
      conda init powershell
      ```
  - Disable default environment activation
    ```console
    conda config --set auto_activate_base false
    ```
  - Create conda enviroment from `ml_tutorial_resource` using requirements.txt file as follows
    ```console
    conda create -n ml_sandbox
    conda activate ml_sandbox
    conda install --yes --file requirements.txt
    ```
  - Make sure the packages are correctly installed. 
