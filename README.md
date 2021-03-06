# android-note

### Commom issues

#### Memory leaks
* [Garena explanation](https://engineering.garena.com/memory-leaks-in-android/)

### Material Guideline

#### [Material Components from Google](https://github.com/material-components/material-components-android/blob/master/docs/getting-started.md)

#### Style and Theme
* [Google Guide](https://developer.android.com/guide/topics/ui/look-and-feel/themes)

#### Use Toolbar
* [CodePath Guide](https://guides.codepath.com/android/using-the-app-toolbar#using-toolbar-as-actionbar)

#### Font size guide
* [Learnui.design](https://learnui.design/blog/android-material-design-font-size-guidelines.html)

#### Search/filer in a list
* [Androidhive](https://www.androidhive.info/2017/11/android-recyclerview-with-search-filter-functionality/)
1. `Adapter` implements `Filterable`
2. Use `dataSource` & `filteredDatasource` (`filteredDatasource` is the main list of `Adapter`)
3. `SearchView|EditText` calls: `adapter.getFilter().filter(charSequence)`

#### Custom EditText to make PIN view
* [Medium-PinEntryEdittext](https://medium.com/@ali.muzaffar/building-a-pinentryedittext-in-android-5f2eddcae5d3)


#### Custom Views Guide
* [Kipalog - IndicatorView](https://kipalog.com/posts/Android--Hieu-sau-hon-ve-CustomView-va-Huong-dan-xay-dung-thu-vien-UI-IndicatorView)
 - View's LifeCycle: `init -> onMeasure(đo đạc và xác định width height) -> onLayout (có width height + toạ độ 4 góc) -> onDraw (vẽ view)` 
* [Kipalog - Facebook Reaction](https://kipalog.com/posts/Android-2D-Graphics--Phan-tich-va-mo-phong-nut-cam-xuc-cua-Android-Facebook-Application)
* [Video explanation](https://academy.realm.io/posts/360andev-huyen-tue-dao-measure-layout-draw-repeat-custom-views-and-viewgroups-android/)

#### Drop shadow for view/textview
* [Youtube](https://www.youtube.com/watch?v=nNHChjTZCtw)
* [Github - materialshadowninepatch](https://github.com/h6ah4i/android-materialshadowninepatch)
* [Github - Carbon](https://github.com/ZieIony/Carbon)
* [Github - Material Shadow](https://github.com/harjot-oberai/MaterialShadows)

### News in Android

#### ConstraintLayout
* [Mastering ConstraintLayout](https://www.youtube.com/watch?v=rzmB3UxxhaA)
* [Mastering ConstraintLayout 2](https://www.youtube.com/watch?v=ytZteMo4ETk)
* Note:
1. Tools attribute: live data when creating layout
2. Advanced animation

#### [Android Architecture Component](https://developer.android.com/topic/libraries/architecture/)

#### Good examples [CodeLabs](https://codelabs.developers.google.com/)

#### [Support library and cool things](https://developer.android.com/topic/libraries/support-library/features)
* `PercentRelativeLayout, PercentFrameLayout`
* `AppCompatDialogFragment = DialogFragment + AppCompatDialog`
* `CoordinatorLayout, AppBarLayout`
* `Vector drawables`

#### [Android Jetpack - Quick build Android apps using components](https://developer.android.com/jetpack/)
* [Raywenderlich guide](https://www.raywenderlich.com/5365-jetpack-navigation-controller)
* [Google-Getting started](https://developer.android.com/jetpack/docs/getting-started)

### KOTLIN lang

#### [Android Offical](https://developer.android.com/kotlin/)

### Android platform Docs & Guides

#### [Android Developer](https://developer.android.com/docs/)

### Android Studio guide

#### [Android Developer](https://developer.android.com/studio/intro/)

### Dagger 

#### [Android Dagger (2.11–2.16) Butterknife (8.7-8.8) MVP (Part 1)](https://proandroiddev.com/how-to-android-dagger-2-10-2-11-butterknife-mvp-part-1-eb0f6b970fd)

### Clean Architecture

#### [hantrungkien_github](https://github.com/hantrungkien/android-clean-architecture-components-boilerplate)
