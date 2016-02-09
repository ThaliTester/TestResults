#### Test 586983493da948e_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{28c0acaf type 2 when 101312 android} when 101312
I/ActivityManager( 1046): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6785 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
I/ReaderUtils( 6785): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/GAV2    ( 6785): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6785): Created application version: 3.2.35 (30235)
I/BooksSync( 6785): Starting books sync
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/ContactsSyncAdapter( 2130): innerSync failed
D/ContactsSyncAdapter( 2130): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2130): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2130): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2130): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 75389, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1046): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 167267, reason: 10019
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/BooksSync( 6785): started syncMyEbooks
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6785): null auth token
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
W/ApiaryClient( 6785): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=280140854405154468&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
D/AndroidRuntime( 6842): 
D/AndroidRuntime( 6842): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6842): CheckJNI is OFF
D/AndroidRuntime( 6842): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1046): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1966): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1046): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1046): setTaskToReturnTo : TaskRecord{3976087 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1046): setTaskToReturnTo : TaskRecord{3976087 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1046): AppWindowTokenEx init.. 
E/GBMv2   (  333): DFP En is all cleared set to be enabled
I/ActivityManager( 1046): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6872 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6842): Shutting down VM
V/ActivityManager( 1046): Display changed displayId=0
D/DSDPConnection( 1860): Display #0 changed.
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{35b01bff co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{2abdcdcc co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6872): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6872): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6872): Loading: webviewchromium
I/LibraryLoader( 6872): Time to load native libraries: 4 ms (timestamps 3067-3071)
I/LibraryLoader( 6872): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6872): Binding Chromium to main looper Looper (main, tid 1) {11e7db6f}
,I/LibraryLoader( 6872): Expected native library version number "",actual native library version number ""
I/chromium( 6872): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6872): Initializing chromium process, renderers=0
W/art     ( 6872): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6872): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6872): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 6872): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb14fd880, uid 10311
D/BluetoothManagerService( 1046): Message: 20
D/BluetoothManagerService( 1046): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b2de0d9:true
I/Adreno-EGL( 6872): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6872): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6872): Build Date: 12/12/14 금
I/Adreno-EGL( 6872): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6872): Remote Branch: 
I/Adreno-EGL( 6872): Local Patches: 
I/Adreno-EGL( 6872): Reconstruct Branch: 
,W/chromium( 6872): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6872): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6872): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6872): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6872): CordovaWebView is running on device made by: LGE
,W/art     ( 6872): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6872): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6872): Render dirty regions requested: true
I/OpenGLRenderer( 6872): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6872): Enabling debug mode 0
D/Atlas   ( 6872): Validating map...
,D/SplitWindow( 1046): check instance of lgWin Window{3082548b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6872): LgDataFeature() Constructor: none
,D/LgDataFeature( 6872): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1046): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1046): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1046): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1046): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f443c8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1462): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1462): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1462):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1462): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1046): Displayed com.test.thalitest/.MainActivity: +627ms (total +727ms)
I/Timeline( 1046): Timeline: Activity_windows_visible id: ActivityRecord{16476bb4 u0 com.test.thalitest/.MainActivity t4} time:103544
,I/Timeline( 6872): Timeline: Activity_idle id: android.os.BinderProxy@dac7e5f time:103545
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/chromium( 6872): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6872): 
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 21914(1284KB) AllocSpace objects, 6(864KB) LOS objects, 51% free, 30MB/62MB, paused 1.752ms total 68.087ms
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6785): null auth token
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,D/JsMessageQueue( 6872): Set native->JS mode to OnlineEventsBridgeMode
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
W/ApiaryClient( 6785): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=280140854405154468&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
,E/GBMv2   (  333): DFP En is all cleared set to be enabled
E/GBMv2   (  333): Set value is all cleared set the max
,I/GBMv2   (  333): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 6872): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435218688
,I/chromium( 6872): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6872): 
,I/chromium( 6872): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6785): null auth token
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
W/ApiaryClient( 6785): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=280140854405154468&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
,W/jxcore-log( 6872): Initializing JXcore engine
W/jxcore-log( 6872): JXcore engine is ready
,W/Thread-804( 6932): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7563]" dev="sockfs" ino=7563 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-804( 6932): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-804( 6932): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10615]" dev="sockfs" ino=10615 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-804( 6932): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-804( 6932): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32608]" dev="sockfs" ino=32608 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6872): Starting JXcore engine
,W/jxcore-log( 6872): Platform android
W/jxcore-log( 6872): 
W/jxcore-log( 6872): Process ARCH arm
W/jxcore-log( 6872): 
,I/jxcore-log( 6872): JXcore Cordova bridge is ready!
I/jxcore-log( 6872): 
W/jxcore-log( 6872): JXcore engine is started
,E/BooksSync( 6785): Soft error: 
E/BooksSync( 6785): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=280140854405154468&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6785): Headers:
E/BooksSync( 6785): accept-encoding: [gzip]
E/BooksSync( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6785): gdata-version: 2
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6785): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6785): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6785): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6785): {
E/BooksSync( 6785):  "error": {
E/BooksSync( 6785):   "errors": [
E/BooksSync( 6785):    {
E/BooksSync( 6785):     "domain": "global",
E/BooksSync( 6785):     "reason": "required",
E/BooksSync( 6785):     "message": "Login Required",
E/BooksSync( 6785):     "locationType": "header",
E/BooksSync( 6785):     "location": "Authorization"
E/BooksSync( 6785):    }
E/BooksSync( 6785):   ],
E/BooksSync( 6785):   "code": 401,
E/BooksSync( 6785):   "message": "Login Required"
E/BooksSync( 6785):  }
E/BooksSync( 6785): }
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6785): 	... 8 more
E/BooksSync( 6785): Sync error
E/BooksSync( 6785): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=280140854405154468&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6785): Headers:
E/BooksSync( 6785): accept-encoding: [gzip]
E/BooksSync( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6785): gdata-version: 2
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6785): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.NetworkTaskQue,ue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6785): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6785): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6785): {
E/BooksSync( 6785):  "error": {
E/BooksSync( 6785):   "errors": [
E/BooksSync( 6785):    {
E/BooksSync( 6785):     "domain": "global",
E/BooksSync( 6785):     "reason": "required",
E/BooksSync( 6785):     "message": "Login Required",
E/BooksSync( 6785):     "locationType": "header",
E/BooksSync( 6785):     "location": "Authorization"
E/BooksSync( 6785):    }
E/BooksSync( 6785):   ],
E/BooksSync( 6785):   "code": 401,
E/BooksSync( 6785):   "message": "Login Required"
E/BooksSync( 6785):  }
E/BooksSync( 6785): }
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6785): 	... 8 more
I/BooksSync( 6785): Finished books sync
,I/ActivityManager( 1046): Killing 6516:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78877, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 6872): Toggling radios to true
I/jxcore-log( 6872): 
D/BluetoothAdapter( 6872): enable(): BT is already enabled..!
D/WifiService( 1046): New client listening to asynchronous messages
,W/libprocessgroup( 1046): failed to open /acct/uid_10008/pid_6516/cgroup.procs: No such file or directory
D/WifiServiceImplEx( 1046): setWifiEnabled: true pid=6872, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1046): setWifiEnabled: true pid=6872, uid=10311
E/WifiService( 1046): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1046): disconnect pid=6872, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1046): reconnect pid=6872, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1046):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6872): Radios toggled
I/jxcore-log( 6872): 
I/jxcore-log( 6872): My device name is: LGE-LG-D855
I/jxcore-log( 6872): 
E/WifiNative: ( 1046): [106,050,920 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1046): doBoolean: DISCONNECT
I/wpa_supplicant( 2615): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiNative-wlan0( 1046): DISCONNECT: returned true
E/WifiStateMachine( 1046): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1046): InitialState.processMessage what=4
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1046): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1046): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
D/Tethering( 1046): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1046): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1046): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/DhcpStateMachine( 1046): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  310): Clearing all IP addresses on wlan0
V/NativeCrypto( 2130): Read error: ssl=0xaa7b4200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2130): SSL shutdown failed: ssl=0xaa7b4200: I/O error during system call, Broken pipe
,I/ActivityManager( 1046): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6945 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1046): Start Disconnecting Watchdog 1
V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 0
D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1046):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1046): [106,171,378 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1046): doBoolean: RECONNECT
I/wpa_supplicant( 2615): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1046): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1046): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1046): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1046): RECONNECT: returned true
E/WifiStateMachine( 1046):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106196
,E/WifiStateMachine( 1046):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106196
D/LGWifiP2pService( 1046): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1046): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1046): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1046): disableDataServiceNotify
D/DSQN    ( 1046): stop dsqn bin
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1046): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106244  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106244  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1046):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1046):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1046): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1046): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Disconnected - quitting
D/CSLegacyTypeTracker( 1046): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1046): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1046): sendStickyBroadcast: action=andro,id.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1046): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
V/NetworkPolicy( 1046): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
V/NetworkPolicy( 1046): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1046): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1046): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1046): Removing idletimer
D/TelephonyNetworkFactory-1( 1860): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1046): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1046): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1046): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1046):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1046): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106262  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1046): hidePasspointNotification off =false
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106268  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WIFI    ( 1046): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt( 1046): setSupplicantStateDISCONNECTED
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateSCANNING
W/ResourcesManager( 6945): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6945): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
,W/ResourcesManager( 6945): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1046): StoppedState
D/DhcpStateMachine( 1046): StoppedState{ when=-184ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6945): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6945): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6945): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6945): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6945): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6945): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1046): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6981 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1046): Killing 6134:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1046): failed to open /acct/uid_10011/pid_6134/cgroup.procs: No such file or directory
,I/GAV2    ( 6785): Thread[GAThread,5,main]: No campaign data found.
,I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6981): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6945): LgDataFeature() Constructor: none
D/LgDataFeature( 6945): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
I/ActivityManager( 1046): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7007 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1046): Killing 6154:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_10019/pid_6154/cgroup.procs: No such file or directory
,W/ResourcesManager( 7007): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7007): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7007): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7007): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 7007): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7007): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7007): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7007): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7007): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7007): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7007): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6981): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6981): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6981): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7007): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7007): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7007): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7007): LgDataFeature() Constructor: none
,D/LgDataFeature( 7007): LgDataFeature() Constructor Done, null
V/SoundPool( 7007): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7007): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7007): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7007): doLoad: loading sample sampleID=1
V/SoundPool( 7007): Start decode
V/MediaPlayer[Native]( 7007): decode(31, 10857164, 17813)
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb5474d80, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
I/QRemote ( 7007): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6719): QS Service created
,D/QRemote ( 7007): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/UEI.SmartControl( 6719): Service initServices...
D/UEI.SmartControl( 6719): QS start get config
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
,V/MediaPlayerService(  315): prepare
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
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf10 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder,] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb5474d80, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb5474d80, 1, 0, 0)
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
E/QRemote ( 7007): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797584
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb5474d80, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb57ca000, 4096)
,V/AudioCache(  315): memcpy(0xab602000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab603000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
,V/AudioCache(  315): memcpy(0xab604000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab605000, 0xb57ca000, 4096)
,V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab606000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab607000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab608000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab609000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60a000, 0xb57ca000, 4096)
V/LGMDMManager( 7007): Create singleton instance
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60b000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60c000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60d000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60e000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab60f000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab610000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab611000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab612000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab613000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab614000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab615000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab616000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab617000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab618000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab619000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61a000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61b000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61c000, 0xb57ca000, 4096)
,V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61d000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61e000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab61f000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab620000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab621000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab622000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab623000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab624000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab625000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab626000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab627000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab628000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab629000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62a000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62b000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62c000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62d000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62e000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab62f000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab630000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab631000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab632000, 0xb57ca000, 4096)
V/AudioCache(  315): write(0xb57ca000, 4096)
V/AudioCache(  315): memcpy(0xab633000, 0xb57ca000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb57ca000, 280)
V/AudioCache(  315): memcpy(0xab634000, 0xb57ca000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
,V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb5474d80, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb5474d80, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb5474d80, 8, 0, 0)
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
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca60 on port 1
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
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 7007): close(31)
V/SoundPool( 7007): pointer = 0x9ffc0000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7007): [RemoteAppWidgetProv,ider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8101
I/MusicWidget( 2673): mDelayedStopHandler : unbind
I/MusicBrowser( 2193): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2193): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2193): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2193): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2193): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2193): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1046):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@19c4a17bcom.lge.music.MediaPlaybackService$5@20e6b98
,D/MusicBrowser( 2193): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@89a4481
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2193): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2193): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2193): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2193): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2193): reset
V/MediaPlayer[Native]( 2193): setListener
V/MediaPlayer[Native]( 2193): disconnect
V/MediaPlayer[Native]( 2193): destructor
V/AudioFlinger(  315): releasing 13 from 2193 for -1
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
,V/MediaPlayer[Native]( 2193): disconnect
D/MusicBrowser( 2193): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2193): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2193): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2193): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2193): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2193): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2193): [SmartShareManagerClient] unregisterListener: 343691249
W/SmartShareClient( 2193): [SmartShareManagerClient] unregisterListener invalid listener: 343691249
I/SmartShareClient( 2193): [SmartShareManagerClient] terminate service: 2193/MediaPlaybackService/300407663
,E/HomeCloudIF( 2193): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2193): [SmartShareManagerClient] unbindService context:android.app.Application@1eafa7d6
V/CloudHub( 2193): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2193): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2193): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2193): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2193): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/UEI.SmartControl( 6719): Supports setup maps: true
,D/UEI.SmartControl( 6719): QS start statue = true Error code = 0
I/UEI.SmartControl( 6719): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6719): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6719): ### init IR Blaster...
D/serial_port( 6719): Configuring serial port
,E/UEI.SmartControl( 6719): UEIBLaster setting for 616,
I/UEI.SmartControl( 6719): Setting serial record hearder size = 2
I/UEI.SmartControl( 6719): configuring settings for MAXQ616
,I/UEI.SmartControl( 6719): Get version...
D/UEI.SmartControl( 6719): serial port data available: 21
,D/UEI.SmartControl( 6719): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6719): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6719): QS saving settings...
,D/UEI.SmartControl( 6719): IR Blaster version: 25672567
D/UEI.SmartControl( 6719): serial port data available: 4
,I/UEI.SmartControl( 6719): Device manager: loading config....
,D/UEI.SmartControl( 6719): ----------- loading internal config...
W/ContextImpl( 6719): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6719): Services init done
D/UEI.SmartControl( 6719): QS Service init finished
D/UEI.SmartControl( 6719): QS Service version name: 2.1.91
D/UEI.SmartControl( 6719): QS Service version code: 201091
D/UEI.SmartControl( 6719): Service requested: Control
D/UEI.SmartControl( 6719): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6719): Loading SETTINGS...
,D/UEI.SmartControl( 6719): Internal service binding...
I/QRemote ( 7007): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6719): ------ IControl API: 11
D/UEI.SmartControl( 6719): File observer start...
E/UEI.SmartControl( 6719): IR Port is disabled: false
D/UEI.SmartControl( 6719): Starting file observer...
I/UEI.SmartControl( 6719): Registering callback...
I/UEI.SmartControl( 6719): ------ IControl API: 19
I/UEI.SmartControl( 6719): Registering Services Ready callback...
D/UEI.SmartControl( 6719): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6719): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6719): -----service ready thread exits
I/QRemote ( 7007): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7007): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7007): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7007): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7007): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6719): ------ IControl API: 8
D/QRemote ( 7007): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7007): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7007): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7007): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7007): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7007): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7007): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{32a9ec74 type 0 when 1454986316435 android} when 1454986316435
,V/QRemote ( 7007): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7007): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7007): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454986317688]
D/QRemote ( 7007): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
E/WifiStateMachine( 1046):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:42769] from screen [on:0 period:-1007595652]
I/ActivityManager( 1046): Killing 6174:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 7007): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1046): Killing 6538:com.lge.email/u0a23 (adj 15): empty #18
,W/libprocessgroup( 1046): failed to open /acct/uid_10023/pid_6538/cgroup.procs: No such file or directory
W/libprocessgroup( 1046): failed to open /acct/uid_10027/pid_6174/cgroup.procs: No such file or directory
V/QRemote ( 7007): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7007): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1046): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
I/wpa_supplicant( 2615): Trying to associate with SSID 'NG700'
W/WifiMonitor( 1046): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1046):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1046):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1046):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1046):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1046): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108276  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108289  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2615): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1046): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1046):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1046):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1046): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6945): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6945): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6945): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108387  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108388  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbSettingsControl( 6945): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6945): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6945): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1046):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108389
E/WifiStateMachine( 1046):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108390
D/UsbSettingsControl( 6945): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1046):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108390
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108391
E/WifiStateMachine( 1046):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108394
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108395  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2615): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2615): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1046): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1046): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1046): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108407  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1046):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108408  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108408  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1046):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108409
E/WifiStateMachine( 1046):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108409
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1046): doString: [STATUS]
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiMonitor( 1046): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1046): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateASSOCIATED
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1046):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServiceExtension( 1046): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1046): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1046): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1046): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1046): Got NetworkAgent Messenger
E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1046): NetworkAgent connected
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
E/WifiConfigStore( 1046): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1046): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1046): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1046): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1046): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
E/WifiStateMachine( 1046): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1046): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1046): WaitBeforeStartState
E/WifiStateMachine( 1046):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108467  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1046):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108468  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1046): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
E/WifiStateMachine( 1046):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108468  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1046):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108479  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1046):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1046): doBoolean: DRIVER SETSUSPENDMODE 0
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1046): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 0
D/WifiNative-wlan0( 1046): SET ps 0: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1046): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1046): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d37e425 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1046): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d37e425 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1046): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1046): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1046): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1046): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1046): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1046):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1046): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1046): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1046):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1046):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1046): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1046): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1046): doBoolean: DRIVER BTCOEXMODE 2
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1046): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1046): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2615): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1046): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1046): doBoolean: SET ps 1
D/WifiNative-wlan0( 1046): SET ps 1: returned true
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1046):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1046):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1046): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1046): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1046): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1046): Adding iface wlan0 to network 101
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiHS20( 1046): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 0
E/WifiStateMachine( 1046): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1046): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1046): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1046): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  310): netlink response contains error (File exists)
D/ConnectivityService( 1046): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/WifiHS20( 1046): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1046): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1046): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1046): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1046): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1046): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1046): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Checking http://clients3.google.com/generate_204 on "NG700"
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1046): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1046): currentScore = 0, newScore = 20
D/ConnectivityService( 1046):    accepting network in place of null
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1046): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1860): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1046): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1046): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1046): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1046): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1046): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1046): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1046): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1046): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1046): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1046): validation of new default Network = false
D/ConnectivityService( 1046): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1046): enableDataServiceNotify 
D/DSQN    ( 1046): start dsqn bin
D/ConnectivityService( 1046): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
V/NetworkPolicy( 1046): [LG_RESTRICTED] checkMobilePolicy_type()
W/dsqn    ( 7067): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7067): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
E/DSQN    ( 7067): DSQN ssw
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7007): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7007): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7007): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7007): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6981): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6981): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6945): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine( 1046): DHCPV4 request on wlan0
D/WiFiOffLoadBroadcast( 6945): MCCMNC not supported: null
V/LgDhcpStateMachineHelper( 1046): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1046): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1046): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1046): start to monitor internet connection
W/dhcpcd  ( 7072): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7072): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7007): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7007): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/dhcpcd  ( 7072): version 5.5.6 starting
D/QRemote ( 7007): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7007): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7007): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
E/dhcpcd  ( 7072): get_duid: m
D/dhcpcd  ( 7072): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7072): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:51:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454986318734], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454986318714]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1046): Validated
D/ConnectivityService( 1046): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1046):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1046): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1046): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1046): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1860): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1046): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1046):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7072): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7072): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7072): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7072): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7072): wlan0: sending REQUEST (xid 0xa23e2234), next in 3.36 seconds
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1046): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1046): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1046): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7099 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 81866(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.809ms total 140.771ms
,I/AppUp4:AppBoxCP( 7099): onCreate
,W/AppUp4:DB( 7099):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7099):  setFingerPrint start
I/AppUp4:DB( 7099):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7099):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7099):  SDK version = 21
I/AppUp4:DB( 7099):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7099): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7099): onReceive
D/LgDataFeature( 7099): LgDataFeature() Constructor: none
D/LgDataFeature( 7099): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7099): Context : android.app.ReceiverRestrictedContext@2033dd05
,D/AppUp4:CustFacade( 7099): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7099): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7099): begin check event
I/AppUp4:CustModeStarterReceiver( 7099): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7099): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7099): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7099): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7099): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1046): Killing 6194:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1046): failed to open /acct/uid_10080/pid_6194/cgroup.procs: No such file or directory
V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{c915009 type 0 when 1454986319692 com.android.vending} when 1454986319692
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3373): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3373): DownloadService onCreate
D/LGDMClient( 4327): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4327): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3373): in removeSpuriousFiles
,D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3373): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@1eab5199 on behalf of 3373
I/ActivityManager( 1046): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7131 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4327): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4327): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4327): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
V/DownloadManager( 3373): DownloadService onStartCommand
V/DownloadManager( 3373): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@3dc6350c on behalf of 3373
I/DownloadManager( 3373): in trimDatabase
V/DownloadManager( 3373): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3373): processing inserted download 1
V/DownloadManager( 3373): processing inserted download 4
V/DownloadManager( 3373): processing inserted download 7
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@4d66e55 on behalf of 3373
V/DownloadManager( 3373): processing inserted download 8
V/DownloadManager( 3373): processing inserted download 9
V/DownloadManager( 3373): processing inserted download 10
,V/DownloadManager( 3373): processing inserted download 16
,V/DownloadManager( 3373): processing inserted download 17
V/DownloadManager( 3373): processing inserted download 18
V/DownloadManager( 3373): processing inserted download 21
V/DownloadManager( 3373): processing inserted download 22
V/SIM_STK ( 1046): Menu title from STK is T-Mobile
V/DownloadManager( 3373): DownloadService onDestroy
,W/ResourcesManager( 7131): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7131): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7131): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7131): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7131): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7131): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
W/ResourceType( 7131): No package identifier when getting value for resource number 0x00000000
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6236): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6236): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6236): [1] 5.onFinished: Scheduling replication attempt 2.
,D/LgDataFeature( 7131): LgDataFeature() Constructor: none
,D/LgDataFeature( 7131): LgDataFeature() Constructor Done, null
,D/eas_req ( 7131): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1046): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7156 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,E/WifiStateMachine( 1046):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1046):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1046): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1046): identical MTU - not setting
,D/Nat464Xlat( 1046): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/dhcpcd  ( 7072): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/ConnectivityService( 1046): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1046):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/HubEmail( 7131): JNI_OnLoad()
I/HubEmail( 7131): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7131): registerNatives()
I/HubEmail( 7131): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7131): registerNativeMethods()
I/HubEmail( 7131): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7131): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/ConnectivityService( 1046): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524295
,W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager( 1046): Killing 6578:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/dhcpcd  ( 7072): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7072): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7072): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7072): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7072): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7072): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7072): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7072): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/libprocessgroup( 1046): failed to open /acct/uid_10061/pid_6578/cgroup.procs: No such file or directory
,W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3326): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3326): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3326): networkInfo.isConnected() = false
,I/ActivityManager( 1046): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7193 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/DhcpStateMachine( 1046): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1046): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1046): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1046): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1046): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1046): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1046): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1046): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1046): RunningState
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1046): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7219 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6212:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/art     (  337): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.625ms total 18.818ms
,V/FormManager( 7156): There are no updated forms. The schedule will be deleted.
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 25.466ms
V/FormManager( 7156): Alarm would be updated, because LastCheckTime has been updated.
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 18.439ms
,W/libprocessgroup( 1046): failed to open /acct/uid_10097/pid_6212/cgroup.procs: No such file or directory
,I/ActivityManager( 1046): Killing 6635:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6635/cgroup.procs: No such file or directory
,I/ActivityManager( 1046): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7240 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1046): Killing 6061:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6872): 
,E/WifiStateMachine( 1046):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1046):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1046):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1046): failed to open /acct/uid_10005/pid_6061/cgroup.procs: No such file or directory
I/art     ( 7240): Almond Protected OAT
,D/WeatherApplication( 7240): removeAccount
,D/WeatherApplication( 7240): Account.length = 0
E/WeatherApplication( 7240): OPERATOR:OPEN
D/WeatherAncestor( 7240): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:1
,D/Weather.Utils( 7240): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7240): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7240): 2 : This is isUpdating : false
D/WeatherAncestor( 7240): connectivity changed - connection : true
D/WeatherService( 7240): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7240): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7240): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7240): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7240): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7240): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:1
,I/ActivityManager( 1046): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7258 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6669:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6669/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7258): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1046): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1046): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1046): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1046): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5518): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1046): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7258): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7258): Loading: webviewchromium
I/LibraryLoader( 7258): Time to load native libraries: 5 ms (timestamps 1804-1809)
I/LibraryLoader( 7258): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7258): Binding Chromium to main looper Looper (main, tid 1) {364aa944}
I/LibraryLoader( 7258): Expected native library version number "",actual native library version number ""
,I/chromium( 7258): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6872): 
,I/BrowserStartupController( 7258): Initializing chromium process, renderers=0
,W/art     ( 7258): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7258): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7258): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7258): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb57bbb40, uid 10093
W/AudioManagerAndroid( 7258): Requires BLUETOOTH permission
I/Adreno-EGL( 7258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7258): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7258): Build Date: 12/12/14 금
I/Adreno-EGL( 7258): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7258): Remote Branch: 
I/Adreno-EGL( 7258): Local Patches: 
I/Adreno-EGL( 7258): Reconstruct Branch: 
,I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6872): 
,I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6872): 
I/NSApplication( 7258): Starting up...
,I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6872): 
,I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6872): 
,I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6872): 
I/ActivityManager( 1046): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7318 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1046): Killing 6700:com.android.calendar/u0a13 (adj 15): empty #17
I/jxcore-log( 6872): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6872): 
W/libprocessgroup( 1046): failed to open /acct/uid_10013/pid_6700/cgroup.procs: No such file or directory
,W/ResourcesManager( 7318): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=71743952, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/ChimeraCfgMgr( 2319): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2319): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSActivity( 2130): [ac] getting account id
I/GLSUser ( 2130): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7099): onReceive
,D/AppUp4:CustFacade( 7099): Context : android.app.ReceiverRestrictedContext@2033dd05
D/AppUp4:CustFacade( 7099): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7099): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7099): begin check event
I/AppUp4:CustModeStarterReceiver( 7099): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3373): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3373): DownloadService onCreate
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2319): [AccountUtils] Account not ready
W/Kids    ( 2319): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2319): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2319): 	at java.lang.Thread.run(Thread.java:818)
D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4327): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LgeQuickCoverNLService( 1405): onNotificationPosted
I/LGDMClient( 4327): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 6719): Internal timer expired: 2
D/UEI.SmartControl( 6719): unbind internal service
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,I/LgeMiscReceiver( 3326): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3326): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3326): networkInfo.isConnected() = false
W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/DownloadManager( 3373): in removeSpuriousFiles
E/LGDMClient( 4327): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3373): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4327): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4327): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@9f8795b on behalf of 3373
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
D/WeatherAncestor( 7240): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:2
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3373): in trimDatabase
V/DownloadManager( 3373): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/Weather.Utils( 7240): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7240): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7240): 2 : This is isUpdating : false
D/WeatherAncestor( 7240): connectivity changed - connection : true
D/WeatherService( 7240): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2340bf8b
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@2b2795f8 on behalf of 3373
D/ForecastDataCache( 7240): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7240): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7240): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7240): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7240): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:2
V/DownloadManager( 3373): DownloadService onStartCommand
V/DownloadManager( 3373): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@363b5037 on behalf of 3373
V/DownloadManager( 3373): processing inserted download 1
V/DownloadManager( 3373): processing inserted download 4
V/DownloadManager( 3373): processing inserted download 7
V/DownloadManager( 3373): processing inserted download 8
V/DownloadManager( 3373): processing inserted download 9
V/DownloadManager( 3373): processing inserted download 10
V/DownloadManager( 3373): processing inserted download 16
,V/DownloadManager( 3373): processing inserted download 17
V/DownloadManager( 3373): processing inserted download 18
V/DownloadManager( 3373): processing inserted download 21
V/DownloadManager( 3373): processing inserted download 22
V/DownloadManager( 3373): DownloadService onDestroy
D/serial_port( 6719): close(fd = 24)
I/UEI.SmartControl( 6719): Serial port is closed.
,V/FormManager( 7156): There are no updated forms. The schedule will be deleted.
V/FormManager( 7156): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2319): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7099): onReceive
,D/AppUp4:CustFacade( 7099): Context : android.app.ReceiverRestrictedContext@2033dd05
D/AppUp4:CustFacade( 7099): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7099): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7099): begin check event
I/AppUp4:CustModeStarterReceiver( 7099): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4327): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4327): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3373): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4327): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3373): DownloadService onCreate
I/DownloadManager( 3373): in removeSpuriousFiles
,V/DownloadManager( 3373): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@38b742c2 on behalf of 3373
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3373): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3373): in trimDatabase
V/DownloadManager( 3373): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@206ab8d3 on behalf of 3373
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
I/art     ( 1046): Explicit concurrent mark sweep GC freed 30193(1417KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 1.844ms total 84.584ms
,V/DownloadManager( 3373): DownloadService onStartCommand
,W/ContextImpl( 4327): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3373): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3373): created cursor android.database.sqlite.SQLiteCursor@2e56d309 on behalf of 3373
V/DownloadManager( 3373): processing inserted download 1
V/DownloadManager( 3373): processing inserted download 4
V/DownloadManager( 3373): processing inserted download 7
V/DownloadManager( 3373): processing inserted download 8
V/DownloadManager( 3373): processing inserted download 9
V/DownloadManager( 3373): processing inserted download 10
V/DownloadManager( 3373): processing inserted download 16
V/DownloadManager( 3373): processing inserted download 17
V/DownloadManager( 3373): processing inserted download 18
V/DownloadManager( 3373): processing inserted download 21
,V/DownloadManager( 3373): processing inserted download 22
V/WifiInternetCheck( 1046): isHttpConnectionAvailable - We got a valid response : 204
W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4327): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4327): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3373): DownloadService onDestroy
D/LGDMClient( 4327): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2319): [AccountUtils] Account not ready
W/Kids    ( 2319): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2319): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2319): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
I/LgeMiscReceiver( 3326): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3326): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3326): networkInfo.isConnected() = true
D/PhoneState( 3326): setPdpRejectCasuse : false
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,D/WeatherAncestor( 7240): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:2
D/Weather.Utils( 7240): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7240): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7240): 2 : This is isUpdating : false
D/WeatherAncestor( 7240): connectivity changed - connection : true
D/WeatherService( 7240): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2340bf8b
D/ForecastDataCache( 7240): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7240): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7240): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7240): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7240): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:52:2
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2319): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/QRemote ( 7007): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7007): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8101
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=71743952 [*alarm*], flags=0x0
V/FormManager( 7156): There are no updated forms. The schedule will be deleted.
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7156): Alarm would be updated, because LastCheckTime has been updated.
,V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1405): onNotificationPosted
W/Kids    ( 2319): [AccountUtils] Account not ready
W/Kids    ( 2319): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2319): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2319): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2319): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2319): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2319): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{20cf2cb7 type 2 when 113490 com.google.android.gms} when 113490
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2130): Connected
,D/GCM     ( 2130): Message class com.google.f.a.a.p
I/GAV4    ( 7258): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6872): Test app app.js loaded
I/jxcore-log( 6872): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6872): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bc66412 added. We now have 1 listener(s)
,I/chromium( 6872): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6872): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6872): 
I/CloudHub( 2193): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19988
,I/ActivityManager( 1046): Killing 6092:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1046): failed to open /acct/uid_10014/pid_6092/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 118362530791; DSPS: 4019163; Offset : -4306802608
,I/CloudHub( 2193): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2193): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 138364506043; DSPS: 4674588; Offset : -4306811233
,V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{399fdd53 type 0 when 1454986340064 com.android.vending} when 1454986340064
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{3fb2b690 type 2 when 131499 android} when 131499
V/SIM_STK ( 1046): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6236): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6236): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6236): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1046):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1046):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1046):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1046):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1046):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1046):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 158368100203; DSPS: 5330066; Offset : -4306818200
,V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{baac143 type 0 when 1454986372309 com.android.vending} when 1454986372309
,V/SIM_STK ( 1046): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6236): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6236): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6236): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/PowerManagerServiceEx( 1046): acquireWakeLockInternal: lock=71743952, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1046
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{3d13cc6d type 2 when 172460 android} when 172460
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1046): releaseWakeLockInternal: lock=71743952 [*alarm*], flags=0x0
,I/BooksSync( 6785): Starting books sync
,D/BooksSync( 6785): started syncMyEbooks
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6785): null auth token
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
W/ResourcesManager( 1405): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1405): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
W/ResourcesManager( 1405): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1405): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
W/ApiaryClient( 6785): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7099186396345167722&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6785): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
,W/ApiaryClient( 6785): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7099186396345167722&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1046): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1046): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1046): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1046): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1046): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1405): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1405): handleNotificationPosted(true)
D/QuickCircle( 1405): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1405): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): post do just update job
D/LgeQuickCoverNotificationData( 1405): showAll3
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1405): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1405): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6785): Authentication error
E/BooksAccountManager( 6785): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6785): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6785): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6785): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6785): null auth token
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{313f130d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6785): Error response from books API: {
W/ApiaryClient( 6785):  "error": {
W/ApiaryClient( 6785):   "errors": [
W/ApiaryClient( 6785):    {
W/ApiaryClient( 6785):     "domain": "global",
W/ApiaryClient( 6785):     "reason": "required",
W/ApiaryClient( 6785):     "message": "Login Required",
W/ApiaryClient( 6785):     "locationType": "header",
W/ApiaryClient( 6785):     "location": "Authorization"
W/ApiaryClient( 6785):    }
W/ApiaryClient( 6785):   ],
W/ApiaryClient( 6785):   "code": 401,
W/ApiaryClient( 6785):   "message": "Login Required"
W/ApiaryClient( 6785):  }
W/ApiaryClient( 6785): }
,W/ApiaryClient( 6785): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7099186396345167722&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6785): Headers:
W/ApiaryClient( 6785): accept-encoding: [gzip]
W/ApiaryClient( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6785): gdata-version: 2
,E/BooksSync( 6785): Soft error: 
E/BooksSync( 6785): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7099186396345167722&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6785): Headers:
E/BooksSync( 6785): accept-encoding: [gzip]
E/BooksSync( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6785): gdata-version: 2
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6785): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6785): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6785): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6785): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6785): {
E/BooksSync( 6785):  "error": {
E/BooksSync( 6785):   "errors": [
E/BooksSync( 6785):    {
E/BooksSync( 6785):     "domain": "global",
E/BooksSync( 6785):     "reason": "required",
E/BooksSync( 6785):     "message": "Login Required",
E/BooksSync( 6785):     "locationType": "header",
E/BooksSync( 6785):     "location": "Authorization"
E/BooksSync( 6785):    }
E/BooksSync( 6785):   ],
E/BooksSync( 6785):   "code": 401,
E/BooksSync( 6785):   "message": "Login Required"
E/BooksSync( 6785):  }
E/BooksSync( 6785): }
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6785): 	... 8 more
,E/BooksSync( 6785): Sync error
E/BooksSync( 6785): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6785): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7099186396345167722&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6785): Headers:
E/BooksSync( 6785): accept-encoding: [gzip]
E/BooksSync( 6785): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6785): gdata-version: 2
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6785): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6785): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6785): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6785): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6785): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6785): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6785): {
E/BooksSync( 6785):  "error": {
E/BooksSync( 6785):   "errors": [
E/BooksSync( 6785):    {
E/BooksSync( 6785):     "domain": "global",
E/BooksSync( 6785):     "reason": "required",
E/BooksSync( 6785):     "message": "Login Required",
E/BooksSync( 6785):     "locationType": "header",
E/BooksSync( 6785):     "location": "Authorization"
E/BooksSync( 6785):    }
E/BooksSync( 6785):   ],
E/BooksSync( 6785):   "code": 401,
E/BooksSync( 6785):   "message": "Login Required"
E/BooksSync( 6785):  }
E/BooksSync( 6785): }
E/BooksSync( 6785): 
E/BooksSync( 6785): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6785): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6785): 	... 8 more
I/BooksSync( 6785): Finished books sync
D/SyncManager( 1046): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 170671, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 178370001392; DSPS: 5985488; Offset : -4306808893
,I/[SystemUI]LGPowerUI( 1462): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1462): On Skip Timer : true
,D/LEDHandler( 1966): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1966): Battery Level Remaining: 100%
D/LEDHandler( 1966): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1462): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
D/WifiController( 1046): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1462): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1462): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1046): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1046): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3787): Disconnected process message: 10, size: 0
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4327): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{3cda747c type 0 when 1454986395620 com.android.vending} when 1454986395620
,V/SIM_STK ( 1046): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6236): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6236): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6236): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 198371485188; DSPS: 6640897; Offset : -4306820561
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{32b21afe type 2 when 202578 android} when 202578
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 218373122315; DSPS: 7296310; Offset : -4306800918
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{3883125f type 2 when 186771 com.google.android.gms} when 186771
,V/AlarmManager( 1046): ELAPSED_WAKEUP set : Alarm{13e1f4ac type 2 when 207737 android} when 207737
,V/AlarmManager( 1046): RTC_WAKEUP set : Alarm{1590e90a type 0 when 1454986427896 com.android.vending} when 1454986427896
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1046): Menu title from STK is T-Mobile
,I/VacuumService( 2130): Vacuum at: now=1454986438798 tag=VacuumService
I/GoogleURLConnFactory( 2130): Using platform SSLCertificateSocketFactory
,W/Uploader( 2130): No account for auth token provided
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6236): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6236): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6236): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2130): No account for auth token provided
,W/Uploader( 2130): No account for auth token provided
,W/Uploader( 2130): No account for auth token provided
,W/Uploader( 2130):  no longer exists, so no auth token.
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
,I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
,I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1046): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1046): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1046): tsOffsetIs: Apps: 238374757412; DSPS: 7951724; Offset : -4306813745
,I/jxcore-log( 6872): --= Surplus to requirements =--
I/jxcore-log( 6872): 
I/jxcore-log( 6872): ****TEST TOOK:  ms ****
I/jxcore-log( 6872): 
I/jxcore-log( 6872): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6872): 
,D/AndroidRuntime( 7510): 
D/AndroidRuntime( 7510): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7510): CheckJNI is OFF
D/AndroidRuntime( 7510): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1046): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1046): Killing 6872:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1046): Skipping PackageSetting{2cab6f12 com.example.hello/10319} due to missing metadata
,I/WindowState( 1046): WIN DEATH: Window{3082548b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1046): Client connection lost with reason: 4
,D/InputDispatcher( 1046): Window went away: Window{3082548b u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1046):   Force finishing activity ActivityRecord{16476bb4 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  333): DFP En is all cleared set to be enabled
,I/ActivityManager( 1046): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1046):   Force finishing activity ActivityRecord{16476bb4 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1046): Duplicate finish request for ActivityRecord{16476bb4 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1046): Spurious death for ProcessRecord{d1c9512 6872:com.test.thalitest/u0a311}, curProc for 6872: null
I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{3f4cf815 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{1c9a372a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1462): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2040): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,D/LIA_MrGDBLogger_PackageInfoDetector( 3706): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1046): Reconfiguring input devices.  changes=0x00000010
W/System.err( 4583): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4583): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4583): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4583): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4583): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4583): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4583): 	at android.os.Looper.loop(Looper.java:135)
,D/PostponalbeReceiver( 6466): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4583): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4583): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4583): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[SystemUI]QSlideListController( 1462): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 1046): Explicit concurrent mark sweep GC freed 39013(2016KB) AllocSpace objects, 9(784KB) LOS objects, 33% free, 44MB/66MB, paused 1.979ms total 157.322ms
I/art     ( 1046): WaitForGcToComplete blocked for 146.957ms for cause Explicit
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1462): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1462): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,V/SIM_STK ( 1046): Menu title from STK is T-Mobile
I/art     ( 4634): Explicit concurrent mark sweep GC freed 15077(877KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 5.695ms total 191.255ms
,D/SplitUIManager( 1883): split_name #11 / not available #0
D/SplitUIService( 1883): removed split : 
,I/art     ( 1046): Explicit concurrent mark sweep GC freed 2548(135KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 5.032ms total 97.056ms
,I/art     ( 1046): WaitForGcToComplete blocked for 248.192ms for cause Explicit
W/GeofencerStateMachine( 1825): Ignoring removeGeofence because network location is disabled.
D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
D/administrator( 1046): Handling package changes for user 0
,I/ActivityManager( 1046): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7543 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1930): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000003)
V/SIM_STK ( 1046): Menu title from STK is T-Mobile
V/SIM_STK ( 1046): Menu title from STK is T-Mobile
,I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
,D/ActionManagerService( 1930): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3706): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/AppUp4:PreloadHelper( 7099): added Exclude : com.test.thalitest
,V/BoardContentProvider( 3706): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1046): Menu title from STK is T-Mobile
I/LockScreenSettings( 7543): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/ActivityManager( 1046): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7560 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ActivityManager( 1046): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [-] updateMediaPlayerInfo
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2082): , create_time: 1430558575574
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2082): , create_time: 1430558575600
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2082): , create_time: 1454599633839
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/KeyguardModel( 1462): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1462): createShortcutInfo...
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1462): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1462): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1462): createShortcutInfo...
,D/KeyguardModel( 1462): handleShortcutListChanged...
D/KeyguardModel( 1462): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1462): createShortcutInfo...
I/SystemUI[Framework]( 1046): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1046): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1046): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1046): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f443c8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1046): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1462): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1462): createShortcutInfo...
,W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1462): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1462): createShortcutInfo...
W/ResourceType( 1462): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1462): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1462): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1462): createShortcutInfo...
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1046): Killing 2193:com.lge.music/u0a34 (adj 15): empty #17
I/NotificationService( 1046): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1046): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1046): Receieved: android.intent.action.PACKAGE_REMOVED
,V/AudioFlinger(  315): 2193 died, releasing its sessions
V/AudioFlinger(  315):  pid 1860 @ 0
V/AudioFlinger(  315):  pid 3326 @ 1
V/AudioFlinger(  315):  pid 3326 @ 2
I/art     ( 1046): Explicit concurrent mark sweep GC freed 7209(402KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.527ms total 187.490ms
,D/KeyguardModel( 1462): handleShortcutListChanged...
,W/libprocessgroup( 1046): failed to open /acct/uid_10034/pid_2193/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1462): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1046): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
I/[SystemUI]NavigationThemeResource( 1462): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1462):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1462): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 7510): Shutting down VM
,W/ResourcesManager( 7560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7560): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7560): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7560): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7560): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1046): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SystemConfig( 7560): BUILD Country: EU
I/SystemConfig( 7560): BUILD Operator: OPEN
W/ResourceType( 1046): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline( 1046): Timeline: Activity_windows_visible id: ActivityRecord{16a63115 u0 com.lge.launcher2/.Launcher t3} time:250753
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager( 1046): Killing 6981:com.lge.sync/1000 (adj 15): empty #17
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2616): onStartCommand(). Type : 8
D/[Concierge]Service( 2616): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2082): change position of spinner
,D/[Concierge]Service( 2616): Update widget ID : 11
W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6981/cgroup.procs: No such file or directory
I/SystemConfig( 7560): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7560): existFile = false
I/SystemConfig( 7560): canReadFile = false
I/SystemConfig( 7560): systemFeature RCS result false
D/SystemConfig( 7560): refreshRcsSupport() :false
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1454986460817
,D/[Concierge]Service( 2616): onStartCommand(). Type : 0
I/PackageChangeReceiver( 7131): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2156): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1046): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7585 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 622537327
,D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2c142517
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1454986238055, New one : 1454986460817
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7585): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7585): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7585): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7585): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@b7191be time:251011
,I/AppConfig( 7585): Total System Memory = 2995761152
,D/SystemHelper( 7585): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7585): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,I/ActivityManager( 1046): Killing 6945:com.android.settings/1000 (adj 15): empty #17
W/libprocessgroup( 1046): failed to open /acct/uid_1000/pid_6945/cgroup.procs: No such file or directory
,D/LIA_Service_NativeEventReceiver( 2040): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2040): startLIAService() : Trying to start LIA service ...
D/LIA_Service_LIAService( 2040): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6466): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
