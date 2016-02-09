#### Test 583805004f2b042_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
W/GAV2    ( 6639): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6639): Created application version: 3.2.35 (30235)
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BooksSync( 6639): Starting books sync
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1405): onNotificationPosted
D/SmartCoverUpdateMonitor( 1405): received broadcast com.lge.intent.action.NLDataPosted
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{12c46dc1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 89522, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1038): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 166145, reason: 10019
D/BooksSync( 6639): started syncMyEbooks
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6688): 
D/AndroidRuntime( 6688): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/AndroidRuntime( 6688): CheckJNI is OFF
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1405): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
E/BooksAccountManager( 6639): Authentication error
E/BooksAccountManager( 6639): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6639): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6639): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6639): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{12c46dc1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 6688): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1966): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{15ea7e3b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{15ea7e3b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  331): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6710 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6688): Shutting down VM
W/ApiaryClient( 6639): Error response from books API: {
W/ApiaryClient( 6639):  "error": {
W/ApiaryClient( 6639):   "errors": [
W/ApiaryClient( 6639):    {
W/ApiaryClient( 6639):     "domain": "global",
W/ApiaryClient( 6639):     "reason": "required",
W/ApiaryClient( 6639):     "message": "Login Required",
W/ApiaryClient( 6639):     "locationType": "header",
W/ApiaryClient( 6639):     "location": "Authorization"
W/ApiaryClient( 6639):    }
W/ApiaryClient( 6639):   ],
W/ApiaryClient( 6639):   "code": 401,
W/ApiaryClient( 6639):   "message": "Login Required"
W/ApiaryClient( 6639):  }
W/ApiaryClient( 6639): }
W/ApiaryClient( 6639): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6639): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-649405499603632572&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6639): Headers:
W/ApiaryClient( 6639): accept-encoding: [gzip]
W/ApiaryClient( 6639): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6639): gdata-version: 2
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{6508813 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{b71ea50 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6710): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6710): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6710): Loading: webviewchromium
I/LibraryLoader( 6710): Time to load native libraries: 4 ms (timestamps 2360-2364)
I/LibraryLoader( 6710): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6710): Binding Chromium to main looper Looper (main, tid 1) {11ff0c83}
I/LibraryLoader( 6710): Expected native library version number "",actual native library version number ""
I/chromium( 6710): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6710): Initializing chromium process, renderers=0
W/art     ( 6710): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  314): registerClient() client 0xb1243ce0, uid 10311
W/chromium( 6710): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6710): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6710): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fcdf0ed:true
I/Adreno-EGL( 6710): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6710): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6710): Build Date: 12/12/14 금
I/Adreno-EGL( 6710): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6710): Remote Branch: 
I/Adreno-EGL( 6710): Local Patches: 
I/Adreno-EGL( 6710): Reconstruct Branch: 
W/chromium( 6710): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6710): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6710): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6710): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6710): CordovaWebView is running on device made by: LGE
W/art     ( 6710): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6710): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6710): Render dirty regions requested: true
I/OpenGLRenderer( 6710): Initialized EGL, version 1.4
D/OpenGLRenderer( 6710): Enabling debug mode 0
D/Atlas   ( 6710): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{199d88ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1456): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38feee31,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6710): LgDataFeature() Constructor: none
D/LgDataFeature( 6710): LgDataFeature() Constructor Done, null
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +591ms (total +722ms)
I/Timeline( 6710): Timeline: Activity_idle id: android.os.BinderProxy@38c1c73 time:102797
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{23efe958 u0 com.test.thalitest/.MainActivity t4} time:102797
I/chromium( 6710): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6710): 
D/JsMessageQueue( 6710): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6710): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6710): 
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
E/BooksAccountManager( 6639): Authentication error
E/BooksAccountManager( 6639): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6639): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6639): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6639): null auth token
D/jxcore_app_log( 6710): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435206912
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{12c46dc1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/chromium( 6710): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ApiaryClient( 6639): Error response from books API: {
W/ApiaryClient( 6639):  "error": {
W/ApiaryClient( 6639):   "errors": [
W/ApiaryClient( 6639):    {
W/ApiaryClient( 6639):     "domain": "global",
W/ApiaryClient( 6639):     "reason": "required",
W/ApiaryClient( 6639):     "message": "Login Required",
W/ApiaryClient( 6639):     "locationType": "header",
W/ApiaryClient( 6639):     "location": "Authorization"
W/ApiaryClient( 6639):    }
W/ApiaryClient( 6639):   ],
W/ApiaryClient( 6639):   "code": 401,
W/ApiaryClient( 6639):   "message": "Login Required"
W/ApiaryClient( 6639):  }
W/ApiaryClient( 6639): }
,W/ApiaryClient( 6639): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6639): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-649405499603632572&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6639): Headers:
W/ApiaryClient( 6639): accept-encoding: [gzip]
W/ApiaryClient( 6639): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6639): gdata-version: 2
E/GBMv2   (  331): DFP En is all cleared set to be enabled
E/GBMv2   (  331): Set value is all cleared set the max
I/GBMv2   (  331): DFP Enabled. Ignore VFP set
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1405): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1405): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6639): Authentication error
E/BooksAccountManager( 6639): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6639): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6639): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6639): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1405): Notification difference=198
D/QuickStatusbarLayout( 1405): child = android.widget.LinearLayout{12c46dc1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/HttpHelper( 6639): null auth token
W/ApiaryClient( 6639): Error response from books API: {
W/ApiaryClient( 6639):  "error": {
W/ApiaryClient( 6639):   "errors": [
W/ApiaryClient( 6639):    {
W/ApiaryClient( 6639):     "domain": "global",
W/ApiaryClient( 6639):     "reason": "required",
W/ApiaryClient( 6639):     "message": "Login Required",
W/ApiaryClient( 6639):     "locationType": "header",
W/ApiaryClient( 6639):     "location": "Authorization"
W/ApiaryClient( 6639):    }
W/ApiaryClient( 6639):   ],
W/ApiaryClient( 6639):   "code": 401,
W/ApiaryClient( 6639):   "message": "Login Required"
W/ApiaryClient( 6639):  }
W/ApiaryClient( 6639): }
W/ApiaryClient( 6639): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6639): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-649405499603632572&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6639): Headers:
W/ApiaryClient( 6639): accept-encoding: [gzip]
W/ApiaryClient( 6639): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6639): gdata-version: 2
W/jxcore-log( 6710): Initializing JXcore engine
W/jxcore-log( 6710): JXcore engine is ready
W/Thread-799( 6772): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10326]" dev="sockfs" ino=10326 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6772): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-799( 6772): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9852]" dev="sockfs" ino=9852 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-799( 6772): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-799( 6772): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31614]" dev="sockfs" ino=31614 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6710): Starting JXcore engine
W/jxcore-log( 6710): Platform android
W/jxcore-log( 6710): 
W/jxcore-log( 6710): Process ARCH arm
W/jxcore-log( 6710): 
,I/jxcore-log( 6710): JXcore Cordova bridge is ready!
I/jxcore-log( 6710): 
W/jxcore-log( 6710): JXcore engine is started
,I/jxcore-log( 6710): Toggling radios to true
I/jxcore-log( 6710): 
,D/BluetoothAdapter( 6710): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=6710, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=6710, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=6710, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [105,364,164 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=6710, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6710): Radios toggled
I/jxcore-log( 6710): 
I/jxcore-log( 6710): My device name is: LGE-LG-D855
I/jxcore-log( 6710): 
,I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
E/BooksSync( 6639): Soft error: 
E/BooksSync( 6639): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6639): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-649405499603632572&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6639): Headers:
E/BooksSync( 6639): accept-encoding: [gzip]
E/BooksSync( 6639): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6639): gdata-version: 2
E/BooksSync( 6639): 
E/BooksSync( 6639): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6639): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6639): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6639): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6639): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6639): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6639): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6639): {
E/BooksSync( 6639):  "error": {
E/BooksSync( 6639):   "errors": [
E/BooksSync( 6639):    {
E/BooksSync( 6639):     "domain": "global",
E/BooksSync( 6639):     "reason": "required",
E/BooksSync( 6639):     "message": "Login Required",
E/BooksSync( 6639):     "locationType": "header",
E/BooksSync( 6639):     "location": "Authorization"
E/BooksSync( 6639):    }
E/BooksSync( 6639):   ],
E/BooksSync( 6639):   "code": 401,
E/BooksSync( 6639):   "message": "Login Required"
E/BooksSync( 6639):  }
E/BooksSync( 6639): }
E/BooksSync( 6639): 
E/BooksSync( 6639): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6639): 	... 8 more
E/BooksSync( 6639): Sync error
E/BooksSync( 6639): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6639): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-649405499603632572&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-and,roid-app
E/BooksSync( 6639): Headers:
E/BooksSync( 6639): accept-encoding: [gzip]
E/BooksSync( 6639): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6639): gdata-version: 2
E/BooksSync( 6639): 
E/BooksSync( 6639): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6639): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6639): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6639): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6639): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6639): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6639): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6639): {
E/BooksSync( 6639):  "error": {
E/BooksSync( 6639):   "errors": [
E/BooksSync( 6639):    {
E/BooksSync( 6639):     "domain": "global",
E/BooksSync( 6639):     "reason": "required",
E/BooksSync( 6639):     "message": "Login Required",
E/BooksSync( 6639):     "locationType": "header",
E/BooksSync( 6639):     "location": "Authorization"
E/BooksSync( 6639):    }
E/BooksSync( 6639):   ],
E/BooksSync( 6639):   "code": 401,
E/BooksSync( 6639):   "message": "Login Required"
E/BooksSync( 6639):  }
E/BooksSync( 6639): }
E/BooksSync( 6639): 
E/BooksSync( 6639): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6639): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6639): 	... 8 more
I/BooksSync( 6639): Finished books sync
V/NativeCrypto( 2119): Read error: ssl=0xaa6d7200: I/O error during system call, Connection timed out
,D/DhcpStateMachine( 1038): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2119): SSL shutdown failed: ssl=0xaa6d7200: I/O error during system call, Broken pipe
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [105,501,911 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105504
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105504
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 0
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  309): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79660, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105547  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=105548  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1038): Killing 6020:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524292
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105562  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6020/cgroup.procs: No such file or directory
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/WifiHS20( 1038): hidePasspointNotification off =false
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=105627  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 6797): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6797): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-193ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6797): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6797): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6797): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6797): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6797): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6797): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6833 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6041:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6041/cgroup.procs: No such file or directory
,I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6833): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 6797): LgDataFeature() Constructor: none
D/LgDataFeature( 6797): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6854 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1038): Killing 6415:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6415/cgroup.procs: No such file or directory
,W/ResourcesManager( 6854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6854): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....,
,I/GAV2    ( 6639): Thread[GAThread,5,main]: No campaign data found.
,D/QRemote ( 6854): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6854): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6854): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6854): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6854): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6854): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6854): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6833): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6854): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6833): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6833): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 6854): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6854): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6854): LgDataFeature() Constructor: none,
,D/LgDataFeature( 6854): LgDataFeature() Constructor Done, null
V/SoundPool( 6854): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6854): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6854): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6854): doLoad: loading sample sampleID=1
I/QRemote ( 6854): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6575): QS Service created
D/QRemote ( 6854): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/SoundPool( 6854): Start decode
V/MediaPlayer[Native]( 6854): decode(31, 10857164, 17813)
,V/MediaPlayerService(  314): decode(24, 10857164, 17813)
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
V/AudioCache(  314): notify(0xb1432380, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6575): Service initServices...
D/UEI.SmartControl( 6575): QS start get config
E/QRemote ( 6854): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6854): Create singleton instance
,V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
,V/AwesomePlayer(  314): initAudioDecoder() 
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1a0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1f0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a240 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a290 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a2e0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a380 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a510 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a830 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() ,mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb1432380, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb1432380, 1, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971247328
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971247488
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971247888
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2971248688
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a510 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a380 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb119a2e0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb1432380, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab602000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab603000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab604000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab605000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab606000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab607000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab608000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab609000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60a000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60b000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60c000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60d000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60e000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab60f000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab610000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab611000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab612000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab613000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab614000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab615000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab616000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab617000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab618000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab619000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61a000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61b000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61c000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61d000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61e000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab61f000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab620000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab621000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab622000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab623000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab624000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab625000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab626000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab627000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab628000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab629000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62a000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62b000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62c000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62d000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62e000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab62f000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab630000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab631000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab632000, 0xb57ec000, 4096)
V/AudioCache(  314): write(0xb57ec000, 4096)
V/AudioCache(  314): memcpy(0xab633000, 0xb57ec000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb57ec000, 280)
V/AudioCache(  314): memcpy(0xab634000, 0xb57ec000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb1432380, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb1432380, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1432380, 8, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a290 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a240 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1f0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1a0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a2e0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a380 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb119a510 on port 1
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
V/SoundPool( 6854): close(31)
V/SoundPool( 6854): pointer = 0x9ff36000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6854): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7780
I/MusicWidget( 2602): mDelayedStopHandler : unbind
,I/MusicBrowser( 2198): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2198): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2198): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2198): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2198): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2198): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1038):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@321fb92ecom.lge.music.MediaPlaybackService$5@29820ccf
D/MusicBrowser( 2198): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2a06ccf5
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2198): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2198): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2198): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2198): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2198): reset
V/MediaPlayer[Native]( 2198): setListener
V/MediaPlayer[Native]( 2198): disconnect
V/MediaPlayer[Native]( 2198): destructor
V/AudioFlinger(  314): releasing 13 from 2198 for -1
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
V/MediaPlayer[Native]( 2198): disconnect
D/MusicBrowser( 2198): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2198): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2198): [SmartShareManagerClient] smartshare client enabled
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{77ee56 type 0 when 1455035807836 android} when 1455035807836
I/MusicBrowser( 2198): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2198): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2198): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2198): [SmartShareManagerClient] unregisterListener: 56669788
W/SmartShareClient( 2198): [SmartShareManagerClient] unregisterListener invalid listener: 56669788
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):5 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:42702] from screen [on:0 period:-958104253]
,I/SmartShareClient( 2198): [SmartShareManagerClient] terminate service: 2198/MediaPlaybackService/301927555
E/HomeCloudIF( 2198): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2198): [SmartShareManagerClient] unbindService context:android.app.Application@ee5dd65
V/CloudHub( 2198): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2198): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2198): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2198): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2198): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
,W/ContextImpl( 4498): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/UEI.SmartControl( 6575): Supports setup maps: true
,D/UEI.SmartControl( 6575): QS start statue = true Error code = 0
I/UEI.SmartControl( 6575): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6575): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6575): ### init IR Blaster...
D/serial_port( 6575): Configuring serial port
E/UEI.SmartControl( 6575): UEIBLaster setting for 616
I/UEI.SmartControl( 6575): Setting serial record hearder size = 2
I/UEI.SmartControl( 6575): configuring settings for MAXQ616
I/UEI.SmartControl( 6575): Get version...
D/UEI.SmartControl( 6575): serial port data available: 21
,D/UEI.SmartControl( 6575): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6575): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6575): QS saving settings...
,D/UEI.SmartControl( 6575): IR Blaster version: 25672567
D/UEI.SmartControl( 6575): serial port data available: 4
,I/UEI.SmartControl( 6575): Device manager: loading config....
,D/UEI.SmartControl( 6575): ----------- loading internal config...
W/ContextImpl( 6575): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6575): Services init done
D/UEI.SmartControl( 6575): QS Service init finished
D/UEI.SmartControl( 6575): QS Service version name: 2.1.91
D/UEI.SmartControl( 6575): QS Service version code: 201091
D/UEI.SmartControl( 6575): Service requested: Control
E/UEI.SmartControl( 6575): Loading SETTINGS...
D/UEI.SmartControl( 6575): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6575): -- Open brand translation xml: brands_translations_ko
,D/UEI.SmartControl( 6575): Internal service binding...
I/QRemote ( 6854): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6575): ------ IControl API: 11
D/UEI.SmartControl( 6575): File observer start...
E/UEI.SmartControl( 6575): IR Port is disabled: false
D/UEI.SmartControl( 6575): Starting file observer...
I/UEI.SmartControl( 6575): Registering callback...
I/UEI.SmartControl( 6575): ------ IControl API: 19
I/UEI.SmartControl( 6575): Registering Services Ready callback...
I/UEI.SmartControl( 6575): Notify client services are ready...
,I/QRemote ( 6854): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6854): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6854): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
I/UEI.SmartControl( 6575): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6575): -----service ready thread exits
D/QRemote ( 6854): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
I/QRemote ( 6854): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6854): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6575): ------ IControl API: 8
D/QRemote ( 6854): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6854): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6854): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6854): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6854): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,D/QRemote ( 6854): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6854): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6854): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6854): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6854): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 6854): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6854): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6854): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455035809321]
D/QRemote ( 6854): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6090:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 46260(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.481ms total 68.945ms
,D/QRemote ( 6854): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/ActivityManager( 1038): Killing 6064:com.android.gallery3d/u0a27 (adj 15): empty #18
W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6090/cgroup.procs: No such file or directory
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6064/cgroup.procs: No such file or directory
V/QRemote ( 6854): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6854): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6854): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2672): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107628  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=107638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2672): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107729  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=107730  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107730
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107730
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107731
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107731
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=107731
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107731  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6797): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6797): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6797): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/wpa_supplicant( 2672): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=107746  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6797): [AUTORUN] getUsbConnected() : connected=true
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : availableList=[wlan0]
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6797): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6797): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6797): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107754  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=107754  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107755
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=107755
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1038): Got NetworkAgent Messenger
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107799  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107800  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=107800  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107801  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107802  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=107802  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@202826e1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@202826e1 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1966): handleWifiStateChangedEvent: 1
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/Netd    (  309): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supporte,d: null
W/dsqn    ( 6930): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6930): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 6930): DSQN ssw
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6854): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6854): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6854): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6854): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6833): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6833): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6797): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6797): MCCMNC not supported: null
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
D/QRemote ( 6854): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6854): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6854): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6854): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6854): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
,D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:36:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455035810105], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455035810084]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6937): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6937): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 6937): version 5.5.6 starting
E/dhcpcd  ( 6937): get_duid: m
D/dhcpcd  ( 6937): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6937): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6937): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6937): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6937): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6937): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6937): wlan0: sending REQUEST (xid 0xc1445fe), next in 3.86 seconds
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5409): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5409): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6962 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6962): onCreate
W/AppUp4:DB( 6962):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6962):  setFingerPrint start
I/AppUp4:DB( 6962):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6962):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6962):  SDK version = 21
I/AppUp4:DB( 6962):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6962): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6962): onReceive
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524295
,D/LgDataFeature( 6962): LgDataFeature() Constructor: none
,D/LgDataFeature( 6962): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6962): Context : android.app.ReceiverRestrictedContext@13e50639
D/AppUp4:CustFacade( 6962): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6962): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6962): begin check event
I/AppUp4:CustModeStarterReceiver( 6962): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6962): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6962): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6962): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6962): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6457:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6457/cgroup.procs: No such file or directory
,D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3362): DownloadService onCreate
,D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6990 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@388e7e8d on behalf of 3362
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk,
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@2d490842 on behalf of 3362
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@15f17689 on behalf of 3362
,V/DownloadManager( 3362): processing inserted download 1
V/DownloadManager( 3362): processing inserted download 4
,V/DownloadManager( 3362): processing inserted download 7
V/DownloadManager( 3362): processing inserted download 8
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
,V/DownloadManager( 3362): processing inserted download 18
V/DownloadManager( 3362): processing inserted download 21
V/DownloadManager( 3362): processing inserted download 22
V/DownloadManager( 3362): DownloadService onDestroy
,W/ResourcesManager( 6990): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6990): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6990): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6990): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 6990): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6990): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6990): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 6990): LgDataFeature() Constructor: none
D/LgDataFeature( 6990): LgDataFeature() Constructor Done, null
,D/eas_req ( 6990): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7021 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6990): JNI_OnLoad()
I/HubEmail( 6990): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6990): registerNatives()
I/HubEmail( 6990): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6990): registerNativeMethods()
I/HubEmail( 6990): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6990): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1038): Killing 6108:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6108/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{71266 type 0 when 1455035811774 com.android.vending} when 1455035811774
,W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3340): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7049 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/dhcpcd  ( 6937): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 6937): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6937): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6937): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6937): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6937): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 6937): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6937): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6937): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7021): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7021): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7083 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1038): Killing 6507:com.lge.eula/1000 (adj 15): empty #17
I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6710): 
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6507/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
,V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7110 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 5949:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/art     (  341): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 11.341ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.815ms
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.872ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_5949/cgroup.procs: No such file or directory
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6130): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6130): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6130): [1] 5.onFinished: Scheduling replication attempt 2.
I/art     ( 7110): Almond Protected OAT
I/ActivityManager( 1038): Killing 6535:com.lge.bnr/1000 (adj 15): empty #17
,E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6535/cgroup.procs: No such file or directory
,D/WeatherApplication( 7110): removeAccount
,D/WeatherApplication( 7110): Account.length = 0
E/WeatherApplication( 7110): OPERATOR:OPEN
D/WeatherAncestor( 7110): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:52
,D/Weather.Utils( 7110): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7110): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7110): 2 : This is isUpdating : false
,D/WeatherAncestor( 7110): connectivity changed - connection : true
D/WeatherService( 7110): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7110): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7110): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7110): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7110): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7110): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:52
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7129 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6554:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10013/pid_6554/cgroup.procs: No such file or directory
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5409): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6710): 
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6710): 
I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6710): 
,I/WebViewFactory( 7129): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7129): Loading: webviewchromium
I/LibraryLoader( 7129): Time to load native libraries: 3 ms (timestamps 1236-1239)
I/LibraryLoader( 7129): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7129): Binding Chromium to main looper Looper (main, tid 1) {1870dc48}
I/LibraryLoader( 7129): Expected native library version number "",actual native library version number ""
I/chromium( 7129): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7129): Initializing chromium process, renderers=0
W/art     ( 7129): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7129): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7129): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7129): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb558a2a0, uid 10093
W/AudioManagerAndroid( 7129): Requires BLUETOOTH permission
I/Adreno-EGL( 7129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7129): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7129): Build Date: 12/12/14 금
I/Adreno-EGL( 7129): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7129): Remote Branch: 
I/Adreno-EGL( 7129): Local Patches: 
I/Adreno-EGL( 7129): Reconstruct Branch: 
,I/NSApplication( 7129): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7187 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 5982:com.android.providers.calendar/u0a14 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10014/pid_5982/cgroup.procs: No such file or directory
,W/ResourcesManager( 7187): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2337): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6962): onReceive
,I/art     ( 2119): Explicit concurrent mark sweep GC freed 23624(1396KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 5.042ms total 93.143ms
D/AppUp4:CustFacade( 6962): Context : android.app.ReceiverRestrictedContext@13e50639
D/AppUp4:CustFacade( 6962): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6962): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6962): begin check event
I/AppUp4:CustModeStarterReceiver( 6962): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3362): DownloadService onCreate
,I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@3a71f245 on behalf of 3362
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@b35d9a on behalf of 3362
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3362): processing inserted download 1
V/DownloadManager( 3362): processing inserted download 4
,V/DownloadManager( 3362): processing inserted download 7
I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3340): networkInfo.isConnected() = false
V/DownloadManager( 3362): processing inserted download 8
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@31fff6cb on behalf of 3362
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
V/DownloadManager( 3362): processing inserted download 18
V/DownloadManager( 3362): processing inserted download 21
D/WeatherAncestor( 7110): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:54
V/DownloadManager( 3362): processing inserted download 22
D/Weather.Utils( 7110): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7110): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7110): 2 : This is isUpdating : false
D/WeatherAncestor( 7110): connectivity changed - connection : true
D/WeatherService( 7110): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@249beddf
,D/ForecastDataCache( 7110): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7110): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7110): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7110): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7110): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:54
V/DownloadManager( 3362): DownloadService onDestroy
I/GLSActivity( 2119): [ac] getting account id
,I/GLSUser ( 2119): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2337): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/FormManager( 7021): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7021): Alarm would be updated, because LastCheckTime has been updated.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6962): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6962): onReceive
,D/AppUp4:CustFacade( 6962): Context : android.app.ReceiverRestrictedContext@13e50639
D/AppUp4:CustFacade( 6962): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6962): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6962): begin check event
I/AppUp4:CustModeStarterReceiver( 6962): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3362): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3362): DownloadService onCreate
I/DownloadManager( 3362): in removeSpuriousFiles
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@12c46dc1 on behalf of 3362
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3362): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3362): DownloadService onStartCommand
V/DownloadManager( 3362): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@3bc7d54 on behalf of 3362
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4287): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3362): in trimDatabase
V/DownloadManager( 3362): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 4287): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4287): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4287): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4287): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
V/DownloadManager( 3362): processing inserted download 1
V/DownloadManager( 3362): processing inserted download 4
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/DownloadManager( 3362): processing inserted download 7
I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3362): processing inserted download 8
W/Settings( 6990): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3340): networkInfo.isConnected() = true
D/PhoneState( 3340): setPdpRejectCasuse : false
V/DownloadManager( 3362): processing inserted download 9
V/DownloadManager( 3362): processing inserted download 10
V/DownloadManager( 3362): processing inserted download 16
V/DownloadManager( 3362): processing inserted download 17
,V/DownloadManager( 3362): created cursor android.database.sqlite.SQLiteCursor@86924fd on behalf of 3362
D/WeatherAncestor( 7110): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:54
V/DownloadManager( 3362): processing inserted download 18
V/DownloadManager( 3362): processing inserted download 21
D/Weather.Utils( 7110): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7110): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7110): 2 : This is isUpdating : false
D/WeatherAncestor( 7110): connectivity changed - connection : true
D/WeatherService( 7110): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@249beddf
V/DownloadManager( 3362): processing inserted download 22
D/ForecastDataCache( 7110): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7110): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7110): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7110): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7110): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:54
V/DownloadManager( 3362): DownloadService onDestroy
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,D/ChimeraCfgMgr( 2337): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7021): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7021): Alarm would be updated, because LastCheckTime has been updated.
I/Kids    ( 2337): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/UEI.SmartControl( 6575): Internal timer expired: 2
D/UEI.SmartControl( 6575): unbind internal service
I/art     ( 1038): Explicit concurrent mark sweep GC freed 67360(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.556ms total 79.092ms
,D/serial_port( 6575): close(fd = 24)
,I/UEI.SmartControl( 6575): Serial port is closed.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{259a710a type 2 when 113600 com.google.android.gms} when 113600
,V/QRemote ( 6854): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6854): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7780
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2119): Connected
,D/GCM     ( 2119): Message class com.google.f.a.a.p
I/GAV4    ( 7129): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6710): 
,I/ActivityManager( 1038): Killing 6639:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6639/cgroup.procs: No such file or directory
,I/CloudHub( 2198): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19988
,I/jxcore-log( 6710): Test app app.js loaded
I/jxcore-log( 6710): 
,I/chromium( 6710): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6710): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac4b27f added. We now have 1 listener(s)
,I/jxcore-log( 6710): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6710): 
I/jxcore-log( 6710): TAP version 13
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 5 should be equal
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 6 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 7 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 8 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 9 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): ok 10 should throw
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons expiration out of range lower
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 12 Expiration out of range
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons expiration out of range lower
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 13 Expiration out of range
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons no beacons returns null
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 14 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6710): 
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 117555294074; DSPS: 3992806; Offset : -4308530305
I/jxcore-log( 6710): ok 16 should be equal
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 17 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ok 18 should be equal
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): ok 19 should be equal
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): ok 20 (unnamed assert)
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # setup
I/jxcore-log( 6710): 
I/jxcore-log( 6710): # #parseBeacons with beacons both for and not for the user,
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): ok 21 (unnamed assert)
I/jxcore-log( 6710): 
,I/jxcore-log( 6710): # teardown
I/jxcore-log( 6710): 
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
,I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/LEDHandler( 1966): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1966): Battery Level Remaining: 100%
D/LEDHandler( 1966): Battery Temp: 299, mChargingStatus=5, mChargingStop=false
D/WifiController( 1038): battery changed pluggedType: 2
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3798): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=438004721, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{388c5657 type 0 when 1455035832547 com.android.vending} when 1455035832547
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=438004721 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{34597544 type 2 when 131353 android} when 131353
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6130): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6130): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6130): [1] 5.onFinished: Scheduling replication attempt 3.
,I/CloudHub( 2198): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2198): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 137557303285; DSPS: 4648232; Offset : -4308536999
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2cf98347 type 0 when 1455035853583 com.android.vending} when 1455035853583
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6130): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6130): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6130): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 157559353590; DSPS: 5303659; Offset : -4308531423
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{b6cb536 type 0 when 1455035876117 com.android.vending} when 1455035876117
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6130): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6130): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6130): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 177561957853; DSPS: 5959105; Offset : -4308551620
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 197564026752; DSPS: 6614533; Offset : -4308557994
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=438004721, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{38c4f641 type 0 when 1455035897535 com.android.vending} when 1455035897535
,D/[Concierge]Service( 2620): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=438004721 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6130): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6130): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6130): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 217566060598; DSPS: 7269959; Offset : -4308538361
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{17c7d3b type 2 when 186074 com.google.android.gms} when 186074
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{26cb7c58 type 2 when 208203 android} when 208203
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2119): Vacuum at: now=1455035935806 tag=VacuumService
,I/GoogleURLConnFactory( 2119): Using platform SSLCertificateSocketFactory
,W/Uploader( 2119): No account for auth token provided
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119):  no longer exists, so no auth token.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{378119c type 2 when 236918 android} when 236918
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 237568014966; DSPS: 7925383; Offset : -4308536988
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1966): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1966): Battery Level Remaining: 100%
D/LEDHandler( 1966): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3798): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4287): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 6710): --= Surplus to requirements =--
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ****TEST TOOK:  ms ****
I/jxcore-log( 6710): 
I/jxcore-log( 6710): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6710): 
,D/AndroidRuntime( 7363): 
D/AndroidRuntime( 7363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7363): CheckJNI is OFF
D/AndroidRuntime( 7363): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 6710:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1038): WIN DEATH: Window{199d88ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{199d88ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1038): Skipping PackageSetting{267ad4b6 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{23efe958 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  331): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{a2537a5 6710:com.test.thalitest/u0a311}, curProc for 6710: null
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{23efe958 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{23efe958 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2076): [Launcher.java:5338:onStart()]onStart
,D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{1ec55449 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2076): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1966): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1966): topRunningActivity=ActivityInfo{3329514e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2076): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2038): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,E/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3733): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
D/PostponalbeReceiver( 6364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
W/System.err( 4498): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4498): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4498): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4498): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4498): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4498): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4498): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4498): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4498): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4498): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
,I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7394 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1912): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3733): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2076): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[SystemUI]QSlideListController( 1456): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2076): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2076): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1912): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3733): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3733): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2076): , create_time: 1430558575574
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2076): , create_time: 1430558575600
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/GBoardWebViewUtils( 2076): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2076): , create_time: 1454599633839
I/GBoardWebViewUtils( 2076): , expire_time: 0
I/GBoardWebViewUtils( 2076): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2076): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2076): , display: false
I/GBoardWebViewUtils( 2076): , animation: false }
I/art     ( 4552): Explicit concurrent mark sweep GC freed 16908(943KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 451us total 170.632ms
D/WallpaperManager( 2076): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1456): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@38feee31,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 29910(1677KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.555ms total 196.564ms
I/art     ( 1038): WaitForGcToComplete blocked for 195.008ms for cause Explicit
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2076): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 6962): added Exclude : com.test.thalitest
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7414 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/LockScreenSettings( 7394): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/administrator( 1038): Handling package changes for user 0
,D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 2076): [Launcher.java:5349:onStop()]onStop
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] installed app name: Music
D/KeyguardModel( 1456): createShortcutInfo...
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3798): [BTUI] [-] updateMediaPlayerInfo
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
,W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 7414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourcesManager( 7414): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7414): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7414): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7414): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1456): handleShortcutListChanged...
D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
,I/ActivityManager( 1038): Killing 2198:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  314): 2198 died, releasing its sessions
V/AudioFlinger(  314):  pid 1859 @ 0
V/AudioFlinger(  314):  pid 3340 @ 1
V/AudioFlinger(  314):  pid 3340 @ 2
,I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2076): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 7645(411KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.815ms total 216.593ms
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7414): BUILD Country: EU
I/SystemConfig( 7414): BUILD Operator: OPEN
I/[Concierge]WidgetView( 2076): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1456): handleShortcutListChanged...
D/MediaSessionService( 1038): clear user.mLastMediaButtonReceiver
,D/PhoneStatusBar( 1456): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2198/cgroup.procs: No such file or directory
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{50b3d49 u0 com.lge.launcher2/.Launcher t3} time:250977
D/[Concierge]Service( 2620): onStartCommand(). Type : 8
D/[Concierge]Service( 2620): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2620): Update widget ID : 11
D/[Concierge]WidgetView( 2076): change position of spinner
,D/[Concierge]Service( 2620): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2076): initWebView(). Time : 1455035953065
I/ActivityManager( 1038): Killing 6833:com.lge.sync/1000 (adj 15): empty #17
D/AndroidRuntime( 7363): Shutting down VM
,I/ThermalEngine(  325): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3133): Thermal-Lib-Client: Client request sent
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6833/cgroup.procs: No such file or directory
,I/SystemConfig( 7414): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7414): existFile = false
I/SystemConfig( 7414): canReadFile = false
I/SystemConfig( 7414): systemFeature RCS result false
D/SystemConfig( 7414): refreshRcsSupport() :false
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/PackageChangeReceiver( 6990): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2178): Cleaning up data for package: com.test.thalitest
W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7439 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[Concierge]WebView( 2076): Return exist ConciergeWebView. Reuse : 969391417
D/[Concierge]WidgetView( 2076): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2076): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@986eeee
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2076): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2076): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2076): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7439): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/[Concierge]WidgetView( 2076): Widget kill message received. Destory myself. My : 1455035730143, New one : 1455035953065
D/[Concierge]WidgetView( 2076): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2076): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2076): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppConfig( 7439): Total System Memory = 2995761152
,D/SystemHelper( 7439): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/ActivityManager( 1038): Killing 6797:com.android.settings/1000 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2076): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2076): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2076): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2076): Timeline: Activity_idle id: android.os.BinderProxy@3c79cfa2 time:251205
,D/LIA_Service_NativeEventReceiver( 2038): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2038): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6797/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2038): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 6364): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7461 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/chromium( 2076): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
E/SQLiteDatabase( 7461): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 7461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7461): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 7461): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7461): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7461): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7461): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7461): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7461): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7461): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 7461): Unable to open database for writing.
E/LifetrackerProvider2( 7461): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 7461): 	at android.data,base.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 7461): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 7461): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 7461): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 7461): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 7461): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 7461): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 7461): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 7461): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 7461): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 7461): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 7461): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 7461): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 7461): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)

```
