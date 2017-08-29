# Package Management on TFS

You no longer need to manage legacy on-prem file shares or host private package servers. We’ll host, index, and manage your packages seamlessly in the cloud right alongside your source code, builds, and releases.

## Install

To add `Package Management` to your TFS, go to the [Marketplace](https://marketplace.visualstudio.com/items?itemName=ms.feed) and click install. Once you've successfully installed `Package Management` you should be able to navigate to `Packages` under the `Build & Release` tab.

![](https://raw.githubusercontent.com/barend-erasmus/package-management-on-tfs/master/screenshots/menu.PNG)

## Configure

Once you navigated to the `Packages` section, you should see the following.

![](https://raw.githubusercontent.com/barend-erasmus/package-management-on-tfs/master/screenshots/modal-3.PNG)

Click on the `New Feed` button and a modal will appear.

![](https://github.com/barend-erasmus/package-management-on-tfs/raw/master/screenshots/modal-4.PNG)

Enter a feed name, description and click the `Create` button.

After you've clicked the `Create` button a page should appear where there is a `Connect to Feed` button in the left-upper corner.

![](https://github.com/barend-erasmus/package-management-on-tfs/raw/master/screenshots/connect-to-feed.PNG)

Click on the `Connect to Feed` button and a modal will appear.

![](https://github.com/barend-erasmus/package-management-on-tfs/raw/master/screenshots/modal.PNG)

On the left of the modal there are three sections called `NuGet`, `npm`, `Maven`.

You can click on either of these sections and the corresponding details should appear.

## Publish (npm)