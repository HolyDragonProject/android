## Getting Started ##
---------------

To get started with OmniDragon, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OmniDragon trees, use a command like this:

    repo init -u https://gitlab.com/holydragonproject/android.git -b hdo

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>


Good luck!
