## FREQUENTLY ASKED QUESTIONS
1. [How can i get into my projects terminal?][1]
2. [How to install packages?][2]
3. [How to install system libraries?][3]
4. [How to connect my project to GIT repository?][4]
4a. [How to connect my project with GitHub?][4a]
5. [I'm out of funds and cannot access my project, what to do??][5]
6. [How can i publish my project and what does it involve?][6]
7. [How can i upload files to my project?][7]
8. [How can i contact you?][8]

### 1. How can i get into my projects terminal?

To get access to the terminal simply click the _Open terminal_ button.

![Open terminal](/images/terminal.png)

Copy your password to clipboard by clicking the button.

![Copy password](/images/terminal1.png)

Type `project` as username

![Username](/images/terminal2.png)

Paste your password by pressing <kbd>Ctrl</kbd> + <kbd>Shift</kbd> +  <kbd>V</kbd> simultaneously and submit it with <kbd>Enter</kbd>. The password won't be visible.

![Password](/images/terminal3.png)



### 2. How to install packages?

The easiest way to install a package is by clicking the _Packages_ button in upper-right corner of the main view of your project. 

![Packages button](/images/packages.png)

Then you just need to write the name of the package you'd wish to install in the field in the bottom of the window that has showed up and click _Install_. 

![Packages install](/images/packages2.png)


You could do this via Interactive Console or [terminal][1] as well. Depending on language it would be 
- **Python** (`!pip3` for Python3)
```
!pip install <package_name>
``` 
- **Julia**
```
Pkg.add("<package_name>")
```
- **R**
```
install.packages("<package_name>")
```
- **Octave**
```
pkg install <package_name>
```



### 3. How to install system libraries?

The easiest way to do that is by logging in to the terminal and then simply typing in 

```sh
> sudo apt-get install -y <package_name> <other_package_name>
```


However, you could do that from the Interactive Console as well by typing in acordingly 
- **Python** or **Octave**
```python
!sudo apt-get install -y <package_name>
```
- **Julia** - *mind the backticks (grave accents)!*
```julia
Base.run(`sudo apt-get install -y <package_name> <other_package_name>`)
``` 
- **R**
```R
system("sudo apt-get install -y <package_name> <other_package_name>")
```



### 4. How to connect my project to GIT repository?

You can do it by typing in 
```sh
git init
git remote add origin <url-to-your-repository>
``` 
into the [terminal][1] or [Interactive Cosnole][3].

In case if you want to create a new repository type:
```sh
git checkout -b master
git add README.md
git push
```

Otherwise just pull all the data:
```sh
git fetch && git pull
```


#### 4a. How to connect my project with GitHub?

We have prepared a video explaining the whole process step-by-step. 
<a href="#" onclick="show_video()">How to put your PLON project on GitHub?</a>
<div id="video_container"></div>




### 5. I'm out of funds and cannot access my project, what to do??

Free accounts funds are renewed monthly. The credits are added automatically every month after creating an account. 

In case you would like to access your project and files earlier, you can always add funds to your account by visiting [billing](https://app.plon.io/dashboard/billing) page.

![Billing page](/images/billing.png)




### 6. How can i publish my project and what does it involve?

You can now publish your project by simply clicking the _Publish_ button in the upper-right corner of IDE, or in the Dashboard by clicking the Publish Project icon. 

![Publish project](/images/publish.png)

If you don't want your project to be shown and be accessible from the public [Explore](https://plon.io/explore) area, you can simply check the _Private_ option. 

![Private](/images/publish1.png)

You will then get a direct link to your project which you can later share.




### 7. How can i upload files to my project?

After opening your project you can simply **drag & drop** files from your computer to the workspace folder which is shown on the left of the IDE.

![File upload gif](/images/file_upload.gif)




### 8. How can i contact you?

The easiest way to do this is sending us an e-mail to [support@plon.io](support@plon.io),
contact us directly by Messenger on our [Facebook page](https://www.facebook.com/plonsci) or 
the built-in chat on [plon.io](https://plon.io) in the lower-right corner of the page. 

![chat](/images/chat.png) 


## Meet us!
- For important notices and announcements you can visit our [Facebook page](https://www.facebook.com/plonsci). 
- If you're interested in our workflow and some thoughts on machine-learning and software house management, visit our [blog](http://ermlab.com/blog/).
- You will find more videos on using [*plon.io*](https://plon.io/) and it's various features on our [YouTube channel](https://www.youtube.com/channel/UCgXErw2D2ZarzNybmlYRYTA).
- For most recent news and interesting projects visit out [Twitter](https://twitter.com/plon_io).


[1]:#1-how-can-i-get-into-my-projects-terminal
[2]:#2-how-to-install-packages
[3]:#3-how-to-install-system-libraries
[4]:#4-how-to-connect-my-project-to-git-repository
[4a]:#4a-how-to-connect-my-project-with-github
[5]:#5-im-out-of-funds-and-cannot-access-my-project-what-to-do
[6]:#6-how-can-i-publish-my-project-and-what-does-it-involve
[7]:#7-how-can-i-upload-files-to-my-project
[8]:#8-how-can-i-contact-you
