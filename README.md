[![Alt text](http://s14.postimg.org/a1yhsqbe9/BLACKBOX.png)](http://www.blackbox-os.gq)
# BlackBox-OS [Platform Manifest]
###### Let's get started with your build for BlackBox-OS. The branch you are looking at is 5.1 lollipop branch, if you are looking to build a different version of blackbox change the branch from the top left corner.

Getting Started
---------------
To get started with the BlackBox-Project sources, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/version-control.html).

Creating Directories
---------------
You will need to set up some directories in your build environment.

To create them run:

    mkdir ~/blackbox


Syncing Sources
---------------
Next step is to sync the sources so that you can get started with your geeky lifestyle. Run the following code in the terminal window.

    repo init -u git://github.com/SOKP/platform_manifest.git -b sokp-l5.1
    &&
    repo sync -f

The first code will initialize the repo and the second command will start syncing the project. (Grab yourself some coffee, coz its gonna take some time)


Time To Build The ROM
-------------------
Initialize the environment with the envsetup.sh script. Note that replacing "source" with a single dot saves a few characters, and the short form is more commonly used in documentation.

    . build/envsetup.sh
    brunch [Codename] (Codename is the Codename of your device -_-)

Codename examples, Nexus 5- Hammerhead. Nexus 6- Shamu. OnePlus One- Bacon.

**Device isn't supported? Not a problem! Contact US
