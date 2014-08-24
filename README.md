Bluebird Glx-Dock Theme
=======================================================================

**Sometimes even little things can make a difference. With the Bluebird theme for Glx-Dock you can add a little punch to your professional Linux desktop, that makes it even more useful and enjoyable.**

Bluebird theme for Glx-Dock (aka Cairo-Dock) has been carefully designed to bridge the best of many worlds:

*The desktop clarity and simplicity offered by the Bluebird desktop theme

*The consistent and strong associations between functions and their graphical representations, polished by the Faenza icon theme

*The unobtrusive flexibility of the Glx-Dock

and bring them together in a consistent manner.

![Screenshot of an XFCE desktop with the Bluebird theme and Glx-Dock](screenshot.png)

Of course, one could look at this README also from a completely different standpoint. You might be asking:

*Now that I have found a promising piece of software in that vast ocean of free open source, how do I take advantage of it?

*How do I keep that software updated, since it is not (ever going to be) included my OS updates?

*What will happen if this software project gets abandoned? Can I continue to get bug fixes and new features from somewhere else?

*Now that I have used and poked around that software a bit, I may have discovered and fixed few bugs, or even made the software better. And if it is perfectly fine to keep all that for myself, how could I eventually share what I have done with friends, colleagues or the rest of the world?

*And ultimately, if the software I have found proves to be not what I have been looking for, how can I safely get rid of it?

Clearly, questions like these have no simple answers. In fact, they reflect on complex topics like software development life cycle, asynchronous workflow, version control, systems integration etc., each covered extensively elsewhere.

What this README aims however, is to look at the questions above as a whole and provide some of the essential answers in a neat and simple (but in no way simplistic) manner. Therefore, you can think of this README as a short, hands-on end-user survival guide to the world of open source.

#Table of contents

1. Prerequisites

2. Install

3. Upgrade

4. Making changes

5. Contribute

6. Uninstall

7. Final words

8. Credits

9. Legal notice

#Prerequisites

To achieve the effect intended by this theme, you will need the following free software and artwork installed and configured:

-*NIX OS with a desktop environment

-Glx-Dock version 3.0.0 or newer

http://glx-dock.org/

-Bluebird desktop theme by the Shimmer Project

http://shimmerproject.org/project/bluebird/

-Faenza icon theme by thieum

http://tiheum.deviantart.com/art/Faenza-Icons-173323228

-(optionally) Faience Azur icon theme distributed together with the Faience icon theme by thieum

http://tiheum.deviantart.com/art/Faience-icon-theme-255099649

-Git core client

http://git-scm.com/downloads

Most probably the majority of the items referenced above is already available through your *NIX OS distribution channels. The URLs are provided for your convenience, whether you choose to look for any newer versions.

#Install

Once the prerequisites above are met, in order to install the Bluebird theme for Glx-Dock, open Terminal and execute the following statement:

git clone https://github.com/bogomirov/glx-dock-bluebird-theme.git ~/.config/cairo-dock/themes/Bluebird

Note that installing the theme does not immediately affect the appearance of Glx-Dock. In order to actually use the theme, you should apply it through the Glx-Dock Theme Manager.

#Upgrade

Once installed by completing the step above, the Bluebird Glx-Dock theme can be upgraded by executing the following statements in Terminal:

1. Switch to the folder where the Bluebird Glx-Dock is installed:

cd ~/.config/cairo-dock/themes/Bluebird

2. Upgrade the theme with the latest changes from the GitGub repo:

git pull origin master

Note that upgrading the theme this way does not immediately affect the appearance of Glx-Dock. In order to actually use the new version, you should re-apply the theme through the Glx-Dock Theme Manager.

#Making changes

Making changes to your local copy of the Bluebird Glx-Dock theme is pretty straightforward. Just alter the appearance and behavior of Glx-Dock through its configuration panel and export the changes overwriting the Bluebird theme through the Theme Manager.

