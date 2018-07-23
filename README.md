# android-note

### Material Guideline

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
