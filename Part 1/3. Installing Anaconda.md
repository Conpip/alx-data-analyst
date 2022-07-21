# Installing Anaconda
Anaconda is available for Windows, Mac OS X, and Linux. Follow the links below to get started:

1. Download the installer from https://www.anaconda.com/download/. Choose the Python 3.7 or higher 
version, and the appropriate 64/32-bit installer. If you already have Python installed on your 
computer, this won't break anything. Instead, the default Python used by your scripts and programs
will be the one that comes with Anaconda.

2. Refer the installation instructions [here][1]
3. Verify the installation [here][2] for your respective OS

After installation, you’re automatically in the default conda environment with all packages installed.
You can check out your own install by entering the following command into your terminal.

```conda list```

## List of Applications Installed with Anaconda
The following packages will get installed with Anaconda:

* **Anaconda Navigator** - a GUI for managing your environments and packages
* **```conda```** - a command-line utility
* **Python** - The latest version of Python gets installed as an individual package.
* **Anaconda Prompt** - [Only for Windows] a terminal where you can use the command-line 
interface to manage your environments and packages
* A bunch of applications, such as **Spyder**. It is an IDE geared toward scientific 
development. In total, over 160 scientific packages and their dependencies are also installed.

To avoid errors later, it's best to update all the packages in the default environment. 
Open the Terminal/ Anaconda Prompt application. In the prompt, run the following commands:

```conda upgrade conda``` <br>

```conda upgrade --all```

and answer yes when asked if you want to install the packages. The packages that come with 
the initial install tend to be out of date, so updating them now will prevent future errors 
from out of date software.

> Note: In the previous step, running ```conda upgrade conda``` should not be necessary because ```--all``` 
includes the conda package itself, but some users have encountered errors without it.

In the rest of this lesson, you'll learn to use commands in your Terminal/Anaconda Prompt. 
I highly suggest you start working with command-line utility first, then later use the GUI if 
you'd like. Once you get acquainted with the command-line utility, refer to the [Starter Guide 
for Anaconda distribution (GUI)][3].

Troubleshooting Resources
If you are facing difficulty in installing and running conda, refer to the FAQ - [Should I add 
Anaconda to the macOS/Linux/Windows PATH?][4]. Additionally, the following links might be useful:

1. Linux/macOS -

    * If you are seeing the "conda command not found" and are using ZShell, you have to add ```export 
    PATH="/Users/USERNAME/opt/anaconda/bin:$PATH"``` to your .zsh_config file.

2. Windows users -

      * ['export' is not recognized as an internal or external command][5]
      * ['Conda' is not recognized as internal or external command][6]

## How to Install ```pip``` Package Manager
If you have successfully installed Anaconda/Miniconda, possibly you will have conda (and pip) 
automatically installed on your system. If pip is not there, we recommend you install the ```pip``` 
as well because you will be able to run ```pip``` commands only after installing it.

> *Check if pip is already installed, by running this command on Terminal/Anaconda Prompt* <br>
```pip --version```

> *Once you have conda installed, run the command below on Terminal/Anaconda Prompt* <br>
```conda install pip```


### *Update Note*
*In newer version of Anaconda/Miniconda, both ```pip``` and ```conda``` package managers are included by default, 
so you do not need to install them separately*.





[1]:https://docs.anaconda.com/anaconda/install/
[2]:https://docs.anaconda.com/anaconda/install/verify-install/
[3]:https://docs.anaconda.com/_downloads/9ee215ff15fde24bf01791d719084950/Anaconda-Starter-Guide.pdf
[4]:https://docs.anaconda.com/anaconda/user-guide/faq/
[5]:https://stackoverflow.com/questions/26368306/export-is-not-recognized-as-an-internal-or-external-command
[6]:https://stackoverflow.com/questions/44515769/conda-is-not-recognized-as-internal-or-external-command



