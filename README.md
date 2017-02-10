# HOW TO CREATE TAB ACTIVITY IN ANDROID

Follow the below steps

1) In `activity_main.xml` file add below code


    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        android:orientation="vertical"
        android:id="@+id/activity_main"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:paddingBottom="@dimen/activity_vertical_margin"
        android:paddingLeft="@dimen/activity_horizontal_margin"
        android:paddingRight="@dimen/activity_horizontal_margin"
        android:paddingTop="@dimen/activity_vertical_margin"
        xmlns:app="http://schemas.android.com/apk/lib/com.app.chasebank"
        tools:context="in.gauriinfotech.tabdemo.MainActivity">

        <android.support.design.widget.TabLayout
            android:id="@+id/tabs"
            app:tabGravity="fill"
            app:tabMode="fixed"
            android:layout_width="fill_parent"
            android:layout_height="50dp">

        </android.support.design.widget.TabLayout>
        <android.support.v4.view.ViewPager
            android:id="@+id/viewPager"
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight=".7">

        </android.support.v4.view.ViewPager>

    </LinearLayout>

