# Android Weekly Updates (January 2022)

## 01/22 ~

### Google Developers

- [Android Studio Bumblebee (2021.1.1) Stable](https://android-developers.googleblog.com/2022/01/android-studio-bumblebee-202111-stable.html)
- [Preferences DataStore - MAD Skills](https://www.youtube.com/watch?v=kp53qL_O5gk)
- [TalkBack - Accessibility on Android](https://www.youtube.com/watch?v=_1yRVwhEv5I)
- [Announcing Glance: Tiles for Wear OS made simple](https://android-developers.googleblog.com/2022/01/announcing-glance-tiles-for-wear-os.html)
- [What's new in Android Studio Bumblebee](https://www.youtube.com/watch?v=rIt13HjCRiI)
- [lib update](https://developer.android.com/jetpack/androidx/versions/all-channel#january_26_2022)
  - Activity Version 1.5.0-alpha01
    - The no parameter constructor for ActivityResultContracts.CreateDocument has been deprecated and replaced with a new constructor that takes a concrete mime type (e.g., "image/png") as is required by Intent.ACTION_CREATE_DOCUMENT
  - Benchmark Version 1.1.0-beta02
  - Camera Version 1.1.0-beta01
    - From 1.1.0-beta01, all CameraX libraries will align the same version number. This will help developers track versions much easier and reduce the complexity of large version compatibility matrix.
  - Car App Version 1.2.0-beta02
  - Compose Animation Version 1.1.0-rc03
  - Compose Compiler Version 1.1.0-rc03
  - Compose Foundation Version 1.1.0-rc03
  - Compose Material Version 1.1.0-rc03
    - Note that, with respect to Compose 1.0, Material components will expand their layout space to meet Material accessibility guidelines touch target size.
  - Compose Runtime Version 1.1.0-rc03
  - Compose UI Version 1.1.0-rc03
  - Compose Animation Version 1.2.0-alpha02
    - Use AnimatedImageVector.animatedVectorResource instead of animatedVectorResource to load an <animated-vector> resource file.
  - Compose Compiler Version 1.2.0-alpha02
  - Compose Foundation Version 1.2.0-alpha02
  - Compose Material Version 1.2.0-alpha02
    - Add support for action chip
  - Compose Material 3 Version 1.0.0-alpha04
  - Compose Runtime Version 1.2.0-alpha02
  - Compose UI Version 1.2.0-alpha02
  - Core Core-Ktx Version 1.8.0-alpha03
    - [API changes](https://developer.android.com/jetpack/androidx/releases/core#1.8.0-alpha03)
  - Core-RemoteViews Version 1.0.0-alpha02
  - Drag And Drop Version 1.0.0-alpha03
  - Emoji2 Version 1.1.0-beta01
  - Fragment Version 1.4.1
  - Fragment Version 1.5.0-alpha01
  - Games-Activity Version 1.1.0-beta03
  - Games-Controller Version 1.1.0-beta01
  - Games-Frame-Pacing Version 1.10.0-beta01
  - Games-Performance-Tuner Version 1.5.0-rc01
  - Games-Text-Input Version 1.1.0-rc01
  - Glance Version 1.0.0-alpha02
  - Hilt-Navigation-Compose Version 1.0.0
    - The androidx.hilt:hilt-navigation-compose artifact provides APIs that allow users to get a @HiltViewModel annotated ViewModel from a Navigation back stack entry within a Compose application using :navigation-compose.The function hiltViewModel() returns an existing ViewModel or creates a new one scoped to the current navigation graph present on the NavController back stack. The function can optionally take a NavBackStackEntry to scope the ViewModel to a parent back stack entry.
  - Lifecycle Version 2.5.0-alpha01
    - [ViewModel CreationExtras](https://developer.android.com/jetpack/androidx/releases/lifecycle#2.5.0-alpha01)
  - Media Version 1.5.0-rc01
  - Mediarouter Version 1.2.6
  - Navigation Version 2.5.0-alpha01
    - NavBackStackEntry now integrates with ViewModel CreationExtras, introduced as part of Lifecycle 2.5.0-alpha01.
  - Navigation Version 2.4.0
    - [Important changes since 2.3.0](https://developer.android.com/jetpack/androidx/releases/navigation#2.4.0)
  - Preference Version 1.2.0
    - [Important changes since 1.1.0](https://developer.android.com/jetpack/androidx/releases/preference#1.2.0)
  - ProfileInstaller Version 1.2.0-alpha02
  - ResourceInspection Version 1.0.1
  - SavedState Version 1.2.0-alpha01
  - SlidingPaneLayout Version 1.2.0
  - Wear Compose Version 1.0.0-alpha15
  - Wear Tiles Version 1.1.0-alpha01
  - Wear Tiles Version 1.0.1
  - Window Version 1.0.0
    - Support for folding phones through WindowInfoTracker and FoldingFeature. WindowMetricsCalculator to help calculate the current WindowMetrics.

### r/androiddev

- [Ever wonder how Android Access View Items evolve over the years?](https://www.reddit.com/r/androiddev/comments/sg6f2z/ever_wonder_how_android_access_view_items_evolve/)
- [Keep API Key Outside of Gradle and Git](https://www.reddit.com/r/androiddev/comments/semy8q/keep_api_key_outside_of_gradle_and_git/)

## 01/16 ~

### Google Developers

- [DataStore - MAD Skills](youtube.com/watch?v=9ws-cJzlJkU)
- [Introduction to DataStore - MAD Skills](https://www.youtube.com/watch?v=mdQjuZbLv9Y)
- [Google Play Games beta launches on PC in Korea, Taiwan, and Hong Kong](https://android-developers.googleblog.com/2022/01/googleplaygames.html)
- [Material Components for Android](https://github.com/material-components/material-components-android)
- [Baseline Profiles](https://developer.android.com/studio/profile/baselineprofiles)
- [Jetnews for every screen](https://medium.com/androiddevelopers/jetnews-for-every-screen-4d8e7927752)
- [12L Beta](https://developer.android.com/about/versions/12/12L)
- lib update
  - [Firebase BoM v29.0.4](https://firebase.google.com/support/release-notes/android#2022-01-20)

### r/androiddev

- [So my Android developer account was terminated by Google](https://www.reddit.com/r/androiddev/comments/s93076/so_my_android_developer_account_was_terminated_by/)
  - [How attackers can delete your Google developer account!](https://www.reddit.com/r/androiddev/comments/mp9za4/how_attackers_can_delete_your_google_developer/)
- [Does Jetpack Compose have all features of traditional XML?](https://www.reddit.com/r/androiddev/comments/s8i3m2/does_jetpack_compose_have_all_features_of/ )

## 01/01 ~

### Google Developers

- [On Device Watch Next - Integrate with Android TV & Google TV](https://www.youtube.com/watch?v=QFMIP5GOo70)
- [lib update](https://developer.android.com/jetpack/androidx/versions/all-channel#january_12_2022)
  - AppCompat AppCompat-Resources Version 1.4.1
  - Benchmark Version 1.1.0-beta01
  - Compose Animation Version 1.2.0-alpha01
  - Compose Compiler Version 1.2.0-alpha01
  - Compose Foundation Version 1.2.0-alpha01
  - Compose Material Version 1.2.0-alpha01
  - Compose Material 3 Version 1.0.0-alpha03
  - Compose Runtime Version 1.2.0-alpha01
  - Compose UI Version 1.2.0-alpha01
  - CoordinatorLayout Version 1.2.0
  - Core-Splashscreen Version 1.0.0-beta01
  - Localbroadcastmanager Version 1.1.0
  - ProfileInstaller Version 1.2.0-alpha01
  - Room Version 2.4.1
  - Wear Compose Version 1.0.0-alpha14
  - Wear Watchface Version 1.1.0-alpha02
  - WorkManager Version 2.8.0-alpha01
  - [Google Play Services updates](https://developers.google.com/android/guides/releases)
    - The latest updates to several libraries include using the latest versions of play-services-base and play-services-tasks (v18.0.1) to fix the issue described in the December 09, 2021 release.
  - [Compose to Kotlin Compatibility Map](https://developer.android.com/jetpack/androidx/releases/compose-kotlin)

### r/androiddev

- [Compose Destinations: simple and type-safe navigation in Jetpack Compose](https://www.reddit.com/r/androiddev/comments/rzsw78/compose_destinations_simple_and_typesafe/)
- [I dedicated 3 years to building this Android Contacts API library written in Kotlin with Java interop. I want to share it with the Reddit community for the first time.](https://www.reddit.com/r/androiddev/comments/rz370s/i_dedicated_3_years_to_building_this_android/)
- [Drawn A Summarized Fragment's Lifecycle Aware Coroutine Scope Behavior](https://www.reddit.com/r/androiddev/comments/ryv6fu/drawn_a_summarized_fragments_lifecycle_aware/)
- [Android dev has become impossible as a hobby](https://www.reddit.com/r/androiddev/comments/rybndr/android_dev_has_become_impossible_as_a_hobby/)
- [What is the thing you most struggle with when using Jetpack Compose?](https://www.reddit.com/r/androiddev/comments/rxmb0z/what_is_the_thing_you_most_struggle_with_when/)
  - みんな苦労してますな

### Other

- [The Ultimate Guide for Android Developers](https://androidtopics.dipien.com/the-ultimate-guide-for-android-developers-b11268ed21f7)
- [Gradle Enterprise Gradle Plugin v3.8.1](https://docs.gradle.com/enterprise/gradle-plugin/#release_history)
- [LeakCanary v2.8.1](https://square.github.io/leakcanary/changelog/)