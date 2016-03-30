# Useful Development Tools

### Learning Stuff
- [StrictMode](http://developer.android.com/reference/android/os/StrictMode.html)
- [Stetho](http://facebook.github.io/stetho/)
- [Chrome Extension - Android SDK search](https://chrome.google.com/webstore/detail/android-sdk-search/hgcbffeicehlpmgmnhnkjbjoldkfhoin)
- [Vysor](http://www.vysor.io/)
- adb shell commands
	- pm
		- List installed packages `adb shell pm list packages -f`
		- Help of pm `adb shell pm -h`
	- dumpsys
		- Show activities, services, providers, broadcasts and processes information `adb shell dumpsys activity`
		- List all dumpsys services `adb shell dumpsys |grep DUMP`
	- am
		- Start activity `adb shell am start -n 'com.android.xxx/.xxx'`
		- Help of am `adb shell am -h`
- Network Tools
	- [Wireshark](https://www.wireshark.org/)
	- [tcpdump](http://www.tcpdump.org/)
	- [mitmproxy](https://mitmproxy.org/)
	- [Charles](https://www.charlesproxy.com/)
	- [Fiddler](http://www.telerik.com/fiddler)
- [Optimizing UI with Hierarchy Viewer](http://developer.android.com/tools/help/hierarchy-viewer.html)
- [DB Browser for SQLite](http://sqlitebrowser.org/)
- [SourceTree](https://www.sourcetreeapp.com/)

### References
- [Handy adb commands for Android](http://www.growingwiththeweb.com/2014/01/handy-adb-commands-for-android.html)
- [PID Cat](https://github.com/JakeWharton/pidcat)

