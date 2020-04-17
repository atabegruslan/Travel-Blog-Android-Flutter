# Travel Blog Android App

- This is an update for https://github.com/Ruslan-Aliyev/Travel-Blog-Android
- This is the Laravel part of https://github.com/atabegruslan/Travel-Blog-Laravel-5-8

# Setup Flutter (Mac)

- https://flutter.dev/docs/get-started/install/macos

- Download Java
- Download and install Android Studio
- Download Flutter
	- `cd Applications`
	- `git clone https://github.com/flutter/flutter.git`
	- `sudo chmod 777 flutter`
	- (`export PATH="$PATH:pwd/flutter/bin"`)
	- (or `nano /etc/paths`, `/Users/ruslan/Applications/flutter/bin`)
	- `nano ~/.bash_profile`, `export PATH=/Users/ruslan/Applications/flutter/bin:$PATH`, `source $HOME/.bash_profile`
	- `flutter`
- Prepare phone
	- Enable Developer options on Android phone: Settings, About phone, tap Build number 7 times.
	- Enable USB debugging: Settings, Developer options, turn this on, turn on Stay awake, turn on USB debugging.
	- Connect device: Press Allow on phone. Set to the appropriate USB connect options on phone. Download necessary drivers if needed.
		- https://www.samsung.com/vn/apps/smart-switch/
		- https://www.android.com/filetransfer/
	- `flutter devices`
- Prepare Android Studio's simulator
	- Open Android Studio, Configure, AVD manager, Create virtual device, set it up.
- Install DART and Flutter plugins into Android Studio
	- Open Android Studio, Configure, Plugins, search DART, install, then search Flutter, install.

# Setup Flutter (Windows)

- https://flutter.dev/docs/get-started/install/windows

- Download Java
- Download and install Android Studio
- Download Flutter
	- `git clone https://github.com/flutter/flutter.git` in `C:\`
	- Add `C:/flutter/bin;` to user env path
	- In PowerShell 5+, run `flutter doctor`
- In AndroidStudio's SDK Manager
	- Get Android SDK Tools
	- Get DART plugin
	- Get Flutter Plugin
- Prepare Android Studio's simulator
	- Open Android Studio, Configure, AVD manager, Create virtual device, set it up.
- Prepare phone
	- Enable Developer options on Android phone: Settings, About phone, tap Build number 7 times.
	- Enable USB debugging: Settings, Developer options, turn this on, turn on Stay awake, turn on USB debugging.
	- Connect device: Press Allow on phone. Set to the appropriate USB connect options on phone. Download necessary drivers if needed.
	- `flutter devices`

## USB Debug Problems

If you cant see your phone there or in AndroidStudio's Select Deployment Target window, the most likely cause is the driver. 

Start, Device Manager: if you see "other devices" with ADB Interface and Android Samsung under it with exclaimation icons beside them, then do:

https://uptodrivers.com/samsung-galaxy-a01-usb-driver-free-download/90393/ (I have Samsung A01)
- https://uptodrivers.com/android-usb-driver/ (Get Google USB Driver in Android Package Manager > SDK tools)
-- https://uptodrivers.com/adb-usb-drivers-free-download/ (NEED ADB Driver)
--- https://www.youtube.com/watch?v=171KC_K3W4E (Have to manually install ADB Driver)
-- https://developer.samsung.com/mobile/android-usb-driver.html (Get Android driver)

Manually install ADB Driver:

1. Device Manager
2. Right click on faulty ADB interface
3. Update Driver Software
4. Browse computer
5. Pick from a list of device drivers
6. Select the android_winusb.inf in the unzipped ADB driver that was downloaded from https://dl-ssl.google.com/android/repository/latest_usb_driver_windows.zip
7. Install

# Start FLutter Project

Open AndroidStudio, file, new, chose *new flutter project* 

# Tutorials

- https://www.youtube.com/playlist?list=PLlxmoA0rQ-Lw6tAs2fGFuXGP13-dWdKsB
- https://www.youtube.com/playlist?list=PLUbFnGajtZlX9ubiLzYz_cw92esraiIBi

# Documentations

- https://flutter.dev/docs/get-started/codelab
- https://flutter.dev/docs/cookbook
- https://flutter.dev/docs

# HTTP Libraries

Chopper is like Retrofit: https://resocoder.com/2019/07/14/chopper-retrofit-for-flutter-3-converters-built-value-integration/

# Publishing APK

- https://flutter.dev/docs/deployment/android
