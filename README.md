# Travel Blog Android App

- This is an update for https://github.com/Ruslan-Aliyev/Travel-Blog-Android
- This is the Android App part of https://github.com/atabegruslan/Travel-Blog-Laravel-5-8

# Setup Flutter (Mac)

- https://flutter.dev/docs/get-started/install/macos

Download Java
Download and install Android Studio
Download Flutter
	- `cd Applications`
	- `git clone https://github.com/flutter/flutter.git`
	- `sudo chmod 777 flutter`
	- (`export PATH="$PATH:pwd`/flutter/bin"`)
	- (or `nano /etc/paths`, `/Users/ruslan/Applications/flutter/bin`)
	- `nano ~/.bash_profile`, `export PATH=/Users/ruslan/Applications/flutter/bin:$PATH`, `source $HOME/.bash_profile`
	- `flutter`
Prepare phone
	- Enable Developer options on Android phone: Settings, About phone, tap Build number 7 times.
	- Enable USB debugging: Settings, Developer options, turn this on, turn on Stay awake, turn on USB debugging.
	- Connect device: Press Allow on phone. Set to the appropriate USB connect options on phone. Download necessary drivers if needed.
		- https://www.samsung.com/vn/apps/smart-switch/
		- https://www.android.com/filetransfer/
	- `flutter devices`
Prepare Android Studio's simulator
	- Open Android Studio, Configure, AVD manager, Create virtual device, set it up.
Install DART and Flutter plugins into Android Studio
	- Open Android Studio, Configure, Plugins, search DART, install, then search Flutter, install.

# Tutorials

- https://www.youtube.com/playlist?list=PLlxmoA0rQ-Lw6tAs2fGFuXGP13-dWdKsB
- https://www.youtube.com/playlist?list=PLUbFnGajtZlX9ubiLzYz_cw92esraiIBi
- https://flutter.dev/docs/get-started/codelab
- https://flutter.dev/docs/cookbook
- https://flutter.dev/docs

# HTTP Libraries

Chopper is like Retrofit: https://resocoder.com/2019/07/14/chopper-retrofit-for-flutter-3-converters-built-value-integration/

# Publishing APK

- https://flutter.dev/docs/deployment/android