Now, there are two main issues to deal with here:

1. What will happen with the original Bluebird theme you have installed when you manually overwrite it? What will happen with your previous changes if you make other changes tomorrow, or in the day after?

2. What will happen with your changes to the Bluebird theme you have made so far, when you upgrade the theme, as described above? Are they lost? Which settings will take precedence? Is there a way you can somehow merge your changes with the changes made in the original theme?

All these issues have their elegant solutions with just few keystrokes. Nothing can be lost, and you would need not to do again work you have done already. Solutions like these however require deeper understanding of commits, branching and merging, which are beyond the scope of this README. But you can always refer for more information in the free on-line book about Git: http://git-scm.com/book

For the sake of simplicity however, you can always update your theme first and then manually re-apply any previous changes.

#Contribute

Now that you have made modifications to your local copy of the Bluebird theme, you might want to share them with the world. This would require dealing with the following issues:

*Deciding where the on-line copy of the locally modified Bluebird theme will be hosted. This README assumes that you will use GitHub as an on-line provider. This means you have to open your own account on GitHub.

*Forking the original Bluebird Glx-Dock theme repository to your account

https://help.github.com/articles/fork-a-repo#fork-an-example-repository

*Configuring your Git client to be able to send updates on-line:

https://help.github.com/articles/set-up-git#setting-up-git

*Configuring your local copy of the Bluebird Glx-Dock theme so your modifications can be sent online, but also to incorporate updates and bug fixes from the original repository when needed

https://help.github.com/articles/fork-a-repo#step-3-configure-git-to-sync-your-fork-with-the-original-spoon-knife-repository

Note here that at step 5 in the on-line manual your origin will be the URL of the original repository, not yours. Therefore you should rename your origin to upstream:

https://help.github.com/articles/renaming-a-remote

and add as origin the URL of your online fork

https://help.github.com/articles/adding-a-remote

*Now you can publish the changes you have made of the theme online, any time

*A final and optional step could be to initiate a pull request, so your changes can be incorporated in the original theme

https://help.github.com/articles/creating-a-pull-request

#Uninstall

To uninstall the Bluebird theme from the Glx-Dock Theme Manager, open Terminal and execute:

rm -rf ~/.config/cairo-dock/themes/Bluebird

Note that removing the theme from the Glx-Dock Theme Manager does not alter the current appearance of Glx-Dock. In order to do so, you should either select another theme or alter the appearance/configuration of Glx-Dock manually.

Furthermore, removing the theme will irrecoverably delete all modifications you have made to it in the past, unless you keep an archive of your work elsewhere, e.g. by sharing it online.

#Final words

This README has been written having the general end-user in mind, and not only the software developer, as most of the version control guides do. That is why the workflow followed here is different. This README also looks at the big picture. Whether you have found online other software to use, write a book, an article or produce other kinds of digital media, use other version control systems like Subversion or collaborate on a closed-source project on the corporate intranet, the workflow you can follow is almost the same. Namely, to achieve faster, better results with less burden.

#Credits

This theme utilizes code and/or artwork from the following sources:

The Glx-Dock project

http://glx-dock.org/

Faenza icon theme by thieum

http://tiheum.deviantart.com/art/Faenza-Icons-173323228

Faience icon theme by thieum

http://tiheum.deviantart.com/art/Faience-icon-theme-255099649

Faenza-Xfce icon theme by the Shimmer project

https://github.com/shimmerproject/Faenza-Xfce

Xfce4.8 Panel BGs 1920x28 by kazu-spara

http://kazu-spara.deviantart.com/art/Xfce4-8-Panel-BGs-1920x28-267098524

#Legal notice

Copyright on the project concept, theme design, the specific Glx-Dock configuration and some of the digital artwork &copy; Bogomir Bogomirov, 2014.

This project is distributed under GPL version 3. See [LICENSE](LICENSE) file for details.
