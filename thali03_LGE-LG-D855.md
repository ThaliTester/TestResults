#### Test 50650278d1b06e8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
W/ApiaryClient( 6919): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2227830247704640798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,D/AndroidRuntime( 7035): 
D/AndroidRuntime( 7035): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7035): CheckJNI is OFF
D/AndroidRuntime( 7035): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{34731675 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{34731675 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7055 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7035): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{270a28ee co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{de0218f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7055): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7055): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7055): Loading: webviewchromium
,I/LibraryLoader( 7055): Time to load native libraries: 3 ms (timestamps 6115-6118)
,I/LibraryLoader( 7055): Expected native library version number "",actual native library version number ""
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 7055): Binding Chromium to main looper Looper (main, tid 1) {38c3f41e}
,I/LibraryLoader( 7055): Expected native library version number "",actual native library version number ""
I/chromium( 7055): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 7055): Initializing chromium process, renderers=0
,W/art     ( 7055): Attempt to remove local handle scope entry from IRT, ignoring
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/AudioPolicyService(  314): registerClient() client 0xb54ecde0, uid 10311
W/chromium( 7055): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7055): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7055): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fb786e5:true
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Adreno-EGL( 7055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7055): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7055): Build Date: 12/12/14 금
I/Adreno-EGL( 7055): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7055): Remote Branch: 
I/Adreno-EGL( 7055): Local Patches: 
I/Adreno-EGL( 7055): Reconstruct Branch: 
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2227830247704640798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,W/chromium( 7055): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7055): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7055): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7055): onDetachedFromWindow called when already detached. Ignoring
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 296345041921; DSPS: 9851971; Offset : -4324876607
D/SystemWebViewEngine( 7055): CordovaWebView is running on device made by: LGE
,W/art     ( 7055): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7055): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7055): Render dirty regions requested: true
I/OpenGLRenderer( 7055): Initialized EGL, version 1.4
D/OpenGLRenderer( 7055): Enabling debug mode 0
,D/Atlas   ( 7055): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{2239ad37 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7055): LgDataFeature() Constructor: none
,D/LgDataFeature( 7055): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@333d6eac,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +635ms (total +712ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{3956660a u0 com.test.thalitest/.MainActivity t4} time:296568
,I/Timeline( 7055): Timeline: Activity_idle id: android.os.BinderProxy@1063a0ce time:296570
I/chromium( 7055): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7055): 
,D/JsMessageQueue( 7055): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7055): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435100416
D/JX-Cordova( 7055): jxcore cordova android initializing
,E/BooksSync( 6919): Soft error: 
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2227830247704640798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
E/BooksSync( 6919): Sync error
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2227830247704640798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
I/BooksSync( 6919): Finished books sync
,D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293501, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7055): Initializing JXcore engine
W/jxcore-log( 7055): JXcore engine is ready
W/jxcore-log( 7055): Starting JXcore engine
W/.test.thalitest( 7055): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7457]" dev="sockfs" ino=7457 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7055): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7055): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10481]" dev="sockfs" ino=10481 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7055): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7055): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33440]" dev="sockfs" ino=33440 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7055): Background sticky concurrent mark sweep GC freed 123271(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.657ms total 126.414ms
W/jxcore-log( 7055): Platform android
W/jxcore-log( 7055): 
W/jxcore-log( 7055): Process ARCH arm
W/jxcore-log( 7055): 
,I/jxcore-log( 7055): JXcore Cordova bridge is ready!
I/jxcore-log( 7055): 
W/jxcore-log( 7055): JXcore engine is started
I/jxcore-log( 7055): Toggling radios to true
I/jxcore-log( 7055): 
D/BluetoothAdapter( 7055): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=7055, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=7055, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1036): disconnect pid=7055, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1036): [300,174,824 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1036): reconnect pid=7055, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7055): Radios toggled
I/jxcore-log( 7055): 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7055): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7055): 
I/jxcore-log( 7055): Perf Test app loaded loaded
I/jxcore-log( 7055): 
I/jxcore-log( 7055): check test folder
I/jxcore-log( 7055): 
I/jxcore-log( 7055): found test : ./testFindPeers.js
I/jxcore-log( 7055): 
I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1036): InitialState.processMessage what=4
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DhcpStateMachine( 1036): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/CommandListener(  306): Clearing all IP addresses on wlan0
I/jxcore-log( 7055): found test : ./testSendData.js
I/jxcore-log( 7055): 
V/NativeCrypto( 2135): Read error: ssl=0xaf4d6e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaf4d6e00: I/O error during system call, Broken pipe
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/WifiHS20( 1036): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): hidePasspointNotification off =false
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 1036): [300,329,132 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-SCAN-STARTED 
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 7055): found test : ./testSendData2.js
I/jxcore-log( 7055): 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=300339
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=300339
E/jxcore  ( 7055): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 7055): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/LGWifiP2pService( 1036): InactiveState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
W/ResourcesManager( 7136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/chromium( 7055): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourcesManager( 7136): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7136): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
I/chromium( 7055): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7055): 
W/ResourcesManager( 7136): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7136): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/CommandListener(  306): Clearing all IP addresses on wlan0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1036): hidePasspointNotification off =false
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=300379  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=300380  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=300383  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1036): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=300389  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7055): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-108ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7136): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7136): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7136): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7136): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7173 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6072:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6072/cgroup.procs: No such file or directory
,I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7173): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7136): LgDataFeature() Constructor: none
,D/LgDataFeature( 7136): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
,I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7197 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1036): Killing 6093:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6093/cgroup.procs: No such file or directory
,W/ResourcesManager( 7197): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7197): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7197): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7197): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7197): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7197): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7197): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7197): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7197): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7197): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7197): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7173): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7173): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7173): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7197): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7197): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7197): LgDataFeature() Constructor: none
D/LgDataFeature( 7197): LgDataFeature() Constructor Done, null
,V/SoundPool( 7197): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7197): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7197): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7197): doLoad: loading sample sampleID=1
I/QRemote ( 7197): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7197): Start decode
V/MediaPlayer[Native]( 7197): decode(31, 10857164, 17813)
,D/UEI.SmartControl( 6744): QS Service created
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
,W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474e40, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
D/QRemote ( 7197): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7197): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 6744): Service initServices...
D/UEI.SmartControl( 6744): QS start get config
V/LGMDMManager( 7197): Create singleton instance
,V/LGParserOSAL(  314): supported mime: application/ogg
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff100 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff330 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff470 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff6a0 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb5474e40, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb5474e40, 1, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045060864
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045061424
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045061744
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045062304
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff470 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff330 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff100 on output port
V/OMXCodec(  314): [OMX.google.vorbi,s.decoder] allocated buffer 0xb14fc7e0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb5474e40, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab700000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab701000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab702000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab703000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab704000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab705000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab706000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab707000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab708000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab709000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70a000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70b000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70c000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70d000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70e000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab70f000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab710000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab711000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab712000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab713000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab714000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab715000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab716000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab717000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab718000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab719000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71a000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71b000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71c000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71d000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71e000, 0xb173c000, 4096)
,V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab71f000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab720000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab721000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab722000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab723000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab724000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab725000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab726000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab727000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab728000, 0xb173c000, 4096)
,V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab729000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72a000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72b000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72c000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72d000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72e000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab72f000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab730000, 0xb173c000, 4096)
V/AudioCache(  314): write(0xb173c000, 4096)
V/AudioCache(  314): memcpy(0xab731000, 0xb173c000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb173c000, 280)
V/AudioCache(  314): memcpy(0xab732000, 0xb173c000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb5474e40, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb5474e40, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474e40, 8, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
,V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57ff100 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57ff330 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57ff470 on port 1
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
V/SoundPool( 7197): close(31)
V/SoundPool( 7197): pointer = 0x9ff42000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7197): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8818
I/UEI.SmartControl( 6744): Supports setup maps: true
,D/UEI.SmartControl( 6744): QS start statue = true Error code = 0
I/UEI.SmartControl( 6744): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6744): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6744): ### init IR Blaster...
D/serial_port( 6744): Configuring serial port
E/UEI.SmartControl( 6744): UEIBLaster setting for 616
I/UEI.SmartControl( 6744): Setting serial record hearder size = 2
I/UEI.SmartControl( 6744): configuring settings for MAXQ616
I/UEI.SmartControl( 6744): Get version...
D/UEI.SmartControl( 6744): serial port data available: 21
,D/UEI.SmartControl( 6744): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6744): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6744): QS saving settings...
D/UEI.SmartControl( 6744): IR Blaster version: 25672567
,D/UEI.SmartControl( 6744): serial port data available: 4
,W/ContextImpl( 6744): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6744): Device manager: loading config....
D/UEI.SmartControl( 6744): ----------- loading internal config...
,E/UEI.SmartControl( 6744): Services init done
D/UEI.SmartControl( 6744): QS Service init finished
D/UEI.SmartControl( 6744): QS Service version name: 2.1.91
D/UEI.SmartControl( 6744): QS Service version code: 201091
D/UEI.SmartControl( 6744): Service requested: Control
E/UEI.SmartControl( 6744): Loading SETTINGS...
D/UEI.SmartControl( 6744): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6744): Internal service binding...
,I/QRemote ( 7197): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6744): ------ IControl API: 11
D/UEI.SmartControl( 6744): File observer start...
E/UEI.SmartControl( 6744): IR Port is disabled: false
D/UEI.SmartControl( 6744): Starting file observer...
I/UEI.SmartControl( 6744): Registering callback...
I/UEI.SmartControl( 6744): ------ IControl API: 19
I/UEI.SmartControl( 6744): Registering Services Ready callback...
D/UEI.SmartControl( 6744): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6744): Notify AllClients services are ready: 0
,I/QRemote ( 7197): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6744): -----service ready thread exits
D/QRemote ( 7197): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7197): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7197): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7197): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6744): ------ IControl API: 8
D/QRemote ( 7197): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7197): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7197): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7197): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7197): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7197): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7197): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7197): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7197): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7197): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7197): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450655726550]
D/QRemote ( 7197): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6598:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 7197): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6598/cgroup.procs: No such file or directory
,V/QRemote ( 7197): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7197): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7197): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2748): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE-AUTH 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
,E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=302470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=302491  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
I/wpa_supplicant( 2748): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2748): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=302585  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=302586  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=302592
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=302593
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=302598
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=302598
,E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=302603
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=302604  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=302620  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=302623  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=302623  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=302625
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=302625
,D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7136): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7136): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7136): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7136): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7136): [AUTORUN] setTetherStatus() : status=false
,I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 1036): Got NetworkAgent Messenger
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1036): NetworkAgent connected
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  306): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=302698  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1036): WaitBeforeStartState
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=302698  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=302699  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATED
,E/WifiStateMachine( 1036):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=302706  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=302707  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=302707  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
,V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@271d6d34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@271d6d34 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  306): Setting iface cfg
D/CommandListener(  306): Trying to bring up wlan0
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
I/wpa_supplicant( 2748): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 1
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  306): netlink response contains error (File exists)
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService(, 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
W/dsqn    ( 7283): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7283): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
E/DSQN    ( 7283): DSQN ssw
,V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7197): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7197): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7197): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7197): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7173): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7173): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7136): MCCMNC not supported: null
D/LGDataListener(  306): argv[0]=dsqncommand
D/LGDataListener(  306): argv[1]=wlan0
D/LGDataListener(  306): argv[2]=1
D/LGDataListener(  306): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1036): start to monitor internet connection
D/QRemote ( 7197): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7197): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7197): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7197): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7197): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7289): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7289): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:55:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450655727530], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450655727501]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Validated
D/ConnectivityService( 1036): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/dhcpcd  ( 7289): version 5.5.6 starting
E/dhcpcd  ( 7289): get_duid: m
D/dhcpcd  ( 7289): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7289): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7289): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7289): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7289): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7289): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7289): wlan0: sending REQUEST (xid 0xe2df9ff0), next in 3.97 seconds
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5458): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6539): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5458): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7306 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7306): onCreate
,W/AppUp4:DB( 7306):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7306):  setFingerPrint start
I/AppUp4:DB( 7306):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7306):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7306):  SDK version = 21
I/AppUp4:DB( 7306):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7306): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7306): onReceive
D/LgDataFeature( 7306): LgDataFeature() Constructor: none
,D/LgDataFeature( 7306): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7306): Context : android.app.ReceiverRestrictedContext@341142cc
D/AppUp4:CustFacade( 7306): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7306): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7306): begin check event
I/AppUp4:CustModeStarterReceiver( 7306): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7306): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7306): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7306): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7306): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6488:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6488/cgroup.procs: No such file or directory
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3428): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4301): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3428): DownloadService onCreate
I/DownloadManager( 3428): in removeSpuriousFiles
V/DownloadManager( 3428): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@e2b7430 on behalf of 3428
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3428): in trimDatabase
V/DownloadManager( 3428): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@130748a9 on behalf of 3428
,I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7351 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3428): DownloadService onStartCommand
V/DownloadManager( 3428): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@10808dcf on behalf of 3428
E/LGDMClient( 4301): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3428): processing inserted download 1
D/LGDMClient( 4301): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4301): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3428): processing inserted download 4
V/DownloadManager( 3428): processing inserted download 7
V/DownloadManager( 3428): processing inserted download 8
V/DownloadManager( 3428): processing inserted download 9
V/DownloadManager( 3428): processing inserted download 10
V/DownloadManager( 3428): processing inserted download 16
,V/DownloadManager( 3428): processing inserted download 17
I/art     (  341): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.895ms
V/DownloadManager( 3428): processing inserted download 18
V/DownloadManager( 3428): processing inserted download 21
V/DownloadManager( 3428): DownloadService onDestroy
I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 18.128ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 16.172ms
,W/ResourcesManager( 7351): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7351): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7351): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7351): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7351): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7351): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7351): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7351): LgDataFeature() Constructor: none
D/LgDataFeature( 7351): LgDataFeature() Constructor Done, null
,D/eas_req ( 7351): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/dhcpcd  ( 7289): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7378 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524295
,I/dhcpcd  ( 7289): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7289): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7289): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7289): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7289): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 7289): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7289): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7289): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/LgeMiscReceiver( 3378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3378): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3378): networkInfo.isConnected() = false
,I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7415 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 82670(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.209ms total 204.369ms
,I/HubEmail( 7351): JNI_OnLoad()
I/HubEmail( 7351): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7351): registerNatives()
I/HubEmail( 7351): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7351): registerNativeMethods()
I/HubEmail( 7351): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7351): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1036): Killing 6632:com.android.gallery3d/u0a27 (adj 15): empty #17
D/libc-netbsd(  306): res_queryN name = static-avc.lglime.com succeed
,W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6632/cgroup.procs: No such file or directory
,W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7378): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7378): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7456 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6660:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine( 1036): RunningState
,W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6660/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Killing 6689:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6689/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7476 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6777:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6777/cgroup.procs: No such file or directory
,I/art     ( 7476): Almond Protected OAT
,D/WeatherApplication( 7476): removeAccount
,D/WeatherApplication( 7476): Account.length = 0
E/WeatherApplication( 7476): OPERATOR:OPEN
D/WeatherAncestor( 7476): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:29
D/Weather.Utils( 7476): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7476): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7476): 2 : This is isUpdating : false
D/WeatherAncestor( 7476): connectivity changed - connection : true
,D/WeatherService( 7476): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7476): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7476): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7476): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7476): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7476): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:29
I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7497 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6706:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7055): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7055): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7055): BLE supported!!
I/jxcore-log( 7055): 
,W/libprocessgroup( 1036): failed to open /acct/uid_10097/pid_6706/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7497): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7497): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7497): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7497): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7497): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7497): Loading: webviewchromium
I/LibraryLoader( 7497): Time to load native libraries: 4 ms (timestamps 5650-5654)
I/LibraryLoader( 7497): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7497): Binding Chromium to main looper Looper (main, tid 1) {3601e9e7}
I/LibraryLoader( 7497): Expected native library version number "",actual native library version number ""
I/chromium( 7497): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7497): Initializing chromium process, renderers=0
W/art     ( 7497): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7497): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7497): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7497): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  314): registerClient() client 0xb57faa00, uid 10093
W/AudioManagerAndroid( 7497): Requires BLUETOOTH permission
I/Adreno-EGL( 7497): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7497): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7497): Build Date: 12/12/14 금
I/Adreno-EGL( 7497): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7497): Remote Branch: 
I/Adreno-EGL( 7497): Local Patches: 
I/Adreno-EGL( 7497): Reconstruct Branch: 
,V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
,I/NSApplication( 7497): Starting up...
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1036): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7552 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6801:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6801/cgroup.procs: No such file or directory
,D/Tethering( 1036): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5458): type=WIFI subType= reason=null isConnected=true
W/ResourcesManager( 7552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6539): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] request level :IDLE....
I/GLSActivity( 2135): [ac] getting account id
I/AppUp4:CustModeStarterReceiver( 7306): onReceive
D/AppUp4:CustFacade( 7306): Context : android.app.ReceiverRestrictedContext@341142cc
D/AppUp4:CustFacade( 7306): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7306): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7306): begin check event
I/AppUp4:CustModeStarterReceiver( 7306): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3428): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3428): DownloadService onCreate
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4301): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3428): in removeSpuriousFiles
I/LGDMClient( 4301): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3428): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@8e2c665 on behalf of 3428
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3428): in trimDatabase
V/DownloadManager( 3428): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@381f6f3a on behalf of 3428
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3428): DownloadService onStartCommand
V/DownloadManager( 3428): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@3a3e63e1 on behalf of 3428
,E/LGDMClient( 4301): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/LgeMiscReceiver( 3378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3378): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3378): networkInfo.isConnected() = false
D/LGDMClient( 4301): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4301): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3428): processing inserted download 1
,V/DownloadManager( 3428): processing inserted download 4
V/DownloadManager( 3428): processing inserted download 7
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3428): processing inserted download 8
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3428): processing inserted download 9
V/DownloadManager( 3428): processing inserted download 10
V/DownloadManager( 3428): processing inserted download 16
W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7476): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:31
V/DownloadManager( 3428): processing inserted download 17
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,V/DownloadManager( 3428): processing inserted download 18
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/Weather.Utils( 7476): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7476): 2 : All the weather widget is gone.
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/UpdateThreadPoolManager( 7476): 2 : This is isUpdating : false
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/WeatherAncestor( 7476): connectivity changed - connection : true
D/WeatherService( 7476): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e37342a
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/ForecastDataCache( 7476): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7476): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7476): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7476): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7476): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:31
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
V/DownloadManager( 3428): processing inserted download 21
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
V/DownloadManager( 3428): DownloadService onDestroy
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6539): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6539): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7306): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7306): onReceive
V/FormManager( 7378): There are no updated forms. The schedule will be deleted.
V/FormManager( 7378): Alarm would be updated, because LastCheckTime has been updated.
D/AppUp4:CustFacade( 7306): Context : android.app.ReceiverRestrictedContext@341142cc
D/AppUp4:CustFacade( 7306): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7306): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7306): begin check event
I/AppUp4:CustModeStarterReceiver( 7306): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3428): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3428): DownloadService onCreate
I/DownloadManager( 3428): in removeSpuriousFiles
V/DownloadManager( 3428): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4301): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@35ea67c7 on behalf of 3428
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3428): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/LGDMClient( 4301): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3428): in trimDatabase
V/DownloadManager( 3428): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@2d5c5d1d on behalf of 3428
,V/DownloadManager( 3428): DownloadService onStartCommand
V/DownloadManager( 3428): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3428): created cursor android.database.sqlite.SQLiteCursor@251bb963 on behalf of 3428
W/ContextImpl( 4301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3428): processing inserted download 1
E/LGDMClient( 4301): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4301): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4301): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3428): processing inserted download 4
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3428): processing inserted download 7
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3378): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3378): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3378): networkInfo.isConnected() = true
D/PhoneState( 3378): setPdpRejectCasuse : false
,V/DownloadManager( 3428): processing inserted download 8
V/DownloadManager( 3428): processing inserted download 9
V/DownloadManager( 3428): processing inserted download 10
V/DownloadManager( 3428): processing inserted download 16
V/DownloadManager( 3428): processing inserted download 17
V/DownloadManager( 3428): processing inserted download 18
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3428): processing inserted download 21
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
D/WeatherAncestor( 7476): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:31
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
V/DownloadManager( 3428): DownloadService onDestroy
W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
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
D/Weather.Utils( 7476): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7476): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7476): 2 : This is isUpdating : false
D/WeatherAncestor( 7476): connectivity changed - connection : true
D/WeatherService( 7476): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2e37342a
D/ForecastDataCache( 7476): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7476): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7476): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7476): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7476): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:55:31
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2343): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7378): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7378): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2343): [AccountUtils] Account not ready
W/Kids    ( 2343): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2343): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2343): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2343): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2343): 	at java.lang.Thread.run(Thread.java:818)
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
,D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6744): Internal timer expired: 4
D/UEI.SmartControl( 6744): unbind internal service
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.google.com, class = 1, type = 1
,D/serial_port( 6744): close(fd = 24)
,I/UEI.SmartControl( 6744): Serial port is closed.
,D/libc-netbsd(  306): res_queryN name = www.google.com succeed
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{19205ac1 type 2 when 307433 com.google.android.gms} when 307433
,V/QRemote ( 7197): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7197): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8818
,D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2135): Connected
,D/GCM     ( 2135): Message class com.google.f.a.a.p
I/GAV4    ( 7497): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1036): Killing 6827:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6827/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 316346748060; DSPS: 10507387; Offset : -4324881093
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3dc70e54 type 2 when 323746 android} when 323746
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 336348403625; DSPS: 11162801; Offset : -4324873191
,E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 356350724139; DSPS: 11818237; Offset : -4324871988
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 26199(1248KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 3.536ms total 148.073ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6194): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6194): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6194): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6194): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6194): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6194): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6194): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6194): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 376351667100; DSPS: 12473628; Offset : -4324874993
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 396353593342; DSPS: 13129051; Offset : -4324871358
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 416355188230; DSPS: 13784463; Offset : -4324863436
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 436356735827; DSPS: 14439874; Offset : -4324872236
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 456358317590; DSPS: 15095286; Offset : -4324877387
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 476359880549; DSPS: 15750697; Offset : -4324870850
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/HeadsetStateMachine( 3800): Disconnected process message: 10, size: 0
D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 496362154502; DSPS: 16406131; Offset : -4324855146
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 516364001317; DSPS: 17061552; Offset : -4324870033
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 536365581257; DSPS: 17716964; Offset : -4324876929
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3b5f7116 type 2 when 539734 android} when 539734
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,I/BooksSync( 6919): Starting books sync
,D/BooksSync( 6919): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6194757218993729202&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
,W/ApiaryClient( 6919): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6194757218993729202&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
,W/ApiaryClient( 6919): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6194757218993729202&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
E/BooksSync( 6919): Soft error: 
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6194757218993729202&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
,E/BooksSync( 6919): Sync error
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6194757218993729202&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
I/BooksSync( 6919): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 539734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 556367198958; DSPS: 18372377; Offset : -4324876582
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3759cc7c type 2 when 569926 android} when 569926,
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 576368798481; DSPS: 19027789; Offset : -4324863947
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,I/ActivityManager( 1036): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7712 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7712): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7712): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@108c8059
I/ActivityManager( 1036): Killing 6194:com.android.vending/u0a44 (adj 15): empty #17
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
W/libprocessgroup( 1036): failed to open /acct/uid_10044/pid_6194/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 596371297902; DSPS: 19683231; Offset : -4324867149
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 616372830394; DSPS: 20338641; Offset : -4324860484
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 636374711219; DSPS: 20994063; Offset : -4324871671
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 656376560118; DSPS: 21649484; Offset : -4324884448
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 676378075422; DSPS: 22304893; Offset : -4324864506
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 696379947446; DSPS: 22960314; Offset : -4324853976
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 716382159678; DSPS: 23615747; Offset : -4324869553
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 736383876077; DSPS: 24271163; Offset : -4324862035
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 756385620340; DSPS: 24926580; Offset : -4324857326
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 776387196582; DSPS: 25581992; Offset : -4324868024
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 796388976678; DSPS: 26237410; Offset : -4324857895
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 816391179224; DSPS: 26892842; Offset : -4324852719
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 836393000257; DSPS: 27548262; Offset : -4324862636
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 856394526448; DSPS: 28203672; Offset : -4324862533
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 876396116909; DSPS: 28859084; Offset : -4324858777
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 896397935651; DSPS: 29514504; Offset : -4324871324
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 916399544081; DSPS: 30169917; Offset : -4324880066
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated(),
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 936401808657; DSPS: 30825351; Offset : -4324874025
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,W/bt-smp  ( 3800): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3800): Plain text(LSB ~ MSB) = ef 7f 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3800): Encrypted text(LSB ~ MSB) = 07 36 31 a0 c0 ad aa d0 c9 6c 1b 6d 85 52 5b 0f 
,W/bt-btm  ( 3800): Stopping oneshot timer
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{11720905 type 2 when 943494 com.android.bluetooth} when 943494
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 956411264118; DSPS: 31481020; Offset : -4324848469
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 976412801506; DSPS: 32136431; Offset : -4324867582
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 996413933790; DSPS: 32791828; Offset : -4324864553
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1036): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3800): Disconnected process message: 10, size: 0
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1016415538001; DSPS: 33447241; Offset : -4324877513
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2b2b8d5a type 2 when 1028324 android} when 1028324
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,I/BooksSync( 6919): Starting books sync
,D/BooksSync( 6919): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-167888707132288678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-167888707132288678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 2135): Explicit concurrent mark sweep GC freed 52712(2MB) AllocSpace objects, 30(4MB) LOS objects, 51% free, 30MB/62MB, paused 1.492ms total 93.323ms
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-167888707132288678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,E/BooksSync( 6919): Soft error: 
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-167888707132288678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
E/BooksSync( 6919): Sync error
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-167888707132288678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
,I/BooksSync( 6919): Finished books sync
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1028324, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1036422655598; DSPS: 34102834; Offset : -4324870328
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1056424239757; DSPS: 34758246; Offset : -4324873449
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3751e6e0 type 2 when 1058580 android} when 1058580
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1076425848604; DSPS: 35413658; Offset : -4324851152
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1096427375887; DSPS: 36069068; Offset : -4324849955
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1116429015567; DSPS: 36724482; Offset : -4324858277
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1136431234414; DSPS: 37379915; Offset : -4324867083
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1156433037792; DSPS: 38035334; Offset : -4324864373
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1176434744398; DSPS: 38690750; Offset : -4324866699
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1196436305485; DSPS: 39346161; Offset : -4324862034
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1216437835841; DSPS: 40001571; Offset : -4324857427
,I/UsageStatsService( 1036): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1236439720000; DSPS: 40656993; Offset : -4324865411
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1256441914212; DSPS: 41312425; Offset : -4324868437
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1276443462381; DSPS: 41967836; Offset : -4324876821
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1296445060915; DSPS: 42623248; Offset : -4324865201
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1316446629970; DSPS: 43278659; Offset : -4324852543
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1336448143816; DSPS: 43934069; Offset : -4324864419
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1356449721673; DSPS: 44589481; Offset : -4324873476
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1376451413593; DSPS: 45244896; Offset : -4324859867
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1036): battery changed pluggedType: 2
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3800): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1396453249366; DSPS: 45900316; Offset : -4324855305
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1416454995349; DSPS: 46555733; Offset : -4324848902
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1436456572320; DSPS: 47211145; Offset : -4324858741
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1456458058094; DSPS: 47866554; Offset : -4324868433
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1476459639961; DSPS: 48521966; Offset : -4324873479
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7712): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7712): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@108c8059
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1496461320214; DSPS: 49177381; Offset : -4324871641
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1516462945728; DSPS: 49832794; Offset : -4324863377
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1536464513844; DSPS: 50488205; Offset : -4324851839
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1556466099461; DSPS: 51143617; Offset : -4324852928
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1576467914558; DSPS: 51799037; Offset : -4324868937
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1596469483404; DSPS: 52454448; Offset : -4324856645
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1616471810325; DSPS: 53109885; Offset : -4324879603
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1636473386046; DSPS: 53765296; Offset : -4324860408
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1656474968746; DSPS: 54420708; Offset : -4324864570
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1676476532229; DSPS: 55076119; Offset : -4324857224
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1696478043314; DSPS: 55731529; Offset : -4324872174
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1716479859869; DSPS: 56386948; Offset : -4324856287
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1736482037519; DSPS: 57042380; Offset : -4324875849
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1756483561625; DSPS: 57697790; Offset : -4324877596
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1776485374066; DSPS: 58353209; Offset : -4324865510
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1796486959839; DSPS: 59008621; Offset : -4324866729
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1816488517071; DSPS: 59664032; Offset : -4324865946
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3800): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4301): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1836490554043; DSPS: 60319459; Offset : -4324873600
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,W/bt-smp  ( 3800): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3800): Plain text(LSB ~ MSB) = 35 c4 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3800): Encrypted text(LSB ~ MSB) = a4 7f 60 14 49 30 49 96 a9 2f 07 02 ee 18 b7 b9 
,W/bt-btm  ( 3800): Stopping oneshot timer
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2316885e type 2 when 1843521 com.android.bluetooth} when 1843521
I/ProcessStatsService( 1036): Prepared write state in 23ms
,I/ProcessStatsService( 1036): Prepared write state in 17ms
,D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,I/ProcessStatsService( 1036): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-52.bin
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1856492255337; DSPS: 60974875; Offset : -4324881394
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{24d8e43f type 0 when 1450656470482 com.google.android.gms} when 1450656470482
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{d9e910c type 2 when 1207851 com.google.android.gms} when 1207851
,D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2343): Aggregate from 1450654670433 (log), 1450654670433 (data)
,D/GCM     ( 2135): Message class com.google.f.a.a.i
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 40402(1927KB) AllocSpace objects, 16(1263KB) LOS objects, 33% free, 44MB/66MB, paused 3.080ms total 180.937ms
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1876494255485; DSPS: 61630300; Offset : -4324864915
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1896495832926; DSPS: 62285712; Offset : -4324874441
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1916497414012; DSPS: 62941124; Offset : -4324880216
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1936498899002; DSPS: 63596532; Offset : -4324859862
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1956500769778; DSPS: 64251953; Offset : -4324850840
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1976502619041; DSPS: 64907374; Offset : -4324863019
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 1996504122003; DSPS: 65562783; Offset : -4324855652
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{aea7b4b type 2 when 2001565 android} when 2001565
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,I/BooksSync( 6919): Starting books sync
,D/BooksSync( 6919): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1418): onNotificationPosted
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/libc-netbsd(  306): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  306): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  306): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
W/ApiaryClient( 6919): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8450067134376562671&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
,W/ApiaryClient( 6919): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8450067134376562671&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6919): Authentication error
E/BooksAccountManager( 6919): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6919): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6919): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6919): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6919): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{2b5701f4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6919): Error response from books API: {
W/ApiaryClient( 6919):  "error": {
W/ApiaryClient( 6919):   "errors": [
W/ApiaryClient( 6919):    {
W/ApiaryClient( 6919):     "domain": "global",
W/ApiaryClient( 6919):     "reason": "required",
W/ApiaryClient( 6919):     "message": "Login Required",
W/ApiaryClient( 6919):     "locationType": "header",
W/ApiaryClient( 6919):     "location": "Authorization"
W/ApiaryClient( 6919):    }
W/ApiaryClient( 6919):   ],
W/ApiaryClient( 6919):   "code": 401,
W/ApiaryClient( 6919):   "message": "Login Required"
W/ApiaryClient( 6919):  }
W/ApiaryClient( 6919): }
,W/ApiaryClient( 6919): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8450067134376562671&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6919): Headers:
W/ApiaryClient( 6919): accept-encoding: [gzip]
W/ApiaryClient( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6919): gdata-version: 2
E/BooksSync( 6919): Soft error: 
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8450067134376562671&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdata-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
E/BooksSync( 6919): Sync error
E/BooksSync( 6919): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6919): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8450067134376562671&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6919): Headers:
E/BooksSync( 6919): accept-encoding: [gzip]
E/BooksSync( 6919): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6919): gdat,a-version: 2
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6919): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6919): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6919): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6919): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6919): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6919): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6919): {
E/BooksSync( 6919):  "error": {
E/BooksSync( 6919):   "errors": [
E/BooksSync( 6919):    {
E/BooksSync( 6919):     "domain": "global",
E/BooksSync( 6919):     "reason": "required",
E/BooksSync( 6919):     "message": "Login Required",
E/BooksSync( 6919):     "locationType": "header",
E/BooksSync( 6919):     "location": "Authorization"
E/BooksSync( 6919):    }
E/BooksSync( 6919):   ],
E/BooksSync( 6919):   "code": 401,
E/BooksSync( 6919):   "message": "Login Required"
E/BooksSync( 6919):  }
E/BooksSync( 6919): }
E/BooksSync( 6919): 
E/BooksSync( 6919): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6919): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6919): 	... 8 more
I/BooksSync( 6919): Finished books sync
,D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2001565, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2016505763141; DSPS: 66218197; Offset : -4324862438
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=174219155, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{15d865d type 2 when 2032408 android} when 2032408
D/[Concierge]Service( 2632): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=174219155 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2036507358705; DSPS: 66873609; Offset : -4324853684
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2056509260261; DSPS: 67529032; Offset : -4324874866
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2076510866295; DSPS: 68184444; Offset : -4324855693
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 2096512763006; DSPS: 68839866; Offset : -4324851098
,TIME-OUT KILL (timeout was 1800000ms)
```
