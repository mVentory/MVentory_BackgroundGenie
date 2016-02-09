# BackGround Genie
### Links Magento to a shared Dropbox folder for background removal and other image editing

Watch a demo on http://mventory.com/photo-background-remover/

![](http://mventory.com/wp-content/uploads/2015/01/magento-photo-editor.png)

## Installation

1. Install mVentory API extension
2. Install this extension
3. Create a new Dropbox account
4. Create a new application in Dropbox
5. Paste the credentials into Background Genie

The extension has access to the entire Dropbox account, so we recommend setting up a separate account just for this purpose.

Most of the users will fall under Dropbox's free offer.

You can create a folder within your Dropbox account and include it in the configuration path or work in the root of the account.

## File processing

When a new photo is take with the phone it adds the file to Dropbox and any users linked to the shared folder will get a notification about a new file being added. Install Dropbox desktop client to get timely notifcations on your desktop.

Open a file, edit, save. Every time a file is saved it fires up an event in Magento to grab the edited file and update it inside Magento.

The original files are backed up in a folder on Magento and can be restored by copying them to `media` folder.

## License

Creative Commons - [BY-NC-ND-4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/#)

The license allows any non-commercial use. A waiver for commercial use is available from [mVentory licensing](http://mventory.com/licensing/) page.

## Contributions

Please, make a pull request with necessary comments on what has been changed and why, including any specific use cases.




