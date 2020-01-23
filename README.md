# Responsive-User-UI
A Simple Library to Import a Responsive UI screens

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  	dependencies {
	        implementation 'com.github.hamze-ibraheem:Responsive-User-UI:1.1'
	}

Usage:

create a View in your xml file and import the login_layout,

    <include
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        layout="@layout/login_main"

	import com.taskfoundation.responsive_user_ui_lib.LoginActivity;

        LoginActivity loginActivity = new LoginActivity();
        /**
         * Example for getting the facebook login button object.
         */
        loginActivity.findViewById(R.id.login_facebook_button);
	
	
