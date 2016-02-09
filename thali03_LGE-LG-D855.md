#### Test 587523534d3a10e_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1a856cf4 type 2 when 101465 android} when 101465
,I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6747 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
I/ReaderUtils( 6747): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/GAV2    ( 6747): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BooksApp( 6747): Created application version: 3.2.35 (30235)
D/AndroidRuntime( 6745): 
D/AndroidRuntime( 6745): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6745): CheckJNI is OFF
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/ContactsSyncAdapter( 2139): innerSync failed
D/ContactsSyncAdapter( 2139): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2139): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2139): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2139): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2139): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2139): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2139): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2139): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2139): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2139): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2139): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
I/BooksSync( 6747): Starting books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 75181, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1037): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 166381, reason: 10019
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 6745): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1988): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3c0f166 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3c0f166 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  334): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6806 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6745): Shutting down VM
D/BooksSync( 6747): started syncMyEbooks
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1878): Display #0 changed.
D/SplitWindowPolicy( 1988): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1988): topRunningActivity=ActivityInfo{1ea28df6 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1988): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1988): topRunningActivity=ActivityInfo{14bb95f7 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ContextHelper( 6806): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 6747): Authentication error
E/BooksAccountManager( 6747): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6747): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6747): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6747): null auth token
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/WebViewFactory( 6806): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6806): Loading: webviewchromium
I/LibraryLoader( 6806): Time to load native libraries: 3 ms (timestamps 2192-2195)
I/LibraryLoader( 6806): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6806): Binding Chromium to main looper Looper (main, tid 1) {33d71b26}
,I/LibraryLoader( 6806): Expected native library version number "",actual native library version number ""
I/chromium( 6806): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6806): Initializing chromium process, renderers=0
W/art     ( 6806): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  315): registerClient() client 0xb558a940, uid 10311
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fde8016:true
W/chromium( 6806): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6806): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6806): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6806): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6806): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6806): Build Date: 12/12/14 금
I/Adreno-EGL( 6806): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6806): Remote Branch: 
I/Adreno-EGL( 6806): Local Patches: 
I/Adreno-EGL( 6806): Reconstruct Branch: 
,W/chromium( 6806): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6806): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6806): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6806): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6806): CordovaWebView is running on device made by: LGE
,W/art     ( 6806): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6806): Attempt to remove local handle scope entry from IRT, ignoring
,W/ApiaryClient( 6747): Error response from books API: {
W/ApiaryClient( 6747):  "error": {
W/ApiaryClient( 6747):   "errors": [
W/ApiaryClient( 6747):    {
W/ApiaryClient( 6747):     "domain": "global",
W/ApiaryClient( 6747):     "reason": "required",
W/ApiaryClient( 6747):     "message": "Login Required",
W/ApiaryClient( 6747):     "locationType": "header",
W/ApiaryClient( 6747):     "location": "Authorization"
W/ApiaryClient( 6747):    }
W/ApiaryClient( 6747):   ],
W/ApiaryClient( 6747):   "code": 401,
W/ApiaryClient( 6747):   "message": "Login Required"
W/ApiaryClient( 6747):  }
W/ApiaryClient( 6747): }
W/ApiaryClient( 6747): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6747): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2674975493552279757&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6747): Headers:
W/ApiaryClient( 6747): accept-encoding: [gzip]
W/ApiaryClient( 6747): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6747): gdata-version: 2
D/OpenGLRenderer( 6806): Render dirty regions requested: true
,I/OpenGLRenderer( 6806): Initialized EGL, version 1.4
D/OpenGLRenderer( 6806): Enabling debug mode 0
D/Atlas   ( 6806): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{28677120 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6806): LgDataFeature() Constructor: none
,D/LgDataFeature( 6806): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1474): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@135e2b7f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +530ms (total +614ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{3d980ca7 u0 com.test.thalitest/.MainActivity t4} time:102577
I/Timeline( 6806): Timeline: Activity_idle id: android.os.BinderProxy@31b299d6 time:102578
,I/chromium( 6806): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6806): 
D/JsMessageQueue( 6806): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6806): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6806): 
D/jxcore_app_log( 6806): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435227392
I/chromium( 6806): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 6747): Authentication error
E/BooksAccountManager( 6747): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6747): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6747): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6747): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6747): Error response from books API: {
W/ApiaryClient( 6747):  "error": {
W/ApiaryClient( 6747):   "errors": [
W/ApiaryClient( 6747):    {
W/ApiaryClient( 6747):     "domain": "global",
W/ApiaryClient( 6747):     "reason": "required",
W/ApiaryClient( 6747):     "message": "Login Required",
W/ApiaryClient( 6747):     "locationType": "header",
W/ApiaryClient( 6747):     "location": "Authorization"
W/ApiaryClient( 6747):    }
W/ApiaryClient( 6747):   ],
W/ApiaryClient( 6747):   "code": 401,
W/ApiaryClient( 6747):   "message": "Login Required"
W/ApiaryClient( 6747):  }
W/ApiaryClient( 6747): }
W/ApiaryClient( 6747): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6747): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2674975493552279757&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6747): Headers:
W/ApiaryClient( 6747): accept-encoding: [gzip]
W/ApiaryClient( 6747): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6747): gdata-version: 2
E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
I/GBMv2   (  334): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6806): Initializing JXcore engine
W/jxcore-log( 6806): JXcore engine is ready
,W/Thread-799( 6868): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10278]" dev="sockfs" ino=10278 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6868): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-799( 6868): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7605]" dev="sockfs" ino=7605 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6868): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-799( 6868): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30288]" dev="sockfs" ino=30288 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6806): Starting JXcore engine
,W/jxcore-log( 6806): Platform android
W/jxcore-log( 6806): 
W/jxcore-log( 6806): Process ARCH arm
W/jxcore-log( 6806): 
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2139): Explicit concurrent mark sweep GC freed 23767(1408KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.861ms total 49.950ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 6747): Authentication error
E/BooksAccountManager( 6747): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6747): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6747): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6747): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6747): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6747): Error response from books API: {
W/ApiaryClient( 6747):  "error": {
W/ApiaryClient( 6747):   "errors": [
W/ApiaryClient( 6747):    {
W/ApiaryClient( 6747):     "domain": "global",
W/ApiaryClient( 6747):     "reason": "required",
W/ApiaryClient( 6747):     "message": "Login Required",
W/ApiaryClient( 6747):     "locationType": "header",
W/ApiaryClient( 6747):     "location": "Authorization"
W/ApiaryClient( 6747):    }
W/ApiaryClient( 6747):   ],
W/ApiaryClient( 6747):   "code": 401,
W/ApiaryClient( 6747):   "message": "Login Required"
W/ApiaryClient( 6747):  }
W/ApiaryClient( 6747): }
W/ApiaryClient( 6747): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6747): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2674975493552279757&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6747): Headers:
W/ApiaryClient( 6747): accept-encoding: [gzip]
W/ApiaryClient( 6747): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6747): gdata-version: 2
,I/jxcore-log( 6806): JXcore Cordova bridge is ready!
I/jxcore-log( 6806): 
W/jxcore-log( 6806): JXcore engine is started
,I/jxcore-log( 6806): Toggling radios to true
I/jxcore-log( 6806): 
,D/BluetoothAdapter( 6806): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6806, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6806, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6806, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [105,159,157 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=6806, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6806): Radios toggled
I/jxcore-log( 6806): 
I/jxcore-log( 6806): My device name is: LGE-LG-D855
I/jxcore-log( 6806): 
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1037): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2139): Read error: ssl=0xaa6d9a00: I/O error during system call, Connection timed out
V/NativeCrypto( 2139): SSL shutdown failed: ssl=0xaa6d9a00: I/O error during system call, Broken pipe
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6870 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1037): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1988): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [105,282,842 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1037): RECONNECT: returned true
,E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105300
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105300
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  310): Clearing all IP addresses on wlan0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI ,() - null]( 1037): Disconnected - quitting
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1878): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1878):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
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
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105359  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105366  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-137ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6870): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6870): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6870): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6870): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6870): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6870): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6905 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6905): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6870): LgDataFeature() Constructor: none
D/LgDataFeature( 6870): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6930 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6095:com.lge.appbox.client/u0a11 (adj 15): empty #17
,E/BooksSync( 6747): Soft error: 
E/BooksSync( 6747): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6747): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2674975493552279757&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6747): Headers:
E/BooksSync( 6747): accept-encoding: [gzip]
E/BooksSync( 6747): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6747): gdata-version: 2
E/BooksSync( 6747): 
E/BooksSync( 6747): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6747): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6747): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6747): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6747): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6747): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6747): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6747): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6747): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6747): {
E/BooksSync( 6747):  "error": {
E/BooksSync( 6747):   "errors": [
E/BooksSync( 6747):    {
E/BooksSync( 6747):     "domain": "global",
E/BooksSync( 6747):     "reason": "required",
E/BooksSync( 6747):     "message": "Login Required",
E/BooksSync( 6747):     "locationType": "header",
E/BooksSync( 6747):     "location": "Authorization"
E/BooksSync( 6747):    }
E/BooksSync( 6747):   ],
E/BooksSync( 6747):   "code": 401,
E/BooksSync( 6747):   "message": "Login Required"
E/BooksSync( 6747):  }
E/BooksSync( 6747): }
E/BooksSync( 6747): 
E/BooksSync( 6747): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6747): 	... 8 more
E/BooksSync( 6747): Sync error
E/BooksSync( 6747): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6747): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2674975493552279757&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6747): Headers:
E/BooksSync( 6747): accept-encoding: [gzip]
E/BooksSync( 6747): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6747): gdata-version: 2
E/BooksSync( 6747): 
E/BooksSync( 6747): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6747): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6747): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6747): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6747): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6747): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6747): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6747): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6747): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6747): {
E/BooksSync( 6747):  "error": {
E/BooksSync( 6747):   "errors": [
E/BooksSync( 6747):    {
E/BooksSync( 6747):     "domain": "global",
E/BooksSync( 6747):     "reason": "required",
E/BooksSync( 6747):     "message": "Login Required",
E/BooksSync( 6747):     "locationType": "header",
E/BooksSync( 6747):     "location": "Authorization"
E/BooksSync( 6747):    }
E/BooksSync( 6747):   ],
E/BooksSync( 6747):   "code": 401,
E/BooksSync( 6747):   "message": "Login Required"
E/BooksSync( 6747):  }
E/BooksSync( 6747): }
E/BooksSync( 6747): 
E/BooksSync( 6747): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6747): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6747): 	... 8 more
I/BooksSync( 6747): Finished books sync
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6095/cgroup.procs: No such file or directory
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1037): Killing 6505:com.lge.email/u0a23 (adj 15): empty #17
W/ResourcesManager( 6930): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1037): Killing 6114:com.android.contacts/u0a19 (adj 15): empty #18
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6505/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6114/cgroup.procs: No such file or directory
D/QRemote ( 6930): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6930): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6930): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6930): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6930): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6930): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6930): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6930): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6930): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6930): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6905): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6905): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6905): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6930): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 6930): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6930): LgDataFeature() Constructor: none
D/LgDataFeature( 6930): LgDataFeature() Constructor Done, null
,V/SoundPool( 6930): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6930): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6930): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6930): doLoad: loading sample sampleID=1
V/SoundPool( 6930): Start decode
I/QRemote ( 6930): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayer[Native]( 6930): decode(31, 10857164, 17813)
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
,V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb54748c0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/QRemote ( 6930): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6671): QS Service created
E/QRemote ( 6930): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6930): Create singleton instance
,I/UEI.SmartControl( 6671): Service initServices...
D/UEI.SmartControl( 6671): QS start get config
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57c6100 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ,allocated buffer 0xb57c6290 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57c6420 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb54748c0, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb54748c0, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044827392
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044827792
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044828192
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57c6290 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57c6100 on output port
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{112f9b9 type 0 when 1455029426560 android} when 1455029426560
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on output port
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1b40e1fe type 2 when 106621 com.google.android.gms} when 106621
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb54748c0, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac300000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac301000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac302000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac303000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac304000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac305000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac306000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac307000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac308000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac309000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30a000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30b000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30c000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30d000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30e000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac30f000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac310000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac311000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac312000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac313000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac314000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac315000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac316000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac317000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac318000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac319000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31a000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31b000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31c000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31d000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31e000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac31f000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac320000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac321000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac322000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac323000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac324000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac325000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac326000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac327000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac328000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac329000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32a000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32b000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32c000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32d000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32e000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac32f000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac330000, 0xb1694000, 4096)
V/AudioCache(  315): write(0xb1694000, 4096)
V/AudioCache(  315): memcpy(0xac331000, 0xb1694000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb1694000, 280)
V/AudioCache(  315): memcpy(0xac332000, 0xb1694000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb54748c0, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb54748c0, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): Pause Playback at 1068125
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb54748c0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb57c6100 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb57c6290 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 6930): close(31)
V/SoundPool( 6930): pointer = 0x9ffb4000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2523
E/WifiStateMachine( 1037):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:41796] from screen [on:0 period:-964485633]
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/GAV2    ( 6747): Thread[GAThread,5,main]: No campaign data found.
,I/UEI.SmartControl( 6671): Supports setup maps: true
,D/UEI.SmartControl( 6671): QS start statue = true Error code = 0
I/UEI.SmartControl( 6671): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6671): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6671): ### init IR Blaster...
D/serial_port( 6671): Configuring serial port
E/UEI.SmartControl( 6671): UEIBLaster setting for 616
I/UEI.SmartControl( 6671): Setting serial record hearder size = 2
I/UEI.SmartControl( 6671): configuring settings for MAXQ616
I/UEI.SmartControl( 6671): Get version...
D/UEI.SmartControl( 6671): serial port data available: 21
,D/UEI.SmartControl( 6671): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6671): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6671): QS saving settings...
D/UEI.SmartControl( 6671): IR Blaster version: 25672567
,D/UEI.SmartControl( 6671): serial port data available: 4
,W/ContextImpl( 6671): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6671): Services init done
D/UEI.SmartControl( 6671): QS Service init finished
D/UEI.SmartControl( 6671): QS Service version name: 2.1.91
D/UEI.SmartControl( 6671): QS Service version code: 201091
D/UEI.SmartControl( 6671): Service requested: Control
I/UEI.SmartControl( 6671): Device manager: loading config....
D/UEI.SmartControl( 6671): ----------- loading internal config...
I/QRemote ( 6930): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6671): ------ IControl API: 11
D/UEI.SmartControl( 6671): File observer start...
E/UEI.SmartControl( 6671): IR Port is disabled: false
D/UEI.SmartControl( 6671): Starting file observer...
I/UEI.SmartControl( 6671): Registering callback...
I/UEI.SmartControl( 6671): ------ IControl API: 19
D/UEI.SmartControl( 6671): Internal service binding...
I/UEI.SmartControl( 6671): Registering Services Ready callback...
E/UEI.SmartControl( 6671): Loading SETTINGS...
D/UEI.SmartControl( 6671): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6671): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6671): -----service ready thread exits
,I/QRemote ( 6930): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6930): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6930): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6930): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6930): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6671): ------ IControl API: 8
D/QRemote ( 6930): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6930): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6930): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6930): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6930): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6930): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6930): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6930): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6930): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 6930): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6930): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455029428149]
D/QRemote ( 6930): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6142:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6930): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6142/cgroup.procs: No such file or directory
,V/QRemote ( 6930): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6930): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
I/MusicWidget( 2677): mDelayedStopHandler : unbind
,I/MusicBrowser( 2236): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2236): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
,D/MusicBrowser( 2236): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2236): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2236): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2668): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107374  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 6930): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107390  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
I/wpa_supplicant( 2668): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107477  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107478  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107479
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107479
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107479
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107480
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107480
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107480  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107487  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2668): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107492  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107493  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
I/wpa_supplicant( 2668): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107498
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107498
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
I/art     ( 1037): Explicit concurrent mark sweep GC freed 47463(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.604ms total 139.753ms
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/MediaFocusControl( 1037):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@c967d62com.lge.music.MediaPlaybackService$5@12136ef3
D/MusicBrowser( 2236): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/MusicBrowser( 2236): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2f3a6e80
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2236): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
I/MusicBrowser( 2236): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2236): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2236): [MediaPlaybackService.java:6665:stop()] oooooo 
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/MediaPlayer[Native]( 2236): reset
I/QRemote ( 6930): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
,E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107542  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/MediaPlayer[Native]( 2236): setListener
V/MediaPlayer[Native]( 2236): disconnect
V/MediaPlayer[Native]( 2236): destructor
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107542  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/AudioFlinger(  315): releasing 13 from 2236 for -1
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
V/MediaPlayer[Native]( 2236): disconnect
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107543  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107543  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107543  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/MusicBrowser( 2236): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107543  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1037): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client supported version code: 305000
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/SmartShareClient( 2236): [SmartShareManagerClient] smartshare client enabled
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/MusicBrowser( 2236): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
I/MusicBrowser( 2236): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2236): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener: 554071984
W/SmartShareClient( 2236): [SmartShareManagerClient] unregisterListener invalid listener: 554071984
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/SmartShareClient( 2236): [SmartShareManagerClient] terminate service: 2236/MediaPlaybackService/869735206
,E/HomeCloudIF( 2236): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2236): [SmartShareManagerClient] unbindService context:android.app.Application@a58c629
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
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b79fa95 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b79fa95 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
V/CloudHub( 2236): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
I/wpa_supplicant( 2668): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
V/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/MusicBrowser( 2236): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
V/WfdStateTracker( 1988): handleWifiStateChangedEvent: 1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only ,value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/Netd    (  310): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = true, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1878): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1878):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6997): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6997): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/DSQN    ( 6997): DSQN ssw
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6870): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6870): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6870): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6870): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6870): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6870): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6870): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:50:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455029428762], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455029428736]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524290
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1878): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1878):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6930): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/dhcpcd  ( 7004): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7004): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6930): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/dhcpcd  ( 7004): version 5.5.6 starting
I/QRemote ( 6930): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6930): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
E/dhcpcd  ( 7004): get_duid: m
D/dhcpcd  ( 7004): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7004): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6905): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6905): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6870): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6870): MCCMNC not supported: null
D/QRemote ( 6930): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6930): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6930): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6930): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6930): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/ActivityManager( 1037): Killing 6193:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/dhcpcd  ( 7004): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7004): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7004): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7004): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7004): wlan0: sending REQUEST (xid 0x59ca2b1e), next in 3.54 seconds
,W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6193/cgroup.procs: No such file or directory
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/Tethering( 1037): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5505): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5505): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6446): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7028 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7028): onCreate
W/AppUp4:DB( 7028):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7028):  setFingerPrint start
I/AppUp4:DB( 7028):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7028):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7028):  SDK version = 21
I/AppUp4:DB( 7028):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7028): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7028): onReceive
,D/LgDataFeature( 7028): LgDataFeature() Constructor: none
D/LgDataFeature( 7028): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7028): Context : android.app.ReceiverRestrictedContext@37771514
D/AppUp4:CustFacade( 7028): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7028): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7028): begin check event
I/AppUp4:CustModeStarterReceiver( 7028): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7028): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7028): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7028): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7028): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6536:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6536/cgroup.procs: No such file or directory
,D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3422): DownloadService onCreate
I/DownloadManager( 3422): in removeSpuriousFiles
,V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@16b9b7f8 on behalf of 3422
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/LGDMClient( 4337): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@4f114d1 on behalf of 3422
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7059 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3422): DownloadService onStartCommand
V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@1ace5ba4 on behalf of 3422
E/LGDMClient( 4337): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4337): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4337): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3422): processing inserted download 1
V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
,V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): processing inserted download 22
V/DownloadManager( 3422): DownloadService onDestroy
,W/ResourcesManager( 7059): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7059): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7059): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7059): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7059): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7059): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524295
I/dhcpcd  ( 7004): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
W/ResourceType( 7059): No package identifier when getting value for resource number 0x00000000
,I/dhcpcd  ( 7004): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7004): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7004): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7004): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7004): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7004): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7004): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7004): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/LgDataFeature( 7059): LgDataFeature() Constructor: none
D/LgDataFeature( 7059): LgDataFeature() Constructor Done, null
,D/eas_req ( 7059): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7104 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{23d1df10 type 0 when 1455029430309 com.android.vending} when 1455029430309
I/HubEmail( 7059): JNI_OnLoad()
I/HubEmail( 7059): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7059): registerNatives()
I/HubEmail( 7059): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7059): registerNativeMethods()
I/HubEmail( 7059): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7059): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{16793dc5 type 2 when 109324 com.google.android.gms} when 109324
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7129 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7149 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6221:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_6221/cgroup.procs: No such file or directory
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6262): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6262): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6262): [1] 5.onFinished: Scheduling replication attempt 2.
V/FormManager( 7104): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7104): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7167 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6600:com.lge.eula/1000 (adj 15): empty #17
I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 22.989ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 18.275ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 15.925ms
,I/ActivityManager( 1037): Killing 6022:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6806): 
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6600/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6022/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6624:com.lge.bnr/1000 (adj 15): empty #17
,W/ProcessCpuTracker( 1037): Skipping unknown process pid 7100
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7103
I/art     ( 7167): Almond Protected OAT
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6624/cgroup.procs: No such file or directory
,D/WeatherApplication( 7167): removeAccount
D/WeatherApplication( 7167): Account.length = 0
E/WeatherApplication( 7167): OPERATOR:OPEN
D/WeatherAncestor( 7167): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:31
D/Weather.Utils( 7167): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7167): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7167): 2 : This is isUpdating : false
D/WeatherAncestor( 7167): connectivity changed - connection : true
D/WeatherService( 7167): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7167): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7167): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7167): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7167): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7167): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:31
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7188 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6645:com.android.calendar/u0a13 (adj 15): empty #17
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,W/libprocessgroup( 1037): failed to open /acct/uid_10013/pid_6645/cgroup.procs: No such file or directory
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5505): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7188): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7188): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7188): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7188): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6806): 
,I/WebViewFactory( 7188): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6806): 
I/LibraryLoader( 7188): Loading: webviewchromium
I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6806): 
,I/LibraryLoader( 7188): Time to load native libraries: 4 ms (timestamps 974-978)
I/LibraryLoader( 7188): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7188): Binding Chromium to main looper Looper (main, tid 1) {316c074f}
I/LibraryLoader( 7188): Expected native library version number "",actual native library version number ""
,I/chromium( 7188): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7188): Initializing chromium process, renderers=0
,W/art     ( 7188): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7188): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7188): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7188): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb558ad60, uid 10093
,W/AudioManagerAndroid( 7188): Requires BLUETOOTH permission
I/Adreno-EGL( 7188): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7188): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7188): Build Date: 12/12/14 금
I/Adreno-EGL( 7188): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7188): Remote Branch: 
I/Adreno-EGL( 7188): Local Patches: 
I/Adreno-EGL( 7188): Reconstruct Branch: 
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6806): 
,I/NSApplication( 7188): Starting up...
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7243 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6055:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10014/pid_6055/cgroup.procs: No such file or directory
,W/ResourcesManager( 7243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2347): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6446): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7028): onReceive
,D/AppUp4:CustFacade( 7028): Context : android.app.ReceiverRestrictedContext@37771514
D/AppUp4:CustFacade( 7028): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7028): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7028): begin check event
I/AppUp4:CustModeStarterReceiver( 7028): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3422): DownloadService onCreate
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3b6854c2 on behalf of 3422
D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/LGDMClient( 4337): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/GLSActivity( 2139): [ac] getting account id
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@254b62d3 on behalf of 3422
W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3422): DownloadService onStartCommand
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = false
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@22eafb0e on behalf of 3422
I/GLSUser ( 2139): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3422): processing inserted download 1
V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
D/WeatherAncestor( 7167): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:32
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
,V/DownloadManager( 3422): processing inserted download 16
D/Weather.Utils( 7167): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7167): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7167): 2 : This is isUpdating : false
D/WeatherAncestor( 7167): connectivity changed - connection : true
D/WeatherService( 7167): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3509c3b2
D/ForecastDataCache( 7167): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7167): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7167): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7167): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7167): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:32
V/DownloadManager( 3422): processing inserted download 17
V/DownloadManager( 3422): processing inserted download 18
E/LGDMClient( 4337): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4337): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4337): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): processing inserted download 22
V/DownloadManager( 3422): DownloadService onDestroy
V/FormManager( 7104): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7104): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2347): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6446): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7028): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7028): onReceive
D/AppUp4:CustFacade( 7028): Context : android.app.ReceiverRestrictedContext@37771514
D/AppUp4:CustFacade( 7028): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7028): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7028): begin check event
I/AppUp4:CustModeStarterReceiver( 7028): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4561): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/DownloadManager( 3422): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3422): DownloadService onCreate
I/LGDMClient( 4337): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4337): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4337): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4337): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4337): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
I/DownloadManager( 3422): in removeSpuriousFiles
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3c1f7b3c on behalf of 3422
,I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3422): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3422): in trimDatabase
V/DownloadManager( 3422): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@3d5bf0c5 on behalf of 3422
I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = true
D/PhoneState( 3359): setPdpRejectCasuse : false
V/DownloadManager( 3422): DownloadService onStartCommand
,V/DownloadManager( 3422): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WeatherAncestor( 7167): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:32
D/Weather.Utils( 7167): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7167): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7167): 2 : This is isUpdating : false
D/WeatherAncestor( 7167): connectivity changed - connection : true
D/WeatherService( 7167): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3509c3b2
D/ForecastDataCache( 7167): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7167): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7167): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7167): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7167): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:50:32
V/DownloadManager( 3422): created cursor android.database.sqlite.SQLiteCursor@1e070f28 on behalf of 3422
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7059): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ChimeraCfgMgr( 2347): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/DownloadManager( 3422): processing inserted download 1
V/DownloadManager( 3422): processing inserted download 4
V/DownloadManager( 3422): processing inserted download 7
I/Kids    ( 2347): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/DownloadManager( 3422): processing inserted download 8
V/DownloadManager( 3422): processing inserted download 9
V/DownloadManager( 3422): processing inserted download 10
V/DownloadManager( 3422): processing inserted download 16
D/libc-netbsd(  310): res_queryN name = www.google.com succeed
V/DownloadManager( 3422): processing inserted download 17
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
,V/DownloadManager( 3422): processing inserted download 18
V/DownloadManager( 3422): processing inserted download 21
V/DownloadManager( 3422): processing inserted download 22
V/FormManager( 7104): There are no updated forms. The schedule will be deleted.
V/FormManager( 7104): Alarm would be updated, because LastCheckTime has been updated.
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
I/art     ( 1037): Explicit concurrent mark sweep GC freed 62658(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.258ms total 73.458ms
,V/DownloadManager( 3422): DownloadService onDestroy
,D/GCM     ( 2139): Connected
,D/GCM     ( 2139): Message class com.google.f.a.a.p
,D/UEI.SmartControl( 6671): Internal timer expired: 2
D/UEI.SmartControl( 6671): unbind internal service
,D/serial_port( 6671): close(fd = 24)
,I/UEI.SmartControl( 6671): Serial port is closed.
I/GAV4    ( 7188): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6806): 
,I/ActivityManager( 1037): Killing 6747:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/jxcore-log( 6806): Test app app.js loaded
I/jxcore-log( 6806): 
,I/chromium( 6806): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6747/cgroup.procs: No such file or directory
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6806): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d7356a added. We now have 1 listener(s)
I/jxcore-log( 6806): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6806): 
I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19993
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 117723176626; DSPS: 3998379; Offset : -4310240601
,I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1037): battery changed pluggedType: 2
D/LEDHandler( 1988): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1988): Battery Level Remaining: 100%
D/LEDHandler( 1988): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3828): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{37fcc52c type 0 when 1455029450867 com.android.vending} when 1455029450867
,V/QRemote ( 6930): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6930): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2523
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{6bb8bf5 type 2 when 131568 android} when 131568
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6262): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6262): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6262): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2236): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 137725048336; DSPS: 4653800; Offset : -4310230594
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
,I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
,I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=832946130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{2451d15c type 0 when 1455029472817 com.android.vending} when 1455029472817
,D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=832946130 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6262): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6262): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6262): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 157727156141; DSPS: 5309229; Offset : -4310228372
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1c186cde type 2 when 166921 android} when 166921
,I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7359 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7359): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7359): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7359): Created application version: 3.2.35 (30235)
,I/BooksSync( 7359): Starting books sync
,D/BooksSync( 7359): started syncMyEbooks
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
W/ApiaryClient( 7359): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5184399198913999526&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
,W/ApiaryClient( 7359): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5184399198913999526&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
,W/ApiaryClient( 7359): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5184399198913999526&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
,E/BooksSync( 7359): Soft error: 
E/BooksSync( 7359): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5184399198913999526&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7359): Headers:
E/BooksSync( 7359): accept-encoding: [gzip]
E/BooksSync( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7359): gdata-version: 2
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7359): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7359): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7359): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7359): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7359): {
E/BooksSync( 7359):  "error": {
E/BooksSync( 7359):   "errors": [
E/BooksSync( 7359):    {
E/BooksSync( 7359):     "domain": "global",
E/BooksSync( 7359):     "reason": "required",
E/BooksSync( 7359):     "message": "Login Required",
E/BooksSync( 7359):     "locationType": "header",
E/BooksSync( 7359):     "location": "Authorization"
E/BooksSync( 7359):    }
E/BooksSync( 7359):   ],
E/BooksSync( 7359):   "code": 401,
E/BooksSync( 7359):   "message": "Login Required"
E/BooksSync( 7359):  }
E/BooksSync( 7359): }
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7359): 	... 8 more
,E/BooksSync( 7359): Sync error
E/BooksSync( 7359): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5184399198913999526&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7359): Headers:
E/BooksSync( 7359): accept-encoding: [gzip]
E/BooksSync( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7359): gdata-version: 2
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7359): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7359): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7359): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7359): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7359): {
E/BooksSync( 7359):  "error": {
E/BooksSync( 7359):   "errors": [
E/BooksSync( 7359):    {
E/BooksSync( 7359):     "domain": "global",
E/BooksSync( 7359):     "reason": "required",
E/BooksSync( 7359):     "message": "Login Required",
E/BooksSync( 7359):     "locationType": "header",
E/BooksSync( 7359):     "location": "Authorization"
E/BooksSync( 7359):    }
E/BooksSync( 7359):   ],
E/BooksSync( 7359):   "code": 401,
E/BooksSync( 7359):   "message": "Login Required"
E/BooksSync( 7359):  }
E/BooksSync( 7359): }
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7359): 	... 8 more
I/BooksSync( 7359): Finished books sync
I/ActivityManager( 1037): Killing 2236:com.lge.music/u0a34 (adj 15): empty #17
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166921, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AudioFlinger(  315): 2236 died, releasing its sessions
V/AudioFlinger(  315):  pid 1878 @ 0
V/AudioFlinger(  315):  pid 3359 @ 1
V/AudioFlinger(  315):  pid 3359 @ 2
,W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2236/cgroup.procs: No such file or directory
,I/GAV2    ( 7359): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 177728314623; DSPS: 5964627; Offset : -4310229427
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{25a3cdab type 0 when 1455029494470 com.android.vending} when 1455029494470
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6262): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6262): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6262): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{26973295 type 2 when 197053 android} when 197053
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 197730891022; DSPS: 6620072; Offset : -4310247153
,I/[SystemUI]TimeTickManager( 1474): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1474): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1474): called onTimeUpdated()
I/[SystemUI]Clock( 1474): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
I/[SystemUI]DateView( 1474): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1474): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=832946130, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{897779b type 0 when 1455029521992 com.android.vending} when 1455029521992
,D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=832946130 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6262): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6262): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6262): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 217732730286; DSPS: 7275492; Offset : -4310238865
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2faaeb05 type 2 when 227083 android} when 227083
,I/BooksSync( 7359): Starting books sync
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 29873(1278KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.550ms total 159.989ms
,D/BooksSync( 7359): started syncMyEbooks
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
,W/ApiaryClient( 7359): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=512002433135764874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{34b0df7b type 2 when 186850 com.google.android.gms} when 186850
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2788d198 type 2 when 207430 android} when 207430
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
,W/ApiaryClient( 7359): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=512002433135764874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
I/VacuumService( 2139): Vacuum at: now=1455029549806 tag=VacuumService
,I/GoogleURLConnFactory( 2139): Using platform SSLCertificateSocketFactory
,I/art     ( 2139): Explicit concurrent mark sweep GC freed 35949(2MB) AllocSpace objects, 13(1872KB) LOS objects, 51% free, 30MB/62MB, paused 1.440ms total 77.199ms
,W/Uploader( 2139): No account for auth token provided
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2139): No account for auth token provided
,W/Uploader( 2139): No account for auth token provided
,W/Uploader( 2139): No account for auth token provided
,W/Uploader( 2139):  no longer exists, so no auth token.
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{3c1f7b3c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7359): Authentication error
E/BooksAccountManager( 7359): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7359): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7359): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7359): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7359): null auth token
W/ApiaryClient( 7359): Error response from books API: {
W/ApiaryClient( 7359):  "error": {
W/ApiaryClient( 7359):   "errors": [
W/ApiaryClient( 7359):    {
W/ApiaryClient( 7359):     "domain": "global",
W/ApiaryClient( 7359):     "reason": "required",
W/ApiaryClient( 7359):     "message": "Login Required",
W/ApiaryClient( 7359):     "locationType": "header",
W/ApiaryClient( 7359):     "location": "Authorization"
W/ApiaryClient( 7359):    }
W/ApiaryClient( 7359):   ],
W/ApiaryClient( 7359):   "code": 401,
W/ApiaryClient( 7359):   "message": "Login Required"
W/ApiaryClient( 7359):  }
W/ApiaryClient( 7359): }
W/ApiaryClient( 7359): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=512002433135764874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7359): Headers:
W/ApiaryClient( 7359): accept-encoding: [gzip]
W/ApiaryClient( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7359): gdata-version: 2
,E/BooksSync( 7359): Soft error: 
E/BooksSync( 7359): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=512002433135764874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7359): Headers:
E/BooksSync( 7359): accept-encoding: [gzip]
E/BooksSync( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7359): gdata-version: 2
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7359): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7359): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7359): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7359): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7359): {
E/BooksSync( 7359):  "error": {
E/BooksSync( 7359):   "errors": [
E/BooksSync( 7359):    {
E/BooksSync( 7359):     "domain": "global",
E/BooksSync( 7359):     "reason": "required",
E/BooksSync( 7359):     "message": "Login Required",
E/BooksSync( 7359):     "locationType": "header",
E/BooksSync( 7359):     "location": "Authorization"
E/BooksSync( 7359):    }
E/BooksSync( 7359):   ],
E/BooksSync( 7359):   "code": 401,
E/BooksSync( 7359):   "message": "Login Required"
E/BooksSync( 7359):  }
E/BooksSync( 7359): }
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7359): 	... 8 more
,E/BooksSync( 7359): Sync error
E/BooksSync( 7359): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7359): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=512002433135764874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7359): Headers:
E/BooksSync( 7359): accept-encoding: [gzip]
E/BooksSync( 7359): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7359): gdata-version: 2
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7359): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7359): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7359): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7359): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7359): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7359): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7359): {
E/BooksSync( 7359):  "error": {
E/BooksSync( 7359):   "errors": [
E/BooksSync( 7359):    {
E/BooksSync( 7359):     "domain": "global",
E/BooksSync( 7359):     "reason": "required",
E/BooksSync( 7359):     "message": "Login Required",
E/BooksSync( 7359):     "locationType": "header",
E/BooksSync( 7359):     "location": "Authorization"
E/BooksSync( 7359):    }
E/BooksSync( 7359):   ],
E/BooksSync( 7359):   "code": 401,
E/BooksSync( 7359):   "message": "Login Required"
E/BooksSync( 7359):  }
E/BooksSync( 7359): }
E/BooksSync( 7359): 
E/BooksSync( 7359): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7359): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7359): 	... 8 more
I/BooksSync( 7359): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203222, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 237734609809; DSPS: 7930914; Offset : -4310251458
,I/[SystemUI]LGPowerUI( 1474): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1474): On Skip Timer : true
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1037): battery changed pluggedType: 2
D/HeadsetStateMachine( 3828): Disconnected process message: 10, size: 0
D/LEDHandler( 1988): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1988): Battery Level Remaining: 100%
D/LEDHandler( 1988): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1474): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1474): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1474): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4337): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/jxcore-log( 6806): --= Surplus to requirements =--
I/jxcore-log( 6806): 
I/jxcore-log( 6806): ****TEST TOOK:  ms ****
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6806): 
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3e3a866a type 2 when 257124 android} when 257124
,D/AndroidRuntime( 7526): 
D/AndroidRuntime( 7526): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7526): CheckJNI is OFF
,D/AndroidRuntime( 7526): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6806:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1037): Skipping PackageSetting{4343e55 com.example.hello/10319} due to missing metadata
,I/WindowState( 1037): WIN DEATH: Window{28677120 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
,D/InputDispatcher( 1037): Window went away: Window{28677120 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257735854124; DSPS: 8586315; Offset : -4310257453
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{3d980ca7 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{33dbb75b 6806:com.test.thalitest/u0a311}, curProc for 6806: null
I/[LGHome]EVENT( 2100): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2100): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2100): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2100): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1938): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3747): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2100): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2100): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2100): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2100): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1938): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3747): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2100): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2100): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2100): , create_time: 1430558575574
I/GBoardWebViewUtils( 2100): , expire_time: 0
I/GBoardWebViewUtils( 2100): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2100): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2100): , display: false
I/GBoardWebViewUtils( 2100): , animation: false }
I/GBoardWebViewUtils( 2100): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2100): , create_time: 1430558575600
I/GBoardWebViewUtils( 2100): , expire_time: 0
I/GBoardWebViewUtils( 2100): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2100): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2100): , display: false
I/GBoardWebViewUtils( 2100): , animation: false }
I/GBoardWebViewUtils( 2100): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2100): , create_time: 1454599633839
I/GBoardWebViewUtils( 2100): , expire_time: 0
I/GBoardWebViewUtils( 2100): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2100): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2100): , display: false
I/GBoardWebViewUtils( 2100): , animation: false }
D/SplitWindowPolicy( 1988): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1988): topRunningActivity=ActivityInfo{2f9a4c64 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1988): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1988): topRunningActivity=ActivityInfo{1512ecd co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,D/PhoneStatusBar( 1474): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@135e2b7f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2100): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/[LGHome]GBoardWebView( 2100): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/WeatherAncestor( 7167): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:52:59
,D/Weather.Utils( 7167): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7167): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7167): 2 : This is isUpdating : false
D/Weather.Utils( 7167): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7167): 2 : All the weather widget is gone.
D/WeatherAncestor( 7167): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:52:59
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/[LGHome]EVENT( 2100): [Launcher.java:5349:onStop()]onStop
,D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2049): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3747): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
I/art     ( 4609): Explicit concurrent mark sweep GC freed 16909(943KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 327us total 32.634ms
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2100): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,W/System.err( 4561): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4561): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4561): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 4561): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4561): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4561): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4561): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4561): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4561): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4561): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4561): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4561): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[SystemUI]QSlideListController( 1474): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/PostponalbeReceiver( 6446): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{3f8b6964 u0 com.lge.launcher2/.Launcher t3} time:258155
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1474): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1897): split_name #11 / not available #0
D/SplitUIService( 1897): removed split : 
I/[LGHome]EVENT( 2100): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]Launcher.Model( 2100): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7591 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2100): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2100): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2100): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/SplitUIManager( 1897): split_name #11 / not available #0
I/SplitUIService( 1897): split app #11
I/[Concierge]WidgetView( 2100): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]WidgetView( 2100): change position of spinner
D/[Concierge]Service( 2615): onStartCommand(). Type : 8
D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,I/[Concierge]WidgetView( 2100): initWebView(). Time : 1455029579239
D/[Concierge]Service( 2615): Update widget ID : 11
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
D/AppUp4:PreloadHelper( 7028): added Exclude : com.test.thalitest
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 21053(1309KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.711ms total 203.308ms
I/art     ( 1037): WaitForGcToComplete blocked for 35.111ms for cause Explicit
I/LockScreenSettings( 7591): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7609 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[Concierge]WebView( 2100): Return exist ConciergeWebView. Reuse : 8168998
D/[Concierge]WidgetView( 2100): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2100): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2100): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2994c36e
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2100): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2100): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/[Concierge]WidgetView( 2100): Widget kill message received. Destory myself. My : 1455029349576, New one : 1455029579239
D/[Concierge]WidgetView( 2100): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2100): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/ThermalEngine(  328): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3176): Thermal-Lib-Client: Client request sent
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
D/administrator( 1037): Handling package changes for user 0
,I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3828): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourcesManager( 7609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
I/[LgeWidgetLib]LgeAppWidgetHostView( 2100): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
E/[LgeWidgetLib]LgeAppWidgetHostView( 2100): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2100): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2100): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
I/ActivityManager( 1037): Killing 6905:com.lge.sync/1000 (adj 15): empty #17
I/Timeline( 2100): Timeline: Activity_idle id: android.os.BinderProxy@2fd54fb1 time:258367
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1474): handleShortcutListChanged...
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6905/cgroup.procs: No such file or directory
D/[Concierge]WidgetView( 2100): isWidgetUpdateSkippable ? true
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
,W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
I/art     ( 1037): Explicit concurrent mark sweep GC freed 8143(450KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.508ms total 196.049ms
D/KeyguardModel( 1474): handleShortcutListChanged...
I/SystemConfig( 7609): BUILD Country: EU
I/SystemConfig( 7609): BUILD Operator: OPEN
,I/ActivityManager( 1037): Killing 6870:com.android.settings/1000 (adj 15): empty #17
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AndroidRuntime( 7526): Shutting down VM
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/chromium( 2100): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2100): onReloaded()
,I/GBoardWebViewClient( 2100): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6870/cgroup.procs: No such file or directory
V/BoardContentProvider( 3747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 3747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/PackageChangeReceiver( 7059): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2170): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7609): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7609): existFile = false
I/SystemConfig( 7609): canReadFile = false
I/SystemConfig( 7609): systemFeature RCS result false
D/SystemConfig( 7609): refreshRcsSupport() :false
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7630 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/ActionManagerService( 1938): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3747): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3747): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1938): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3747): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3747): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3747): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3747): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3747): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2100): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,D/GBoardWebViewUtils( 2100): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2100): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2100): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2100): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2100): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/[LGHome]EVENT( 2100): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7630): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7630): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7630): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7630): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7630): Total System Memory = 2995761152
,D/SystemHelper( 7630): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1037): Killing 7104:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 2049): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2049): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7104/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2049): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6446): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7654 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/GBoardtInterface( 2100): exportHTML()
,E/SQLiteDatabase( 7654): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 7654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7654): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 7654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7654): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7654): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7654): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7654): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7654): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7654): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 7654): Unable to open database for writing.
E/LifetrackerProvider2( 7654): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/Lifetrac,kerProvider2( 7654): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 7654): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 7654): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 7654): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 7654): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 7654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 7654): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 7654): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 7654): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 7654): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 7654): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 7654): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 7654): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 7654): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/ActivityThread( 7654): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 7654): No ProfileInfo entries
I/LG Account v2.2( 7654): isEnabled: false
I/Feature ( 7654): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7654): [Lifetracker]Country: EU
I/Feature ( 7654): [Lifetracker]Operator: OPEN
I/Feature ( 7654): [Lifetracker]Ranking support: false
I/Feature ( 7654): [Lifetracker]Comfort support: false
I/Feature ( 7654): [Lifetracker]Accessory: true
I/Feature ( 7654): [Lifetracker]Health device: true
I/Feature ( 7654): [Lifetracker]Extra Pedometer: false
I/Feature ( 7654): [Lifetracker]Blood glucose device: false
I/Feature ( 7654): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 7654): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
I/GBoardtInterface( 2100): exportHTML()
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7680 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 7129:com.android.chrome/u0a57 (adj 15): empty #17
I/GBoardtInterface( 2100): exportHTML()

```
