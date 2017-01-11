# Awesome Android Release Notes
Awesome Android Release Notes is a useful directory for Android software developers to keep up-to-date with all the things related with Android. **Contributions are welcome**.


###**Note on Update Frequency**: 

For several websites I've tried to provide the update frequency of the webpage in question. This way you can know how frequently it is worth visiting that webpage to keep track of what's new. I further recommend using a browser extension like [Tab Snooze](https://chrome.google.com/webstore/detail/tab-snooze/pdiebiamhaleloakpcgmpnenggpjbcbm?hl=en), which allows you to set a **webpage to open periodically** to automate those which interest you.

# Android OS Updates

For the entire history of Android versions check the official [interactive page for Android history](https://www.android.com/history) that gives you the highlights on each Android version previous to the current one. [Wikipedia has a comprehensive and concise list](https://en.wikipedia.org/wiki/Android_version_history) of all the Android versions, their release date and prominent features.
And last but not least the [**in-depth developer-oriented documentation**](https://developer.android.com/about/index.html) for the latest Android versions. 


Check [SDK Platform release logs](https://developer.android.com/studio/releases/platforms.html) for information about **revisions of each Android release**. This will let you know what changed from versions like Android *7.1\_r1* to *7.1\_r2*. Notice that both of these versions are still considered *Android 7.1* for the consumer, but there could still be practical diferences for developers to be aware of. **Android Police** website usually does a [**diff detailing the new stuff**](http://www.androidpolice.com/tags/changelog/) of each new revision. `Update Frequency: Biweekly`


If you like to stay informed about **OS security** check the [Android Security Bulletins](https://source.android.com/security/bulletin/index.html), they get updated `every month`. Furthermore each major Android version release contains a [round of changes pertaining to Security](https://source.android.com/security/enhancements/index.html).

## Android Auto

* [Google Plus Developer announcements page](https://plus.google.com/communities/116320632775523824083/stream/b2eff625-c529-476d-b3b2-6d3321484e71)

## Android Wear

* [Android Wear release notes here](https://developer.android.com/wear/preview/support.html). This webpage includes preview versions of Android Wear as well - `monthly`
* [Details about **behavioral changes**](https://developer.android.com/wear/preview/behavior-changes.html) that are introduced with each new Wear version
* [Wikipedia page](https://en.wikipedia.org/wiki/Android_Wear) - Contains an overview of the version history of Android Wear

## Google Cast and Android TV

* [Release notes](https://developers.google.com/cast/docs/release-notes) for each Google Cast version - `twice a month`
* [Chromecast Firmware versions](https://support.google.com/chromecast/answer/7124014?hl=en)
* [Android TV Developer Announcements on Google Plus](https://plus.google.com/communities/112881895888889393129/stream/8726bf2b-3211-48e9-a857-4a6d1aec24ad) - This is the closest thing to official release notes
*  


## Android Things

* [Android Things](https://developer.android.com/things/preview/releases.html) - release notes
* [GitHub page](https://github.com/androidthings) - Official samples

# Relevant Info

The following websites are always up-do-date with information pertinent to Android software development:

* [Build Numbers webpage](https://source.android.com/source/build-numbers.html) - Check the relation between Android **Codenames** (*Nougat, ...*), with **API Versions** (*25,..*), **Android Version** (*7.1,...*) and other things like **Source Code Tags** for each device release (*N6F26Q,...*) and their branch name
* [Android Dashboards](https://developer.android.com/about/dashboards/index.html#Platform) - This one gets updated every week and display **global stats** on the distribution of **Android versions**, **Screen densities** and others
* [Android Open-Source Project repositories](https://android.googlesource.com/?format=HTML) - If you're feel like diving into the source of all of the things that make up the **AOSP**
* [Google Samples GitHub](https://github.com/googlesamples) - Google provided repositories and projects, a great way to explore and improve your integration with their products and APIs 
* [Google Developers Medium page](https://medium.com/google-developers) - The **Medium's page of Google Developers** offers a great array of articles regarding development, it is not exclusive to Android but still worth checking out


## Device updates

If you've a Nexus, Pixel or other device that is officially supported by Google you can find the [**Factory Images** here](https://developers.google.com/android/images). In this page you'll typically find *developer preview builds* to install on selected devices every time Google announces a new Android release that is not yet ready to ship.
The factory images require you to wipe the data of your device, so be sure to check the [OTA (*Over-The-Air*) binaries](https://developers.google.com/android/ota) that you can flash on your device to keep it up-to-date without resetting it. This is basically the same update your device gets when it automatically prompts you to update itself, this behavior can take longer depending on how Google decides to roll-out the update so basically with this you can force that update sooner onto your device.

# Blogs and News

Here are some places that you should check out regularly if you're not doing so already, that contain all sorts of new stuff about Android:

* [Google Android Developers Blog](https://android-developers.googleblog.com/) - `Weekly`
* [Android Developers YouTube channel](https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg) - Also contains a playlist of Android related Google I/O videos - `Weekly`
* [Official Android Mailling Lists and IRC information](https://source.android.com/source/community.html#open-source-project-discussions)
* [Awesome Android Performance](https://github.com/Juude/awesome-android-performance) - A good directory that is kept up-to-date relating to **Android applications performance** 
* [Android tips and tricks GitHub](https://github.com/nisrulz/android-tips-tricks) - A GitHub page that gets frequent contributions and serves as a directory for tips, tricks and tools. Definately worth checking out!
* [Android Weekly](http://androidweekly.net/) - A **weekly newsletter** to stay up-to-date with Android Development
* [AndroidDev Digest](https://www.androiddevdigest.com/) - Another **weekly newsletter** regarding Android Development
* [Realm News Blog](https://realm.io/news/tags/android/) - Realm invites known developers to talk about varied topics related with Android development and provides the video sessions afterwards for free - `weekly`




# Android development Tools

Here are the **links** for the **development tools release logs**:

* [Android Studio](http://tools.android.com/recent) - `monthly`
* [New Jill and Jack build system](http://tools.android.com/tech-docs/new-build-system)
* [SDK Tools](https://developer.android.com/studio/releases/sdk-tools.html) - Android Studio informs you of updates to this one by default as well, check this release log to see what the update brings exactly
* [SDK Build Tools](https://developer.android.com/studio/releases/build-tools.html) - Check this one to keep the **buildToolsVersion** of your *gradle build file* up-to-date. `monthly`
* [Android Plugin for Gradle](https://developer.android.com/studio/releases/gradle-plugin.html) - Reading this one is a great way to stay informed about **new flags**, **properties** and other changes to of the **Gradle build syntax**
* [SDK Platform Tools](https://developer.android.com/studio/releases/platform-tools.html) - Contains updates to the command line tools used for development such as *adb*, *fastboot* and *systrace*. 
* [Android NDK release notes](https://developer.android.com/ndk/downloads/revision_history.html) - `twice a year`

## Complimentary development tools

* [Gradle release log](https://docs.gradle.org/current/release-notes) - Android is always behind the current Gradle release, but it is worth checking this website for more in-depth understanding of each new version that Android supports and for the curious to peek into what's coming next :)
* [IntelliJ Release Blog](https://blog.jetbrains.com/idea/category/releases/) - Android Studio is based on IntelliJ IDEA, some even prefer to stick with that instead of Studio as they work similarly if you have the Android plugin enabled. Check this to know new **features and tips** about the IDE, they usually work on Studio as well

# Libraries

## Google Play Services SDK

By far the most relevant library or group of libraries to always keep track of is the [**Google Play Services SDK**](https://developers.google.com/android/guides/releases).
The Google Play Services SDK is composed by more than a dozen libraries, you can see the [full up-to-date list here](https://developers.google.com/android/guides/setup). This includes know libraries such as **Google Maps**, **Google Cloud Messaging**, **Android Wear**, **Firebase**, **Google Account Login**, **Google Analytics**, and the list goes on... Basically integrations with most Google products out there, so it bound to keep growing.

Update Frequency: `Monthly`

## Support Library

The **Google Support Library** is another super set of libraries, and you can check the [latest changes here](https://developer.android.com/topic/libraries/support-library/revisions.html). Some of the most know libraries it provides are used to provide support for **retro-compatibility**, various aspects and components of **material design**, **TV and Media Playback**, etc.

Update Frequency: `Monthly`

## JUnit

If you're writing tests you should keep track of the [changes in JUnit4](https://github.com/junit-team/junit4/tree/master/doc). The throughput of new releases varies, but as good thumb of rule check this one `twice a year`.

