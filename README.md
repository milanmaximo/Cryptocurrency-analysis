# Cryptocurrency-analysis
Cryptocurrency analysis using Python

Step 1 - Setup Your Data Laboratory

The tutorial is intended to be accessible for enthusiasts, engineers, and data scientists at all skill levels. The only skills that you will need are a basic understanding of Python and enough knowledge of the command line to setup a project.
Step 1.1 - Install Anaconda

The easiest way to install the dependencies for this project from scratch is to use Anaconda, a prepackaged Python data science ecosystem and dependency manager.

To setup Anaconda, I would recommend following the official installation instructions - https://www.continuum.io/downloads.

If you're an advanced user, and you don't want to use Anaconda, that's totally fine; I'll assume you don't need help installing the required dependencies. Feel free to skip to section 2.
Step 1.2 - Setup an Anaconda Project Environment

Once Anaconda is installed, we'll want to create a new environment to keep our dependencies organized.

Run conda create --name cryptocurrency-analysis python=3 to create a new Anaconda environment for our project.

Next, run source activate cryptocurrency-analysis (on Linux/macOS) or activate cryptocurrency-analysis (on windows) to activate this environment.

Finally, run conda install numpy pandas nb_conda jupyter plotly quandl to install the required dependencies in the environment. This could take a few minutes to complete.

Why use environments? If you plan on developing multiple Python projects on your computer, it is helpful to keep the dependencies (software libraries and packages) separate in order to avoid conflicts. Anaconda will create a special environment directory for the dependencies for each project to keep everything organized and separated.
Step 1.3 - Start An Interative Jupyter Notebook

Once the environment and dependencies are all set up, run jupyter notebook to start the iPython kernel, and open your browser to http://localhost:8888/. Create a new Python notebook, making sure to use the Python [conda env:cryptocurrency-analysis] kernel.
