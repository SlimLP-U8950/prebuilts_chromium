# prebuilts_chromium
* Chromuim files
* This adds a chromium_prebuilt function to envsetup.sh that is invoked by lunch to check
whether the chromium prebuilts are up-to-date or not. If not, it will be built from source
and then the new source built version will be pulled during brunch/mka bacon to become the
new prebuilts for future builds.
