#### Test 563583788793eb6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
W/ApiaryClient( 7005): Error response from books API: {
W/ApiaryClient( 7005):  "error": {
W/ApiaryClient( 7005):   "errors": [
W/ApiaryClient( 7005):    {
W/ApiaryClient( 7005):     "domain": "global",
W/ApiaryClient( 7005):     "reason": "required",
W/ApiaryClient( 7005):     "message": "Login Required",
W/ApiaryClient( 7005):     "locationType": "header",
W/ApiaryClient( 7005):     "location": "Authorization"
W/ApiaryClient( 7005):    }
W/ApiaryClient( 7005):   ],
W/ApiaryClient( 7005):   "code": 401,
W/ApiaryClient( 7005):   "message": "Login Required"
W/ApiaryClient( 7005):  }
W/ApiaryClient( 7005): }
W/ApiaryClient( 7005): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7005): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5423976654902958559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7005): Headers:
W/ApiaryClient( 7005): accept-encoding: [gzip]
W/ApiaryClient( 7005): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7005): gdata-version: 2
,D/AndroidRuntime( 7140): 
D/AndroidRuntime( 7140): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7140): CheckJNI is OFF
D/AndroidRuntime( 7140): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1993): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{14a87d89 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{14a87d89 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  352): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7159 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7140): Shutting down VM
V/ActivityManager( 1035): Display changed displayId=0
D/DSDPConnection( 1874): Display #0 changed.
D/SplitWindowPolicy( 1993): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1993): topRunningActivity=ActivityInfo{2851e2c9 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1993): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1993): topRunningActivity=ActivityInfo{e6cfdce co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/BooksAccountManager( 7005): Authentication error
E/BooksAccountManager( 7005): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7005): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7005): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7005): null auth token
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{159f727 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ContextHelper( 7159): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,W/ApiaryClient( 7005): Error response from books API: {
W/ApiaryClient( 7005):  "error": {
W/ApiaryClient( 7005):   "errors": [
W/ApiaryClient( 7005):    {
W/ApiaryClient( 7005):     "domain": "global",
W/ApiaryClient( 7005):     "reason": "required",
W/ApiaryClient( 7005):     "message": "Login Required",
W/ApiaryClient( 7005):     "locationType": "header",
W/ApiaryClient( 7005):     "location": "Authorization"
W/ApiaryClient( 7005):    }
W/ApiaryClient( 7005):   ],
W/ApiaryClient( 7005):   "code": 401,
W/ApiaryClient( 7005):   "message": "Login Required"
W/ApiaryClient( 7005):  }
W/ApiaryClient( 7005): }
W/ApiaryClient( 7005): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7005): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5423976654902958559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7005): Headers:
W/ApiaryClient( 7005): accept-encoding: [gzip]
W/ApiaryClient( 7005): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7005): gdata-version: 2
I/WebViewFactory( 7159): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7159): Loading: webviewchromium
I/LibraryLoader( 7159): Time to load native libraries: 4 ms (timestamps 5153-5157)
,I/LibraryLoader( 7159): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7159): Binding Chromium to main looper Looper (main, tid 1) {264d34b9}
,I/LibraryLoader( 7159): Expected native library version number "",actual native library version number ""
I/chromium( 7159): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7159): Initializing chromium process, renderers=0
W/art     ( 7159): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7159): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7159): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 7159): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb57f4fe0, uid 10311
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2caedaf9:true
I/Adreno-EGL( 7159): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7159): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7159): Build Date: 12/12/14 금
I/Adreno-EGL( 7159): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7159): Remote Branch: 
I/Adreno-EGL( 7159): Local Patches: 
I/Adreno-EGL( 7159): Reconstruct Branch: 
,W/chromium( 7159): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7159): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7159): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7159): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7159): CordovaWebView is running on device made by: LGE
,W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{2f3618e u0 com.test.thalitest/.MainActivity t4}
W/art     ( 7159): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7159): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7159): Render dirty regions requested: true
I/OpenGLRenderer( 7159): Initialized EGL, version 1.4
D/OpenGLRenderer( 7159): Enabling debug mode 0
,D/Atlas   ( 7159): Validating map...
D/SplitWindow( 1035): check instance of lgWin Window{be305ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7159): LgDataFeature() Constructor: none
D/LgDataFeature( 7159): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2b989f78,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1471): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +704ms (total +821ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{2f3618e u0 com.test.thalitest/.MainActivity t4} time:295606
I/Timeline( 7159): Timeline: Activity_idle id: android.os.BinderProxy@1e47be29 time:295611
D/JsMessageQueue( 7159): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7159): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7159): 
I/chromium( 7159): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7159): 
E/GBMv2   (  352): DFP En is all cleared set to be enabled
E/GBMv2   (  352): Set value is all cleared set the max
I/GBMv2   (  352): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 7159): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1436528384
I/chromium( 7159): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
W/GLSActivity( 2145): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2145): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2145): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2145): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2145): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7005): Authentication error
E/BooksAccountManager( 7005): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7005): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7005): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7005): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7005): null auth token
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{159f727 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7005): Error response from books API: {
W/ApiaryClient( 7005):  "error": {
W/ApiaryClient( 7005):   "errors": [
W/ApiaryClient( 7005):    {
W/ApiaryClient( 7005):     "domain": "global",
W/ApiaryClient( 7005):     "reason": "required",
W/ApiaryClient( 7005):     "message": "Login Required",
W/ApiaryClient( 7005):     "locationType": "header",
W/ApiaryClient( 7005):     "location": "Authorization"
W/ApiaryClient( 7005):    }
W/ApiaryClient( 7005):   ],
W/ApiaryClient( 7005):   "code": 401,
W/ApiaryClient( 7005):   "message": "Login Required"
W/ApiaryClient( 7005):  }
W/ApiaryClient( 7005): }
W/ApiaryClient( 7005): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7005): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5423976654902958559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7005): Headers:
W/ApiaryClient( 7005): accept-encoding: [gzip]
W/ApiaryClient( 7005): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7005): gdata-version: 2
,E/BooksSync( 7005): Soft error: 
E/BooksSync( 7005): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7005): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5423976654902958559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7005): Headers:
E/BooksSync( 7005): accept-encoding: [gzip]
E/BooksSync( 7005): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7005): gdata-version: 2
E/BooksSync( 7005): 
E/BooksSync( 7005): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7005): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7005): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7005): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7005): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7005): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7005): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7005): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7005): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7005): {
E/BooksSync( 7005):  "error": {
E/BooksSync( 7005):   "errors": [
E/BooksSync( 7005):    {
E/BooksSync( 7005):     "domain": "global",
E/BooksSync( 7005):     "reason": "required",
E/BooksSync( 7005):     "message": "Login Required",
E/BooksSync( 7005):     "locationType": "header",
E/BooksSync( 7005):     "location": "Authorization"
E/BooksSync( 7005):    }
E/BooksSync( 7005):   ],
E/BooksSync( 7005):   "code": 401,
E/BooksSync( 7005):   "message": "Login Required"
E/BooksSync( 7005):  }
E/BooksSync( 7005): }
E/BooksSync( 7005): 
E/BooksSync( 7005): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7005): 	... 8 more
E/BooksSync( 7005): Sync error
E/BooksSync( 7005): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7005): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5423976654902958559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7005): Headers:
E/BooksSync( 7005): accept-encoding: [gzip]
E/BooksSync( 7005): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7005): gdata-version: 2
E/BooksSync( 7005): 
E/BooksSync( 7005): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7005): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7005): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7005): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7005): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7005): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7005): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7005): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7005): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7005): {
E/BooksSync( 7005):  "error": {
E/BooksSync( 7005):   "errors": [
E/BooksSync( 7005):    {
E/BooksSync( 7005):     "domain": "global",
E/BooksSync( 7005):     "reason": "required",
E/BooksSync( 7005):     "message": "Login Required",
E/BooksSync( 7005):     "locationType": "header",
E/BooksSync( 7005):     "location": "Authorization"
E/BooksSync( 7005):    }
E/BooksSync( 7005):   ],
E/BooksSync( 7005):   "code": 401,
E/BooksSync( 7005):   "message": "Login Required"
E/BooksSync( 7005):  }
E/BooksSync( 7005): }
E/BooksSync( 7005): 
E/BooksSync( 7005): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7005): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7005): 	... 8 more
I/BooksSync( 7005): Finished books sync
D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293414, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
W/jxcore-log( 7159): Initializing JXcore engine
W/jxcore-log( 7159): JXcore engine is ready
W/Thread-814( 7229): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7437]" dev="sockfs" ino=7437 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-814( 7229): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-814( 7229): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8590]" dev="sockfs" ino=8590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-814( 7229): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-814( 7229): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34223]" dev="sockfs" ino=34223 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7159): Starting JXcore engine
I/art     ( 7159): Background sticky concurrent mark sweep GC freed 133649(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.192ms total 127.324ms
W/jxcore-log( 7159): Platform android
W/jxcore-log( 7159): 
W/jxcore-log( 7159): Process ARCH arm
W/jxcore-log( 7159): 
,I/jxcore-log( 7159): JXcore Cordova bridge is ready!
I/jxcore-log( 7159): 
,W/jxcore-log( 7159): JXcore engine is started
,I/jxcore-log( 7159): Toggling radios to true
I/jxcore-log( 7159): 
,D/BluetoothAdapter( 7159): enable(): BT is already enabled..!
,D/WifiService( 1035): New client listening to asynchronous messages
D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=7159, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: true pid=7159, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1035): disconnect pid=7159, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1035): [298,386,140 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiServiceImplEx( 1035): reconnect pid=7159, uid=10311, packageName=com.test.thalitest
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
,I/jxcore-log( 7159): Radios toggled
I/jxcore-log( 7159): 
I/jxcore-log( 7159): My device name is: LGE-LG-D855,
I/jxcore-log( 7159): 
I/wpa_supplicant( 2768): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1035): DISCONNECT: returned true
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
,D/Tethering( 1035): InitialState.processMessage what=4
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2145): Read error: ssl=0xaa6d4800: I/O error during system call, Connection timed out
D/DhcpStateMachine( 1035): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaa6d4800: I/O error during system call, Broken pipe
,D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7268 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1035): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1035):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1035): [298,532,400 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
I/wpa_supplicant( 2768): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1035): RECONNECT: returned true
E/WifiStateMachine( 1035):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=298534
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=298534
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/WifiHS20( 1035): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1993): handleWifiStateChangedEvent: 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  314): Clearing all IP addresses on wlan0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=298576  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=298576  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1035): Dns fail occured do internet check.
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1035): hidePasspointNotification off =false
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    ( 1035): EVENT_INTERNET_CHECK_REQUEST received
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1035): try Internet connection check
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=298582  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=298584  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, ret,urning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524292
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateSCANNING
D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICT,ED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkManagementService( 1035): Removing idletimer
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DSQN    ( 1035): ThreadTCPConnectionCheck DNS fail internet is not possible
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1035): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/DSQN    ( 1035): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1035): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1035): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/WifiDataContinuityService( 1035): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/WifiServiceExtension( 1993): isInternetCheckAvailable return false
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7268): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7268): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7268): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7268): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7268): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7268): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7268): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7268): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7296 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6658:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10008/pid_6658/cgroup.procs: No such file or directory
,I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7268): LgDataFeature() Constructor: none
D/LgDataFeature( 7268): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
I/ActivityManager( 1035): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7320 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1035): Killing 6184:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6184/cgroup.procs: No such file or directory
W/ResourcesManager( 7320): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7320): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7320): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7320): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7320): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7320): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7320): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7320): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7320): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7320): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7320): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE,
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
,D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
,D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7320): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7320): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7320): LgDataFeature() Constructor: none
,D/LgDataFeature( 7320): LgDataFeature() Constructor Done, null
V/SoundPool( 7320): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7320): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7320): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7320): doLoad: loading sample sampleID=1
V/SoundPool( 7320): Start decode
V/MediaPlayer[Native]( 7320): decode(31, 10857164, 17813)
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14ce540, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
I/QRemote ( 7320): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
D/QRemote ( 7320): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 7320): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/DSQN    ( 1035): EVENT_INTERNET_CHECK_ENABLE received
V/LGMDMManager( 7320): Create singleton instance
D/UEI.SmartControl( 6775): QS Service created
,I/UEI.SmartControl( 6775): Service initServices...
D/UEI.SmartControl( 6775): QS start get config
,V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf1f0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated, buffer 0xb57bf290 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb14ce540, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb14ce540, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798960
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799120
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf1f0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb14ce540, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab504000, 0xb57c0000, 4096)
,V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab505000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab506000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab507000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab508000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab509000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50a000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50b000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50c000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50d000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50e000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab50f000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab510000, 0xb57c0000, 4096)
,V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab511000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab512000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab513000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab514000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab515000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab516000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab517000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab518000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab519000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51a000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51b000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51c000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51d000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51e000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab51f000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab520000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab521000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab522000, 0xb57c0000, 4096)
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab523000, 0xb57c0000, 4096)
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab524000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab525000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab526000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab527000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab528000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab529000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52a000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52b000, 0xb57c0000, 4096)
,V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52c000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52d000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52e000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab52f000, 0xb57c0000, 4096)
,V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab530000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab531000, 0xb57c0000, 4096)
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4887
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab532000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab533000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab534000, 0xb57c0000, 4096)
V/AudioCache(  321): write(0xb57c0000, 4096)
V/AudioCache(  321): memcpy(0xab535000, 0xb57c0000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb57c0000, 280)
V/AudioCache(  321): memcpy(0xab536000, 0xb57c0000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb14ce540, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb14ce540, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14ce540, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf1f0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321),: [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
,V/SoundPool( 7320): close(31)
V/SoundPool( 7320): pointer = 0x9fe58000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6775): Supports setup maps: true
,D/UEI.SmartControl( 6775): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6775): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6775): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6775): ### init IR Blaster...
D/serial_port( 6775): Configuring serial port
E/UEI.SmartControl( 6775): UEIBLaster setting for 616
I/UEI.SmartControl( 6775): Setting serial record hearder size = 2
I/UEI.SmartControl( 6775): configuring settings for MAXQ616
I/UEI.SmartControl( 6775): Get version...
D/UEI.SmartControl( 6775): serial port data available: 21
,D/UEI.SmartControl( 6775): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6775): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6775): QS saving settings...
D/UEI.SmartControl( 6775): IR Blaster version: 25672567
,D/UEI.SmartControl( 6775): serial port data available: 4
,I/UEI.SmartControl( 6775): Device manager: loading config....
D/UEI.SmartControl( 6775): ----------- loading internal config...
W/ContextImpl( 6775): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6775): Services init done
D/UEI.SmartControl( 6775): QS Service init finished
,D/UEI.SmartControl( 6775): QS Service version name: 2.1.91
D/UEI.SmartControl( 6775): QS Service version code: 201091
D/UEI.SmartControl( 6775): Service requested: Control
E/UEI.SmartControl( 6775): Loading SETTINGS...
D/UEI.SmartControl( 6775): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6775): Internal service binding...
,I/QRemote ( 7320): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6775): ------ IControl API: 11
D/UEI.SmartControl( 6775): File observer start...
E/UEI.SmartControl( 6775): IR Port is disabled: false
D/UEI.SmartControl( 6775): Starting file observer...
I/UEI.SmartControl( 6775): Registering callback...
I/UEI.SmartControl( 6775): ------ IControl API: 19
I/UEI.SmartControl( 6775): Registering Services Ready callback...
D/UEI.SmartControl( 6775): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6775): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6775): -----service ready thread exits
,I/QRemote ( 7320): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7320): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7320): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7320): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7320): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6775): ------ IControl API: 8
D/QRemote ( 7320): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7320): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7320): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7320): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7320): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7320): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7320): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7320): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7320): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7320): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453134456162]
D/QRemote ( 7320): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1035): Killing 6204:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7320): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_6204/cgroup.procs: No such file or directory
,V/QRemote ( 7320): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7320): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7320): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2768): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
,W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=300677  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=300686  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
,D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7268): Not supported operator for automatic switch
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2768): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=300761  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=300761  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=300762
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=300762
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=300762
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=300763
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=300763
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=300764  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=300765  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2768): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2768): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateFOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=300780  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsControl( 7268): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7268): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7268): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=300781  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=300781
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=300782
D/WifiNative-wlan0( 1035): doString: [STATUS]
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
,I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1035): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
,D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1035): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1035): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1035): WaitBeforeStartState
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=300831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=300832  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=300832  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=300833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=300833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=300833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3274e4c5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3274e4c5 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1035): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
,E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1035): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1035): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1993): handleWifiStateChangedEvent: 1
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 101
,I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1035): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
,V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
W/dsqn    ( 7391): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7391): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,E/DSQN    ( 7391): DSQN ssw
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7320): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7320): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7320): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1035): start to monitor internet connection
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7320): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7320): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7320): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 16:27:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453134457075], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453134457055]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Validated
D/ConnectivityService( 1035): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524290
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7397): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7397): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7397): version 5.5.6 starting
E/dhcpcd  ( 7397): get_duid: m
D/dhcpcd  ( 7397): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7397): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7397): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7397): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7397): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7397): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7397): wlan0: sending REQUEST (xid 0xd43e652f), next in 3.58 seconds
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1035): MasterInitialState.processMessage what=3
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1035): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5966): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5966): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 5366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7424 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7424): onCreate
W/AppUp4:DB( 7424):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7424):  setFingerPrint start
I/AppUp4:DB( 7424):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7424):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7424):  SDK version = 21
I/AppUp4:DB( 7424):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7424): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7424): onReceive
D/LgDataFeature( 7424): LgDataFeature() Constructor: none
D/LgDataFeature( 7424): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7424): Context : android.app.ReceiverRestrictedContext@a50005f
D/AppUp4:CustFacade( 7424): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7424): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7424): begin check event
I/AppUp4:CustModeStarterReceiver( 7424): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7424): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7424): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7424): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7424): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1035): Killing 6680:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_6680/cgroup.procs: No such file or directory
,D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3435): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3435): DownloadService onCreate
D/LGDMClient( 4294): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4294): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3435): in removeSpuriousFiles
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@13236610 on behalf of 3435
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3435): in trimDatabase
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@2f8b8509 on behalf of 3435
I/ActivityManager( 1035): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7453 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3435): DownloadService onStartCommand
V/DownloadManager( 3435): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@2fc0d33c on behalf of 3435
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3435): processing inserted download 1
V/DownloadManager( 3435): processing inserted download 4
E/LGDMClient( 4294): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4294): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3435): processing inserted download 7
,D/LGDMClient( 4294): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3435): processing inserted download 8
V/DownloadManager( 3435): processing inserted download 9
,V/DownloadManager( 3435): processing inserted download 10
V/DownloadManager( 3435): processing inserted download 16
V/DownloadManager( 3435): processing inserted download 17
V/DownloadManager( 3435): processing inserted download 18
V/DownloadManager( 3435): processing inserted download 21
V/DownloadManager( 3435): processing inserted download 22
V/DownloadManager( 3435): DownloadService onDestroy
,W/ResourcesManager( 7453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7453): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7453): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7453): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7453): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7453): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7453): No package identifier when getting value for resource number 0x00000000
,E/WifiStateMachine( 1035):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1035): identical MTU - not setting
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524295
I/dhcpcd  ( 7397): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/LgDataFeature( 7453): LgDataFeature() Constructor: none
D/LgDataFeature( 7453): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7397): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7397): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7397): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 7397): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7397): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7397): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7397): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7397): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/eas_req ( 7453): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7491 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/HubEmail( 7453): JNI_OnLoad()
I/HubEmail( 7453): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7453): registerNatives()
I/HubEmail( 7453): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7453): registerNativeMethods()
I/HubEmail( 7453): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7453): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1035): Killing 6713:com.android.gallery3d/u0a27 (adj 15): empty #17
I/art     (  356): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 312us total 25.573ms
,I/art     (  356): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 242us total 11.950ms
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.052ms
,I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7159): 
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_6713/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1035): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3379): networkInfo.isConnected() = false
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1035): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7533 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
V/FormManager( 7491): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7491): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1035): Killing 6598:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10004/pid_6598/cgroup.procs: No such file or directory
,I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7552 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6742:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6742/cgroup.procs: No such file or directory
,I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7159): 
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7569 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7159): 
I/ActivityManager( 1035): Killing 6815:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7159): 
W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_6815/cgroup.procs: No such file or directory
,I/art     ( 7569): Almond Protected OAT
,E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1035):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,D/WeatherApplication( 7569): removeAccount
,D/WeatherApplication( 7569): Account.length = 0
,E/WeatherApplication( 7569): OPERATOR:OPEN
D/WeatherAncestor( 7569): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:39
D/Weather.Utils( 7569): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7569): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7569): 2 : This is isUpdating : false
,D/WeatherAncestor( 7569): connectivity changed - connection : true
D/WeatherService( 7569): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7569): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7569): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7569): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7569): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7569): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:39
,I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7590 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1035): Killing 6875:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6875/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1035): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5966): type=WIFI subType= reason=null isConnected=true
I/jxcore-log( 7159): Test app app.js loaded
I/jxcore-log( 7159): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7159): BLE advertisement is supported
I/jxcore-log( 7159): 
I/chromium( 7159): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WebViewFactory( 7590): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7590): Loading: webviewchromium
I/LibraryLoader( 7590): Time to load native libraries: 4 ms (timestamps 4120-4124)
I/LibraryLoader( 7590): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7590): Binding Chromium to main looper Looper (main, tid 1) {82dbc86}
,I/LibraryLoader( 7590): Expected native library version number "",actual native library version number ""
I/chromium( 7590): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7590): Initializing chromium process, renderers=0
W/art     ( 7590): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  321): registerClient() client 0xb57d7e60, uid 10093
,W/AudioManagerAndroid( 7590): Requires BLUETOOTH permission
,W/chromium( 7590): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7590): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7590): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7590): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7590): Build Date: 12/12/14 금
I/Adreno-EGL( 7590): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7590): Remote Branch: 
I/Adreno-EGL( 7590): Local Patches: 
I/Adreno-EGL( 7590): Reconstruct Branch: 
,I/NSApplication( 7590): Starting up...
,I/ActivityManager( 1035): Killing 6924:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6924/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 84880(4MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.175ms total 169.895ms
,D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7424): onReceive
D/AppUp4:CustFacade( 7424): Context : android.app.ReceiverRestrictedContext@a50005f
D/AppUp4:CustFacade( 7424): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7424): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7424): begin check event
I/AppUp4:CustModeStarterReceiver( 7424): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3435): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3435): DownloadService onCreate
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 4294): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4294): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3435): in removeSpuriousFiles
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null,
,W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@29c5914b on behalf of 3435
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
V/DownloadManager( 3435): DownloadService onStartCommand
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3435): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@16c1cc41 on behalf of 3435
I/LgeMiscReceiver( 3379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3379): networkInfo.isConnected() = false
W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3435): processing inserted download 1
,V/DownloadManager( 3435): processing inserted download 4
I/DownloadManager( 3435): in trimDatabase
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3435): processing inserted download 7
V/DownloadManager( 3435): processing inserted download 8
V/DownloadManager( 3435): processing inserted download 9
V/DownloadManager( 3435): processing inserted download 10
V/DownloadManager( 3435): processing inserted download 16
V/DownloadManager( 3435): processing inserted download 17
V/DownloadManager( 3435): processing inserted download 18
V/DownloadManager( 3435): processing inserted download 21
V/DownloadManager( 3435): processing inserted download 22
,V/DownloadManager( 3435): DownloadService onDestroy
E/LGDMClient( 4294): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4294): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@159f727 on behalf of 3435
D/WeatherAncestor( 7569): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:40
D/Weather.Utils( 7569): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7569): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7569): 2 : This is isUpdating : false
D/WeatherAncestor( 7569): connectivity changed - connection : true
D/WeatherService( 7569): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29036375
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 7569): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7569): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7569): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7569): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7569): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:40
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/LGDMClient( 4294): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2325): [AccountUtils] Account not ready
W/Kids    ( 2325): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2325): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2325): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{159f727 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7424): [onReceive] request level :IDLE....
V/FormManager( 7491): There are no updated forms. The schedule will be deleted.
,I/AppUp4:CustModeStarterReceiver( 7424): onReceive
V/FormManager( 7491): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustFacade( 7424): Context : android.app.ReceiverRestrictedContext@a50005f
D/AppUp4:CustFacade( 7424): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7424): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7424): begin check event
I/AppUp4:CustModeStarterReceiver( 7424): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4294): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3435): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4294): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4294): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3435): DownloadService onCreate
,I/DownloadManager( 3435): in removeSpuriousFiles
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@bc64dd4 on behalf of 3435
W/ContextImpl( 4294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
E/LGDMClient( 4294): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3435): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4294): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,I/DownloadManager( 3435): in trimDatabase
V/DownloadManager( 3435): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4294): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@1b2b8a72 on behalf of 3435
V/DownloadManager( 3435): DownloadService onStartCommand
V/DownloadManager( 3435): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3435): created cursor android.database.sqlite.SQLiteCursor@2a247340 on behalf of 3435
W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3435): processing inserted download 1
V/DownloadManager( 3435): processing inserted download 4
V/DownloadManager( 3435): processing inserted download 7
W/Settings( 7453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3435): processing inserted download 8
,V/DownloadManager( 3435): processing inserted download 9
V/DownloadManager( 3435): processing inserted download 10
V/DownloadManager( 3435): processing inserted download 16
I/LgeMiscReceiver( 3379): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3379): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3379): networkInfo.isConnected() = true
D/PhoneState( 3379): setPdpRejectCasuse : false
V/DownloadManager( 3435): processing inserted download 17
V/DownloadManager( 3435): processing inserted download 18
V/DownloadManager( 3435): processing inserted download 21
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3435): processing inserted download 22
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2325): [AccountUtils] Account not ready
W/Kids    ( 2325): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2325): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2325): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7569): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:40
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/Weather.Utils( 7569): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7569): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7569): 2 : This is isUpdating : false
D/WeatherAncestor( 7569): connectivity changed - connection : true
D/WeatherService( 7569): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29036375
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
V/DownloadManager( 3435): DownloadService onDestroy
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/ForecastDataCache( 7569): 2 : lastUpdatedTime: 1430558561343
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/ForecastDataCache( 7569): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7569): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7569): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7569): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:27:40
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{159f727 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7491): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7491): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2145): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2145): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2145): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2145): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2145): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2325): [AccountUtils] Account not ready
W/Kids    ( 2325): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2325): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2325): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2325): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2325): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2325): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1421): onNotificationPosted
D/SmartCoverUpdateMonitor( 1421): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1421): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1421): handleNotificationPosted(true)
D/QuickCircle( 1421): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1421): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): post do just update job
D/LgeQuickCoverNotificationData( 1421): showAll3
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1421): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1421): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1421): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1421): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1421): updateNotificationData: count=3
D/QuickStatusbarLayout( 1421): Notification difference=198
D/QuickStatusbarLayout( 1421): child = android.widget.LinearLayout{159f727 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6775): Internal timer expired: 2
,D/UEI.SmartControl( 6775): unbind internal service
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
,D/serial_port( 6775): close(fd = 24)
I/UEI.SmartControl( 6775): Serial port is closed.
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1035): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7159): TAP version 13
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # multiplex can send data
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 1 String should be length:200
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # basic
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 2 sane
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # another
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 3 sane
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 4 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 5 null
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 6 (unnamed assert)
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 7 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 8 should not throw
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 306417457750; DSPS: 10181904; Offset : -4321913863
I/jxcore-log( 7159): ok 9 (unnamed assert)
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 10 (unnamed assert)
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 11 should not throw
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 12 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 13 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 14 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # failed to get mobile documents path
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 15 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 16 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 17 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 18 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #init should register the networkChanged event
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 19 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should throw on null device name
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 20 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 21 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 22 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 23 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should throw on negative port
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 24 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should throw on too large port
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 25 should throw
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 26 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 27 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 28 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 29 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 30 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 31 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 32 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 33 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 34 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 35 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 36 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 37 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 38 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 39 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 40 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 41 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 42 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 43 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 44 should be equal
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134463894.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134463894.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3789): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134463894.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134463894.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134463894.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134463894.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134463894.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fca6d02c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fca6d02c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436333839342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436333839342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436333839341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436333839341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1993): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134463894.7159
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/jxcore-log( 7159): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436333839341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436333839341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=32 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464011.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464011.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464011.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464011.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464011.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464011.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464011.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e4b27750 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e4b27750 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343031312e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343031312e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343031311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343031311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464011.7159
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=33 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
D/LGWifiP2pService( 1035): discovery change broadcast true
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=34 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
,I/jxcore-log( 7159): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343031311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343031311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7159): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464050.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{1c95da83 type 2 when 308031 com.google.android.gms} when 308031
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464050.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
V/QRemote ( 7320): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/QRemote ( 7320): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4887
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464050.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464050.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464050.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464050.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464050.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9701f50a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9701f50a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343035302e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343035302e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343035301f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343035301f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464050.7159
D/org.thaliproject.p2p.btconnectorlib.DiscoveryMana,ger( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
I/jxcore-log( 7159): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=35 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343035301f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343035301f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
I/jxcore-log( 7159): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464088.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464088.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464088.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464088.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464088.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464088.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464088.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8a11434 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8a11434 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343038382e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343038382e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343038381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343038381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464088.7159
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/jxcore-log( 7159): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343038381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343038381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464127.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464127.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464127.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464127.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464127.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464127.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464127.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@82449ac0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@82449ac0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343132372e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343132372e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343132371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464127.7159
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343132371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
I/jxcore-log( 7159): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343132371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343132371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/jxcore-log( 7159): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464168.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464168.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464168.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464168.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464168.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464168.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464168.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@45ecaaf6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@45ecaaf6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343136382e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343136382e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343136381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343136381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464168.7159
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 7159): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343136381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343136381f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1035): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464214.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464214.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464214.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464214.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464214.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464214.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464214.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@344a4786 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@344a4786 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343231342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343231342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343231341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343231341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464214.7159
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.Discovery,Manager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 7159): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
,D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
,D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343231341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
,D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343231341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1035): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7159): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464266.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464266.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464266.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464266.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464266.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464266.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464266.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8f5d92b8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8f5d92b8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343236362e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343236362e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343236361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343236361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464266.7159
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNIN,G_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 7159): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
D/LGWifiP2pService( 1035): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343236361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343236361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): ,Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464311.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464311.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464311.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464311.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464311.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464311.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464311.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f50ee60a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f50ee60a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343331312e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343331312e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343331311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343331311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464311.7159
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1035): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1993): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/LGWifiP2pService( 1035): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
I/jxcore-log( 7159): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343331311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343331311f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/jxcore-log( 7159): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464357.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464357.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464357.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134464357.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134464357.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134464357.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134464357.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@64146476 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@64146476 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343335372e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436343335372e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343335371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343335371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134464357.7159
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/WfdsMonitor( 1993): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/LGWifiP2pService( 1035): discovery change broadcast true
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7159): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343335371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436343335371f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
I/jxcore-log( 7159): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
,I/GAV4    ( 7590): Thread[GAThread,5,main]: No campaign data found.
,D/GCM     ( 2145): Connected
,D/GCM     ( 2145): Message class com.google.f.a.a.p
,I/jxcore-log( 7159): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465096.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134465096.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465096.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134465096.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134465096.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134465096.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134465096.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d45b5634 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d45b5634 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436353039362e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436353039362e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353039361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353039361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1993): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465096.7159
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService( 1035): discovery change broadcast true
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
,E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
I/jxcore-log( 7159): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353039361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353039361f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/jxcore-log( 7159): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465615.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134465615.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465615.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134465615.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134465615.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134465615.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134465615.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f6705c7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f6705c7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436353631352e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436353631352e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353631351f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353631351f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1993): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134465615.7159
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/jxcore-log( 7159): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 7159): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 7159): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 7159): ok 69 Should not connect to a bad peer
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353631351f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436353631351f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134466194.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134466194.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7159): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): start: OK
I/io.jxcore.node.ConnectionHelper( 7159): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134466194.7159
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): createAdvertiseData: From: 1453134466194.7159 b6a44ad1-d319-4b3a-815d-8b805a47fb51 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 7159): 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 7159): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 88, 63, 84, 115, 100, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 7159): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7159): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1453134466194.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): start: {"pi":"58:3F:54:73:64:C0","pn":"1453134466194.7159","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1453134466194.7159","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ec2020b4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ec2020b4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState add service
D/LGWifiP2pService( 1035): add a new client
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436363139342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435333133343436363139342e37313539222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436363139341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1035): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436363139341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1993): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1035): P2P_FIND 120: returned true
D/LGWifiP2pService( 1035): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1453134466194.7159
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2768): P2P-FIND-STOPPED 
D/WfdsMonitor( 1993): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1035): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1035): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-FIND-STOPPED 
,D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): P2P device discovery stopped successfully
D/LGWifiP2pService( 1035): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: RESTARTING
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 7159): start: OK
I/jxcore-log( 7159): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 7159): 
D/io.jxcore.node.ConnectionHelper( 7159): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 7159): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 7159): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7159): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 7159): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 7159): 
I/io.jxcore.node.ConnectionHelper( 7159): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7159): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stop: Stopping peer discovery...
D/BluetoothLeScanner( 7159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7159): stop: Stopping services
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1035): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436363139341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1035): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435333133343436363139341f37313539222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1035): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7159): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1035): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1035): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7159): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7159): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7159): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7159): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 7159): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 74 should be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 75 should not be equal
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # setup
I/jxcore-log( 7159): 
I/jxcore-log( 7159): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): # teardown
I/jxcore-log( 7159): 
,I/jxcore-log( 7159): ok 76 irrelevant messages should be ignored
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 77 relevant messages should not be ignored
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ok 78 messages from this device should be ignored
I/jxcore-log( 7159): 
I/jxcore-log( 7159): Tests Complete
I/jxcore-log( 7159): 
,I/chromium( 7159): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7159): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 7159): 
I/jxcore-log( 7159): Toggling radios to false
I/jxcore-log( 7159): 
,D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1035): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1aff1e4d mBinding = false
I/chromium( 7159): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/LocationManagerService( 1035): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1035): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1035): JNI:system_update. Event-4
D/BluetoothManagerService( 1035): Message: 2
D/BluetoothManagerService( 1035): Sending off request.
D/LGBluetoothServiceAdapter( 3789): [BTUI] Precleanup
D/BluetoothAdapterState( 3789): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3789): Setting state to 13
I/BluetoothAdapterState( 3789): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3789): onBluetoothDisable()
I/BluetoothAdapterState( 3789): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3789): Scan Mode:20
,D/BluetoothAdapterState( 3789): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 3789): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3789): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3789): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3789): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3789): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3789): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3789): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3789): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3789): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3789): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3789): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3789): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3789): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3789): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3789): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3789): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3789): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1035): Message: 60
D/BluetoothManagerService( 1035): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1035): Bluetooth State Change Intent: 12 -> 13
,I/ActivityManager( 1035): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7810 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1035): setWifiEnabled: false pid=7159, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: false pid=7159, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
,D/LGBluetoothAPIService( 1993): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1471): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 3789): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3789): STATE_TURNING_OFF
V/BluetoothMapService( 3789): Handler(): got msg=4
D/BluetoothMapService( 3789): MAP Service closeService in
D/BluetoothMapMasInstance( 3789): MAP Service shutdown
D/LGBluetoothMapAdapter( 3789): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3789): MAP Service closeService out
V/BtOppService( 3789): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3789): stopping Accept Thread
V/BtOppRfcommListener( 3789): close mBtServerSocket
V/BtOppRfcommListener( 3789): waiting for thread to terminate
I/BtOppRfcommListener( 3789): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3789): done waiting for thread to terminate
W/ContextImpl( 7268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BtOppService( 3789): onDestroy
D/LGBluetoothOppAdapter( 3789): [BTUI] LGBluetoothOppAdapter cleanup
D/LocationManagerService( 1035): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1035): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1035): JNI:system_update. Event-4
I/jxcore-log( 7159): Radios toggled
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ****TEST TOOK:  ms ****
I/jxcore-log( 7159): 
I/jxcore-log( 7159): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7159): 
E/WifiStateMachine( 1035):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 1035):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
V/BluetoothPbapReceiver( 3789): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3789): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3789): ***********state = 13
V/BluetoothPbapReceiver( 3789): ***********Calling start service!!!! with action = null
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@233e2050:true
V/BluetoothPbapService( 3789): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3789): state: 13
V/BluetoothPbapService( 3789): Pbap Service closeService in
V/BluetoothPbapService( 3789): successfully stopped pbap service
V/BluetoothPbapService( 3789): Pbap Service closeService out
V/BluetoothPbapService( 3789): Pbap Service onDestroy
V/BluetoothPbapService( 3789): Pbap Service closeService in
V/BluetoothPbapService( 3789): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3789): [BTUI] cleanup
,D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/BluetoothManagerService( 1035): Message: 30
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1035): RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1035): Message: 30
D/LocalBluetoothProfileManager( 7268): Adding local MAP profile
D/BluetoothMap( 7268): Create BluetoothMap proxy object
,I/jxcore-log( 7159): Toggling radios to false
I/jxcore-log( 7159): 
D/BluetoothManagerService( 1035): Message: 30
V/NativeCrypto( 2145): Read error: ssl=0xaa6d4800: I/O error during system call, Connection timed out
V/NativeCrypto( 2145): SSL shutdown failed: ssl=0xaa6d4800: I/O error during system call, Broken pipe
D/BluetoothManagerService( 1035): Message: 30
,D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiHS20( 1035): hidePasspointNotification off =false
D/BluetoothManagerService( 1035): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1aff1e4d mBinding = false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1993): handleWifiStateChangedEvent: 0
D/WifiServiceImplEx( 1035): setWifiEnabled: false pid=7159, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: false pid=7159, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7159): Radios toggled
I/jxcore-log( 7159): 
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1035): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@7c665c2
D/LGWifiP2pService( 1035): P2pDisablingState
D/LGWifiP2pService( 1035): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): p2p socket connection lost
D/LGWifiP2pService( 1035): P2pDisabledState
E/WifiStateMachine( 1035):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1035):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1035): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2768): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/WifiHS20( 1035): hidePasspointNotification off =false
D/BluetoothManagerService( 1035): Message: 2
D/BluetoothManagerService( 1035): Sending off request.
D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothServiceAdapter( 3789): [BTUI] Precleanup
D/BluetoothAdapterService( 3789): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1035): IBluetooth.disable() returned false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiScanningService( 1035): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1035): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1035): SCAN_AVAILABLE : 1
D/RttService( 1035): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1993): WfdStateTracker handleDirectStateChangedEvent: 0
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdsService( 1993): WifiP2pState is changed : false
D/WfdsService( 1993): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1993): Set the WFDS Monitor: false
D/LocalBluetoothProfileManager( 7268): LocalBluetoothProfileManager construction complete
D/WfdsMonitor( 1993): WFDS Monitor is stopped
D/WfdsService( 1993): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1993): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1993): Received on exit socket, terminate
E/CtrlSupplicant( 1993): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1993): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1993): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1993): DefaultState - msg [9445378] is not handled
D/LGBluetoothFeatureConfig( 7268):  get() - isFeatureLoaded : false
D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiNative-p2p0( 1035): doBoolean: TERMINATE
D/WifiHS20( 1035): hidePasspointNotification off =false
D/WifiNative-p2p0( 1035): TERMINATE: returned true
E/WifiStateMachine( 1035): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1035): useWiFiOffloading() : false
E/WifiStateMachine( 1035): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/WifiServerServiceExt( 1035): WIFI_STATE_CHANGED_ACTION [0]
V/WfdStateTracker( 1993): WfdStateTracker handleDirectStateChangedEvent: 6
I/StatusBar.NetworkController( 1471): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1471): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateDISCONNECTED
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothUserBindClient( 7268): [BTUI] initUserBindClient
,W/ContextImpl( 7268): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1035): Removing idletimer
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provid,er.Settings.Global, returning read-only value.
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1035): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityManager.CallbackHandler( 1471): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/DockEventReceiver( 7268): finishStartingService: stopping service
D/BluetoothInputDevice( 7268): Proxy object connected
D/HidProfile( 7268): Bluetooth service connected
,D/BluetoothPan( 7268): BluetoothPAN Proxy object connected
D/PanProfile( 7268): Bluetooth service connected
D/BluetoothMap( 7268): Proxy object connected
D/MapProfile( 7268): Bluetooth service connected
D/BluetoothMap( 7268): getConnectedDevices()
D/BluetoothMap( 7268): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7268): [BTUI] onServiceConnected
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1471): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ActivityThread( 7810): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7810): No ProfileInfo entries
I/LG Account v2.2( 7810): isEnabled: false
,I/Feature ( 7810): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7810): [Lifetracker]Country: EU
I/Feature ( 7810): [Lifetracker]Operator: OPEN
I/Feature ( 7810): [Lifetracker]Ranking support: false
I/Feature ( 7810): [Lifetracker]Comfort support: false
I/Feature ( 7810): [Lifetracker]Accessory: true
I/Feature ( 7810): [Lifetracker]Health device: true
I/Feature ( 7810): [Lifetracker]Extra Pedometer: false
I/Feature ( 7810): [Lifetracker]Blood glucose device: false
I/Feature ( 7810): [Lifetracker]Device Number: 3
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGBluetoothAuthorization( 7268): [BTUI] cancel All Notification
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothPermissionRequest( 7268): onReceive
,D/LGBluetoothAuthorization( 7268): [BTUI] cancel All Notification
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
I/wpa_supplicant( 2768): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2768): monitor socket send errors count : 1
I/wpa_supplicant( 2768): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1993-2\x00 that cannot receive messages
D/WifiMonitor( 1035): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1035): Dropping event because (p2p0) is stopped
I/ActivityManager( 1035): Killing 6904:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 7268): return without doing reset settings.
,D/AndroidRuntime( 7849): 
D/AndroidRuntime( 7849): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7849): CheckJNI is OFF
I/wpa_supplicant( 2768): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
W/wpa_supplicant( 2768): USIM:  scard_deinit function
D/Tethering( 1035): InitialState.processMessage what=4
E/WifiStateMachine( 1035):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=311425
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=311425
E/WifiStateMachine( 1035):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=311426  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=311426  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/BluetoothOppReceiver( 3789): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3789): [BTUI] cancel opp incoming file confirm notification
W/libprocessgroup( 1035): failed to open /acct/uid_10005/pid_6904/cgroup.procs: No such file or directory
,D/BluetoothOppNotification( 3789): [BTUI] cancel opp active transfer file notification
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1035):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1035):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/BluetoothFtpReceiver( 3789): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/BluetoothFtpReceiver( 3789): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3789): Ftp Service onStartCommand
V/BluetoothFtpService( 3789): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3789): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3789): Shutdown
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3789): successfully stopped ftp service
,V/BluetoothSapReceiver( 3789): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3789): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3789): SapReceiver onReceive 
V/BluetoothSapReceiver( 3789): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3789):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3789): Calling SAP service start service with action = null
V/BluetoothFtpService( 3789): Ftp Service onDestroy
V/BluetoothFtpService( 3789): Ftp Service closeService
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1035): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7873 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/AndroidRuntime( 7849): Calling main entry com.android.commands.pm.Pm
V/BluetoothSapService( 3789): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3789): state: 13
V/BluetoothSapService( 3789): Stopping SAP server process
V/BluetoothSapService( 3789): Sap Service closeSapService in
V/BluetoothSapService( 3789): Close listen Socket : 
V/BluetoothSapService( 3789): Close rfcomm Socket : 
V/BluetoothSapService( 3789): Close sapd  Socket : 
V/BluetoothSapService( 3789): Sap Service closeSapService out
V/BluetoothSapService( 3789): Sap Service onDestroy
V/BluetoothSapService( 3789): Sap Service closeSapService in
V/BluetoothSapService( 3789): Close listen Socket : 
V/BluetoothSapService( 3789): Close rfcomm Socket : 
V/BluetoothSapService( 3789): Close sapd  Socket : 
V/BluetoothSapService( 3789): Sap Service closeSapService out
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/wpa_supplicant( 2768): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1035): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1035):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 59 0
W/PackageSettings( 1035): Skipping PackageSetting{136f81a4 com.example.hello/10319} due to missing metadata
,V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1035): Killing 7159:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
I/WindowState( 1035): WIN DEATH: Window{be305ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1035): Client connection lost with reason: 4
,D/InputDispatcher( 1035): Window went away: Window{be305ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2f3618e u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  352): DFP En is all cleared set to be enabled
,I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2f3618e u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1035): Duplicate finish request for ActivityRecord{2f3618e u0 com.test.thalitest/.MainActivity t4 f}
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Service_RemotePackageHandler( 2055): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3706): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [+] updateMediaPlayerInfo
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
,D/bt_hci_bdroid( 3789): cleanup
,I/bt_userial_mct( 3789): exiting userial_read_thread
D/bt_userial_mct( 3789): Leaving userial_evt_read_thread()
,W/bt-btif ( 3789): ag scb idx 1 not allocated
E/bt-btif ( 3789): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3789): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3789): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3789): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3789): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3789): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3789): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3789): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3789): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3789): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3789): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3789): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3789): userial_close_reader Joined userial reader thread: 0
I/bt_lpm  ( 3789): LPM is already off!!!
I/bt_vendor( 3789): hw_epilog_process
D/bt_hci_bdroid( 3789): cleanup Finalizing cleanup
D/bt_userial_mct( 3789): userial_close
E/bt_userial_mct( 3789): pthread_join() FAILED result:3
I/bt_vendor( 3789): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/art     ( 4561): Explicit concurrent mark sweep GC freed 15224(884KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 546us total 88.903ms
,W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 2106): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2106): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1993): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1993): topRunningActivity=ActivityInfo{351104ef co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[SystemUI]QSlideListController( 1471): onReceive = android.intent.action.PACKAGE_REMOVED
W/System.err( 4513): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4513): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4513): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4513): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4513): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4513): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4513): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4513): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4513): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4513): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4513): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4513): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/WifiOffDelayIfNotUsed( 1035): stopMonitoring
E/WifiStateMachine( 1035): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1035): useWiFiOffloading() : false
E/WifiStateMachine( 1035): CONFIG_LGE_WLAN_PATH : true
D/SplitWindowPolicy( 1993): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1993): topRunningActivity=ActivityInfo{79a1bfc co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7901 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1035): Spurious death for ProcessRecord{2b2260d6 7159:com.test.thalitest/u0a311}, curProc for 7159: null
I/[LGHome]EVENT( 2106): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/ResourcesManager( 7873): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1935): notifyUserLog: 1000003
,D/WfdsService( 1993): Supplicant Connection state is changed : false
D/WfdsService( 1993): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
V/WfdStateTracker( 1993): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1993): Set the WFDS Monitor: false
D/WfdsMonitor( 1993): WFDS Monitor is stopped
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000003)
W/Settings( 1839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[LGHome]LGActivityUtil( 2106): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2106): [Launcher.java:1056:onResume()]onResume end
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1471): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/StatusBar.NetworkController( 1471): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/[LGHome]EVENT( 2106): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1471): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/AuthorizationBluetoothService( 2145): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1935): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2106): , create_time: 1430558575574
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2106): , create_time: 1430558575600
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2106): , create_time: 1452774039338
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/PCSuite ( 7296): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7296): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hci_bdroid( 3789): set_power 0
I/bt_vendor( 3789): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3789): bluetooth satus is on
I/bt_vendor( 3789): bt-vendor : resetting BT status
I/bt_vendor( 3789): Starting hciattach daemon
I/bt_vendor( 3789): try to set false
I/bt_vendor( 3789): Starting hciattach daemon
I/bt_vendor( 3789): try to set false
I/bt_vendor( 3789): cleanup
I/GKI_LINUX( 3789): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3789): GKI_exit_task 0 done
I/GKI_LINUX( 3789): GKI_shutdown(): task [BTU] terminated
D/WallpaperManager( 2106): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/BluetoothAdapterState( 3789): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
W/ActivityManager( 1035): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
I/art     ( 1035): Explicit concurrent mark sweep GC freed 73022(4MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.995ms total 210.682ms
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] installed app name: Google Play Music
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] [-] updateMediaPlayerInfo
I/art     ( 1035): WaitForGcToComplete blocked for 58.191ms for cause Explicit
,D/HeadsetService( 3789): Received stop request...Stopping profile...
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
D/BluetoothAdapterState( 3789): Stopping profile services that were post enabled
I/LGBluetoothHfpAdapter( 3789): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3789): Cleaning up Bluetooth Handsfree callback object
D/HeadsetStateMachine( 3789): Exit Disconnected: -1
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/A2dpService( 3789): Received stop request...Stopping profile...
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/A2dpStateMachine( 3789): Exit Disconnected: -1
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2b989f78,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LGBluetoothAvrcpQcomAdapter( 3789): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3789): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3789): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
D/HidService( 3789): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
D/BluetoothInputDevice( 7268): Proxy object disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
D/HealthService( 3789): Received stop request...Stopping profile...
D/HidProfile( 7268): Bluetooth service disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
,D/PanService( 3789): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
D/BtGatt.DebugUtils( 3789): handleDebugAction() action=null
D/BtGatt.GattService( 3789): Received stop request...Stopping profile...
D/BtGatt.GattService( 3789): stop()
D/BtGatt.AdvertiseManager( 3789): advertise clients cleared
I/[LGHome]EVENT( 2106): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/SplitUIManager( 1891): split_name #11 / not available #0
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIService( 1891): removed split : 
I/LockScreenSettings( 7901): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
D/BluetoothMapService( 3789): Received stop request...Stopping profile...
D/BluetoothMapService( 3789): stop()
D/BluetoothMapEmailAppObserver( 3789): deinitObservers()
D/BluetoothMapEmailAppObserver( 3789): removeReceiver()
D/BluetoothAdapterService( 3789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ca74aac
,D/BluetoothPan( 7268): BluetoothPAN Proxy object disconnected
D/HeadsetStateMachine( 3789): Unbinding service...
D/HeadsetPhoneState( 3789): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3789): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3789): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3789): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3789): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3789): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3789): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3789): cleanupNative
I/GKI_LINUX( 3789): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3789): GKI_exit_task 2 done
I/GKI_LINUX( 3789): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3789): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3789): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3789): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3789): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3789): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3789): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3789): Cleaning up Bluetooth PAN callback object
D/PanProfile( 7268): Bluetooth service disconnected
D/BluetoothMap( 7268): Proxy object disconnected
D/MapProfile( 7268): Bluetooth service disconnected
V/BluetoothMapService( 3789): Handler(): got msg=4
D/BluetoothMapService( 3789): MAP Service closeService in
D/LGBluetoothMapAdapter( 3789): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3789): MAP Service closeService out
D/BluetoothMapService( 3789): cleanup()
D/BluetoothMapService( 3789): MAP Service closeService in
D/LGBluetoothMapAdapter( 3789): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3789): MAP Service closeService out
D/BluetoothAdapterState( 3789): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3789): Setting state to 10
I/BluetoothAdapterState( 3789): Bluetooth adapter state changed: 13-> 10
D/QRemote ( 7320): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7320): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7320): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/administrator( 1035): Handling package changes for user 0
,D/BluetoothManagerService( 1035): Message: 60
D/BluetoothManagerService( 1035): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1035): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1035): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3789): Entering OffState
D/KeyguardModel( 1471): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/BluetoothMap( 7268): onBluetoothStateChange: up=false
D/KeyguardModel( 1471): createShortcutInfo...
,D/PCSuite ( 7296): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothPan( 7268): onBluetoothStateChange on: false
D/KeyguardModel( 1471): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/SplitUIManager( 1891): split_name #11 / not available #0
I/SplitUIService( 1891): split app #11
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7268): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothPbap( 7268): onBluetoothStateChange: up=false
V/WiFiOffLoadBroadcast( 7268): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/KeyguardModel( 1471): handleShortcutListChanged...
D/BluetoothA2dp( 1035): onBluetoothStateChange: up=false
W/FormManager( 7491): Network not available. Please check & try again.
D/KeyguardModel( 1471): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/BluetoothManagerService( 1035): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1035): Broadcasting onBluetoothServiceDown() to 7 receivers.
,D/KeyguardModel( 1471): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothManagerService( 1035): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1035): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1035): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1aff1e4d mBinding = false
I/[LGHome]EVENT( 2106): [Launcher.java:5349:onStop()]onStop
D/BluetoothManagerService( 1035): Sending unbind request.
D/KeyguardModel( 1471): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1471): createShortcutInfo...
D/BluetoothManagerService( 1035): Bluetooth State Change Intent: 13 -> 10
I/[SystemUI]BluetoothHandler( 1471): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1993): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1993): Message: 2
D/LGBluetoothAPIService( 1993): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@120ce285 mBinding = false
D/LGBluetoothAPIService( 1993): Sending unbind request.
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapter( 1471): 300491350: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1471): 300491350: getState() :  mService = null. Returning STATE_OFF
D/KeyguardModel( 1471): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1471): createShortcutInfo...
W/ResourceType( 1471): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1471): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,V/FormManager( 7491): Network unavailable.
D/KeyguardModel( 1471): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1471): createShortcutInfo...
I/GKI_LINUX( 3789): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3789): GKI_exit_task 1 done
I/GKI_LINUX( 3789): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3789): cleanupNative: return from cleanup
I/art     ( 3789): --- WEIRD: removing null entry 246
W/art     ( 3789): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3789): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3789): [BTUI] unregister observer for LG device name DB
D/WiFiOffLoadBroadcast( 7268): MCCMNC not supported: null
I/art     ( 3789): System.exit called, status: 0
I/AndroidRuntime( 3789): VM exiting with result code 0, cleanup skipped.
,D/LGBluetoothFeatureConfig( 7268): isPrivacyLogsEnabled : true
I/ActivityManager( 1035): Killing 6306:com.android.vending/u0a44 (adj 15): empty #17
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/AudioFlinger(  321): 3789 died, releasing its sessions
V/AudioFlinger(  321):  pid 1874 @ 0
V/AudioFlinger(  321):  pid 3379 @ 1
V/AudioFlinger(  321):  pid 3379 @ 2
,D/LGBluetoothUtils( 7268): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7268): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7268): [BTUI] clear device connection state
W/ContextImpl( 7268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 2950): Thermal-Lib-Client: Client request sent
I/NotificationService( 1035): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1035): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2106): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2106): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2106): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 1035): Explicit concurrent mark sweep GC freed 11526(602KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.713ms total 222.788ms
,D/KeyguardModel( 1471): handleShortcutListChanged...
,I/ActivityManager( 1035): Process com.android.bluetooth (pid 3789) has died
,W/ActivityManager( 1035): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,I/WifiServerServiceExt( 1035): WIFI_STATE_CHANGED_ACTION [1]
,D/TaskPersister( 1035): removeObsoleteFile: deleting file=4_task.xml
W/libprocessgroup( 1035): failed to open /acct/uid_10044/pid_6306/cgroup.procs: No such file or directory
I/WifiServerServiceExt( 1035): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1035): batteryPsActivateMsgHandler : this is not treated
D/PhoneStatusBar( 1471): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/LGBluetoothUserBindClient( 7268): [BTUI] onServiceDisconnected
I/[SystemUI]NavigationThemeResource( 1471): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1471):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1471): , Keyguard show=false, IME shown=false, Panel expanded=false
V/FormManager( 7491): Network unavailable.
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{344d95ef u0 com.lge.launcher2/.Launcher t3} time:312526
D/DockEventReceiver( 7268): finishStartingService: stopping service
D/[Concierge]Service( 2619): onStartCommand(). Type : 8
D/[Concierge]Service( 2619): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2106): change position of spinner
D/[Concierge]Service( 2619): Update widget ID : 11
,D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7268): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7268): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7268): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7268): [AUTORUN] setTetherStatus() : status=false
I/[Concierge]WidgetView( 2106): initWebView(). Time : 1453134468553
D/[Concierge]Service( 2619): onStartCommand(). Type : 0
D/BluetoothPermissionRequest( 7268): onReceive
D/LGBluetoothUtils( 7268): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7268): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7268): return without doing reset settings.
I/ActivityManager( 1035): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7931 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 7005:com.google.android.apps.books/u0a54 (adj 15): empty #17
,D/AndroidRuntime( 7849): Shutting down VM
W/libprocessgroup( 1035): failed to open /acct/uid_10054/pid_7005/cgroup.procs: No such file or directory
,D/PostponalbeReceiver( 5366): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ResourcesManager( 7931): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7931): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7931): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7931): Loading JNI Library
I/[Concierge]WebView( 2106): Return exist ConciergeWebView. Reuse : 104314824
D/[Concierge]WidgetView( 2106): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2106): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2b25d621
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AppUp4:PreloadHelper( 7424): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2106): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/BluetoothAdapterApp( 7931): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10b9b9bd Instance Count = 1
D/[Concierge]WidgetView( 2106): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2106): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1035): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7948 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/BluetoothAdapterApp( 7931): onCreate
W/[Concierge]WidgetView( 2106): Widget kill message received. Destory myself. My : 1453134184245, New one : 1453134468553
D/[Concierge]WidgetView( 2106): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2106): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/ProfileConfigQcom( 7931): [BTUI] HeadsetService is supported
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
D/ProfileConfigQcom( 7931): Adding HeadsetService
D/ProfileConfigQcom( 7931): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7931): Adding A2dpService
D/ProfileConfigQcom( 7931): [BTUI] HidService is supported
D/ProfileConfigQcom( 7931): Adding HidService
D/ProfileConfigQcom( 7931): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7931): Adding HealthService
D/LGBluetoothFeatureConfig( 7931): isSupportPan() :  mTargetOp=OPEN
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
D/ProfileConfigQcom( 7931): [BTUI] PanService is supported
D/ProfileConfigQcom( 7931): Adding PanService
D/ProfileConfigQcom( 7931): [BTUI] GattService is supported
D/ProfileConfigQcom( 7931): Adding GattService
D/ProfileConfigQcom( 7931): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7931): Adding BluetoothMapService
D/ProfileConfigQcom( 7931): [BTUI] HeadsetClientService is NOT supported
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/LGBluetoothOppAdapter( 7931): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGBluetoothUserBindClient( 7268): [BTUI] onServiceConnected
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/LGMDMManagerInternal( 7931): Create singleton instance
W/ResourcesManager( 7948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7948): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7948): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7948): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7948): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/BluetoothFtpReceiver( 7931): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7931): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7931): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7931): SapReceiver onReceive 
V/BluetoothSapReceiver( 7931): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7931):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7873): [BTUI] STATE_OFF : reset connected device information EasySettings
I/Timeline( 2106): Timeline: Activity_idle id: android.os.BinderProxy@13db2c70 time:312738
I/ActivityManager( 1035): Killing 7453:com.lge.email/u0a23 (adj 15): empty #17
I/SystemConfig( 7948): BUILD Country: EU
,I/SystemConfig( 7948): BUILD Operator: OPEN
D/AuthorizationBluetoothService( 2145): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_7453/cgroup.procs: No such file or directory
I/ActivityManager( 1035): Killing 7533:com.android.chrome/u0a57 (adj 15): empty #17
I/chromium( 2106): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2106): onReloaded()
,W/libprocessgroup( 1035): failed to open /acct/uid_10057/pid_7533/cgroup.procs: No such file or directory
E/SQLiteLog( 2172): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/GBoardWebViewClient( 2106): onPageFinished url:file:///android_asset/www/main.html
D/ContactsProvider2ForLG( 2172): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2172): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2172): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2172): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2172): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2172): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2172): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2172): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2172): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2172): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SystemConfig( 7948): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7948): existFile = false
I/SystemConfig( 7948): canReadFile = false
I/SystemConfig( 7948): systemFeature RCS result false
D/SystemConfig( 7948): refreshRcsSupport() :false
V/BoardContentProvider( 3706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/VoicemailCleanupService( 2172): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2172): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2172): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2172): Process: android.process.acore, PID: 2172
E/AndroidRuntime( 2172): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2172): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2172): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2172): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2172): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2172): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2172): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2172): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2172): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2172): 	at android.content.ContentProvider$Tr,ansport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2172): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2172): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2172): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2172): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2172): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2172): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1035): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7972 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/BoardContentProvider( 3706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/Process ( 2172): Sending signal. PID: 2172 SIG: 9
I/ActivityManager( 1035): Process android.process.acore (pid 2172) has died
,W/ActivityManager( 1035): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1035): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
D/ActionManagerService( 1935): notifyUserLog: 1000001
E/DropBoxManagerService( 1035): Can't write: system_app_crash
E/DropBoxManagerService( 1035): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1035): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1035): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1035): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1035): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1035): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1035): 	... 5 more
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3706): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1935): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3706): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3706): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3706): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2106): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2106): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2106): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2106): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2106): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2106): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,W/ResourcesManager( 7972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7972): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7972): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7972): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7972): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 7972): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7972): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7972): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7972): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7972): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7972): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7972): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 7972): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7972): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 7972): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 7972): 	at android,.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 7972): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 7972): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 7972): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 7972): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 7972): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 7972): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 7972): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 7972): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 7972): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 7972): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 7972): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 7972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7972): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7972): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7972): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7972): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/SQLiteDatabase( 7972): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 7972): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7972): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7972): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7972): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7972): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7972): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7972): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7972): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7972): Shutting down VM
E/AndroidRuntime( 7972): FATAL EXCEPTION: main
E/AndroidRuntime( 7972): Process: com.lge.email, PID: 7972
E/AndroidRuntime( 7972): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7972): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7972): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7972): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7972): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7972): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7972): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7972): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 797,2): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7972): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7972): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7972): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7972): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7972): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7972): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7972): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7972): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7972): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7972): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7972): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7972): 	... 11 more
E/DropBoxManagerService( 1035): Can't write: system_app_crash
E/DropBoxManagerService( 1035): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1035): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1035): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1035): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1035): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1035): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1035): 	... 5 more
I/Process ( 7972): Sending signal. PID: 7972 SIG: 9
I/ActivityManager( 1035): Process com.lge.email (pid 7972) has died
,I/GBoardtInterface( 2106): exportHTML()
,I/GBoardtInterface( 2106): exportHTML()

```
