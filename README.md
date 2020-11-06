## Jitpack Android Sample

A sample library to demonstrate publishing to Jitpack.

Look at [lib/build.gradle](lib/build.gradle) for how to setup the `maven-publish` plugin.

This repo is automatically built by Jitpack and made available on Jitpack maven repo. To use it, add the below to your app/build.gradle[.kts]

```kotlin
repositories {
    maven { url = uri("https://jitpack.io") }
}

dependencies {
    implementation("com.github.martinbonnin:jitpack-android-sample:v1.0")
}
```

If you want to experiment, fork it, push a tag to your fork and consume your fork with:

```
dependencies {
    implementation("com.github.$yourUserName:jitpack-android-sample:$yourTag")
}
```
