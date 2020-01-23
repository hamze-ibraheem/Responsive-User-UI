# Responsive-User-UI
A Simple Library to Import a Responsive UI screens

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  	dependencies {
	        implementation 'com.github.hamze-ibraheem:Responsive-User-UI:1.0'
	}

Usage:

create a View in your xml file and import the login_layout,

    <View
        android:layout="@layout/login_main"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>
