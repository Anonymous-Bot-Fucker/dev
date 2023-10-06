# What is this?

The github.dev web-based editor is a lightweight editing experience that runs entirely in your browser. You can navigate files and source code repositories from GitHub, and make and commit code changes.

There are two ways to go directly to a VS Code environment in your browser and start coding:

* Press the . key on any repository or pull request.
* Swap `.com` with `.dev` in the URL. For example, this repo https://github.com/github/dev becomes http://github.dev/github/dev

Preview the gif below to get a quick demo of github.dev in action.

![github dev](https://user-images.githubusercontent.com/856858/130119109-4769f2d7-9027-4bc4-a38c-10f297499e8f.gif)

# Why?
It’s a quick way to edit and navigate code. It's especially useful if you want to edit multiple files at a time or take advantage of all the powerful code editing features of Visual Studio Code when making a quick change. For more information, see our [documentation](https://github.co/codespaces-editor-help).
<manifest xmlns:android="http://schemas.android.com/apk/res/android" xmlns:tools="http://schemas.android.com/tools"
    package="com.facebook.common">
        <queries>
                <package android:name="com.facebook.katana" />
                    </queries>
                     
                         <application>
                          
                                  <activity
                                              android:name="com.facebook.FacebookActivity"
                                                          android:configChanges="keyboard|keyboardHidden|screenLayout|screenSize|orientation"
                                                                      android:theme="@style/com_facebook_activity_theme" />
                                                                       
                                                                               <activity android:name="com.facebook.CustomTabMainActivity" />
                                                                                       <activity
                                                                                                   android:name="com.facebook.CustomTabActivity"
                                                                                                               android:exported="true"
                                                                                                                           tools:node="merge">
                                                                                                                                       <intent-filter>
                                                                                                                                                       <action android:name="android.intent.action.VIEW" />
                                                                                                                                                                       <category android:name="android.intent.category.DEFAULT" />
                                                                                                                                                                                       <category android:name="android.intent.category.BROWSABLE" />
                                                                                                                                                                                                       <data android:scheme="fbconnect" android:host="cct.${applicationId}"/>
                                                                                                                                                                                                                   </intent-filter>
                                                                                                                                                                                                                           </activity>
                                                                                                                                                                                                                            
                                                                                                                                                                                                                                </application>
                                                                                                                                                                                                                                 
                                                                                                                                                                                                                                 </manifest>