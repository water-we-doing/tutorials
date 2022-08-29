# How to Clone a GitHub Repo from the Terminal

# <a href = "https://youtu.be/TD6AQRPQs3I">VIDEO TUTORIAL!</a> 

The following are *very* detailed instructions to accomplish these simple tasks:
1. Check that Python is downloaded
2. Check that the git package is downloaded
3. Clone a GitHub repository!

Lets go!!

1. Open the terminal.
2. Check if you have Python already installed by typing ```python --version```.
3. If the first number is <3 or you don't have Python, follow <a href = "https://realpython.com/installing-python/">these instructions</a> to update or install python.
4. Check if you have git installed by typing ```git --version```.
5. If you don't have git (or even if you do!), install <a href = "https://brew.sh/">Homebrew</a>:
  * This is a tool that lets you download packages more easily.
  * Type ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``` into the terminal. It will walk you through the steps to install via the terminal.
  * Now you can type ```brew install git``` to install git.
6. Type ```pip install scipy``` to get a package that this code needs installed on your computer.
7. Now let's go to the folder where we want to save (ie clone) the repository:
  * To move into a specific folder, type its name like ```cd Desktop```. You'll see that the name of this folder is now to the left of your cursor.
  * You can print a list of all of the folders and files inside of this folder (called a directory) by typing ```ls```.
  * To go back to the previous folder level, type ```cd ..```
  * I suggest making a folder in your Documents called something like "GITHUB" and storing all of your cloned repositories in there. To do that, you would type:
    * ```cd Documents```
    * ```mkdir GITHUB```
    * ```cd GITHUB```
8. Now we'll clone the desired repository (aka repo) by typing something like: ```git clone https://github.com/water-we-doing/gas-flux-sampling```. Replace water-we-doing with the user and gas-well-sampling with the repo name for other repos.
9. Now when you look in the your Documents/GITHUB/ folder, you should see a folder called gas-flux-sampling with files in it!
