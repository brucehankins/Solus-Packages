# Solus-Packages
The pupose of this github is to learn how to use git, improve CLI ability, and learn packaging for Solus.
All code hosted on this page will be pulled from other sources that fall under opensource and have opensource licenses attached to them. I am not a programmer, so no changes to source code will be made
This is solely to learn to repackage software I find useful that is not currently available through snap, flatpak, or on in the Solus repos into a .eopkg for use on a local repository. Licensing is directly related to the source code used to compile each package and can be found in the package directory.
Any feedback is welcome, if you have any tips or tricks please let me know!

## Package Files
After further consideration, I've decided to include the .eopkg files that I create into this repository. A few considerations to note:

* This repository and packages included should not be used for package inclusion requests for Solus or any other distribution
  * For package inclusion requests, use the source code linked in each package readme.md or the package.yml file
* .eopkg files hosted here will not utilize Github's release framework
  * .eopkg files will added to the corresponding directory for that package
  * There will be directories for each version, ex. */Package/Package 1.1*
    * Updates will require that you download/save the latest version (*if available*) of the package and index/install through your own local repo
* The packages hosted here are solely to make it easier for myself or others to build their own *local repository*
* It is not recommended to use this as a primary source for your packages. Always use the repos recommended by your distribution or other trusted channels such as Flatpak as your primary source
    * Think of this more as a testing/at your own risk source if you choose to use packages found here

Bruce Hankins
@brucehankins_ on twitter 
Telegram @brucehankins https://t.me/brucehankins
