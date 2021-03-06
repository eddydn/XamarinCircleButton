
This library for Xamarin.Android based on original library [Android Circle Button](https://github.com/markushi/android-circlebutton/blob/master/README.md)


E.g. the [Android Design Support Library](http://developer.android.com/tools/support-library/index.html) offers a [FAB](http://developer.android.com/reference/android/support/design/widget/FloatingActionButton.html) implementation.

#Xamarin Circle Button
====================

Circle button widget for Android

![Button Example](https://github.com/markushi/android-circlebutton/raw/master/example/example.gif)


Example Usage:
```
<FrameLayout
	xmlns:android="http://schemas.android.com/apk/res/android"
	xmlns:app="http://schemas.android.com/apk/res-auto"
	android:layout_width="match_parent"
	android:layout_height="match_parent" >

	<at.markushi.ui.CircleButton
		android:layout_width="64dip"
		android:layout_height="64dip"
		android:src="@drawable/ic_action_tick"
		app:cb_color="#99CC00"
		app:cb_pressedRingWidth="8dip" />

</FrameLayout>
```
