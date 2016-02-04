#### Test 58259810381ca4f_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2a6030f8 type 2 when 101838 android} when 101838
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6765 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
I/art     ( 1038): Explicit concurrent mark sweep GC freed 16637(839KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.662ms total 150.255ms
D/AndroidRuntime( 6773): 
D/AndroidRuntime( 6773): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6773): CheckJNI is OFF
I/ReaderUtils( 6765): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6773): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/GAV2    ( 6765): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3ec82f79 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3ec82f79 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  336): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6809 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6773): Shutting down VM
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
I/BooksApp( 6765): Created application version: 3.2.35 (30235)
D/ContactsSyncAdapter( 2121): innerSync failed
D/ContactsSyncAdapter( 2121): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2121): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2121): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2121): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2121): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 90263, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1038): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 167026, reason: 10019
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1858): Display #0 changed.
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{1ffee892 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{3d51b263 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/BooksSync( 6765): Starting books sync
D/ContextHelper( 6809): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6809): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6809): Loading: webviewchromium
I/LibraryLoader( 6809): Time to load native libraries: 3 ms (timestamps 2567-2570)
I/LibraryLoader( 6809): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6809): Binding Chromium to main looper Looper (main, tid 1) {1fcf5cc2}
I/LibraryLoader( 6809): Expected native library version number "",actual native library version number ""
,I/chromium( 6809): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6809): Initializing chromium process, renderers=0
W/art     ( 6809): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  311): registerClient() client 0xb1427f00, uid 10311
,D/BooksSync( 6765): started syncMyEbooks
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10160504:true
W/chromium( 6809): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6809): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6809): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6809): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6809): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6809): Build Date: 12/12/14 금
I/Adreno-EGL( 6809): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6809): Remote Branch: 
I/Adreno-EGL( 6809): Local Patches: 
I/Adreno-EGL( 6809): Reconstruct Branch: 
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 6809): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6809): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 6809): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6809): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6809): CordovaWebView is running on device made by: LGE
,W/art     ( 6809): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6809): Attempt to remove local handle scope entry from IRT, ignoring
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/OpenGLRenderer( 6809): Render dirty regions requested: true
I/OpenGLRenderer( 6809): Initialized EGL, version 1.4
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
D/OpenGLRenderer( 6809): Enabling debug mode 0
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/Atlas   ( 6809): Validating map...
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
D/SplitWindow( 1038): check instance of lgWin Window{a605564 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgDataFeature( 6809): LgDataFeature() Constructor: none
D/LgDataFeature( 6809): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bbc7d3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +491ms (total +619ms)
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{2a4944be u0 com.test.thalitest/.MainActivity t4} time:102932
I/Timeline( 6809): Timeline: Activity_idle id: android.os.BinderProxy@bbc7a72 time:102933
I/chromium( 6809): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6809): 
,D/JsMessageQueue( 6809): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6809): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435215104
,I/chromium( 6809): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6809): 
,I/chromium( 6809): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3080636895982884615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6809): Initializing JXcore engine
W/jxcore-log( 6809): JXcore engine is ready
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Thread-814( 6875): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9845]" dev="sockfs" ino=9845 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-814( 6875): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-814( 6875): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8507]" dev="sockfs" ino=8507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-814( 6875): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-814( 6875): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31322]" dev="sockfs" ino=31322 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 6809): Starting JXcore engine
I/art     ( 2121): Explicit concurrent mark sweep GC freed 21184(1235KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 3.110ms total 42.576ms
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
,W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
W/ApiaryClient( 6765): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3080636895982884615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,W/jxcore-log( 6809): Platform android
W/jxcore-log( 6809): 
W/jxcore-log( 6809): Process ARCH arm
W/jxcore-log( 6809): 
,I/jxcore-log( 6809): JXcore Cordova bridge is ready!
I/jxcore-log( 6809): 
W/jxcore-log( 6809): JXcore engine is started
,I/jxcore-log( 6809): Toggling radios to true
I/jxcore-log( 6809): 
,D/BluetoothAdapter( 6809): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=6809, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=6809, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=6809, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1038): reconnect pid=6809, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6809): Radios toggled
I/jxcore-log( 6809): 
E/WifiNative: ( 1038): [105,614,915 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
I/jxcore-log( 6809): My device name is: LGE-LG-D855
I/jxcore-log( 6809): 
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
,I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6891 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  306): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2121): Read error: ssl=0xaf499600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2121): SSL shutdown failed: ssl=0xaf499600: I/O error during system call, Broken pipe
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2fe9b7e7 type 0 when 1454578956301 com.android.vending} when 1454578956301
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1038): Dns fail occured do internet check.
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [105,760,162 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 0
D/WifiHS20( 1038): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105766
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=105766
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): SET ps 1: returned true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  306): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1038): InternetcheckProgress is not set don't send DS quality intent
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=105795  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=105795  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=105801  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=105805  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524292
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 6891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
W/ResourcesManager( 6891): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/ResourcesManager( 6891): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6891): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6891): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6891): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ApiaryClient( 6765): errCount = 3: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3080636895982884615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
E/BooksSync( 6765): Soft error: 
E/BooksSync( 6765): Sync error
I/BooksSync( 6765): Finished books sync
,D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 79592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6891): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6891): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6891): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6891): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6891): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6891): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6510:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6510/cgroup.procs: No such file or directory
,I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Scheduling replication attempt 1.
,I/ActivityManager( 1038): Killing 6158:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LgDataFeature( 6891): LgDataFeature() Constructor: none
D/LgDataFeature( 6891): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6158/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6954 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1038): Killing 6181:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6181/cgroup.procs: No such file or directory
,W/ResourcesManager( 6954): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6954): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6954): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6954): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6954): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6954): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6954): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6954): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6954): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6954): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6954): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6954): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6954): LgDataFeature() Constructor: none
D/LgDataFeature( 6954): LgDataFeature() Constructor Done, null
,V/SoundPool( 6954): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6954): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6954): create sampleID=1, fd=31, offset=17813 length=10857164
,V/SoundPool( 6954): doLoad: loading sample sampleID=1
V/SoundPool( 6954): Start decode
V/MediaPlayer[Native]( 6954): decode(31, 10857164, 17813)
V/MediaPlayerService(  311): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  311): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  311): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  311): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  311): player type = 3
V/AwesomePlayer(  311): AwesomePlayer create()
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): setAudioSink() 
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb1432740, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/Utils   (  311): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  311): setDataSource_l dataSource
V/LGParserOSAL(  311): SniffLGParser start
V/LGParserOSAL(  311): MainType:5, SubType=0
V/LGParserOSAL(  311): #### check Mime : application/ogg
V/LGParserOSAL(  311): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  311): Use LGExtractor :application/ogg 
I/QRemote ( 6954): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6700): QS Service created
D/QRemote ( 6954): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 6954): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  311): supported mime: application/ogg
V/AwesomePlayer(  311): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  311): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  311): mBitrate = -1 bits/sec
V/AwesomePlayer(  311): AudioTrack Setting
V/AwesomePlayer(  311): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  311): setAudioSource() 
V/MediaPlayerService(  311): prepare
V/AwesomePlayer(  311): prepareAsync_l() 
V/MediaPlayerService(  311): wait for prepare
V/AwesomePlayer(  311): onPrepareAsyncEvent() 
V/AwesomePlayer(  311): initAudioDecoder() 
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  311): isAudioPlaybackHookOn() false
V/AwesomePlayer(  311): getUseOffload() = 0 
V/OMXCodec(  311): OMXCodec::Create
V/OMXCodec(  311): findMatchingCodecs()
V/OMXCodec(  311): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  311): matchingCodecs.size()=1
V/OMXCodec(  311): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  311): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  311): LG Codec Adapter start
V/OMXCodec(  311): OMXCodec Createtor
V/OMXCodec(  311): setComponentRole
V/OMXCodec(  311): configureCodec protected=0
V/LGCodecAdapter(  311): called getLGCodecSpecificData
V/LGCodecOSAL(  311): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMSG
V/LGCodecOSAL(  311): Not support LGCodec
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  311): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  311): Could not offload audio decode, try pcm offload
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  311): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  311): init()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  311): allocateBuffers
V/OMXCodec(  311): allocateBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder,] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ab0 on output port
V/OMXCodec(  311): init() mAsyncCompletion wait!!! 
I/UEI.SmartControl( 6700): Service initServices...
D/UEI.SmartControl( 6700): QS start get config
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/LGMDMManager( 6954): Create singleton instance
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  311): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  311): finishAsyncPrepare_l() 
V/AudioCache(  311): notify(0xb1432740, 5, 0, 0)
V/AudioCache(  311): ignored
V/AudioCache(  311): notify(0xb1432740, 1, 0, 0)
V/AudioCache(  311): prepared
V/AudioCache(  311): wait - success
V/MediaPlayerService(  311): start
V/AwesomePlayer(  311): play_l() 
V/AwesomePlayer(  311): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  311): createAudioPlayer_l
V/AwesomePlayer(  311): seekAudioIfNecessary_l() 
V/AwesomePlayer(  311): startAudioPlayer_l() 
D/AudioPlayer(  311): start of Playback, useOffload 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  311): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  311): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977264
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  311): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  311): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  311): notify(0xb1432740, 6, 0, 0)
V/AudioCache(  311): ignored
V/MediaPlayerService(  311): wait for playback complete
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf404000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf405000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf406000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf407000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf408000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf409000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40a000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40b000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40c000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40d000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40e000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf40f000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf410000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf411000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf412000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf413000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf414000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf415000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf416000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf417000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf418000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf419000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41a000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41b000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41c000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41d000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41e000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf41f000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf420000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf421000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf422000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf423000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf424000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf425000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf426000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf427000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf428000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf429000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42a000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42b000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42c000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42d000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42e000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf42f000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf430000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf431000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf432000, 0xb1230000, 4096)
,V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf433000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf434000, 0xb1230000, 4096)
V/AudioCache(  311): write(0xb1230000, 4096)
V/AudioCache(  311): memcpy(0xaf435000, 0xb1230000, 4096)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  311): postAudioEOS() 
V/AudioCache(  311): write(0xb1230000, 280)
V/AudioCache(  311): memcpy(0xaf436000, 0xb1230000, 280)
V/AwesomePlayer(  311): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  311): onStreamDone
V/AwesomePlayer(  311): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  311): notify(0xb1432740, 2, 0, 0)
V/AudioCache(  311): playback complete
V/AwesomePlayer(  311): pause_l() 
V/AudioCache(  311): wait - success
V/MediaPlayerService(  311): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  311): notify(0xb1432740, 7, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/AudioPlayer(  311): Pause Playback at 1068125
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb1432740, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/AudioPlayer(  311): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  311): AudioPlayer releasing audio source
D/AudioPlayer(  311): AudioPlayer done releasing audio source
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): ~AwesomePlayer call
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/SoundPool( 6954): close(31)
V/SoundPool( 6954): pointer = 0xa000d000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6954): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9397
I/GAV2    ( 6765): Thread[GAThread,5,main]: No campaign data found.
,I/UEI.SmartControl( 6700): Supports setup maps: true
,D/UEI.SmartControl( 6700): QS start statue = true Error code = 0
I/UEI.SmartControl( 6700): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6700): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6700): ### init IR Blaster...
D/serial_port( 6700): Configuring serial port
E/UEI.SmartControl( 6700): UEIBLaster setting for 616
I/UEI.SmartControl( 6700): Setting serial record hearder size = 2
I/UEI.SmartControl( 6700): configuring settings for MAXQ616
I/UEI.SmartControl( 6700): Get version...
D/UEI.SmartControl( 6700): serial port data available: 21
,D/UEI.SmartControl( 6700): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6700): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6700): QS saving settings...
D/UEI.SmartControl( 6700): IR Blaster version: 25672567
D/UEI.SmartControl( 6700): serial port data available: 4
,I/UEI.SmartControl( 6700): Device manager: loading config....
,W/ContextImpl( 6700): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 6700): ----------- loading internal config...
E/UEI.SmartControl( 6700): Services init done
D/UEI.SmartControl( 6700): QS Service init finished
D/UEI.SmartControl( 6700): QS Service version name: 2.1.91
D/UEI.SmartControl( 6700): QS Service version code: 201091
D/UEI.SmartControl( 6700): Service requested: Control
E/UEI.SmartControl( 6700): Loading SETTINGS...
D/UEI.SmartControl( 6700): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6700): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 6954): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6700): Internal service binding...
I/UEI.SmartControl( 6700): ------ IControl API: 11
D/UEI.SmartControl( 6700): File observer start...
E/UEI.SmartControl( 6700): IR Port is disabled: false
D/UEI.SmartControl( 6700): Starting file observer...
I/UEI.SmartControl( 6700): Registering callback...
I/UEI.SmartControl( 6700): ------ IControl API: 19
I/UEI.SmartControl( 6700): Registering Services Ready callback...
I/UEI.SmartControl( 6700): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6700): -----service ready thread exits
I/QRemote ( 6954): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6954): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6954): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6954): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6954): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6700): ------ IControl API: 8
,D/QRemote ( 6954): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6954): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6954): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6954): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6954): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6954): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6954): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6954): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6954): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6954): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454578961348]
D/QRemote ( 6954): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1038): Killing 6540:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 6954): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6540/cgroup.procs: No such file or directory
,V/QRemote ( 6954): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6954): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/MusicWidget( 2633): mDelayedStopHandler : unbind
,I/MusicBrowser( 2184): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2184): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2184): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2184): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2184): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2184): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,I/MediaFocusControl( 1038):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@26dc7279com.lge.music.MediaPlaybackService$5@3953cbbe
D/MusicBrowser( 2184): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@80e433c
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2184): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2184): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2184): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2184): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2184): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2184): reset
V/MediaPlayer[Native]( 2184): setListener
V/MediaPlayer[Native]( 2184): disconnect
V/MediaPlayer[Native]( 2184): destructor
,V/AudioFlinger(  311): releasing 13 from 2184 for -1
V/AudioFlinger(  311):  decremented refcount to 0
V/AudioFlinger(  311): purging stale effects
V/MediaPlayer[Native]( 2184): disconnect
D/MusicBrowser( 2184): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2184): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2184): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2184): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2184): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2184): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2184): [SmartShareManagerClient] unregisterListener: 62247967
W/SmartShareClient( 2184): [SmartShareManagerClient] unregisterListener invalid listener: 62247967
I/SmartShareClient( 2184): [SmartShareManagerClient] terminate service: 2184/MediaPlaybackService/533683394
,E/HomeCloudIF( 2184): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2184): [SmartShareManagerClient] unbindService context:android.app.Application@2a06f36c
V/CloudHub( 2184): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2184): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2184): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2184): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2184): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/ActivityManager( 1038): Killing 6203:com.android.gallery3d/u0a27 (adj 15): empty #17
I/wpa_supplicant( 2614): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=107874  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6203/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=107901  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{3d60b7f4 type 0 when 1454578957036 com.google.android.gms} when 1454578957036
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{14f2db1d type 0 when 1454578959860 android} when 1454578959860
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 47101(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.209ms total 163.995ms
,E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:43771] from screen [on:0 period:-1414951279]
I/EventLogService( 2346): Aggregate from 1454577156915 (log), 1454577156915 (data)
,W/ContextImpl( 4576): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1038): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5944): type=WIFI subType= reason=null isConnected=false
I/NetworkMonitor( 5944): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7021 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7021): onCreate
W/AppUp4:DB( 7021):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7021):  setFingerPrint start
I/AppUp4:DB( 7021):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7021):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7021):  SDK version = 21
I/AppUp4:DB( 7021):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7021): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7021): onReceive
D/LgDataFeature( 7021): LgDataFeature() Constructor: none
D/LgDataFeature( 7021): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7021): Context : android.app.ReceiverRestrictedContext@1479d610
D/AppUp4:CustFacade( 7021): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7021): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7021): begin check event
I/AppUp4:CustModeStarterReceiver( 7021): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7021): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7021): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7021): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7021): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6232:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6232/cgroup.procs: No such file or directory
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7052 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 7052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7052): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7052): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7052): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 7052): LgDataFeature() Constructor: none
D/LgDataFeature( 7052): LgDataFeature() Constructor Done, null
D/eas_req ( 7052): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7078 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7052): JNI_OnLoad()
I/HubEmail( 7052): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7052): registerNatives()
I/HubEmail( 7052): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7052): registerNativeMethods()
I/HubEmail( 7052): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7052): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  344): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 24.680ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 427us total 19.794ms
,I/ActivityManager( 1038): Killing 6575:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.575ms
W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6575/cgroup.procs: No such file or directory
,W/Settings( 7052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7106 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7078): Network not available. Please check & try again.
V/FormManager( 7078): Network unavailable.
V/FormManager( 7078): Network unavailable.
,I/ActivityManager( 1038): Killing 6256:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState ASSOCIATION_REJECTION_EVENT 25 1 c0:ff:d4:d3:aa:48 blacklist=false rt=109935
E/WifiStateMachine( 1038):  ConnectModeState ASSOCIATION_REJECTION_EVENT 25 1 c0:ff:d4:d3:aa:48 blacklist=false rt=109935
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=109935  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6256/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=109942  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7126 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6633:com.lge.eula/1000 (adj 15): empty #17
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=110033  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6809): 
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6633/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=110141  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7143 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6092:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6092/cgroup.procs: No such file or directory
,I/art     ( 7143): Almond Protected OAT
,D/WeatherApplication( 7143): removeAccount
,D/WeatherApplication( 7143): Account.length = 0
,E/WeatherApplication( 7143): OPERATOR:OPEN
D/WeatherAncestor( 7143): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:44
D/Weather.Utils( 7143): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7143): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7143): 2 : This is isUpdating : false
,D/WeatherAncestor( 7143): connectivity changed - connection : true
D/WeatherService( 7143): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7143): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7143): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7143): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7143): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7143): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:44
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7164 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6662:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6662/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1038):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7164): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7164): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7164): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7164): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6809): 
,I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6809): 
,I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6809): 
I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6809): 
,I/WebViewFactory( 7164): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6809): 
I/LibraryLoader( 7164): Loading: webviewchromium
,I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6809): 
I/LibraryLoader( 7164): Time to load native libraries: 4 ms (timestamps 1098-1102)
I/LibraryLoader( 7164): Expected native library version number "",actual native library version number ""
I/jxcore-log( 6809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6809): 
V/WebViewChromiumFactoryProvider( 7164): Binding Chromium to main looper Looper (main, tid 1) {34a8bd35}
I/LibraryLoader( 7164): Expected native library version number "",actual native library version number ""
I/chromium( 7164): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7164): Initializing chromium process, renderers=0
,W/art     ( 7164): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7164): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7164): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7164): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  311): registerClient() client 0xb1427f20, uid 10093
W/AudioManagerAndroid( 7164): Requires BLUETOOTH permission
I/Adreno-EGL( 7164): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7164): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7164): Build Date: 12/12/14 금
I/Adreno-EGL( 7164): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7164): Remote Branch: 
I/Adreno-EGL( 7164): Local Patches: 
I/Adreno-EGL( 7164): Reconstruct Branch: 
,I/NSApplication( 7164): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7219 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6682:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10013/pid_6682/cgroup.procs: No such file or directory
,W/ResourcesManager( 7219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2346): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 2346): num queued entries: 0
I/iu.UploadsManager( 2346): num updated entries: 0
,I/iu.SyncManager( 2346): NEXT; no task
D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7021): onReceive
,D/AppUp4:CustFacade( 7021): Context : android.app.ReceiverRestrictedContext@1479d610
D/AppUp4:CustFacade( 7021): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7021): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7021): begin check event
I/AppUp4:CustModeStarterReceiver( 7021): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSActivity( 2121): [ac] getting account id
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2121): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 7052): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/Settings( 7052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7078): Network unavailable.
V/FormManager( 7078): Network unavailable.
W/FormManager( 7078): Network not available. Please check & try again.
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3333): networkInfo.isConnected() = false
D/WeatherAncestor( 7143): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:45
D/Weather.Utils( 7143): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7143): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7143): 2 : This is isUpdating : false
D/WeatherAncestor( 7143): connectivity changed - connection : true
D/WeatherService( 7143): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1aba830e
D/ForecastDataCache( 7143): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7143): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7143): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7143): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7143): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:45
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
,D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
I/wpa_supplicant( 2614): Trying to associate with SSID 'NG700'
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=112161  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=112172  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UEI.SmartControl( 6700): Internal timer expired: 2
D/UEI.SmartControl( 6700): unbind internal service
,D/serial_port( 6700): close(fd = 24)
,I/UEI.SmartControl( 6700): Serial port is closed.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{40aaf9e type 2 when 112588 com.google.android.gms} when 112588
,V/QRemote ( 6954): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6954): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9397
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState ASSOCIATION_REJECTION_EVENT 32 1 c0:ff:d4:d3:aa:48 blacklist=false rt=114253
E/WifiStateMachine( 1038):  ConnectModeState ASSOCIATION_REJECTION_EVENT 32 1 c0:ff:d4:d3:aa:48 blacklist=false rt=114253
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=114253  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=114259  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=114757  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=114788  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING],
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6930): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/GAV4    ( 7164): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1038): Killing 6592:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/jxcore-log( 6809): Test app app.js loaded
I/jxcore-log( 6809): 
,I/chromium( 6809): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6809): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb7c409 added. We now have 1 listener(s)
,I/jxcore-log( 6809): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6809): 
W/libprocessgroup( 1038): failed to open /acct/uid_10014/pid_6592/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2614): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=116944  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=116954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 2614): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2614): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2614): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=40 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=43 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=117068  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=117068  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=117070
,E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=117071
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=117071
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=117075
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 40 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=117075
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=117076  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=117079  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=117080  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=117080  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=117081
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=117081
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6891): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6891): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6891): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6891): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6891): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6891): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6891): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  306): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=117145  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=117146  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=117146  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=117148  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=117149  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=117149  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1da20b4f target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1da20b4f target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  306): Setting iface cfg
D/CommandListener(  306): Trying to bring up wlan0
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2614): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1038): SET ps 1: returned true
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK],
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  306): netlink response contains error (File exists)
,D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1858): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 28
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7321): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7321): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7321): DSQN ssw
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6954): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
,D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6954): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6954): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6954): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6930): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6930): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6891): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6891): MCCMNC not supported: null
D/QRemote ( 6954): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6954): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6954): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6954): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6954): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  306): argv[0]=dsqncommand
,D/LGDataListener(  306): argv[1]=wlan0
D/LGDataListener(  306): argv[2]=1
D/LGDataListener(  306): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 09:42:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454578971229], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454578971208]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
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
,D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1858): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/dhcpcd  ( 7328): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7328): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7328): version 5.5.6 starting
E/dhcpcd  ( 7328): get_duid: m
D/dhcpcd  ( 7328): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7328): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7328): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7328): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7328): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7328): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7328): wlan0: sending REQUEST (xid 0xe3a68080), next in 4.73 seconds
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 117559436366; DSPS: 3992985; Offset : -4311800348
,I/CloudHub( 2184): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19990
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524295
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5944): type=WIFI subType= reason=null isConnected=true
,I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7021): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7021): onReceive
,D/AppUp4:CustFacade( 7021): Context : android.app.ReceiverRestrictedContext@1479d610
D/AppUp4:CustFacade( 7021): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7021): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7021): begin check event
I/AppUp4:CustModeStarterReceiver( 7021): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3365): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/eas_req ( 7052): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3365): DownloadService onCreate
I/LgeMiscReceiver( 3333): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3333): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3333): networkInfo.isConnected() = true
,D/PhoneState( 3333): setPdpRejectCasuse : false
D/WeatherAncestor( 7143): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:54
,I/DownloadManager( 3365): in removeSpuriousFiles
V/DownloadManager( 3365): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@3a48b634 on behalf of 3365
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
D/Weather.Utils( 7143): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7143): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7143): 2 : This is isUpdating : false
D/WeatherAncestor( 7143): connectivity changed - connection : true
D/WeatherService( 7143): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1aba830e
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3365): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/ForecastDataCache( 7143): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7143): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7143): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7143): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7143): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:42:54
I/DownloadManager( 3365): in trimDatabase
,V/DownloadManager( 3365): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@18b19c5d on behalf of 3365
,W/Settings( 7052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4336): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/Settings( 7052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LGDMClient( 4336): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3365): DownloadService onStartCommand
D/LGDMClient( 4336): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3365): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3365): created cursor android.database.sqlite.SQLiteCursor@24d501a0 on behalf of 3365
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3365): processing inserted download 1
E/LGDMClient( 4336): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4336): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3365): processing inserted download 4
D/LGDMClient( 4336): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3365): processing inserted download 7
V/DownloadManager( 3365): processing inserted download 8
V/DownloadManager( 3365): processing inserted download 9
V/DownloadManager( 3365): processing inserted download 10
V/DownloadManager( 3365): processing inserted download 16
V/DownloadManager( 3365): processing inserted download 17
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3365): processing inserted download 18
V/DownloadManager( 3365): processing inserted download 21
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = mtalk.google.com, class = 1, type = 1
,V/DownloadManager( 3365): processing inserted download 22
I/iu.Environment( 2346): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/dhcpcd  ( 7328): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/iu.UploadsManager( 2346): num queued entries: 0
V/DownloadManager( 3365): DownloadService onDestroy
,I/iu.UploadsManager( 2346): num updated entries: 0
I/iu.SyncManager( 2346): NEXT; no task
D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/ChimeraCfgMgr( 2346): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/dhcpcd  ( 7328): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7328): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7328): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7328): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7328): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7328): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7328): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7328): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  306): res_queryN name = mtalk.google.com succeed
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
W/Kids    ( 2346): [AccountUtils] Account not ready
W/Kids    ( 2346): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2346): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2346): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2346): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2346): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2346): 	at java.lang.Thread.run(Thread.java:818)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com succeed
,D/GCM     ( 2121): Connected
,V/FormManager( 7078): There are no updated forms. The schedule will be deleted.
V/FormManager( 7078): Alarm would be updated, because LastCheckTime has been updated.
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
I/art     ( 1038): Explicit concurrent mark sweep GC freed 78091(3MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 2.525ms total 139.860ms
D/DhcpStateMachine( 1038): RunningState
,D/GCM     ( 2121): Message class com.google.f.a.a.p
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  306): res_queryN name = www.google.com succeed
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=581469007, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1ff577e5 type 0 when 1454578980106 com.android.vending} when 1454578980106
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=581469007 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1556de3f type 2 when 131953 android} when 131953
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 137562046984; DSPS: 4648430; Offset : -4311784011
,I/CloudHub( 2184): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2184): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 157563730466; DSPS: 5303845; Offset : -4311779047
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{380d2455 type 0 when 1454579000545 com.android.vending} when 1454579000545
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Scheduling replication attempt 3.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{289d52f type 2 when 169694 android} when 169694
,I/BooksSync( 6765): Starting books sync
,D/BooksSync( 6765): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3291683975857396275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
W/ApiaryClient( 6765): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3291683975857396275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
W/ResourcesManager( 1404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1404): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3291683975857396275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,E/BooksSync( 6765): Soft error: 
E/BooksSync( 6765): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3291683975857396275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6765): Headers:
E/BooksSync( 6765): accept-encoding: [gzip]
E/BooksSync( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6765): gdata-version: 2
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6765): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6765): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6765): 	at java.lang.Thread.run(Thread.java:818),
E/BooksSync( 6765): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6765): {
E/BooksSync( 6765):  "error": {
E/BooksSync( 6765):   "errors": [
E/BooksSync( 6765):    {
E/BooksSync( 6765):     "domain": "global",
E/BooksSync( 6765):     "reason": "required",
E/BooksSync( 6765):     "message": "Login Required",
E/BooksSync( 6765):     "locationType": "header",
E/BooksSync( 6765):     "location": "Authorization"
E/BooksSync( 6765):    }
E/BooksSync( 6765):   ],
E/BooksSync( 6765):   "code": 401,
E/BooksSync( 6765):   "message": "Login Required"
E/BooksSync( 6765):  }
E/BooksSync( 6765): }
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6765): 	... 8 more
,E/BooksSync( 6765): Sync error
E/BooksSync( 6765): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3291683975857396275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6765): Headers:
E/BooksSync( 6765): accept-encoding: [gzip]
E/BooksSync( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6765): gdata-version: 2
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6765): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6765): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6765): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6765): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6765): {
E/BooksSync( 6765):  "error": {
E/BooksSync( 6765):   "errors": [
E/BooksSync( 6765):    {
E/BooksSync( 6765):     "domain": "global",
E/BooksSync( 6765):     "reason": "required",
E/BooksSync( 6765):     "message": "Login Required",
E/BooksSync( 6765):     "locationType": "header",
E/BooksSync( 6765):     "location": "Authorization"
E/BooksSync( 6765):    }
E/BooksSync( 6765):   ],
E/BooksSync( 6765):   "code": 401,
E/BooksSync( 6765):   "message": "Login Required"
E/BooksSync( 6765):  }
E/BooksSync( 6765): }
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6765): 	... 8 more
I/BooksSync( 6765): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169694, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 177565602020; DSPS: 5959267; Offset : -4311799245
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{18623346 type 0 when 1454579035286 com.android.vending} when 1454579035286
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/HeadsetStateMachine( 3816): Disconnected process message: 10, size: 0
,D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1038): battery changed pluggedType: 2
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4336): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 197570940294; DSPS: 6614801; Offset : -4311771264
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=581469007, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1f94a8b8 type 2 when 199740 android} when 199740
D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=581469007 [*alarm*], flags=0x0
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{29c3f9f6 type 0 when 1454579058871 com.android.vending} when 1454579058871
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 217573331797; DSPS: 7270240; Offset : -4311788696
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{22dfafe8 type 2 when 187286 com.google.android.gms} when 187286
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3646c601 type 2 when 205777 android} when 205777
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2121): Vacuum at: now=1454579082796 tag=VacuumService
,I/GoogleURLConnFactory( 2121): Using platform SSLCertificateSocketFactory
,W/Uploader( 2121): No account for auth token provided
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  306): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2121): No account for auth token provided
I/GoogleURLConnFactory( 2121): Using platform SSLCertificateSocketFactory
,W/Uploader( 2121): No account for auth token provided
,W/Uploader( 2121): No account for auth token provided
I/art     ( 2121): Explicit concurrent mark sweep GC freed 40209(2MB) AllocSpace objects, 17(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.335ms total 79.751ms
,W/Uploader( 2121):  no longer exists, so no auth token.
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{11f18c4 type 2 when 229865 android} when 229865
,I/BooksSync( 6765): Starting books sync
,D/BooksSync( 6765): started syncMyEbooks
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 30496(1359KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.407ms total 143.539ms
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5116418899587399856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5116418899587399856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1404): onNotificationPosted
D/SmartCoverUpdateMonitor( 1404): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1404): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1404): handleNotificationPosted(true)
D/QuickCircle( 1404): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1404): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): post do just update job
D/LgeQuickCoverNotificationData( 1404): showAll3
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1404): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1404): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1404): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1404): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1404): updateNotificationData: count=3
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6765): Authentication error
E/BooksAccountManager( 6765): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6765): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6765): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6765): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6765): null auth token
D/QuickStatusbarLayout( 1404): Notification difference=198
D/QuickStatusbarLayout( 1404): child = android.widget.LinearLayout{201d64b8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6765): Error response from books API: {
W/ApiaryClient( 6765):  "error": {
W/ApiaryClient( 6765):   "errors": [
W/ApiaryClient( 6765):    {
W/ApiaryClient( 6765):     "domain": "global",
W/ApiaryClient( 6765):     "reason": "required",
W/ApiaryClient( 6765):     "message": "Login Required",
W/ApiaryClient( 6765):     "locationType": "header",
W/ApiaryClient( 6765):     "location": "Authorization"
W/ApiaryClient( 6765):    }
W/ApiaryClient( 6765):   ],
W/ApiaryClient( 6765):   "code": 401,
W/ApiaryClient( 6765):   "message": "Login Required"
W/ApiaryClient( 6765):  }
W/ApiaryClient( 6765): }
,W/ApiaryClient( 6765): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5116418899587399856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6765): Headers:
W/ApiaryClient( 6765): accept-encoding: [gzip]
W/ApiaryClient( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6765): gdata-version: 2
E/BooksSync( 6765): Soft error: 
E/BooksSync( 6765): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5116418899587399856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6765): Headers:
E/BooksSync( 6765): accept-encoding: [gzip]
E/BooksSync( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6765): gdata-version: 2
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6765): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6765): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6765): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6765): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6765): {
E/BooksSync( 6765):  "error": {
E/BooksSync( 6765):   "errors": [
E/BooksSync( 6765):    {
E/BooksSync( 6765):     "domain": "global",
E/BooksSync( 6765):     "reason": "required",
E/BooksSync( 6765):     "message": "Login Required",
E/BooksSync( 6765):     "locationType": "header",
E/BooksSync( 6765):     "location": "Authorization"
E/BooksSync( 6765):    }
E/BooksSync( 6765):   ],
E/BooksSync( 6765):   "code": 401,
E/BooksSync( 6765):   "message": "Login Required"
E/BooksSync( 6765):  }
E/BooksSync( 6765): }
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6765): 	... 8 more
,E/BooksSync( 6765): Sync error
E/BooksSync( 6765): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6765): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5116418899587399856&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6765): Headers:
E/BooksSync( 6765): accept-encoding: [gzip]
E/BooksSync( 6765): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6765): gdata-version: 2
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6765): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6765): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6765): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6765): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6765): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6765): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6765): {
E/BooksSync( 6765):  "error": {
E/BooksSync( 6765):   "errors": [
E/BooksSync( 6765):    {
E/BooksSync( 6765):     "domain": "global",
E/BooksSync( 6765):     "reason": "required",
E/BooksSync( 6765):     "message": "Login Required",
E/BooksSync( 6765):     "locationType": "header",
E/BooksSync( 6765):     "location": "Authorization"
E/BooksSync( 6765):    }
E/BooksSync( 6765):   ],
E/BooksSync( 6765):   "code": 401,
E/BooksSync( 6765):   "message": "Login Required"
E/BooksSync( 6765):  }
E/BooksSync( 6765): }
E/BooksSync( 6765): 
E/BooksSync( 6765): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6765): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6765): 	... 8 more
I/BooksSync( 6765): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 205083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 237575010174; DSPS: 7925655; Offset : -4311790688
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2acf7caf type 0 when 1454579091617 com.android.vending} when 1454579091617
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6279): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6279): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6279): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=581469007, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7551 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2615): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7551): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7551): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@79f550d
I/ActivityManager( 1038): Killing 2184:com.lge.music/u0a34 (adj 15): empty #17
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=581469007 [*alarm*], flags=0x0
V/AudioFlinger(  311): 2184 died, releasing its sessions
V/AudioFlinger(  311):  pid 1858 @ 0
V/AudioFlinger(  311):  pid 3333 @ 1
,V/AudioFlinger(  311):  pid 3333 @ 2
W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2184/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 257576682302; DSPS: 8581070; Offset : -4311797105
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{23641f9 type 2 when 259905 android} when 259905
,I/jxcore-log( 6809): --= Surplus to requirements =--
I/jxcore-log( 6809): 
I/jxcore-log( 6809): ****TEST TOOK:  ms ****
I/jxcore-log( 6809): 
I/jxcore-log( 6809): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6809): 
,D/AndroidRuntime( 7605): 
D/AndroidRuntime( 7605): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7605): CheckJNI is OFF
D/AndroidRuntime( 7605): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 6809:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1038): WIN DEATH: Window{a605564 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{a605564 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1038): Skipping PackageSetting{bfd0521 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{2a4944be u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{38ca253e 6809:com.test.thalitest/u0a311}, curProc for 6809: null
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{2a4944be u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{2a4944be u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2074): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{1bb54e60 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2074): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2074): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{853cf19 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]Launcher.Model( 2074): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]GBoardWebView( 2074): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1911): notifyUserLog: 1000003
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Informant_ActionManagerMessageHandler( 3761): handleMessage: what(1000) actionID(0x1000003)
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
,E/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3761): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2019): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
W/GeofencerStateMachine( 1823): Ignoring removeGeofence because network location is disabled.
I/[LGHome]LGActivityUtil( 2074): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/PostponalbeReceiver( 6477): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/System.err( 4576): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4576): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4576): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4576): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4576): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4576): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4576): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4576): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4576): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4576): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4576): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4576): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7636 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2074): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2074): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1451): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1911): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 3761): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2074): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/SplitUIManager( 1875): split_name #11 / not available #0
V/BoardContentProvider( 3761): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/SplitUIService( 1875): removed split : 
,I/GBoardWebViewUtils( 2074): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2074): , create_time: 1430558575574
I/GBoardWebViewUtils( 2074): , expire_time: 0
I/GBoardWebViewUtils( 2074): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2074): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2074): , display: false
I/GBoardWebViewUtils( 2074): , animation: false }
I/GBoardWebViewUtils( 2074): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2074): , create_time: 1430558575600
I/GBoardWebViewUtils( 2074): , expire_time: 0
I/GBoardWebViewUtils( 2074): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2074): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2074): , display: false
I/GBoardWebViewUtils( 2074): , animation: false }
I/GBoardWebViewUtils( 2074): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2074): , create_time: 1453982950152
I/GBoardWebViewUtils( 2074): , expire_time: 0
I/GBoardWebViewUtils( 2074): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2074): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2074): , display: false
I/GBoardWebViewUtils( 2074): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1451): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bbc7d3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]GBoardWebView( 2074): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1875): split_name #11 / not available #0
I/SplitUIService( 1875): split app #11
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/WallpaperManager( 2074): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/art     ( 4624): Explicit concurrent mark sweep GC freed 15853(890KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 413us total 137.883ms
I/LockScreenSettings( 7636): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
D/AppUp4:PreloadHelper( 7021): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2074): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7658 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/art     ( 1038): Explicit concurrent mark sweep GC freed 19631(1243KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.639ms total 276.650ms
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3136): Thermal-Lib-Client: Client request sent
,W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     ( 1038): WaitForGcToComplete blocked for 269.806ms for cause Explicit
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): handleShortcutListChanged...
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
I/[LGHome]EVENT( 2074): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] installed app name: Google Play Music
,D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          packageName: com.lge.music
,D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3816): [BTUI] [-] updateMediaPlayerInfo
I/ActivityManager( 1038): Killing 6930:com.lge.sync/1000 (adj 15): empty #17
D/administrator( 1038): Handling package changes for user 0
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/[LGHome]Launcher.Model( 2074): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2074): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2074): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2074): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,D/KeyguardModel( 1451): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2074): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6930/cgroup.procs: No such file or directory
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{26eafb60 u0 com.lge.launcher2/.Launcher t3} time:268577
I/[Concierge]WidgetView( 2074): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2615): onStartCommand(). Type : 8
D/[Concierge]Service( 2615): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2615): Update widget ID : 11
,D/[Concierge]WidgetView( 2074): change position of spinner
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 7658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2074): initWebView(). Time : 1454579122441
D/[Concierge]Service( 2615): onStartCommand(). Type : 0
W/ResourcesManager( 7658): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 7658): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
,I/[Concierge]WebView( 2074): Return exist ConciergeWebView. Reuse : 325396947
,D/[Concierge]WidgetView( 2074): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2074): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2074): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@14f8078a
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2074): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2074): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2074): Widget kill message received. Destory myself. My : 1454578881066, New one : 1454579122441
,D/[Concierge]WidgetView( 2074): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2074): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/[Concierge]WidgetView( 2074): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7658): BUILD Country: EU
,I/SystemConfig( 7658): BUILD Operator: OPEN
I/ActivityManager( 1038): Killing 6700:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/art     ( 1038): Explicit concurrent mark sweep GC freed 9980(543KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 6.568ms total 202.457ms
I/[LgeWidgetLib]LgeAppWidgetHostView( 2074): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2074): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2074): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2074): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/QRemote ( 6954): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6954): android.os.DeadObjectException
W/System.err( 6954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6954): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6954): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6954): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6954): android.os.DeadObjectException
W/System.err( 6954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6954): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6954): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6954): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6954): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/Timeline( 2074): Timeline: Activity_idle id: android.os.BinderProxy@d988d3d time:268715
,W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 7605): Shutting down VM
,I/chromium( 2074): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2074): onReloaded()
,I/GBoardWebViewClient( 2074): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6700/cgroup.procs: No such file or directory
,W/ActivityManager( 1038): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6954): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6954): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/BoardContentProvider( 3761): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/VoicemailCleanupService( 2206): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1038): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7681 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6954): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/BoardContentProvider( 3761): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/PackageChangeReceiver( 7052): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/SystemConfig( 7658): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7658): existFile = false
I/SystemConfig( 7658): canReadFile = false
I/SystemConfig( 7658): systemFeature RCS result false
D/SystemConfig( 7658): refreshRcsSupport() :false
I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7698 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/ActionManagerService( 1911): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3761): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3761): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1911): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3761): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3761): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3761): getSize() : size - 0
,D/LIA_Informant_Tips_SmartTipsActionManager( 3761): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3761): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2074): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2074): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2074): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2074): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2074): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2074): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/[LGHome]EVENT( 2074): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/UEI.SmartControl( 7681): Quickset Services start...
,I/UEI.SmartControl( 7681): Manufacture = LGE
D/UEI.SmartControl( 7681): Id = LGNevo
D/UEI.SmartControl( 7681): File observer start...
E/UEI.SmartControl( 7681): IR Port is disabled: false
D/UEI.SmartControl( 7681): Starting file observer...
D/UEI.SmartControl( 7681): Extracting JNI libs...
D/UEI.SmartControl( 7681): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 7698): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7681): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7681): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7681): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/UEI.SmartControl( 7681): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/libqs_jni.so: open failed: EROFS (Read-only file system)
,I/UEI.SmartControl( 7681): --- Selecting new region: 6
I/UEI.SmartControl( 7681): Model = LG-D855
D/UEI.SmartControl( 7681): QS Service created
I/UEI.SmartControl( 7681): Service initServices...
,I/AppConfig( 7698): Total System Memory = 2995761152
D/SystemHelper( 7698): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 7681): QS start get config
,E/SharedPreferencesImpl( 7698): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,I/ActivityManager( 1038): Killing 6891:com.android.settings/1000 (adj 15): empty #17
D/UEI.SmartControl( 7681): Loading JNI Libs...
,E/UEI.SmartControl( 7681): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)

```
