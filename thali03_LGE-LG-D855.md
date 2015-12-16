#### Test 506502789b39735_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 46549(2MB) AllocSpace objects, 14(1911KB) LOS objects, 51% free, 30MB/62MB, paused 1.799ms total 76.716ms
--------- beginning of system
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
W/ApiaryClient( 6417): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=336623153098870938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
D/AndroidRuntime( 7088): 
D/AndroidRuntime( 7088): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7088): CheckJNI is OFF
D/AndroidRuntime( 7088): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1944): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{bba62b3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{bba62b3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  336): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7121 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7088): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1858): Display #0 changed.
D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{7c9213 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{373e2c50 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7121): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 7121): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7121): Loading: webviewchromium
I/LibraryLoader( 7121): Time to load native libraries: 3 ms (timestamps 2509-2512)
I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7121): Binding Chromium to main looper Looper (main, tid 1) {250d9683}
,I/LibraryLoader( 7121): Expected native library version number "",actual native library version number ""
I/chromium( 7121): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7121): Initializing chromium process, renderers=0
W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7121): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7121): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7121): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb558a940, uid 10311
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cc7f1a5:true
,I/Adreno-EGL( 7121): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7121): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7121): Build Date: 12/12/14 금
I/Adreno-EGL( 7121): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7121): Remote Branch: 
I/Adreno-EGL( 7121): Local Patches: 
I/Adreno-EGL( 7121): Reconstruct Branch: 
,W/chromium( 7121): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7121): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7121): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7121): CordovaWebView is running on device made by: LGE
,W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7121): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7121): Render dirty regions requested: true
I/OpenGLRenderer( 7121): Initialized EGL, version 1.4
D/OpenGLRenderer( 7121): Enabling debug mode 0
,D/Atlas   ( 7121): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{37c771f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7121): LgDataFeature() Constructor: none
,D/LgDataFeature( 7121): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@15c28a02,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +611ms (total +681ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{11e0c070 u0 com.test.thalitest/.MainActivity t4} time:292990
I/Timeline( 7121): Timeline: Activity_idle id: android.os.BinderProxy@4512673 time:292993
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
I/chromium( 7121): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7121): 
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/JsMessageQueue( 7121): Set native->JS mode to OnlineEventsBridgeMode
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
W/ApiaryClient( 6417): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=336623153098870938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
,D/jxcore_app_log( 7121): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435086080
,D/JX-Cordova( 7121): jxcore cordova android initializing
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
,E/BooksSync( 6417): Soft error: 
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=336623153098870938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
E/BooksSync( 6417): Sync error
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=336623153098870938&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQue,ue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
,I/BooksSync( 6417): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 290301, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/jxcore-log( 7121): Initializing JXcore engine
W/jxcore-log( 7121): JXcore engine is ready
W/jxcore-log( 7121): Starting JXcore engine
W/.test.thalitest( 7121): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8583]" dev="sockfs" ino=8583 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7121): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7121): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7701]" dev="sockfs" ino=7701 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7121): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7121): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34257]" dev="sockfs" ino=34257 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7121): Background sticky concurrent mark sweep GC freed 123779(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.619ms total 130.339ms
W/jxcore-log( 7121): Platform android
W/jxcore-log( 7121): 
W/jxcore-log( 7121): Process ARCH arm
W/jxcore-log( 7121): 
I/jxcore-log( 7121): JXcore Cordova bridge is ready!
I/jxcore-log( 7121): 
W/jxcore-log( 7121): JXcore engine is started
,I/jxcore-log( 7121): Toggling radios to true
I/jxcore-log( 7121): 
,D/BluetoothAdapter( 7121): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=7121, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=7121, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=7121, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [296,224,768 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=7121, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7121): Radios toggled
I/jxcore-log( 7121): 
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7121): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7121): 
I/jxcore-log( 7121): Perf Test app loaded loaded
I/jxcore-log( 7121): 
,I/jxcore-log( 7121): check test folder
I/jxcore-log( 7121): 
I/jxcore-log( 7121): found test : ./testFindPeers.js
I/jxcore-log( 7121): 
I/jxcore-log( 7121): found test : ./testSendData.js
I/jxcore-log( 7121): 
,I/wpa_supplicant( 2627): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/CommandListener(  309): Clearing all IP addresses on wlan0
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7216 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2117): Read error: ssl=0xaf466200: I/O error during system call, Connection timed out
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [296,342,316 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2627): wlan0: CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2117): SSL shutdown failed: ssl=0xaf466200: I/O error during system call, Broken pipe
D/WifiHS20( 1037): hidePasspointNotification off =false
,D/WifiNative-wlan0( 1037): RECONNECT: returned true
V/WfdStateTracker( 1944): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296353
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296354
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): Dns fail occured do internet check.
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1037): try Internet connection check
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296414  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
W/ResourcesManager( 7216): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1037): ThreadTCPConnectionCheck DNS fail internet is not possible
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DSQN    ( 1037): ThreadInternetCheck internet check NOK 
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DSQN    ( 1037): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296419  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/ContextImpl( 1037): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524292
D/WifiDataContinuityService( 1037): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailabl,e: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ResourcesManager( 7216): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
W/ResourcesManager( 7216): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7216): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1858): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296427  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServiceExtension( 1944): isInternetCheckAvailable return false
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/chromium( 7121): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296438  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
I/chromium( 7121): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7121): 
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7121): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7216): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7216): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7216): [AUTORUN] setTetherStatus() : status=false
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6646:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6646/cgroup.procs: No such file or directory
,I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7256): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7216): LgDataFeature() Constructor: none
,D/LgDataFeature( 7216): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7280 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 6075:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6075/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297000359787; DSPS: 9872982; Offset : -4311612820
,W/ResourcesManager( 7280): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7280): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7280): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7280): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7280): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7280): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7280): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7280): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7280): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7280): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7280): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7256): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7256): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7256): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7280): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7280): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7280): LgDataFeature() Constructor: none
D/LgDataFeature( 7280): LgDataFeature() Constructor Done, null
,V/SoundPool( 7280): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7280): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7280): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7280): doLoad: loading sample sampleID=1
I/QRemote ( 7280): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6785): QS Service created
V/SoundPool( 7280): Start decode
V/MediaPlayer[Native]( 7280): decode(31, 10857164, 17813)
,V/MediaPlayerService(  313): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  313): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  313): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  313): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  313): player type = 3
V/AwesomePlayer(  313): AwesomePlayer create()
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): setAudioSink() 
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb14329c0, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
,D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
,V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
,V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
,E/MediaExtractor(  313): Use LGExtractor :application/ogg 
D/QRemote ( 7280): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11,
E/QRemote ( 7280): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,I/UEI.SmartControl( 6785): Service initServices...
D/UEI.SmartControl( 6785): QS start get config
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  313): supported mime: application/ogg
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
,V/OMXCodec(  313): configureCodec protected=0
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
,V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  313): allocateBuffers
V/OMXCodec(  313): allocateBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3290 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3510 on output port
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
V/AudioCache(  313): notify(0xb14329c0, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb14329c0, 1, 0, 0)
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815504
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044816144
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/LGMDMManager( 7280): Create singleton instance
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/O,MXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3290 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb57c36f0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb14329c0, 6, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab700000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab701000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab702000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab703000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab704000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab705000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab706000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab707000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab708000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab709000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70a000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70b000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70c000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70d000, 0xb57d0000, 4096)
D/DSQN    ( 1037): EVENT_INTERNET_CHECK_ENABLE received
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70e000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab70f000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab710000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab711000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab712000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab713000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab714000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab715000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab716000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab717000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab718000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab719000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71a000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71b000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71c000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71d000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71e000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab71f000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab720000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab721000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab722000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab723000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab724000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab725000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab726000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab727000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab728000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab729000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72a000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72b000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72c000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72d000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72e000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab72f000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab730000, 0xb57d0000, 4096)
V/AudioCache(  313): write(0xb57d0000, 4096)
V/AudioCache(  313): memcpy(0xab731000, 0xb57d0000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb57d0000, 280)
V/AudioCache(  313): memcpy(0xab732000, 0xb57d0000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb14329c0, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): notify(0xb14329c0, 7, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  313): Pause Playback at 1068125
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb14329c0, 8, 0, 0)
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb57c36f0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3290 on port 1
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
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): ~AwesomePlayer call
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/SoundPool( 7280): close(31)
V/SoundPool( 7280): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7280): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7268
I/UEI.SmartControl( 6785): Supports setup maps: true
,D/UEI.SmartControl( 6785): QS start statue = true Error code = 0
I/UEI.SmartControl( 6785): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6785): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6785): ### init IR Blaster...
D/serial_port( 6785): Configuring serial port
E/UEI.SmartControl( 6785): UEIBLaster setting for 616
I/UEI.SmartControl( 6785): Setting serial record hearder size = 2
I/UEI.SmartControl( 6785): configuring settings for MAXQ616
I/UEI.SmartControl( 6785): Get version...
D/UEI.SmartControl( 6785): serial port data available: 21
,D/UEI.SmartControl( 6785): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6785): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6785): QS saving settings...
,D/UEI.SmartControl( 6785): IR Blaster version: 25672567
,D/UEI.SmartControl( 6785): serial port data available: 4
,I/UEI.SmartControl( 6785): Device manager: loading config....
,D/UEI.SmartControl( 6785): ----------- loading internal config...
,W/ContextImpl( 6785): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6785): Services init done
D/UEI.SmartControl( 6785): QS Service init finished
D/UEI.SmartControl( 6785): QS Service version name: 2.1.91
D/UEI.SmartControl( 6785): QS Service version code: 201091
D/UEI.SmartControl( 6785): Service requested: Control
D/UEI.SmartControl( 6785): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6785): Loading SETTINGS...
,I/QRemote ( 7280): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6785): Internal service binding...
I/UEI.SmartControl( 6785): ------ IControl API: 11
D/UEI.SmartControl( 6785): File observer start...
E/UEI.SmartControl( 6785): IR Port is disabled: false
D/UEI.SmartControl( 6785): Starting file observer...
I/UEI.SmartControl( 6785): Registering callback...
I/UEI.SmartControl( 6785): ------ IControl API: 19
I/UEI.SmartControl( 6785): Registering Services Ready callback...
D/UEI.SmartControl( 6785): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6785): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6785): -----service ready thread exits
I/QRemote ( 7280): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7280): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7280): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7280): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7280): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6785): ------ IControl API: 8
D/QRemote ( 7280): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7280): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7280): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7280): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7280): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7280): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7280): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7280): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7280): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7280): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7280): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450229855598]
D/QRemote ( 7280): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1037): Killing 6098:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7280): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6098/cgroup.procs: No such file or directory
,V/QRemote ( 7280): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7280): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7280): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 7280): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7280): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2627): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=298475  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=298506  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2627): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2627): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2627): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298580  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=298581  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298592
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298592
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298592
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298602
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298602
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298606  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=298634  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298636  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=298643  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298645
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298646
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
,D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7216): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7216): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7216): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7216): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7216): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
,D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
,E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298715  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=298716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298722  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298723  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=298723  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39604782 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@39604782 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2627): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): SET ps 1: returned true
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WfdStateTracker( 1944): handleWifiStateChangedEvent: 1
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  309): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
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
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1858): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
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
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
W/dsqn    ( 7352): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7352): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7352): DSQN ssw
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7280): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
,D/QRemote ( 7280): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7280): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7280): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7256): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7256): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
,W/dhcpcd  ( 7358): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 7216): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/dhcpcd  ( 7358): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7358): version 5.5.6 starting
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:37:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229856670], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229856651]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/WiFiOffLoadBroadcast( 7216): MCCMNC not supported: null
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
E/dhcpcd  ( 7358): get_duid: m
D/dhcpcd  ( 7358): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7358): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory-1( 1858): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1858):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 7280): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7280): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7280): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7280): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7280): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7358): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7358): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7358): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7358): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7358): wlan0: sending REQUEST (xid 0x8b65540d), next in 4.44 seconds
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5813): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5813): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7387 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 380us total 19.073ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 663us total 19.371ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 15.421ms
,I/AppUp4:AppBoxCP( 7387): onCreate
W/AppUp4:DB( 7387):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7387):  setFingerPrint start
,I/AppUp4:DB( 7387):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7387):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7387):  SDK version = 21
,I/AppUp4:DB( 7387):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7387): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7387): onReceive
D/LgDataFeature( 7387): LgDataFeature() Constructor: none
,D/LgDataFeature( 7387): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7387): Context : android.app.ReceiverRestrictedContext@37dfa039
D/AppUp4:CustFacade( 7387): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7387): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7387): begin check event
I/AppUp4:CustModeStarterReceiver( 7387): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7387): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7387): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7387): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7387): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6671:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6671/cgroup.procs: No such file or directory
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3349): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3349): DownloadService onCreate
,D/LGDMClient( 4306): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4306): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3349): in removeSpuriousFiles
V/DownloadManager( 3349): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@4fa2524 on behalf of 3349
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3349): in trimDatabase
,V/DownloadManager( 3349): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@2194fa42 on behalf of 3349
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7421 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3349): DownloadService onStartCommand
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3349): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4306): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@1a466f90 on behalf of 3349
D/LGDMClient( 4306): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4306): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3349): processing inserted download 1
V/DownloadManager( 3349): processing inserted download 4
V/DownloadManager( 3349): processing inserted download 7
V/DownloadManager( 3349): processing inserted download 8
V/DownloadManager( 3349): processing inserted download 9
V/DownloadManager( 3349): processing inserted download 10
V/DownloadManager( 3349): processing inserted download 16
V/DownloadManager( 3349): processing inserted download 17
V/DownloadManager( 3349): processing inserted download 18
V/DownloadManager( 3349): processing inserted download 21
,V/DownloadManager( 3349): DownloadService onDestroy
,W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7421): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7421): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7421): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7421): LgDataFeature() Constructor: none
,D/LgDataFeature( 7421): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7358): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7358): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7358): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7358): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7358): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7358): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7358): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7358): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7358): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/eas_req ( 7421): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7454 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524295
I/HubEmail( 7421): JNI_OnLoad()
I/HubEmail( 7421): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7421): registerNatives()
,I/HubEmail( 7421): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7421): registerNativeMethods()
I/HubEmail( 7421): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7421): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6531:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6531/cgroup.procs: No such file or directory
,W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3321): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3321): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7493 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7516 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6698:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6698/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7533 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6724:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6724/cgroup.procs: No such file or directory
,I/art     ( 7533): Almond Protected OAT
,D/WeatherApplication( 7533): removeAccount
,D/WeatherApplication( 7533): Account.length = 0
E/WeatherApplication( 7533): OPERATOR:OPEN
D/WeatherAncestor( 7533): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:38
D/Weather.Utils( 7533): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7533): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7533): 2 : This is isUpdating : false
,D/WeatherAncestor( 7533): connectivity changed - connection : true
D/WeatherService( 7533): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7533): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7533): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7533): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7533): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7533): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:38
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7551 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6764:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6764/cgroup.procs: No such file or directory
,I/jxcore-log( 7121): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7121): 
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7551): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7454): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7454): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Killing 6842:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6842/cgroup.procs: No such file or directory
,I/WebViewFactory( 7551): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7551): Loading: webviewchromium
,I/LibraryLoader( 7551): Time to load native libraries: 5 ms (timestamps 1683-1688)
I/LibraryLoader( 7551): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7551): Binding Chromium to main looper Looper (main, tid 1) {32085e48}
,I/LibraryLoader( 7551): Expected native library version number "",actual native library version number ""
I/chromium( 7551): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7551): Initializing chromium process, renderers=0
W/art     ( 7551): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7551): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7551): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7551): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb57bed00, uid 10093
W/AudioManagerAndroid( 7551): Requires BLUETOOTH permission
I/Adreno-EGL( 7551): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7551): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7551): Build Date: 12/12/14 금
I/Adreno-EGL( 7551): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7551): Remote Branch: 
I/Adreno-EGL( 7551): Local Patches: 
I/Adreno-EGL( 7551): Reconstruct Branch: 
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5813): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 7551): Starting up...
I/ActivityManager( 1037): Killing 6875:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6875/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 85951(4MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 3.228ms total 163.014ms
,I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7387): onReceive
,D/AppUp4:CustFacade( 7387): Context : android.app.ReceiverRestrictedContext@37dfa039
D/AppUp4:CustFacade( 7387): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7387): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7387): begin check event
I/AppUp4:CustModeStarterReceiver( 7387): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3349): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3349): DownloadService onCreate
I/DownloadManager( 3349): in removeSpuriousFiles
V/DownloadManager( 3349): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@32fc788e on behalf of 3349
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4306): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3349): in trimDatabase
V/DownloadManager( 3349): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LGDMClient( 4306): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@2e0ec8af on behalf of 3349
D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3321): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3321): networkInfo.isConnected() = false
V/DownloadManager( 3349): DownloadService onStartCommand
,V/DownloadManager( 3349): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@104b8f9a on behalf of 3349
V/DownloadManager( 3349): processing inserted download 1
,V/DownloadManager( 3349): processing inserted download 4
V/DownloadManager( 3349): processing inserted download 7
V/DownloadManager( 3349): processing inserted download 8
V/DownloadManager( 3349): processing inserted download 9
V/DownloadManager( 3349): processing inserted download 10
V/DownloadManager( 3349): processing inserted download 16
W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7533): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:39
V/DownloadManager( 3349): processing inserted download 17
V/DownloadManager( 3349): processing inserted download 18
V/DownloadManager( 3349): processing inserted download 21
D/Weather.Utils( 7533): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7533): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7533): 2 : This is isUpdating : false
D/WeatherAncestor( 7533): connectivity changed - connection : true
D/WeatherService( 7533): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b0917df
D/ForecastDataCache( 7533): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7533): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7533): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7533): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7533): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:39
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4306): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4306): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4306): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3349): DownloadService onDestroy
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 7454): There are no updated forms. The schedule will be deleted.
V/FormManager( 7454): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6606): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7387): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7387): onReceive
,D/AppUp4:CustFacade( 7387): Context : android.app.ReceiverRestrictedContext@37dfa039
D/AppUp4:CustFacade( 7387): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7387): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7387): begin check event
I/AppUp4:CustModeStarterReceiver( 7387): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 4306): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4306): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3349): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4306): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3349): DownloadService onCreate
,I/DownloadManager( 3349): in removeSpuriousFiles
,V/DownloadManager( 3349): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@ab0a0a8 on behalf of 3349
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3349): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3349): in trimDatabase
V/DownloadManager( 3349): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4306): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4306): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4306): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@817c7c1 on behalf of 3349
V/DownloadManager( 3349): DownloadService onStartCommand
,V/DownloadManager( 3349): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@1fc31f54 on behalf of 3349
V/DownloadManager( 3349): processing inserted download 1
V/DownloadManager( 3349): processing inserted download 4
V/DownloadManager( 3349): processing inserted download 7
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3349): processing inserted download 8
V/DownloadManager( 3349): processing inserted download 9
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/LgeMiscReceiver( 3321): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3321): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3321): networkInfo.isConnected() = true
D/PhoneState( 3321): setPdpRejectCasuse : false
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
W/Settings( 7421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
V/DownloadManager( 3349): processing inserted download 10
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
V/DownloadManager( 3349): processing inserted download 16
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
V/DownloadManager( 3349): processing inserted download 17
V/DownloadManager( 3349): processing inserted download 18
,V/DownloadManager( 3349): processing inserted download 21
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/WeatherAncestor( 7533): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:40
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
D/Weather.Utils( 7533): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7533): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7533): 2 : This is isUpdating : false
D/WeatherAncestor( 7533): connectivity changed - connection : true
D/WeatherService( 7533): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1b0917df
V/DownloadManager( 3349): DownloadService onDestroy
D/ForecastDataCache( 7533): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7533): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7533): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7533): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7533): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:37:40
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7454): There are no updated forms. The schedule will be deleted.
V/FormManager( 7454): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1402): Notification difference=198
,D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6785): Internal timer expired: 3
,D/UEI.SmartControl( 6785): unbind internal service
,I/jxcore-log( 7121): Connected to the server!
I/jxcore-log( 7121): 
,I/chromium( 7121): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
D/serial_port( 6785): close(fd = 24)
I/UEI.SmartControl( 6785): Serial port is closed.
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2faac414 type 2 when 306323 com.google.android.gms} when 306323
,V/QRemote ( 7280): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/QRemote ( 7280): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7268
I/GAV4    ( 7551): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2117): Connected
,D/GCM     ( 2117): Message class com.google.f.a.a.p
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317003157539; DSPS: 10528433; Offset : -4311593523
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{837a03 type 2 when 320368 android} when 320368
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337005359980; DSPS: 11183865; Offset : -4311588268
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357007304868; DSPS: 11839289; Offset : -4311596480
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6190): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6190): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6190): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6190): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6190): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6190): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6190): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6190): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377009307620; DSPS: 12494715; Offset : -4311608096
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{317c572d type 2 when 381310 android} when 381310
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397011948134; DSPS: 13150161; Offset : -4311591807
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417013983282; DSPS: 13805588; Offset : -4311601494
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1944): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1944): Battery Level Remaining: 100%
D/LEDHandler( 1944): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3772): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437015897858; DSPS: 14461011; Offset : -4311609473
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457017932590; DSPS: 15116437; Offset : -4311588902
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477019512582; DSPS: 15771849; Offset : -4311595771
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497022267418; DSPS: 16427299; Offset : -4311587622
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517024465692; DSPS: 17082731; Offset : -4311586613
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{e4f0462 type 2 when 534703 android} when 534703
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,I/BooksSync( 6417): Starting books sync
,D/BooksSync( 6417): started syncMyEbooks
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3372976445156889172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
,W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3372976445156889172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537026471413; DSPS: 17738157; Offset : -4311595156
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3372976445156889172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
E/BooksSync( 6417): Soft error: 
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3372976445156889172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
,E/BooksSync( 6417): Sync error
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3372976445156889172&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
I/BooksSync( 6417): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 534703, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557028581927; DSPS: 18393586; Offset : -4311590250
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{38cf4a3c type 2 when 564912 android} when 564912
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577030603378; DSPS: 19049012; Offset : -4311582700
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 597032650870; DSPS: 19704440; Offset : -4311610741
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 617034485342; DSPS: 20359860; Offset : -4311607272
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 637036360907; DSPS: 21015281; Offset : -4311593123
,I/ActivityManager( 1037): Killing 6898:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6898/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 657037994857; DSPS: 21670695; Offset : -4311607304
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 677040735892; DSPS: 22326145; Offset : -4311612721
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 697042730467; DSPS: 22981570; Offset : -4311601919
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 717044711189; DSPS: 23636995; Offset : -4311604708
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{3f4913c5 type 0 when 1450230150788 com.google.android.gms} when 1450230150788
,D/Finsky  ( 6190): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{b63b44b type 0 when 1450230273207 com.android.vending} when 1450230273207
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6190): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6190): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 33547(1525KB) AllocSpace objects, 8(1024KB) LOS objects, 33% free, 44MB/66MB, paused 1.457ms total 154.504ms
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,I/EventLogService( 2316): Aggregate from 1450228350697 (log), 1450228350697 (data)
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6190): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6190): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6190): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6190): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
D/DeviceConnectionService( 1823): client connected with version: 7571000
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 737046945921; DSPS: 24292428; Offset : -4311597838
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{150d0d91 type 0 when 1450230298414 com.android.vending} when 1450230298414
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6190): [1] 5.onFinished: Scheduling replication attempt 1.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7789 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7789): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7789): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@22a94932
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
I/ActivityManager( 1037): Killing 7256:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7256/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 757049235704; DSPS: 24947863; Offset : -4311596745
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1928e2e8 type 0 when 1450230319507 com.android.vending} when 1450230319507
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6190): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 777051708093; DSPS: 25603304; Offset : -4311596383
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{37f225fb type 0 when 1450230348448 com.android.vending} when 1450230348448
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 39433(2MB) AllocSpace objects, 21(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.403ms total 38.782ms
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6190): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 797053854283; DSPS: 26258734; Offset : -4311586397
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 817055659171; DSPS: 26914154; Offset : -4311612643
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{11fb6b3a type 0 when 1450230373481 com.android.vending} when 1450230373481
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6190): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 837057291612; DSPS: 27569567; Offset : -4311597606
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1abc7ed5 type 0 when 1450230407548 com.android.vending} when 1450230407548
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6190): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 857059178166; DSPS: 28224989; Offset : -4311603220
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 877061963211; DSPS: 28880440; Offset : -4311595171
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{bf69bbc type 0 when 1450230431663 com.android.vending} when 1450230431663
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6190): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6190): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6190): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 897072015808; DSPS: 29536130; Offset : -4311613167
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 917074101841; DSPS: 30191558; Offset : -4311602407
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 937076144855; DSPS: 30846985; Offset : -4311604228
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,W/bt-smp  ( 3772): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3772): Plain text(LSB ~ MSB) = 0a 86 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3772): Encrypted text(LSB ~ MSB) = 4f 05 e7 4a ef 88 ba 50 f9 78 e9 c5 27 b7 45 13 
,W/bt-btm  ( 3772): Stopping oneshot timer
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2f73703e type 2 when 942243 com.android.bluetooth} when 942243
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 957078168857; DSPS: 31502411; Offset : -4311594177
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 977079929058; DSPS: 32157829; Offset : -4311604203
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 997081967645; DSPS: 32813256; Offset : -4311610242
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1017083840189; DSPS: 33468677; Offset : -4311599375
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2e4dde9f type 2 when 1019910 android} when 1019910
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,I/BooksSync( 6417): Starting books sync
,D/BooksSync( 6417): started syncMyEbooks
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-960705271188890772&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-960705271188890772&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 25116(1031KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 3.799ms total 187.959ms
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-960705271188890772&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
E/BooksSync( 6417): Soft error: 
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-960705271188890772&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
,E/BooksSync( 6417): Sync error
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-960705271188890772&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
I/BooksSync( 6417): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1019910, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1037086149504; DSPS: 34124113; Offset : -4311609344
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2e151911 type 2 when 1050264 android} when 1050264
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1057088175538; DSPS: 34779539; Offset : -4311597417
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1077090306364; DSPS: 35434969; Offset : -4311602744
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1097092474951; DSPS: 36090400; Offset : -4311600905
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1117094381245; DSPS: 36745822; Offset : -4311586831
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1137096475455; DSPS: 37401251; Offset : -4311598438
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1157098296229; DSPS: 38056671; Offset : -4311608666
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1177101113722; DSPS: 38712123; Offset : -4311598765
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1197103228089; DSPS: 39367552; Offset : -4311590215
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1217105269436; DSPS: 40022979; Offset : -4311593571
,I/UsageStatsService( 1037): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{c50a76 type 2 when 1206678 com.google.android.gms} when 1206678
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/GCM     ( 2117): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1237107473646; DSPS: 40678411; Offset : -4311586367
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1257109357389; DSPS: 41333833; Offset : -4311594792
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1277111677902; DSPS: 41989269; Offset : -4311593485
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1297113751696; DSPS: 42644697; Offset : -4311594990
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1317115955752; DSPS: 43300129; Offset : -4311588252
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1337117503244; DSPS: 43955540; Offset : -4311597208
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1357123700788; DSPS: 44611103; Offset : -4311594576
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1377125573385; DSPS: 45266524; Offset : -4311583734
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1397127279471; DSPS: 45921941; Offset : -4311617176
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1417129203732; DSPS: 46577364; Offset : -4311615444
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1437131083519; DSPS: 47232785; Offset : -4311597073
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1457133118979; DSPS: 47888212; Offset : -4311606578
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1477134988451; DSPS: 48543633; Offset : -4311598521
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1497136921516; DSPS: 49199056; Offset : -4311588220
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/LEDHandler( 1944): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1944): Battery Level Remaining: 100%
D/LEDHandler( 1944): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3772): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4306): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1517138926508; DSPS: 49854482; Offset : -4311597388
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1537141078272; DSPS: 50509913; Offset : -4311612269
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1557143095139; DSPS: 51165339; Offset : -4311609614
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1577145144141; DSPS: 51820766; Offset : -4311605159
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1597146881113; DSPS: 52476183; Offset : -4311607767
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1617148495324; DSPS: 53131596; Offset : -4311610857
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1637150983755; DSPS: 53787037; Offset : -4311594585
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7789): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 7789): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@22a94932
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1657152897132; DSPS: 54442460; Offset : -4311603711
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1677154719260; DSPS: 55097880; Offset : -4311612663
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1697156616648; DSPS: 55753302; Offset : -4311607391
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1717158528619; DSPS: 56408724; Offset : -4311587458
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1737160671060; DSPS: 57064155; Offset : -4311611765
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1757162747928; DSPS: 57719583; Offset : -4311610093
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1777164830628; DSPS: 58375011; Offset : -4311602641
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1797166720100; DSPS: 59030433; Offset : -4311605180
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1817168528321; DSPS: 59685852; Offset : -4311597653
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1837170744147; DSPS: 60341285; Offset : -4311609506
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,W/bt-smp  ( 3772): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3772): Plain text(LSB ~ MSB) = 37 b8 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3772): Encrypted text(LSB ~ MSB) = 0d 73 de 77 0c 0a 0c af 13 cb 23 71 7d e4 8e e1 
,W/bt-btm  ( 3772): Stopping oneshot timer
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{37a45ce4 type 2 when 1842270 com.android.bluetooth} when 1842270
I/ProcessStatsService( 1037): Prepared write state in 21ms
,I/ProcessStatsService( 1037): Prepared write state in 20ms
,D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,I/ProcessStatsService( 1037): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-48.bin
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1857172906119; DSPS: 60996715; Offset : -4311583581
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1877174727569; DSPS: 61652135; Offset : -4311593369
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1897176653238; DSPS: 62307558; Offset : -4311590254
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1917178521981; DSPS: 62962979; Offset : -4311582902
I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1937180520880; DSPS: 63618405; Offset : -4311598267
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1957182380403; DSPS: 64273826; Offset : -4311600316
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1977184277114; DSPS: 64929248; Offset : -4311595903
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1a1354d type 2 when 1986322 android} when 1986322
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,I/BooksSync( 6417): Starting books sync
,D/BooksSync( 6417): started syncMyEbooks
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4512170069685200292&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4512170069685200292&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1402): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1402): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1402): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1402): handleNotificationPosted(true)
D/QuickCircle( 1402): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1402): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): post do just update job
D/LgeQuickCoverNotificationData( 1402): showAll3
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1402): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1402): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1402): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1402): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1402): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6417): Authentication error
E/BooksAccountManager( 6417): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6417): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6417): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6417): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6417): null auth token
,D/QuickStatusbarLayout( 1402): Notification difference=198
D/QuickStatusbarLayout( 1402): child = android.widget.LinearLayout{817c7c1 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6417): Error response from books API: {
W/ApiaryClient( 6417):  "error": {
W/ApiaryClient( 6417):   "errors": [
W/ApiaryClient( 6417):    {
W/ApiaryClient( 6417):     "domain": "global",
W/ApiaryClient( 6417):     "reason": "required",
W/ApiaryClient( 6417):     "message": "Login Required",
W/ApiaryClient( 6417):     "locationType": "header",
W/ApiaryClient( 6417):     "location": "Authorization"
W/ApiaryClient( 6417):    }
W/ApiaryClient( 6417):   ],
W/ApiaryClient( 6417):   "code": 401,
W/ApiaryClient( 6417):   "message": "Login Required"
,W/ApiaryClient( 6417):  }
W/ApiaryClient( 6417): }
,W/ApiaryClient( 6417): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4512170069685200292&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6417): Headers:
W/ApiaryClient( 6417): accept-encoding: [gzip]
W/ApiaryClient( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6417): gdata-version: 2
E/BooksSync( 6417): Soft error: 
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4512170069685200292&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
,E/BooksSync( 6417): Sync error
E/BooksSync( 6417): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6417): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4512170069685200292&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6417): Headers:
E/BooksSync( 6417): accept-encoding: [gzip]
E/BooksSync( 6417): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6417): gdata-version: 2
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6417): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6417): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6417): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6417): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6417): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6417): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6417): {
E/BooksSync( 6417):  "error": {
E/BooksSync( 6417):   "errors": [
E/BooksSync( 6417):    {
E/BooksSync( 6417):     "domain": "global",
E/BooksSync( 6417):     "reason": "required",
E/BooksSync( 6417):     "message": "Login Required",
E/BooksSync( 6417):     "locationType": "header",
E/BooksSync( 6417):     "location": "Authorization"
E/BooksSync( 6417):    }
E/BooksSync( 6417):   ],
E/BooksSync( 6417):   "code": 401,
E/BooksSync( 6417):   "message": "Login Required"
E/BooksSync( 6417):  }
E/BooksSync( 6417): }
E/BooksSync( 6417): 
E/BooksSync( 6417): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6417): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6417): 	... 8 more
I/BooksSync( 6417): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1986322, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 1997186488148; DSPS: 65584681; Offset : -4311612496
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=388480687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3657014f type 2 when 2016758 android} when 2016758
D/[Concierge]Service( 2634): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=388480687 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2017188388870; DSPS: 66240103; Offset : -4311603865
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2037190617404; DSPS: 66895536; Offset : -4311603296
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2057192490729; DSPS: 67550957; Offset : -4311591388
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2077194199108; DSPS: 68206373; Offset : -4311592018
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2097196339933; DSPS: 68861803; Offset : -4311587424
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 2117198093050; DSPS: 69517221; Offset : -4311604404
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,TIME-OUT KILL (timeout was 1800000ms)
```
