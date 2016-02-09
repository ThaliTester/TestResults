#### Test 58751238ee11130_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/[Concierge]Service( 2622): onStartCommand(). Type : 9
--------- beginning of system
D/PowerManagerServiceEx( 1049): releaseWakeLockInternal: lock=169080146 [*alarm*], flags=0x0
,I/ActivityManager( 1049): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6714 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ReaderUtils( 6714): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/AndroidRuntime( 6712): 
D/AndroidRuntime( 6712): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6712): CheckJNI is OFF
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2119): innerSync failed
D/ContactsSyncAdapter( 2119): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2119): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2119): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2119): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2119): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2119): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2119): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2119): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2119): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2119): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2119): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1049): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 88106, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
W/GAV2    ( 6714): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/SyncManager( 1049): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 162190, reason: 10019
I/BooksApp( 6714): Created application version: 3.2.35 (30235)
D/AndroidRuntime( 6712): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1049): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1959): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1049): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1049): setTaskToReturnTo : TaskRecord{8641381 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1049): setTaskToReturnTo : TaskRecord{8641381 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1049): AppWindowTokenEx init.. 
E/GBMv2   (  331): DFP En is all cleared set to be enabled
I/ActivityManager( 1049): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6754 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6712): Shutting down VM
I/BooksSync( 6714): Starting books sync
V/ActivityManager( 1049): Display changed displayId=0
D/DSDPConnection( 1862): Display #0 changed.
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{263aa1bf co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{3cf9408c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6754): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/BooksSync( 6714): started syncMyEbooks
,I/WebViewFactory( 6754): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6754): Loading: webviewchromium
I/LibraryLoader( 6754): Time to load native libraries: 4 ms (timestamps 2511-2515)
I/LibraryLoader( 6754): Expected native library version number "",actual native library version number ""
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
V/WebViewChromiumFactoryProvider( 6754): Binding Chromium to main looper Looper (main, tid 1) {ea7d12f}
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LibraryLoader( 6754): Expected native library version number "",actual native library version number ""
I/chromium( 6754): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 6754): Initializing chromium process, renderers=0
W/art     ( 6754): Attempt to remove local handle scope entry from IRT, ignoring
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/AudioPolicyService(  314): registerClient() client 0xb152de80, uid 10311
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
W/chromium( 6754): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/BluetoothManagerService( 1049): Message: 20
D/BluetoothManagerService( 1049): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@140ac444:true
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
I/chromium( 6754): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6754): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
I/Adreno-EGL( 6754): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6754): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6754): Build Date: 12/12/14 금
I/Adreno-EGL( 6754): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6754): Remote Branch: 
I/Adreno-EGL( 6754): Local Patches: 
I/Adreno-EGL( 6754): Reconstruct Branch: 
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/chromium( 6754): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6754): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6754): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6754): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6754): CordovaWebView is running on device made by: LGE
W/art     ( 6754): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6754): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6754): Render dirty regions requested: true
I/OpenGLRenderer( 6754): Initialized EGL, version 1.4
D/OpenGLRenderer( 6754): Enabling debug mode 0
D/Atlas   ( 6754): Validating map...
D/SplitWindow( 1049): check instance of lgWin Window{32028f5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6754): LgDataFeature() Constructor: none
D/LgDataFeature( 6754): LgDataFeature() Constructor Done, null
W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
I/SystemUI[Framework]( 1049): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1049): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1049): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1049): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1049): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33e2ff37,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1049): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ApiaryClient( 6714): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
I/ActivityManager( 1049): Displayed com.test.thalitest/.MainActivity: +548ms (total +649ms)
I/Timeline( 6754): Timeline: Activity_idle id: android.os.BinderProxy@1035641f time:102893
I/Timeline( 1049): Timeline: Activity_windows_visible id: ActivityRecord{2753cc26 u0 com.test.thalitest/.MainActivity t4} time:102897
D/JsMessageQueue( 6754): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6754): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6754): 
D/jxcore_app_log( 6754): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435094784
I/chromium( 6754): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6754): 
I/chromium( 6754): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  331): DFP En is all cleared set to be enabled
E/GBMv2   (  331): Set value is all cleared set the max
I/GBMv2   (  331): DFP Enabled. Ignore VFP set
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
W/ApiaryClient( 6714): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
W/jxcore-log( 6754): Initializing JXcore engine
W/jxcore-log( 6754): JXcore engine is ready
W/Thread-799( 6821): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8460]" dev="sockfs" ino=8460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6821): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-799( 6821): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10364]" dev="sockfs" ino=10364 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6821): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-799( 6821): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30702]" dev="sockfs" ino=30702 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6754): Starting JXcore engine
W/jxcore-log( 6754): Platform android
W/jxcore-log( 6754): 
W/jxcore-log( 6754): Process ARCH arm
W/jxcore-log( 6754): 
,I/jxcore-log( 6754): JXcore Cordova bridge is ready!
I/jxcore-log( 6754): 
W/jxcore-log( 6754): JXcore engine is started
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2119): Explicit concurrent mark sweep GC freed 23382(1378KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.224ms total 64.805ms
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 6754): Toggling radios to true
I/jxcore-log( 6754): 
,D/BluetoothAdapter( 6754): enable(): BT is already enabled..!
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WifiService( 1049): New client listening to asynchronous messages
V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/WifiServiceImplEx( 1049): setWifiEnabled: true pid=6754, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1049): setWifiEnabled: true pid=6754, uid=10311
E/WifiService( 1049): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1049): disconnect pid=6754, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1049):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1049):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1049): reconnect pid=6754, uid=10311, packageName=com.test.thalitest
E/WifiNative: ( 1049): [105,151,712 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1049): doBoolean: DISCONNECT
I/jxcore-log( 6754): Radios toggled
I/jxcore-log( 6754): 
I/jxcore-log( 6754): My device name is: LGE-LG-D855
I/jxcore-log( 6754): 
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6714): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/wpa_supplicant( 2651): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1049): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1049): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering( 1049): InitialState.processMessage what=4
D/Tethering( 1049): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1049): DISCONNECT: returned true
E/WifiStateMachine( 1049): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1049): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1049): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1049): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1049): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1049): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1049): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1049): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1049): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1049): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1049): doBoolean: SET ps 1
D/WifiNative-wlan0( 1049): SET ps 1: returned true
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1049): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1049): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2119): Read error: ssl=0xaa6f7000: I/O error during system call, Connection timed out
V/NativeCrypto( 2119): SSL shutdown failed: ssl=0xaa6f7000: I/O error during system call, Broken pipe
D/ConnectivityService( 1049): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1049): Dns fail occured do internet check.
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1049): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1049): ignoring duplicate network state non-change
D/ConnectivityService( 1049): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1049): hidePasspointNotification off =false
D/DSQN    ( 1049): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1049): try Internet connection check
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1049): Start Disconnecting Watchdog 1
D/WifiHS20( 1049): hidePasspointNotification off =false
E/WifiStateMachine( 1049):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1049): [105,258,140 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1049): doBoolean: RECONNECT
D/WifiNative-wlan0( 1049): RECONNECT: returned true
E/WifiStateMachine( 1049):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105259
I/wpa_supplicant( 2651): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1049):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105259
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1049): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1049): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1049): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1049): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1049): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1049): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1049): doBoolean: SET ps 1
D/WifiNative-wlan0( 1049): SET ps 1: returned true
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/ApiaryClient( 6714): errCount = 3: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: javax.net.ssl.SSLException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/BooksSync( 6714): Soft error: 
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:87)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:158)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: javax.net.ssl.SSLException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapException(HttpHelper.java:168)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:237)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	... 7 more
E/BooksSync( 6714): Caused by: javax.net.ssl.SSLException: Read error: ssl=0xaf456e00: I/O error during system call, Connection timed out
E/BooksSync( 6714): 	at com.android.org.conscrypt.NativeCrypto.SSL_read(Native Method)
E/BooksSync( 6714): 	at com.android.org.conscrypt.OpenSSLSocketImpl$SSLInputStream.read(OpenSSLSocketImpl.java:674)
E/BooksSync( 6714): 	at com.android.okio.Okio$2.read(Okio.java:113)
E/BooksSync( 6714): 	at com.android.okio.RealBufferedSource.indexOf(RealBufferedSource.java:147)
E/BooksSync( 6714): 	at com.android.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:94)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:175)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:101)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:616)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:379)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:491)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
E/BooksSync( 6714): 	at com.,google.api.client.http.javanet.NetHttpResponse.<init>(NetHttpResponse.java:36)
E/BooksSync( 6714): 	at com.google.api.client.http.javanet.NetHttpRequest.execute(NetHttpRequest.java:94)
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:965)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
E/BooksSync( 6714): Sync error
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:87)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:158)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: javax.net.ssl.SSLException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6255053553845764248&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapException(HttpHelper.java:168)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:237)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	... 7 more
E/BooksSync( 6714): Caused by: javax.net.ssl.SSLException: Read error: ssl=0xaf456e00: I/O error during system call, Connection timed out
E/BooksSync( 6714): 	at com.android.org.conscrypt.NativeCrypto.SSL_read(Native Method)
E/BooksSync( 6714): 	at com.android.org.conscrypt.OpenSSLSocketImpl$SSLInputStream.read(OpenSSLSocketImpl.java:674)
E/BooksSync( 6714): 	at com.android.okio.Okio$2.read(Okio.java:113)
E/BooksSync( 6714): 	at com.android.okio.RealBufferedSource.indexOf(RealBufferedSource.java:147)
E/BooksSync( 6714): 	at com.android.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:94)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:175)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:101)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:616)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:379)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConn,ectionImpl.java:491)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
E/BooksSync( 6714): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
E/BooksSync( 6714): 	at com.google.api.client.http.javanet.NetHttpResponse.<init>(NetHttpResponse.java:36)
E/BooksSync( 6714): 	at com.google.api.client.http.javanet.NetHttpRequest.execute(NetHttpRequest.java:94)
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:965)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
I/BooksSync( 6714): Finished books sync
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1049): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1049): disableDataServiceNotify
D/DSQN    ( 1049): stop dsqn bin
D/DSQN    ( 1049): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1049): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1049): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1049): InternetcheckProgress is not set don't send DS quality intent
D/SyncManager( 1049): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78318, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/WifiHS20( 1049): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105306  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105306  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1049): Killing 6446:com.google.android.partnersetup/u0a8 (adj 15): empty #17
E/WifiStateMachine( 1049):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1049): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat( 1049): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1049):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1049): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1049): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Disconnected - quitting
E/WifiStateMachine( 1049):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
E/WifiStateMachine( 1049):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/ResourcesManager( 6838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
E/WifiStateMachine( 1049):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/ResourcesManager( 6838): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WifiNetworkAgent( 1049): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105315  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/ResourcesManager( 6838): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6838): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1049): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup( 1049): failed to open /acct/uid_10008/pid_6446/cgroup.procs: No such file or directory
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105378  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1049): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1049): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1049): Removing idletimer
W/Settings( 1049): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1049): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1049): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1049):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1862): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1049): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1049): hidePasspointNotification off =false
D/LocSvc_java( 1049): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1049): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1049): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1049): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1049): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateSCANNING
D/LocSvc_java( 1049): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1049): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1049): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1049): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6838): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6838): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6838): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/DhcpStateMachine( 1049): StoppedState
D/DhcpStateMachine( 1049): StoppedState{ when=-178ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsControl( 6838): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6838): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6838): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1049): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6871 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1049): Killing 6071:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10011/pid_6071/cgroup.procs: No such file or directory
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6871): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6838): LgDataFeature() Constructor: none
D/LgDataFeature( 6838): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
I/ActivityManager( 1049): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6895 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1049): Killing 6090:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10019/pid_6090/cgroup.procs: No such file or directory
,W/ResourcesManager( 6895): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6895): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6895): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6895): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6895): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6895): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6895): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6895): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6895): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6895): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6871): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6871): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6871): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 6895): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6895): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6895): LgDataFeature() Constructor: none
D/LgDataFeature( 6895): LgDataFeature() Constructor Done, null
,V/SoundPool( 6895): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6895): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6895): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6895): doLoad: loading sample sampleID=1
I/QRemote ( 6895): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6895): Start decode
V/MediaPlayer[Native]( 6895): decode(31, 10857164, 17813)
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb54748c0, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
,D/UEI.SmartControl( 6608): QS Service created
D/QRemote ( 6895): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 6895): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  314): supported mime: application/ogg
,V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
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
D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
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
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb15210b0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521100 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521150 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb15211a0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521240 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521290 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521380 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
I/UEI.SmartControl( 6608): Service initServices...
D/UEI.SmartControl( 6608): QS start get config
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb54748c0, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb54748c0, 1, 0, 0)
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
V/LGMDMManager( 6895): Create singleton instance
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974945696
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974945856
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974945936
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974946176
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521290 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1521240 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb15211a0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb54748c0, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb100b000, 4096)
,V/AudioCache(  314): memcpy(0xac202000, 0xb100b000, 4096),
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac203000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac204000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac205000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac206000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac207000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
,V/AudioCache(  314): memcpy(0xac208000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac209000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20a000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20b000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20c000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20d000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20e000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac20f000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac210000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac211000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac212000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac213000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac214000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac215000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac216000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac217000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac218000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac219000, 0xb100b000, 4096)
,V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21a000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21b000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21c000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21d000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21e000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac21f000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac220000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac221000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac222000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac223000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac224000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac225000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac226000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac227000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac228000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac229000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22a000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22b000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22c000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22d000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22e000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac22f000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac230000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac231000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac232000, 0xb100b000, 4096)
V/AudioCache(  314): write(0xb100b000, 4096)
V/AudioCache(  314): memcpy(0xac233000, 0xb100b000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb100b000, 280)
,V/AudioCache(  314): memcpy(0xac234000, 0xb100b000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb54748c0, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb54748c0, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): Pause Playback at 1068125
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb54748c0, 8, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1521150 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1521100 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb15210b0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb15211a0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1521240 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1521290 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
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
V/SoundPool( 6895): close(31)
V/SoundPool( 6895): pointer = 0x9fe85000, size = 205080, sampleRate = 48000, numChannels = 2
D/DSQN    ( 1049): EVENT_INTERNET_CHECK_ENABLE received
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4465
,I/UEI.SmartControl( 6608): Supports setup maps: true
,D/UEI.SmartControl( 6608): QS start statue = true Error code = 0
I/UEI.SmartControl( 6608): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6608): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6608): ### init IR Blaster...
D/serial_port( 6608): Configuring serial port
E/UEI.SmartControl( 6608): UEIBLaster setting for 616
I/UEI.SmartControl( 6608): Setting serial record hearder size = 2
I/UEI.SmartControl( 6608): configuring settings for MAXQ616
I/UEI.SmartControl( 6608): Get version...
D/UEI.SmartControl( 6608): serial port data available: 21
,D/UEI.SmartControl( 6608): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6608): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6608): QS saving settings...
D/UEI.SmartControl( 6608): IR Blaster version: 25672567
,D/UEI.SmartControl( 6608): serial port data available: 4
,I/UEI.SmartControl( 6608): Device manager: loading config....
,D/UEI.SmartControl( 6608): ----------- loading internal config...
W/ContextImpl( 6608): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6608): Services init done
D/UEI.SmartControl( 6608): QS Service init finished
D/UEI.SmartControl( 6608): QS Service version name: 2.1.91
D/UEI.SmartControl( 6608): QS Service version code: 201091
D/UEI.SmartControl( 6608): Service requested: Control
,E/UEI.SmartControl( 6608): Loading SETTINGS...
D/UEI.SmartControl( 6608): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6608): Internal service binding...
,I/QRemote ( 6895): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6608): ------ IControl API: 11
D/UEI.SmartControl( 6608): File observer start...
E/UEI.SmartControl( 6608): IR Port is disabled: false
D/UEI.SmartControl( 6608): Starting file observer...
D/UEI.SmartControl( 6608): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6608): Registering callback...
I/UEI.SmartControl( 6608): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6608): -----service ready thread exits
,I/UEI.SmartControl( 6608): ------ IControl API: 19
I/UEI.SmartControl( 6608): Registering Services Ready callback...
I/UEI.SmartControl( 6608): Notify client services are ready...
I/QRemote ( 6895): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6895): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6895): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6895): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6895): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6608): ------ IControl API: 8
,D/QRemote ( 6895): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6895): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6895): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6895): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6895): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6895): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6895): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6895): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6895): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6895): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455027725130]
D/QRemote ( 6895): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1049): Killing 6474:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 6895): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1049): failed to open /acct/uid_10023/pid_6474/cgroup.procs: No such file or directory
,V/QRemote ( 6895): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6895): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/GAV2    ( 6714): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 2651): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1049): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1049): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1049): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiStateMachine( 1049):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1049):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1049):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1049):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1049): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107336  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107352  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2651): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1049): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107429  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107430  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1049):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107430
E/WifiStateMachine( 1049):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107431
D/Tethering( 1049): sendTetherStateChangedBroadcast 1, 0, 0
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1049):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107434
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107434
I/wpa_supplicant( 2651): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2651): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1049):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107435
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107435  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1049): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1049): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1049): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6838): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6838): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6838): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107449  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6838): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6838): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6838): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateASSOCIATED
D/UsbSettingsControl( 6838): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1049):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1049):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107454  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107455  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1049):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107455
E/WifiStateMachine( 1049):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107456
D/WifiNative-wlan0( 1049): doString: [STATUS]
D/WifiMonitor( 1049): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1049): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1049):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1049): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
I/WifiServerServiceExt( 1049): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1049): setKeepAlivePacketInterval msec : 60
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1049): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1049): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1049): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1049): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1049): SET_NETWORK 0 bssid any: returned true
D/ConnectivityService( 1049): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1049): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1049): NetworkAgent connected
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1049): SAVE_CONFIG: returned true
E/WifiConfigStore( 1049): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1049): doBoolean: SET_NETWORK 0 bssid any
D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/WifiNative-wlan0( 1049): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1049): doBoolean: SAVE_CONFIG
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1049): SAVE_CONFIG: returned true
D/CommandListener(  305): Setting iface cfg
E/WifiStateMachine( 1049): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1049): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1049): WaitBeforeStartState
E/WifiStateMachine( 1049):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107509  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1049):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107509  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1049):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107511  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1049):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107512  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1049):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107512  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1049):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1049): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1049):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1049):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1049): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1049): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1049): doBoolean: SET ps 0
D/WifiNative-wlan0( 1049): SET ps 0: returned true
D/WifiNative-wlan0( 1049): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1049): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1049): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1049): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1049): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11f8a7be target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1049): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@11f8a7be target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1049): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1049): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1049): DHCP Start wake lock is acquired.
D/CommandListener(  305): Setting iface cfg
D/CommandListener(  305): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1049): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1049): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1049): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1049):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1049):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1049): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1049):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1049):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,D/LGWifiP2pService( 1049): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1049): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1049): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1049): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1049): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2651): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1049): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1049): doBoolean: SET ps 1
D/WifiNative-wlan0( 1049): SET ps 1: returned true
D/ConnectivityService( 1049): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1049):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1049):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1049): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1049): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1049): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1049): Adding iface wlan0 to network 101
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1049): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1049): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/WifiHS20( 1049): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1049): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1049): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1049): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1049): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  305): netlink response contains error (File exists)
D/ConnectivityService( 1049): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1049): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1049): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1049): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1049): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1049): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1049): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1049):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1049):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1049): currentScore = 0, newScore = 20
D/ConnectivityService( 1049):    accepting network in place of null
D/ConnectivityService( 1049): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1049): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1049):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1049): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory-1( 1862): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1049): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1049): sendStickyBroadcast: actio,n=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1049): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1049): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1049): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1049): ignore wifi update if we are not in OPENING or CLOSING
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/ConnectivityService( 1049): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1049): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1049): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1049): validation of new default Network = false
D/ConnectivityService( 1049): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1049): enableDataServiceNotify 
,D/DSQN    ( 1049): start dsqn bin
,D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1049): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6968): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6968): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1049): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 6968): DSQN ssw
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6895): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6895): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6895): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6895): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6871): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6871): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/QRemote ( 6895): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6895): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6895): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6895): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6895): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  305): argv[0]=dsqncommand
D/LGDataListener(  305): argv[1]=wlan0
D/LGDataListener(  305): argv[2]=1
D/LGDataListener(  305): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1049): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1049): start to monitor internet connection
D/DhcpStateMachine( 1049): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1049): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1049): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6974): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6974): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:22:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455027726141], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455027726121]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1049): Validated
D/ConnectivityService( 1049): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1049):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1049): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1049): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1049): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1049):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1862): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/dhcpcd  ( 6974): version 5.5.6 starting
,E/dhcpcd  ( 6974): get_duid: m
D/dhcpcd  ( 6974): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6974): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 6974): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6974): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6974): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6974): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6974): wlan0: sending REQUEST (xid 0xbe0d617d), next in 4.28 seconds
I/MusicWidget( 2595): mDelayedStopHandler : unbind
,I/MusicBrowser( 2208): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2208): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2208): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2208): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2208): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2208): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
,I/MusicBrowser( 2208): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1049):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@356db5cacom.lge.music.MediaPlaybackService$5@1156233b
D/MusicBrowser( 2208): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@cd48c41
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2208): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2208): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2208): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2208): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2208): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2208): reset
,V/MediaPlayer[Native]( 2208): setListener
V/MediaPlayer[Native]( 2208): disconnect
V/MediaPlayer[Native]( 2208): destructor
V/AudioFlinger(  314): releasing 13 from 2208 for -1
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
V/MediaPlayer[Native]( 2208): disconnect
D/MusicBrowser( 2208): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,I/SmartShareClient( 2208): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2208): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2208): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2208): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2208): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2208): [SmartShareManagerClient] unregisterListener: 453716568
W/SmartShareClient( 2208): [SmartShareManagerClient] unregisterListener invalid listener: 453716568
I/SmartShareClient( 2208): [SmartShareManagerClient] terminate service: 2208/MediaPlaybackService/245879087
E/HomeCloudIF( 2208): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2208): [SmartShareManagerClient] unbindService context:android.app.Application@2b807b1
,V/CloudHub( 2208): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2208): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2208): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2208): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2208): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/ActivityManager( 1049): Killing 6117:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1049): failed to open /acct/uid_10027/pid_6117/cgroup.procs: No such file or directory
,D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1049): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1049): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1049): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1049): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5473): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/Tethering( 1049): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5473): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1049): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7000 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     ( 1049): Explicit concurrent mark sweep GC freed 82404(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.555ms total 103.458ms
,D/GpsLocationProvider( 1049): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7000): onCreate
,W/AppUp4:DB( 7000):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7000):  setFingerPrint start
I/AppUp4:DB( 7000):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7000):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7000):  SDK version = 21
I/AppUp4:DB( 7000):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7000): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7000): onReceive
,D/LgDataFeature( 7000): LgDataFeature() Constructor: none
D/LgDataFeature( 7000): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7000): Context : android.app.ReceiverRestrictedContext@84528c5
,D/AppUp4:CustFacade( 7000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7000): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7000): begin check event
,I/AppUp4:CustModeStarterReceiver( 7000): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7000): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7000): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7000): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7000): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1049): Killing 6164:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1049): failed to open /acct/uid_10080/pid_6164/cgroup.procs: No such file or directory
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3376): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3376): DownloadService onCreate
,D/LGDMClient( 4313): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3376): in removeSpuriousFiles
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4313): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@3ba9b159 on behalf of 3376
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3376): in trimDatabase
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@d775dff on behalf of 3376
I/ActivityManager( 1049): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7029 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3376): DownloadService onStartCommand
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3376): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4313): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4313): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4313): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@21bb0a15 on behalf of 3376
V/DownloadManager( 3376): processing inserted download 1
,V/DownloadManager( 3376): processing inserted download 4
V/DownloadManager( 3376): processing inserted download 7
V/DownloadManager( 3376): processing inserted download 8
V/DownloadManager( 3376): processing inserted download 9
V/DownloadManager( 3376): processing inserted download 10
V/DownloadManager( 3376): processing inserted download 16
V/DownloadManager( 3376): processing inserted download 17
V/DownloadManager( 3376): processing inserted download 18
V/DownloadManager( 3376): processing inserted download 21
V/DownloadManager( 3376): processing inserted download 22
,V/DownloadManager( 3376): DownloadService onDestroy
W/ResourcesManager( 7029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7029): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7029): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7029): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7029): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7029): LgDataFeature() Constructor: none
D/LgDataFeature( 7029): LgDataFeature() Constructor Done, null
,D/eas_req ( 7029): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1049): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7059 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7029): JNI_OnLoad()
I/HubEmail( 7029): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7029): registerNatives()
I/HubEmail( 7029): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7029): registerNativeMethods()
I/HubEmail( 7029): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7029): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1049): Killing 6502:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,E/WifiStateMachine( 1049):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1049):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1049):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1049):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 6974): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1049):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
W/libprocessgroup( 1049): failed to open /acct/uid_10061/pid_6502/cgroup.procs: No such file or directory
D/ConnectivityService( 1049): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1049): identical MTU - not setting
D/Nat464Xlat( 1049): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1049): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1049):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1049): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/dhcpcd  ( 6974): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6974): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6974): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6974): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6974): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6974): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6974): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6974): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/LgeMiscReceiver( 3322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3322): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3322): networkInfo.isConnected() = false
I/ActivityManager( 1049): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7087 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
D/DhcpStateMachine( 1049): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1049): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1049): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1049): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1049): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1049): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1049): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1049): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1049): RunningState
I/ActivityManager( 1049): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7129 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1049): Killing 6206:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10097/pid_6206/cgroup.procs: No such file or directory
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{2a4b3cfc type 2 when 109906 com.google.android.gms} when 109906
,I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6754): 
,I/ActivityManager( 1049): Killing 6556:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1049): failed to open /acct/uid_1000/pid_6556/cgroup.procs: No such file or directory
,V/AlarmManager( 1049): RTC_WAKEUP set : Alarm{3edfb1da type 0 when 1455027728384 com.android.vending} when 1455027728384
,I/ActivityManager( 1049): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7149 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  343): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 35.877ms
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
I/art     (  343): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 19.799ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 18.707ms
,I/art     ( 7149): Almond Protected OAT
E/WifiStateMachine( 1049):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1049):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1049):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1049):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1049):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1049):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/WeatherApplication( 7149): removeAccount
,D/WeatherApplication( 7149): Account.length = 0
E/WeatherApplication( 7149): OPERATOR:OPEN
D/WeatherAncestor( 7149): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:8,
D/Weather.Utils( 7149): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7149): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7149): 2 : This is isUpdating : false
D/WeatherAncestor( 7149): connectivity changed - connection : true
D/WeatherService( 7149): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7149): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7149): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7149): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7149): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7149): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:8
I/ActivityManager( 1049): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7171 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1049): Killing 5998:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10005/pid_5998/cgroup.procs: No such file or directory
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WifiInternetCheck( 1049): Single check msg out of sync, ignoring.
,D/Finsky  ( 6228): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6228): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6228): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1049): Killing 6581:com.lge.bnr/1000 (adj 15): empty #17
D/ConnectivityService( 1049): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7171): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6754): 
,D/Tethering( 1049): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1049): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1049): failed to open /acct/uid_1000/pid_6581/cgroup.procs: No such file or directory
I/NetworkMonitor( 5473): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1049): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6754): 
,I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6754): 
I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6754): 
,I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6754): 
,I/WebViewFactory( 7171): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7171): Loading: webviewchromium
I/LibraryLoader( 7171): Time to load native libraries: 3 ms (timestamps 1014-1017)
I/LibraryLoader( 7171): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7171): Binding Chromium to main looper Looper (main, tid 1) {3a349404}
,I/LibraryLoader( 7171): Expected native library version number "",actual native library version number ""
I/chromium( 7171): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7171): Initializing chromium process, renderers=0
,W/art     ( 7171): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7171): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7171): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7171): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb152db20, uid 10093
,I/Adreno-EGL( 7171): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7171): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7171): Build Date: 12/12/14 금
I/Adreno-EGL( 7171): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7171): Remote Branch: 
I/Adreno-EGL( 7171): Local Patches: 
I/Adreno-EGL( 7171): Reconstruct Branch: 
W/AudioManagerAndroid( 7171): Requires BLUETOOTH permission
I/NSApplication( 7171): Starting up...
,I/ActivityManager( 1049): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7228 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1049): Killing 6627:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10013/pid_6627/cgroup.procs: No such file or directory
,W/ResourcesManager( 7228): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6608): Internal timer expired: 2
D/UEI.SmartControl( 6608): unbind internal service
,D/serial_port( 6608): close(fd = 24)
,I/UEI.SmartControl( 6608): Serial port is closed.
D/ChimeraCfgMgr( 2330): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2330): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7000): onReceive
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.google.com, class = 1, type = 1
D/AppUp4:CustFacade( 7000): Context : android.app.ReceiverRestrictedContext@84528c5
D/AppUp4:CustFacade( 7000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7000): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7000): begin check event
I/AppUp4:CustModeStarterReceiver( 7000): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSActivity( 2119): [ac] getting account id
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3376): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3376): DownloadService onCreate
D/LGDMClient( 4313): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3376): in removeSpuriousFiles
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  305): res_queryN name = www.google.com succeed
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@38eddb1b on behalf of 3376
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LgeMiscReceiver( 3322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3322): action = android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3376): in trimDatabase
I/LgeMiscReceiver( 3322): networkInfo.isConnected() = false
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@7eab4b8 on behalf of 3376
,I/LGDMClient( 4313): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/WeatherAncestor( 7149): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:10
D/Weather.Utils( 7149): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7149): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7149): 2 : This is isUpdating : false
D/WeatherAncestor( 7149): connectivity changed - connection : true
D/WeatherService( 7149): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@296a514b
,D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/ForecastDataCache( 7149): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7149): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7149): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7149): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7149): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:10
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3376): DownloadService onStartCommand
V/WifiInternetCheck( 1049): isHttpConnectionAvailable - We got a valid response : 204
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3376): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@1a850df7 on behalf of 3376
V/DownloadManager( 3376): processing inserted download 1
V/DownloadManager( 3376): processing inserted download 4
V/DownloadManager( 3376): processing inserted download 7
V/DownloadManager( 3376): processing inserted download 8
,V/DownloadManager( 3376): processing inserted download 9
V/DownloadManager( 3376): processing inserted download 10
V/DownloadManager( 3376): processing inserted download 16
V/DownloadManager( 3376): processing inserted download 17
V/DownloadManager( 3376): processing inserted download 18
V/DownloadManager( 3376): processing inserted download 21
V/DownloadManager( 3376): processing inserted download 22
I/GLSUser ( 2119): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3376): DownloadService onDestroy
,W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4313): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4313): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4313): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ChimeraCfgMgr( 2330): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2330): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = mtalk.google.com, class = 1, type = 1
,W/ContextImpl( 6413): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7000): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7000): onReceive
V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustFacade( 7000): Context : android.app.ReceiverRestrictedContext@84528c5
D/AppUp4:CustFacade( 7000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7000): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7000): begin check event
I/AppUp4:CustModeStarterReceiver( 7000): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/libc-netbsd(  305): res_queryN name = mtalk.google.com succeed
V/DownloadManager( 3376): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3376): DownloadService onCreate
,I/DownloadManager( 3376): in removeSpuriousFiles
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
D/LGDMClient( 4313): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@32366cd on behalf of 3376
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3376): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4313): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3376): in trimDatabase
V/DownloadManager( 3376): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@2ef36b82 on behalf of 3376
I/LGDMClient( 4313): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3376): DownloadService onStartCommand
V/DownloadManager( 3376): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3376): created cursor android.database.sqlite.SQLiteCursor@1a8ca2c9 on behalf of 3376
V/DownloadManager( 3376): processing inserted download 1
V/DownloadManager( 3376): processing inserted download 4
V/DownloadManager( 3376): processing inserted download 7
W/ContextImpl( 4313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3376): processing inserted download 8
V/DownloadManager( 3376): processing inserted download 9
V/DownloadManager( 3376): processing inserted download 10
V/DownloadManager( 3376): processing inserted download 16
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3376): processing inserted download 17
V/DownloadManager( 3376): processing inserted download 18
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3376): processing inserted download 21
E/LGDMClient( 4313): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4313): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4313): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3376): processing inserted download 22
I/LgeMiscReceiver( 3322): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3322): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3322): networkInfo.isConnected() = true
D/PhoneState( 3322): setPdpRejectCasuse : false
V/DownloadManager( 3376): DownloadService onDestroy
,D/WeatherAncestor( 7149): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:10
D/Weather.Utils( 7149): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7149): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7149): 2 : This is isUpdating : false
D/WeatherAncestor( 7149): connectivity changed - connection : true
D/WeatherService( 7149): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@296a514b
D/ForecastDataCache( 7149): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7149): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7149): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7149): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7149): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:22:10
D/ChimeraCfgMgr( 2330): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2330): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1049): Explicit concurrent mark sweep GC freed 32596(1522KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.204ms total 72.130ms
,D/GCM     ( 2119): Connected
D/GCM     ( 2119): Message class com.google.f.a.a.p
I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6754): 
,I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6754): 
I/jxcore-log( 6754): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6754): 
I/GAV4    ( 7171): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6754): Test app app.js loaded
I/jxcore-log( 6754): 
,I/chromium( 6754): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6754): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1331a3 added. We now have 1 listener(s)
I/jxcore-log( 6754): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6754): 
I/ActivityManager( 1049): Killing 6029:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1049): failed to open /acct/uid_10014/pid_6029/cgroup.procs: No such file or directory
,I/CloudHub( 2208): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19998
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 118032723292; DSPS: 4008947; Offset : -4325892658
,I/[SystemUI]LGPowerUI( 1469): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1469): On Skip Timer : true
,D/LEDHandler( 1959): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1959): Battery Level Remaining: 100%
D/LEDHandler( 1959): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1469): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
D/WifiController( 1049): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1469): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1469): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1049): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1049): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3779): Disconnected process message: 10, size: 0
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4313): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1049): RTC_WAKEUP set : Alarm{164295ec type 0 when 1455027749004 com.android.vending} when 1455027749004
,V/QRemote ( 6895): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6895): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4465
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6228): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6228): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6228): [1] 5.onFinished: Scheduling replication attempt 3.
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{13167eee type 2 when 131945 android} when 131945
,I/CloudHub( 2208): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2208): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 138034876200; DSPS: 4664378; Offset : -4325906524
,E/WifiStateMachine( 1049):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1049):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1049):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1049):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1049):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1049):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/AlarmManager( 1049): RTC_WAKEUP set : Alarm{1f0d521c type 0 when 1455027769407 com.android.vending} when 1455027769407
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6228): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6228): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6228): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 158036940515; DSPS: 5319805; Offset : -4325886913
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/PowerManagerServiceEx( 1049): acquireWakeLockInternal: lock=169080146, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{167f9e type 2 when 167712 android} when 167712
D/[Concierge]Service( 2622): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1049): releaseWakeLockInternal: lock=169080146 [*alarm*], flags=0x0
,I/BooksSync( 6714): Starting books sync
,D/BooksSync( 6714): started syncMyEbooks
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
,W/ApiaryClient( 6714): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9113510157155422436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required",
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
,W/ApiaryClient( 6714): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9113510157155422436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
,W/ApiaryClient( 6714): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9113510157155422436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
,E/BooksSync( 6714): Soft error: 
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9113510157155422436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
,E/BooksSync( 6714): Sync error
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9113510157155422436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
I/BooksSync( 6714): Finished books sync
D/SyncManager( 1049): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167712, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 178038543112; DSPS: 5975218; Offset : -4325901721
,V/AlarmManager( 1049): RTC_WAKEUP set : Alarm{89875f1 type 0 when 1455027793099 com.android.vending} when 1455027793099
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6228): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6228): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6228): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{cc11d47 type 2 when 197826 android} when 197826
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 198040679928; DSPS: 6630648; Offset : -4325901006
,V/AlarmManager( 1049): RTC_WAKEUP set : Alarm{f9bce9d type 0 when 1455027819867 com.android.vending} when 1455027819867
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6228): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6228): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6228): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 218042516430; DSPS: 7286068; Offset : -4325895533
,I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
,I/[SystemUI]Clock( 1469): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
,I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
D/PowerManagerServiceEx( 1049): acquireWakeLockInternal: lock=169080146, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{1025e637 type 2 when 227849 android} when 227849
D/[Concierge]Service( 2622): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1049): releaseWakeLockInternal: lock=169080146 [*alarm*], flags=0x0
,I/BooksSync( 6714): Starting books sync
,D/BooksSync( 6714): started syncMyEbooks
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
,D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
W/ApiaryClient( 6714): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9149202113747132744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1049): Explicit concurrent mark sweep GC freed 27526(1150KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.459ms total 149.983ms
,V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
,W/ApiaryClient( 6714): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9149202113747132744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1049): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1049): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1049): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1049): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1049): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6714): Authentication error
E/BooksAccountManager( 6714): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6714): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6714): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6714): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6714): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{32366cd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6714): Error response from books API: {
W/ApiaryClient( 6714):  "error": {
W/ApiaryClient( 6714):   "errors": [
W/ApiaryClient( 6714):    {
W/ApiaryClient( 6714):     "domain": "global",
W/ApiaryClient( 6714):     "reason": "required",
W/ApiaryClient( 6714):     "message": "Login Required",
W/ApiaryClient( 6714):     "locationType": "header",
W/ApiaryClient( 6714):     "location": "Authorization"
W/ApiaryClient( 6714):    }
W/ApiaryClient( 6714):   ],
W/ApiaryClient( 6714):   "code": 401,
W/ApiaryClient( 6714):   "message": "Login Required"
W/ApiaryClient( 6714):  }
W/ApiaryClient( 6714): }
,W/ApiaryClient( 6714): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9149202113747132744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6714): Headers:
W/ApiaryClient( 6714): accept-encoding: [gzip]
W/ApiaryClient( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6714): gdata-version: 2
,E/BooksSync( 6714): Soft error: 
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9149202113747132744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
,E/BooksSync( 6714): Sync error
E/BooksSync( 6714): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6714): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=9149202113747132744&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6714): Headers:
E/BooksSync( 6714): accept-encoding: [gzip]
E/BooksSync( 6714): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6714): gdata-version: 2
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6714): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6714): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6714): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6714): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6714): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6714): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6714): {
E/BooksSync( 6714):  "error": {
E/BooksSync( 6714):   "errors": [
E/BooksSync( 6714):    {
E/BooksSync( 6714):     "domain": "global",
E/BooksSync( 6714):     "reason": "required",
E/BooksSync( 6714):     "message": "Login Required",
E/BooksSync( 6714):     "locationType": "header",
E/BooksSync( 6714):     "location": "Authorization"
E/BooksSync( 6714):    }
E/BooksSync( 6714):   ],
E/BooksSync( 6714):   "code": 401,
E/BooksSync( 6714):   "message": "Login Required"
E/BooksSync( 6714):  }
E/BooksSync( 6714): }
E/BooksSync( 6714): 
E/BooksSync( 6714): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6714): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6714): 	... 8 more
I/BooksSync( 6714): Finished books sync
D/SyncManager( 1049): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 202985, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1049): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1049): tsOffsetIs: Apps: 238046652464; DSPS: 7941564; Offset : -4325909837
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{8176fe9 type 2 when 187324 com.google.android.gms} when 187324
,V/AlarmManager( 1049): ELAPSED_WAKEUP set : Alarm{d49d46e type 2 when 208147 android} when 208147
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2119): Vacuum at: now=1455027859342 tag=VacuumService
,I/GoogleURLConnFactory( 2119): Using platform SSLCertificateSocketFactory
,W/Uploader( 2119): No account for auth token provided
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  305): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  305): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119):  no longer exists, so no auth token.
I/jxcore-log( 6754): --= Surplus to requirements =--
I/jxcore-log( 6754): 
I/jxcore-log( 6754): ****TEST TOOK:  ms ****
I/jxcore-log( 6754): 
I/jxcore-log( 6754): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6754): 
,D/AndroidRuntime( 7456): 
D/AndroidRuntime( 7456): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7456): CheckJNI is OFF
D/AndroidRuntime( 7456): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1049): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1049): Killing 6754:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1049): WIN DEATH: Window{32028f5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1049): Client connection lost with reason: 4
D/InputDispatcher( 1049): Window went away: Window{32028f5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1049): Skipping PackageSetting{335e7d2 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1049):   Force finishing activity ActivityRecord{2753cc26 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  331): DFP En is all cleared set to be enabled
,W/ActivityManager( 1049): Spurious death for ProcessRecord{2e8fe05d 6754:com.test.thalitest/u0a311}, curProc for 6754: null
I/ActivityManager( 1049): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1049):   Force finishing activity ActivityRecord{2753cc26 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1049): Duplicate finish request for ActivityRecord{2753cc26 u0 com.test.thalitest/.MainActivity t4 f}
,I/art     ( 4612): Explicit concurrent mark sweep GC freed 15833(889KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 458us total 134.364ms
,I/[LGHome]EVENT( 2077): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2077): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{201353d5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{3783c7ea co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2077): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2077): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader( 1049): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1826): Ignoring removeGeofence because network location is disabled.
,E/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2033): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,D/LIA_MrGDBLogger_PackageInfoDetector( 3701): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/art     ( 1049): Explicit concurrent mark sweep GC freed 14524(970KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.259ms total 160.326ms
I/art     ( 1049): WaitForGcToComplete blocked for 49.061ms for cause Explicit
,V/SIM_STK ( 1049): Menu title from STK is T-Mobile
,W/System.err( 4566): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4566): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4566): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4566): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4566): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4566): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4566): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4566): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4566): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4566): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4566): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4566): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]GBoardWebView( 2077): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1913): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3701): handleMessage: what(1000) actionID(0x1000003)
D/PostponalbeReceiver( 6413): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/ActivityManager( 1049): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7504 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2077): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2077): [Launcher.java:1056:onResume()]onResume end
D/SplitUIManager( 1879): split_name #11 / not available #0
D/SplitUIService( 1879): removed split : 
D/WallpaperManager( 2077): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1049): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
V/SIM_STK ( 1049): Menu title from STK is T-Mobile
V/SIM_STK ( 1049): Menu title from STK is T-Mobile
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator( 1049): Handling package changes for user 0
,W/PhoneWindowManagerEx( 1049): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1049): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1049): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1049): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33e2ff37,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1049): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2077): [Launcher.java:1114:onPause()]onPause
,D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
I/[LGHome]GBoardWebView( 2077): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3701): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1913): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3701): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2077): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2077): , create_time: 1430558575574
I/GBoardWebViewUtils( 2077): , expire_time: 0
I/GBoardWebViewUtils( 2077): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2077): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2077): , display: false
I/GBoardWebViewUtils( 2077): , animation: false }
I/GBoardWebViewUtils( 2077): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2077): , create_time: 1430558575600
I/GBoardWebViewUtils( 2077): , expire_time: 0
I/GBoardWebViewUtils( 2077): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2077): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2077): , display: false
I/GBoardWebViewUtils( 2077): , animation: false }
I/GBoardWebViewUtils( 2077): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2077): , create_time: 1454599633839
I/GBoardWebViewUtils( 2077): , expire_time: 0
I/GBoardWebViewUtils( 2077): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2077): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2077): , display: false
I/GBoardWebViewUtils( 2077): , animation: false }
V/SIM_STK ( 1049): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2077): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2077): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ActivityManager( 1049): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3779): [BTUI] [-] updateMediaPlayerInfo
I/LockScreenSettings( 7504): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
,W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/NotificationService( 1049): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1049): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1049): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
D/TaskPersister( 1049): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3151): Thermal-Lib-Client: Client request sent
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/AppUp4:PreloadHelper( 7000): added Exclude : com.test.thalitest
,I/art     ( 1049): Explicit concurrent mark sweep GC freed 7850(433KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.618ms total 227.124ms
I/ActivityManager( 1049): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7527 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/KeyguardModel( 1469): handleShortcutListChanged...
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
I/ActivityManager( 1049): Killing 6871:com.lge.sync/1000 (adj 15): empty #17
,D/AndroidRuntime( 7456): Shutting down VM
,D/KeyguardModel( 1469): handleShortcutListChanged...
W/libprocessgroup( 1049): failed to open /acct/uid_1000/pid_6871/cgroup.procs: No such file or directory
,W/ResourcesManager( 1049): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2077): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/Timeline( 1049): Timeline: Activity_windows_visible id: ActivityRecord{17458cd5 u0 com.lge.launcher2/.Launcher t3} time:255847
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
W/ResourceType( 1049): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 7527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7527): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7527): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7527): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7527): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 2077): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2077): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2077): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2077): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]Launcher.Model( 2077): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2077): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2077): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2622): onStartCommand(). Type : 8
D/[Concierge]Service( 2622): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2622): Update widget ID : 11
D/[Concierge]WidgetView( 2077): change position of spinner
,I/[Concierge]WidgetView( 2077): initWebView(). Time : 1455027874265
D/[Concierge]Service( 2622): onStartCommand(). Type : 0
I/SystemConfig( 7527): BUILD Country: EU
,I/SystemConfig( 7527): BUILD Operator: OPEN
I/[Concierge]WebView( 2077): Return exist ConciergeWebView. Reuse : 312315845
D/[Concierge]WidgetView( 2077): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2077): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2077): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2378d78a
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2077): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2077): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2077): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1049): Killing 6838:com.android.settings/1000 (adj 15): empty #17
W/[Concierge]WidgetView( 2077): Widget kill message received. Destory myself. My : 1455027646456, New one : 1455027874265
D/[Concierge]WidgetView( 2077): Unregister all receivers
,W/[Concierge]WidgetBroadcastReceiver( 2077): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/libprocessgroup( 1049): failed to open /acct/uid_1000/pid_6838/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/SystemConfig( 7527): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7527): existFile = false
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/SystemConfig( 7527): canReadFile = false
I/SystemConfig( 7527): systemFeature RCS result false
D/SystemConfig( 7527): refreshRcsSupport() :false
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 7029): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2244): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1049): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7552 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2077): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2077): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2077): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2077): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7552): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7552): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/Timeline( 2077): Timeline: Activity_idle id: android.os.BinderProxy@2cee367e time:256083
I/AppConfig( 7552): Total System Memory = 2995761152
,D/SystemHelper( 7552): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1049): Killing 2208:com.lge.music/u0a34 (adj 15): empty #17

```
