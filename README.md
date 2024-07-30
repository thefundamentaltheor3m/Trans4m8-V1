# Welcome to Trans4m8!

Trans4m8 is an educational tool designed using 3blue1brown's manim. Its purpose is to help teachers and students tackle the topic of consecutive graph transformations, covering scaling and translation in the positive and negative $x$ and $y$ directions. Trans4m8 is easy and intuitive to use.

# Installation Instructions

Trans4m8 runs on Python 3.8, which can be [downloaded online](https://www.python.org/downloads/release/python-387/) for free.

After you have successfully installed Python on your Mac, download and unzip the `Trans4m8_Executable.zip` file in the above repository.

Open a terminal at the folder `Trans4m8_Executable`. You can do this by pressing control and clicking on the folder in Finder and then selecting "New Terminal at Folder".

Alternatively, launch Terminal and type `cd` followed by any of the following:  

- clicking and dragging the folder `Trans4m8_Executable` from Finder to the terminal window  
- copying the folder `Trans4m8_Executable` (⌘C) and pasting it in your terminal window  
- manually entering the file path  

Your command should ultimately look like

```
cd /Some/Path/Trans4m8_Executable
```

After opening your terminal, your terminal prompt should show

```
YourUserName@Your-Macs-Name Trans4m8_Executable %
```

Enter the following command:

```
chmod a+x ./Installation_Script.sh
```

This command will ensure that that the bash script in `Installation_Script.sh` is in an executable format. You will not get any output in the terminal; this is absolutely normal. This command is what makes the next command possible:

```
./Installation_Script.sh
```

This is the script that installs Trans4m8 and all the libraries it uses. Pay attention to your terminal window, because you may need to enter your password. Follow any instructions that may pop up. Ensure that you have a stable internet connection. The installation can take a fair amount of time.

After that exhaustive installation, your computer should be ready to run Trans4m8!

# Running Trans4m8

To run Trans4m8, all you will need to do is open a terminal in the `Trans4m8_Executable` directory and type

```
./Trans4m8.sh
```

and Trans4m8 should launch momentarily.

If it does not, you can try the more direct

```
./venv/bin/python ./__main__.py
```

that will directly invoke the execution of the `__main__.py` file in the Python virtual environment.

# And that's that!

While this installation process is no doubt very tedious, I must fully disclose my limited knowledge of app development. In fact, this is my very first properly functioning, _somewhat_ distributable GUI Application! The software itself is also by no means anywhere NEAR perfect. It's often slow and can only render functions of certain families correctly. Perhaps I will patch up the source code with a more recent release of Manim.

I would really appreciate any suggestions on how to make the installation process more streamlined and user-friendly. Suggestions on other ways to improve Trans4m8 are also very welcome. Do also check out my [YouTube Channel](https://www.youtube.com/channel/UCFqNAj6riU1m2hfA883BVdA) and my [Instagram Account](https://www.instagram.com/the_fundamental_theor3m/) for awesome Mathematical content!
