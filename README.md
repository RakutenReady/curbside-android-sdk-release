# curbside-android-sdk-release
This repository is used to host android sdk dependency on github

### Installing
* Add following lines to your gradle file:

```java

repositories {
    maven {url "https://raw.github.com/Curbside/curbside-android-sdk-release/master"}
}


dependencies {
    compile 'com.curbside:sdk:3.0+'
}
```

### Optional
If required, following dependencies are optional packages that you can include in your gradle file for complete experience:
```java
    compile fileTree(dir: 'libs', include: ['*.jar'])
    compile 'com.squareup.retrofit:retrofit:1.9.0'
    compile 'com.squareup.okhttp:okhttp-urlconnection:2.2.0'
    compile 'com.squareup.okhttp:okhttp:2.2.0'
    compile 'io.reactivex:rxandroid:1.0.1'
    compile 'com.google.android.gms:play-services:8.1.0'
    compile 'com.android.support:support-v4:23'
    compile 'com.google.code.gson:gson:1.7.2'
```

* Compile the code, it should compile successfully.
