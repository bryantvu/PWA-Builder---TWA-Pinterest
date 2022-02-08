# Pinterest TWA

This Android project is a TWA built using [PWABuilder](https://www.pwabuilder.com). While PWA Builder can automatically generate an APK without the Android Studio IDE, it is very simple for a developer with some Android experience to modify this project directly to test how different websites work on a TWA.

This option might be better if:
-   There are issues using PWA Builder to generate an APK.
-  The target website does not satisfy the requirements to be considered a PWA. 

## FAQ
1.  What is a PWA?  
    PWA = Progress Web Application. Web apps that are built with modern APIs to deliver enhanced capabilities, reliability, and a better end user experience that is closer to native mobile app.  [https://web.dev/what-are-pwas/](https://web.dev/what-are-pwas/)
2.  What is PWA Builder?  
    [PWABuilder.com](https://www.pwabuilder.com/)  is a Microsoft open-source tool to package PWAs for mobile app stores.
3.  What is the ideal use case for using a TWA?  
-   Owner of host URL does not have already an Android app
-   PWABuilder.com will only generate an APK when the host URL passes the PWA test (on PWA Builder.com). Non-PWA websites cannot be used to generate PWA APKs.

## Testing Setup
-  ['app/build.gradle', line 26](https://github.com/bryantvu/PWA-Builder---TWA-Pinterest/blob/4fd0c6f08e95cf1a31eed181d33c70e5c93edbb9/app/build.gradle#L26) replace 'hostName' with the url of your desired website. 
	- Correct URL format: "www.pinterest.com"
	- Incorrect URL format: "https://www.pinterest.com"
-  ['app/build.gradle', line 29](https://github.com/bryantvu/PWA-Builder---TWA-Pinterest/blob/4fd0c6f08e95cf1a31eed181d33c70e5c93edbb9/app/build.gradle#L29) (optional) replace 'launcherName' with your desired app name.

