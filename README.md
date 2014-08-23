Bluebird Glx-Dock Theme
=======================================================================

**Sometimes even little things can make a difference. With the Bluebird theme for Glx-Dock you can add that little something to your professional Linux desktop, which makes it even more useful and enjoyable.**

*Bluebird theme for Glx-Dock (aka Cairo-Dock) has been carefully designed to address the best of many worlds:

*The desktop clarity and simplicity offered by the Bluebird desktop theme

*The consistent and strong associations between functions and their graphical representations, polished by the Faenza icon theme

*The unobtrusive flexibility of the Glx-Dock

and bridge them together in a consistent manner.

![Screenshot of an XFCE desktop with the Bluebird theme and Glx-Dock](screenshot.png)

Of course, one could look at this README also from a completely different standpoint. You might be asking:

*Now that I have found a promising piece of software in the vast ocean of free open source, how do I take advantage of it?

*How do I keep that software updated, since it is not (ever going to be) included my OS updates?

*What will happen if this software project gets abandoned? Can I continue to get bug fixes and new features from somewhere else?

*Now that I have used and poked around that software a bit, I may have discovered and fixed some bugs, or even made the software better. And if it is perfectly fine to keep all that for myself, how could I eventually share what I have done with friends, colleagues or the rest of the world?

*And ultimately, if the software I have found proves to be not what I have been looking for, how can I safely get rid of it?

Clearly, innocent-looking questions like these have no simple answers. In fact, they reflect on complex topics like software development life cycle, asynchronous workflow, version control, systems integration etc., each covered extensively elsewhere.

What this README aims however, is to look at the questions above as a whole and provide some of the essential answers in a neat and simple (but in no way simplistic) manner. Therefore, this README can be also thought of as a short, hands-on, end-user survival guide to the world of open source.

#Table of contents

#Prerequisites

*NIX OS with a desktop environment

Glx-Dock version 3.0.0 or newer

http://glx-dock.org/

Bluebird desktop theme by the Shimmer Project

http://shimmerproject.org/project/bluebird/

Faenza icon theme by thieum

http://tiheum.deviantart.com/art/Faenza-Icons-173323228

Git core client

http://git-scm.com/downloads

Most probably the majority of the software and artwork referenced above is already available through your OS distribution channels. The URLs are provided for your convenience, whether you choose to look for any newer versions.

#Install

Once the prerequisites above are met, in order to install the Bluebird theme in Glx-Dock, execute the folowwing statement in Terminal:

git clone https://github.com/bogomirov/glx-dock-bluebird-theme.git ~/.config/cairo-dock/themes/Bluebird

Note that installing the theme does not immediately affect the appearance of Glx-Dock. In order to actually use the theme, you should apply it through the Glx-Dock Theme Manager.

#Upgrade

Once installed by following the step above, the Bluebird Glx-Dock theme can be upgraded by executing the following statements in Terminal:

1. Switch to the Bluebird Glx-Dock theme folder:

cd ~/.config/cairo-dock/themes/Bluebird

2. Upgrade the theme with the latest changes from the GitGub repo:

git pull origin master

Note that upgrading the theme this way does not immediately affect the appearance of Glx-Dock. In order to actually use the new version you should re-apply the theme through the Glx-Dock Theme Manager.

#Contribute

Create an account with GitHub

Make sure your local installation of Git is configured properly

https://help.github.com/articles/set-up-git#setting-up-git


On GitHub, fork the Bluebird Glx-Dock repo to your account:

Navigate to the octocat/Spoon-Knife repository.
In the top-right corner of the page, click Fork.



On GitHub, navigate to your fork of the Spoon-Knife repository

In the right sidebar of your fork's repository page, copy in clipboard the HTTPS clone URL of your fork. 

Open Terminal and switch to the location of the previously installed Bluebird Glx-Dock Theme:

cd ~/.config/cairo-dock/themes/Bluebird

see the currently configured remote repository 

git remote -v

The result should be:

origin  https://github.com/bogomirov/glx-dock-bluebird-theme.git (fetch)
origin  https://github.com/bogomirov/glx-dock-bluebird-theme.git (push)

Change the origin URL with the URL of your fork:

git remote set-url origin paste-the-URL-of-your-fork-here


Verify your fork URL is properly configured

git remote -v

and the result should be:

origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)

where YOUR_USERNAME is your GitHub username, and YOUR_FORK is the name of your Bluebird theme repo.

If you haven't done already so, make changes to the appearance of Glx-Dock and export them by overwriting the Bluebird theme through the Theme Manager

Store the changes of the Bluebird theme in the clone of your fork. Open Terminal and execute the following statements:

cd ~/.config/cairo-dock/themes/Bluebird

git add .

git commit -m "Describe the changes you have done to the Bluebird theme here"

Publish your changes of the Bluebird Glx-Dock theme by sending them back to your fork on Github:

git push origin master

Initiate a pull request, so your changes can be incorporated in the original theme:

Open the web browser and navigate to your fork on GitHub

Press the "Pull request" link

Enter a message describing your proposed changes

Press the "Create Pull request" button


#Uninstall/Remove

To uninstall the Bluebird theme from the Glx-Dock Theme Manager, open Terminal and execute:

rm -rf ~/.config/cairo-dock/themes/Bluebird

Note that removing the theme grom the Glx-Dock Theme Manager does not alter the current appearance of Glx-Dock. In order to do so, you should either select another theme or alter the appearance/configuration of Glx-Dock manually.

#Issues

#Credits

This theme utilizes code and/or artwork from the following sources:

The Glx-Dock project

http://glx-dock.org/

Faenza icon theme by thieum

http://tiheum.deviantart.com/art/Faenza-Icons-173323228

Faience icon theme by thieum

http://tiheum.deviantart.com/art/Faience-icon-theme-255099649

Xfce4.8 Panel BGs 1920x28 by kazu-spara

http://kazu-spara.deviantart.com/art/Xfce4-8-Panel-BGs-1920x28-267098524

#Legal notice

Copyright on the project concept, theme design, the specific Glx-Dock configuration and some of the digital artwork &copy; Bogomir Bogomirov, 2014.

This project is distributed under GPL version 3. See [LICENSE](LICENSE) file for details.
