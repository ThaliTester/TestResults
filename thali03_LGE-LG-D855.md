#### Test 58135655812b57f_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
--------- beginning of main
D/LgeQuickCoverNLService( 1420): onNotificationPosted
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=781076910983210559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
D/AndroidRuntime( 6716): 
D/AndroidRuntime( 6716): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6716): CheckJNI is OFF
D/AndroidRuntime( 6716): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1980): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{9c31dc3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{9c31dc3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6734 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6716): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{23afc85a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{107fea8b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6734): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6734): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6734): Loading: webviewchromium
I/LibraryLoader( 6734): Time to load native libraries: 4 ms (timestamps 3142-3146)
I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6734): Binding Chromium to main looper Looper (main, tid 1) {1a9dae8a}
I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
I/chromium( 6734): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6734): Initializing chromium process, renderers=0
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  312): registerClient() client 0xb14fd9a0, uid 10311
W/chromium( 6734): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6734): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6734): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c985435:true
I/Adreno-EGL( 6734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6734): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6734): Build Date: 12/12/14 금
I/Adreno-EGL( 6734): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6734): Remote Branch: 
I/Adreno-EGL( 6734): Local Patches: 
I/Adreno-EGL( 6734): Reconstruct Branch: 
W/chromium( 6734): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6734): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6734): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6734): CordovaWebView is running on device made by: LGE
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6734): Render dirty regions requested: true
I/OpenGLRenderer( 6734): Initialized EGL, version 1.4
D/OpenGLRenderer( 6734): Enabling debug mode 0
D/Atlas   ( 6734): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{e4de407 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6734): LgDataFeature() Constructor: none
D/LgDataFeature( 6734): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33fc21b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Timeline( 6734): Timeline: Activity_idle id: android.os.BinderProxy@646ce3a time:103595
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +612ms (total +719ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{22f74640 u0 com.test.thalitest/.MainActivity t4} time:103598
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/JsMessageQueue( 6734): Set native->JS mode to OnlineEventsBridgeMode
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=781076910983210559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
I/chromium( 6734): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6734): 
D/jxcore_app_log( 6734): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435227392
I/chromium( 6734): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6734): 
I/chromium( 6734): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
,I/GBMv2   (  335): DFP Enabled. Ignore VFP set
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=781076910983210559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
W/jxcore-log( 6734): Initializing JXcore engine
W/jxcore-log( 6734): JXcore engine is ready
,W/Thread-794( 6805): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8455]" dev="sockfs" ino=8455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-794( 6805): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-794( 6805): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9603]" dev="sockfs" ino=9603 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-794( 6805): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-794( 6805): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33879]" dev="sockfs" ino=33879 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6734): Starting JXcore engine
,W/jxcore-log( 6734): Platform android
W/jxcore-log( 6734): 
W/jxcore-log( 6734): Process ARCH arm
W/jxcore-log( 6734): 
,I/jxcore-log( 6734): JXcore Cordova bridge is ready!
I/jxcore-log( 6734): 
W/jxcore-log( 6734): JXcore engine is started
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=781076910983210559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=781076910983210559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
,I/ActivityManager( 1037): Killing 5179:com.android.calendar/u0a13 (adj 15): empty #17
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78496, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1037): failed to open /acct/uid_10013/pid_5179/cgroup.procs: No such file or directory
,I/jxcore-log( 6734): Toggling radios to true
I/jxcore-log( 6734): 
D/BluetoothAdapter( 6734): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6734, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6734, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6734, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=6734, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6734): Radios toggled
I/jxcore-log( 6734): 
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6734): My device name is: LGE-LG-D855
I/jxcore-log( 6734): 
E/WifiNative: ( 1037): [106,029,938 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  308): Clearing all IP addresses on wlan0
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6822 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2141): Read error: ssl=0xaf4d4400: I/O error during system call, Connection timed out
,V/NativeCrypto( 2141): SSL shutdown failed: ssl=0xaf4d4400: I/O error during system call, Broken pipe
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [106,156,975 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106164
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106164
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 0
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CommandListener(  308): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1037): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106210  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106226  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106238  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 6822): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6822): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6822): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6822): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6822): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6822): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 2141): Explicit concurrent mark sweep GC freed 23855(1420KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 949us total 49.659ms
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2141): innerSync failed
D/ContactsSyncAdapter( 2141): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2141): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2141): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2141): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2141): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2141): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2141): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2141): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2141): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2141): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2141): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindo,w( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 102101, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1037): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 167269, reason: 10019
,D/QuickStatusbarLayout( 1420): Notification difference=198
,D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-169ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6822): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6822): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6822): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6822): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6404:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6404/cgroup.procs: No such file or directory
,I/GAV2    ( 6652): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{c827f2c type 0 when 1454948695332 android} when 1454948695332
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1e57bdf5 type 2 when 106601 com.google.android.gms} when 106601
I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6858): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6822): LgDataFeature() Constructor: none
D/LgDataFeature( 6822): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6884 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6057:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6057/cgroup.procs: No such file or directory
,W/ResourcesManager( 6884): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6884): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6884): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6884): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6884): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6884): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6884): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6884): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6884): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6858): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6884): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null,
D/QRemote ( 6884): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6858): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6858): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiStateMachine( 1037):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:42049] from screen [on:0 period:-1045217274]
V/QRemote ( 6884): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6884): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6884): LgDataFeature() Constructor: none
D/LgDataFeature( 6884): LgDataFeature() Constructor Done, null
,V/SoundPool( 6884): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6884): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6884): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6884): doLoad: loading sample sampleID=1
I/QRemote ( 6884): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6884): Start decode
V/MediaPlayer[Native]( 6884): decode(31, 10857164, 17813)
,D/UEI.SmartControl( 6592): QS Service created
V/MediaPlayerService(  312): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  312): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  312): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  312): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  312): player type = 3
V/AwesomePlayer(  312): AwesomePlayer create()
D/QRemote ( 6884): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AwesomePlayer(  312): reset_l() 
,V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): setAudioSink() 
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb5474c00, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/Utils   (  312): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  312): setDataSource_l dataSource
V/LGParserOSAL(  312): SniffLGParser start
V/LGParserOSAL(  312): MainType:5, SubType=0
V/LGParserOSAL(  312): #### check Mime : application/ogg
V/LGParserOSAL(  312): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  312): Use LGExtractor :application/ogg 
E/QRemote ( 6884): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6592): Service initServices...
D/UEI.SmartControl( 6592): QS start get config
V/LGMDMManager( 6884): Create singleton instance
,V/LGParserOSAL(  312): supported mime: application/ogg
V/AwesomePlayer(  312): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  312): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  312): mBitrate = -1 bits/sec
V/AwesomePlayer(  312): AudioTrack Setting
V/AwesomePlayer(  312): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  312): setAudioSource() 
V/MediaPlayerService(  312): prepare
V/AwesomePlayer(  312): prepareAsync_l() 
V/MediaPlayerService(  312): wait for prepare
V/AwesomePlayer(  312): onPrepareAsyncEvent() 
V/AwesomePlayer(  312): initAudioDecoder() 
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  312): isAudioPlaybackHookOn() false
V/AwesomePlayer(  312): getUseOffload() = 0 
V/OMXCodec(  312): OMXCodec::Create
V/OMXCodec(  312): findMatchingCodecs()
V/OMXCodec(  312): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  312): matchingCodecs.size()=1
V/OMXCodec(  312): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  312): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  312): LG Codec Adapter start
V/OMXCodec(  312): OMXCodec Createtor
V/OMXCodec(  312): setComponentRole
V/OMXCodec(  312): configureCodec protected=0
V/LGCodecAdapter(  312): called getLGCodecSpecificData
V/LGCodecOSAL(  312): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMSG
V/LGCodecOSAL(  312): Not support LGCodec
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  312): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  312): Could not offload audio decode, try pcm offload
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  312): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  312): init()
,V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  312): allocateBuffers
V/OMXCodec(  312): allocateBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fce20 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb17502e0 on output port
V/OMXCodec(  312): init() mAsyncCompletion wait!!! 
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  312): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  312): finishAsyncPrepare_l() 
V/AudioCache(  312): notify(0xb5474c00, 5, 0, 0)
V/AudioCache(  312): ignored
V/AudioCache(  312): notify(0xb5474c00, 1, 0, 0)
V/AudioCache(  312): prepared
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): start
V/AwesomePlayer(  312): play_l() 
V/AwesomePlayer(  312): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  312): createAudioPlayer_l
V/AwesomePlayer(  312): seekAudioIfNecessary_l() 
V/AwesomePlayer(  312): startAudioPlayer_l() 
D/AudioPlayer(  312): start of Playback, useOffload 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  312): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797344
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2977235680
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  312): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] alloc,ating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fce20 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  312): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  312): notify(0xb5474c00, 6, 0, 0)
V/AudioCache(  312): ignored
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab700000, 0xb57ea000, 4096)
V/MediaPlayerService(  312): wait for playback complete
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab701000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab702000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab703000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab704000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab705000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
,V/AudioCache(  312): memcpy(0xab706000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab707000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab708000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab709000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70a000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70b000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70c000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70d000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70e000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab70f000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab710000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab711000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab712000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab713000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab714000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab715000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab716000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab717000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab718000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab719000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71a000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71b000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71c000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71d000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71e000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab71f000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab720000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab721000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab722000, 0xb57ea000, 4096)
,V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab723000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab724000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab725000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab726000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab727000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab728000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab729000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72a000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72b000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72c000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72d000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72e000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab72f000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab730000, 0xb57ea000, 4096)
V/AudioCache(  312): write(0xb57ea000, 4096)
V/AudioCache(  312): memcpy(0xab731000, 0xb57ea000, 4096)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  312): postAudioEOS() 
V/AudioCache(  312): write(0xb57ea000, 280)
V/AudioCache(  312): memcpy(0xab732000, 0xb57ea000, 280)
V/AwesomePlayer(  312): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  312): onStreamDone
V/AwesomePlayer(  312): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  312): notify(0xb5474c00, 2, 0, 0)
V/AudioCache(  312): playback complete
V/AwesomePlayer(  312): pause_l() 
V/AudioCache(  312): notify(0xb5474c00, 7, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  312): Pause Playback at 1068125
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb5474c00, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/AudioPlayer(  312): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14fce20 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  312): AudioPlayer releasing audio source
D/AudioPlayer(  312): AudioPlayer done releasing audio source
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): ~AwesomePlayer call
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/SoundPool( 6884): close(31)
V/SoundPool( 6884): pointer = 0x9ff45000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6884): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2341
I/UEI.SmartControl( 6592): Supports setup maps: true
,D/UEI.SmartControl( 6592): QS start statue = true Error code = 0
I/UEI.SmartControl( 6592): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6592): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6592): ### init IR Blaster...
D/serial_port( 6592): Configuring serial port
E/UEI.SmartControl( 6592): UEIBLaster setting for 616
I/UEI.SmartControl( 6592): Setting serial record hearder size = 2
I/UEI.SmartControl( 6592): configuring settings for MAXQ616
I/UEI.SmartControl( 6592): Get version...
I/MusicWidget( 2685): mDelayedStopHandler : unbind
,D/UEI.SmartControl( 6592): serial port data available: 21
I/MusicBrowser( 2212): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2212): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2212): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2212): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2212): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2212): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1037):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@8d88ee1com.lge.music.MediaPlaybackService$5@22c39406
,D/MusicBrowser( 2212): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3866c6c4
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2212): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,D/UEI.SmartControl( 6592): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6592): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6592): QS saving settings...
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 6592): IR Blaster version: 25672567
I/MusicBrowser( 2212): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2212): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2212): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2212): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2212): reset
,V/MediaPlayer[Native]( 2212): setListener
V/MediaPlayer[Native]( 2212): disconnect
V/MediaPlayer[Native]( 2212): destructor
V/AudioFlinger(  312): releasing 13 from 2212 for -1
V/AudioFlinger(  312):  decremented refcount to 0
V/AudioFlinger(  312): purging stale effects
V/MediaPlayer[Native]( 2212): disconnect
D/MusicBrowser( 2212): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
D/UEI.SmartControl( 6592): serial port data available: 4
I/SmartShareClient( 2212): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2212): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2212): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2212): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2212): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2212): [SmartShareManagerClient] unregisterListener: 654576327
,W/SmartShareClient( 2212): [SmartShareManagerClient] unregisterListener invalid listener: 654576327
,I/SmartShareClient( 2212): [SmartShareManagerClient] terminate service: 2212/MediaPlaybackService/446541450
,E/HomeCloudIF( 2212): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2212): [SmartShareManagerClient] unbindService context:android.app.Application@34eb68f4
V/CloudHub( 2212): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2212): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2212): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2212): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
W/ContextImpl( 6592): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/CloudHub( 2212): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/UEI.SmartControl( 6592): Device manager: loading config....
D/UEI.SmartControl( 6592): ----------- loading internal config...
E/UEI.SmartControl( 6592): Loading SETTINGS...
E/UEI.SmartControl( 6592): Services init done
D/UEI.SmartControl( 6592): QS Service init finished
,D/UEI.SmartControl( 6592): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6592): QS Service version name: 2.1.91
D/UEI.SmartControl( 6592): QS Service version code: 201091
D/UEI.SmartControl( 6592): Service requested: Control
I/QRemote ( 6884): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6592): Internal service binding...
I/UEI.SmartControl( 6592): ------ IControl API: 11
D/UEI.SmartControl( 6592): File observer start...
E/UEI.SmartControl( 6592): IR Port is disabled: false
D/UEI.SmartControl( 6592): Starting file observer...
I/UEI.SmartControl( 6592): Registering callback...
I/UEI.SmartControl( 6592): ------ IControl API: 19
,I/UEI.SmartControl( 6592): Registering Services Ready callback...
I/UEI.SmartControl( 6592): Notify client services are ready...
I/QRemote ( 6884): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6884): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6884): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6884): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6884): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6592): ------ IControl API: 8
D/QRemote ( 6884): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6884): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6884): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6884): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6884): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6884): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6884): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6884): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6884): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 6884): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
I/UEI.SmartControl( 6592): Notify AllClients services are ready: 0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
I/QRemote ( 6884): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6884): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6884): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6592): -----service ready thread exits
D/QRemote ( 6884): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454948696581]
D/QRemote ( 6884): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
D/QRemote ( 6884): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
I/ActivityManager( 1037): Killing 6440:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 6884): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1037): Killing 6076:com.android.contacts/u0a19 (adj 15): empty #18
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6440/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6076/cgroup.procs: No such file or directory
V/QRemote ( 6884): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6884): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6884): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3c435c30 type 2 when 108024 com.google.android.gms} when 108024
,W/ContextImpl( 4544): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2668): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108276  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108280  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 2668): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108384  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108386  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6822): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108388
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108389
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108390
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108392
I/wpa_supplicant( 2668): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108395
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108396  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108399  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6822): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6822): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6822): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6822): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108402  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108402  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108403
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108406
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  308): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108465  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108465  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1037): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108468  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108470  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108471  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11826982 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11826982 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  308): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabi,lities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/DSQN    ( 1037): enableDataServiceNotify 
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/DSQN    ( 1037): start dsqn bin
,D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6950): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6950): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
E/DSQN    ( 6950): DSQN ssw
,D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6884): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6884): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6884): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6884): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6858): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6858): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6822): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6822): MCCMNC not supported: null
D/QRemote ( 6884): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6884): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6884): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6884): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6884): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
,D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6956): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6956): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6956): version 5.5.6 starting
E/dhcpcd  ( 6956): get_duid: m
D/dhcpcd  ( 6956): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6956): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6956): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6956): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6956): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6956): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6956): wlan0: sending REQUEST (xid 0x2e1f05fc), next in 4.54 seconds
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:24:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454948697757], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454948697644]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5424): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 5424): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6977 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 6977): onCreate
W/AppUp4:DB( 6977):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6977):  setFingerPrint start
I/AppUp4:DB( 6977):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6977):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6977):  SDK version = 21
I/AppUp4:DB( 6977):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6977): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6977): onReceive
,D/LgDataFeature( 6977): LgDataFeature() Constructor: none
D/LgDataFeature( 6977): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6977): Context : android.app.ReceiverRestrictedContext@20dbb118,
D/AppUp4:CustFacade( 6977): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6977): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6977): begin check event
I/AppUp4:CustModeStarterReceiver( 6977): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6977): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6977): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6977): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6977): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6098:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6098/cgroup.procs: No such file or directory
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3370): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3370): DownloadService onCreate
D/LGDMClient( 4308): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/DownloadManager( 3370): in removeSpuriousFiles
I/LGDMClient( 4308): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@37ce06bc on behalf of 3370
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3370): in trimDatabase
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@2261f19a on behalf of 3370
,I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7011 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3370): DownloadService onStartCommand
V/DownloadManager( 3370): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4308): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4308): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4308): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@30d2d2a8 on behalf of 3370
V/DownloadManager( 3370): processing inserted download 1
V/DownloadManager( 3370): processing inserted download 4
V/DownloadManager( 3370): processing inserted download 7
V/DownloadManager( 3370): processing inserted download 8
V/DownloadManager( 3370): processing inserted download 9
V/DownloadManager( 3370): processing inserted download 10
V/DownloadManager( 3370): processing inserted download 16
V/DownloadManager( 3370): processing inserted download 17
V/DownloadManager( 3370): processing inserted download 18
V/DownloadManager( 3370): processing inserted download 21
V/DownloadManager( 3370): processing inserted download 22
V/DownloadManager( 3370): DownloadService onDestroy
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{7a8d8b7 type 2 when 109749 com.google.android.gms} when 109749
W/ResourcesManager( 7011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7011): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7011): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7011): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7011): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7011): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7011): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7011): LgDataFeature() Constructor: none
D/LgDataFeature( 7011): LgDataFeature() Constructor Done, null
,D/eas_req ( 7011): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7041 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7011): JNI_OnLoad()
I/HubEmail( 7011): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7011): registerNatives()
I/HubEmail( 7011): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7011): registerNativeMethods()
I/HubEmail( 7011): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7011): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6119:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6119/cgroup.procs: No such file or directory
W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = false
I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7065 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 6956): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
I/dhcpcd  ( 6956): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6956): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6956): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6956): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6956): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6956): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6956): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6956): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/FormManager( 7041): There are no updated forms. The schedule will be deleted.
V/FormManager( 7041): Alarm would be updated, because LastCheckTime has been updated.
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6734): 
I/ActivityManager( 1037): Killing 6475:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/art     ( 1037): Explicit concurrent mark sweep GC freed 83703(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.720ms total 117.414ms
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6475/cgroup.procs: No such file or directory
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7112 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6137:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6137/cgroup.procs: No such file or directory
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1b1ddfc0 type 0 when 1454948699760 com.android.vending} when 1454948699760
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7129 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 7129): Almond Protected OAT
,D/WeatherApplication( 7129): removeAccount
D/WeatherApplication( 7129): Account.length = 0
E/WeatherApplication( 7129): OPERATOR:OPEN
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherAncestor( 7129): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:0
D/Weather.Utils( 7129): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7129): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7129): 2 : This is isUpdating : false
,D/WeatherAncestor( 7129): connectivity changed - connection : true
D/WeatherService( 7129): 2 : isServiceAlived():false forecastCache:null
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
D/ForecastDataCache( 7129): 2 : lastUpdatedTime: 1430558561343
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/ForecastDataCache( 7129): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7129): 2 : Cache is not up-to-date, count: 0
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/Finsky  ( 6159): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6159): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6159): [1] 5.onFinished: Scheduling replication attempt 2.
,D/Weather_cast( 7129): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7129): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:0
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6734): 
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7147 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6524:com.lge.eula/1000 (adj 15): empty #17
I/art     (  339): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 210us total 10.322ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 200us total 9.479ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.056ms
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6734): 
I/ActivityManager( 1037): Killing 5984:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6734): 
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6734): 
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6524/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_5984/cgroup.procs: No such file or directory
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7147): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7147): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7147): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7147): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5424): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7147): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7147): Loading: webviewchromium
I/LibraryLoader( 7147): Time to load native libraries: 4 ms (timestamps 1712-1716)
I/LibraryLoader( 7147): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7147): Binding Chromium to main looper Looper (main, tid 1) {31ac8c63}
I/LibraryLoader( 7147): Expected native library version number "",actual native library version number ""
I/chromium( 7147): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7147): Initializing chromium process, renderers=0
W/art     ( 7147): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7147): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7147): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7147): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  312): registerClient() client 0xb14fd100, uid 10093
W/AudioManagerAndroid( 7147): Requires BLUETOOTH permission
I/Adreno-EGL( 7147): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7147): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7147): Build Date: 12/12/14 금
I/Adreno-EGL( 7147): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7147): Remote Branch: 
I/Adreno-EGL( 7147): Local Patches: 
I/Adreno-EGL( 7147): Reconstruct Branch: 
,I/NSApplication( 7147): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7205 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6563:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,W/ResourcesManager( 7205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6977): onReceive
D/AppUp4:CustFacade( 6977): Context : android.app.ReceiverRestrictedContext@20dbb118
D/AppUp4:CustFacade( 6977): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6977): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 6977): begin check event
I/AppUp4:CustModeStarterReceiver( 6977): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSActivity( 2141): [ac] getting account id
V/DownloadManager( 3370): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4308): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3370): DownloadService onCreate
I/GLSUser ( 2141): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3370): in removeSpuriousFiles
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4308): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3370): DownloadService onStartCommand
,D/LGDMClient( 4308): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4308): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3370): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@ad67154 on behalf of 3370
V/DownloadManager( 3370): processing inserted download 1
V/DownloadManager( 3370): processing inserted download 4
V/DownloadManager( 3370): processing inserted download 7
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@2ece08fd on behalf of 3370
V/DownloadManager( 3370): processing inserted download 8
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
V/DownloadManager( 3370): processing inserted download 9
,I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3370): processing inserted download 10
V/DownloadManager( 3370): processing inserted download 16
V/DownloadManager( 3370): processing inserted download 17
V/DownloadManager( 3370): processing inserted download 18
V/DownloadManager( 3370): processing inserted download 21
V/DownloadManager( 3370): processing inserted download 22
I/DownloadManager( 3370): in trimDatabase
I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = false
,W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@252519f2 on behalf of 3370
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7129): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:1
,D/Weather.Utils( 7129): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7129): 2 : All the weather widget is gone.
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/UpdateThreadPoolManager( 7129): 2 : This is isUpdating : false
D/WeatherAncestor( 7129): connectivity changed - connection : true
D/WeatherService( 7129): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37b02956
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
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/ForecastDataCache( 7129): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7129): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7129): 2 : Cache is up-to-date, count: 0
V/DownloadManager( 3370): DownloadService onDestroy
D/Weather_cast( 7129): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7129): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:1
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6373): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6977): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6977): onReceive
D/AppUp4:CustFacade( 6977): Context : android.app.ReceiverRestrictedContext@20dbb118
D/AppUp4:CustFacade( 6977): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6977): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6977): begin check event
I/AppUp4:CustModeStarterReceiver( 6977): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7041): There are no updated forms. The schedule will be deleted.
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4308): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3370): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
I/LGDMClient( 4308): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3370): DownloadService onCreate
D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4308): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7041): Alarm would be updated, because LastCheckTime has been updated.
W/ContextImpl( 4308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/DownloadManager( 3370): in removeSpuriousFiles
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4308): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4308): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4308): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3370): DownloadService onStartCommand
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
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/UEI.SmartControl( 6592): Internal timer expired: 2
D/UEI.SmartControl( 6592): unbind internal service
V/DownloadManager( 3370): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = true
D/PhoneState( 3303): setPdpRejectCasuse : false
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@d66e33e on behalf of 3370
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3370): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@dffd59f on behalf of 3370
V/DownloadManager( 3370): processing inserted download 1
V/DownloadManager( 3370): processing inserted download 4
V/DownloadManager( 3370): processing inserted download 7
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/DownloadManager( 3370): in trimDatabase
V/DownloadManager( 3370): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WeatherAncestor( 7129): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:1
W/Settings( 7011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Weather.Utils( 7129): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7129): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7129): 2 : This is isUpdating : false
D/WeatherAncestor( 7129): connectivity changed - connection : true
D/WeatherService( 7129): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37b02956
D/ForecastDataCache( 7129): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7129): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7129): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7129): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7129): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:25:1
V/DownloadManager( 3370): created cursor android.database.sqlite.SQLiteCursor@fe96ec on behalf of 3370
V/DownloadManager( 3370): processing inserted download 8
V/DownloadManager( 3370): processing inserted download 9
V/DownloadManager( 3370): processing inserted download 10
V/DownloadManager( 3370): processing inserted download 16
V/DownloadManager( 3370): processing inserted download 17
D/serial_port( 6592): close(fd = 24)
V/DownloadManager( 3370): processing inserted download 18
V/DownloadManager( 3370): processing inserted download 21
V/DownloadManager( 3370): processing inserted download 22
V/DownloadManager( 3370): DownloadService onDestroy
I/UEI.SmartControl( 6592): Serial port is closed.
D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/QRemote ( 6884): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6884): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2341
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/FormManager( 7041): There are no updated forms. The schedule will be deleted.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
W/Kids    ( 2372): [AccountUtils] Account not ready
W/Kids    ( 2372): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2372): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2372): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2372): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2372): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2372): 	at java.lang.Thread.run(Thread.java:818)
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
V/FormManager( 7041): Alarm would be updated, because LastCheckTime has been updated.
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  308): res_queryN name = www.google.com succeed
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/GCM     ( 2141): Connected
,D/GCM     ( 2141): Message class com.google.f.a.a.p
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/GAV4    ( 7147): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6734): Test app app.js loaded
I/jxcore-log( 6734): 
,I/chromium( 6734): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235dcc90 added. We now have 1 listener(s)
,I/jxcore-log( 6734): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6734): 
I/ActivityManager( 1037): Killing 6018:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10014/pid_6018/cgroup.procs: No such file or directory
,I/CloudHub( 2212): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19997
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 118142747303; DSPS: 4012133; Offset : -4314209864
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{9b090e3 type 0 when 1454948720044 com.android.vending} when 1454948720044
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1ee50ae0 type 2 when 131252 android} when 131252
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1037): Explicit concurrent mark sweep GC freed 36795(1692KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 1.612ms total 82.649ms
,D/Finsky  ( 6159): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6159): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6159): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2212): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2212): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 138150403494; DSPS: 4667744; Offset : -4314213820,
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 158152141767; DSPS: 5323161; Offset : -4314214919
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{285778d3 type 0 when 1454948745671 com.android.vending} when 1454948745671
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6159): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6159): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6159): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3f46997d type 2 when 169238 android} when 169238
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6652): Error response from books API: {,
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198831803195665723&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
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
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198831803195665723&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198831803195665723&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198831803195665723&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=198831803195665723&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-v,ersion: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169238, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 178154777488; DSPS: 5978608; Offset : -4314234279
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1980): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1980): Battery Level Remaining: 100%
D/LEDHandler( 1980): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3777): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{ea0871e type 0 when 1454948777017 com.android.vending} when 1454948777017
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6159): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6159): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6159): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 198156465710; DSPS: 6634023; Offset : -4314224577
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{344928d0 type 2 when 199280 android} when 199280
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 218158140337; DSPS: 7289438; Offset : -4314228286
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2e75f0c9 type 2 when 186423 com.google.android.gms} when 186423
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3c0af3ce type 2 when 208835 android} when 208835
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{2f6001fc type 0 when 1454948806333 com.android.vending} when 1454948806333
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3163d085 type 2 when 229306 android} when 229306
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2141): Vacuum at: now=1454948818832 tag=VacuumService
I/GoogleURLConnFactory( 2141): Using platform SSLCertificateSocketFactory
,W/Uploader( 2141): No account for auth token provided
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
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
,E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4992713200448763224&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6159): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6159): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6159): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141): No account for auth token provided
,W/Uploader( 2141):  no longer exists, so no auth token.
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4992713200448763224&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 27510(1180KB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 3.426ms total 168.847ms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2141): Explicit concurrent mark sweep GC freed 55556(3MB) AllocSpace objects, 23(3MB) LOS objects, 51% free, 30MB/62MB, paused 1.541ms total 44.750ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1420): onNotificationPosted
D/SmartCoverUpdateMonitor( 1420): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1420): MSG_NOTIFICATION_POSTED
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
,D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4992713200448763224&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4992713200448763224&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4992713200448763224&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 204290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 238159960538; DSPS: 7944857; Offset : -4314208518
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 258161675219; DSPS: 8600274; Offset : -4314233469
,I/jxcore-log( 6734): TAP version 13
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # multiplex can send data
I/jxcore-log( 6734): 
I/jxcore-log( 6734): got: setup_multiplex can send data
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_multiplex can send data_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 1 String should be length:200
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1abda853 type 2 when 259860 android} when 259860
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/jxcore-log( 6734): # enqueue and run in order
I/jxcore-log( 6734): 
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,I/jxcore-log( 6734): got: setup_enqueue and run in order
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_enqueue and run in order_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 2 firstPromise setTimeout
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 3 firstPromise result
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 4 firstPromise testValue
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 5 secondPromise setTimeout
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 6 secondPromise result
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 7 secondPromise testValue
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 8 thirdPromise in promise
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 9 thirdPromise result
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 10 thirdPromise testValue
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # basic
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_basic
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ack: setup_basic_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 11 sane
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # another
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_another
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_another_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 12 sane
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_successfully create a new pkcs12 file and return hash value_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 13 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 14 null
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 15 (unnamed assert)
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 16 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 17 should not throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_successfully read a previous pkcs12 file and return hash value_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 18 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 19 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 20 should not throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 21 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 22 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_failed to extract public key because of corrupt pkcs12 file_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 23 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # failed to get mobile documents path
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_failed to get mobile documents path
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_failed to get mobile documents path_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 24 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#init should register the peerAvailabilityChanged event
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#init should register the peerAvailabilityChanged event_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 25 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 26 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 27 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #init should register the networkChanged event
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#init should register the networkChanged event
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#init should register the networkChanged event_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 28 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on null device name
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on null device name
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on null device name_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 29 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on empty string device name
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on empty string device name_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 30 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on non-number port
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on non-number port_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 31 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on NaN port
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on NaN port_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 32 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on negative port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on negative port
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on negative port_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 33 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #startBroadcasting should throw on too large port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should throw on too large port
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should throw on too large port_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 34 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 35 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 36 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 37 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 38 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 39 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 40 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 41 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 42 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 43 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 44 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 45 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 46 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 47 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_#connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ack: setup_#connect should call Mobile("Connect") and handle an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 48 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 49 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_should call Mobile("Disconnect") without an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_should call Mobile("Disconnect") without an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 50 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 51 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ack: setup_should call Mobile("Disconnect") and handle an error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 52 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 53 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aa42989 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852158.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852158.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852158.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3777): [BTUI] createSocketChannel FD=84 mFd=82
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852158.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852158.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852158.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cffb4ade target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cffb4ade target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323135382e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323135382e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323135381f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323135381f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852158.6734, mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/jxcore-log( 6734): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323135381f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323135381f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@331cd545 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported:, false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852279.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852279.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852279.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852279.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852279.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852279.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d0eef1d6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d0eef1d6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323237392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323237392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323237391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323237391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852279.6734, mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p,2p0( 1037): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/jxcore-log( 6734): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323237391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323237391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
,D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eba80c1 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852355.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852355.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852355.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852355.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852355.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852355.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eb8963a0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eb8963a0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323335352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323335352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323335351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323335351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852355.6734, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c,01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323335351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323335351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@292d67fd added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852413.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852413.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852413.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852413.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852413.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852413.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f9fe846a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f9fe846a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323431332e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323431332e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323431331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323431331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService( 1037): discovery change broadcast true
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852413.6734, mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6734): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P,2P device discovery...
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323431331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323431331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
I/jxcore-log( 6734): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): add,Listener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eed86f9 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852481.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852481.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852481.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852481.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852481.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852481.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4fde8e20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4fde8e20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323438312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323438312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323438311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852481.6734, mode: WIFI
I/jxcore-log( 6734): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323438311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323438311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323438311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/jxcore-log( 6734): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f699b5 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852542.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852542.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852542.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852542.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852542.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852542.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8588aa4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8588aa4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323534322e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323534322e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323534321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323534321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852542.6734, mode: WIFI
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/jxcore-log( 6734): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting t,hread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323534321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
,D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323534321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
I/jxcore-log( 6734): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.Discove,ryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e441c31 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852619.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852619.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852619.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852619.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852619.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852619.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e39b305a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e39b305a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323631392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323631392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323631391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323631391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852619.6734, mode: WIFI
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant( 2668): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/jxcore-log( 6734): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323631391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323631391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
,I/jxcore-log( 6734): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a0d4a6d added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852689.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852689.6734","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852689.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852689.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852689.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852689.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4ad3cc8c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4ad3cc8c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323638392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323638392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323638391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323638391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852689.6734, mode: WIFI
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 6734): start: OK
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323638391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323638391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
I/jxcore-log( 6734): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.andr,oid.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc12069 added. We now have 10 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852755.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852755.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
,I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852755.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852755.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852755.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852755.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@56af4c98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@56af4c98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323735352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323735352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323735351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323735351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852755.6734, mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
,I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/jxcore-log( 6734): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.,ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc25a25 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323735351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323735351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wif,i.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852826.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852826.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852826.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454948852826.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454948852826.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454948852826.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@de83ada target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@de83ada target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323832362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343934383835323832362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323832361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323832361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454948852826.6734, mode: WIFI
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2668): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/jxcore-log( 6734): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/wpa_supplicant( 2668): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323832361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343934383835323832361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1037): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Cannot start, because not initialized
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 278163591408; DSPS: 9255696; Offset : -4314209370
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1f65bfdc type 2 when 295991 android} when 295991
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2842078246871151984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2842078246871151984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 298165016660; DSPS: 9911103; Offset : -4314218393
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
,D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2842078246871151984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2842078246871151984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2842078246871151984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 295991, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 318166888685; DSPS: 10566524; Offset : -4314207965
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{8a736e6 type 2 when 326156 android} when 326156
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 338168478521; DSPS: 11221937; Offset : -4314235587
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 358169698461; DSPS: 11877337; Offset : -4314236533
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6159): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6159): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6159): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6159): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6159): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6159): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6159): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6159): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 378172182256; DSPS: 12532778; Offset : -4314224583,
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 398175342769; DSPS: 13188242; Offset : -4314237716
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7503 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7503): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7503): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@29a030f5
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
I/ActivityManager( 1037): Killing 2212:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  312): 2212 died, releasing its sessions
V/AudioFlinger(  312):  pid 1873 @ 0
V/AudioFlinger(  312):  pid 3303 @ 1
V/AudioFlinger(  312):  pid 3303 @ 2
,W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2212/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 418177309793; DSPS: 13843666; Offset : -4314223791
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{25f2c358 type 2 when 424282 android} when 424282
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=423256172781251239&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 31908(1681KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 2.881ms total 170.311ms
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 1,0|com.google.android.gms|1|null|10005,
D/LgeQuickCoverNotificationData( 1420): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1420): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): ,	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=423256172781251239&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=423256172781251239&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=423256172781251239&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=423256172781251239&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 424282, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 438178752753; DSPS: 14499073; Offset : -4314215261
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{22f2bc82 type 2 when 454328 android} when 454328
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 458180681652; DSPS: 15154496; Offset : -4314208918
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
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 478182374301; DSPS: 15809912; Offset : -4314225331
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 498184071377; DSPS: 16465328; Offset : -4314237265
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 518185669494; DSPS: 17120740; Offset : -4314225932
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 538187124278; DSPS: 17776147; Offset : -4314205500
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 558188875260; DSPS: 18431565; Offset : -4314224512
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 578191091815; DSPS: 19086998; Offset : -4314235818
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
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 598192741859; DSPS: 19742412; Offset : -4314233671
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 618194388414; DSPS: 20397826; Offset : -4314235014
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 638196106688; DSPS: 21053242; Offset : -4314225802
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,I/ActivityManager( 1037): Killing 6858:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 658198391732; DSPS: 21708677; Offset : -4314229342
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{25560f93 type 2 when 677421 android} when 677421
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8501864108632899728&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 678200886361; DSPS: 22364119; Offset : -4314237520
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8501864108632899728&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8501864108632899728&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8501864108632899728&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): ,	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8501864108632899728&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 677421, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 698202603644; DSPS: 23019535; Offset : -4314228985
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2c76dc65 type 2 when 707519 android} when 707519
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
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 718204487543; DSPS: 23674957; Offset : -4314237255
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 738206381962; DSPS: 24330379; Offset : -4314234978
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 758207954923; DSPS: 24985790; Offset : -4314218309
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 778209743873; DSPS: 25641209; Offset : -4314229870
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 798211855794; DSPS: 26296638; Offset : -4314223740
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 818213482817; DSPS: 26952051; Offset : -4314214201
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 838215137392; DSPS: 27607465; Offset : -4314207549
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
D/LEDHandler( 1980): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1980): Battery Level Remaining: 100%
D/LEDHandler( 1980): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3777): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 858216904364; DSPS: 28262883; Offset : -4314210701
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 878218608627; DSPS: 28918299; Offset : -4314215162
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 898220355443; DSPS: 29573716; Offset : -4314207978
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 918222259758; DSPS: 30229139; Offset : -4314226218
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 938223630844; DSPS: 30884544; Offset : -4314228294
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/LEDHandler( 1980): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1980): Battery Level Remaining: 100%
D/LEDHandler( 1980): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 3777): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4308): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037,
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{e0cd3a type 2 when 943202 com.android.bluetooth} when 943202
,W/bt-smp  ( 3777): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3777): Plain text(LSB ~ MSB) = 14 45 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3777): Encrypted text(LSB ~ MSB) = e0 ad 4a a5 25 30 ea 16 7c 5f 50 53 10 0c 79 50 
W/bt-btm  ( 3777): Stopping oneshot timer
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{131b3deb type 2 when 950092 android} when 950092
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 958225463233; DSPS: 31539964; Offset : -4314226959
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 978227021714; DSPS: 32195375; Offset : -4314224927
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 998228816342; DSPS: 32850794; Offset : -4314230992
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
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1018231058314; DSPS: 33506227; Offset : -4314216752
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1038232679452; DSPS: 34161640; Offset : -4314212967
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1058234239184; DSPS: 34817052; Offset : -4314240358
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
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1078236114228; DSPS: 35472473; Offset : -4314226833
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1098237916408; DSPS: 36127892; Offset : -4314225087
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1118239544577; DSPS: 36783305; Offset : -4314214192
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
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1138241982851; DSPS: 37438745; Offset : -4314217533
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1158243533781; DSPS: 38094156; Offset : -4314222869
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1178245150492; DSPS: 38749569; Offset : -4314223668
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3e392748 type 2 when 1179186 android} when 1179186
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{11fdd9e1 type 2 when 1012867 com.google.android.gms} when 1012867
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{267e8306 type 0 when 1454949747860 com.google.android.gms} when 1454949747860
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/GCM     ( 2141): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,I/EventLogService( 2372): Aggregate from 1454947947796 (log), 1454947947796 (data)
,I/BooksSync( 6652): Starting books sync
,D/BooksSync( 6652): started syncMyEbooks
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
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
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1079075734468850252&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1198247040224; DSPS: 39404991; Offset : -4314226182
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1420): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1420): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1420): updateNotificationData: count=3
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
,D/QuickStatusbarLayout( 1420): Notification difference=198
,D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1079075734468850252&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2141): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2141): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2141): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2141): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2141): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 31159(1419KB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 3.451ms total 150.663ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2141): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2141): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2141): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2141): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2141): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6652): Authentication error
E/BooksAccountManager( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6652): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6652): null auth token
D/QuickStatusbarLayout( 1420): Notification difference=198
D/QuickStatusbarLayout( 1420): child = android.widget.LinearLayout{30d34ec0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6652): Error response from books API: {
W/ApiaryClient( 6652):  "error": {
W/ApiaryClient( 6652):   "errors": [
W/ApiaryClient( 6652):    {
W/ApiaryClient( 6652):     "domain": "global",
W/ApiaryClient( 6652):     "reason": "required",
W/ApiaryClient( 6652):     "message": "Login Required",
W/ApiaryClient( 6652):     "locationType": "header",
W/ApiaryClient( 6652):     "location": "Authorization"
W/ApiaryClient( 6652):    }
W/ApiaryClient( 6652):   ],
W/ApiaryClient( 6652):   "code": 401,
W/ApiaryClient( 6652):   "message": "Login Required"
W/ApiaryClient( 6652):  }
W/ApiaryClient( 6652): }
,W/ApiaryClient( 6652): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1079075734468850252&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6652): Headers:
W/ApiaryClient( 6652): accept-encoding: [gzip]
W/ApiaryClient( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6652): gdata-version: 2
,E/BooksSync( 6652): Soft error: 
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1079075734468850252&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
,E/BooksSync( 6652): Sync error
E/BooksSync( 6652): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6652): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1079075734468850252&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6652): Headers:
E/BooksSync( 6652): accept-encoding: [gzip]
E/BooksSync( 6652): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6652): gdata-version: 2
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6652): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6652): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6652): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6652): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6652): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6652): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6652): {
E/BooksSync( 6652):  "error": {
E/BooksSync( 6652):   "errors": [
E/BooksSync( 6652):    {
E/BooksSync( 6652):     "domain": "global",
E/BooksSync( 6652):     "reason": "required",
E/BooksSync( 6652):     "message": "Login Required",
E/BooksSync( 6652):     "locationType": "header",
E/BooksSync( 6652):     "location": "Authorization"
E/BooksSync( 6652):    }
E/BooksSync( 6652):   ],
E/BooksSync( 6652):   "code": 401,
E/BooksSync( 6652):   "message": "Login Required"
E/BooksSync( 6652):  }
E/BooksSync( 6652): }
E/BooksSync( 6652): 
E/BooksSync( 6652): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6652): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6652): 	... 8 more
I/BooksSync( 6652): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1179186, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1218248868810; DSPS: 40060411; Offset : -4314228651
,I/UsageStatsService( 1037): User[0] Flushing usage stats to disk
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{ae735b5 type 2 when 1227234 android} when 1227234
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1238250600209; DSPS: 40715827; Offset : -4314206002
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1258252374420; DSPS: 41371246; Offset : -4314232459
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1278254058006; DSPS: 42026661; Offset : -4314227209
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1298255679613; DSPS: 42682074; Offset : -4314223190
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=697341856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7503): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7503): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@29a030f5
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=697341856 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1318257468459; DSPS: 43337493; Offset : -4314234777
,TIME-OUT KILL (timeout was 1200000ms)
```
