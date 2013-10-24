How to use
========

Simply add the repository to your `build.gradle` file:

```groovy
repositories {
	mavenCentral()
    maven { url 'http://stanfy.github.io/maven-repo/' }
}
```

Currently available artifacts:

```groovy
dependencies {
    compile 'com.facebook:facebook-android-sdk:3.5.2@aar'
    compile("com.actionbarsherlock:viewpagerindicator:2.4.1@aar")
}
```

License:
--------
The licenses are provided by the individual libary owner. This "maven-repo" utilizes these libaries and won´t provide any support, responsibility or licenses itself.
