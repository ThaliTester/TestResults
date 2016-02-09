#### Test 58135655e9e7eb8_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{31e1ed1a type 2 when 101459 android} when 101459
I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6983 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
I/art     (  354): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 37.209ms
I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 27.134ms
I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 36.973ms
I/ReaderUtils( 6983): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2138): innerSync failed
D/ContactsSyncAdapter( 2138): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2138): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2138): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2138): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2138): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GAV2    ( 6983): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 78368, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1038): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 163286, reason: 10019
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 2138): Explicit concurrent mark sweep GC freed 22135(1313KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 1.515ms total 53.993ms
I/BooksApp( 6983): Created application version: 3.2.35 (30235)
I/BooksSync( 6983): Starting books sync
D/BooksSync( 6983): started syncMyEbooks
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
W/ApiaryClient( 6983): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2437491050662726419&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
D/AndroidRuntime( 7044): 
D/AndroidRuntime( 7044): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7044): CheckJNI is OFF
D/AndroidRuntime( 7044): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1967): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{2628da1b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{2628da1b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7067 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7044): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1872): Display #0 changed.
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{1aff7631 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{2fae7116 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7067): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7067): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7067): Loading: webviewchromium
,I/LibraryLoader( 7067): Time to load native libraries: 3 ms (timestamps 3273-3276)
,I/LibraryLoader( 7067): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7067): Binding Chromium to main looper Looper (main, tid 1) {3d2bc2b}
I/LibraryLoader( 7067): Expected native library version number "",actual native library version number ""
,I/chromium( 7067): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7067): Initializing chromium process, renderers=0
,W/art     ( 7067): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7067): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7067): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7067): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  313): registerClient() client 0xb14fd820, uid 10311
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@322e6dcd:true
,I/Adreno-EGL( 7067): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7067): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7067): Build Date: 12/12/14 금
I/Adreno-EGL( 7067): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7067): Remote Branch: 
I/Adreno-EGL( 7067): Local Patches: 
I/Adreno-EGL( 7067): Reconstruct Branch: 
,W/chromium( 7067): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7067): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7067): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7067): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7067): CordovaWebView is running on device made by: LGE
,W/art     ( 7067): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7067): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{3dbb47b8 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 7067): Render dirty regions requested: true
I/OpenGLRenderer( 7067): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7067): Enabling debug mode 0
D/Atlas   ( 7067): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{e6856df u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2fb16f49,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 7067): Timeline: Activity_idle id: android.os.BinderProxy@199f061b time:103665
,D/LgDataFeature( 7067): LgDataFeature() Constructor: none
D/LgDataFeature( 7067): LgDataFeature() Constructor Done, null
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +617ms (total +731ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3dbb47b8 u0 com.test.thalitest/.MainActivity t4} time:103690
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1417): onNotificationPosted
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6983): null auth token
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2437491050662726419&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
D/JsMessageQueue( 7067): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7067): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435053312
,I/chromium( 7067): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7067): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7067): 
,I/chromium( 7067): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7067): 
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
,I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
E/BooksAccountManager( 6983): Authentication error
E/BooksAccountManager( 6983): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6983): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6983): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6983): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/HttpHelper( 6983): null auth token
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6983): Error response from books API: {
W/ApiaryClient( 6983):  "error": {
W/ApiaryClient( 6983):   "errors": [
W/ApiaryClient( 6983):    {
W/ApiaryClient( 6983):     "domain": "global",
W/ApiaryClient( 6983):     "reason": "required",
W/ApiaryClient( 6983):     "message": "Login Required",
W/ApiaryClient( 6983):     "locationType": "header",
W/ApiaryClient( 6983):     "location": "Authorization"
W/ApiaryClient( 6983):    }
W/ApiaryClient( 6983):   ],
W/ApiaryClient( 6983):   "code": 401,
W/ApiaryClient( 6983):   "message": "Login Required"
W/ApiaryClient( 6983):  }
W/ApiaryClient( 6983): }
,W/ApiaryClient( 6983): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2437491050662726419&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6983): Headers:
W/ApiaryClient( 6983): accept-encoding: [gzip]
W/ApiaryClient( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6983): gdata-version: 2
W/jxcore-log( 7067): Initializing JXcore engine
W/jxcore-log( 7067): JXcore engine is ready
,W/Thread-849( 7133): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7489]" dev="sockfs" ino=7489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-849( 7133): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-849( 7133): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10064]" dev="sockfs" ino=10064 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-849( 7133): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-849( 7133): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33445]" dev="sockfs" ino=33445 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 7067): Starting JXcore engine
W/jxcore-log( 7067): Platform android
W/jxcore-log( 7067): 
W/jxcore-log( 7067): Process ARCH arm
W/jxcore-log( 7067): 
,I/jxcore-log( 7067): JXcore Cordova bridge is ready!
I/jxcore-log( 7067): 
,W/jxcore-log( 7067): JXcore engine is started
,E/BooksSync( 6983): Soft error: 
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2437491050662726419&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
,E/BooksSync( 6983): Sync error
E/BooksSync( 6983): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6983): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2437491050662726419&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6983): Headers:
E/BooksSync( 6983): accept-encoding: [gzip]
E/BooksSync( 6983): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6983): gdata-version: 2
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6983): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6983): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6983): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6983): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6983): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6983): {
E/BooksSync( 6983):  "error": {
E/BooksSync( 6983):   "errors": [
E/BooksSync( 6983):    {
E/BooksSync( 6983):     "domain": "global",
E/BooksSync( 6983):     "reason": "required",
E/BooksSync( 6983):     "message": "Login Required",
E/BooksSync( 6983):     "locationType": "header",
E/BooksSync( 6983):     "location": "Authorization"
E/BooksSync( 6983):    }
E/BooksSync( 6983):   ],
E/BooksSync( 6983):   "code": 401,
E/BooksSync( 6983):   "message": "Login Required"
E/BooksSync( 6983):  }
E/BooksSync( 6983): }
E/BooksSync( 6983): 
E/BooksSync( 6983): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6983): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6983): 	... 8 more
I/BooksSync( 6983): Finished books sync
,I/jxcore-log( 7067): Toggling radios to true
I/jxcore-log( 7067): 
D/BluetoothAdapter( 7067): enable(): BT is already enabled..!
I/ActivityManager( 1038): Killing 6279:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/WifiService( 1038): New client listening to asynchronous messages
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 76913, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7067, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6279/cgroup.procs: No such file or directory
D/WifiService( 1038): setWifiEnabled: true pid=7067, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7067, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [106,049,587 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
,D/WifiServiceImplEx( 1038): reconnect pid=7067, uid=10311, packageName=com.test.thalitest
,I/jxcore-log( 7067): Radios toggled
I/jxcore-log( 7067): 
I/jxcore-log( 7067): My device name is: LGE-LG-D855
I/jxcore-log( 7067): 
I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
V/NativeCrypto( 2138): Read error: ssl=0xaf4d6000: I/O error during system call, Connection timed out
,V/NativeCrypto( 2138): SSL shutdown failed: ssl=0xaf4d6000: I/O error during system call, Broken pipe
D/DhcpStateMachine( 1038): RunningState{ when=-13ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7148 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [106,197,607 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106219
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=106220
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
,D/DSQN    ( 1038): stop dsqn bin
D/WifiHS20( 1038): hidePasspointNotification off =false
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106252  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=106252  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 un,available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106271  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=106278  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
,D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7148): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7148): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-127ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7148): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7148): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7148): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7182 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6299:com.android.contacts/u0a19 (adj 15): empty #17
I/MusicWidget( 2701): mDelayedStopHandler : unbind
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6299/cgroup.procs: No such file or directory
I/MusicBrowser( 2235): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2235): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2235): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2235): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2235): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2235): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1038):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@81e4cf6com.lge.music.MediaPlaybackService$5@2c9de8f7
D/MusicBrowser( 2235): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3dfebf5d
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2235): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2235): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2235): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2235): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2235): reset
V/MediaPlayer[Native]( 2235): setListener
V/MediaPlayer[Native]( 2235): disconnect
V/MediaPlayer[Native]( 2235): destructor
V/AudioFlinger(  313): releasing 13 from 2235 for -1
V/AudioFlinger(  313):  decremented refcount to 0
V/AudioFlinger(  313): purging stale effects
V/MediaPlayer[Native]( 2235): disconnect
D/MusicBrowser( 2235): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2235): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2235): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2235): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2235): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2235): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2235): [SmartShareManagerClient] unregisterListener: 37856100
W/SmartShareClient( 2235): [SmartShareManagerClient] unregisterListener invalid listener: 37856100
I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/SmartShareClient( 2235): [SmartShareManagerClient] terminate service: 2235/MediaPlaybackService/64142379
E/HomeCloudIF( 2235): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2235): [SmartShareManagerClient] unbindService context:android.app.Application@391339cd
V/CloudHub( 2235): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2235): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2235): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2235): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2235): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
I/ActivityManager( 1038): Killing 6715:com.lge.email/u0a23 (adj 15): empty #17
D/PCSuite ( 7182): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{25418fc7 type 0 when 1455021513262 android} when 1455021513262
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6715/cgroup.procs: No such file or directory
I/GAV2    ( 6983): Thread[GAThread,5,main]: No campaign data found.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7148): LgDataFeature() Constructor: none
D/LgDataFeature( 7148): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7205 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6324:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6324/cgroup.procs: No such file or directory
W/ResourcesManager( 7205): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 7205): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 7205): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7205): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7205): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7205): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7205): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7205): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7205): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7205): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7182): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7205): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7182): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7182): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:43074] from screen [on:0 period:-972399103]
V/QRemote ( 7205): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7205): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7205): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
W/ContextImpl( 4616): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/LgDataFeature( 7205): LgDataFeature() Constructor: none
D/LgDataFeature( 7205): LgDataFeature() Constructor Done, null
,V/SoundPool( 7205): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7205): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7205): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7205): doLoad: loading sample sampleID=1
I/QRemote ( 7205): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6848): QS Service created
D/QRemote ( 7205): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7205): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/SoundPool( 7205): Start decode
V/MediaPlayer[Native]( 7205): decode(31, 10857164, 17813)
I/UEI.SmartControl( 6848): Service initServices...
D/UEI.SmartControl( 6848): QS start get config
V/MediaPlayerService(  313): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  313): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  313): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  313): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  313): player type = 3
V/AwesomePlayer(  313): AwesomePlayer create()
,V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): setAudioSink() 
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb5474dc0, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  313): Use LGExtractor :application/ogg 
,V/LGMDMManager( 7205): Create singleton instance
V/LGParserOSAL(  313): supported mime: application/ogg
V/AwesomePlayer(  313): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  313): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  313): mBitrate = -1 bits/sec
V/AwesomePlayer(  313): AudioTrack Setting
V/AwesomePlayer(  313): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  313): setAudioSource() 
V/MediaPlayerService(  313): prepare
V/AwesomePlayer(  313): prepareAsync_l() 
V/MediaPlayerService(  313): wait for prepare
V/AwesomePlayer(  313): onPrepareAsyncEvent() 
V/AwesomePlayer(  313): initAudioDecoder() 
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  313): isAudioPlaybackHookOn() false
V/AwesomePlayer(  313): getUseOffload() = 0 
V/OMXCodec(  313): OMXCodec::Create
V/OMXCodec(  313): findMatchingCodecs()
V/OMXCodec(  313): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  313): matchingCodecs.size()=1
V/OMXCodec(  313): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  313): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  313): LG Codec Adapter start
V/OMXCodec(  313): OMXCodec Createtor
V/OMXCodec(  313): setComponentRole
V/OMXCodec(  313): configureCodec protected=0
V/LGCodecAdapter(  313): called getLGCodecSpecificData
V/LGCodecOSAL(  313): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMSG
V/LGCodecOSAL(  313): Not support LGCodec
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  313): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  313): Could not offload audio decode, try pcm offload
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  313): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  313): init()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  313): allocateBuffers
V/OMXCodec(  313): allocateBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXC,odec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  313): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  313): finishAsyncPrepare_l() 
V/AudioCache(  313): notify(0xb5474dc0, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb5474dc0, 1, 0, 0)
V/AudioCache(  313): prepared
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): start
V/AwesomePlayer(  313): play_l() 
V/AwesomePlayer(  313): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  313): createAudioPlayer_l
V/AwesomePlayer(  313): seekAudioIfNecessary_l() 
V/AwesomePlayer(  313): startAudioPlayer_l() 
D/AudioPlayer(  313): start of Playback, useOffload 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  313): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3470 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb5474dc0, 6, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab502000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab503000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab504000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab505000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab506000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab507000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab508000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab509000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50a000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50b000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50c000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50d000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50e000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab50f000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab510000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab511000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab512000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab513000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab514000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab515000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab516000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab517000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab518000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab519000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51a000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51b000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51c000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51d000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51e000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab51f000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab520000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab521000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab522000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab523000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab524000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab525000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab526000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab527000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab528000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab529000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52a000, 0xb169d000, 4096)
,V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52b000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52c000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52d000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52e000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab52f000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab530000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab531000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab532000, 0xb169d000, 4096)
V/AudioCache(  313): write(0xb169d000, 4096)
V/AudioCache(  313): memcpy(0xab533000, 0xb169d000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb169d000, 280)
V/AudioCache(  313): memcpy(0xab534000, 0xb169d000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb5474dc0, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): notify(0xb5474dc0, 7, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  313): Pause Playback at 1068125
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb5474dc0, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/AudioPlayer(  313): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3470 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  313): AudioPlayer releasing audio source
D/AudioPlayer(  313): AudioPlayer done releasing audio source
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): ~AwesomePlayer call
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/SoundPool( 7205): close(31)
V/SoundPool( 7205): pointer = 0x9fe39000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7205): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1855
I/UEI.SmartControl( 6848): Supports setup maps: true
D/UEI.SmartControl( 6848): QS start statue = true Error code = 0
I/UEI.SmartControl( 6848): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6848): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6848): ### init IR Blaster...
,D/serial_port( 6848): Configuring serial port
E/UEI.SmartControl( 6848): UEIBLaster setting for 616
,I/UEI.SmartControl( 6848): Setting serial record hearder size = 2
I/UEI.SmartControl( 6848): configuring settings for MAXQ616
I/UEI.SmartControl( 6848): Get version...
D/UEI.SmartControl( 6848): serial port data available: 21
,D/UEI.SmartControl( 6848): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6848): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6848): QS saving settings...
D/UEI.SmartControl( 6848): IR Blaster version: 25672567
,D/UEI.SmartControl( 6848): serial port data available: 4
,W/ContextImpl( 6848): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6848): Device manager: loading config....
D/UEI.SmartControl( 6848): ----------- loading internal config...
E/UEI.SmartControl( 6848): Loading SETTINGS...
D/UEI.SmartControl( 6848): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6848): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6848): -----service ready thread exits
I/art     ( 1038): Explicit concurrent mark sweep GC freed 49990(2MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.856ms total 160.846ms
E/UEI.SmartControl( 6848): Services init done
D/UEI.SmartControl( 6848): QS Service init finished
D/UEI.SmartControl( 6848): QS Service version name: 2.1.91
D/UEI.SmartControl( 6848): QS Service version code: 201091
D/UEI.SmartControl( 6848): Service requested: Control
,D/UEI.SmartControl( 6848): Internal service binding...
I/QRemote ( 7205): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6848): ------ IControl API: 11
D/UEI.SmartControl( 6848): File observer start...
E/UEI.SmartControl( 6848): IR Port is disabled: false
D/UEI.SmartControl( 6848): Starting file observer...
I/UEI.SmartControl( 6848): Registering callback...
I/UEI.SmartControl( 6848): ------ IControl API: 19
I/UEI.SmartControl( 6848): Registering Services Ready callback...
I/UEI.SmartControl( 6848): Notify client services are ready...
I/QRemote ( 7205): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7205): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7205): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 7205): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7205): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6848): ------ IControl API: 8
D/QRemote ( 7205): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7205): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7205): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7205): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7205): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7205): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7205): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7205): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7205): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 7205): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455021514946]
D/QRemote ( 7205): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6353:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/QRemote ( 7205): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6353/cgroup.procs: No such file or directory
,V/QRemote ( 7205): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7205): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 7205): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 2723): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108284  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=108294  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2723): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108390  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=108390  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108401
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108401
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.state = ptp_only,adb
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108402
D/UsbSettingsReceiver( 7148): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108402
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=108402
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108402  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/UsbSettingsControl( 7148): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7148): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
I/wpa_supplicant( 2723): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=108410  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsControl( 7148): [AUTORUN] setTetherStatus() : status=false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108412  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=108415  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108416
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=108417
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
,D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108490  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108491  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=108491  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1038): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108493  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108494  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=108494  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
,D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@186f0f64 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@186f0f64 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
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
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2723): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
,D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
,D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 1
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  309): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
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
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&I,MS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
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
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7270): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dsqn    ( 7270): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
E/DSQN    ( 7270): DSQN ssw
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7205): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7205): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7205): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7205): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7182): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7182): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 7205): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7205): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7205): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7205): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7205): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:38:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455021515522], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455021515502]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7276): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7276): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7276): version 5.5.6 starting
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
E/dhcpcd  ( 7276): get_duid: m
D/dhcpcd  ( 7276): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7276): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7276): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7276): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7276): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7276): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7276): wlan0: sending REQUEST (xid 0x6f075cbc), next in 4.02 seconds
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2c327da7 type 0 when 1455021516040 com.android.vending} when 1455021516040
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5241): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5241): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7301 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/AppUp4:AppBoxCP( 7301): onCreate
,W/AppUp4:DB( 7301):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7301):  setFingerPrint start
I/AppUp4:DB( 7301):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7301):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7301):  SDK version = 21
I/AppUp4:DB( 7301):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7301): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7301): onReceive
D/LgDataFeature( 7301): LgDataFeature() Constructor: none
,D/LgDataFeature( 7301): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@13b32221
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7301): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7301): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7301): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7301): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4372): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4372): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3416): DownloadService onCreate
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3416): in removeSpuriousFiles
,V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@3ba1adfb on behalf of 3416
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@31fbbe18 on behalf of 3416
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7329 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3416): DownloadService onStartCommand
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@3fa77e56 on behalf of 3416
E/LGDMClient( 4372): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4372): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4372): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3416): processing inserted download 1
,V/DownloadManager( 3416): processing inserted download 4
V/DownloadManager( 3416): processing inserted download 7
V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
V/DownloadManager( 3416): processing inserted download 10
V/DownloadManager( 3416): processing inserted download 16
V/DownloadManager( 3416): processing inserted download 17
V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
V/DownloadManager( 3416): DownloadService onDestroy
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7329): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ResourcesManager( 7329): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7329): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6399): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6399): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6399): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1038): Killing 6371:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6371/cgroup.procs: No such file or directory
,I/LGEmail ( 7329): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7329): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7329): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7329): LgDataFeature() Constructor: none
D/LgDataFeature( 7329): LgDataFeature() Constructor Done, null
,D/eas_req ( 7329): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7353 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7329): JNI_OnLoad()
I/HubEmail( 7329): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7329): registerNatives()
I/HubEmail( 7329): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7329): registerNativeMethods()
I/HubEmail( 7329): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7329): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1038): Killing 6823:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6823/cgroup.procs: No such file or directory
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = false
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524295
,I/dhcpcd  ( 7276): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7376 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7276): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7276): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7276): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7276): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7276): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7276): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7276): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7276): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7353): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7353): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7419 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6214:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7067): 
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6214/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 6869:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7443 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6901:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6869/cgroup.procs: No such file or directory
,W/libprocessgroup( 1038): failed to open /acct/uid_10013/pid_6901/cgroup.procs: No such file or directory
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/art     ( 7443): Almond Protected OAT
,D/WeatherApplication( 7443): removeAccount
,D/WeatherApplication( 7443): Account.length = 0
,E/WeatherApplication( 7443): OPERATOR:OPEN
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:38
D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:38
I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7067): 
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7461 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6251:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/art     (  354): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 31.326ms
,I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7067): 
,I/art     (  354): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 22.178ms
I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7067): 
I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 19.963ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10014/pid_6251/cgroup.procs: No such file or directory
,I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7067): 
,I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 7067): 
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5241): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7461): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7461): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7461): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7461): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7461): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7461): Loading: webviewchromium
,I/LibraryLoader( 7461): Time to load native libraries: 5 ms (timestamps 1946-1951)
,I/LibraryLoader( 7461): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7461): Binding Chromium to main looper Looper (main, tid 1) {192791d0}
I/LibraryLoader( 7461): Expected native library version number "",actual native library version number ""
I/chromium( 7461): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7461): Initializing chromium process, renderers=0
,W/art     ( 7461): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7461): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7461): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7461): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  313): registerClient() client 0xb57bed20, uid 10093
W/AudioManagerAndroid( 7461): Requires BLUETOOTH permission
I/Adreno-EGL( 7461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7461): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7461): Build Date: 12/12/14 금
I/Adreno-EGL( 7461): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7461): Remote Branch: 
I/Adreno-EGL( 7461): Local Patches: 
I/Adreno-EGL( 7461): Reconstruct Branch: 
,I/NSApplication( 7461): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7522 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6746:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6746/cgroup.procs: No such file or directory
,W/ResourcesManager( 7522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2367): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7301): onReceive
W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@13b32221
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4372): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3416): DownloadService onCreate
,W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4372): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4372): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4372): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3416): in removeSpuriousFiles
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@ffaa3c4 on behalf of 3416
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@1935a2ad on behalf of 3416
,I/GLSActivity( 2138): [ac] getting account id
V/DownloadManager( 3416): DownloadService onStartCommand
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@be03830 on behalf of 3416
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3416): processing inserted download 1
V/DownloadManager( 3416): processing inserted download 4
I/GLSUser ( 2138): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = false
V/DownloadManager( 3416): processing inserted download 7
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:39
,V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5bef007
V/DownloadManager( 3416): processing inserted download 10
D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:39
V/DownloadManager( 3416): processing inserted download 16
V/DownloadManager( 3416): processing inserted download 17
V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
V/DownloadManager( 3416): DownloadService onDestroy
,D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 2367): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7301): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7301): onReceive
D/AppUp4:CustFacade( 7301): Context : android.app.ReceiverRestrictedContext@13b32221
D/AppUp4:CustFacade( 7301): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7301): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7301): begin check event
I/AppUp4:CustModeStarterReceiver( 7301): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7353): There are no updated forms. The schedule will be deleted.
V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4372): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7353): Alarm would be updated, because LastCheckTime has been updated.
I/LGDMClient( 4372): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 62641(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.831ms total 86.290ms
,V/DownloadManager( 3416): DownloadService onCreate
I/DownloadManager( 3416): in removeSpuriousFiles
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4372): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@300022e on behalf of 3416
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@253f21cf on behalf of 3416
E/LGDMClient( 4372): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3416): DownloadService onStartCommand
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4372): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4372): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@1b8e133a on behalf of 3416
V/DownloadManager( 3416): processing inserted download 1
,V/DownloadManager( 3416): processing inserted download 4
V/DownloadManager( 3416): processing inserted download 7
V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
V/DownloadManager( 3416): processing inserted download 10
V/DownloadManager( 3416): processing inserted download 16
V/DownloadManager( 3416): processing inserted download 17
V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
V/DownloadManager( 3416): DownloadService onDestroy
I/LgeMiscReceiver( 3359): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3359): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7329): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3359): networkInfo.isConnected() = true
D/PhoneState( 3359): setPdpRejectCasuse : false
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:39
D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5bef007
D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:38:39
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2367): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,V/FormManager( 7353): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7353): Alarm would be updated, because LastCheckTime has been updated.
D/UEI.SmartControl( 6848): Internal timer expired: 4
,D/UEI.SmartControl( 6848): unbind internal service
,D/serial_port( 6848): close(fd = 24)
,I/UEI.SmartControl( 6848): Serial port is closed.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2610a89d type 2 when 113634 com.google.android.gms} when 113634
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
V/QRemote ( 7205): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7205): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1855
D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2138): Connected
,I/GCM     ( 2367): Message from null null
E/GCM     ( 2367): Dropping message from null
,D/GCM     ( 2138): Message class com.google.f.a.a.p
,I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7067): 
,I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7067): 
I/jxcore-log( 7067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7067): 
I/GAV4    ( 7461): Thread[GAThread,5,main]: No campaign data found.
,I/CloudHub( 2235): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19994
,I/jxcore-log( 7067): Test app app.js loaded
I/jxcore-log( 7067): 
,I/chromium( 7067): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7067): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b29df added. We now have 1 listener(s)
,I/jxcore-log( 7067): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7067): 
,I/ActivityManager( 1038): Killing 6983:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6983/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 117743286522; DSPS: 3999401; Offset : -4325050113
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,I/CloudHub( 2235): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2235): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 137745374119; DSPS: 4654829; Offset : -4325037713
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2147aae0 type 2 when 131657 android} when 131657
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{38cbec5e type 0 when 1455021536462 com.android.vending} when 1455021536462
,D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6399): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6399): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6399): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 157747236142; DSPS: 5310250; Offset : -4325037287
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2677b309 type 0 when 1455021566946 com.android.vending} when 1455021566946
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6399): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6399): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6399): [1] 5.onFinished: Scheduling replication attempt 4.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{10195cc3 type 2 when 169832 android} when 169832
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7650 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7650): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7650): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7650): Created application version: 3.2.35 (30235)
,I/BooksSync( 7650): Starting books sync
,D/BooksSync( 7650): started syncMyEbooks
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
E/BooksAccountManager( 7650): Authentication error
E/BooksAccountManager( 7650): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7650): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7650): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7650): null auth token
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7650): Error response from books API: {
W/ApiaryClient( 7650):  "error": {
W/ApiaryClient( 7650):   "errors": [
W/ApiaryClient( 7650):    {
W/ApiaryClient( 7650):     "domain": "global",
W/ApiaryClient( 7650):     "reason": "required",
W/ApiaryClient( 7650):     "message": "Login Required",
W/ApiaryClient( 7650):     "locationType": "header",
W/ApiaryClient( 7650):     "location": "Authorization"
W/ApiaryClient( 7650):    }
W/ApiaryClient( 7650):   ],
W/ApiaryClient( 7650):   "code": 401,
W/ApiaryClient( 7650):   "message": "Login Required"
W/ApiaryClient( 7650):  }
W/ApiaryClient( 7650): }
,W/ApiaryClient( 7650): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7650): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5601250970081466203&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7650): Headers:
W/ApiaryClient( 7650): accept-encoding: [gzip]
W/ApiaryClient( 7650): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7650): gdata-version: 2
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7650): Authentication error
E/BooksAccountManager( 7650): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7650): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7650): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7650): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7650): Error response from books API: {
W/ApiaryClient( 7650):  "error": {
W/ApiaryClient( 7650):   "errors": [
W/ApiaryClient( 7650):    {
W/ApiaryClient( 7650):     "domain": "global",
W/ApiaryClient( 7650):     "reason": "required",
W/ApiaryClient( 7650):     "message": "Login Required",
W/ApiaryClient( 7650):     "locationType": "header",
W/ApiaryClient( 7650):     "location": "Authorization"
W/ApiaryClient( 7650):    }
W/ApiaryClient( 7650):   ],
W/ApiaryClient( 7650):   "code": 401,
W/ApiaryClient( 7650):   "message": "Login Required"
W/ApiaryClient( 7650):  }
W/ApiaryClient( 7650): }
,W/ApiaryClient( 7650): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7650): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5601250970081466203&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7650): Headers:
W/ApiaryClient( 7650): accept-encoding: [gzip]
W/ApiaryClient( 7650): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7650): gdata-version: 2
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7650): Authentication error
E/BooksAccountManager( 7650): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7650): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7650): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7650): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7650): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{4b6bca9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7650): Error response from books API: {
W/ApiaryClient( 7650):  "error": {
W/ApiaryClient( 7650):   "errors": [
W/ApiaryClient( 7650):    {
W/ApiaryClient( 7650):     "domain": "global",
W/ApiaryClient( 7650):     "reason": "required",
W/ApiaryClient( 7650):     "message": "Login Required",
W/ApiaryClient( 7650):     "locationType": "header",
W/ApiaryClient( 7650):     "location": "Authorization"
W/ApiaryClient( 7650):    }
W/ApiaryClient( 7650):   ],
W/ApiaryClient( 7650):   "code": 401,
W/ApiaryClient( 7650):   "message": "Login Required"
W/ApiaryClient( 7650):  }
W/ApiaryClient( 7650): }
,W/ApiaryClient( 7650): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7650): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5601250970081466203&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7650): Headers:
W/ApiaryClient( 7650): accept-encoding: [gzip]
W/ApiaryClient( 7650): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7650): gdata-version: 2
,E/BooksSync( 7650): Soft error: 
E/BooksSync( 7650): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7650): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5601250970081466203&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7650): Headers:
E/BooksSync( 7650): accept-encoding: [gzip]
E/BooksSync( 7650): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7650): gdata-version: 2
E/BooksSync( 7650): 
E/BooksSync( 7650): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7650): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7650): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7650): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7650): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7650): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7650): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7650): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7650): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7650): {
E/BooksSync( 7650):  "error": {
E/BooksSync( 7650):   "errors": [
E/BooksSync( 7650):    {
E/BooksSync( 7650):     "domain": "global",
E/BooksSync( 7650):     "reason": "required",
E/BooksSync( 7650):     "message": "Login Required",
E/BooksSync( 7650):     "locationType": "header",
E/BooksSync( 7650):     "location": "Authorization"
E/BooksSync( 7650):    }
E/BooksSync( 7650):   ],
E/BooksSync( 7650):   "code": 401,
E/BooksSync( 7650):   "message": "Login Required"
E/BooksSync( 7650):  }
E/BooksSync( 7650): }
E/BooksSync( 7650): 
E/BooksSync( 7650): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7650): 	... 8 more
,E/BooksSync( 7650): Sync error
E/BooksSync( 7650): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7650): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5601250970081466203&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7650): Headers:
E/BooksSync( 7650): accept-encoding: [gzip]
E/BooksSync( 7650): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7650): gdata-version: 2
E/BooksSync( 7650): 
E/BooksSync( 7650): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7650): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7650): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7650): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7650): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7650): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7650): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7650): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7650): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7650): {
E/BooksSync( 7650):  "error": {
E/BooksSync( 7650):   "errors": [
E/BooksSync( 7650):    {
E/BooksSync( 7650):     "domain": "global",
E/BooksSync( 7650):     "reason": "required",
E/BooksSync( 7650):     "message": "Login Required",
E/BooksSync( 7650):     "locationType": "header",
E/BooksSync( 7650):     "location": "Authorization"
E/BooksSync( 7650):    }
E/BooksSync( 7650):   ],
E/BooksSync( 7650):   "code": 401,
E/BooksSync( 7650):   "message": "Login Required"
E/BooksSync( 7650):  }
E/BooksSync( 7650): }
E/BooksSync( 7650): 
E/BooksSync( 7650): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7650): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7650): 	... 8 more
I/BooksSync( 7650): Finished books sync
I/ActivityManager( 1038): Killing 2235:com.lge.music/u0a34 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166470, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/AudioFlinger(  313): 2235 died, releasing its sessions
V/AudioFlinger(  313):  pid 1872 @ 0
V/AudioFlinger(  313):  pid 3359 @ 1
V/AudioFlinger(  313):  pid 3359 @ 2
W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2235/cgroup.procs: No such file or directory
,I/GAV2    ( 7650): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 177749524311; DSPS: 5965685; Offset : -4325037676
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/HeadsetStateMachine( 3834): Disconnected process message: 10, size: 0
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{3e1c10c9 type 0 when 1455021594694 com.android.vending} when 1455021594694
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6399): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6399): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6399): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 197752190763; DSPS: 6621133; Offset : -4325057058
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=272717402, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{325b0483 type 2 when 199972 android} when 199972
D/[Concierge]Service( 2579): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=272717402 [*alarm*], flags=0x0
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1ccdbe39 type 0 when 1455021618550 com.android.vending} when 1455021618550
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2138): Explicit concurrent mark sweep GC freed 30763(1806KB) AllocSpace objects, 13(1872KB) LOS objects, 51% free, 30MB/62MB, paused 1.935ms total 62.535ms
,D/Finsky  ( 6399): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6399): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6399): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 217754024609; DSPS: 7276553; Offset : -4325053927
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{ed61473 type 2 when 183815 com.google.android.gms} when 183815
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{f53ef30 type 2 when 207613 android} when 207613
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 30751(1323KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 3.133ms total 154.402ms
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2138): Vacuum at: now=1455021637395 tag=VacuumService
,I/GoogleURLConnFactory( 2138): Using platform SSLCertificateSocketFactory
,W/Uploader( 2138): No account for auth token provided
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2138): No account for auth token provided
,W/Uploader( 2138): No account for auth token provided
,W/Uploader( 2138):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 237756126893; DSPS: 7931982; Offset : -4325057539
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
,I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3834): Disconnected process message: 10, size: 0
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated(),
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
I/jxcore-log( 7067): --= Surplus to requirements =--
I/jxcore-log( 7067): 
I/jxcore-log( 7067): ****TEST TOOK:  ms ****
I/jxcore-log( 7067): 
I/jxcore-log( 7067): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7067): 
,D/AndroidRuntime( 7767): 
D/AndroidRuntime( 7767): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7767): CheckJNI is OFF
D/AndroidRuntime( 7767): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7067:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1038): Skipping PackageSetting{24f11b7e com.example.hello/10319} due to missing metadata
,I/WindowState( 1038): WIN DEATH: Window{e6856df u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{e6856df u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3dbb47b8 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
,W/ActivityManager( 1038): Spurious death for ProcessRecord{3c268cf4 7067:com.test.thalitest/u0a311}, curProc for 7067: null
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3dbb47b8 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{3dbb47b8 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2088): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2088): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{bf0a97 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{e5bb484 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2088): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1923): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3667): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2088): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2045): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3667): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,E/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 2088): [Launcher.java:1056:onResume()]onResume end
,D/PostponalbeReceiver( 6660): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4616): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4616): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4616): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4616): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4616): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4616): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4616): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4616): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4616): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4616): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7798 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2088): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1923): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3667): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/SplitUIManager( 1889): split_name #11 / not available #0
D/SplitUIService( 1889): removed split : 
V/BoardContentProvider( 3667): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2088): , create_time: 1430558575574
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2088): , create_time: 1430558575600
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2088): , create_time: 1454599633839
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2fb16f49,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/WallpaperManager( 2088): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIManager( 1889): split_name #11 / not available #0
I/SplitUIService( 1889): split app #11
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 15563(1083KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.192ms total 234.853ms
I/art     ( 4661): Explicit concurrent mark sweep GC freed 24242(1362KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 288us total 249.994ms
,I/art     ( 1038): WaitForGcToComplete blocked for 247.398ms for cause Explicit
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 257760175428; DSPS: 8587475; Offset : -4325067085
I/[LGHome]EVENT( 2088): [Launcher.java:5349:onStop()]onStop
D/AppUp4:PreloadHelper( 7301): added Exclude : com.test.thalitest
I/LockScreenSettings( 7798): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/administrator( 1038): Handling package changes for user 0
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7820 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3834): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
,W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3137): Thermal-Lib-Client: Client request sent
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1038): Killing 7182:com.lge.sync/1000 (adj 15): empty #17
,I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 7820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7820): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/ResourcesManager( 7820): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7820): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7820): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[Concierge]WidgetView( 2088): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1461): handleShortcutListChanged...
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7182/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3fc8bf31 u0 com.lge.launcher2/.Launcher t3} time:257935
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/[Concierge]Service( 2579): onStartCommand(). Type : 8
D/[Concierge]Service( 2579): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2579): Update widget ID : 11
D/[Concierge]WidgetView( 2088): change position of spinner
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
I/[Concierge]WidgetView( 2088): initWebView(). Time : 1455021664740
D/[Concierge]Service( 2579): onStartCommand(). Type : 0
,W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
I/art     ( 1038): Explicit concurrent mark sweep GC freed 8183(448KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.897ms total 211.133ms
D/KeyguardModel( 1461): handleShortcutListChanged...
I/SystemConfig( 7820): BUILD Country: EU
I/SystemConfig( 7820): BUILD Operator: OPEN
,I/[Concierge]WebView( 2088): Return exist ConciergeWebView. Reuse : 44202795
D/[Concierge]WidgetView( 2088): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2088): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@36b5ba89
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2088): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2088): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2088): Widget kill message received. Destory myself. My : 1455021434554, New one : 1455021664740
D/[Concierge]WidgetView( 2088): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2088): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 7767): Shutting down VM
I/ActivityManager( 1038): Killing 7148:com.android.settings/1000 (adj 15): empty #17
,W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2088): Timeline: Activity_idle id: android.os.BinderProxy@631beea time:258066
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7148/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 3834): Disconnected process message: 10, size: 0
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4372): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1038): battery changed pluggedType: 2
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/VoicemailCleanupService( 2168): Cleaning up data for package: com.test.thalitest
I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/SystemConfig( 7820): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7820): existFile = false
I/SystemConfig( 7820): canReadFile = false
I/SystemConfig( 7820): systemFeature RCS result false
D/SystemConfig( 7820): refreshRcsSupport() :false
I/PackageChangeReceiver( 7329): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7844 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7844): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7844): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7844): Total System Memory = 2995761152
,D/SystemHelper( 7844): region [EU], country [EU], operator [OPEN], sub-operator []
I/chromium( 2088): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1038): Killing 7353:com.lge.formmanager/u0a26 (adj 15): empty #17
I/GBoardtInterface( 2088): onReloaded()
,I/GBoardWebViewClient( 2088): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2045): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2045): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1038): failed to open /acct/uid_10026/pid_7353/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2045): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3667): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6660): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3667): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7865 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1923): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3667): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3667): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1923): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3667): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 3667): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3667): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3667): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3667): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,E/SQLiteDatabase( 7865): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 7865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7865): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 7865): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7865): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7865): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7865): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7865): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7865): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 7865): Unable to open database for writing.
E/LifetrackerProvider2( 7865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 7865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 7865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 7865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 7865): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 7865): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 7865): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 7865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 7865): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 7865): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 7865): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 7865): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 7865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 7865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/ActivityThread( 7865): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7865): No ProfileInfo entries
I/LG Account v2.2( 7865): isEnabled: false
I/Feature ( 7865): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7865): [Lifetracker]Country: EU
I/Feature ( 7865): [Lifetracker]Operator: OPEN
I/Feature ( 7865): [Lifetracker]Ranking support: false
I/Feature ( 7865): [Lifetracker]Comfort support: false
I/Feature ( 7865): [Lifetracker]Accessory: true
I/Feature ( 7865): [Lifetracker]Health device: true
I/Feature ( 7865): [Lifetracker]Extra Pedometer: false
I/Feature ( 7865): [Lifetracker]Blood glucose device: false
I/Feature ( 7865): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 7865): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7888 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 7376:com.android.chrome/u0a57 (adj 15): empty #17

```
