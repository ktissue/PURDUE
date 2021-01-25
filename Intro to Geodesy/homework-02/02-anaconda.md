
# Installing anaconda on your machine.

1. Visit https://www.anaconda.com/distribution/
1. Click **Download**
1. Select your OS and download **Python 3.7** version
1. Install using the downloaded file
    - It is recommended to install on your own machine, but installing on ECN machine is also possible.
    - When installing on Windows, especially on ECN machine, make it sure to select **Just me (recommended)** when asked on *installation type*.
    - ~~Install it on a location where all ECN machines can have access. For example, **U:\anaconda3**~~
    - Installation may take a while: It took me about 30-45 minute to finish installation on a machine in HAMP 1211.
1. After finish installing, start anaconda command line.
    - For Windows, you need to start either *Anaconda Prompt* or *Anaconda Powershell Prompt*
    - For Mac and Linux, you just need to start a regular command line window.

# Conda Cheat Sheet

* Print out information of your conda installation
```bash
$ conda info
```
```diff
- Submit the screenshot of conda info command window
```
* Get a list of all my virtual environments
```bash
$ conda info --envs
or
$ conda info -e
```
* Create a virtual environment and install programs
```bash
$ conda create --name geodesy numpy matplotlib pandas
or
$ conda create -n geodesy numpy matplotlib pandas
```
* Create a new virtual environment with specific Python version
```bash
$ conda create -n geodesy python=3.4 numpy matplotlib pandas
```
* Activate an environment
```bash
$ conda activate geodesy
```
* Deactivate the environment
```bash
$ conda deactivate
```
* Make exact copy of an environment
```bash
$ conda create -n geodesy2 --clone geodesy
```
* Delete an environment
```bash
$ conda remove -n geodesy2 --all
```
* Save current environment to a file
```bash
$ conda env export > geodesy.yml
```
* Load environment from a file
```bash
$ conda env create -f geodesy.yml
```
* View a list of packages and versions installed in an active environment
```bash
$ conda list
```
* Search for a package to see if it is available to install
```bash
$ conda search scipy
```
* Install a new package (If you don't provide the name of environment, then it will install in the current active environment)
```bash
$ conda install -n geodesy scipy
```
* Update a package
```bash
$ conda update numpy
```
* Remove a package from the active environment
```bash
$ conda remove scipy
```
