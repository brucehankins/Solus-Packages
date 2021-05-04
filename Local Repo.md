# Creating a local repository 
More detailed and better information can be found in the Solus Help section. This is just a extremely basic set of commands and should be used at your own risk.
You'll need to replace *user* and *Repo Directory* with your own unique fields. This is not a copy/paste set of commands and will not work out well for you if you try that.
The commands listed here are for use with Solus only. Again, at your own risk.

* Create the local repo
  * $ mkdir ../../*Repo Directory*
    * Make sure to copy or move the local package files (.eopkg) files to this new directory before jndexing
* Index the packages in your custom local repo
  * $ sudo eopkg index -o /home/*user*/*Repo Directory*/eopkg-index.xml --skip-signing /home/*user*/*Repo Directory*
* Add your custom local repo
  * $ sudo eopkg ar *Repo Directory* /home/*user*/*Repo Directory*/eopkg-index.xml.xz
* View active repositories, make sure you see your local repo in the output
  * $ sudo eopkg lr

This will get you going...it does not set priority of the repositories being used or any of the more detailed tasks that you may want to do. It will only index the .eopkg files you'e added to the repository directory and make it available to install those files from you're local repository via software center or *sudo eopkg it package name*.

***Again, do this at your own risk. This is not a official source of information or packages, it may break your system. You are aware of this and take full responsibility for any and all issues that may arise from following these instructions or using packages from this github repository***
