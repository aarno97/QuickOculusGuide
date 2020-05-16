# QuickOculusGuide
A quick guide to some crucial things to coding for Oculus on Mac

Some crucial things you'll need to install to modify the code base: 

* [Unity Hub and Unity](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwi036_2lrnpAhUPGKwKHRNXDz0QFjAAegQIEBAC&url=https%3A%2F%2Funity3d.com%2Fget-unity%2Fdownload&usg=AOvVaw1pra6oM2sX39lpFrcjBCXf)

* [Android Command Line Tools](https://developer.android.com/studio#downloads) I personally just use the command line tools found at the bottom of the page. 

Unity is used to directly modify the application itself. Android's Command Line Tools are used to install the application on the Oculus. 

On my personal installation, in terminal I had to call bash_profile every time to install/uninstall the application:

* `source ~/.bash_profile`

To install an apk:

* `adb install path_to_apk` -- Example: `adb install Desktop/application.apk`

You must uninstall an apk before writing a new version: 

* `adb uninstall applicationName` -- Example: `adb uninstall com.AaronArnold.OphthalmologyProject`

***I personally used these websites to help understand how to code on Oculus and get your packages from Unity to Oculus:***

* I recommend following Oculus's guide to building a first VR app to get acquianted: [Oculus](https://developer.oculus.com/documentation/unity/unity-tutorial/#build-your-simple-application)

* To set up Android Debug Tools (also known as the command line tools and shortened to adb): [StackOverflow](https://stackoverflow.com/questions/17901692/set-up-adb-on-mac-os-x)

* This taught me every step to taking a package to the Oculus: [Scriptable](https://scriptable.com/blog/oculus-go-unity-setup-quick-start)

