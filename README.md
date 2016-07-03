# trosh-android
That game from @stabyourself (stabyourself.net)

* **Where can I download it?**
> On [this page] (https://github.com/pavlukivan/trosh-android/releases)

* **How to build it from source?**

>1. Clone this repo :D
2. Zip all project files into game.love
3. Clone the project from https://bitbucket.org/MartinFelis/love-android-sdl2
4. Set up AndroidManifest.xml as you want
5. Create assets folder
6. Put your game.love from p.2 into assets folder
7. Open and compile the project using Eclipse **OR do following**
8. Install Android SDK, Android NDK and Apache Ant
9. Set (If not already setted) environment variables ANDROID_NDK, ANDROID_SDK and ANDROID_HOME
10. Command: cd *love-android-sdl2_clone_dir*
11. Command: ndk-build -j4
12. Command: ant debug (or release)
