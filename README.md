PortableApps.com Format Packaging for Cygwin Console
====================================================
A [PortableApps.com](https://portableapps.com/) package bundler for the Cygwin Console project,
which is an edition of the [PortableApps.com Console Portable project](https://portableapps.com/apps/utilities/console_portable)
that has been specifically configured for a portable Cygwin environment.

This project is intended to be used in conjunction with the Cygwin Setup Portable project.
For installation and usage details, please refer to the unified documentation under that project.
* [Cygwin Setup Portable](https://github.com/mesheets/PAF-CygwinSetupPortable)


PortableApps.com Format Packaging Steps
---------------------------------------
1. Copy icons and icon images to .\App\AppInfo
2. Create a .\Help.html file, with file dependencies under .\Other\Help
3. Copy the app distribution itself to .\App\console
4. Create the PortableApps.com configuration files
   1. .\App\AppInfo\AppInfo.ini
   2. .\App\AppInfo\Launcher\CygwinConsolePortable.ini
5. Run the PortableApps.com Launcher to create the portable app launcher
6. Capture desired default configuration from folder Data and copy to App\DefaultData
7. Run the PortableApps.com Installer to create the portable app installer
