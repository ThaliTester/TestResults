#### Test 575312431be71d2_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2166): Explicit concurrent mark sweep GC freed 21516(1266KB) AllocSpace objects, 6(864KB) LOS objects, 51% free, 30MB/62MB, paused 1.812ms total 50.621ms
--------- beginning of system
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1310351505551508465&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
D/AndroidRuntime( 6725): 
D/AndroidRuntime( 6725): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6725): CheckJNI is OFF
D/AndroidRuntime( 6725): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1971): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{37b698f2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{37b698f2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  349): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6740 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6725): Shutting down VM
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager( 1040): Display changed displayId=0
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
D/DSDPConnection( 1874): Display #0 changed.
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{19dcdf04 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{10165ced co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ContextHelper( 6740): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
W/ApiaryClient( 6661): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1310351505551508465&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,I/WebViewFactory( 6740): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6740): Loading: webviewchromium
,I/LibraryLoader( 6740): Time to load native libraries: 5 ms (timestamps 5080-5085)
I/LibraryLoader( 6740): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6740): Binding Chromium to main looper Looper (main, tid 1) {29c4fb4}
,I/LibraryLoader( 6740): Expected native library version number "",actual native library version number ""
I/chromium( 6740): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6740): Initializing chromium process, renderers=0
W/art     ( 6740): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6740): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6740): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6740): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  332): registerClient() client 0xb165c040, uid 10311
D/BluetoothManagerService( 1040): Message: 20
,D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fc322a2:true
I/Adreno-EGL( 6740): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6740): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6740): Build Date: 12/12/14 금
I/Adreno-EGL( 6740): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6740): Remote Branch: 
I/Adreno-EGL( 6740): Local Patches: 
I/Adreno-EGL( 6740): Reconstruct Branch: 
W/chromium( 6740): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6740): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6740): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6740): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6740): CordovaWebView is running on device made by: LGE
,W/art     ( 6740): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6740): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6740): Render dirty regions requested: true
I/OpenGLRenderer( 6740): Initialized EGL, version 1.4
D/OpenGLRenderer( 6740): Enabling debug mode 0
D/Atlas   ( 6740): Validating map...
,D/SplitWindow( 1040): check instance of lgWin Window{17a5024c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20edeaf3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6740): LgDataFeature() Constructor: none
D/LgDataFeature( 6740): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +569ms (total +690ms)
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{18850b43 u0 com.test.thalitest/.MainActivity t4} time:105489
,I/Timeline( 6740): Timeline: Activity_idle id: android.os.BinderProxy@18cd0de4 time:105493
I/chromium( 6740): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6740): 
,D/JsMessageQueue( 6740): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6740): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6740): 
,E/GBMv2   (  349): DFP En is all cleared set to be enabled
E/GBMv2   (  349): Set value is all cleared set the max
I/GBMv2   (  349): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 6740): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434982656
,I/chromium( 6740): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/BooksSync( 6661): Soft error: 
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1310351505551508465&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
,E/BooksSync( 6661): Sync error
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1310351505551508465&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
I/BooksSync( 6661): Finished books sync
I/ActivityManager( 1040): Killing 6310:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78440, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1040): failed to open /acct/uid_10004/pid_6310/cgroup.procs: No such file or directory
,I/GAV2    ( 6661): Thread[GAThread,5,main]: No campaign data found.
,I/MusicWidget( 2619): mDelayedStopHandler : unbind
,I/MusicBrowser( 2237): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2237): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2237): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2237): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2237): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2237): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1040):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@e866a13com.lge.music.MediaPlaybackService$5@13f2450
D/MusicBrowser( 2237): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@5eece9e
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2237): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2237): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2237): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2237): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2237): reset
V/MediaPlayer[Native]( 2237): setListener
V/MediaPlayer[Native]( 2237): disconnect
V/MediaPlayer[Native]( 2237): destructor
V/AudioFlinger(  332): releasing 13 from 2237 for -1
V/AudioFlinger(  332):  decremented refcount to 0
V/AudioFlinger(  332): purging stale effects
V/MediaPlayer[Native]( 2237): disconnect
,D/MusicBrowser( 2237): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,I/SmartShareClient( 2237): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2237): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2237): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2237): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2237): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2237): [SmartShareManagerClient] unregisterListener: 718472777
W/SmartShareClient( 2237): [SmartShareManagerClient] unregisterListener invalid listener: 718472777
I/SmartShareClient( 2237): [SmartShareManagerClient] terminate service: 2237/MediaPlaybackService/43798452
,E/HomeCloudIF( 2237): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2237): [SmartShareManagerClient] unbindService context:android.app.Application@2d3a1b4e
V/CloudHub( 2237): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2237): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2237): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2237): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1040): Killing 6431:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
W/libprocessgroup( 1040): failed to open /acct/uid_10008/pid_6431/cgroup.procs: No such file or directory
,W/jxcore-log( 6740): Initializing JXcore engine
W/jxcore-log( 6740): JXcore engine is ready
,W/Thread-794( 6814): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8485]" dev="sockfs" ino=8485 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-794( 6814): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-794( 6814): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7619]" dev="sockfs" ino=7619 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-794( 6814): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-794( 6814): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33096]" dev="sockfs" ino=33096 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6740): Starting JXcore engine
,W/jxcore-log( 6740): Platform android
W/jxcore-log( 6740): 
W/jxcore-log( 6740): Process ARCH arm
W/jxcore-log( 6740): 
,I/jxcore-log( 6740): JXcore Cordova bridge is ready!
I/jxcore-log( 6740): 
W/jxcore-log( 6740): JXcore engine is started
,I/jxcore-log( 6740): Toggling radios to true
I/jxcore-log( 6740): 
,D/BluetoothAdapter( 6740): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=6740, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1040): setWifiEnabled: true pid=6740, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=6740, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1040): reconnect pid=6740, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1040): [108,329,912 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
I/jxcore-log( 6740): Radios toggled
I/jxcore-log( 6740): 
I/jxcore-log( 6740): My device name is: LGE-LG-D855
I/jxcore-log( 6740): 
,I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1040): InitialState.processMessage what=4
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1040): DISCONNECT: returned true
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
,D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
,D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  328): Clearing all IP addresses on wlan0
,I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6837 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2166): Read error: ssl=0xaa6ff200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2166): SSL shutdown failed: ssl=0xaa6ff200: I/O error during system call, Broken pipe
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1971): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1040): [108,491,498 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNative-wlan0( 1040): RECONNECT: returned true
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=108498
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=108499
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  328): Clearing all IP addresses on wlan0
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
,D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): Dns fail occured do internet check.
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1040): try Internet connection check
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1040): stop dsqn bin
D/WifiHS20( 1040): hidePasspointNotification off =false
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=108547  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=108547  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1040): ThreadTCPConnectionCheck DNS fail internet is not possible
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1040): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1040): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
,E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 1040): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiDataContinuityService( 1040): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/WifiServiceExtension( 1971): isInternetCheckAvailable return false
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=108558  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=108564  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUs,ed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1040): StoppedState
D/DhcpStateMachine( 1040): StoppedState{ when=-100ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6837): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6837): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6837): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6053:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6053/cgroup.procs: No such file or directory
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6837): LgDataFeature() Constructor: none
D/LgDataFeature( 6837): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
,I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6897 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1040): Killing 6072:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6072/cgroup.procs: No such file or directory
,W/ResourcesManager( 6897): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6897): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6897): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6897): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6897): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6897): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6897): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6897): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6897): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6897): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6897): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 6897): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6897): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6897): LgDataFeature() Constructor: none
D/LgDataFeature( 6897): LgDataFeature() Constructor Done, null
,V/SoundPool( 6897): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6897): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6897): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6897): doLoad: loading sample sampleID=1
,V/SoundPool( 6897): Start decode
V/MediaPlayer[Native]( 6897): decode(31, 10857164, 17813)
I/QRemote ( 6897): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  332): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  332): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  332): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  332): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  332): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  332): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  332): player type = 3
V/AwesomePlayer(  332): AwesomePlayer create()
V/AwesomePlayer(  332): reset_l() 
V/AwesomePlayer(  332): cancelPlayerEvents
V/AwesomePlayer(  332): setAudioSink() 
V/AwesomePlayer(  332): reset_l() 
V/AudioCache(  332): notify(0xb1432fc0, 8, 0, 0)
V/AudioCache(  332): ignored
V/AwesomePlayer(  332): cancelPlayerEvents
D/Utils   (  332): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  332): setDataSource_l dataSource
V/LGParserOSAL(  332): SniffLGParser start
V/LGParserOSAL(  332): MainType:5, SubType=0
V/LGParserOSAL(  332): #### check Mime : application/ogg
V/LGParserOSAL(  332): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  332): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6613): QS Service created
D/QRemote ( 6897): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6897): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  332): supported mime: application/ogg
V/AwesomePlayer(  332): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  332): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  332): mBitrate = -1 bits/sec
V/AwesomePlayer(  332): AudioTrack Setting
V/AwesomePlayer(  332): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  332): setAudioSource() 
V/MediaPlayerService(  332): prepare
V/AwesomePlayer(  332): prepareAsync_l() 
V/MediaPlayerService(  332): wait for prepare
V/AwesomePlayer(  332): onPrepareAsyncEvent() 
V/AwesomePlayer(  332): initAudioDecoder() 
W/Utils   (  332): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  332): isOffloadSupported()
V/AudioPolicyManager(  332): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  332): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  332): isAudioPlaybackHookOn() false
V/AwesomePlayer(  332): getUseOffload() = 0 
V/OMXCodec(  332): OMXCodec::Create
V/OMXCodec(  332): findMatchingCodecs()
V/OMXCodec(  332): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  332): matchingCodecs.size()=1
V/OMXCodec(  332): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  332): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  332): LG Codec Adapter start
V/OMXCodec(  332): OMXCodec Createtor
V/OMXCodec(  332): setComponentRole
V/OMXCodec(  332): configureCodec protected=0
V/LGCodecAdapter(  332): called getLGCodecSpecificData
V/LGCodecOSAL(  332): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  332): Called LGconfigureCodecMETA
V/LGCodecOSAL(  332): Called LGconfigureCodecMSG
V/LGCodecOSAL(  332): Not support LGCodec
V/OMXCodec(  332): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  332): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  332): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  332): Could not, offload audio decode, try pcm offload
W/Utils   (  332): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  332): isOffloadSupported()
V/AudioPolicyManager(  332): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  332): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  332): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  332): init()
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  332): allocateBuffers
V/OMXCodec(  332): allocateBuffersOnPort portIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcb00 on input port
V/OMXCodec(  332): allocateBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcc40 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fce70 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf10 on output port
V/OMXCodec(  332): init() mAsyncCompletion wait!!! 
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  332): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  332): finishAsyncPrepare_l() 
V/AudioCache(  332): notify(0xb1432fc0, 5, 0, 0)
V/AudioCache(  332): ignored
V/AudioCache(  332): notify(0xb1432fc0, 1, 0, 0)
V/AudioCache(  332): prepared
V/AudioCache(  332): wait - success
V/MediaPlayerService(  332): start
V/AwesomePlayer(  332): play_l() 
V/AwesomePlayer(  332): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  332): createAudioPlayer_l
V/AwesomePlayer(  332): seekAudioIfNecessary_l() 
V/AwesomePlayer(  332): startAudioPlayer_l() 
D/AudioPlayer(  332): start of Playback, useOffload 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  332): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/LGMDMManager( 6897): Create singleton instance
V/OMXCodec(  332): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  332): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796864
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797424
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797504
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797584
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  332): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  332): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  332): allocateBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fce70 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcc40 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
V/OMXCodec(  332): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  332): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  332): notify(0xb1432fc0, 6, 0, 0)
V/AudioCache(  332): ignored
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab700000, 0xb57cf000, 4096)
V/MediaPlayerService(  332): wait for playback complete
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab701000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab702000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab703000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab704000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab705000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab706000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab707000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab708000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab709000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70a000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70b000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70c000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70d000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70e000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab70f000, 0xb57cf000, 4096)
I/UEI.SmartControl( 6613): Service initServices...
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab710000, 0xb57cf000, 4096)
D/UEI.SmartControl( 6613): QS start get config
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab711000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab712000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab713000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab714000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab715000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab716000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab717000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab718000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab719000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71a000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71b000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71c000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71d000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71e000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab71f000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab720000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab721000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab722000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab723000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab724000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab725000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab726000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab727000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab728000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab729000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72a000, 0xb57cf000, 4096)
,V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72b000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72c000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72d000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72e000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab72f000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab730000, 0xb57cf000, 4096)
V/AudioCache(  332): write(0xb57cf000, 4096)
V/AudioCache(  332): memcpy(0xab731000, 0xb57cf000, 4096)
V/OMXCodec(  332): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  332): postAudioEOS() 
V/AudioCache(  332): write(0xb57cf000, 280)
V/AudioCache(  332): memcpy(0xab732000, 0xb57cf000, 280)
,V/AwesomePlayer(  332): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  332): onStreamDone
V/AwesomePlayer(  332): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  332): notify(0xb1432fc0, 2, 0, 0)
V/AudioCache(  332): playback complete
V/AwesomePlayer(  332): pause_l() 
V/AudioCache(  332): notify(0xb1432fc0, 7, 0, 0)
V/AudioCache(  332): ignored
V/AudioCache(  332): wait - success
V/MediaPlayerService(  332): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  332): cancelPlayerEvents
D/AudioPlayer(  332): Pause Playback at 1068125
V/AwesomePlayer(  332): reset_l() 
V/AudioCache(  332): notify(0xb1432fc0, 8, 0, 0)
V/AudioCache(  332): ignored
V/AwesomePlayer(  332): cancelPlayerEvents
D/AudioPlayer(  332): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcb00 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcc40 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fce70 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcec0 on port 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  332): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  332): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  332): AudioPlayer releasing audio source
D/AudioPlayer(  332): AudioPlayer done releasing audio source
V/AwesomePlayer(  332): reset_l() 
,V/AwesomePlayer(  332): cancelPlayerEvents
V/AwesomePlayer(  332): ~AwesomePlayer call
V/AwesomePlayer(  332): reset_l() 
V/AwesomePlayer(  332): cancelPlayerEvents
V/SoundPool( 6897): close(31)
V/SoundPool( 6897): pointer = 0x9fe30000, size = 205080, sampleRate = 48000, numChannels = 2
D/DSQN    ( 1040): EVENT_INTERNET_CHECK_ENABLE received
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6897): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7739
I/UEI.SmartControl( 6613): Supports setup maps: true
,D/UEI.SmartControl( 6613): QS start statue = true Error code = 0
I/UEI.SmartControl( 6613): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6613): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6613): ### init IR Blaster...
D/serial_port( 6613): Configuring serial port
E/UEI.SmartControl( 6613): UEIBLaster setting for 616
I/UEI.SmartControl( 6613): Setting serial record hearder size = 2
I/UEI.SmartControl( 6613): configuring settings for MAXQ616
I/UEI.SmartControl( 6613): Get version...
D/UEI.SmartControl( 6613): serial port data available: 21
,D/UEI.SmartControl( 6613): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6613): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6613): QS saving settings...
D/UEI.SmartControl( 6613): IR Blaster version: 25672567
,D/UEI.SmartControl( 6613): serial port data available: 4
,W/ContextImpl( 6613): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6613): Services init done
D/UEI.SmartControl( 6613): QS Service init finished
D/UEI.SmartControl( 6613): QS Service version name: 2.1.91
D/UEI.SmartControl( 6613): QS Service version code: 201091
D/UEI.SmartControl( 6613): Service requested: Control
I/QRemote ( 6897): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6613): ------ IControl API: 11
D/UEI.SmartControl( 6613): File observer start...
E/UEI.SmartControl( 6613): IR Port is disabled: false
D/UEI.SmartControl( 6613): Starting file observer...
I/UEI.SmartControl( 6613): Registering callback...
I/UEI.SmartControl( 6613): ------ IControl API: 19
I/UEI.SmartControl( 6613): Registering Services Ready callback...
D/UEI.SmartControl( 6613): Internal service binding...
I/UEI.SmartControl( 6613): Device manager: loading config....
D/UEI.SmartControl( 6613): ----------- loading internal config...
E/UEI.SmartControl( 6613): Loading SETTINGS...
D/UEI.SmartControl( 6613): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6613): Notify AllClients services are ready: 0
I/QRemote ( 6897): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6897): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6897): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6897): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6897): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6613): ------ IControl API: 8
,D/UEI.SmartControl( 6613): -----service ready thread exits
D/QRemote ( 6897): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6897): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6897): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6897): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6897): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6897): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6897): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6897): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6897): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6897): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6897): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454419109036]
,D/QRemote ( 6897): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1040): Killing 6453:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 6897): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6453/cgroup.procs: No such file or directory
,V/QRemote ( 6897): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6897): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6897): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2730): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=110588  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=110604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
,D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
,D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2730): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=111061  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=111062  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111062
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111062
E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111062
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111063
,E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111063
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111066  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=111067  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateFOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6837): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6837): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6837): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/Tethering( 1040): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=false
I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7009 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7009): onCreate
,W/AppUp4:DB( 7009):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7009):  setFingerPrint start
I/AppUp4:DB( 7009):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7009):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7009):  SDK version = 21
I/AppUp4:DB( 7009):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7009): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7009): onReceive
,D/LgDataFeature( 7009): LgDataFeature() Constructor: none
D/LgDataFeature( 7009): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7009): Context : android.app.ReceiverRestrictedContext@5d30f52
D/AppUp4:CustFacade( 7009): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7009): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7009): begin check event
I/AppUp4:CustModeStarterReceiver( 7009): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7009): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7009): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7009): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7009): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6098:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6098/cgroup.procs: No such file or directory
,D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7037 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{1a787b2 type 0 when 1454419107772 android} when 1454419107772
V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{bd7d280 type 0 when 1454419109317 com.android.vending} when 1454419109317
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1c07d0b9 type 2 when 110909 com.google.android.gms} when 110909
,W/ResourcesManager( 7037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7037): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7037): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7037): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
I/LGEmail ( 7037): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7037): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7037): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7037): LgDataFeature() Constructor: none
D/LgDataFeature( 7037): LgDataFeature() Constructor Done, null
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/eas_req ( 7037): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6171): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6171): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6171): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7063 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7037): JNI_OnLoad()
I/HubEmail( 7037): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7037): registerNatives()
I/HubEmail( 7037): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7037): registerNativeMethods()
I/HubEmail( 7037): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7037): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1040): Killing 6487:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6487/cgroup.procs: No such file or directory
W/Settings( 7037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3372): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3372): networkInfo.isConnected() = false
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7090 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7063): Network not available. Please check & try again.
,V/FormManager( 7063): Network unavailable.
V/FormManager( 7063): Network unavailable.
I/ActivityManager( 1040): Killing 6124:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6124/cgroup.procs: No such file or directory
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 58028(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.592ms total 96.116ms
I/jxcore-log( 6740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6740): 
,I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7115 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6147:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10097/pid_6147/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7135 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6550:com.lge.eula/1000 (adj 15): empty #17
,E/WifiStateMachine( 1040):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6550/cgroup.procs: No such file or directory
,I/art     ( 7135): Almond Protected OAT
,I/jxcore-log( 6740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6740): 
,D/WeatherApplication( 7135): removeAccount
D/WeatherApplication( 7135): Account.length = 0
E/WeatherApplication( 7135): OPERATOR:OPEN
D/WeatherAncestor( 7135): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:32
,D/Weather.Utils( 7135): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7135): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7135): 2 : This is isUpdating : false
D/WeatherAncestor( 7135): connectivity changed - connection : true
D/WeatherService( 7135): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7135): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7135): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7135): 2 : Cache is not up-to-date, count: 0
I/jxcore-log( 6740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6740): 
,D/Weather_cast( 7135): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7135): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:32
I/jxcore-log( 6740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6740): 
I/jxcore-log( 6740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6740): 
,I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7153 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 5980:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  361): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.192ms total 21.959ms
,I/art     (  361): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 19.521ms
,I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.330ms total 27.341ms
,W/libprocessgroup( 1040): failed to open /acct/uid_10005/pid_5980/cgroup.procs: No such file or directory
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/wpa_supplicant( 2730): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=114089  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=114091  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114093
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114094
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1040): Got NetworkAgent Messenger
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1040): NetworkAgent connected
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/CommandListener(  328): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1040): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=114151  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=114152  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=114152  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=114153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=114153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=114154  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
,I/WebViewFactory( 7153): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7153): Loading: webviewchromium
I/LibraryLoader( 7153): Time to load native libraries: 3 ms (timestamps 4216-4219)
I/LibraryLoader( 7153): Expected native library version number "",actual native library version number ""
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb110d6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb110d6 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
D/CommandListener(  328): Setting iface cfg
D/CommandListener(  328): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
V/WebViewChromiumFactoryProvider( 7153): Binding Chromium to main looper Looper (main, tid 1) {2263946f}
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
I/LibraryLoader( 7153): Expected native library version number "",actual native library version number ""
I/chromium( 7153): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7153): Initializing chromium process, renderers=0
W/art     ( 7153): Attempt to remove local handle scope entry from IRT, ignoring
,D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1040): Adding iface wlan0 to network 101
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1971): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/chromium( 7153): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7153): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7153): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/AudioPolicyService(  332): registerClient() client 0xb57bd220, uid 10093
W/AudioManagerAndroid( 7153): Requires BLUETOOTH permission
I/Adreno-EGL( 7153): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7153): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7153): Build Date: 12/12/14 금
I/Adreno-EGL( 7153): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7153): Remote Branch: 
I/Adreno-EGL( 7153): Local Patches: 
I/Adreno-EGL( 7153): Reconstruct Branch: 
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  328): netlink response contains error (File exists)
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=tr,ue
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7214): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7214): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
,V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
,E/DSQN    ( 7214): DSQN ssw
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 1
,I/NSApplication( 7153): Starting up...
,D/libc-netbsd(  328): res_queryN name = clients3.google.com succeed
,I/ActivityManager( 1040): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7223 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6577:com.lge.bnr/1000 (adj 15): empty #17
D/LGDataListener(  328): argv[0]=dsqncommand
D/LGDataListener(  328): argv[1]=wlan0
D/LGDataListener(  328): argv[2]=1
D/LGDataListener(  328): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1040): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:18:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454419113421], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454419113403]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
,D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1040): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7242): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7242): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6509 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7242): version 5.5.6 starting
E/dhcpcd  ( 7242): get_duid: m
D/dhcpcd  ( 7242): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7242): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6577/cgroup.procs: No such file or directory
,D/dhcpcd  ( 7242): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7242): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7242): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7242): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 7242): wlan0: sending REQUEST (xid 0x808abfeb), next in 3.83 seconds
W/ResourcesManager( 7223): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] request level :IDLE....
,I/GLSActivity( 2166): [ac] getting account id
I/GLSUser ( 2166): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/AppUp4:CustModeStarterReceiver( 7009): onReceive
D/AppUp4:CustFacade( 7009): Context : android.app.ReceiverRestrictedContext@5d30f52
D/AppUp4:CustFacade( 7009): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7009): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7009): begin check event
I/AppUp4:CustModeStarterReceiver( 7009): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/UEI.SmartControl( 6613): Internal timer expired: 2
D/UEI.SmartControl( 6613): unbind internal service
V/DownloadManager( 3419): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
I/LGDMClient( 4320): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
,W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
E/LGDMClient( 4320): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LGDMClient( 4320): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LGDMClient( 4320): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
V/DownloadManager( 3419): DownloadService onCreate
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/eas_req ( 7037): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
I/DownloadManager( 3419): in removeSpuriousFiles
V/DownloadManager( 3419): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@1133f357 on behalf of 3419
V/DownloadManager( 3419): DownloadService onStartCommand
V/DownloadManager( 3419): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3419): in trimDatabase
V/DownloadManager( 3419): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@d9b3b2d on behalf of 3419
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@8ee1862 on behalf of 3419
I/LgeMiscReceiver( 3372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3372): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3372): networkInfo.isConnected() = false
,V/DownloadManager( 3419): processing inserted download 1
V/DownloadManager( 3419): processing inserted download 4
V/DownloadManager( 3419): processing inserted download 7
D/WeatherAncestor( 7135): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:34
V/DownloadManager( 3419): processing inserted download 8
V/DownloadManager( 3419): processing inserted download 9
W/Settings( 7037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3419): processing inserted download 10
W/Settings( 7037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Weather.Utils( 7135): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7135): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7135): 2 : This is isUpdating : false
D/WeatherAncestor( 7135): connectivity changed - connection : true
D/WeatherService( 7135): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@488b320
D/ForecastDataCache( 7135): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7135): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7135): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7135): 2 : isUpdateNeedForAlarm : no city return false
V/DownloadManager( 3419): processing inserted download 16
D/WeatherAncestor( 7135): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:34
V/DownloadManager( 3419): processing inserted download 17
V/DownloadManager( 3419): processing inserted download 18
V/DownloadManager( 3419): processing inserted download 21
V/DownloadManager( 3419): processing inserted download 22
V/DownloadManager( 3419): DownloadService onDestroy
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = static-avc.lglime.com, class = 1, type = 1
E/WifiStateMachine( 1040):  ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:50240] from screen [on:0 period:-1574799285]
E/WifiStateMachine( 1040):  L2ConnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1574799284]
E/WifiStateMachine( 1040): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-127
D/WifiNative-wlan0( 1040): doBoolean: SCAN TYPE=ONLY
D/WifiNative-wlan0( 1040): SCAN TYPE=ONLY: returned true
I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  328): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 4559): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/serial_port( 6613): close(fd = 24)
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/UEI.SmartControl( 6613): Serial port is closed.
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6897): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6897): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6897): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
,D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6897): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6897): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6897): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  328): res_queryN name = mtalk.google.com succeed
,E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
D/libc-netbsd(  328): res_queryN name = static-avc.lglime.com succeed
,I/dhcpcd  ( 7242): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7242): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7242): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7242): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7242): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7242): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7242): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7242): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7242): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,V/FormManager( 7063): There are no updated forms. The schedule will be deleted.
V/FormManager( 7063): Alarm would be updated, because LastCheckTime has been updated.
D/GCM     ( 2166): Connected
,D/GCM     ( 2166): Message class com.google.f.a.a.p
D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19985
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7009): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7009): onReceive
,D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AppUp4:CustFacade( 7009): Context : android.app.ReceiverRestrictedContext@5d30f52
,D/AppUp4:CustFacade( 7009): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7009): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7009): begin check event
I/AppUp4:CustModeStarterReceiver( 7009): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3419): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4320): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3419): DownloadService onCreate
,I/DownloadManager( 3419): in removeSpuriousFiles
,V/DownloadManager( 3419): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@2a330ab0 on behalf of 3419
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3419): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,I/DownloadManager( 3419): in trimDatabase
V/DownloadManager( 3419): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@391d5d29 on behalf of 3419
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3419): DownloadService onStartCommand
,W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3419): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3419): created cursor android.database.sqlite.SQLiteCursor@163621dc on behalf of 3419
E/LGDMClient( 4320): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4320): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4320): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3419): processing inserted download 1
V/DownloadManager( 3419): processing inserted download 4
V/DownloadManager( 3419): processing inserted download 7
W/Settings( 7037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3419): processing inserted download 8
V/DownloadManager( 3419): processing inserted download 9
V/DownloadManager( 3419): processing inserted download 10
V/DownloadManager( 3419): processing inserted download 16
V/DownloadManager( 3419): processing inserted download 17
V/DownloadManager( 3419): processing inserted download 18
I/LgeMiscReceiver( 3372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3372): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3372): networkInfo.isConnected() = true
D/PhoneState( 3372): setPdpRejectCasuse : false
,V/DownloadManager( 3419): processing inserted download 21
V/DownloadManager( 3419): processing inserted download 22
W/Settings( 7037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7135): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:36
D/Weather.Utils( 7135): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7135): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7135): 2 : This is isUpdating : false
D/WeatherAncestor( 7135): connectivity changed - connection : true
D/WeatherService( 7135): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@488b320
D/ForecastDataCache( 7135): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7135): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7135): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7135): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7135): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:18:36
,V/DownloadManager( 3419): DownloadService onDestroy
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1420): Notification difference=198
,D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7063): There are no updated forms. The schedule will be deleted.
V/FormManager( 7063): Alarm would be updated, because LastCheckTime has been updated.
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 118065810895; DSPS: 4009458; Offset : -4307545658
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine( 1040):  ConnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6837): Not supported operator for automatic switch
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  328): res_queryN name = www.google.com succeed
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  328): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7153): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6740): Test app app.js loaded
I/jxcore-log( 6740): 
,I/chromium( 6740): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6740): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e81120 added. We now have 1 listener(s)
,I/jxcore-log( 6740): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6740): 
I/ActivityManager( 1040): Killing 6015:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10014/pid_6015/cgroup.procs: No such file or directory
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{104d03df type 2 when 131406 android} when 131406
,V/QRemote ( 6897): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6897): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7739
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{8e4d2f5 type 0 when 1454419131478 com.android.vending} when 1454419131478
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6171): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6171): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6171): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2237): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 138067995731; DSPS: 4664890; Offset : -4307558479
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,E/WifiStateMachine( 1040):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1040):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1040):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1040):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 158069639786; DSPS: 5320304; Offset : -4307562059
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{18ce945c type 0 when 1454419153730 com.android.vending} when 1454419153730
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 67058(3MB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.666ms total 91.931ms
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6171): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6171): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6171): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2d8177de type 2 when 169309 android} when 169309
,I/BooksSync( 6661): Starting books sync
,D/BooksSync( 6661): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  328): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1823487842102489106&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
W/ResourcesManager( 1420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
W/ResourcesManager( 1420): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1420): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1823487842102489106&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1823487842102489106&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,E/BooksSync( 6661): Soft error: 
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1823487842102489106&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
,E/BooksSync( 6661): Sync error
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1823487842102489106&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
I/BooksSync( 6661): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169309, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 178072066133; DSPS: 5975744; Offset : -4307577250
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/WifiController( 1040): battery changed pluggedType: 2
,D/LEDHandler( 1971): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1971): Battery Level Remaining: 100%
D/LEDHandler( 1971): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3825): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{3ab1af31 type 0 when 1454419182253 com.android.vending} when 1454419182253
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6171): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6171): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6171): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 198073878469; DSPS: 6631163; Offset : -4307565763
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{484acab type 2 when 199350 android} when 199350
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 218075888253; DSPS: 7286589; Offset : -4307569931
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{105bcf08 type 2 when 209037 android} when 209037
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{185bc6a1 type 2 when 229377 android} when 229377
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{171ed0c6 type 2 when 185647 com.google.android.gms} when 185647
V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{262d3b4 type 0 when 1454419216092 com.android.vending} when 1454419216092
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,V/SIM_STK ( 1040): Menu title from STK is T-Mobile
I/BooksSync( 6661): Starting books sync
,D/BooksSync( 6661): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2166): Vacuum at: now=1454419229253 tag=VacuumService
I/GoogleURLConnFactory( 2166): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 2166): No account for auth token provided
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/libc-netbsd(  328): res_queryN name = play.googleapis.com succeed
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6171): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6171): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6171): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2166): No account for auth token provided
,W/Uploader( 2166): No account for auth token provided
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1164986107976679916&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,W/Uploader( 2166):  no longer exists, so no auth token.
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2166): Explicit concurrent mark sweep GC freed 46622(2MB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.482ms total 69.311ms
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
,D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1420): post do just update job
E/HttpHelper( 6661): null auth token
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1164986107976679916&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1040): Explicit concurrent mark sweep GC freed 26230(1140KB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 2.416ms total 145.792ms
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1164986107976679916&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,E/BooksSync( 6661): Soft error: 
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1164986107976679916&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
,E/BooksSync( 6661): Sync error
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1164986107976679916&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
I/BooksSync( 6661): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203970, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 238077709339; DSPS: 7942008; Offset : -4307549096
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 258079553185; DSPS: 8597429; Offset : -4307567134
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{17f5b386 type 2 when 260152 android} when 260152
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 278082182397; DSPS: 9252875; Offset : -4307562330
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2ff47447 type 2 when 295734 android} when 295734
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,I/BooksSync( 6661): Starting books sync
,D/BooksSync( 6661): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7514747577484675560&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6661): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7514747577484675560&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 298084142077; DSPS: 9908299; Offset : -4307556062
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7514747577484675560&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,E/BooksSync( 6661): Soft error: 
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7514747577484675560&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
,E/BooksSync( 6661): Sync error
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7514747577484675560&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
I/BooksSync( 6661): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 295734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 318085784412; DSPS: 10563713; Offset : -4307561467
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{20051579 type 2 when 325897 android} when 325897
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 338088309405; DSPS: 11219156; Offset : -4307569381
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 358091017991; DSPS: 11874604; Offset : -4307546082
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 6171): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6171): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6171): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6171): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6171): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6171): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6171): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6171): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  328): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  328): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 378092827410; DSPS: 12530024; Offset : -4307568004
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 398094883236; DSPS: 13185451; Offset : -4307556907
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 418096673385; DSPS: 13840870; Offset : -4307566982
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/LEDHandler( 1971): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1971): Battery Level Remaining: 100%
D/LEDHandler( 1971): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1040): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 3825): Disconnected process message: 10, size: 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1e279e0f type 2 when 422254 android} when 422254
V/AlarmManager( 1040): RTC_WAKEUP set : Alarm{37a10e9c type 0 when 1454419238252 com.google.android.gms} when 1454419238252
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,I/EventLogService( 2332): Aggregate from 1454417438190 (log), 1454417438190 (data)
,I/BooksSync( 6661): Starting books sync
D/BooksSync( 6661): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/HttpHelper( 6661): null auth token
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1767465243524319662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1767465243524319662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1420): handleNotificationPosted(true)
D/QuickCircle( 1420): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1420): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): post do just update job
D/LgeQuickCoverNotificationData( 1420): showAll3
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6661): Authentication error
E/BooksAccountManager( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6661): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{25a651ba V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6661): Error response from books API: {
W/ApiaryClient( 6661):  "error": {
W/ApiaryClient( 6661):   "errors": [
W/ApiaryClient( 6661):    {
W/ApiaryClient( 6661):     "domain": "global",
W/ApiaryClient( 6661):     "reason": "required",
W/ApiaryClient( 6661):     "message": "Login Required",
W/ApiaryClient( 6661):     "locationType": "header",
W/ApiaryClient( 6661):     "location": "Authorization"
W/ApiaryClient( 6661):    }
W/ApiaryClient( 6661):   ],
W/ApiaryClient( 6661):   "code": 401,
W/ApiaryClient( 6661):   "message": "Login Required"
W/ApiaryClient( 6661):  }
W/ApiaryClient( 6661): }
,W/ApiaryClient( 6661): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1767465243524319662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6661): Headers:
W/ApiaryClient( 6661): accept-encoding: [gzip]
W/ApiaryClient( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6661): gdata-version: 2
,E/BooksSync( 6661): Soft error: 
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1767465243524319662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
,E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
,E/BooksSync( 6661): Sync error
E/BooksSync( 6661): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6661): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1767465243524319662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6661): Headers:
E/BooksSync( 6661): accept-encoding: [gzip]
E/BooksSync( 6661): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6661): gdata-version: 2
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6661): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6661): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6661): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6661): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6661): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6661): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6661): {
E/BooksSync( 6661):  "error": {
E/BooksSync( 6661):   "errors": [
E/BooksSync( 6661):    {
E/BooksSync( 6661):     "domain": "global",
E/BooksSync( 6661):     "reason": "required",
E/BooksSync( 6661):     "message": "Login Required",
E/BooksSync( 6661):     "locationType": "header",
E/BooksSync( 6661):     "location": "Authorization"
E/BooksSync( 6661):    }
E/BooksSync( 6661):   ],
E/BooksSync( 6661):   "code": 401,
E/BooksSync( 6661):   "message": "Login Required"
E/BooksSync( 6661):  }
E/BooksSync( 6661): }
E/BooksSync( 6661): 
E/BooksSync( 6661): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6661): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6661): 	... 8 more
I/BooksSync( 6661): Finished books sync
D/SyncManager( 1040): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 422254, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 438098532492; DSPS: 14496291; Offset : -4307569501
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 458101109933; DSPS: 15151735; Offset : -4307555744
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{1df8e032 type 2 when 460125 android} when 460125
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 478103079143; DSPS: 15807160; Offset : -4307570151
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 498105100334; DSPS: 16462586; Offset : -4307563224
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 518107002982; DSPS: 17118008; Offset : -4307552562
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 538108948339; DSPS: 17773432; Offset : -4307560356
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 558111059426; DSPS: 18428861; Offset : -4307555164
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1040): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1040): InitialState.processMessage what=4
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=575651
E/WifiStateMachine( 1040):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=575651
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=575651
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
,D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/DhcpStateMachine( 1040): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  328): Clearing all IP addresses on wlan0
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,V/NativeCrypto( 2166): Read error: ssl=0xaa6ff200: I/O error during system call, Connection timed out
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6837): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6740): Toggling radios to false
I/jxcore-log( 6740): 
,D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1040): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ff2e183 mBinding = false
,D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6837): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6837): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6837): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6837): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=575808  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=575808  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=575811  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=575812  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,D/WifiHS20( 1040): hidePasspointNotification off =false
D/LocationManagerService( 1040): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1040): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1040): JNI:system_update. Event-4
D/BluetoothManagerService( 1040): Message: 2
V/NativeCrypto( 2166): SSL shutdown failed: ssl=0xaa6ff200: I/O error during system call, Broken pipe
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
V/WfdStateTracker( 1971): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/BluetoothManagerService( 1040): Sending off request.
D/LGBluetoothServiceAdapter( 3825): [BTUI] Precleanup
D/BluetoothAdapterState( 3825): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3825): Setting state to 13
I/BluetoothAdapterState( 3825): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3825): onBluetoothDisable()
I/BluetoothAdapterState( 3825): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
D/BluetoothManagerService( 1040): Message: 60
D/BluetoothManagerService( 1040): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1040): Bluetooth State Change Intent: 12 -> 13
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): stop dsqn bin
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/DhcpStateMachine( 1040): StoppedState
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceImplEx( 1040): setWifiEnabled: false pid=6740, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/BluetoothAdapterProperties( 3825): Scan Mode:20
D/BluetoothAdapterState( 3825): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3825): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/WifiService( 1040): setWifiEnabled: false pid=6740, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothSapService( 3825): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3825): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3825): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 3825): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x000f
V/BluetoothMapMasInstance( 3825): Accept exception: (exp,ected at shutdown)
V/BluetoothMapMasInstance( 3825): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3825): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3825): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3825): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3825): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3825): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3825): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-btif ( 3825): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3825): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3825): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3825): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3825): bta_gattc_deregister Deregister Failedm unknown client cif
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
,V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
I/jxcore-log( 6740): Radios toggled
I/jxcore-log( 6740): 
D/LocationManagerService( 1040): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1040):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
D/Ulp_jni ( 1040): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1040): JNI:system_update. Event-4
E/WifiStateMachine( 1040):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
I/BluetoothMapService( 3825): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3825): STATE_TURNING_OFF
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
V/BtOppService( 3825): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3825): Handler(): got msg=4
D/BluetoothMapService( 3825): MAP Service closeService in
D/BluetoothMapMasInstance( 3825): MAP Service shutdown
D/LGBluetoothMapAdapter( 3825): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3825): MAP Service closeService out
I/BtOppRfcommListener( 3825): stopping Accept Thread
V/BtOppRfcommListener( 3825): close mBtServerSocket
V/BtOppRfcommListener( 3825): waiting for thread to terminate
I/BtOppRfcommListener( 3825): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3825): done waiting for thread to terminate
D/LGBluetoothAPIService( 1971): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
V/BtOppService( 3825): onDestroy
D/LGWifiP2pService( 1040): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiMonitor( 1040): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@39bc6df1
D/LGBluetoothOppAdapter( 3825): [BTUI] LGBluetoothOppAdapter cleanup
W/ContextImpl( 6837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGWifiP2pService( 1040): P2pDisablingState
D/LGWifiP2pService( 1040): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): p2p socket connection lost
D/LGWifiP2pService( 1040): P2pDisabledState
D/WifiScanningService( 1040): SCAN_AVAILABLE : 1
D/RttService( 1040): SCAN_AVAILABLE : 1
E/WifiStateMachine( 1040):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
D/RttService( 1040): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2730): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiScanningService( 1040): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
V/WfdStateTracker( 1971): WfdStateTracker handleDirectStateChangedEvent: 0
D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/WfdsService( 1971): WifiP2pState is changed : false
D/CommandListener(  328): Clearing all IP addresses on wlan0
D/WfdsService( 1971): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1971): Set the WFDS Monitor: false
D/DhcpStateMachine( 1040): StoppedState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1971): WFDS Monitor is stopped
D/CtrlSupplicant( 1971): Received on exit socket, terminate
E/CtrlSupplicant( 1971): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsService( 1971): STATE : WfdsDisabledState - enter
D/WfdsMonitor( 1971): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1971): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1971): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1971): DefaultState - msg [9441355] is not handled
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-p2p0( 1040): doBoolean: TERMINATE
D/WifiNative-p2p0( 1040): TERMINATE: returned true
E/WifiStateMachine( 1040): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1040): useWiFiOffloading() : false
E/WifiStateMachine( 1040): CONFIG_LGE_WLAN_PATH : true
,D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1040):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_ON_QUIT 0 0
V/WfdStateTracker( 1971): WfdStateTracker handleDirectStateChangedEvent: 6
,I/WifiServerServiceExt( 1040): WIFI_STATE_CHANGED_ACTION [0]
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
V/BluetoothPbapReceiver( 3825): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3825): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3825): ***********state = 13
V/BluetoothPbapReceiver( 3825): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3825): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3825): state: 13
V/BluetoothPbapService( 3825): Pbap Service closeService in
,I/ActivityManager( 1040): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7607 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 3825): successfully stopped pbap service
V/BluetoothPbapService( 3825): Pbap Service closeService out
V/BluetoothPbapService( 3825): Pbap Service onDestroy
V/BluetoothPbapService( 3825): Pbap Service closeService in
V/BluetoothPbapService( 3825): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3825): [BTUI] cleanup
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1469): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 1040): Explicit concurrent mark sweep GC freed 57681(2MB) AllocSpace objects, 11(1200KB) LOS objects, 33% free, 44MB/66MB, paused 1.888ms total 141.570ms
D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@167812df:true
,D/BluetoothManagerService( 1040): Message: 30
,D/BluetoothManagerService( 1040): Message: 30
D/LocalBluetoothProfileManager( 6837): Adding local MAP profile
,D/BluetoothMap( 6837): Create BluetoothMap proxy object
D/BluetoothManagerService( 1040): Message: 30
,D/BluetoothManagerService( 1040): Message: 30
,D/LocalBluetoothProfileManager( 6837): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6837):  get() - isFeatureLoaded : false
E/ActivityThread( 7607): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7607): No ProfileInfo entries
I/LG Account v2.2( 7607): isEnabled: false
,I/Feature ( 7607): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7607): [Lifetracker]Country: EU
I/Feature ( 7607): [Lifetracker]Operator: OPEN
I/Feature ( 7607): [Lifetracker]Ranking support: false
I/Feature ( 7607): [Lifetracker]Comfort support: false
I/Feature ( 7607): [Lifetracker]Accessory: true
I/Feature ( 7607): [Lifetracker]Health device: true
I/Feature ( 7607): [Lifetracker]Extra Pedometer: false
I/Feature ( 7607): [Lifetracker]Blood glucose device: false
I/Feature ( 7607): [Lifetracker]Device Number: 3
D/LGBluetoothUserBindClient( 6837): [BTUI] initUserBindClient
,W/ContextImpl( 6837): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6837): finishStartingService: stopping service
,D/BluetoothInputDevice( 6837): Proxy object connected
,D/HidProfile( 6837): Bluetooth service connected
D/BluetoothPan( 6837): BluetoothPAN Proxy object connected
D/PanProfile( 6837): Bluetooth service connected
D/BluetoothMap( 6837): Proxy object connected
D/MapProfile( 6837): Bluetooth service connected
D/BluetoothMap( 6837): getConnectedDevices()
D/BluetoothMap( 6837): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6837): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 6837): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 6837): onReceive
D/LGBluetoothAuthorization( 6837): [BTUI] cancel All Notification
I/ActivityManager( 1040): Killing 2237:com.lge.music/u0a34 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6837): return without doing reset settings.
V/AudioFlinger(  332): 2237 died, releasing its sessions
V/AudioFlinger(  332):  pid 1874 @ 0
V/AudioFlinger(  332):  pid 3372 @ 1
V/AudioFlinger(  332):  pid 3372 @ 2
,V/BluetoothOppReceiver( 3825): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup( 1040): failed to open /acct/uid_10034/pid_2237/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3825): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 3825): [BTUI] cancel opp active transfer file notification
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpReceiver( 3825): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3825): BluetoothFtpReceiver Start Service
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/BluetoothFtpService( 3825): Ftp Service onStartCommand
V/BluetoothFtpService( 3825): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3825): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3825): Shutdown
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothFtpService( 3825): successfully stopped ftp service
V/BluetoothSapReceiver( 3825): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3825): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3825): SapReceiver onReceive 
V/BluetoothSapReceiver( 3825): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3825):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3825): Calling SAP service start service with action = null
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothFtpService( 3825): Ftp Service onDestroy
V/BluetoothFtpService( 3825): Ftp Service closeService
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothSapService( 3825): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3825): state: 13
V/BluetoothSapService( 3825): Stopping SAP server process
V/BluetoothSapService( 3825): Sap Service closeSapService in
V/BluetoothSapService( 3825): Close listen Socket : 
V/BluetoothSapService( 3825): Close rfcomm Socket : 
V/BluetoothSapService( 3825): Close sapd  Socket : 
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
I/ActivityManager( 1040): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7637 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3825): Sap Service closeSapService out
,V/BluetoothSapService( 3825): Sap Service onDestroy
V/BluetoothSapService( 3825): Sap Service closeSapService in
V/BluetoothSapService( 3825): Close listen Socket : 
V/BluetoothSapService( 3825): Close rfcomm Socket : 
V/BluetoothSapService( 3825): Close sapd  Socket : 
V/BluetoothSapService( 3825): Sap Service closeSapService out
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ResourcesManager( 7637): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2166): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6876): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/QRemote ( 6897): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6897): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6897): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7063): Network not available. Please check & try again.
V/FormManager( 7063): Network unavailable.
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
V/FormManager( 7063): Network unavailable.
I/ActivityManager( 1040): Killing 7009:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_7009/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3825): cleanup
,I/bt_lpm  ( 3825): LPM is already off!!!
I/bt_userial_mct( 3825): exiting userial_read_thread
D/bt_userial_mct( 3825): Leaving userial_evt_read_thread()
,W/bt-btif ( 3825): ag scb idx 1 not allocated
E/bt-btif ( 3825): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3825): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3825): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3825): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3825): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3825): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3825): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3825): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3825): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3825): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3825): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3825): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3825): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3825): hw_epilog_process
D/bt_hci_bdroid( 3825): cleanup Finalizing cleanup
D/bt_userial_mct( 3825): userial_close
E/bt_userial_mct( 3825): pthread_join() FAILED result:3
I/bt_vendor( 3825): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/bt_hci_bdroid( 3825): set_power 0
I/bt_vendor( 3825): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3825): bluetooth satus is on
I/bt_vendor( 3825): bt-vendor : resetting BT status
I/bt_vendor( 3825): Starting hciattach daemon
I/bt_vendor( 3825): try to set false
I/bt_vendor( 3825): Starting hciattach daemon
I/bt_vendor( 3825): try to set false
I/bt_vendor( 3825): cleanup
,I/GKI_LINUX( 3825): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3825): GKI_exit_task 0 done
I/GKI_LINUX( 3825): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3825): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3825): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 3825): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3825): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/HeadsetStateMachine( 3825): Exit Disconnected: -1
,D/BluetoothHeadset( 1040): Proxy object disconnected
D/AudioService( 1040): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
D/A2dpService( 3825): Received stop request...Stopping profile...
D/A2dpStateMachine( 3825): Exit Disconnected: -1
D/BluetoothAdapterState( 3825): Stopping profile services that were post enabled
,D/LGBluetoothAvrcpQcomAdapter( 3825): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3825): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3825): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/BluetoothA2dp( 1040): Proxy object disconnected
D/AudioService( 1040): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3825): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/HeadsetStateMachine( 3825): Unbinding service...
D/HeadsetPhoneState( 3825): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3825): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3825): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3825): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3825): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3825): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3825): [BTUI] LGBluetoothHfpAdapter cleanup
,D/HealthService( 3825): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/PanService( 3825): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/BtGatt.DebugUtils( 3825): handleDebugAction() action=null
D/BtGatt.GattService( 3825): Received stop request...Stopping profile...
D/BtGatt.GattService( 3825): stop()
D/BtGatt.AdvertiseManager( 3825): advertise clients cleared
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
D/BluetoothMapService( 3825): Received stop request...Stopping profile...
D/BluetoothMapService( 3825): stop()
,D/BluetoothMapEmailAppObserver( 3825): deinitObservers()
D/BluetoothMapEmailAppObserver( 3825): removeReceiver()
D/BluetoothAdapterService( 3825): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f4b223
I/BluetoothA2dpServiceJni( 3825): cleanupNative
I/GKI_LINUX( 3825): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3825): GKI_exit_task 2 done
I/GKI_LINUX( 3825): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3825): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3825): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3825): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3825): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3825): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3825): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3825): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3825): Handler(): got msg=4
D/BluetoothMapService( 3825): MAP Service closeService in
D/LGBluetoothMapAdapter( 3825): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3825): MAP Service closeService out
D/BluetoothAdapterState( 3825): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3825): Setting state to 10
I/BluetoothAdapterState( 3825): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3825): cleanup()
D/BluetoothMapService( 3825): MAP Service closeService in
D/LGBluetoothMapAdapter( 3825): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3825): MAP Service closeService out
D/BluetoothManagerService( 1040): Message: 60
D/BluetoothManagerService( 1040): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1040): Broadcasting onBluetoothStateChange(false) to 9 receivers.
,I/BluetoothAdapterState( 3825): Entering OffState
D/BluetoothMap( 6837): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1040): onBluetoothStateChange: up=false
D/BluetoothPbap( 6837): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothPan( 6837): onBluetoothStateChange on: false
D/BluetoothInputDevice( 6837): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1040): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1040): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1040): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1040): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1040): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1040): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ff2e183 mBinding = false
D/BluetoothManagerService( 1040): Sending unbind request.
I/GKI_LINUX( 3825): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3825): GKI_exit_task 1 done
I/GKI_LINUX( 3825): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3825): cleanupNative: return from cleanup
I/art     ( 3825): --- WEIRD: removing null entry 246
W/art     ( 3825): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3825): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3825): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1040): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3825): System.exit called, status: 0
I/AndroidRuntime( 3825): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  332): 3825 died, releasing its sessions
V/AudioFlinger(  332):  pid 1874 @ 0
V/AudioFlinger(  332):  pid 3372 @ 1
V/AudioFlinger(  332):  pid 3372 @ 2
,D/LGBluetoothAPIService( 1971): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1971): Message: 101
E/LGBluetoothAPIService( 1971): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1971): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1971): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 6837): [BTUI] onServiceDisconnected
I/ActivityManager( 1040): Process com.android.bluetooth (pid 3825) has died
W/ActivityManager( 1040): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
W/ActivityManager( 1040): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,D/LGBluetoothAPIService( 1971): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1971): Message: 2
I/[SystemUI]BluetoothHandler( 1469): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1971): unbindAndFinish(): null mBinding = false
D/LGBluetoothFeatureConfig( 6837): isPrivacyLogsEnabled : true
,E/LGBluetoothEventManager( 6837): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6837): [BTUI] clear device connection state
W/ContextImpl( 6837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapter( 1469): 729366549: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1469): 729366549: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager( 1040): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7683 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 6837): finishStartingService: stopping service
,W/ResourcesManager( 7683): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7683): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7683): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7683): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7683): Loading JNI Library
,D/BluetoothAdapterApp( 7683): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3eb58b08 Instance Count = 1
,D/BluetoothAdapterApp( 7683): onCreate
,D/ProfileConfigQcom( 7683): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7683): Adding HeadsetService
D/ProfileConfigQcom( 7683): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7683): Adding A2dpService
,D/ProfileConfigQcom( 7683): [BTUI] HidService is supported
D/ProfileConfigQcom( 7683): Adding HidService
D/ProfileConfigQcom( 7683): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7683): Adding HealthService
D/LGBluetoothFeatureConfig( 7683): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 7683): [BTUI] PanService is supported
D/ProfileConfigQcom( 7683): Adding PanService
D/ProfileConfigQcom( 7683): [BTUI] GattService is supported
D/ProfileConfigQcom( 7683): Adding GattService
,D/ProfileConfigQcom( 7683): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7683): Adding BluetoothMapService
D/ProfileConfigQcom( 7683): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7683): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 7683): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 7683): ***********state = 10
,V/LGMDMManagerInternal( 7683): Create singleton instance
D/LGBluetoothAPIServer( 7683): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7683): [BTUI] onBind()
D/LGBluetoothAPIService( 1971): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1971): Message: 100
D/LGBluetoothAPIService( 1971): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LGBluetoothUserBindClient( 6837): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6837): onReceive
,D/LGBluetoothUtils( 6837): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6837): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 6837): return without doing reset settings.
D/LGBluetoothOppAdapter( 7683): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7683): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7683): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7683): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7683): SapReceiver onReceive 
V/BluetoothSapReceiver( 7683): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7683):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7637): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2166): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2730): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2730): monitor socket send errors count : 1
,I/wpa_supplicant( 2730): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1971-2\x00 that cannot receive messages
,W/wpa_supplicant( 2730): USIM:  scard_deinit function
D/WifiMonitor( 1040): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1040): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=577830  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1040):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=577831  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,I/wpa_supplicant( 2730): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1040): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1040):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
D/WfdsService( 1971): Supplicant Connection state is changed : false
D/WfdsService( 1971): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1971): Set the WFDS Monitor: false
D/WfdsMonitor( 1971): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1040): stopMonitoring
E/WifiStateMachine( 1040): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1040): useWiFiOffloading() : false
E/WifiStateMachine( 1040): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1971): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1040): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1040): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1040): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 6876): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 6876): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6876): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6837): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6837): MCCMNC not supported: null
D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/FormManager( 7063): Network unavailable.
V/FormManager( 7063): Network unavailable.
W/FormManager( 7063): Network not available. Please check & try again.
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{2db75d63 type 2 when 577991 com.google.android.gms} when 577991
D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 578112945511; DSPS: 19084283; Offset : -4307560934
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/Tethering( 1040): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5477): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7738 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7738): onCreate
W/AppUp4:DB( 7738):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7738):  setFingerPrint start
I/AppUp4:DB( 7738):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7738):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7738):  SDK version = 21
I/AppUp4:DB( 7738):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7738): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7738): onReceive
,D/LgDataFeature( 7738): LgDataFeature() Constructor: none
,D/LgDataFeature( 7738): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7738): Context : android.app.ReceiverRestrictedContext@5d30f52
D/AppUp4:CustFacade( 7738): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7738): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7738): begin check event
I/AppUp4:CustModeStarterReceiver( 7738): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7738): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7738): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7738): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7738): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1040): Killing 7037:com.lge.email/u0a23 (adj 15): empty #17
,D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_7037/cgroup.procs: No such file or directory
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7776 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7776): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7776): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7776): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7776): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7776): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7776): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7776): LgDataFeature() Constructor: none
D/LgDataFeature( 7776): LgDataFeature() Constructor Done, null
,D/eas_req ( 7776): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3372): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3372): networkInfo.isConnected() = false
,D/WeatherAncestor( 7135): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:18
,D/Weather.Utils( 7135): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7135): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7135): 2 : This is isUpdating : false
D/WeatherAncestor( 7135): connectivity changed - connection : true
D/WeatherService( 7135): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@488b320
D/ForecastDataCache( 7135): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7135): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7135): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7135): 2 : isUpdateNeedForAlarm : no city return false
V/FormManager( 7063): Network unavailable.
D/WeatherAncestor( 7135): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:18
I/HubEmail( 7776): JNI_OnLoad()
I/HubEmail( 7776): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7776): registerNatives()
I/HubEmail( 7776): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7776): registerNativeMethods()
I/HubEmail( 7776): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7776): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/FormManager( 7063): Network not available. Please check & try again.
V/FormManager( 7063): Network unavailable.
,W/Settings( 7776): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager( 1040): Killing 6171:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10044/pid_6171/cgroup.procs: No such file or directory
,I/iu.Environment( 2332): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2332): num queued entries: 0
I/iu.UploadsManager( 2332): num updated entries: 0
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.SyncManager( 2332): NEXT; no task
,D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7738): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7738): onReceive
,D/AppUp4:CustFacade( 7738): Context : android.app.ReceiverRestrictedContext@5d30f52
,D/AppUp4:CustFacade( 7738): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7738): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7738): begin check event
I/AppUp4:CustModeStarterReceiver( 7738): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4320): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7776): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4320): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7776): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7063): Network not available. Please check & try again.
I/LgeMiscReceiver( 3372): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3372): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3372): networkInfo.isConnected() = false
V/FormManager( 7063): Network unavailable.
V/FormManager( 7063): Network unavailable.
,D/WeatherAncestor( 7135): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:19
D/Weather.Utils( 7135): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7135): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7135): 2 : This is isUpdating : false
D/WeatherAncestor( 7135): connectivity changed - connection : true
D/WeatherService( 7135): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@488b320
,D/ForecastDataCache( 7135): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7135): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7135): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7135): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7135): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:26:19
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LGWifiP2pService( 1040): P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1040): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1040):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1040):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{396b369f type 2 when 582230 com.google.android.gms} when 582230
,D/libc-netbsd(  328): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 598115048004; DSPS: 19739712; Offset : -4307564233
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 618117069038; DSPS: 20395138; Offset : -4307557385
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 638119077207; DSPS: 21050564; Offset : -4307563350
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
,I/ActivityManager( 1040): Killing 6661:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10054/pid_6661/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 658121732252; DSPS: 21706011; Offset : -4307563308
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 678123553963; DSPS: 22361431; Offset : -4307572522
,V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{3b44e3ec type 2 when 679112 android} when 679112
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 698125569632; DSPS: 23016857; Offset : -4307571169
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 718127445875; DSPS: 23672278; Offset : -4307556472
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 738129566075; DSPS: 24327708; Offset : -4307572529
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 758131686225; DSPS: 24983137; Offset : -4307558066
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 778133504081; DSPS: 25638557; Offset : -4307571290
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 798135541052; DSPS: 26293983; Offset : -4307548479
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=844909271, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
,I/ActivityManager( 1040): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7862 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2636): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7862): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7862): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@32615487
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=844909271 [*alarm*], flags=0x0
I/ActivityManager( 1040): Killing 6613:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6897): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6897): android.os.DeadObjectException
W/System.err( 6897): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6897): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6897): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6897): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6897): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6897): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6897): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6897): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6897): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6897): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6897): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6897): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6897): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6897): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6897): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6897): android.os.DeadObjectException
W/System.err( 6897): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6897): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6897): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6897): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6897): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6897): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6897): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6897): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6897): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6897): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6897): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6897): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6897): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6897): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6897): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6897): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6613/cgroup.procs: No such file or directory
,W/ActivityManager( 1040): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6897): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,I/QRemote ( 6897): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1040): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6897): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7900): Quickset Services start...
,I/UEI.SmartControl( 7900): Manufacture = LGE
D/UEI.SmartControl( 7900): Id = LGNevo
D/UEI.SmartControl( 7900): File observer start...
E/UEI.SmartControl( 7900): IR Port is disabled: false
D/UEI.SmartControl( 7900): Starting file observer...
D/UEI.SmartControl( 7900): Extracting JNI libs...
D/UEI.SmartControl( 7900): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7900): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7900): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7900): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7900): --- Selecting new region: 6
,I/UEI.SmartControl( 7900): Model = LG-D855
D/UEI.SmartControl( 7900): QS Service created
I/UEI.SmartControl( 7900): Service initServices...
,D/UEI.SmartControl( 7900): QS start get config
D/UEI.SmartControl( 7900): Loading JNI Libs...
,I/UEI.SmartControl( 7900): Supports setup maps: true
,D/UEI.SmartControl( 7900): QS start statue = true Error code = 0
,I/UEI.SmartControl( 7900): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7900): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7900): ### init IR Blaster...
D/serial_port( 7900): Configuring serial port
E/UEI.SmartControl( 7900): UEIBLaster setting for 616
I/UEI.SmartControl( 7900): Setting serial record hearder size = 2
I/UEI.SmartControl( 7900): configuring settings for MAXQ616
I/UEI.SmartControl( 7900): Get version...
,D/UEI.SmartControl( 7900): serial port data available: 21
,D/UEI.SmartControl( 7900): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7900): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 7900): QS saving settings...
,D/UEI.SmartControl( 7900): IR Blaster version: 25672567
D/UEI.SmartControl( 7900): serial port data available: 4
,I/UEI.SmartControl( 7900): Device manager: loading config....
,D/UEI.SmartControl( 7900): ----------- loading internal config...
,W/ContextImpl( 7900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7900): Services init done
D/UEI.SmartControl( 7900): QS Service init finished
,D/UEI.SmartControl( 7900): QS Service version name: 2.1.91
D/UEI.SmartControl( 7900): QS Service version code: 201091
,D/UEI.SmartControl( 7900): Service requested: Control
,E/UEI.SmartControl( 7900): Loading SETTINGS...
D/UEI.SmartControl( 7900): Request IControl service: devices are loaded...
,I/ActivityManager( 1040): Killing 6897:com.lge.qremote/u0a112 (adj 15): empty #17
I/QRemote ( 6897): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7900): ------ IControl API: 11
I/UEI.SmartControl( 7900): Registering callback...
D/UEI.SmartControl( 7900): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7900): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7900): -----service ready thread exits
D/UEI.SmartControl( 7900): Internal service binding...
W/libprocessgroup( 1040): failed to open /acct/uid_10112/pid_6897/cgroup.procs: No such file or directory
,D/serial_port( 7900): close(fd = 25)
,I/UEI.SmartControl( 7900): Serial port is closed.
,D/UEI.SmartControl( 7900): Internal timer expired: 1
,D/UEI.SmartControl( 7900): unbind internal service
,D/UEI.SmartControl( 7900): Service.onUnbind: IControl
,D/UEI.SmartControl( 7900): Service.onDestroy
,D/UEI.SmartControl( 7900): Lock is in USE false
,D/UEI.SmartControl( 7900): unbind internal service
,W/System.err( 7900): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@5eece9e
W/System.err( 7900): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,W/System.err( 7900): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7900): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,W/System.err( 7900): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7900): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7900): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7900): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,W/System.err( 7900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7900): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/System.err( 7900): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7900): ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7900): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 7900): 	,at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,W/System.err( 7900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/UEI.SmartControl( 7900): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@5eece9e
I/UEI.SmartControl( 7900): Serial port is closed.
,I/UEI.SmartControl( 7900): Serial port is closed.
D/UEI.SmartControl( 7900): Blaster closed
,D/UEI.SmartControl( 7900): Shut down QS...
D/UEI.SmartControl( 7900): Stopping QS lib
D/UEI.SmartControl( 7900): QS lib stop result = true
D/UEI.SmartControl( 7900): Stopped QS lib
D/UEI.SmartControl( 7900): Stopped file observer...
D/UEI.SmartControl( 7900): QS shutdown complete
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 818137637295; DSPS: 26949412; Offset : -4307557949
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 838139683693; DSPS: 27604839; Offset : -4307556021
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 858142123009; DSPS: 28260279; Offset : -4307558319
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
D/WifiController( 1040): battery changed pluggedType: 2
,D/LEDHandler( 1971): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1971): Battery Level Remaining: 100%
D/LEDHandler( 1971): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 878144186126; DSPS: 28915707; Offset : -4307570398
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 898146018618; DSPS: 29571127; Offset : -4307568908
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 918148104965; DSPS: 30226555; Offset : -4307557835
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 938150756520; DSPS: 30882002; Offset : -4307561205
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 958152785575; DSPS: 31537429; Offset : -4307576906
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 978154574890; DSPS: 32192847; Offset : -4307557610
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 998156639205; DSPS: 32848275; Offset : -4307568438
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1018158205031; DSPS: 33503686; Offset : -4307558983
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1038160698409; DSPS: 34159128; Offset : -4307567994
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1058162552724; DSPS: 34814549; Offset : -4307575330
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1078164544123; DSPS: 35469974; Offset : -4307567547
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1098166367969; DSPS: 36125394; Offset : -4307574782
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1118168231555; DSPS: 36780815; Offset : -4307572847
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1138170262642; DSPS: 37436241; Offset : -4307555919
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/WifiController( 1040): battery changed pluggedType: 2
D/LEDHandler( 1971): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1971): Battery Level Remaining: 100%
D/LEDHandler( 1971): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
,I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4320): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1158172375238; DSPS: 38091670; Offset : -4307548854
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1178174307678; DSPS: 38747094; Offset : -4307569748
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1198176323660; DSPS: 39402520; Offset : -4307567821
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1218178324277; DSPS: 40057945; Offset : -4307551030
,I/UsageStatsService( 1040): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1238179797499; DSPS: 40713354; Offset : -4307573246
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1258181947648; DSPS: 41368784; Offset : -4307558964
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1278183810869; DSPS: 42024205; Offset : -4307557445
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1298185874976; DSPS: 42679633; Offset : -4307568429
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1318188053510; DSPS: 43335064; Offset : -4307556773
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 1338190821367; DSPS: 43990515; Offset : -4307566043
D/AndroidRuntime( 7989): 
D/AndroidRuntime( 7989): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7989): CheckJNI is OFF
D/AndroidRuntime( 7989): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1040): Killing 6740:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1040): WIN DEATH: Window{17a5024c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1040): Client connection lost with reason: 4
D/InputDispatcher( 1040): Window went away: Window{17a5024c u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1040): Skipping PackageSetting{2d91107b com.example.hello/10319} due to missing metadata
I/ActivityManager( 1040):   Force finishing activity ActivityRecord{18850b43 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  349): DFP En is all cleared set to be enabled
W/ActivityManager( 1040): Spurious death for ProcessRecord{10c75a97 6740:com.test.thalitest/u0a311}, curProc for 6740: null
I/ActivityManager( 1040): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1040):   Force finishing activity ActivityRecord{18850b43 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1040): Duplicate finish request for ActivityRecord{18850b43 u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2090): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{3623f722 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1971): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1971): topRunningActivity=ActivityInfo{8e8c5b3 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2090): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1040): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2046): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3734): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/PostponalbeReceiver( 6399): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1925): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000003)
W/System.err( 4559): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4559): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4559): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4559): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4559): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4559): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4559): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4559): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4559): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4559): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4559): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4559): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SplitUIManager( 1891): split_name #11 / not available #0
D/SplitUIService( 1891): removed split : 
I/ActivityManager( 1040): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8021 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2090): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2090): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2090): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1925): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2090): , create_time: 1430558575574
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2090): , create_time: 1430558575600
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/GBoardWebViewUtils( 2090): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2090): , create_time: 1453982950152
I/GBoardWebViewUtils( 2090): , expire_time: 0
I/GBoardWebViewUtils( 2090): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2090): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2090): , display: false
I/GBoardWebViewUtils( 2090): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2090): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/SplitUIManager( 1891): split_name #11 / not available #0
I/SplitUIService( 1891): split app #11
I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20edeaf3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 4604): Explicit concurrent mark sweep GC freed 15266(888KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 382us total 110.786ms
I/[LGHome]EVENT( 2090): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2090): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 7738): added Exclude : com.test.thalitest
I/art     ( 1040): Explicit concurrent mark sweep GC freed 49371(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 44MB/66MB, paused 1.685ms total 161.066ms
I/art     ( 1040): WaitForGcToComplete blocked for 151.837ms for cause Explicit
I/LockScreenSettings( 8021): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager( 1040): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8041 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 2090): Background sticky concurrent mark sweep GC freed 4378(207KB) AllocSpace objects, 2(32KB) LOS objects, 0% free, 79MB/79MB, paused 10.034ms total 17.292ms
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/administrator( 1040): Handling package changes for user 0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/[LGHome]EVENT( 2090): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8041): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8041): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8041): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8041): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
I/ActivityManager( 1040): Killing 7607:com.lge.lifetracker/u0a37 (adj 15): empty #17
V/SIM_STK ( 1040): Menu title from STK is T-Mobile
I/ThermalEngine(  343): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3168): Thermal-Lib-Client: Client request sent
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/NotificationService( 1040): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1040): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1040): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2090): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2090): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1469): handleShortcutListChanged...
W/libprocessgroup( 1040): failed to open /acct/uid_10037/pid_7607/cgroup.procs: No such file or directory
I/art     ( 1040): Explicit concurrent mark sweep GC freed 7577(449KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.448ms total 182.660ms
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{28985c22 u0 com.lge.launcher2/.Launcher t3} time:1339342
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/[Concierge]Service( 2636): onStartCommand(). Type : 8
D/[Concierge]Service( 2636): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2636): Update widget ID : 11
D/[Concierge]WidgetView( 2090): change position of spinner
D/TaskPersister( 1040): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemConfig( 8041): BUILD Country: EU
I/SystemConfig( 8041): BUILD Operator: OPEN
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/[Concierge]Service( 2636): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2090): initWebView(). Time : 1454420338375
D/KeyguardModel( 1469): handleShortcutListChanged...
I/[Concierge]WebView( 2090): Return exist ConciergeWebView. Reuse : 546884178
D/[Concierge]WidgetView( 2090): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2090): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@4c540d3
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2090): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2090): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2090): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2090): Widget kill message received. Destory myself. My : 1454419027127, New one : 1454420338375
D/[Concierge]WidgetView( 2090): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2090): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/ActivityManager( 1040): Killing 7637:com.lge.settings.easy/1000 (adj 15): empty #17
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2090): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2090): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2090): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7989): Shutting down VM
I/Timeline( 2090): Timeline: Activity_idle id: android.os.BinderProxy@14fde937 time:1339457
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_7637/cgroup.procs: No such file or directory
I/SystemConfig( 8041): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8041): existFile = false
I/SystemConfig( 8041): canReadFile = false
I/SystemConfig( 8041): systemFeature RCS result false
D/SystemConfig( 8041): refreshRcsSupport() :false
I/PackageChangeReceiver( 7776): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2147): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1040): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8066 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/art     (  361): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 9.354ms
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.748ms
I/art     (  361): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.786ms
W/ResourcesManager( 8066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2090): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/AppConfig( 8066): Total System Memory = 2995761152
D/SystemHelper( 8066): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1040): Killing 6876:com.lge.sync/1000 (adj 15): empty #17
I/GBoardtInterface( 2090): onReloaded()
I/GBoardWebViewClient( 2090): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2046): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2046): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6876/cgroup.procs: No such file or directory
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Service_LIAService( 2046): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6399): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1040): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8086 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3734): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2090): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2090): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 8086): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 8086): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8086): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8086): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8086): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8086): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 8086): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8086): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 8086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8086): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8086): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 8086): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 8086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 8086): Unable to open database for writing.
E/LifetrackerProvider2( 8086): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 8086): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 8086): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 8086): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 8086): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 8086): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 8086): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 8086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 8086): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 8086): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 8086): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 8086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 8086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 8086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/ActivityThread( 8086): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 8086): No ProfileInfo entries
I/LG Account v2.2( 8086): isEnabled: false
I/Feature ( 8086): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 8086): [Lifetracker]Country: EU
I/Feature ( 8086): [Lifetracker]Operator: OPEN
I/Feature ( 8086): [Lifetracker]Ranking support: false
I/Feature ( 8086): [Lifetracker]Comfort support: false
I/Feature ( 8086): [Lifetracker]Accessory: true
I/Feature ( 8086): [Lifetracker]Health device: true
I/Feature ( 8086): [Lifetracker]Extra Pedometer: false
I/Feature ( 8086): [Lifetracker]Blood glucose device: false
I/Feature ( 8086): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 8086): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 6837): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 6837): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 6837): replacing : false
D/HideNavigationAppsReceiver( 6837): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 6837): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 6837): replacing : false
I/ActivityManager( 1040): Killing 7063:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10026/pid_7063/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 4604): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE

```
