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
