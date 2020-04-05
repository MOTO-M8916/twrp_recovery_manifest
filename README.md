## Getting Started ##
---------------

To initialize your local repository using the OmniROM trees, use a command like this:

    repo init -u git://MOTO-M8916/twrp_recovery_manifest.git -b android-7.1

Then to sync up:

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

Then to build:

     cd twrp && . build/envsetup.sh && brunch <code_name>



