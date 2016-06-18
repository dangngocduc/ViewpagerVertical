#  VerticalViewPager
 A ViewPager allow croll vertical not use ViewPager.PageTransformer 
### setup 
in your file gradle  : 
```groovy 
android {
...
    repositories {
           maven {
                url 'https://dl.bintray.com/dangngocduc/maven'
        }
   } 
   
 }
```

add line below  to  _dependencies_
```groovy
compile 'android.dangngocduc:viewpagervertical:2.1.0'
```
### Usage
> Using this library like Viewpager support v4  
```xml
 <viewpager.dangngocduc.android.library.ViewPagerVertical
        android:id="@+id/container"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        />
```

## DEMO

