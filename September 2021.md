# Android Weekly Updates (September 2021)

## Week 4 (09/18 ~)

### Google Developers

- [Play Core Library 1.10.1](https://developer.android.com/reference/com/google/android/play/core/release-notes)
  - Increased Android minimum SDK version to 14 (ICS)
- [Make your Android apps more accessible for all users in this new learning pathway! ](https://developer.android.com/courses/pathways/make-your-android-app-accessible)
  - Learn to make your Android apps usable by everyone, including people with accessibility needs.
- [🐶 A new Android Basics in Kotlin codelab just launched! ](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-2-pathway-3)
  - Create an app that displays a scrollable list of inspiring text and images using the RecyclerView widget in Android. Along the way, you’ll learn about using lists in Kotlin to store a collection of data.
- [Migrating from Dagger to Hilt - MAD Skills](https://www.youtube.com/watch?v=Xt1_3Nq4lD0&list=PLWz5rJ2EKKc_9Qo-RBRYhVmME1iR4oeTK)
  - グローバルな Singleton から始めて、Activity、Fragment、etc. と個別にやっていくのがおすすめ。
- [Accessibility in Jetpack Compose](https://developer.android.com/codelabs/jetpack-compose-accessibility#0)
  - ✨ New Accessibility in Compose Codelab released!
Touch target sizes, custom actions, click labels, and a lot more!
  - [Tweet](https://twitter.com/Lojanda/status/1439978973719564290)
- [Things to know about Flow’s shareIn and stateIn operators](https://medium.com/androiddevelopers/things-to-know-about-flows-sharein-and-statein-operators-20e6ccb2bc74)
  - The *shareIn* operator returns a SharedFlow instance.
  - The *stateIn* returns a StateFlow.
  - Don’t create new instances on each function call.
  - The shareIn and stateIn operators can be used with cold flows to improve performance, add a buffer when collectors are not present, or even as a caching mechanism!
- [Making permissions auto-reset available to billions more devices](https://android-developers.googleblog.com/2021/09/making-permissions-auto-reset-available.html)
  - 2021 12 月からパーミッションの自動削除が Android 6.0 (23) 以上のデバイスにも適用される。
  - Android 11 (30) 以降はデフォルトで有効、23 ~ 29 は手動で設定。
- [EditTexts - Accessibility on Android](https://www.youtube.com/watch?v=Pjzjs3kB0JA&list=PLWz5rJ2EKKc8OENfLdh3zM5T6IRdlVYKj&index=6)
  - EditText には android:hint と android:labelFor はちゃんと付けましょう。

### r/androiddev

- [Do you think LiveData will ever be deprecated in the next 5 years?](https://www.reddit.com/r/androiddev/comments/pshgmc/do_you_think_livedata_will_ever_be_deprecated_in/)
- [I've ported the popular Flutter Bloc library into Kotlin and Jetpack Compose - would love some folks to try it out and let me have some feedback.](https://www.reddit.com/r/androiddev/comments/prtg47/ive_ported_the_popular_flutter_bloc_library_into/)
  - [Kotlin Bloc](https://ptrbrynt.github.io/KotlinBloc/#/getting-started)
- [App disables itself when Developer Option is enabled. Any security benefits of doing so?](https://www.reddit.com/r/androiddev/comments/pqi6oy/app_disables_itself_when_developer_option_is/)
  - "As someone working in the financial app industry, I can assure you these ideas aren't made up by the developers." そうなんだろうけど、どこの銀行もやってて本当鬱陶しい。
- [Waves Animation with Jetpack Compose](https://www.reddit.com/r/androiddev/comments/pq97wd/waves_animation_with_jetpack_compose/)
  - [demo](https://twitter.com/manueldidonna/status/1438977513250856960?s=19)

### Other

- [Kotlin 1.5.31](https://github.com/JetBrains/kotlin/releases/tag/v1.5.31)

---

## Week 3 (09/12 ~)

### Google Developers

- [Using WorkManager on Android 12](https://medium.com/androiddevelopers/using-workmanager-on-android-12-f7d483ca0ecb)
  - Android 12 では WorkManager 2.7 を使う
  - Android 12 で setForegroundAsync() をコールしてるなら、 WorkRequest.Builder.setExpedited(…) に置き換え。
- [Adjusting the Focus](https://material.io/blog/inclusive-imagery-at-google)
  - 多様性の中でより多くの人に受け入れられる画像を作る努力してます的な。
- [App performance to drive app excellence](https://android-developers.googleblog.com/2021/09/app-performance-to-drive-app-excellence.html)
  - The main dimensions of high performance
    - Stability
      - [The ANR troubleshooting guide](https://developer.android.com/topic/performance/vitals/anr)
    - Quick loading
      - [Cold](https://developer.android.com/topic/performance/vitals/launch-time#cold) startup shouldn't take 5 seconds or longer.
      - [Warm](https://developer.android.com/topic/performance/vitals/launch-time#warm) startup shouldn't take 2 seconds or longer.
      - [Hot](https://developer.android.com/topic/performance/vitals/launch-time#hot) startup shouldn't take 1.5 seconds or longer.
      - [Testing App Startup Performance](https://medium.com/androiddevelopers/testing-app-startup-performance-36169c27ee55)
    - Fast rendering
      - [Profile HWUI rendering](https://developer.android.com/topic/performance/rendering/inspect-gpu-rendering)
      - [Diagnosis tools](https://developer.android.com/topic/performance/vitals/render)
    - Economical with battery usage
      - [Android Studio energy profiler](https://developer.android.com/studio/profile/energy-profiler)
    - Using up-to-date SDKs
      - [Keep services and dependencies up-to-date](https://developer.android.com/topic/security/best-practices#services-dependencies-updated)
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
      - EdgeEffect を使うクラスはすべてに同じく適用される。ただ、ライブラリの更新だけじゃ何も変わらない模様。
        - RecyclerView
        - ListView
        - ScrollView
        - NestedScrollView
        - HorizontalScrollView
        - ViewPager
        - ViewPager2
    - アップルのパテントが切れて実装できるようになったっぽい（現状同じじゃないけど）。[Tweet](https://twitter.com/SamTheGeek/status/1394834891393613828)
  - ResourceInspection Version 1.0.0-beta01
  - ViewPager Version 1.1.0-alpha01
  - Wear Complications & Watchface Version 1.0.0-alpha22
  - Wear-Input Wear-Input-Testing Version 1.2.0-alpha01
  - Wear-Phone-Interactions Version 1.1.0-alpha01
  - Wear Version 1.2.0
    - [The Wear OS team has gone through a large amount of work to build UI patterns that fit on watches](https://twitter.com/ianhlake/status/1438271755814981632)
  - Wear-Phone-Interactions Wear-Remote-Interactions Version 1.0.0
- Wear Compose Version 1.0.0-alpha06
  - [Wear OS Jetpack libraries now in stable!](https://android-developers.googleblog.com/2021/09/wear-os-jetpack-libraries-now-in-stable.html)
  - We strongly recommend you migrate the libraries within your Wear OS apps from the Wearable Support library to their AndroidX equivalents as we make them available in stable.
- [Hilt extensions - MAD Skills](https://www.youtube.com/watch?v=53higH5LIBs)
  - [Hilt Extensions in the MAD Skills series](https://medium.com/androiddevelopers/hilt-extensions-in-the-mad-skills-series-f2ed6fcba5fe)
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

### r/androiddev


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
