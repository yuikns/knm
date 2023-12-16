# Koji NISHIDA Modified

The google theme [Koji NISHIDA](https://chrome.google.com/webstore/detail/koji-nishida/acganlmcjehnfmehkmlimgkaloifodlf) was my favorite theme. However, with the upgrading of the chrome, the UI framework of chrome is changing, which leads the images becoming strange.

It seems like the author has no plan to fix the issue, I make a simple fix for this theme.

**The copyright belongs to the original author.**

## What was changed

Since the key issue is the height of the toolbar and tabs of the new Chrome were changed. I copied the resource from the extension folder, and then I manually modified the image for "theme_toolbar" to make the new image meet the new UI layout. Besides, I renamed the image names to let us recognize the images easily.

## How to use it

I have already prepared a packaged file for you.

Please visit [the release page](https://github.com/yuikns/knm/releases), and download the latest `knm.crx` file.

After you get the .crx file, you can visit the extensions manage page (as for me, I will type `chrome://extensions` on my address bar), and then drag & drop the `knm.crx` onto the page.


As an alternative solution, you can also load the pack directly.

Please download this repository first, and then visit extensions management page in your chome, turn the `developer mode` on on top right. You should find a new tab on the top.

Click the first buttion `Load unpackaged`, and choose the source folder. You will also get this modified theme.

## References

+ [What are themes?](https://developer.chrome.com/docs/extensions/develop/ui/themes)
+ [Install and manage extensions](https://support.google.com/chrome_webstore/answer/2664769)
+ Related manifest keys:
    + `images`: [kPersistingImages](https://source.chromium.org/search/?q=file:chrome/browser/themes%20symbol:kPersistingImages$)
    + `properties` [kDisplayProperties](https://source.chromium.org/search/?q=file:chrome/browser/themes%20symbol:kDisplayProperties$)
    + `tints` [kTintTable](https://source.chromium.org/search/?q=file:chrome/browser/themes%20symbol:kTintTable$)
    + `colors` [kOverwritableColorTable](https://source.chromium.org/search/?q=file:chrome/browser/themes%20symbol:kOverwritableColorTable$)
