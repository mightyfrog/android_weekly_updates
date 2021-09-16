# Android Weekly Updates (September 2021)

## Week 3 (09/12 ~)

### Google Developers

- [App actions for Android: Capabilities and static shortcuts](https://www.youtube.com/watch?v=JOOyIe50-tE)
  - Google Assistant と音声操作周り
- [Jetpack library update](https://developer.android.com/jetpack/androidx/versions/all-channel#september_15_2021)
  - Activity Version 1.4.0-alpha02
    - [Activity 1.4.0-alpha02 converts the ActivityResultContract base class and the prebuilt implementations in ActivityResultContracts to Kotlin](https://twitter.com/ianhlake/status/1438271761879998466)
  - Browser Version 1.4.0-alpha01
  - Compose Animation Version 1.1.0-alpha04
  - Compose Compiler Version 1.1.0-alpha04
  - Compose Foundation Version 1.1.0-alpha04
  - Compose Material Version 1.1.0-alpha04
  - Compose Runtime Version 1.1.0-alpha04
  - Compose UI Version 1.1.0-alpha04
  - Core Core-Ktx Version 1.7.0-beta01
  - Emoji2 Version 1.0.0-beta01
    - [Support modern emoji](https://developer.android.com/guide/topics/ui/look-and-feel/emoji2)
    - [Emoji2 hits 1.0.0-beta01 today!](https://twitter.com/ianhlake/status/1438271759749304323)
  - Fragment Version 1.4.0-alpha09
    - [Fragment 1.4.0-alpha09 adds what might be our final new API for this release (beta soon: yes please!)](https://twitter.com/ianhlake/status/1438271763708727298)
  - Lifecycle Version 2.4.0-beta01
    - @OnLifecycleEvent was deprecated. LifecycleEventObserver or DefaultLifecycleObserver should be used instead.
    - [Lifecycle 2.4.0-beta01 is an important one](https://twitter.com/ianhlake/status/1438271757891211268)
  - Media Version 1.4.2
  - Media2 Version 1.2.0
  - Navigation Version 2.4.0-alpha09
    - You can now use the clearBackStack() method to clear any state that was saved with popBackStack() or popUpToSaveState.  
    - [Navigation 2.4.0-alpha09 has one breaking change](https://twitter.com/ianhlake/status/1438271765520678912)
  - ProfileInstaller Version 1.1.0-alpha05
  - RecyclerView Version 1.3.0-alpha01
    - Added support for stretch overscroll RecyclerView.
    - [Overscroll effect](https://developer.android.com/about/versions/12/overscroll)
    - ライブラリの更新だけじゃ何も変わらん模様
  - ResourceInspection Version 1.0.0-beta01
  - ViewPager Version 1.1.0-alpha01
    - Added support for Android 12 stretch over scroll edge effect.
  - Wear Complications & Watchface Version 1.0.0-alpha22
  - Wear-Input Wear-Input-Testing Version 1.2.0-alpha01
  - Wear-Phone-Interactions Version 1.1.0-alpha01
  - Wear Version 1.2.0
    - [The Wear OS team has gone through a large amount of work to build UI patterns that fit on watches](https://twitter.com/ianhlake/status/1438271755814981632)
  - Wear-Phone-Interactions Wear-Remote-Interactions Version 1.0.0
- Wear Compose Version 1.0.0-alpha06
  - [Wear OS Jetpack libraries now in stable!](https://android-developers.googleblog.com/2021/09/wear-os-jetpack-libraries-now-in-stable.html)
  - "We strongly recommend you migrate the libraries within your Wear OS apps from the Wearable Support library to their AndroidX equivalents as we make them available in stable."
- [Hilt extensions - MAD Skills](https://www.youtube.com/watch?v=53higH5LIBs)
  - WorkManager extension @HiltWorker
    - not in core library. androidx.hilt:hilt-work, androidx.hilt:hilt-compiler
    - [Inject WorkManager with Hilt](https://developer.android.com/training/dependency-injection/hilt-jetpack#workmanager)
  - Hilt Extension Annotations
    - [Creating extensions](https://dagger.dev/hilt/creating-extensions)
    - [Example in GitHub](https://github.com/danysantiago/hilt-install-binding)
  - Examples and etc.
- [Labeling images for Accessibility](https://www.youtube.com/watch?v=O2DeSITnzFk)
  - TalkBack がちゃんと機能するように contentDescription を付けましょう
  - Be precise and concise. ex. Add ボタンは contentDescription ではもっと分かるように Add Task のようにしましょう。
  - 特に意味のない画像とかには contentDescription = null をセット。Divider 画像とか。

### Reddit

- [Animated BottomNavigation with native control and jetpack navigation…✨🔖🚀](https://www.reddit.com/r/androiddev/comments/pncba5/animated_bottomnavigation_with_native_control_and/)
  - 実装は面白いけど UI/UX 観点から結構ボコボコに。実装の参考にはなりそう。
  - [reddit](https://www.reddit.com/r/androiddev/comments/pncba5/animated_bottomnavigation_with_native_control_and/)

### Other

- [Java 17 available now](https://www.oracle.com/java/technologies/downloads/#JDK17)
  - また無償に
- [square/workflow-kotlin v1.0.0](https://github.com/square/workflow-kotlin/releases/tag/v1.0.0)
  - square の全プロダクトで利用されているステート管理系のライブラリ
- [日本語 Noto フォント](https://fonts.google.com/noto/specimen/Noto+Sans+JP)が API 経由でも利用可能に
  - これは素晴らしい。
  - [Tweet](https://twitter.com/taquo/status/1438271763129901057)
