# Travel Blog Android App

- This is an update for https://github.com/Ruslan-Aliyev/Travel-Blog-Android
- This is the Laravel part of https://github.com/atabegruslan/Travel-Blog-Laravel-5-8

# Setup Flutter (Mac)

https://flutter.dev/docs/get-started/install/macos

- Have Java & AndroidStudio
- Download Flutter
	- `cd Applications`
	- `git clone https://github.com/flutter/flutter.git`
	- `sudo chmod 777 flutter`
	- Add `flutter` to path
		- preferably: `nano ~/.bash_profile`, `export PATH=/Users/ruslan/Applications/flutter/bin:$PATH`, `source $HOME/.bash_profile`
		- or: `export PATH="$PATH:pwd/flutter/bin"`
		- or: `nano /etc/paths`, `/Users/ruslan/Applications/flutter/bin`
- In AndroidStudio's Package Manager
	- Get DART plugin
	- Get Flutter Plugin

# Setup Flutter (Windows)

https://flutter.dev/docs/get-started/install/windows

- Have Java & AndroidStudio
- Download Flutter
	- `git clone https://github.com/flutter/flutter.git` in `C:\`
	- Add `C:/flutter/bin;` to user env path
- In AndroidStudio's Package Manager
	- Get DART plugin
	- Get Flutter Plugin

## Prepare devices

- Phone for USB Debug: https://gist.github.com/atabegruslan/bfe4b95e86457b3a69a50f12d4644b72
- Virtual Device: Setup in AndroidStudio's Virtual Device Manager

# Useful commands that you can now run

- Check if you can use the flutter command: `flutter` or `flutter --version`
- See your devices: `flutter devices` 
- Check that all the requirement of flutter development is met: `flutter doctor` 
- Helpful for debugging: `flutter doctor -v`
- Helpful for debugging: `flutter run --verbose`

Note: For Windows, these are better ran in PowerShell 5+.

# Start Flutter Project

Open AndroidStudio, file, new, chose *new flutter project* . 

If you chose 'new project', you'd start to develop Android apps using Java the old fashioned way. (or Kotlin if you have the Kotlin plugin and ticked 'include Kotlin support' in the start-new-project wizard)

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
