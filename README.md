# Koji NISHIDA Modified

The google theme [Koji NISHIDA](https://chrome.google.com/webstore/detail/koji-nishida/acganlmcjehnfmehkmlimgkaloifodlf) was my favorite theme. However, with the upgrading of the chrome, the UI framework of chrome is changing, which leads the images becoming strange.

It seems like the author has no plan to fix the issue, I make a simple fix for this theme.

## What was changed

I copied the resource from `$HOME/Library/Application Support/Google/Chrome/Default/Extensions/acganlmcjehnfmehkmlimgkaloifodlf`, and updated the image for `theme_toolbar`. The key problem is the height of the toolbar and tabs are changed. I manually modified the image to make the new image match the current UI layout.


## How to use it

I have already prepared a packaged file for you.

Please visit [the release page](https://github.com/yuikns/knm/releases), and download the latest `knm.crx` file.

After you get the .crx file, you can visit <chrome://extensions/>, and then drag & drop the `knm.crx` onto the page.


As an alternative solution, you can also load the pack directly.

Please download this repository first, and then visit <chrome://extensions/> in your chome, turn the `developer mode` on on top right. You should find a new tab on the top.

Click the first buttion `Load unpackaged`, and choose the source folder. You will also get this modified theme.


## References

+ [Google Chrome Theme Tutorial](https://sites.google.com/site/gsugsa/google-apps/google-chrome/how-to-create-a-theme)

