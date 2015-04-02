# PepperTalkAndroidSDK
Android SDK for PepperTalk is available as a Gradle dependency. Its available on [maven as an aar](https://search.maven.org/#search%7Cga%7C1%7Cpeppertalk)

Add PepperTalk to your application

Gradle dependency 
```xml
    compile 'com.espreccino:peppertalk:0.4.13'
```

[build.gradle] [2]

---
### Adding PepperTalk to eclipse project
---
Add the following to your pom.xml [(more info using m2eclipse)] [4]
```xml
<dependency>
 <groupId>com.espreccino</groupId>
 <artifactId>peppertalk</artifactId>
 <version>0.4.13</version>
</dependency>
````

Download the latest aar [here] [5]

Detailed instructions on setting up Eclipse with ADT is [here](eclipse_setup.md)

[1]: https://console.getpeppertalk.com/ "PepperTalk"
[2]: https://github.com/Espreccino/PepperTalkAndroidSDK-Examples/blob/master/app/build.gradle "build.gralde"
[3]: https://github.com/Espreccino/PepperTalkAndroidSDK-Examples/blob/master/app/src/main/res/values/strings.xml#L6 "strings.xml"
[4]: http://books.sonatype.com/m2eclipse-book/reference/dependencies.html "m2eclipse"
[5]: https://search.maven.org/#browse%7C-793624875 "PepperTalk SNAPSHOT"
[6]: https://github.com/Espreccino/PepperTalkAndroidSDK-Examples/blob/master/app/src/main/java/com/espreccino/peppertalk/sample/gcm/GcmIntentService.java#L30
[7]: https://github.com/Espreccino/PepperTalkAndroidSDK-Examples/blob/master/app/src/main/java/com/espreccino/peppertalk/sample/gcm/GcmIntentService.java#L32
[8]: https://github.com/Espreccino/PepperTalkAndroidSDK-Examples/blob/master/app/src/main/AndroidManifest.xml#L24
