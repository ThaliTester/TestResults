#### Test 5813565532fb33b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
W/ApiaryClient( 6822): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3060861744605324835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
D/AndroidRuntime( 6878): 
D/AndroidRuntime( 6878): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6878): CheckJNI is OFF
D/AndroidRuntime( 6878): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1973): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{10695c15 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{10695c15 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  330): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6899 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6878): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1876): Display #0 changed.
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{3e20ec69 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{3e42d6ee co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6899): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6899): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6899): Loading: webviewchromium
I/LibraryLoader( 6899): Time to load native libraries: 4 ms (timestamps 4023-4027)
I/LibraryLoader( 6899): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6899): Binding Chromium to main looper Looper (main, tid 1) {186ca659}
I/LibraryLoader( 6899): Expected native library version number "",actual native library version number ""
I/chromium( 6899): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6899): Initializing chromium process, renderers=0
W/art     ( 6899): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  314): registerClient() client 0xb1427580, uid 10311
W/chromium( 6899): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6899): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6899): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37f0cff7:true
I/Adreno-EGL( 6899): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6899): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6899): Build Date: 12/12/14 금
I/Adreno-EGL( 6899): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6899): Remote Branch: 
I/Adreno-EGL( 6899): Local Patches: 
I/Adreno-EGL( 6899): Reconstruct Branch: 
W/chromium( 6899): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6899): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6899): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6899): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6899): CordovaWebView is running on device made by: LGE
W/art     ( 6899): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6899): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6899): Render dirty regions requested: true
I/OpenGLRenderer( 6899): Initialized EGL, version 1.4
D/OpenGLRenderer( 6899): Enabling debug mode 0
D/Atlas   ( 6899): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{8150239 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3e8b9696,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgDataFeature( 6899): LgDataFeature() Constructor: none
D/LgDataFeature( 6899): LgDataFeature() Constructor Done, null
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Timeline( 6899): Timeline: Activity_idle id: android.os.BinderProxy@2c76d7c9 time:104387
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +567ms (total +664ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{2428cb2a u0 com.test.thalitest/.MainActivity t4} time:104409
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
W/ApiaryClient( 6822): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3060861744605324835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
I/chromium( 6899): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6899): 
D/JsMessageQueue( 6899): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6899): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435227392
I/chromium( 6899): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6899): 
I/chromium( 6899): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/BooksSync( 6822): Soft error: 
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3060861744605324835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
E/BooksSync( 6822): Sync error
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3060861744605324835&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
I/BooksSync( 6822): Finished books sync
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78900, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1037): Killing 6377:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6377/cgroup.procs: No such file or directory
,E/GBMv2   (  330): DFP En is all cleared set to be enabled
E/GBMv2   (  330): Set value is all cleared set the max
I/GBMv2   (  330): DFP Enabled. Ignore VFP set
,I/GAV2    ( 6822): Thread[GAThread,5,main]: No campaign data found.
,I/MusicWidget( 2626): mDelayedStopHandler : unbind
,I/MusicBrowser( 2221): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2221): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2221): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2221): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2221): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2221): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1037):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3aa754fccom.lge.music.MediaPlaybackService$5@2c0c2785
D/MusicBrowser( 2221): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3fd1281b
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2221): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2221): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2221): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2221): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2221): reset
V/MediaPlayer[Native]( 2221): setListener
V/MediaPlayer[Native]( 2221): disconnect
V/MediaPlayer[Native]( 2221): destructor
V/AudioFlinger(  314): releasing 13 from 2221 for -1
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
,V/MediaPlayer[Native]( 2221): disconnect
D/MusicBrowser( 2221): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2221): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2221): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2221): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2221): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2221): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2221): [SmartShareManagerClient] unregisterListener: 185960922
W/SmartShareClient( 2221): [SmartShareManagerClient] unregisterListener invalid listener: 185960922
,W/jxcore-log( 6899): Initializing JXcore engine
W/jxcore-log( 6899): JXcore engine is ready
I/SmartShareClient( 2221): [SmartShareManagerClient] terminate service: 2221/MediaPlaybackService/409773657
,E/HomeCloudIF( 2221): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2221): [SmartShareManagerClient] unbindService context:android.app.Application@c84e0b
V/CloudHub( 2221): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2221): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2221): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2221): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1037): Killing 6522:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2221): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
W/Thread-814( 6956): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8353]" dev="sockfs" ino=8353 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-814( 6956): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-814( 6956): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7602]" dev="sockfs" ino=7602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-814( 6956): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-814( 6956): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33157]" dev="sockfs" ino=33157 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6522/cgroup.procs: No such file or directory
,W/jxcore-log( 6899): Starting JXcore engine
,W/jxcore-log( 6899): Platform android
W/jxcore-log( 6899): 
W/jxcore-log( 6899): Process ARCH arm
W/jxcore-log( 6899): 
,I/jxcore-log( 6899): JXcore Cordova bridge is ready!
I/jxcore-log( 6899): 
,W/jxcore-log( 6899): JXcore engine is started
,I/jxcore-log( 6899): Toggling radios to true
I/jxcore-log( 6899): 
,D/BluetoothAdapter( 6899): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6899, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6899, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1037): disconnect pid=6899, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [107,787,859 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=6899, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6899): Radios toggled
I/jxcore-log( 6899): 
I/jxcore-log( 6899): My device name is: LGE-LG-D855
I/jxcore-log( 6899): 
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1037): InitialState.processMessage what=4
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/DhcpStateMachine( 1037): RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  309): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2148): Read error: ssl=0xaf455600: I/O error during system call, Connection timed out
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2148): SSL shutdown failed: ssl=0xaf455600: I/O error during system call, Broken pipe
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [107,958,922 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/WifiHS20( 1037): hidePasspointNotification off =false
V/WfdStateTracker( 1973): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-wlan0( 1037): RECONNECT: returned true
,E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=107985
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=107987
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  309): Clearing all IP addresses on wlan0
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): Dns fail occured do internet check.
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1037): try Internet connection check
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108058  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1037): hidePasspointNotification off =false
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_REST,RICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108063  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/DSQN    ( 1037): ThreadTCPConnectionCheck DNS fail internet is not possible
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1037): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1037): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1037): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/WifiDataContinuityService( 1037): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServiceExtension( 1973): isInternetCheckAvailable return false
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 6967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6967): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6967): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6967): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6967): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6967): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-168ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6967): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6967): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6967): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7011 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6120:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6120/cgroup.procs: No such file or directory
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6967): LgDataFeature() Constructor: none
D/LgDataFeature( 6967): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7035 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6146:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6146/cgroup.procs: No such file or directory
,W/ResourcesManager( 7035): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7035): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7035): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7035): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7035): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7035): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7035): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7035): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7035): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7035): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7035): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7035): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7035): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7035): LgDataFeature() Constructor: none
D/LgDataFeature( 7035): LgDataFeature() Constructor Done, null
,V/SoundPool( 7035): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7035): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7035): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7035): doLoad: loading sample sampleID=1
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_ENABLE received
I/QRemote ( 7035): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7035): Start decode
V/MediaPlayer[Native]( 7035): decode(31, 10857164, 17813)
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
,V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1163140, 8, 0, 0)
,V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
,D/QRemote ( 7035): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6711): QS Service created
E/QRemote ( 7035): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6711): Service initServices...
D/UEI.SmartControl( 6711): QS start get config
V/LGMDMManager( 7035): Create singleton instance
V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
V/AwesomePlayer(  314): initAudioDecoder() 
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AwesomePlayer(  314): getUseOffload() = 0 
V/OMXCodec(  314): OMXCodec::Create
V/OMXCodec(  314): findMatchingCodecs()
V/OMXCodec(  314): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  314): matchingCodecs.size()=1
V/OMXCodec(  314): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
,V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMSG
V/LGCodecOSAL(  314): Not support LGCodec
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  314): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  314): Could not offload audio decode, try pcm offload
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434a10 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434c90 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb1163140, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb1163140, 1, 0, 0)
V/AudioCache(  314): prepared
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): start
V/AwesomePlayer(  314): play_l() 
V/AwesomePlayer(  314): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  314): createAudioPlayer_l
V/AwesomePlayer(  314): seekAudioIfNecessary_l() 
V/AwesomePlayer(  314): startAudioPlayer_l() 
D/AudioPlayer(  314): start of Playback, useOffload 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975824
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977104
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977744
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434a10 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1a0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb1163140, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab602000, 0xb1249000, 4096)
,V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab603000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab604000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab605000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab606000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab607000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab608000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab609000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60a000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60b000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60c000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60d000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60e000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab60f000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab610000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab611000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab612000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab613000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab614000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab615000, 0xb1249000, 4096)
,V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab616000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab617000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab618000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab619000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61a000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61b000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61c000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61d000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61e000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab61f000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab620000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab621000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab622000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab623000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab624000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab625000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab626000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab627000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab628000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab629000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62a000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62b000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62c000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62d000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62e000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab62f000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab630000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab631000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab632000, 0xb1249000, 4096)
V/AudioCache(  314): write(0xb1249000, 4096)
V/AudioCache(  314): memcpy(0xab633000, 0xb1249000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb1249000, 280)
V/AudioCache(  314): memcpy(0xab634000, 0xb1249000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb1163140, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb1163140, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): Pause Playback at 1068125
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  314): reset_,l() 
V/AudioCache(  314): notify(0xb1163140, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1a0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434a10 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  314): AudioPlayer releasing audio source
D/AudioPlayer(  314): AudioPlayer done releasing audio source
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): ~AwesomePlayer call
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/SoundPool( 7035): close(31)
V/SoundPool( 7035): pointer = 0x9fe5c000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 46303(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.571ms total 92.328ms
,D/QRemote ( 7035): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5850
I/UEI.SmartControl( 6711): Supports setup maps: true
,D/UEI.SmartControl( 6711): QS start statue = true Error code = 0
I/UEI.SmartControl( 6711): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6711): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6711): ### init IR Blaster...
D/serial_port( 6711): Configuring serial port
E/UEI.SmartControl( 6711): UEIBLaster setting for 616
I/UEI.SmartControl( 6711): Setting serial record hearder size = 2
I/UEI.SmartControl( 6711): configuring settings for MAXQ616
I/UEI.SmartControl( 6711): Get version...
D/UEI.SmartControl( 6711): serial port data available: 21
,D/UEI.SmartControl( 6711): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6711): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6711): QS saving settings...
D/UEI.SmartControl( 6711): IR Blaster version: 25672567
D/UEI.SmartControl( 6711): serial port data available: 4
,I/UEI.SmartControl( 6711): Device manager: loading config....
,D/UEI.SmartControl( 6711): ----------- loading internal config...
W/ContextImpl( 6711): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6711): Services init done
D/UEI.SmartControl( 6711): QS Service init finished
D/UEI.SmartControl( 6711): QS Service version name: 2.1.91
D/UEI.SmartControl( 6711): QS Service version code: 201091
D/UEI.SmartControl( 6711): Service requested: Control
E/UEI.SmartControl( 6711): Loading SETTINGS...
,D/UEI.SmartControl( 6711): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6711): Internal service binding...
I/QRemote ( 7035): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6711): ------ IControl API: 11
D/UEI.SmartControl( 6711): File observer start...
,E/UEI.SmartControl( 6711): IR Port is disabled: false
D/UEI.SmartControl( 6711): Starting file observer...
I/UEI.SmartControl( 6711): Registering callback...
I/UEI.SmartControl( 6711): ------ IControl API: 19
I/UEI.SmartControl( 6711): Registering Services Ready callback...
D/UEI.SmartControl( 6711): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6711): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6711): -----service ready thread exits
,I/QRemote ( 7035): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7035): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7035): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7035): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7035): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6711): ------ IControl API: 8
D/QRemote ( 7035): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7035): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7035): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7035): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7035): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7035): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7035): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7035): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7035): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7035): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 7035): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454527834589]
D/QRemote ( 7035): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6547:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7035): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6547/cgroup.procs: No such file or directory
,V/QRemote ( 7035): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7035): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7035): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=110100  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=110108  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7087
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7088
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7090
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{11d520f4 type 0 when 1454527833139 android} when 1454527833139
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7115 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3881901d type 2 when 111209 com.google.android.gms} when 111209
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7115): onCreate
W/AppUp4:DB( 7115):  [AppBoxDatabaseHelper] construct
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1e0ba463 type 0 when 1454527836233 com.android.vending} when 1454527836233
,I/AppUp4:DB( 7115):  setFingerPrint start
,I/AppUp4:DB( 7115):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7115):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7115):  SDK version = 21
I/AppUp4:DB( 7115):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7115): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7115): onReceive
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/LgDataFeature( 7115): LgDataFeature() Constructor: none
D/LgDataFeature( 7115): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7115): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7115): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7115): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7115): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7138 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7138): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7138): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7138): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6234): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6234): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6234): [1] 5.onFinished: Scheduling replication attempt 2.
I/LGEmail ( 7138): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7138): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/ActivityManager( 1037): Killing 6165:com.android.gallery3d/u0a27 (adj 15): empty #17
W/ResourceType( 7138): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6165/cgroup.procs: No such file or directory
,D/LgDataFeature( 7138): LgDataFeature() Constructor: none
,D/LgDataFeature( 7138): LgDataFeature() Constructor Done, null
,D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7166 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7138): JNI_OnLoad()
I/HubEmail( 7138): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7138): registerNatives()
I/HubEmail( 7138): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7138): registerNativeMethods()
I/HubEmail( 7138): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7138): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6645:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     (  349): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 282us total 32.681ms
I/art     (  349): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 12.830ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 273us total 12.884ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6645/cgroup.procs: No such file or directory
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7200 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7166): Network not available. Please check & try again.
V/FormManager( 7166): Network unavailable.
V/FormManager( 7166): Network unavailable.
,I/ActivityManager( 1037): Killing 6591:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6591/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7219 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6733:com.lge.eula/1000 (adj 15): empty #17
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState ASSOCIATION_REJECTION_EVENT 32 1 c0:ff:d4:d3:aa:48 blacklist=false rt=112644
,E/WifiStateMachine( 1037):  ConnectModeState ASSOCIATION_REJECTION_EVENT 32 1 c0:ff:d4:d3:aa:48 blacklist=false rt=112644
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=112645  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6733/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=112781  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=112783  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=112801  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7236 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6685:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1037):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6685/cgroup.procs: No such file or directory
,I/art     ( 7236): Almond Protected OAT
,D/WeatherApplication( 7236): removeAccount
,D/WeatherApplication( 7236): Account.length = 0
E/WeatherApplication( 7236): OPERATOR:OPEN
D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:38
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
,D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:38
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7258 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6055:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6055/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7258): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7258): Loading: webviewchromium
,I/LibraryLoader( 7258): Time to load native libraries: 4 ms (timestamps 3721-3725)
I/LibraryLoader( 7258): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7258): Binding Chromium to main looper Looper (main, tid 1) {492c4e8}
I/LibraryLoader( 7258): Expected native library version number "",actual native library version number ""
,I/chromium( 7258): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7258): Initializing chromium process, renderers=0
W/art     ( 7258): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7258): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7258): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7258): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb1427880, uid 10093
,W/AudioManagerAndroid( 7258): Requires BLUETOOTH permission
I/Adreno-EGL( 7258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7258): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7258): Build Date: 12/12/14 금
I/Adreno-EGL( 7258): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7258): Remote Branch: 
I/Adreno-EGL( 7258): Local Patches: 
I/Adreno-EGL( 7258): Reconstruct Branch: 
,I/NSApplication( 7258): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7313 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6766:com.lge.bnr/1000 (adj 15): empty #17
I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6899): 
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2360): num queued entries: 0
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.UploadsManager( 2360): num updated entries: 0
,I/iu.SyncManager( 2360): NEXT; no task
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSActivity( 2148): [ac] getting account id
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2148): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/FormManager( 7166): Network not available. Please check & try again.
V/FormManager( 7166): Network unavailable.
V/FormManager( 7166): Network unavailable.
I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:39
,D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:39
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiStateMachine( 1037):  DisconnectedState CMD_START_SCAN -2 -2 ic=2 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:49896] from screen [on:0 period:-1466073899]
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 4548): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/UEI.SmartControl( 6711): Internal timer expired: 2
D/UEI.SmartControl( 6711): unbind internal service
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/serial_port( 6711): close(fd = 24)
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
I/UEI.SmartControl( 6711): Serial port is closed.
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=114810  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=114822  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6899): 
,D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=115805  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=115806  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 2674): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115808
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115808
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115808
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115809
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115809
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=115813  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=115814  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/wpa_supplicant( 2674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=115842  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=115860  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115861
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115861
D/WifiNative-wlan0( 1037): doString: [STATUS]
,D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6967): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6967): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6967): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=115943  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=115944  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=115944  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=115946  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=115947  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=115947  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
,I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
,E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb5b42d target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb5b42d target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1973): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/Netd    (  309): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
W/dsqn    ( 7389): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7389): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
E/DSQN    ( 7389): DSQN ssw
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7035): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7035): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7035): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/dhcpcd  ( 7393): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/dhcpcd  ( 7393): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/LGDataListener(  309): argv[0]=dsqncommand
,D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
I/dhcpcd  ( 7393): version 5.5.6 starting
E/dhcpcd  ( 7393): get_duid: m
D/dhcpcd  ( 7393): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7393): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:30:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454527841103], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454527841082]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/QRemote ( 7035): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QRemote ( 7035): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7035): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1876): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ProcessCpuTracker( 1037): Skipping unknown process pid 7395
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7397
D/dhcpcd  ( 7393): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7393): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7393): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7393): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7393): wlan0: sending REQUEST (xid 0x50df182d), next in 4.20 seconds
,I/CloudHub( 2221): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19991
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
,I/dhcpcd  ( 7393): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7393): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7393): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7393): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7393): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7393): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7393): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 117482190325; DSPS: 3990413; Offset : -4310955022
D/dhcpcd  ( 7393): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7393): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/GAV4    ( 7258): Thread[GAThread,5,main]: No campaign data found.
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7115): onReceive
D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3377): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3377): DownloadService onCreate
D/eas_req ( 7138): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3377): in removeSpuriousFiles
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@2a1f4373 on behalf of 3377
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3377): in trimDatabase
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@13cef230 on behalf of 3377
V/DownloadManager( 3377): DownloadService onStartCommand
V/DownloadManager( 3377): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = true
D/PhoneState( 3325): setPdpRejectCasuse : false
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@23a0a3cf on behalf of 3377
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3377): processing inserted download 1
V/DownloadManager( 3377): processing inserted download 4
V/DownloadManager( 3377): processing inserted download 7
V/DownloadManager( 3377): processing inserted download 8
V/DownloadManager( 3377): processing inserted download 9
V/DownloadManager( 3377): processing inserted download 10
V/DownloadManager( 3377): processing inserted download 16
V/DownloadManager( 3377): processing inserted download 17
V/DownloadManager( 3377): processing inserted download 18
V/DownloadManager( 3377): processing inserted download 21
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3377): processing inserted download 22
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:44
V/DownloadManager( 3377): DownloadService onDestroy
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:30:44
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 73199(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.964ms total 109.615ms
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.Environment( 2360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2360): num queued entries: 0
I/iu.UploadsManager( 2360): num updated entries: 0
I/iu.SyncManager( 2360): NEXT; no task
,D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2360): [AccountUtils] Account not ready
W/Kids    ( 2360): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2360): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2360): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2360): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2360): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,D/GCM     ( 2148): Connected
D/GCM     ( 2148): Message class com.google.f.a.a.p
,V/FormManager( 7166): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7166): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Killing 6090:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10014/pid_6090/cgroup.procs: No such file or directory
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 6899): Test app app.js loaded
I/jxcore-log( 6899): 
,I/chromium( 6899): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6899): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8150ff added. We now have 1 listener(s)
,I/jxcore-log( 6899): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6899): 
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1125fa47 type 2 when 130980 android} when 130980
,V/QRemote ( 7035): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 7035): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5850
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{23ec739d type 0 when 1454527856519 com.android.vending} when 1454527856519
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6234): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6234): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6234): [1] 5.onFinished: Scheduling replication attempt 3.
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,I/CloudHub( 2221): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2221): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 137484222766; DSPS: 4645839; Offset : -4310938720
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{3cd250a4 type 0 when 1454527877371 com.android.vending} when 1454527877371
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6234): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6234): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6234): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 157486800518; DSPS: 5301284; Offset : -4310954988
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{28e84ae6 type 2 when 171182 android} when 171182
,I/BooksSync( 6822): Starting books sync
,D/BooksSync( 6822): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2177789945516673730&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2177789945516673730&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1421): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1421): Notification difference=198
,D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
W/ApiaryClient( 6822): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2177789945516673730&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,E/BooksSync( 6822): Soft error: 
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2177789945516673730&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
,E/BooksSync( 6822): Sync error
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2177789945516673730&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
I/BooksSync( 6822): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 171182, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 177488863427; DSPS: 5956711; Offset : -4310936679
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{21221a59 type 0 when 1454527901437 com.android.vending} when 1454527901437
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6234): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6234): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6234): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1037): battery changed pluggedType: 2
D/HeadsetStateMachine( 3830): Disconnected process message: 10, size: 0
D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1973): Battery Level Remaining: 100%
D/LEDHandler( 1973): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 197491438108; DSPS: 6612156; Offset : -4310956070
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1122d393 type 2 when 201249 android} when 201249
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1037): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=210348
E/WifiStateMachine( 1037):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=210349
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=210349
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6967): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6967): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6967): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1037): RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2148): Read error: ssl=0xaf453600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2148): SSL shutdown failed: ssl=0xaf453600: I/O error during system call, Broken pipe
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1efd0fd0 type 2 when 186673 com.google.android.gms} when 186673
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{26cab2ce type 0 when 1454527930203 com.android.vending} when 1454527930203
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{201d15ef type 2 when 208606 android} when 208606
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1973): handleWifiStateChangedEvent: 0
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=210557  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=210558  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=210565  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1037): hidePasspointNotification off =false
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=210584  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/NetworkManagementService( 1037): Removing idletimer
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/DhcpStateMachine( 1037): StoppedState
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6234): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6234): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6234): [1] 5.onFinished: Giving up after 6 failures.
,I/wpa_supplicant( 2674): [LGE_PATCH]scan interval[0] = 2 sec.
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/WfdsMonitor( 1973): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1973): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
,D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:18
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:18
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7166): Network not available. Please check & try again.
,V/FormManager( 7166): Network unavailable.
,V/FormManager( 7166): Network unavailable.
,I/iu.Environment( 2360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2360): num queued entries: 0
I/iu.UploadsManager( 2360): num updated entries: 0
I/iu.SyncManager( 2360): NEXT; no task
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
W/FormManager( 7166): Network not available. Please check & try again.
,D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:18
,V/FormManager( 7166): Network unavailable.
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
V/FormManager( 7166): Network unavailable.
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:18
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2674): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=57 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=216603  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=216637  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
I/wpa_supplicant( 2674): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=60 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=216720  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=216721  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 60 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=216722
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 60 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=216722
I/wpa_supplicant( 2674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=63 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 60 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=216740
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 60 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=216742
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 60 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=216743
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=216744  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=216762  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/UsbSettingsControl( 6967): [AUTORUN] getUsbConnected() : connected=true
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=216769  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=216769  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6967): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216770
D/UsbSettingsControl( 6967): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216770
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
,D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 3
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=216820  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=216820  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=216821  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=216828  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=216829  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=216830  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1037): SET ps 0: returned true
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb5b42d target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2bb5b42d target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
D/ConnectivityService( 1037): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 102
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1973): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 102
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
E/Netd    (  309): netlink response contains error (File exists)
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
D/ConnectivityService( 1037): Setting Dns servers for network 102 to [/192.168.1.1]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 102]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7642): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7642): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7642): DSQN ssw
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7035): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7035): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7035): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7648): type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7648): type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7035): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7035): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7035): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/dhcpcd  ( 7648): version 5.5.6 starting
E/dhcpcd  ( 7648): get_duid: m
D/dhcpcd  ( 7648): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7648): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7648): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7648): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7648): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7648): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7648): wlan0: sending REQUEST (xid 0x7401c4a5), next in 3.68 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:32:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454527942160], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454527941909]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1876): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 217494556745; DSPS: 7267618; Offset : -4310950148
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
I/dhcpcd  ( 7648): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7648): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7648): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7648): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7648): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7648): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7648): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7648): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7648): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3c6fe151 type 2 when 219808 com.google.android.gms} when 219808
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/BooksSync( 6822): Starting books sync
D/BooksSync( 6822): started syncMyEbooks
,D/GCM     ( 2148): Connected
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 107527(4MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.495ms total 165.187ms
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3377): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/GCM     ( 2148): Message class com.google.f.a.a.p
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3377): DownloadService onCreate
,I/DownloadManager( 3377): in removeSpuriousFiles
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@1a47cc65 on behalf of 3377
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/LGDMClient( 4329): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3377): in trimDatabase
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@bf6fd3a on behalf of 3377
D/eas_req ( 7138): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3377): DownloadService onStartCommand
V/DownloadManager( 3377): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@23edc9e1 on behalf of 3377
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3377): processing inserted download 1
V/DownloadManager( 3377): processing inserted download 4
E/LGDMClient( 4329): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4329): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4329): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = true
D/PhoneState( 3325): setPdpRejectCasuse : false
V/DownloadManager( 3377): processing inserted download 7
V/DownloadManager( 3377): processing inserted download 8
V/DownloadManager( 3377): processing inserted download 9
,W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:25
V/DownloadManager( 3377): processing inserted download 10
V/DownloadManager( 3377): processing inserted download 16
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
V/DownloadManager( 3377): processing inserted download 17
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:32:25
V/DownloadManager( 3377): processing inserted download 18
,V/DownloadManager( 3377): processing inserted download 21
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
V/DownloadManager( 3377): processing inserted download 22
,V/DownloadManager( 3377): DownloadService onDestroy
I/VacuumService( 2148): Vacuum at: now=1454527945264 tag=VacuumService
,D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
I/iu.Environment( 2360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/iu.UploadsManager( 2360): num queued entries: 0
I/iu.UploadsManager( 2360): num updated entries: 0
I/iu.SyncManager( 2360): NEXT; no task
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:32:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454527945304], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454527945287]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/Kids    ( 2360): [AccountUtils] Account not ready
W/Kids    ( 2360): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2360): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2360): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2360): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2360): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2360): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2360): 	at java.lang.Thread.run(Thread.java:818)
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GoogleURLConnFactory( 2148): Using platform SSLCertificateSocketFactory
,W/Uploader( 2148): No account for auth token provided
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1035328164125181442&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
V/FormManager( 7166): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7166): Alarm would be updated, because LastCheckTime has been updated.
,W/Uploader( 2148): No account for auth token provided
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
,W/Uploader( 2148): No account for auth token provided
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,W/Uploader( 2148): No account for auth token provided
,W/Uploader( 2148):  no longer exists, so no auth token.
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2148): Explicit concurrent mark sweep GC freed 54804(3MB) AllocSpace objects, 21(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.270ms total 66.308ms
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1035328164125181442&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1035328164125181442&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,E/BooksSync( 6822): Soft error: 
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1035328164125181442&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
,E/BooksSync( 6822): Sync error
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1035328164125181442&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
I/BooksSync( 6822): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 207075, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{290bc950 type 2 when 227196 com.google.android.gms} when 227196
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2148): Connected
,D/GCM     ( 2148): Message class com.google.f.a.a.p
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{153b4749 type 2 when 231389 android} when 231389
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 237495828144; DSPS: 7923019; Offset : -4310930100
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257497602355; DSPS: 8578438; Offset : -4310956531
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{56bc84e type 2 when 261400 android} when 261400
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,I/BooksSync( 6822): Starting books sync
,D/BooksSync( 6822): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
,D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4814374676383460838&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4814374676383460838&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4814374676383460838&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,E/BooksSync( 6822): Soft error: 
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4814374676383460838&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
,E/BooksSync( 6822): Sync error
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4814374676383460838&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
I/BooksSync( 6822): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 255934, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 6899): TAP version 13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 1 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # multiplex can send data
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 2 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 3 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 4 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # enqueue and run in order
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 5 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 6 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 7 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # basic
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 8 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 9 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 10 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # another
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 11 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 12 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 13 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 14 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 15 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/dat,a/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 16 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): ,
I/jxcore-log( 6899): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 17 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       ,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 18 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...,
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 19 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 20 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown,
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 21 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 22 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # failed to get mobile documents path
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 23 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 24 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 25 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 26 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 27 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 28 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #init should register the networkChanged event
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 29 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 30 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup,
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 31 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should throw on null device name
I/jxcore-log( 6899): ,
I/jxcore-log( 6899): not ok 32 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 33 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 34 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13,
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 35 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 36 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 37 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 38 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
,I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 39 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 40 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 41 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js,:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 42 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 43 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # #startBroadcasting should throw on negative port
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 44 ReferenceError: _name is not defined
,I/jxcore-log( 6899): ,
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 45 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 46 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should throw on too large port
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 47 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 48 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
,I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 49 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 50 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): ,
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 51 ReferenceError: _name is not defined,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 52 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 53 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 54 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 55 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 56 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 57 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 58 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 59 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 60 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 61 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 62 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 63 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 64 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 65 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 66 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 67 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 68 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 69 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       ,
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 70 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # should call Mobile("Disconnect") and handle an error
,I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 71 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 72 ReferenceError: _name is not defined,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 73 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 74 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 75 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 76 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 77 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 78 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 79 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 80 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 81 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 82 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 83 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 84 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 85 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 86 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 87 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 88 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 89 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 90 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 91 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       ,
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...,
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # messages with invalid location or USN should be ignored
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 92 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 93 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 94 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 95 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 96 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 97 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #start should fail if called twice in a row
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 98 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 99 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 100 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 101 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 102 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 103 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startUpdateAdvertisingAndListening should fail if router server starting fails,
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 104 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 105 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 106 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-,
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 107 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 108 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 109 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #stop can be called multiple times in a row
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 110 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 111 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 112 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 113 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       ,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 114 ReferenceError: _name is not defined
,I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): ,
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5,
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 115 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 116 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 117 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 118 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): not ok 119 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 120 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # setup
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 121 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): # functions are run from a queue in the right order
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 122 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
,I/jxcore-log( 6899): # teardown
I/jxcore-log( 6899): 
I/jxcore-log( 6899): not ok 123 ReferenceError: _name is not defined
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ---
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     operator: error
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     expected: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       undefined
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):     actual: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       [ReferenceError: _name is not defined]
I/jxcore-log( 6899): 
I/jxcore-log( 6899):     stack: |-
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6899): 
,I/jxcore-log( 6899):       $v@timers.js:363:1
I/jxcore-log( 6899): 
I/jxcore-log( 6899):       
I/jxcore-log( 6899): 
I/jxcore-log( 6899):   ...
I/jxcore-log( 6899): 
I/jxcore-log( 6899): Tests Complete
I/jxcore-log( 6899): 
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277499673753; DSPS: 9233865; Offset : -4310929681
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3d9444c8 type 2 when 291799 android} when 291799
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297502340049; DSPS: 9889313; Offset : -4310948906
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317504336655; DSPS: 10544738; Offset : -4310935837
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1fc66961 type 2 when 328647 android} when 328647
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,I/BooksSync( 6822): Starting books sync
,D/BooksSync( 6822): started syncMyEbooks
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
,W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7692863995673551384&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
I/art     ( 1037): Explicit concurrent mark sweep GC freed 35265(1628KB) AllocSpace objects, 10(1184KB) LOS objects, 33% free, 44MB/66MB, paused 2.680ms total 153.030ms
,D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7692863995673551384&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6822): Authentication error
E/BooksAccountManager( 6822): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6822): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6822): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6822): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6822): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6822): Error response from books API: {
W/ApiaryClient( 6822):  "error": {
W/ApiaryClient( 6822):   "errors": [
W/ApiaryClient( 6822):    {
W/ApiaryClient( 6822):     "domain": "global",
W/ApiaryClient( 6822):     "reason": "required",
W/ApiaryClient( 6822):     "message": "Login Required",
W/ApiaryClient( 6822):     "locationType": "header",
W/ApiaryClient( 6822):     "location": "Authorization"
W/ApiaryClient( 6822):    }
W/ApiaryClient( 6822):   ],
W/ApiaryClient( 6822):   "code": 401,
W/ApiaryClient( 6822):   "message": "Login Required"
W/ApiaryClient( 6822):  }
W/ApiaryClient( 6822): }
,W/ApiaryClient( 6822): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7692863995673551384&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6822): Headers:
W/ApiaryClient( 6822): accept-encoding: [gzip]
W/ApiaryClient( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6822): gdata-version: 2
E/BooksSync( 6822): Soft error: 
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7692863995673551384&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): gdata-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
E/BooksSync( 6822): Sync error
E/BooksSync( 6822): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6822): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7692863995673551384&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6822): Headers:
E/BooksSync( 6822): accept-encoding: [gzip]
E/BooksSync( 6822): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6822): g,data-version: 2
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6822): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6822): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6822): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6822): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6822): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6822): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6822): {
E/BooksSync( 6822):  "error": {
E/BooksSync( 6822):   "errors": [
E/BooksSync( 6822):    {
E/BooksSync( 6822):     "domain": "global",
E/BooksSync( 6822):     "reason": "required",
E/BooksSync( 6822):     "message": "Login Required",
E/BooksSync( 6822):     "locationType": "header",
E/BooksSync( 6822):     "location": "Authorization"
E/BooksSync( 6822):    }
E/BooksSync( 6822):   ],
E/BooksSync( 6822):   "code": 401,
E/BooksSync( 6822):   "message": "Login Required"
E/BooksSync( 6822):  }
E/BooksSync( 6822): }
E/BooksSync( 6822): 
E/BooksSync( 6822): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6822): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6822): 	... 8 more
I/BooksSync( 6822): Finished books sync
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 328647, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337506133001; DSPS: 11200157; Offset : -4310940185
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357507946952; DSPS: 11855577; Offset : -4310957236
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1f803ec3 type 2 when 358780 android} when 358780
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2148): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2148): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2148): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2148): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{1e373dc7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2148): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2148): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2148): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2148): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2148): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6234): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6234): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6234): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6234): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6234): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6234): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6234): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6234): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377510717414; DSPS: 12511027; Offset : -4310933252
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397512548292; DSPS: 13166447; Offset : -4310933585
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417514341930; DSPS: 13821866; Offset : -4310940406
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1037): battery changed pluggedType: 2
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1973): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1973): Battery Level Remaining: 100%
,D/LEDHandler( 1973): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3830): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED,
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437516125672; DSPS: 14477285; Offset : -4310957280
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457518111289; DSPS: 15132710; Offset : -4310955252
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{26520ded type 2 when 458618 android} when 458618
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1037): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=458786
E/WifiStateMachine( 1037):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=458786
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=458786
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1037): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6899): Toggling radios to false
I/jxcore-log( 6899): 
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37c5422 mBinding = false
V/NativeCrypto( 2148): Read error: ssl=0xaf456200: I/O error during system call, Connection timed out
,I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1037): hidePasspointNotification off =false
V/WfdStateTracker( 1973): handleWifiStateChangedEvent: 0
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=458910  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=458910  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 69 0 rt=458913  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6967): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiHS20( 1037): hidePasspointNotification off =false
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
D/BluetoothManagerService( 1037): Message: 2
,V/NativeCrypto( 2148): SSL shutdown failed: ssl=0xaf456200: I/O error during system call, Broken pipe
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 69 0 rt=458939  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/BluetoothManagerService( 1037): Sending off request.
,D/LGBluetoothServiceAdapter( 3830): [BTUI] Precleanup
D/BluetoothAdapterState( 3830): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3830): Setting state to 13
I/BluetoothAdapterState( 3830): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3830): onBluetoothDisable()
I/BluetoothAdapterState( 3830): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1037): Message: 60
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
D/WifiHS20( 1037): hidePasspointNotification off =false
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 12 -> 13
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServiceImplEx( 1037): setWifiEnabled: false pid=6899, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiService( 1037): setWifiEnabled: false pid=6899, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties( 3830): Scan Mode:20
D/BluetoothAdapterState( 3830): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothSapService( 3830): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x000f
D/btif_config_util( 3830): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapService( 3830): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3830): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
E/BtOppRfcommListener( 3830): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
V/BluetoothMapMasInstance( 3830): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3830): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3830): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3830): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3830): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3830): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3830): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3830): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-btif ( 3830): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStic,kyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/UsbSettingsControl( 6967): [AUTORUN] getUsbConnected() : connected=true
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : availableList=[]
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x001b
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : activeList=[]
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/UsbSettingsReceiver( 6967): [AUTORUN] onReceive() : errorList=[]
W/bt-l2cap( 3830): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/UsbSettingsControl( 6967): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
W/bt-l2cap( 3830): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3830): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3830): bta_gattc_deregister Deregister Failedm unknown client cif
D/UsbSettingsControl( 6967): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-10ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1037): Removing idletimer
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServices,Setting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
,I/jxcore-log( 6899): Radios toggled
I/jxcore-log( 6899): 
E/WifiStateMachine( 1037):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1037):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1037):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LGBluetoothAPIService( 1973): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/BluetoothMapService( 3830): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3830): STATE_TURNING_OFF
V/BtOppService( 3830): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3830): Handler(): got msg=4
D/BluetoothMapService( 3830): MAP Service closeService in
D/BluetoothMapMasInstance( 3830): MAP Service shutdown
D/LGBluetoothMapAdapter( 3830): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3830): MAP Service closeService out
V/BluetoothPbapReceiver( 3830): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3830): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3830): ***********state = 13
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,V/BluetoothPbapReceiver( 3830): ***********Calling start service!!!! with action = null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
I/BtOppRfcommListener( 3830): stopping Accept Thread
V/BtOppRfcommListener( 3830): close mBtServerSocket
V/BtOppRfcommListener( 3830): waiting for thread to terminate
I/BtOppRfcommListener( 3830): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3830): done waiting for thread to terminate
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,W/ContextImpl( 6967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7906 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 3830): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3830): state: 13
V/BluetoothPbapService( 3830): Pbap Service closeService in
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1b9c4ce2
D/WifiScanningService( 1037): SCAN_AVAILABLE : 1
D/RttService( 1037): SCAN_AVAILABLE : 1
D/WifiScanningService( 1037): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1037): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapService( 3830): successfully stopped pbap service
D/LGWifiP2pService( 1037): P2pDisablingState
V/BluetoothPbapService( 3830): Pbap Service closeService out
D/LGWifiP2pService( 1037): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
V/BtOppService( 3830): onDestroy
D/LGWifiP2pService( 1037): p2p socket connection lost
D/LGWifiP2pService( 1037): P2pDisabledState
E/WifiStateMachine( 1037):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2674): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/LGWifiP2pService( 1037): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CommandListener(  309): Clearing all IP addresses on wlan0
V/WfdStateTracker( 1973): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1973): WifiP2pState is changed : false
D/WfdsService( 1973): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1973): Set the WFDS Monitor: false
D/LGBluetoothOppAdapter( 3830): [BTUI] LGBluetoothOppAdapter cleanup
D/WfdsMonitor( 1973): WFDS Monitor is stopped
D/WfdsService( 1973): STATE : WfdsDisabledState - enter
V/BluetoothPbapService( 3830): Pbap Service onDestroy
V/BluetoothPbapService( 3830): Pbap Service closeService in
V/BluetoothPbapService( 3830): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3830): [BTUI] cleanup
D/CtrlSupplicant( 1973): Received on exit socket, terminate
E/CtrlSupplicant( 1973): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1973): Event [CTRL-EVENT-TERMINATING  - connection closed]
W/WfdsSession:Controller( 1973): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1973): WfdsMonitorThread is received the interrupt - closing
D/WifiNative-p2p0( 1037): doBoolean: TERMINATE
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): TERMINATE: returned true
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@142f906e:true
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/WfdsService( 1973): DefaultState - msg [9445378] is not handled
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1037):  SupplicantStoppingState CMD_ON_QUIT 0 0
I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [0]
V/WfdStateTracker( 1973): WfdStateTracker handleDirectStateChangedEvent: 6
E/WifiStateMachine( 1037):  DefaultState CMD_ON_QUIT 0 0
,D/BluetoothManagerService( 1037): Message: 30
,D/BluetoothManagerService( 1037): Message: 30
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocalBluetoothProfileManager( 6967): Adding local MAP profile
D/BluetoothMap( 6967): Create BluetoothMap proxy object
D/BluetoothManagerService( 1037): Message: 30
,D/BluetoothManagerService( 1037): Message: 30
D/LocalBluetoothProfileManager( 6967): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6967):  get() - isFeatureLoaded : false
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothUserBindClient( 6967): [BTUI] initUserBindClient
W/ContextImpl( 6967): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6967): finishStartingService: stopping service
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/BluetoothInputDevice( 6967): Proxy object connected
D/HidProfile( 6967): Bluetooth service connected
D/BluetoothPan( 6967): BluetoothPAN Proxy object connected
D/PanProfile( 6967): Bluetooth service connected
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/BluetoothMap( 6967): Proxy object connected
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/MapProfile( 6967): Bluetooth service connected
D/BluetoothMap( 6967): getConnectedDevices()
D/BluetoothMap( 6967): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6967): [BTUI] onServiceConnected
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/ActivityThread( 7906): Failed to find provider info for com.lge.lgaccount.provider
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/LG Account v2.2( 7906): No ProfileInfo entries
I/LG Account v2.2( 7906): isEnabled: false
I/Feature ( 7906): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7906): [Lifetracker]Country: EU
I/Feature ( 7906): [Lifetracker]Operator: OPEN
I/Feature ( 7906): [Lifetracker]Ranking support: false
I/Feature ( 7906): [Lifetracker]Comfort support: false
I/Feature ( 7906): [Lifetracker]Accessory: true
I/Feature ( 7906): [Lifetracker]Health device: true
I/Feature ( 7906): [Lifetracker]Extra Pedometer: false
I/Feature ( 7906): [Lifetracker]Blood glucose device: false
I/Feature ( 7906): [Lifetracker]Device Number: 3
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/LGBluetoothAuthorization( 6967): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 6967): onReceive
D/LGBluetoothAuthorization( 6967): [BTUI] cancel All Notification
I/ActivityManager( 1037): Killing 2221:com.lge.music/u0a34 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6967): return without doing reset settings.
V/AudioFlinger(  314): 2221 died, releasing its sessions
,V/AudioFlinger(  314):  pid 1876 @ 0
V/AudioFlinger(  314):  pid 3325 @ 1
V/AudioFlinger(  314):  pid 3325 @ 2
,D/MediaSessionService( 1037): clear user.mLastMediaButtonReceiver
,V/BluetoothOppReceiver( 3830): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3830): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3830): [BTUI] cancel opp active transfer file notification
W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2221/cgroup.procs: No such file or directory
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/BluetoothFtpReceiver( 3830): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3830): BluetoothFtpReceiver Start Service
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3830): Ftp Service onStartCommand
V/BluetoothFtpService( 3830): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3830): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3830): Shutdown
V/BluetoothFtpService( 3830): successfully stopped ftp service
V/BluetoothSapReceiver( 3830): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3830): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3830): SapReceiver onReceive 
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapReceiver( 3830): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3830):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3830): Calling SAP service start service with action = null
V/BluetoothFtpService( 3830): Ftp Service onDestroy
V/BluetoothFtpService( 3830): Ftp Service closeService
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3830): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3830): state: 13
V/BluetoothSapService( 3830): Stopping SAP server process
V/BluetoothSapService( 3830): Sap Service closeSapService in
V/BluetoothSapService( 3830): Close listen Socket : 
V/BluetoothSapService( 3830): Close rfcomm Socket : 
V/BluetoothSapService( 3830): Close sapd  Socket : 
V/BluetoothSapService( 3830): Sap Service closeSapService out
V/BluetoothSapService( 3830): Sap Service onDestroy
V/BluetoothSapService( 3830): Sap Service closeSapService in
V/BluetoothSapService( 3830): Close listen Socket : 
V/BluetoothSapService( 3830): Close rfcomm Socket : 
V/BluetoothSapService( 3830): Close sapd  Socket : 
V/BluetoothSapService( 3830): Sap Service closeSapService out
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ResourcesManager( 7933): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2148): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7011): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
,D/QRemote ( 7035): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7035): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7035): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7166): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
V/FormManager( 7166): Network unavailable.
,V/FormManager( 7166): Network unavailable.
I/ActivityManager( 1037): Killing 6234:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_6234/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3830): cleanup
,I/bt_lpm  ( 3830): LPM is already off!!!
I/bt_userial_mct( 3830): exiting userial_read_thread
D/bt_userial_mct( 3830): Leaving userial_evt_read_thread()
W/bt-btif ( 3830): ag scb idx 1 not allocated
E/bt-btif ( 3830): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3830): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3830): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3830): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3830): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3830): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3830): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3830): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3830): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3830): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3830): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3830): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3830): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3830): hw_epilog_process
D/bt_hci_bdroid( 3830): cleanup Finalizing cleanup
D/bt_userial_mct( 3830): userial_close
E/bt_userial_mct( 3830): pthread_join() FAILED result:3
I/bt_vendor( 3830): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3830): set_power 0
I/bt_vendor( 3830): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3830): bluetooth satus is on
I/bt_vendor( 3830): bt-vendor : resetting BT status
I/bt_vendor( 3830): Starting hciattach daemon
I/bt_vendor( 3830): try to set false
,I/bt_vendor( 3830): Starting hciattach daemon
I/bt_vendor( 3830): try to set false
I/bt_vendor( 3830): cleanup
I/GKI_LINUX( 3830): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3830): GKI_exit_task 0 done
I/GKI_LINUX( 3830): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3830): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3830): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3830): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3830): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/HeadsetStateMachine( 3830): Exit Disconnected: -1
D/BluetoothAdapterState( 3830): Stopping profile services that were post enabled
D/BluetoothHeadset( 1037): Proxy object disconnected
D/AudioService( 1037): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/A2dpService( 3830): Received stop request...Stopping profile...
D/A2dpStateMachine( 3830): Exit Disconnected: -1
,D/LGBluetoothAvrcpQcomAdapter( 3830): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3830): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3830): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/BluetoothA2dp( 1037): Proxy object disconnected
D/AudioService( 1037): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3830): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/HealthService( 3830): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
,D/PanService( 3830): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/BtGatt.DebugUtils( 3830): handleDebugAction() action=null
D/BtGatt.GattService( 3830): Received stop request...Stopping profile...
D/BtGatt.GattService( 3830): stop()
D/BtGatt.AdvertiseManager( 3830): advertise clients cleared
D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/BluetoothMapService( 3830): Received stop request...Stopping profile...
D/BluetoothMapService( 3830): stop()
D/BluetoothMapEmailAppObserver( 3830): deinitObservers()
D/BluetoothMapEmailAppObserver( 3830): removeReceiver()
,D/BluetoothAdapterService( 3830): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f7420cc
D/HeadsetStateMachine( 3830): Unbinding service...
D/HeadsetPhoneState( 3830): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3830): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3830): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3830): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3830): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3830): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3830): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3830): cleanupNative
I/GKI_LINUX( 3830): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3830): GKI_exit_task 2 done
I/GKI_LINUX( 3830): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3830): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3830): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3830): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3830): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3830): Cleaning up Bluetooth Health object
V/BluetoothMapService( 3830): Handler(): got msg=4
D/BluetoothMapService( 3830): MAP Service closeService in
D/LGBluetoothMapAdapter( 3830): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3830): MAP Service closeService out
D/BluetoothAdapterState( 3830): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3830): Setting state to 10
I/BluetoothAdapterState( 3830): Bluetooth adapter state changed: 13-> 10
W/BluetoothPanServiceJni( 3830): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3830): Cleaning up Bluetooth PAN callback object
D/BluetoothManagerService( 1037): Message: 60
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1037): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1037): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3830): Entering OffState
D/BluetoothMap( 6967): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
D/BluetoothMapService( 3830): cleanup()
D/BluetoothMapService( 3830): MAP Service closeService in
D/LGBluetoothMapAdapter( 3830): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3830): MAP Service closeService out
D/BluetoothPbap( 6967): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1037): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6967): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
D/BluetoothPan( 6967): onBluetoothStateChange on: false
D/BluetoothManagerService( 1037): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1037): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1037): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1037): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1037): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37c5422 mBinding = false
D/BluetoothManagerService( 1037): Sending unbind request.
I/GKI_LINUX( 3830): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3830): GKI_exit_task 1 done
I/GKI_LINUX( 3830): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3830): cleanupNative: return from cleanup
I/art     ( 3830): --- WEIRD: removing null entry 246
W/art     ( 3830): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3830): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3830): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3830): System.exit called, status: 0
I/AndroidRuntime( 3830): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  314): 3830 died, releasing its sessions
V/AudioFlinger(  314):  pid 1876 @ 0
V/AudioFlinger(  314):  pid 3325 @ 1
V/AudioFlinger(  314):  pid 3325 @ 2
,D/LGBluetoothAPIService( 1973): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1973): Message: 101
E/LGBluetoothAPIService( 1973): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1973): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1973): Broadcasting onBluetoothServiceDown() to 0 receivers.
,D/LGBluetoothUserBindClient( 6967): [BTUI] onServiceDisconnected
I/ActivityManager( 1037): Process com.android.bluetooth (pid 3830) has died
W/ActivityManager( 1037): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
W/ActivityManager( 1037): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1973): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1973): Message: 2
D/LGBluetoothAPIService( 1973): unbindAndFinish(): null mBinding = false
D/LGBluetoothFeatureConfig( 6967): isPrivacyLogsEnabled : true
,E/LGBluetoothEventManager( 6967): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6967): [BTUI] clear device connection state
D/BluetoothAdapter( 1472): 933693302: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1472): 933693302: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 6967): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1037): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7982 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 6967): finishStartingService: stopping service
,W/ResourcesManager( 7982): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7982): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7982): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7982): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 7982): Loading JNI Library
,D/BluetoothAdapterApp( 7982): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2207515d Instance Count = 1
,D/BluetoothAdapterApp( 7982): onCreate
D/ProfileConfigQcom( 7982): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 7982): Adding HeadsetService
,D/ProfileConfigQcom( 7982): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7982): Adding A2dpService
D/ProfileConfigQcom( 7982): [BTUI] HidService is supported
D/ProfileConfigQcom( 7982): Adding HidService
D/ProfileConfigQcom( 7982): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7982): Adding HealthService
,D/LGBluetoothFeatureConfig( 7982): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 7982): [BTUI] PanService is supported
D/ProfileConfigQcom( 7982): Adding PanService,
D/ProfileConfigQcom( 7982): [BTUI] GattService is supported
D/ProfileConfigQcom( 7982): Adding GattService,
D/ProfileConfigQcom( 7982): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7982): Adding BluetoothMapService,
D/ProfileConfigQcom( 7982): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7982): PbapReceiver onReceive ,
,V/BluetoothPbapReceiver( 7982): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 7982): ***********state = 10
V/LGMDMManagerInternal( 7982): Create singleton instance
,D/LGBluetoothAPIServer( 7982): [BTUI] onCreate(),
D/LGBluetoothAPIServer( 7982): [BTUI] onBind()
D/LGBluetoothAPIService( 1973): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothUserBindClient( 6967): [BTUI] onServiceConnected
D/LGBluetoothAPIService( 1973): Message: 100
D/LGBluetoothAPIService( 1973): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothPermissionRequest( 6967): onReceive
D/LGBluetoothUtils( 6967): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6967): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 6967): return without doing reset settings.
,D/LGBluetoothOppAdapter( 7982): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 7982): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7982): [BTUI] checkServiceStart
,V/BluetoothSapReceiver( 7982): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7982): SapReceiver onReceive 
V/BluetoothSapReceiver( 7982): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7982):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7933): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 2148): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2674): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2674): monitor socket send errors count : 1
,I/wpa_supplicant( 2674): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1973-2\x00 that cannot receive messages
,W/wpa_supplicant( 2674): USIM:  scard_deinit function
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1037): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 71 0 rt=460981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1037):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 71 0 rt=460982  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2674): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1037): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1037):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 72 0
D/WfdsService( 1973): Supplicant Connection state is changed : false
,D/WfdsService( 1973): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1973): Set the WFDS Monitor: false
D/WfdsMonitor( 1973): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1037): stopMonitoring
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1973): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1037): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1037): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7011): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7011): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7011): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6967): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6967): MCCMNC not supported: null
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/FormManager( 7166): Network not available. Please check & try again.
,V/FormManager( 7166): Network unavailable.
,V/FormManager( 7166): Network unavailable.
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5576): type=WIFI subType= reason=null isConnected=false
,I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
W/FormManager( 7166): Network not available. Please check & try again.
D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:36:27
,D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
V/FormManager( 7166): Network unavailable.
D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:36:27
V/FormManager( 7166): Network unavailable.
I/iu.Environment( 2360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2360): num queued entries: 0
I/iu.UploadsManager( 2360): num updated entries: 0
I/iu.SyncManager( 2360): NEXT; no task
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7115): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2acfdaff
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4329): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4329): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4329): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7138): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4329): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7166): Network not available. Please check & try again.
I/LgeMiscReceiver( 3325): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3325): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3325): networkInfo.isConnected() = false
V/FormManager( 7166): Network unavailable.
,D/WeatherAncestor( 7236): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:36:27
V/FormManager( 7166): Network unavailable.
D/Weather.Utils( 7236): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7236): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7236): 2 : This is isUpdating : false
D/WeatherAncestor( 7236): connectivity changed - connection : true
D/WeatherService( 7236): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@384f15
,D/ForecastDataCache( 7236): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7236): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7236): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7236): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7236): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:36:27
D/ChimeraCfgMgr( 2360): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{31e74000 type 2 when 463278 com.google.android.gms} when 463278
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/LGWifiP2pService( 1037): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1037):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1037):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477520921803; DSPS: 15788162; Offset : -4310952122
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497522971170; DSPS: 16443589; Offset : -4310947562,
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517525021214; DSPS: 17099016; Offset : -4310942144
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537526770998; DSPS: 17754433; Offset : -4310931862
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557529942032; DSPS: 18409897; Offset : -4310934760
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577531725254; DSPS: 19065316; Offset : -4310951997
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597541469517; DSPS: 19720995; Offset : -4310943051
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617543478520; DSPS: 20376421; Offset : -4310948182
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637545536168; DSPS: 21031848; Offset : -4310935211
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037,
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
,I/ActivityManager( 1037): Killing 6822:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6822/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 657547303140; DSPS: 21687266; Offset : -4310938076
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 677549374330; DSPS: 22342694; Offset : -4310942133
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 697561514323; DSPS: 22998452; Offset : -4310948034
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 717563353167; DSPS: 23653872; Offset : -4310940296
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 737565330089; DSPS: 24309297; Offset : -4310947069
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 757567392424; DSPS: 24964724; Offset : -4310929281
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 777572523720; DSPS: 25620253; Offset : -4310955768
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 797574588660; DSPS: 26275680; Offset : -4310935245
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 817576531725; DSPS: 26931104; Offset : -4310945409
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 837579273019; DSPS: 27586554; Offset : -4310950567
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 857581686033; DSPS: 28241993; Offset : -4310948468
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 877583745764; DSPS: 28897420; Offset : -4310933466
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 897585786226; DSPS: 29552847; Offset : -4310937630
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 917587855228; DSPS: 30208275; Offset : -4310943927
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 937589947825; DSPS: 30863704; Offset : -4310956939
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 957592030109; DSPS: 31519132; Offset : -4310949955
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=462653827, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8141 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8141): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8141): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1059faa0
I/ActivityManager( 1037): Killing 6711:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=462653827 [*alarm*], flags=0x0
I/QRemote ( 7035): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 7035): android.os.DeadObjectException
W/System.err( 7035): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7035): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7035): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7035): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 7035): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7035): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7035): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7035): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7035): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7035): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7035): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 7035): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7035): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7035): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7035): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7035): android.os.DeadObjectException
W/System.err( 7035): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7035): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7035): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7035): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 7035): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 7035): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 7035): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7035): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7035): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7035): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7035): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7035): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7035): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7035): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7035): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 7035): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6711/cgroup.procs: No such file or directory
W/ActivityManager( 1037): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 7035): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 7035): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 7035): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8176): Quickset Services start...
I/UEI.SmartControl( 8176): Manufacture = LGE
,D/UEI.SmartControl( 8176): Id = LGNevo
D/UEI.SmartControl( 8176): File observer start...
E/UEI.SmartControl( 8176): IR Port is disabled: false
D/UEI.SmartControl( 8176): Starting file observer...
D/UEI.SmartControl( 8176): Extracting JNI libs...
D/UEI.SmartControl( 8176): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8176): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8176): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8176): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8176): --- Selecting new region: 6
,I/UEI.SmartControl( 8176): Model = LG-D855
D/UEI.SmartControl( 8176): QS Service created
I/UEI.SmartControl( 8176): Service initServices...
,D/UEI.SmartControl( 8176): QS start get config
D/UEI.SmartControl( 8176): Loading JNI Libs...
,I/UEI.SmartControl( 8176): Supports setup maps: true
,D/UEI.SmartControl( 8176): QS start statue = true Error code = 0
I/UEI.SmartControl( 8176): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8176): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8176): ### init IR Blaster...
D/serial_port( 8176): Configuring serial port
E/UEI.SmartControl( 8176): UEIBLaster setting for 616
I/UEI.SmartControl( 8176): Setting serial record hearder size = 2
I/UEI.SmartControl( 8176): configuring settings for MAXQ616
I/UEI.SmartControl( 8176): Get version...
,D/UEI.SmartControl( 8176): serial port data available: 21
,D/UEI.SmartControl( 8176): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 8176): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8176): QS saving settings...
D/UEI.SmartControl( 8176): IR Blaster version: 25672567
,D/UEI.SmartControl( 8176): serial port data available: 4
,W/ContextImpl( 8176): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 8176): Device manager: loading config....
D/UEI.SmartControl( 8176): ----------- loading internal config...
E/UEI.SmartControl( 8176): Services init done
D/UEI.SmartControl( 8176): QS Service init finished
D/UEI.SmartControl( 8176): QS Service version name: 2.1.91
D/UEI.SmartControl( 8176): QS Service version code: 201091
D/UEI.SmartControl( 8176): Service requested: Control
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 977594569580; DSPS: 32174575; Offset : -4310943522
,E/UEI.SmartControl( 8176): Loading SETTINGS...
D/UEI.SmartControl( 8176): Request IControl service: devices are loaded...
I/ActivityManager( 1037): Killing 7035:com.lge.qremote/u0a112 (adj 15): empty #17
,D/UEI.SmartControl( 8176): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8176): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 8176): -----service ready thread exits
,W/libprocessgroup( 1037): failed to open /acct/uid_10112/pid_7035/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8176): Internal service binding...
,D/serial_port( 8176): close(fd = 25)
,D/UEI.SmartControl( 8176): Internal timer expired: 1
D/UEI.SmartControl( 8176): unbind internal service
D/UEI.SmartControl( 8176): Service.onUnbind: IControl
,D/UEI.SmartControl( 8176): Service.onDestroy
,D/UEI.SmartControl( 8176): Lock is in USE false
,D/UEI.SmartControl( 8176): unbind internal service
W/System.err( 8176): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3fd1281b
,W/System.err( 8176): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8176): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,W/System.err( 8176): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8176): 	at com.uei.control.Service.c(Unknown Source)
,W/System.err( 8176): 	at com.uei.control.Service.onDestroy(Unknown Source)
,W/System.err( 8176): ,	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8176): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,W/System.err( 8176): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8176): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8176): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8176): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8176): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8176): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8176): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8176): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3fd1281b
I/UEI.SmartControl( 8176): Serial port is closed.
I/UEI.SmartControl( 8176): Serial port is closed.
I/UEI.SmartControl( 8176): Serial port is closed.
D/UEI.SmartControl( 8176): Blaster closed
,D/UEI.SmartControl( 8176): Shut down QS...
D/UEI.SmartControl( 8176): Stopping QS lib
D/UEI.SmartControl( 8176): QS lib stop result = true
D/UEI.SmartControl( 8176): Stopped QS lib
D/UEI.SmartControl( 8176): Stopped file observer...
D/UEI.SmartControl( 8176): QS shutdown complete
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 997596602698; DSPS: 32830002; Offset : -4310954794
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1017598170763; DSPS: 33485413; Offset : -4310943178
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1037600868568; DSPS: 34140861; Offset : -4310930920
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1057602940279; DSPS: 34796289; Offset : -4310934482
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1077604945480; DSPS: 35451715; Offset : -4310943337
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1097606629535; DSPS: 36107130; Offset : -4310937827
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1117608680152; DSPS: 36762557; Offset : -4310931940
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1137610808738; DSPS: 37417987; Offset : -4310939610
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1157612787221; DSPS: 38073412; Offset : -4310944718
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1177614854869; DSPS: 38728840; Offset : -4310952213
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1197616711892; DSPS: 39384261; Offset : -4310956736
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1217618501520; DSPS: 40039679; Offset : -4310936998
,I/UsageStatsService( 1037): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1237620612867; DSPS: 40695108; Offset : -4310931546
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1257622651505; DSPS: 41350535; Offset : -4310937586
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1277624676862; DSPS: 42005962; Offset : -4310956775
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1297626728416; DSPS: 42661389; Offset : -4310950082
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1317628768565; DSPS: 43316816; Offset : -4310954585
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1337631459391; DSPS: 43972264; Offset : -4310949254
D/AndroidRuntime( 8248): 
D/AndroidRuntime( 8248): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8248): CheckJNI is OFF
D/AndroidRuntime( 8248): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6899:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1037): WIN DEATH: Window{8150239 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{8150239 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1037): Skipping PackageSetting{23698bc4 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2428cb2a u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  330): DFP En is all cleared set to be enabled
W/ActivityManager( 1037): Spurious death for ProcessRecord{31f1a2fb 6899:com.test.thalitest/u0a311}, curProc for 6899: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{2428cb2a u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{2428cb2a u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{a06378f co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1973): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1973): topRunningActivity=ActivityInfo{312d6a1c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2091): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2091): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1841): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2048): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3742): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/[LGHome]EVENT( 2091): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/PostponalbeReceiver( 6485): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 4548): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4548): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4548): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4548): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4548): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4548): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4548): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4548): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4548): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4548): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4548): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4548): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/SplitUIManager( 1893): split_name #11 / not available #0
D/SplitUIService( 1893): removed split : 
I/art     ( 4596): Explicit concurrent mark sweep GC freed 16469(931KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 346us total 79.539ms
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8280 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 21.339ms
D/SplitUIManager( 1893): split_name #11 / not available #0
I/SplitUIService( 1893): split app #11
D/ActionManagerService( 1927): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2091): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2091): [Launcher.java:1056:onResume()]onResume end
D/LIA_Informant_ActionManagerMessageHandler( 3742): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2091): [Launcher.java:1114:onPause()]onPause
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 591us total 19.559ms
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1927): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3742): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2091): , create_time: 1430558575574
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2091): , create_time: 1430558575600
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/GBoardWebViewUtils( 2091): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2091): , create_time: 1453982950152
I/GBoardWebViewUtils( 2091): , expire_time: 0
I/GBoardWebViewUtils( 2091): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2091): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2091): , display: false
I/GBoardWebViewUtils( 2091): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 19.141ms
D/WallpaperManager( 2091): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3e8b9696,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/LockScreenSettings( 8280): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]EVENT( 2091): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2091): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/art     ( 1037): Explicit concurrent mark sweep GC freed 84397(4MB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 44MB/66MB, paused 2.738ms total 161.245ms
D/AppUp4:PreloadHelper( 7115): added Exclude : com.test.thalitest
I/art     ( 1037): WaitForGcToComplete blocked for 170.106ms for cause Explicit
D/administrator( 1037): Handling package changes for user 0
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8302 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
I/[LGHome]EVENT( 2091): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/ActivityManager( 1037): Killing 7906:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/ResourcesManager( 8302): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8302): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8302): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8302): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8302): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2091): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/KeyguardModel( 1472): handleShortcutListChanged...
W/libprocessgroup( 1037): failed to open /acct/uid_10037/pid_7906/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{1a44488f u0 com.lge.launcher2/.Launcher t3} time:1339366
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[Concierge]WidgetView( 2091): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/[Concierge]Service( 2643): onStartCommand(). Type : 8
D/[Concierge]Service( 2643): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/[Concierge]Service( 2643): Update widget ID : 11
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/[Concierge]WidgetView( 2091): change position of spinner
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): handleShortcutListChanged...
I/SystemConfig( 8302): BUILD Country: EU
I/SystemConfig( 8302): BUILD Operator: OPEN
D/[Concierge]Service( 2643): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2091): initWebView(). Time : 1454529064272
I/art     ( 1037): Explicit concurrent mark sweep GC freed 9358(560KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.578ms total 218.660ms
I/[Concierge]WebView( 2091): Return exist ConciergeWebView. Reuse : 279669247
D/[Concierge]WidgetView( 2091): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2091): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@176000bc
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2091): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2091): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2091): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2091): Widget kill message received. Destory myself. My : 1454527752787, New one : 1454529064272
D/[Concierge]WidgetView( 2091): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2091): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/ActivityManager( 1037): Killing 7933:com.lge.settings.easy/1000 (adj 15): empty #17
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/AndroidRuntime( 8248): Shutting down VM
E/[LgeWidgetLib]LgeAppWidgetHostView( 2091): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2091): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2091): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7933/cgroup.procs: No such file or directory
I/SystemConfig( 8302): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8302): existFile = false
I/Timeline( 2091): Timeline: Activity_idle id: android.os.BinderProxy@1eff4890 time:1339498
I/SystemConfig( 8302): canReadFile = false
I/SystemConfig( 8302): systemFeature RCS result false
D/SystemConfig( 8302): refreshRcsSupport() :false
I/PackageChangeReceiver( 7138): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2166): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8324 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager( 8324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8324): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8324): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8324): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2091): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/AppConfig( 8324): Total System Memory = 2995761152
D/SystemHelper( 8324): region [EU], country [EU], operator [OPEN], sub-operator []
I/GBoardtInterface( 2091): onReloaded()
I/GBoardWebViewClient( 2091): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1927): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3742): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3742): onEvent() : ACTION_BOARD_ENABLED
I/ActivityManager( 1037): Killing 7011:com.lge.sync/1000 (adj 15): empty #17
D/LIA_Service_NativeEventReceiver( 2048): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2048): startLIAService() : Trying to start LIA service ...
D/ActionManagerService( 1927): notifyUserLog: 1000001
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7011/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2048): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/LIA_Informant_ActionManagerMessageHandler( 3742): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3742): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3742): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3742): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3742): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2091): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2091): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/PostponalbeReceiver( 6485): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8346 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a

```
