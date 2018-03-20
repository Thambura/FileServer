To set up a new radio, do the following:
----------------------------------------
1. Download the file server package zip file
2. As the package is based on .NET framework 4.6.1, you need to set up IIS in your windows platform and host it. If you have a hosting plan with any of the cloud providers, you can host the downloaded package. Or, if you manage your own servers, you can set up IIS by following the instructions mentioned here:
[Windows Vista and 7](https://docs.microsoft.com/en-us/iis/install/installing-iis-7/installing-iis-on-windows-vista-and-windows-7)
[Windows 8 and 10](https://www.howtogeek.com/112455/how-to-install-iis-8-on-windows-8/)
**Note**: Pretty soon file server based on .NET Core and NodeJS will be released, and thus you will be able to host it in Linux and Mac too.
3. After hosting the package, grant write permission to the App_Data folder for the app pool account.
4. Copy your songs collection into the Songs folder inside App_Data.
5. Try to access the website from your browser and if everything is set up properly, you will see this message - "Thambura FileServer"
6. Open the port the website is running on in your Firewall and in your router, so that it's accessible from the internet. 
**Note**: Pretty soon local hosting will be supported too.
7. Navigate to [https://www.thambura.com](https://www.thambura.com) and log in using Facebook or Google
**Note**: Pretty soon other social network accounts and custom registration will be supported.
8. Add your radio name and your radio's file server location from here
9. After adding your radio, your songs' MP3 metadata information will get synced in our database in ten minutes or so. Currently, we don't support modifying the synced information; so, please update the MP3 metadata using any MP3 tag editors.

If you want to try our file servers for the next 3 months for completely free of charge OR if you run into any problems in the fileserver setup, please contact us by sending an email to contact@thambura.com after adding your radio information.
