# NX606J_BloatRemover
Remove bloatware apps with a simple shell script

## WARNING: USE AT YOUR OWN RISK! I AM NOT RESPONSIBLE FOR ANY DAMAGE TO YOUR DEVICE
## IF ANYTHING SHOULD BREAK, PLEASE SUBMIT AN ISSUE AND I'LL FIX IT AS SOON AS POSSIBLE

### WHAT DOES THIS SCRIPT DO?
This script will remove all the preinstalled Chinese apps on the nubia Z18 and leave you with a bare minimum of services installed that are needed for all functions to work properly.

Because it's removing the default launcher, it will also try to install the following APKs:

#### Lawnchair ([source](https://github.com/LawnchairLauncher/Lawnchair/releases))
#### FDroid ([Source](https://gitlab.com/fdroid/fdroidclient/tags))
#### App Inspector ([Google Play](https://play.google.com/store/apps/details?id=com.ubqsoft.sec01&hl=en))

### HOW DO I REINSTALL THE DELETED APPS?
There's currently no way to reinstall them included, simply because I don't think there's any need for them.
If you feel like something's missing, feel free to extract the apks and submit a PR with a proposed fix
I can help with how to extract them if you need assistance.
If you DO need to get them back, the only way is a factory reset (maybe wiping cache only works as well)

### DO I NEED TO REMOVE ALL OF THE APPS? I WANT TO KEEP X/Y INSTALLED
No, you can leave some apps installed. However it's a bit more difficult than I wish it was..
You need to edit the bash script manually and comment the corresponding line so the script won't delete it.


### CAN I CONTRIBUTE?
**OF COURSE!** If you feel like something is missing or see a better way of removing the apps, feel free to propose a change by doing a PR.
