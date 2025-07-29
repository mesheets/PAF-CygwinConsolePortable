# PortableApps.com Packaging for Cygwin Console
A [PortableApps.com](https://portableapps.com/) package bundler for the Cygwin Console project.

## Packaging Steps
1. Copy icons and icon images to .\App\AppInfo
2. Create a .\Help.html file, with file dependencies under .\Other\Help
3. Copy the app distribution itself to .\App\Normalize
4. Create the PortableApps.com configuration files
   1. .\App\AppInfo\AppInfo.ini
   2. .\App\AppInfo\Launcher\NormalizePortable.ini
5. Run the PortableApps.com Launcher to create the portable app launcher
6. Capture desired default configuration from folder Data and copy to App\DefaultData
7. Run the PortableApps.com Installer to create the portable app installer
