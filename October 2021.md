# Android Weekly Updates (October 2021)

## 10/24 ~
`
### Google Developers

- [Android 12 を AOSP で公開！](https://android-developers-jp.googleblog.com/2021/10/android-12-is-live-in-aosp.html)
- [デベロッパーのニーズに合わせてビジネスモデルを進化させます](https://android-developers-jp.googleblog.com/2021/10/evolving-business-model.html)
  
---

## 10/17 ~

### Google Developers

- [Evolving our business model to address developer needs](https://android-developers.googleblog.com/2021/10/evolving-business-model.html)
- [Paging: Displaying data and its loading state - MAD Skills](https://www.youtube.com/watch?v=OHH_FPbrjtA&list=PLWz5rJ2EKKc9L-fmWJLhyXrdPi1YKmvqS&index=5)
- [android developers backstage - Episode 177: Honor every photon](https://adbackstage.libsyn.com/episode-177-honor-every-photon)
- [Launching Data safety in Play Console: Elevating Privacy and Security for your users](https://android-developers.googleblog.com/2021/10/launching-data-safety-in-play-console.html)
  - なんか面倒そうなの来た

### Other

- [Gradle Plugin v3.1.0](https://github.com/dipien/releases-hub-gradle-plugin)
- [Gradle Enterprise Plugin v3.7.1](https://docs.gradle.com/enterprise/gradle-plugin/#release_history)

## 10/10 ~

---

### Google Developers

- [Android Studio Chipmunk Canary 1 available](https://androidstudio.googleblog.com/2021/10/android-studio-chipmunk-canary-1.html)
- [Using CameraX Exposure Compensation API](https://medium.com/androiddevelopers/using-camerax-exposure-compensation-api-11fd75785bf)
- [Happy 5th birthday, Google Assistant!](https://blog.google/products/assistant/happy-5th-birthday-google-assistant/?utm_source=tw&utm_medium=social&utm_campaign=og&utm_content=&utm_term=)
  - もっと前からある気がしてた。
- [Compose for Wear OS now in Developer Preview!](https://android-developers.googleblog.com/2021/10/compose-for-wear-os-now-in-developer.html)
- [Paging: Fetching data from network - MAD Skills](https://www.youtube.com/watch?v=C0H54K63Lww)
- [Room & Kotlin Symbol Processing](https://medium.com/@yigit/room-kotlin-symbol-processing-24808528a28e)
  - [Tweet](https://twitter.com/yigitboyar/status/1447292073778974722)
- [lib updates](https://developer.android.com/jetpack/androidx/versions/all-channel#october_13_2021)
  - [Activity v1.4.0-rc01](https://developer.android.com/jetpack/androidx/releases/activity#1.4.0-rc01)
  - [Browser v1.4.0-rc01](https://developer.android.com/jetpack/androidx/releases/browser#1.4.0-rc01)
  - [Camera v1.1.0-alpha10](https://developer.android.com/jetpack/androidx/releases/camera#1.1.0-alpha10), [Camera v1.0.0-alpha30](https://developer.android.com/jetpack/androidx/releases/camera#1.0.0-alpha30)
    - Added @RequiresApi(21) annotation to all CameraX classes and dropped minSdkVersion from AndroidManifest.xml.
  - [Collection v1.2.0-beta01](https://developer.android.com/jetpack/androidx/releases/collection#1.2.0-beta01)
  - Compose v1.0.4
  - [Core v1.7.0-rc01](https://developer.android.com/jetpack/androidx/releases/core#1.7.0-rc01)
  - [Media v1.4.3](https://developer.android.com/jetpack/androidx/releases/media#media-1.4.3)
  - [Paging v3.1.0-beta01](https://developer.android.com/jetpack/androidx/releases/paging#3.1.0-beta01)
  - [Paging Compose v1.0.0-alpha14](https://developer.android.com/jetpack/androidx/releases/paging#1.0.0-alpha14)
  - [Room v2.4.0-beta01](https://developer.android.com/jetpack/androidx/releases/room#2.4.0-beta01)
  - [Sqlite v2.2.0-beta01](https://developer.android.com/jetpack/androidx/releases/sqlite#2.2.0-beta01)
  - [WorkManager v2.7.0](https://developer.android.com/jetpack/androidx/releases/work#2.7.0)
    - WorkManager introduces a new WorkRequest.Builder.setExpedited(...) API to help with Foreground Service restrictions in Android 12.
  - [Lint Api v30.0.3]()
  - [Gradle Plugin v7.0.3]()

### r/androiddev

- [LiveData is superior to StateFlow for UI and ViewModel layer.](https://www.reddit.com/r/androiddev/comments/q46b23/livedata_is_superior_to_stateflow_for_ui_and/)
- [What are your favorite shortcuts or features in Android Studio?](https://www.reddit.com/r/androiddev/comments/q5thme/what_are_your_favourite_shortcuts_or_features_in/)
- [Ads are now able to bypass Google Play to install apps WITHOUT user consent. Digital Turbine DSP seems to be the one enabling it.](https://www.reddit.com/r/androiddev/comments/q4nltn/ads_are_now_able_to_bypass_google_play_to_install/)
  - [こいつ](https://www.digitalturbine.com/operators/#tns1-mw)を使うと Google Play をバイパスしてアプリのインストールができるらし。
  - キャリアのロムでなければ心配なし。
  - 日本だとこれだけかな？ com.dti.samsung のパッケージのアプリがいればやばい。

### Other

- [Wake Me Up](https://github.com/romainguy/sample-wake-me-up)
  - Wake Me Up is a sample app showcased in the Google I/O 2021 Developer Keynote that demonstrates interoperability between Jetpack Compose and the Android UI Toolkit, including fragments, SurfaceView, and more.
  - [Tweet](https://twitter.com/romainguy/status/1448718190062682112)
- [Kotlin Symbol Processing is now stable! 🎉](https://twitter.com/kotlin/status/1447918226269220875?t=w4Fuvfz5AnU4PseSvYiQJQ&s=03)
- [Book Club #1: Talking "Androids: The Team That Built the Android Operating System" — with Chet Haase](https://www.youtube.com/watch?v=qofj1-f5FdA)
- [38. Compose internals spelunking — with Jake Wharton](https://www.youtube.com/watch?v=VX6nAvRWQg4)
- [Releases Hub Gradle Plugin](https://blog.dipien.com/releases-hub-gradle-plugin-v3-0-0-a27c18798d81)

---

## 10/01 ~

### Google Developers

- [Apply special effects to images with the CameraX Extensions API](https://medium.com/androiddevelopers/apply-special-effects-to-images-with-the-camerax-extensions-api-d1a169b803d3)
- [Pixel Fall Launch](https://pixelevent.withgoogle.com/)
  - 日本時間 10 月 20 日深夜 2 時
- [Now in Android #48](https://medium.com/androiddevelopers/now-in-android-48-c499493bb83)
  - 先週公表した内容のまとめ的な感じ
- [Create an advanced widget](https://developer.android.com/guide/topics/appwidgets/advanced)
  - Widget 周りのドキュメント更新 [Tweet](https://twitter.com/thagikura/status/1445664749786583047)
- [Android 12 is live in AOSP!](https://android-developers.googleblog.com/2021/10/android-12-is-live-in-aosp.html)
  - 31 のソースコードダウンロード開始
- [Answering your top questions on Android Game Development Kit](https://android-developers.googleblog.com/2021/10/answering-your-top-questions-on-android.html)
- library updates
  - [Dagger/Hilt v2.39.1](https://github.com/google/dagger/releases)
