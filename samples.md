# Samples

### Learning Stuff
- [Samples](http://developer.android.com/samples/index.html)
- Samples of platform in SDK
	- JobScheduler
	- BasicSyncAdapter
- Sample of support libraries in SDK
- Samples in Github

### Get Samples
- Import samples to Android Studio
- Download from SDK manager
	- Samples of platform: `samples/android-23/`
	- Samples of support libraries: `extras/android/support/samples`

### Build and Run Samples
- Build and run imported samples in Android Studio
- Build and install gradle project with command line
```bash
$ ./gradlew installDebug
```
- Build legacy samples
```bash
$ android update project -n 'Support7Demos' -t 8 -p .
$ ant debug
```

### References
- [Google Samples](https://github.com/googlesamples)


