# Maven Android Scala Prototype #
This setup works. I use it with multiple clients.

## Compile & Run on Attached Device or Running Emulator ##

    mvn clean install android:deploy

You must be using Maven 3.

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

