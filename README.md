## FREQUENTLY ASKED QUESTIONS


### 1. How to install packages?

The easiest way to install a package is by clicking the _Packages_ button in upper-right corner of the main view of your project. 
Then you just need to write the name of the package you'd wish to install in the field in the bottom of the window that has showed up and click _install_. 
You could do this via console or terminal as well. Depending on language it would be 
- `!pip install <package_name>` for **Python** (!pip3 for Python3), 
- `Pkg.add("<package_name>")` for **Julia**, 
- `install.packages("<package_name>")` for **R**,
- `pkg install <package_name>` for **Octave**.


### 2. How to install system libraries?

The easiest way to do that is by logging in to the terminal and then simply typing in `sudo apt-get install <package_name> <other_package_name>`. 
However, you could do that from the Interactive Console as well by typing in acordingly 
- `!sudo apt-get install <package_name>` if using **Python** or **Octave**, 
- ```Base.run(`sudo apt-get install <package_name> <other_package_name>`)``` (**Mind the grave accents!**) for **Julia**,
- `system("sudo apt-get install <package_name> <other_package_name>")` for **R**.


### 3. How to connect my project to GIT repository?

You can do it by typing in `git init; git remote add origin <url-to-your-repository>`. 
As said in the question 2., you can do it by typing in the commands in the terminal or Interactive Cosnole.


#### 3a. How to connect my project with GitHub?

We have prepared a video explaining the whole process step-by-step. 
[How to put your PLON project on GitHub?](https://www.youtube.com/watch?v=FmFIYYGKeXc)


### 4. I'm out of funds and cannot access my project, what to do??

Free accounts funds are renewed monthly.


### 5. How can i publish my project and what does it involve?

You can now publish your project by simply clicking the _Publish_ button in the upper-right corner of IDE, or in the Dashboard where all your projects are listed by clicking the Publish Project icon. 
If you don't want your project to be shown and be accessible from the public _Explore_ area, you can simply check the _Private_ option. 
You will then get a direct link to your project which you can share.


### 6. How can i contact you?

The easiest way to do this is sending us an e-mail to [support@plon.io](support@plon.io), or 
contact us directly by Messenger on our [Facebook page](https://www.facebook.com/plonsci) or 
the built-in chat on [plon.io](https://plon.io) in the lower-right corner of the page. 


### 7. How can i upload files to my project?

After opening your project you can simply **drag&drop** files from your computer to the workspace folder which is shown on the left of the IDE.

# Meet us!
- For important notices and announcements you can visit our [Facebook page](https://www.facebook.com/plonsci). 
- If you're interested in our workflow and some thoughts on machine-learning and software house management, visit our [blog](http://ermlab.com/blog/).
- You will find more videos on using *plon.io* and it's different features on our [YouTube channel](https://www.youtube.com/channel/UCgXErw2D2ZarzNybmlYRYTA).
- For most recent news and interesting projects visit out [Twitter](https://twitter.com/plon_io).
