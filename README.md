# bare-bone-android.template

"Latest and greatest" template for Android project for kicking off new app or a library. 
There's few places that bear package name `uk.acm0x.template`, but simple Find & Replace fixing this if you borrowing this. 

### Few notes:
* Library versions are in `gradle/libs.versions.toml`
* build-logic module has its own gradle. Haven't figured this out yet.
* the minSdk and compileSdk sit in build-logic/convention/src/main/kotlin/uk/acm0x/template/AppDefaults.kt 

_Inspired by https://github.com/android/nowinandroid_
