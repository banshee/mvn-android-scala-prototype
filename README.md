# Maven Android Scala Prototype #
This setup works. I use it with multiple clients.

## Setup ##
- Install JDK 1.5+.
- Install the Android SDK.
- Install Maven 3.0.3+.
- Set the ennvironment variable ANDROID_HOME to the paty of your Android SDK.
- Add $ANDROID_HOME/tools and $ANDROID_HOME/platform_tools to your $PATH.

## Compile & Run on Attached Device or Running Emulator ##

    mvn clean install android:deploy

## Help ##

    mvn android:help

## Improvement ##
I'm trying to figure out how to:

- Avoid running ProGuard during development mode
- Reduce the jar search path to avoid all the duplicate jars that ProGuard wastes time on
- Integrate ProguardCache (banshee/ProguardCache)
- Introduce multiple modes, one for development and one for deploy
- Specify the key to sign with

If you can do any of these things, please send me a pull request on GitHub.

## Contact ##

- If you have questions, I suggest you email the scala-on-android Google group (https://groups.google.com/forum/?fromgroups#!forum/scala-on-android) and CC me.
- ymasory@gmail.com
- http://yuvimasory.com

