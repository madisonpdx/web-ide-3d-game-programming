Introduction
------------

So far we've used Sublime Text 2 and ICEcoder to write our code. Both of these tools have a lot of useful features, but
they also have one big drawback which is that they save all your code files on the computer you are working on. This
means that unless you are at the same computer, you have to start from scratch each time you work on your code. Today
we are going to start using a tool that stores all your code on the internet, so you can work on your code anywhere that
you have a computer and an internet connection.

Web IDE
-------

The tool we are going to use is a web based IDE called Koding.com. IDE stands for Integrated Development Environment,
which is a common term used to describe all sorts of different advanced code writing tools. Basically an IDE is a
fancy text editor. An IDE can be an application that runs on your computer, or in this case it can run in a web browser
which means that you can access it wherever you are.


Koding.com
----------

The first thing you need to do is go to Koding.com and create an account. You can do this right from the home page by
entering your email, choosing a username, and clicking the sign up button. Once you are registered click the red icon
in the top menu that looks like a notepad. This switches you to your code editor view. I setup a project
structure so that you can dive right into lessons from the 3D Programming book. To get the project I setup into your
editor you will need to clone a repository from GitHub. Keep reading for instructions on how to do that.

Cloning the Sample Project
--------------------------

In the top menu of Koding.com select the green icon that looks like a command line.

```
cd Web
```

This switches you into the web folder, which is a good place on Koding.com to store any web pages you are building.

```
git clone https://github.com/madisonpdx/web-ide-3d-game-programming.git
```

This connects to GitHub and clones (creates a copy) of the project I setup for you to start with.

Coding and Testing Changes
--------------------------

Now that you cloned the sample project you are ready to start coding. Switch back to your code editor by clicking the
red notepad icon. Double click the Web folder, then double click the folder named web-ide-3d-game-programming to expand
the sample project. Double click index.html to open it in your code editor. Then right click index.html and select
'Public URL' and then select the address and copy it. Open a new browser tab, paste in the address and hit enter to load 
the page. This is a good workflow that you can use. In one browser tab you
have your code editor and in another tab you have the web page with the running code. After you modify your code
switch over to the tab with the running code and refresh to see the changes.