<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# NPM Version Fix

Having problems with your current version of NPM? Getting some funky errors? Well look no further because this guide will get you set up with a different version of NPM.

## Step 1
Open your terminal and navigate to your home directory. NPM allows you to install any previously released versions with a few simple commands. To see a list of available versions to install, type out ```npm view npm versions --json```. You want to be very careful with which version you are installing.

## Step 2
Type into your terminal ```npm i -g npm@5.3``` or whichever version you are wanting to install.

NOTE: If you get an ```npm ERR! code EACCES``` error, [follow these simple steps](https://docs.npmjs.com/getting-started/fixing-npm-permissions) to change ownership of the directory holding Node.

Type ```npm -v``` into the terminal to verify installation of the correct version of NPM.

You should now see ```v5.3``` or whichever version you installed in your terminal.

Happy coding!

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
