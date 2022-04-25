# Android Weekly Updates 2022/04)

## 04/18 ~

### Google Developers

- [Twitter going all in on Jetpack Compose for feature development: greater productivity, less bugs](https://android-developers.googleblog.com/2022/04/twitter-going-all-in-on-jetpack-compose.html)
  - [reddit](https://www.reddit.com/r/androiddev/comments/u7icod/twitter_going_all_in_on_jetpack_compose_for/)
- [Measure and improve performance with Macrobenchmark](https://medium.com/androiddevelopers/measure-and-improve-performance-with-macrobenchmark-560abd0aa5bb
- )
- [lib update](https://developer.android.com/jetpack/androidx/versions/all-channel#april_20_2022)
  - Activity Version 1.5.0-beta01
  - Benchmark Version 1.1.0-rc01
  - Compose Animation Version 1.2.0-alpha08
  - Compose Compiler Version 1.2.0-alpha08
  - Compose Foundation Version 1.2.0-alpha08
    - New experimental LazyLayout API is introduced. This allows you to build your own components like LazyColumn of LazyVerticalGrid. Note that the API is in its early stages and can be changed in the future releases.
  - Compose Material Version 1.2.0-alpha08
  - Compose Material 3 Version 1.0.0-alpha10
  - Compose Runtime Version 1.2.0-alpha08
  - Compose UI Version 1.2.0-alpha08
  - Core Core-Ktx Version 1.8.0-beta01
  - Core-Animation Version 1.0.0-beta01
  - Drag And Drop Version 1.0.0-rc01
  - Emoji2 Version 1.2.0-alpha04
  - Fragment Version 1.5.0-beta01
    - DialogFragment has added a new dismissNow method that uses commitNow for parity with the showNow function. Note that this will not make the Dialog be dismissed immediately, it will only synchronously update the state of the FragmentManager.
  - Lifecycle Version 2.5.0-beta01
    - dded SavedStateHandle.saveable property delegates to use property names as keys for persisting state into the SavedStateHandle
  - Media Version 1.6.0
  - Mediarouter Version 1.3.0
  - Navigation Version 2.5.0-beta01
  - SavedState Version 1.2.0-beta01
    - The SavedStateRegistry and ViewTreeSavedStateRegistryOwner classes have been rewritten in Kotlin. For ViewTreeSavedStateRegistryOwner, this is a source incompatible change...
  - Tracing Version 1.1.0-rc01
  - VectorDrawable Version 1.2.0-beta01
  - VectorDrawable-Seekable Version 1.0.0-beta01
    - VectorDrawable でシークできたのか。知らなかった。
  - Wear Compose Version 1.0.0-alpha21
  - Wear Watchface Version 1.1.0-beta01
  - Window Version 1.1.0-alpha01

### Other

- [Kotlin 1.6.21](https://kotlinlang.org/docs/releases.html#release-details)
- [Kotlin Gradle Plugin v1.6.21](https://github.com/JetBrains/kotlin)
- [LeakCanary v2.9.0/2.9.1](https://square.github.io/leakcanary/changelog/)

## 04/11 ~

### Google Developers

- [The Android App Excellence Summit is coming April 12, 2022!](https://www.youtube.com/watch?v=6SW8Y_m72ug)
  - [Playlist](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_4exbhZ53VKXm86mUbWjZc)
- [Firebase BOM v29.3.1](https://developers.google.com/android/guides/releases#april_14_2022)
- [Play Services Nearby v18.1.0](https://developers.google.com/android/guides/releases#april_12_2022)

### Other

- [Composable metrics](https://chris.banes.dev/composable-metrics/)

## 04/04 ~

### Google Developers

- [Google Play デベロッパー ポリシー ウェビナー 2022 年 4 月](https://developersonair.withgoogle.com/events/policy2022-1)
  - 4/20
- [Android Studio Bumblebee | 2021.1.1 Patch 3 now available](https://androidstudio.googleblog.com/2022/04/android-studio-bumblebee-202111-patch-3.html)
- [Expanding Play’s Target Level API Requirements to Strengthen User Security](https://android-developers.googleblog.com/2022/04/expanding-plays-target-level-api-requirements-to-strengthen-user-security.html?m=1&s=03)
- [Android 13 デベロッパー プレビュー 2](https://android-developers-jp.googleblog.com/2022/04/second-preview-android-13.html)
- [Architecture: The Domain Layer - MAD Skills](https://www.youtube.com/watch?v=gIhjCh3U88I)
- [lib update](https://developer.android.com/jetpack/androidx/versions/all-channel#april_6_2022)
  - Activity Version 1.5.0-alpha05
  - AppCompat AppCompat-Resources Version 1.5.0-alpha01
  - Benchmark Version 1.1.0-beta06
  - Camera Version 1.1.0-beta03
  - Compose Animation Version 1.2.0-alpha07
  - Compose Compiler Version 1.2.0-alpha07
  - Compose Foundation Version 1.2.0-alpha07
    - Added KeyboardType.Decimal as an alternative to Keyboard.Number for specifically including decimal separator in IME.
  - Compose Material Version 1.2.0-alpha07
  - Compose Material 3 Version 1.0.0-alpha09
  - Compose Runtime Version 1.2.0-alpha07
  - Compose UI Version 1.2.0-alpha07
  - Core Core-Ktx Version 1.8.0-alpha07
  - Emoji2 Version 1.2.0-alpha03
  - Fragment Version 1.5.0-alpha05
    - Fragment's setHasOptionsMenu() has been deprecated.
  - Lifecycle Version 2.5.0-alpha06
  - Media Version 1.6.0-rc01
  - Navigation Version 2.5.0-alpha04
  - Navigation Version 2.4.2
  - RecyclerView Version 1.3.0-alpha02
  - SavedState Version 1.2.0-alpha02
  - Sqlite Version 2.3.0-alpha02
  - Wear Compose Version 1.0.0-alpha20
  - Wear Tiles Version 1.1.0-alpha05
  - Wear Watchface Version 1.1.0-alpha05
  - WorkManager Version 2.8.0-alpha02

### Other

- [Ktlint v0.45.2](https://github.com/pinterest/ktlint/releases/tag/0.45.2)
- [Who are the teens suddenly choosing Android over iPhone?](https://www.zdnet.com/article/who-are-the-teens-suddenly-choosing-android-over-iphone/)
  - 誤差では

## 03/28 ~

### Google Developers

- [Google Photos: How we used notifications to boost widget installs 10x!](https://android-developers.googleblog.com/2022/04/google-photos-notifs-boot-installs.html)
  - 最初から勝手にいたような気が…
- [Accessibility on TV - Integrate with Android TV & Google TV](https://www.youtube.com/watch?v=GyglHvJ6LMY)
- [Now in Android: 58 - Android 13, MAD Skills Architecture, Android TV & Google TV series, and more!](https://www.youtube.com/watch?v=Yt39Ip0CrJw)
- [Architecture: Handling UI events - MAD Skills](https://www.youtube.com/watch?v=lwGtp0Yr0PE)

### r/androiddev

- [A naive Jetpack Compose LazyStaggeredGrid](https://www.reddit.com/r/androiddev/comments/ttax35/a_naive_jetpack_compose_lazystaggeredgrid/)

### Other

- [Kotlin v1.6.20](https://github.com/JetBrains/kotlin)
- [Kotlin Gradle Plugin v1.6.20](https://github.com/JetBrains/kotlin)
- [Gradle v7.4.2](https://docs.gradle.org/7.4.2/release-notes.html)
- [Google terminated a company’s Play Store account because a former employee violated policies — 3 years after leaving](https://www.androidpolice.com/google-terminate-personal-account-former-employee-violated-policies/)
  - 相変わらず
