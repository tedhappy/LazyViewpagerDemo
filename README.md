# LazyViewpagerDemo

不会预加载的ViewPager

## 用法

1. 拷贝LazyViewPager.java到工程
2. 在布局中使用
    <com.example.why.view.LazyViewPager
        android:id="@+id/viewpager"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent" />
3. Activity中找到控件
LazyViewPager viewpager = (LazyViewPager)findViewById(R.id.viewpager);

