#### Test 58380500306a2c5_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{39151628 type 2 when 103666 android} when 103666
,--------- beginning of main
V/QRemote ( 6502): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3493
I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6577 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ReaderUtils( 6577): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/AndroidRuntime( 6578): 
D/AndroidRuntime( 6578): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6578): CheckJNI is OFF
W/GAV2    ( 6577): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6577): Created application version: 3.2.35 (30235)
I/BooksSync( 6577): Starting books sync
D/AndroidRuntime( 6578): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1967): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{dedab96 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{dedab96 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6637 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6578): Shutting down VM
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 294us total 17.325ms
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 13.463ms
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1872): Display #0 changed.
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.969ms
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{3f6a35c2 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{32a62fd3 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/art     ( 1039): Explicit concurrent mark sweep GC freed 19422(947KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 4.063ms total 171.032ms
D/ContextHelper( 6637): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/BooksSync( 6577): started syncMyEbooks
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 6637): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LibraryLoader( 6637): Loading: webviewchromium
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 6637): Time to load native libraries: 3 ms (timestamps 4492-4495)
I/LibraryLoader( 6637): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6637): Binding Chromium to main looper Looper (main, tid 1) {926f5f2}
,I/LibraryLoader( 6637): Expected native library version number "",actual native library version number ""
I/chromium( 6637): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6577): Authentication error
E/BooksAccountManager( 6577): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6577): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6577): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
E/HttpHelper( 6577): null auth token
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/BrowserStartupController( 6637): Initializing chromium process, renderers=0
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
V/AudioPolicyService(  319): registerClient() client 0xb1523200, uid 10311
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17269f5d:true
W/chromium( 6637): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6637): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6637): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6637): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6637): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6637): Build Date: 12/12/14 금
I/Adreno-EGL( 6637): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6637): Remote Branch: 
I/Adreno-EGL( 6637): Local Patches: 
I/Adreno-EGL( 6637): Reconstruct Branch: 
,W/chromium( 6637): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6637): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6637): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6637): CordovaWebView is running on device made by: LGE
,W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6637): Render dirty regions requested: true
I/OpenGLRenderer( 6637): Initialized EGL, version 1.4
D/OpenGLRenderer( 6637): Enabling debug mode 0
,D/Atlas   ( 6637): Validating map...
D/SplitWindow( 1039): check instance of lgWin Window{3283dfef u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ApiaryClient( 6577): Error response from books API: {
W/ApiaryClient( 6577):  "error": {
W/ApiaryClient( 6577):   "errors": [
W/ApiaryClient( 6577):    {
W/ApiaryClient( 6577):     "domain": "global",
W/ApiaryClient( 6577):     "reason": "required",
W/ApiaryClient( 6577):     "message": "Login Required",
W/ApiaryClient( 6577):     "locationType": "header",
W/ApiaryClient( 6577):     "location": "Authorization"
W/ApiaryClient( 6577):    }
W/ApiaryClient( 6577):   ],
W/ApiaryClient( 6577):   "code": 401,
W/ApiaryClient( 6577):   "message": "Login Required"
,W/ApiaryClient( 6577):  }
W/ApiaryClient( 6577): }
,W/ApiaryClient( 6577): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6577): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7428058214783372610&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6577): Headers:
W/ApiaryClient( 6577): accept-encoding: [gzip]
W/ApiaryClient( 6577): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6577): gdata-version: 2
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1470): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@6f4aee0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6637): LgDataFeature() Constructor: none
D/LgDataFeature( 6637): LgDataFeature() Constructor Done, null
,I/Timeline( 6637): Timeline: Activity_idle id: android.os.BinderProxy@84bfa2 time:104792
,I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +504ms (total +596ms)
,I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{247df317 u0 com.test.thalitest/.MainActivity t4} time:104827
I/chromium( 6637): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6637): 
,D/JsMessageQueue( 6637): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6637): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6637): 
,D/jxcore_app_log( 6637): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435200256
,I/chromium( 6637): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/MusicWidget( 2619): mDelayedStopHandler : unbind
,I/MusicBrowser( 2213): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2213): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2213): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2213): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2213): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2213): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1039):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@141333eecom.lge.music.MediaPlaybackService$5@3e13d08f
D/MusicBrowser( 2213): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@389192ec
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2213): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2213): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2213): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2213): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2213): reset
V/MediaPlayer[Native]( 2213): setListener
V/MediaPlayer[Native]( 2213): disconnect
V/MediaPlayer[Native]( 2213): destructor
V/AudioFlinger(  319): releasing 13 from 2213 for -1
V/AudioFlinger(  319):  decremented refcount to 0
V/AudioFlinger(  319): purging stale effects
V/MediaPlayer[Native]( 2213): disconnect
,D/MusicBrowser( 2213): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2213): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2213): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2213): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2213): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2213): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2213): [SmartShareManagerClient] unregisterListener: 362123036
W/SmartShareClient( 2213): [SmartShareManagerClient] unregisterListener invalid listener: 362123036
,I/SmartShareClient( 2213): [SmartShareManagerClient] terminate service: 2213/MediaPlaybackService/153548274
E/HomeCloudIF( 2213): unregiterHomeCloudBroadcast(), Illegal argument.
,I/SmartShareClient( 2213): [SmartShareManagerClient] unbindService context:android.app.Application@df0a725
V/CloudHub( 2213): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2213): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2213): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2213): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/CloudHub( 2213): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29998
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 6577): Authentication error
E/BooksAccountManager( 6577): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6577): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6577): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6577): null auth token
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6577): Error response from books API: {
W/ApiaryClient( 6577):  "error": {
W/ApiaryClient( 6577):   "errors": [
W/ApiaryClient( 6577):    {
W/ApiaryClient( 6577):     "domain": "global",
W/ApiaryClient( 6577):     "reason": "required",
W/ApiaryClient( 6577):     "message": "Login Required",
W/ApiaryClient( 6577):     "locationType": "header",
W/ApiaryClient( 6577):     "location": "Authorization"
W/ApiaryClient( 6577):    }
W/ApiaryClient( 6577):   ],
W/ApiaryClient( 6577):   "code": 401,
W/ApiaryClient( 6577):   "message": "Login Required"
W/ApiaryClient( 6577):  }
W/ApiaryClient( 6577): }
,W/ApiaryClient( 6577): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized,
W/ApiaryClient( 6577): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7428058214783372610&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6577): Headers:
W/ApiaryClient( 6577): accept-encoding: [gzip]
W/ApiaryClient( 6577): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6577): gdata-version: 2
W/jxcore-log( 6637): Initializing JXcore engine
W/jxcore-log( 6637): JXcore engine is ready
,W/Thread-788( 6698): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8764]" dev="sockfs" ino=8764 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-788( 6698): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-788( 6698): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9588]" dev="sockfs" ino=9588 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-788( 6698): type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-788( 6698): type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32415]" dev="sockfs" ino=32415 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6637): Starting JXcore engine
,W/jxcore-log( 6637): Platform android
W/jxcore-log( 6637): 
W/jxcore-log( 6637): Process ARCH arm
W/jxcore-log( 6637): 
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
E/BooksAccountManager( 6577): Authentication error
E/BooksAccountManager( 6577): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6577): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6577): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6577): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6577): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/jxcore-log( 6637): JXcore Cordova bridge is ready!
I/jxcore-log( 6637): 
W/jxcore-log( 6637): JXcore engine is started
,W/ApiaryClient( 6577): Error response from books API: {
W/ApiaryClient( 6577):  "error": {
W/ApiaryClient( 6577):   "errors": [
W/ApiaryClient( 6577):    {
W/ApiaryClient( 6577):     "domain": "global",
W/ApiaryClient( 6577):     "reason": "required",
W/ApiaryClient( 6577):     "message": "Login Required",
W/ApiaryClient( 6577):     "locationType": "header",
W/ApiaryClient( 6577):     "location": "Authorization"
W/ApiaryClient( 6577):    }
W/ApiaryClient( 6577):   ],
W/ApiaryClient( 6577):   "code": 401,
W/ApiaryClient( 6577):   "message": "Login Required"
W/ApiaryClient( 6577):  }
W/ApiaryClient( 6577): }
W/ApiaryClient( 6577): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6577): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7428058214783372610&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6577): Headers:
W/ApiaryClient( 6577): accept-encoding: [gzip]
W/ApiaryClient( 6577): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6577): gdata-version: 2
I/jxcore-log( 6637): Toggling radios to true
I/jxcore-log( 6637): 
,D/BluetoothAdapter( 6637): enable(): BT is already enabled..!
D/WifiService( 1039): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=6637, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=6637, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=6637, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1039): reconnect pid=6637, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6637): Radios toggled
I/jxcore-log( 6637): 
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6637): My device name is: LGE-LG-D855
I/jxcore-log( 6637): 
E/WifiNative: ( 1039): [107,260,810 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
,I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
D/Tethering( 1039): InitialState.processMessage what=4
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org succeed
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/DhcpStateMachine( 1039): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  315): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2139): Read error: ssl=0xaf460a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2139): SSL shutdown failed: ssl=0xaf460a00: I/O error during system call, Broken pipe
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6716 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1039):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{321e03c4 type 0 when 1455058237498 com.android.vending} when 1455058237498
E/WifiNative: ( 1039): [107,363,733 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=107386
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=107386
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/LGWifiP2pService( 1039): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  315): Clearing all IP addresses on wlan0,
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
,E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=107427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=107427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=107430  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=107431  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): ne,tworkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524292
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/NetworkManagementService( 1039): Removing idletimer
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1039): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-193ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6716): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6716): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6716): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6716): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6716): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6716): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/Finsky  ( 6019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6019): [1] 5.onFinished: Scheduling replication attempt 1.
D/PCSuite ( 6744): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1039): Killing 5540:com.lge.appbox.client/u0a11 (adj 15): empty #17
,V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 6716): LgDataFeature() Constructor: none
D/LgDataFeature( 6716): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_5540/cgroup.procs: No such file or directory
,D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6744): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1039): Killing 5948:com.android.contacts/u0a19 (adj 15): empty #17
W/ContextImpl( 4457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 6577): Soft error: 
E/BooksSync( 6577): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6577): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7428058214783372610&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6577): Headers:
E/BooksSync( 6577): accept-encoding: [gzip]
E/BooksSync( 6577): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6577): gdata-version: 2
E/BooksSync( 6577): 
E/BooksSync( 6577): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6577): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6577): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6577): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6577): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6577): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6577): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6577): {
E/BooksSync( 6577):  "error": {
E/BooksSync( 6577):   "errors": [
E/BooksSync( 6577):    {
E/BooksSync( 6577):     "domain": "global",
E/BooksSync( 6577):     "reason": "required",
E/BooksSync( 6577):     "message": "Login Required",
E/BooksSync( 6577):     "locationType": "header",
E/BooksSync( 6577):     "location": "Authorization"
E/BooksSync( 6577):    }
E/BooksSync( 6577):   ],
E/BooksSync( 6577):   "code": 401,
E/BooksSync( 6577):   "message": "Login Required"
E/BooksSync( 6577):  }
E/BooksSync( 6577): }
E/BooksSync( 6577): 
E/BooksSync( 6577): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6577): 	... 8 more
,E/BooksSync( 6577): Sync error
E/BooksSync( 6577): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6577): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7428058214783372610&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6577): Headers:
E/BooksSync( 6577): accept-encoding: [gzip]
E/BooksSync( 6577): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6577): gdata-version: 2
E/BooksSync( 6577): 
E/BooksSync( 6577): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6577): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6577): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6577): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6577): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6577): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6577): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6577): {
E/BooksSync( 6577):  "error": {
E/BooksSync( 6577):   "errors": [
E/BooksSync( 6577):    {
E/BooksSync( 6577):     "domain": "global",
E/BooksSync( 6577):     "reason": "required",
E/BooksSync( 6577):     "message": "Login Required",
E/BooksSync( 6577):     "locationType": "header",
E/BooksSync( 6577):     "location": "Authorization"
E/BooksSync( 6577):    }
E/BooksSync( 6577):   ],
E/BooksSync( 6577):   "code": 401,
E/BooksSync( 6577):   "message": "Login Required"
E/BooksSync( 6577):  }
E/BooksSync( 6577): }
E/BooksSync( 6577): 
E/BooksSync( 6577): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6577): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6577): 	... 8 more
I/BooksSync( 6577): Finished books sync
W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_5948/cgroup.procs: No such file or directory
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6744): [StartReceiver][getUpdateNecessity]update = false
I/ActivityManager( 1039): Killing 6315:com.lge.email/u0a23 (adj 15): empty #17
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 81955, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6315/cgroup.procs: No such file or directory
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6744): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1039): Killing 5969:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_5969/cgroup.procs: No such file or directory
W/ProcessCpuTracker( 1039): Skipping unknown process pid 6779
I/GAV2    ( 6577): Thread[GAThread,5,main]: No campaign data found.
,I/wpa_supplicant( 2684): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109473  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109486  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
,D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2684): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=109573  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=109575  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109576
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109576
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109576
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109576
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109576
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=109577  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=109579  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2684): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6716): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6716): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6716): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=109584  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsControl( 6716): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : availableList=[wlan0]
E/WifiStateMachine( 1039):  Conne,ctModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=109585  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6716): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6716): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109585
D/UsbSettingsControl( 6716): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109585
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1039): Got NetworkAgent Messenger
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1039): NetworkAgent connected
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1039): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109630  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109631  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109631  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=109633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=109633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=109633  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10f3bb53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10f3bb53 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
,D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1039): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 1
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1039): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{fa,lse} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
W/dsqn    ( 6802): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6802): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/DSQN    ( 6802): DSQN ssw
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org succeed
D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6502): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6502): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6502): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6744): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6744): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6716): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
,D/WiFiOffLoadBroadcast( 6716): MCCMNC not supported: null
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6502): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6502): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6502): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:50:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455058242612], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455058242593]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524290
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6808): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6808): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 6808): version 5.5.6 starting
E/dhcpcd  ( 6808): get_duid: m
D/dhcpcd  ( 6808): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6808): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6808): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6808): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6808): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6808): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6808): wlan0: sending REQUEST (xid 0x32141880), next in 4.91 seconds
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5513): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/AlarmManagerService( 1039): Setting time of day to sec=1455058243
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/AlarmManagerService( 1039): Unable to set rtc to 1455058243: Invalid argument
D/Tethering( 1039): MasterInitialState.processMessage what=3
,W/ContextImpl( 6248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
I/[SystemUI]Clock( 1470): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1470): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 3687): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 3687): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-09 23:50:43...... Request
I/LIA_Informant_Tips_LogTracer( 3687): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 170, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : SmartTips Total Working Day Count = 170
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : UserGuide Working Duration Count = 6
I/SecureClockService( 1967): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : Last Date Check Time = 2016-02-09 23:50:43
I/NetworkMonitor( 5513): type=WIFI subType= reason=null isConnected=true
I/CalendarProvider2( 6527): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 6527): Scheduling check of next Alarm
W/ActivityManager( 1039): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2089): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
,I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6835 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppUp4:AppBoxCP( 6835): onCreate
W/AppUp4:DB( 6835):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6835):  setFingerPrint start
I/AppUp4:DB( 6835):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6835):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6835):  SDK version = 21
I/AppUp4:DB( 6835):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6835): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6835): onReceive
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgDataFeature( 6835): LgDataFeature() Constructor: none
D/LgDataFeature( 6835): LgDataFeature() Constructor Done, null
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/AppUp4:CustFacade( 6835): Context : android.app.ReceiverRestrictedContext@bee8ac0
D/AppUp4:CustFacade( 6835): isCustomizationCompleted : false
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/AppUp4:CustFacade( 6835): isPhone : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/AppUp4:CustModeStarterReceiver( 6835): begin check event
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/AppUp4:CustModeStarterReceiver( 6835): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6835): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/AppUp4:CustModeStarterReceiver( 6835): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6835): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6835): handleAsyncCustNotification do not startCustService
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
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/ActivityManager( 1039): Killing 5992:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_5992/cgroup.procs: No such file or directory
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 104418, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
V/DownloadManager( 3326): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3326): DownloadService onCreate
,I/DownloadManager( 3326): in removeSpuriousFiles
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@29ace3e4 on behalf of 3326
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3326): in trimDatabase
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@1264b04d on behalf of 3326
D/SyncManager( 1039): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 142923, reason: 10019
I/LGDMClient( 4202): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6861 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3326): DownloadService onStartCommand
V/DownloadManager( 3326): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@2f465a50 on behalf of 3326
E/LGDMClient( 4202): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4202): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4202): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3326): processing inserted download 1
V/DownloadManager( 3326): processing inserted download 4
,V/DownloadManager( 3326): processing inserted download 7
V/DownloadManager( 3326): processing inserted download 8
V/DownloadManager( 3326): processing inserted download 9
V/DownloadManager( 3326): processing inserted download 10
V/DownloadManager( 3326): processing inserted download 16
V/DownloadManager( 3326): processing inserted download 17
V/DownloadManager( 3326): processing inserted download 18
V/DownloadManager( 3326): processing inserted download 21
V/DownloadManager( 3326): processing inserted download 22
,V/DownloadManager( 3326): DownloadService onDestroy
W/ResourcesManager( 6861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 6861): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6861): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6861): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 6861): LgDataFeature() Constructor: none
D/LgDataFeature( 6861): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1039):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1039): identical MTU - not setting
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524295
D/eas_req ( 6861): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 6808): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 6808): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6808): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6808): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6808): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6808): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6808): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6808): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6808): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6887 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/LgeMiscReceiver( 3278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3278): networkInfo.isConnected() = false
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6923 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 69847(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.452ms total 171.945ms
I/HubEmail( 6861): JNI_OnLoad()
I/HubEmail( 6861): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6861): registerNatives()
I/HubEmail( 6861): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6861): registerNativeMethods()
I/HubEmail( 6861): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6861): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1039): Killing 6382:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6382/cgroup.procs: No such file or directory
,W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1039): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
,D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 6887): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6887): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6956 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 5732:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_5732/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6976 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6454:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6454/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Killing 5878:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/art     ( 6976): Almond Protected OAT
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6637): 
,W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_5878/cgroup.procs: No such file or directory
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{30847208 type 2 when 112171 com.google.android.gms} when 112171
D/WeatherApplication( 6976): removeAccount
D/WeatherApplication( 6976): Account.length = 0
E/WeatherApplication( 6976): OPERATOR:OPEN
D/WeatherAncestor( 6976): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:45
,D/Weather.Utils( 6976): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6976): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6976): 2 : This is isUpdating : false
D/WeatherAncestor( 6976): connectivity changed - connection : true
D/WeatherService( 6976): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6976): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6976): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6976): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6976): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 6976): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:45
I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6995 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6478:com.lge.bnr/1000 (adj 15): empty #17
,E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6478/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6995): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6995): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6995): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6995): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5513): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 6995): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6995): Loading: webviewchromium
,I/LibraryLoader( 6995): Time to load native libraries: 3 ms (timestamps 2800-2803)
I/LibraryLoader( 6995): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6995): Binding Chromium to main looper Looper (main, tid 1) {1f86e6ab}
I/LibraryLoader( 6995): Expected native library version number "",actual native library version number ""
I/chromium( 6995): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6995): Initializing chromium process, renderers=0
W/art     ( 6995): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6995): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6995): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 6995): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  319): registerClient() client 0xb1427f20, uid 10093
W/AudioManagerAndroid( 6995): Requires BLUETOOTH permission
I/Adreno-EGL( 6995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6995): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6995): Build Date: 12/12/14 금
I/Adreno-EGL( 6995): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6995): Remote Branch: 
I/Adreno-EGL( 6995): Local Patches: 
I/Adreno-EGL( 6995): Reconstruct Branch: 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6637): 
,I/NSApplication( 6995): Starting up...
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6637): 
I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7059 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6527:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6637): 
,W/libprocessgroup( 1039): failed to open /acct/uid_10014/pid_6527/cgroup.procs: No such file or directory
,W/ResourcesManager( 7059): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2399): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2399): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6835): onReceive
,D/AppUp4:CustFacade( 6835): Context : android.app.ReceiverRestrictedContext@bee8ac0
D/AppUp4:CustFacade( 6835): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6835): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6835): begin check event
I/AppUp4:CustModeStarterReceiver( 6835): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSActivity( 2139): [ac] getting account id
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4202): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4202): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3326): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4202): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3326): DownloadService onCreate
,I/DownloadManager( 3326): in removeSpuriousFiles
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/art     ( 2139): Explicit concurrent mark sweep GC freed 22204(1329KB) AllocSpace objects, 12(1728KB) LOS objects, 51% free, 30MB/62MB, paused 1.132ms total 52.451ms
,I/LgeMiscReceiver( 3278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3278): networkInfo.isConnected() = false
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@10ab414e on behalf of 3326
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3326): in trimDatabase
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@1ebecb7c on behalf of 3326
W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3326): DownloadService onStartCommand
V/DownloadManager( 3326): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@32fe245a on behalf of 3326
I/GLSUser ( 2139): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3326): processing inserted download 1
V/DownloadManager( 3326): processing inserted download 4
V/DownloadManager( 3326): processing inserted download 7
V/DownloadManager( 3326): processing inserted download 8
V/DownloadManager( 3326): processing inserted download 9
V/DownloadManager( 3326): processing inserted download 10
,V/DownloadManager( 3326): processing inserted download 16
V/DownloadManager( 3326): processing inserted download 17
V/DownloadManager( 3326): processing inserted download 18
V/DownloadManager( 3326): processing inserted download 21
V/DownloadManager( 3326): processing inserted download 22
D/WeatherAncestor( 6976): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:46
V/DownloadManager( 3326): DownloadService onDestroy
D/Weather.Utils( 6976): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6976): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6976): 2 : This is isUpdating : false
D/WeatherAncestor( 6976): connectivity changed - connection : true
,D/WeatherService( 6976): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5aa7f3e
D/ForecastDataCache( 6976): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 6976): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6976): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6976): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6976): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:46
D/ChimeraCfgMgr( 2399): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2399): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
V/FormManager( 6887): There are no updated forms. The schedule will be deleted.
V/FormManager( 6887): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7106 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 368us total 17.449ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 15.446ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 12.981ms
D/ALBootInit( 7106): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 7106): Alarm ALBootInit: TIME_SET
D/Alarms  ( 7106): [setNextAlert] start
D/Alarms  ( 7106): [setNextAlert] (1)
,D/Alarms  ( 7106):  minTime  = 0
D/Alarms  ( 7106):  -- OK multi -- 0
E/jeny.kim( 7106): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7106): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 7106): BUILD Country: EU
,D/Alarms  ( 7106): broadcastToWidgetProvider : false
D/Alarms  ( 7106): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1039): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 7106): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 7106): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1357c3f9
V/DigitalAppWidgetProvider( 7106): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1357c3f9
D/QuickCoverProvider( 7106): onReceiver
I/indal   ( 1418): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1418): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6976): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:50:46
,D/Weather.Utils( 6976): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6976): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6976): 2 : This is isUpdating : false
D/WeatherService( 6976): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5aa7f3e
D/ForecastDataCache( 6976): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6976): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6976): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6976): 2 : set auto-update time : 2/10 2:50
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
D/WeatherAncestor( 6976): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:50:46
,D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
I/ActivityManager( 1039): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 2213:com.lge.music/u0a34 (adj 15): empty #17
V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,V/AudioFlinger(  319): 2213 died, releasing its sessions
V/AudioFlinger(  319):  pid 1872 @ 0
V/AudioFlinger(  319):  pid 3278 @ 1
V/AudioFlinger(  319):  pid 3278 @ 2
,W/libprocessgroup( 1039): failed to open /acct/uid_10034/pid_2213/cgroup.procs: No such file or directory
D/TimeService( 7131): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455058247213
,D/        ( 7131): TimeServiceNative: User Time to be set is 1455058247214
D/QC-time-services( 7131): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7131): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7131): Lib:time_genoff_operation: pargs->ts_val = 1455058247214
D/QC-time-services(  364): Daemon: Connection accepted:time_genoff
D/QC-time-services( 7131): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  364): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455058247214
D/QC-time-services(  364): Daemon:genoff_opr: Base = 2, val = 1455058247214, operation = 0
D/QC-time-services(  364): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/19/70 16:2:49
D/QC-time-services(  364): Daemon:Value read from RTC seconds = 14659369000
D/QC-time-services(  364): Daemon:new time 1455058247214 
D/QC-time-services(  364): Daemon: delta 1440398878214 genoff 1440398878214 
D/QC-time-services(  364): Daemon:genoff_persistent_update: Writing genoff = 1440398878214 to memory
D/QC-time-services(  364): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  364): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  364): Updating the TOD offset
D/QC-time-services(  364): Daemon:genoff_persistent_update: Writing genoff = 1440398878214 to memory
D/QC-time-services(  364): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  364): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  364): Daemon:Update to modem bit set
D/QC-time-services(  364): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  364): Daemon: Base = 2, Value being sent to MODEM = 1124434078214
E/QC-time-services( 7131): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  364): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  364): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1039): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7153 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1039): Killing 6019:com.android.vending/u0a44 (adj 15): empty #17
I/rmt_storage(  310): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  310): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  310): wakelock acquired: 1, error no: 42
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_6019/cgroup.procs: No such file or directory
,W/ResourcesManager( 7153): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 7153): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7153): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7153): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3575ed54, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@147dd4fd, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@926f5f2, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2fb2a443, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@bee8ac0, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1357c3f9, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@5aa7f3e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@451419f, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@389192ec, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3f47a6b5, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4b514a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@b1258bb, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@297af1d8, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@418f931, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@7753816, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1b03c597, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@10995384, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@24d2f76d, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@84bfa2, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@4352433, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2e1a23f0, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@13b49d69, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@141333ee, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3e13d08f, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@15958f1c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@df0a725, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2e02a0fa, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1f86e6ab, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@19fa8108, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@372990a1, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2449d2c6, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3ccb4287, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@c3aa5b4, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@30ad95dd, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@23805552, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@70f8023, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@38b66920, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2872b2d9, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@182a749e, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9cffb7f, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@f68f74c, lg_preferences_recent_tim,ezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1bd2a395, lg_
D/GeneralPreferenceUtils( 7153): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  310): 
,I/rmt_storage(  310): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  889): [IMS_FATAL]| 3347 | 920 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/Config  ( 7153): [init]
I/Config  ( 7153): LGCalendar ver.4.40.16
I/Config  ( 7153): start check model
I/Config  ( 7153): start check native_ca
I/Config  ( 7153): Config Operator=OPEN, Country=EU
D/Config  ( 7153): [setDefaultValuesToPref]
D/Config  ( 7153): [parseProfiles]
D/ProfilesParser( 7153): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7153): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7153): [updateProfiletoCountryInfo]
D/GeneralPreference( 7153): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 7153): [updateWidgets] 
,I/InitNotificationRingtoneService( 7153): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7153): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 7153): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 7153): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7153): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 7153): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 7153): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 7153): [onReceive]
D/CalendarWidgetProvider( 7153): [onReceive]
D/CalendarWidgetProvider( 7153): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/HolidayIntentService( 7153): onHandleIntent
,D/HolidayDataLoader( 7153): readJsonAsset : holiday.json
D/CalendarTypeController( 7153): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 7153): [onReceive]
D/CalendarWidgetProvider( 7153): [onReceive]
D/CalendarWidgetProvider( 7153): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7153): [onUpdateAndInitCalendarTime]
E/HolidayIntentService( 7153): onHandleIntent:holiday data empty
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 23684(1135KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.300ms total 69.403ms
,I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6835): onReceive
,D/AppUp4:CustFacade( 6835): Context : android.app.ReceiverRestrictedContext@bee8ac0
D/AppUp4:CustFacade( 6835): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6835): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6835): begin check event
I/AppUp4:CustModeStarterReceiver( 6835): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3326): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3326): DownloadService onCreate
D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4202): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3326): in removeSpuriousFiles
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@14eb2368 on behalf of 3326
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3326): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/DownloadManager( 3326): in trimDatabase
V/DownloadManager( 3326): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 3278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3278): networkInfo.isConnected() = true
D/PhoneState( 3278): setPdpRejectCasuse : false
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@136a2c26 on behalf of 3326
V/DownloadManager( 3326): DownloadService onStartCommand
W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3326): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4202): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4202): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4202): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 6976): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:47
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@25030e14 on behalf of 3326
D/Weather.Utils( 6976): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6976): 2 : All the weather widget is gone.
V/DownloadManager( 3326): processing inserted download 1
D/UpdateThreadPoolManager( 6976): 2 : This is isUpdating : false
D/WeatherAncestor( 6976): connectivity changed - connection : true
D/WeatherService( 6976): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5aa7f3e
D/ForecastDataCache( 6976): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6976): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6976): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6976): 2 : isUpdateNeedForAlarm : no city return false
V/DownloadManager( 3326): processing inserted download 4
D/WeatherAncestor( 6976): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:50:47
V/DownloadManager( 3326): processing inserted download 7
V/DownloadManager( 3326): processing inserted download 8
V/DownloadManager( 3326): processing inserted download 9
,V/DownloadManager( 3326): processing inserted download 10
V/DownloadManager( 3326): processing inserted download 16
V/DownloadManager( 3326): processing inserted download 17
V/DownloadManager( 3326): processing inserted download 18
V/DownloadManager( 3326): processing inserted download 21
V/DownloadManager( 3326): processing inserted download 22
V/DownloadManager( 3326): DownloadService onDestroy
,D/ChimeraCfgMgr( 2399): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2399): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
V/FormManager( 6887): There are no updated forms. The schedule will be deleted.
I/DigitalAppWidgetProvider( 7106): onReceive: android.intent.action.ALARM_CHANGED
V/FormManager( 6887): Alarm would be updated, because LastCheckTime has been updated.
D/WeatherAncestor( 6976): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:50:47
,D/Weather.Utils( 6976): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6976): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6976): 2 : This is isUpdating : false
D/Weather_cast( 6976): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
,D/WeatherAncestor( 6976): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:50:47
I/ActivityManager( 1039): Killing 6577:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_6577/cgroup.procs: No such file or directory
,D/GCM     ( 2139): Connected
,D/GCM     ( 2139): Message class com.google.f.a.a.p
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{18b6549d type 2 when 115561 com.android.providers.calendar} when 115561
,I/ActivityManager( 1039): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7208 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 7208): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7208): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@fb9a966
,D/CalendarProvider2( 7208): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7208): Created com.android.providers.calendar.CalendarAlarmManager@2fb2a443(com.android.providers.calendar.CalendarProvider2@fb9a966)
,D/CalendarProviderBroadcastReceiver( 7208): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7208): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7208): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7208): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7208): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 7208): (284) automatic index on view_events(_id)
D/CalendarProvider2( 7208): [IntentService] Release Lock
,D/CalendarProvider2( 7208): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1039): Killing 6744:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
,I/GAV4    ( 6995): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 118013783397; DSPS: 4008365; Offset : -4327680882,
,I/ActivityManager( 1039): Killing 6345:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6502): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6502): android.os.DeadObjectException
,W/System.err( 6502): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6502): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6502): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6502): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6502): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6502): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6502): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6502): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6502): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,W/System.err( 6502): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6502): IControl.unregisterCallback error: android.os.DeadObjectException,
W/System.err( 6502): android.os.DeadObjectException
,W/System.err( 6502): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6502): 	at android.os.BinderProxy.transact(Binder.java:496),
W/System.err( 6502): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818),
,W/System.err( 6502): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6502): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6502): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 6502): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6502): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6502): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6502): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6502): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/QRemote ( 6502): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6637): 
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6345/cgroup.procs: No such file or directory
W/ActivityManager( 1039): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6502): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6502): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1039): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6502): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6637): 
D/UEI.SmartControl( 7262): Quickset Services start...
,I/UEI.SmartControl( 7262): Manufacture = LGE
D/UEI.SmartControl( 7262): Id = LGNevo
D/UEI.SmartControl( 7262): File observer start...
E/UEI.SmartControl( 7262): IR Port is disabled: false
D/UEI.SmartControl( 7262): Starting file observer...
D/UEI.SmartControl( 7262): Extracting JNI libs...
D/UEI.SmartControl( 7262): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7262): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7262): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7262): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7262): --- Selecting new region: 6
I/UEI.SmartControl( 7262): Model = LG-D855
,D/UEI.SmartControl( 7262): QS Service created
I/UEI.SmartControl( 7262): Service initServices...
,D/UEI.SmartControl( 7262): QS start get config
,D/UEI.SmartControl( 7262): Loading JNI Libs...
,I/UEI.SmartControl( 7262): Supports setup maps: true
,D/UEI.SmartControl( 7262): QS start statue = true Error code = 0
,I/UEI.SmartControl( 7262): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7262): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7262): ### init IR Blaster...
D/serial_port( 7262): Configuring serial port
E/UEI.SmartControl( 7262): UEIBLaster setting for 616
I/UEI.SmartControl( 7262): Setting serial record hearder size = 2
I/UEI.SmartControl( 7262): configuring settings for MAXQ616
I/UEI.SmartControl( 7262): Get version...
D/UEI.SmartControl( 7262): serial port data available: 21
,D/UEI.SmartControl( 7262): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7262): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7262): QS saving settings...
D/UEI.SmartControl( 7262): IR Blaster version: 25672567
,D/UEI.SmartControl( 7262): serial port data available: 4
,W/ContextImpl( 7262): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 7262): Device manager: loading config....
D/UEI.SmartControl( 7262): ----------- loading internal config...
,E/UEI.SmartControl( 7262): Services init done
D/UEI.SmartControl( 7262): QS Service init finished
D/UEI.SmartControl( 7262): QS Service version name: 2.1.91
D/UEI.SmartControl( 7262): QS Service version code: 201091
D/UEI.SmartControl( 7262): Service requested: Control
E/UEI.SmartControl( 7262): Loading SETTINGS...
D/UEI.SmartControl( 7262): Request IControl service: devices are loaded...
I/ActivityManager( 1039): Killing 6716:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6502): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7262): ------ IControl API: 11
I/UEI.SmartControl( 7262): Registering callback...
,I/UEI.SmartControl( 7262): ------ IControl API: 19
I/UEI.SmartControl( 7262): Registering Services Ready callback...
D/UEI.SmartControl( 7262): -- Open brand translation xml: brands_translations_ko
I/jxcore-log( 6637): Test app app.js loaded
I/jxcore-log( 6637): 
,I/chromium( 6637): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/UEI.SmartControl( 7262): Notify AllClients services are ready: 0
,I/QRemote ( 6502): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 6502): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/UEI.SmartControl( 7262): -----service ready thread exits
D/QRemote ( 6502): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6502): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6502): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7262): ------ IControl API: 8
D/QRemote ( 6502): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6502): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6502): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6502): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6502): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6502): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bff125e added. We now have 1 listener(s)
I/jxcore-log( 6637): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6637): 
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6716/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7262): Internal service binding...
,D/QRemote ( 6502): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6502): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6502): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6502): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455058252505]
D/QRemote ( 6502): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6502): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6502): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 6502): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 6502): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6502): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/serial_port( 7262): close(fd = 25)
,I/UEI.SmartControl( 7262): Serial port is closed.
,D/UEI.SmartControl( 7262): Internal timer expired: 1
,D/UEI.SmartControl( 7262): unbind internal service
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3764): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7301 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{60f24d3 type 0 when 1455058260504 com.android.vending} when 1455058260504
,D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/Finsky  ( 7301): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7301): LgDataFeature() Constructor: none
D/LgDataFeature( 7301): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7301): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1039): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7358 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7301): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7301): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7358): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7358): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3326): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3326): created cursor android.database.sqlite.SQLiteCursor@293ce4b2 on behalf of 7301
D/Finsky  ( 7301): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7301): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7301): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7301): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7358): VM with version 2.1.0 has multidex support
I/MultiDex( 7358): install
I/MultiDex( 7358): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7358): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,W/ActivityThread( 7358): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7358): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17249c05: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7358): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2139): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2139): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2399): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1039): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7396 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2399): Restart initialization of location
,W/ResourcesManager( 7396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7396): VM with version 2.1.0 has multidex support
I/MultiDex( 7396): install
I/MultiDex( 7396): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7396): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/Finsky  ( 7301): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ActivityThread( 7396): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7396): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17249c05: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7396): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2139): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2139): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2399): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7396): callingUid 10005, callindPid: 7396
D/LocationInitializer( 2399): Restart initialization of location
,E/MDM     ( 1837): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/MDM     ( 1837): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1039): Killing 7131:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7131/cgroup.procs: No such file or directory
,D/Finsky  ( 7301): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{332c3146 type 0 when 1455058263779 com.android.vending} when 1455058263779
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7301): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7301): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7301): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7301): [1] DailyHygiene.reschedule: Scheduling new run in 804 minutes (failures=5)
D/DeviceConnectionService( 1837): client connected with version: 7571000
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2631ae8a type 2 when 133761 android} when 133761
,I/ActivityManager( 1039): Killing 7153:com.android.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager( 1039): Killing 6835:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10013/pid_7153/cgroup.procs: No such file or directory
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6835/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 138015647035; DSPS: 4663786; Offset : -4327679076
,E/WifiStateMachine( 1039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 43336(2042KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.377ms total 172.406ms
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{288fb118 type 0 when 1455058284028 com.android.vending} when 1455058284028
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 158017017652; DSPS: 5319191; Offset : -4327681776
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{8dbaaeb type 0 when 1455058304960 com.android.vending} when 1455058304960
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{105d9048 type 2 when 173689 android} when 173689
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7487 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ReaderUtils( 7487): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7487): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7487): Created application version: 3.2.35 (30235)
,I/art     ( 2139): Explicit concurrent mark sweep GC freed 20958(1150KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.367ms total 32.846ms
,I/BooksSync( 7487): Starting books sync
,D/BooksSync( 7487): started syncMyEbooks
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
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
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true,
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4549819378221026102&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4549819378221026102&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
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
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4549819378221026102&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 178019103269; DSPS: 5974619; Offset : -4327671354
,E/BooksSync( 7487): Soft error: 
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4549819378221026102&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
,E/BooksSync( 7487): Sync error
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4549819378221026102&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
I/BooksSync( 7487): Finished books sync
I/ActivityManager( 1039): Killing 6861:com.lge.email/u0a23 (adj 15): empty #17
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 173689, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6861/cgroup.procs: No such file or directory
I/GAV2    ( 7487): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 198021415970; DSPS: 6630055; Offset : -4327677832
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{d2bbaab type 2 when 203881 android} when 203881
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{39c0c508 type 2 when 184470 com.google.android.gms} when 184470
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{3983b6c6 type 0 when 1455058326933 com.android.vending} when 1455058326933
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1e95687 type 2 when 207796 android} when 207796
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/VacuumService( 2139): Vacuum at: now=1455058341368 tag=VacuumService
,I/GoogleURLConnFactory( 2139): Using platform SSLCertificateSocketFactory
,W/Uploader( 2139): No account for auth token provided
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7301): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 2139): No account for auth token provided
,W/Uploader( 2139): No account for auth token provided
,W/Uploader( 2139):  no longer exists, so no auth token.
,W/ProcessCpuTracker( 1039): Skipping unknown process pid 7558
W/ProcessCpuTracker( 1039): Skipping unknown process pid 7559
W/ProcessCpuTracker( 1039): Skipping unknown process pid 7561
,W/ProcessCpuTracker( 1039): Skipping unknown process pid 7563
,W/ProcessCpuTracker( 1039): Skipping unknown process pid 7569
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 218023428776; DSPS: 7285481; Offset : -4327679213
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{113acf7c type 0 when 1455058361607 com.android.vending} when 1455058361607
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 25792(1109KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 3.148ms total 155.323ms
,D/Finsky  ( 7301): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7301): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7301): [1] 5.onFinished: Giving up after 6 failures.
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{1024fdfe type 2 when 233956 android} when 233956
,I/BooksSync( 7487): Starting books sync
,D/BooksSync( 7487): started syncMyEbooks
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8905096956556489218&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
,D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8905096956556489218&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
W/ApiaryClient( 7487): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8905096956556489218&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,E/BooksSync( 7487): Soft error: 
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8905096956556489218&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
,E/BooksSync( 7487): Sync error
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8905096956556489218&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
I/BooksSync( 7487): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 208431, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 238024737257; DSPS: 7940884; Offset : -4327683222
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 258026586832; DSPS: 8596304; Offset : -4327664520
,I/jxcore-log( 6637): TAP version 13
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # multiplex can send data
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 1 String should be length:200
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # enqueue and run in order
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 2 firstPromise setTimeout
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 3 firstPromise result
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 4 firstPromise testValue
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 5 secondPromise setTimeout
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 6 secondPromise result
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 7 secondPromise testValue
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 8 thirdPromise in promise
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 9 thirdPromise result
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 10 thirdPromise testValue
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # basic
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 11 sane
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # another
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 12 sane
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 13 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 14 null
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 15 (unnamed assert)
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 16 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 17 should not throw
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 18 (unnamed assert)
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 19 (unnamed assert)
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 20 should not throw
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 21 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 22 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 23 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # failed to get mobile documents path
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 24 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 25 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 26 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 27 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #init should register the networkChanged event
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 28 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3a652155 type 2 when 264032 android} when 264032
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,I/jxcore-log( 6637): # #startBroadcasting should throw on null device name
I/jxcore-log( 6637): 
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 29 should throw
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 30 should throw
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 31 should throw
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 32 should throw
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #startBroadcasting should throw on negative port
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 33 should throw
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startBroadcasting should throw on too large port
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 34 should throw
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 35 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 36 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 37 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 38 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 39 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 40 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 41 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 42 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 43 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 44 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 45 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 46 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 47 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 48 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 49 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 50 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 51 should be equal
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 52 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 53 should be equal
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #start should fail if called twice in a row
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 54 specific error should be received
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 55 specific error should be returned
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 56 error should be null
I/jxcore-log( 6637): 
I/jxcore-log( 6637): ok 57 error should be null
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 58 error should be null
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 59 error should be null
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 60 error should be null
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 61 error should be null
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): ok 62 specific error should be returned
I/jxcore-log( 6637): 
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): # teardown
I/jxcore-log( 6637): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25e7a63f added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399171.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399171.6637","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399171.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399171.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399171.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399171.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3764): [BTUI] createSocketChannel FD=84 mFd=82
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a1ebae6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a1ebae6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393137312e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393137312e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393137311f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393137311f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1967): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399171.6637, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
I/jxcore-log( 6637): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393137311f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393137311f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6637): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dba675b added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399293.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399293.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399293.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399293.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399293.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399293.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3beab1c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3beab1c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393239332e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393239332e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393239331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393239331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399293.6637, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/jxcore-log( 6637): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState:, NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393239331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393239331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6637): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2e1e37 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/B,luetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399367.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399367.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399367.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399367.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399367.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399367.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24fc7518 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@24fc7518 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393336372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393336372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393336371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393336371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399367.6637, mode: WIFI
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1039): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
I/jxcore-log( 6637): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393336371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393336371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btcon,nectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
D/LGWifiP2pService( 1039): discovery change broadcast false
I/jxcore-log( 6637): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30bc66d3 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399406.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399406.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399406.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399406.6637","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399406.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399406.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9e9ffba4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9e9ffba4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393430362e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393430362e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393430361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393430361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399406.6637, mode: WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6637): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/LGWifiP2pService( 1039): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6637): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdc9d2f added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393430361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393430361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-5ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1039): InactiveState{ when=-7ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-8ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: ,Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399447.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399447.6637","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399447.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399447.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399447.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399447.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@62480bda target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@62480bda target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
,D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393434372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399447.6637, mode: WIFI
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393434372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393434371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393434371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/jxcore-log( 6637): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceD,iscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393434371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6637): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393434371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@141fdd4b added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399498.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399498.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399498.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399498.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399498.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399498.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@34af0dce target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@34af0dce target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393439382e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393439382e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393439381f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393439381f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399498.6637, mode: WIFI
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=55 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.intern,al.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
I/jxcore-log( 6637): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6637): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393439381f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393439381f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6637): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btco,nnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@250d0327 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399566.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399566.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399566.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399566.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399566.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399566.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@51e32056 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@51e32056 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393536362e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393536362e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393536361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393536361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1967): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399566.6637, mode: WIFI
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/jxcore-log( 6637): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started s,uccessfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393536361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393536361f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/jxcore-log( 6637): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15bcaac3 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.Disc,overyManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399627.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399627.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399627.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399627.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399627.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399627.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fa5d1cda target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fa5d1cda target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393632372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393632372e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393632371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393632371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399627.6637, mode: WIFI
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6637): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/LGWifiP2pService( 1039): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p,.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6637): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b35301f added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393632371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393632371f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-9ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-10ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-10ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorl,ib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399694.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399694.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399694.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399694.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399694.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399694.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c790dd52 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c790dd52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393639342e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393639342e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393639341f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393639341f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399694.6637, mode: WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/jxcore-log( 6637): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 6637): stop
,E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/jxcore-log( 6637): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1039): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6637): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86af3b added. We now have 11 listener(s)
D/LGWifiP2pService( 1039): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393639341f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393639341f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
,D/LGWifiP2pService( 1039): InactiveState{ when=-6ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-8ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-8ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399753.6637
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399753.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6637): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6637): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399753.6637, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6637): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455058399753.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: {"pi":"58:3F:54:73:64:C0","pn":"1455058399753.6637","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455058399753.6637","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5eb2475a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5eb2475a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393735332e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353035383339393735332e36363337222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393735331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
I/io.jxcore.node.ConnectionHelper( 6637): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455058399753.6637, mode: WIFI
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6637): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 6637): 
I/io.jxcore.node.ConnectionHelper( 6637): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6637): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6637): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6637): setState: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393735331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6637): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6637): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local service added successfully
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6637): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6637): stop: Stopping services
I/wpa_supplicant( 2684): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6637): release: No more listeners, de-initializing...
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6637): release: No more listeners, de-initializing...
D/WfdsMonitor( 1967): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6637): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6637): setState: NOT_STARTED
I/io.jxcore.node.Co,nnectionHelper( 6637): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6637): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 6637): 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): setState: STARTED
D/LGWifiP2pService( 1039): discovery change broadcast true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2684): P2P-FIND-STOPPED 
D/WfdsMonitor( 1967): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/jxcore-log( 6637): # setup
I/jxcore-log( 6637): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393735331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353035383339393735331f36363337222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6637): Local services cleared successfully
,D/LGWifiP2pService( 1039): InactiveState{ when=-6ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-7ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=-7ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6637): Service requests cleared successfully,
D/LGWifiP2pService( 1039): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): Start timer timeout, starting now...,
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6637): start: Cannot start, because not initialized
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 278028470054; DSPS: 9251726; Offset : -4327673362
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{27907456 type 2 when 297865 android} when 297865
,I/BooksSync( 7487): Starting books sync
,D/BooksSync( 7487): started syncMyEbooks
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 298032676193; DSPS: 9907224; Offset : -4327677008
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
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
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2338101806206517631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/HttpHelper( 7487): null auth token
W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2338101806206517631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2338101806206517631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,E/BooksSync( 7487): Soft error: 
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2338101806206517631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    },
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
,E/BooksSync( 7487): Sync error
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2338101806206517631&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
I/BooksSync( 7487): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297865, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3764): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 318034072540; DSPS: 10562630; Offset : -4327686370
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3877d490 type 2 when 327910 android} when 327910
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 338035603834; DSPS: 11218040; Offset : -4327680695
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 358037440128; DSPS: 11873460; Offset : -4327675508
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 378039299547; DSPS: 12528881; Offset : -4327677635
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 398042314957; DSPS: 13184340; Offset : -4327683491
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 418043890626; DSPS: 13839751; Offset : -4327664219
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{5299189 type 2 when 422001 android} when 422001
,I/BooksSync( 7487): Starting books sync
,D/BooksSync( 7487): started syncMyEbooks
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 33616(1751KB) AllocSpace objects, 9(912KB) LOS objects, 33% free, 44MB/66MB, paused 2.390ms total 153.022ms
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4363535440222255540&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4363535440222255540&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2139): Explicit concurrent mark sweep GC freed 51388(2MB) AllocSpace objects, 24(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.011ms total 75.258ms
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4363535440222255540&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,E/BooksSync( 7487): Soft error: 
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4363535440222255540&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
,E/BooksSync( 7487): Sync error
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4363535440222255540&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
I/BooksSync( 7487): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 422001, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/PlayEventLogger( 7301): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7301): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7301): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7301): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7301): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7301): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7301): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 7301): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 438045953796; DSPS: 14495179; Offset : -4327676400
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2a48fe95 type 2 when 452048 android} when 452048
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 458047956652; DSPS: 15150605; Offset : -4327687549
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 478049949717; DSPS: 15806030; Offset : -4327678100
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 498052538617; DSPS: 16461475; Offset : -4327683194
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 518054109077; DSPS: 17116886; Offset : -4327669157
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 538056297508; DSPS: 17772318; Offset : -4327678121
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 558058370104; DSPS: 18427746; Offset : -4327680538
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 578061182284; DSPS: 19083198; Offset : -4327676027
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 598062991339; DSPS: 19738617; Offset : -4327667353
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 618065095289; DSPS: 20394046; Offset : -4327669247
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 638066982365; DSPS: 21049468; Offset : -4327674286
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 658068801003; DSPS: 21704888; Offset : -4327686625
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3ae3fbaa type 2 when 666526 android} when 666526
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,I/BooksSync( 7487): Starting books sync
,D/BooksSync( 7487): started syncMyEbooks
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): errCount = 1: com.google.android.apps.books.net.HttpHelper$UncategorizedIoException: java.io.EOFException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4595653789620312075&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{25313a68 type 0 when 1455058800000 com.google.android.gms} when 1455058800000
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
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
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7487): null auth token
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4595653789620312075&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{25c472ac type 0 when 1455058685691 com.google.android.gms} when 1455058685691
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{c9d6b75 type 0 when 1455058800889 com.lge.ia.task.informant} when 1455058800889
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2742970a type 0 when 1455058800891 com.lge.ia.task.s4urecommender} when 1455058800891
D/LIA_Informant_DailyScheduler( 3687): onReceive! : com.lge.ia.task.informant.scheduler.DailyScheduler.1
D/LIA_Informant_DailyScheduler( 3687): onScheduler currentDate : 20160210
,D/LIA_Informant_AnniversaryRequester( 3687): request
D/LIA_Informant_InformantCalendarUtil( 3687): getCalendarList startTime = 2016-02-09 23:59:59
,D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): ConditionDetectorReceiver onReceive called!! action : com.lge.ia.task.s4urecommender.conditionDetectorStart
D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): firstTime : Wed Feb 10 00:00:01 GMT+01:00 2016 endTime : Wed Feb 10 06:00:01 GMT+01:00 2016
,D/LIA_S4URecommender_BatteryStatusChecker( 3687): isCharging : false fullyCharged : true level : 100
D/LIA_S4URecommender_ScreenStatusChecker( 3687): isInteractive : false
D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): Batch job Start condition - No Additional alarm setting!!
D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): On Receive End
,D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): runBatch Start!
D/LIA_S4URecommender_AsyncChannel( 3687): Receive Order (21)
D/LIA_S4URecommender_AsyncChannel( 3687): Send Order (21)
,D/LIA_Informant_InformantCalendarUtil( 3687): cursor size = 0
,D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): [Condition]Batch Done Callback
D/LIA_Informant_AnniversaryRequester( 3687): no schedule for day 0
D/LIA_Informant_InformantCalendarUtil( 3687): getCalendarList startTime = 2016-02-16 23:59:59
D/LIA_Informant_InformantCalendarUtil( 3687): cursor size = 0
,D/LIA_Informant_AnniversaryRequester( 3687): no schedule for day 7
W/ActivityManager( 1039): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2089): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=9 dayofweek=4 currentDayOfWeek=3
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
,I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/EventLogService( 2399): Aggregate from 1455056885603 (log), 1455056885603 (data)
,D/LIA_S4URecommender_ConditionDetectorReceiver( 3687): [Condition] Service End with batch job processed!!
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2139): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2139): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2139): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2139): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2139): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2139): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2139): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2139): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2139): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2139): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 7487): Authentication error
E/BooksAccountManager( 7487): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7487): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7487): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7487): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7487): null auth token
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{14eb2368 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7487): Error response from books API: {
W/ApiaryClient( 7487):  "error": {
W/ApiaryClient( 7487):   "errors": [
W/ApiaryClient( 7487):    {
W/ApiaryClient( 7487):     "domain": "global",
W/ApiaryClient( 7487):     "reason": "required",
W/ApiaryClient( 7487):     "message": "Login Required",
W/ApiaryClient( 7487):     "locationType": "header",
W/ApiaryClient( 7487):     "location": "Authorization"
W/ApiaryClient( 7487):    }
W/ApiaryClient( 7487):   ],
W/ApiaryClient( 7487):   "code": 401,
W/ApiaryClient( 7487):   "message": "Login Required"
W/ApiaryClient( 7487):  }
W/ApiaryClient( 7487): }
,W/ApiaryClient( 7487): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4595653789620312075&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7487): Headers:
W/ApiaryClient( 7487): accept-encoding: [gzip]
W/ApiaryClient( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7487): gdata-version: 2
,E/BooksSync( 7487): Soft error: 
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4595653789620312075&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
,E/BooksSync( 7487): Sync error
E/BooksSync( 7487): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7487): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4595653789620312075&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7487): Headers:
E/BooksSync( 7487): accept-encoding: [gzip]
E/BooksSync( 7487): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7487): gdata-version: 2
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7487): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7487): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7487): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7487): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7487): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7487): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7487): {
E/BooksSync( 7487):  "error": {
E/BooksSync( 7487):   "errors": [
E/BooksSync( 7487):    {
E/BooksSync( 7487):     "domain": "global",
E/BooksSync( 7487):     "reason": "required",
E/BooksSync( 7487):     "message": "Login Required",
E/BooksSync( 7487):     "locationType": "header",
E/BooksSync( 7487):     "location": "Authorization"
E/BooksSync( 7487):    }
E/BooksSync( 7487):   ],
E/BooksSync( 7487):   "code": 401,
E/BooksSync( 7487):   "message": "Login Required"
E/BooksSync( 7487):  }
E/BooksSync( 7487): }
E/BooksSync( 7487): 
E/BooksSync( 7487): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7487): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7487): 	... 8 more
I/BooksSync( 7487): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 666526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 678071277506; DSPS: 22360329; Offset : -4327682202
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{25a11be5 type 2 when 696759 android} when 696759
,I/DigitalAppWidgetProvider( 7106): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7106): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1357c3f9
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 698072977082; DSPS: 23015744; Offset : -4327661223
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 718075034835; DSPS: 23671172; Offset : -4327678535
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 738077095764; DSPS: 24326599; Offset : -4327662180
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 758079090236; DSPS: 24982025; Offset : -4327681920
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 778081326895; DSPS: 25637458; Offset : -4327673122
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3764): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 798083177460; DSPS: 26292879; Offset : -4327684103
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 100%
D/LEDHandler( 1967): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3764): Disconnected process message: 10, size: 0
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 818085108494; DSPS: 26948302; Offset : -4327675625
,I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1039): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1039): InitialState.processMessage what=4
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=823770
E/WifiStateMachine( 1039):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=823770
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=823770
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1039): RunningState{ when=-15ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2139): Read error: ssl=0xaf460a00: I/O error during system call, Connection timed out
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/jxcore-log( 6637): Toggling radios to false
I/jxcore-log( 6637): 
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7882 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2139): SSL shutdown failed: ssl=0xaf460a00: I/O error during system call, Broken pipe
,I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
,D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): ignoring duplicate network state non-change
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1039): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1436d6ba mBinding = false
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=823946  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 66 0 rt=823947  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=823954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 67 0 rt=823962  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
D/BluetoothManagerService( 1039): Message: 2
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/BluetoothManagerService( 1039): Sending off request.
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LGBluetoothServiceAdapter( 3764): [BTUI] Precleanup
D/BluetoothAdapterState( 3764): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3764): Setting state to 13
I/BluetoothAdapterState( 3764): Bluetooth adapter state changed: 12-> 13
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/BluetoothAdapterProperties( 3764): onBluetoothDisable()
I/BluetoothAdapterState( 3764): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 12 -> 13
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/BluetoothAdapterProperties( 3764): Scan Mode:20
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=6637, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=6637, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
,I/BluetoothMapService( 3764): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3764): STATE_TURNING_OFF
V/BluetoothMapService( 3764): Handler(): got msg=4
D/BluetoothMapService( 3764): MAP Service closeService in
D/BluetoothMapMasInstance( 3764): MAP Service shutdown
D/BluetoothAdapterState( 3764): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3764): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3764): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3764): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3764): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3764): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3764): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3764): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3764): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3764): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3764): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x000f
D/LGBluetoothMapAdapter( 3764): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3764): MAP Service closeService out
E/BtOppRfcommListener( 3764): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 3764): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3764): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
V/BluetoothSapService( 3764): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
V/BtOppService( 3764): Receiver DISABLED_ACTION 
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/BtOppRfcommListener( 3764): stopping Accept Thread
V/BtOppRfcommListener( 3764): close mBtServerSocket
V/BtOppRfcommListener( 3764): waiting for thread to terminate
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/BtOppRfcommListener( 3764): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3764): done waiting for thread to terminate
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3764): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3764): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3764): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3764): bta_gattc_deregister Deregister Failedm unknown client cif
D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1470): CM callback handler got msg 524292
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/BtOppService( 3764): onDestroy
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1039): Removing idletimer
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]BluetoothHandler( 1470): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LGBluetoothOppAdapter( 3764): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,I/jxcore-log( 6637): Radios toggled
I/jxcore-log( 6637): 
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
E/WifiStateMachine( 1039):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1039): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2ee39077
D/WifiScanningService( 1039): SCAN_AVAILABLE : 1
D/RttService( 1039): SCAN_AVAILABLE : 1
D/WifiScanningService( 1039): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1039): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pDisablingState
D/LGWifiP2pService( 1039): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): p2p socket connection lost
D/LGWifiP2pService( 1039): P2pDisabledState
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,D/LGWifiP2pService( 1039): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2684): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
W/ResourcesManager( 7882): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CommandListener(  315): Clearing all IP addresses on wlan0
W/ResourcesManager( 7882): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7882): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1967): WifiP2pState is changed : false
D/WfdsService( 1967): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1967): Set the WFDS Monitor: false
D/WfdsMonitor( 1967): WFDS Monitor is stopped
D/CtrlSupplicant( 1967): Received on exit socket, terminate
E/CtrlSupplicant( 1967): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WifiNative-p2p0( 1039): doBoolean: TERMINATE
D/WfdsService( 1967): STATE : WfdsDisabledState - enter
D/WfdsMonitor( 1967): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1967): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1967): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1967): DefaultState - msg [9441355] is not handled
D/WifiNative-p2p0( 1039): TERMINATE: returned true
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 6
,I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [0]
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1470): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1470): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1470): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1039): StoppedState
,D/DhcpStateMachine( 1039): StoppedState{ when=-124ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1039):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_ON_QUIT 0 0
,W/ContextImpl( 7882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 3764): PbapReceiver onReceive 
,D/UsbSettingsReceiver( 7882): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
V/BluetoothPbapReceiver( 3764): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,D/UsbSettingsReceiver( 7882): [AUTORUN] sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 3764): ***********state = 13
D/UsbSettingsReceiver( 7882): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7882): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7882): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapReceiver( 3764): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3764): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3764): state: 13
V/BluetoothPbapService( 3764): Pbap Service closeService in
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7926 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 3764): successfully stopped pbap service
,V/BluetoothPbapService( 3764): Pbap Service closeService out
V/BluetoothPbapService( 3764): Pbap Service onDestroy
V/BluetoothPbapService( 3764): Pbap Service closeService in
V/BluetoothPbapService( 3764): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3764): [BTUI] cleanup
D/UsbSettingsControl( 7882): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7882): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7882): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7882): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7882): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7882): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16eba486:true
,I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7945 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 19.155ms
,D/BluetoothManagerService( 1039): Message: 30
D/BluetoothManagerService( 1039): Message: 30
D/LocalBluetoothProfileManager( 7882): Adding local MAP profile
D/BluetoothMap( 7882): Create BluetoothMap proxy object
D/BluetoothManagerService( 1039): Message: 30
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 15.849ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 13.174ms
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 52359(2MB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 2.728ms total 119.676ms
,D/BluetoothManagerService( 1039): Message: 30
E/ActivityThread( 7926): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7926): No ProfileInfo entries
I/LG Account v2.2( 7926): isEnabled: false
I/Feature ( 7926): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7926): [Lifetracker]Country: EU
I/Feature ( 7926): [Lifetracker]Operator: OPEN
,I/Feature ( 7926): [Lifetracker]Ranking support: false
I/Feature ( 7926): [Lifetracker]Comfort support: false
I/Feature ( 7926): [Lifetracker]Accessory: true
I/Feature ( 7926): [Lifetracker]Health device: true
I/Feature ( 7926): [Lifetracker]Extra Pedometer: false
I/Feature ( 7926): [Lifetracker]Blood glucose device: false
I/Feature ( 7926): [Lifetracker]Device Number: 3
I/ActivityManager( 1039): Killing 6887:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/PCSuite ( 7945): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/libprocessgroup( 1039): failed to open /acct/uid_10026/pid_6887/cgroup.procs: No such file or directory
,D/LocalBluetoothProfileManager( 7882): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7882):  get() - isFeatureLoaded : false
I/ActivityManager( 1039): Killing 6923:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10057/pid_6923/cgroup.procs: No such file or directory
,D/LGBluetoothUserBindClient( 7882): [BTUI] initUserBindClient
W/ContextImpl( 7882): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 7882): finishStartingService: stopping service
,D/BluetoothInputDevice( 7882): Proxy object connected
,D/HidProfile( 7882): Bluetooth service connected
D/BluetoothPan( 7882): BluetoothPAN Proxy object connected
D/PanProfile( 7882): Bluetooth service connected
D/BluetoothMap( 7882): Proxy object connected
D/MapProfile( 7882): Bluetooth service connected
D/BluetoothMap( 7882): getConnectedDevices()
D/BluetoothMap( 7882): Bluetooth is Not enabled
,V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7882): LgDataFeature() Constructor: none
,D/LgDataFeature( 7882): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 7882): [BTUI] onServiceConnected
,D/LGBluetoothAuthorization( 7882): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 7882): onReceive
,D/LGBluetoothAuthorization( 7882): [BTUI] cancel All Notification
,I/ActivityManager( 1039): Killing 6956:com.lge.drmservice/u0a62 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 7882): return without doing reset settings.
,V/BluetoothOppReceiver( 3764): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3764): [BTUI] cancel opp incoming file confirm notification
W/libprocessgroup( 1039): failed to open /acct/uid_10062/pid_6956/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3764): [BTUI] cancel opp active transfer file notification
,V/BluetoothFtpReceiver( 3764): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3764): BluetoothFtpReceiver Start Service
,D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3764): Ftp Service onStartCommand
V/BluetoothFtpService( 3764): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3764): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3764): Shutdown
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothFtpService( 3764): successfully stopped ftp service
V/BluetoothSapReceiver( 3764): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3764): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3764): SapReceiver onReceive 
V/BluetoothSapReceiver( 3764): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3764):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3764): Calling SAP service start service with action = null
,V/BluetoothFtpService( 3764): Ftp Service onDestroy
V/BluetoothFtpService( 3764): Ftp Service closeService
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothSapService( 3764): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3764): state: 13
V/BluetoothSapService( 3764): Stopping SAP server process
V/BluetoothSapService( 3764): Sap Service closeSapService in
V/BluetoothSapService( 3764): Close listen Socket : 
V/BluetoothSapService( 3764): Close rfcomm Socket : 
V/BluetoothSapService( 3764): Close sapd  Socket : 
W/bt-btif ( 3764): ag scb idx 1 not allocated
D/bt_hci_bdroid( 3764): cleanup
E/bt-btif ( 3764): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0019
I/bt_lpm  ( 3764): LPM is already off!!!
,W/bt-l2cap( 3764): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3764): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3764): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3764): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3764): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3764): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3764): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_userial_mct( 3764): exiting userial_read_thread
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/bt_userial_mct( 3764): Leaving userial_evt_read_thread()
W/bt-l2cap( 3764): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3764): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3764): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3764): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3764): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3764): hw_epilog_process
D/bt_hci_bdroid( 3764): cleanup Finalizing cleanup
D/bt_userial_mct( 3764): userial_close
E/bt_userial_mct( 3764): pthread_join() FAILED result:3
I/bt_vendor( 3764): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/ActivityManager( 1039): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7980 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3764): Sap Service closeSapService out
,V/BluetoothSapService( 3764): Sap Service onDestroy
V/BluetoothSapService( 3764): Sap Service closeSapService in
V/BluetoothSapService( 3764): Close listen Socket : 
V/BluetoothSapService( 3764): Close rfcomm Socket : 
V/BluetoothSapService( 3764): Close sapd  Socket : 
V/BluetoothSapService( 3764): Sap Service closeSapService out
I/PCSuite ( 7945): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/bt_hci_bdroid( 3764): set_power 0
I/bt_vendor( 3764): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3764): bluetooth satus is on
I/bt_vendor( 3764): bt-vendor : resetting BT status
I/bt_vendor( 3764): Starting hciattach daemon
I/bt_vendor( 3764): try to set false
I/bt_vendor( 3764): Starting hciattach daemon
I/bt_vendor( 3764): try to set false
,I/bt_vendor( 3764): cleanup
I/GKI_LINUX( 3764): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3764): GKI_exit_task 0 done
I/GKI_LINUX( 3764): GKI_shutdown(): task [BTU] terminated
D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/BluetoothAdapterState( 3764): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3764): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 3764): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3764): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
D/HeadsetStateMachine( 3764): Exit Disconnected: -1
,D/A2dpService( 3764): Received stop request...Stopping profile...
D/A2dpStateMachine( 3764): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3764): [BTUI] cleanup
D/BluetoothHeadset( 1872): Proxy object disconnected
D/BluetoothHeadset( 1872): Proxy object disconnected
D/BluetoothHeadset( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 1
D/LGBluetoothA2dpAdapter( 3764): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3764): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
D/BluetoothHeadset( 1872): Proxy object disconnected
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothA2dp( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothAdapterState( 3764): Stopping profile services that were post enabled
D/HidService( 3764): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
D/HeadsetStateMachine( 3764): Unbinding service...
D/BluetoothInputDevice( 7882): Proxy object disconnected
D/HeadsetPhoneState( 3764): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3764): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3764): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3764): [BTUI] listenForMultiSimPhoneState : start = false
D/HidProfile( 7882): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 3764): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3764): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3764): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 3764): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PanService( 3764): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
D/BtGatt.DebugUtils( 3764): handleDebugAction() action=null
D/BtGatt.GattService( 3764): Received stop request...Stopping profile...
D/BtGatt.GattService( 3764): stop()
D/BtGatt.AdvertiseManager( 3764): advertise clients cleared
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
D/BluetoothPan( 7882): BluetoothPAN Proxy object disconnected
D/PanProfile( 7882): Bluetooth service disconnected
I/BluetoothA2dpServiceJni( 3764): cleanupNative
I/GKI_LINUX( 3764): gki_task task_id=2 [A2DP-MEDIA] terminating
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/GKI_LINUX( 3764): GKI_exit_task 2 done
I/GKI_LINUX( 3764): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 3764): Received stop request...Stopping profile...
D/BluetoothMapService( 3764): stop()
D/BluetoothMapEmailAppObserver( 3764): deinitObservers()
D/BluetoothMapEmailAppObserver( 3764): removeReceiver()
D/BluetoothAdapterService( 3764): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1357c3f9
I/PCSuite ( 7945): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/BluetoothHidServiceJni( 3764): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3764): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3764): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3764): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3764): Cleaning up Bluetooth Health object
D/BluetoothMap( 7882): Proxy object disconnected
D/MapProfile( 7882): Bluetooth service disconnected
W/BluetoothPanServiceJni( 3764): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3764): Cleaning up Bluetooth PAN callback object
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothMapService( 3764): Handler(): got msg=4
D/BluetoothMapService( 3764): MAP Service closeService in
D/LGBluetoothMapAdapter( 3764): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3764): MAP Service closeService out
D/BluetoothMapService( 3764): cleanup()
D/BluetoothMapService( 3764): MAP Service closeService in
D/LGBluetoothMapAdapter( 3764): [BTUI] LGBluetoothMapAdapter cleanup
D/BluetoothAdapterState( 3764): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3764): Setting state to 10
I/BluetoothAdapterState( 3764): Bluetooth adapter state changed: 13-> 10
V/BluetoothMapService( 3764): MAP Service closeService out
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1039): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3764): Entering OffState
D/BluetoothHeadset( 1872): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1872): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1039): onBluetoothStateChange: up=false
,D/BluetoothMap( 7882): onBluetoothStateChange: up=false
D/BluetoothPbap( 7882): onBluetoothStateChange: up=false
D/BluetoothPan( 7882): onBluetoothStateChange on: false
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/BluetoothHeadset( 1872): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7882): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1039): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1039): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/BluetoothManagerService( 1039): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1039): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1436d6ba mBinding = false
D/BluetoothManagerService( 1039): Sending unbind request.
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 13 -> 10
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ResourcesManager( 7980): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/GKI_LINUX( 3764): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3764): GKI_exit_task 1 done
I/GKI_LINUX( 3764): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3764): cleanupNative: return from cleanup
I/art     ( 3764): --- WEIRD: removing null entry 246
W/art     ( 3764): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3764): Cleaning up Bluetooth Service callback object
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1967): Message: 2
D/LGBluetoothAPIService( 1967): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@386d710 mBinding = false
D/LGBluetoothAPIService( 1967): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1470): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothSettingsDBObserver( 3764): [BTUI] unregister observer for LG device name DB
I/art     ( 3764): System.exit called, status: 0
I/AndroidRuntime( 3764): VM exiting with result code 0, cleanup skipped.
D/LGBluetoothFeatureConfig( 7882): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7882): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7882): [BTUI] clear device connection state
,D/BluetoothAdapter( 1470): 583456571: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1470): 583456571: getState() :  mService = null. Returning STATE_OFF
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/AuthorizationBluetoothService( 2139): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
I/ActivityManager( 1039): Killing 6995:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
W/ContextImpl( 7882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/AudioFlinger(  319): 3764 died, releasing its sessions
V/AudioFlinger(  319):  pid 1872 @ 0
V/AudioFlinger(  319):  pid 3278 @ 1
V/AudioFlinger(  319):  pid 3278 @ 2
,W/BroadcastQueue( 1039): Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
W/BroadcastQueue( 1039): android.os.DeadObjectException
W/BroadcastQueue( 1039): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1039): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 1039): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue( 1039): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
W/BroadcastQueue( 1039): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
W/BroadcastQueue( 1039): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
W/BroadcastQueue( 1039): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue( 1039): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
W/BroadcastQueue( 1039): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
W/BroadcastQueue( 1039): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,I/ActivityManager( 1039): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8007 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,W/ActivityManager( 1039): Spurious death for ProcessRecord{18e77598 8007:com.android.bluetooth/1002}, curProc for 3764: null
D/LGBluetoothUserBindClient( 7882): [BTUI] onServiceDisconnected
W/libprocessgroup( 1039): failed to open /acct/uid_10093/pid_6995/cgroup.procs: No such file or directory
D/DockEventReceiver( 7882): finishStartingService: stopping service
,D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7945): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ResourcesManager( 8007): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8007): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8007): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 8007): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7945): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/QRemote ( 6502): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6502): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6502): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/BluetoothAdapterApp( 8007): Loading JNI Library
D/BluetoothAdapterApp( 8007): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@fb9a966 Instance Count = 1
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8025 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/BluetoothAdapterApp( 8007): onCreate
D/ProfileConfigQcom( 8007): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 8007): Adding HeadsetService
,D/ProfileConfigQcom( 8007): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8007): Adding A2dpService
D/ProfileConfigQcom( 8007): [BTUI] HidService is supported
D/ProfileConfigQcom( 8007): Adding HidService
D/ProfileConfigQcom( 8007): [BTUI] HealthService is supported
D/ProfileConfigQcom( 8007): Adding HealthService
D/LGBluetoothFeatureConfig( 8007): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 8007): [BTUI] PanService is supported
D/ProfileConfigQcom( 8007): Adding PanService
D/ProfileConfigQcom( 8007): [BTUI] GattService is supported
D/ProfileConfigQcom( 8007): Adding GattService
D/ProfileConfigQcom( 8007): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8007): Adding BluetoothMapService
D/ProfileConfigQcom( 8007): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 8007): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 8007): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 8007): ***********state = 10
V/LGMDMManagerInternal( 8007): Create singleton instance
,D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
W/FormManager( 8025): Network not available. Please check & try again.
,V/FormManager( 8025): Network unavailable.
,D/LGBluetoothUserBindClient( 7882): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 7882): onReceive
D/LGBluetoothUtils( 7882): [BTUI] FileNotFound: readProperty
V/FormManager( 8025): Network unavailable.
D/BluetoothDiscoverableTimeoutReceiver( 7882): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7882): return without doing reset settings.
,D/LGBluetoothOppAdapter( 8007): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 8007): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 8007): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 8007): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 8007): SapReceiver onReceive 
,V/BluetoothSapReceiver( 8007): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 8007):  Bluetooth Adapter state = 10
I/ActivityManager( 1039): Killing 7059:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 7980): [BTUI] STATE_OFF : reset connected device information EasySettings
,I/ActivityManager( 1039): Killing 6976:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,I/wpa_supplicant( 2684): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2684): monitor socket send errors count : 1
I/wpa_supplicant( 2684): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-2\x00 that cannot receive messages
W/wpa_supplicant( 2684): USIM:  scard_deinit function
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1039): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 69 0 rt=825988  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,E/WifiStateMachine( 1039):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 69 0 rt=825989  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_7059/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2139): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1039): failed to open /acct/uid_10085/pid_6976/cgroup.procs: No such file or directory
I/wpa_supplicant( 2684): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1039): Disconnecting from the supplicant, no more events
,E/WifiStateMachine( 1039):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 70 0
,D/WfdsService( 1967): Supplicant Connection state is changed : false
,D/WfdsService( 1967): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,D/WfdsService( 1967): Set the WFDS Monitor: false
,D/WfdsMonitor( 1967): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1039): stopMonitoring
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1470): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1837): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7945): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,D/PCSuite ( 7945): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7945): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7882): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7882): MCCMNC not supported: null
D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/FormManager( 8025): Network unavailable.
V/FormManager( 8025): Network unavailable.
W/FormManager( 8025): Network not available. Please check & try again.
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{30003a1a type 2 when 826887 com.google.android.gms} when 826887
,D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5513): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5513): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8090 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 8090): onCreate
,W/AppUp4:DB( 8090):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8090):  setFingerPrint start
I/AppUp4:DB( 8090):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 8090):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 8090):  SDK version = 21
I/AppUp4:DB( 8090):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8090): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8090): onReceive
D/LgDataFeature( 8090): LgDataFeature() Constructor: none
D/LgDataFeature( 8090): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 8090): Context : android.app.ReceiverRestrictedContext@bee8ac0
D/AppUp4:CustFacade( 8090): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8090): isPhone : true
D/AppUp4:CustModeStarterReceiver( 8090): begin check event
I/AppUp4:CustModeStarterReceiver( 8090): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 8090): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 8090): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 8090): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 8090): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 7358:com.google.android.gms:car/u0a5 (adj 15): empty #17
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_7358/cgroup.procs: No such file or directory
,D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8113 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8113): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8113): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8113): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 8113): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8113): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 8113): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8113): LgDataFeature() Constructor: none
D/LgDataFeature( 8113): LgDataFeature() Constructor Done, null
,D/eas_req ( 8113): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3278): networkInfo.isConnected() = false
,I/HubEmail( 8113): JNI_OnLoad()
I/HubEmail( 8113): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8113): registerNatives()
I/HubEmail( 8113): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8113): registerNativeMethods()
I/HubEmail( 8113): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 8113): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8142 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 8025): Network not available. Please check & try again.
,W/Settings( 8113): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 8025): Network unavailable.
V/FormManager( 8025): Network unavailable.
I/ActivityManager( 1039): Killing 7396:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_7396/cgroup.procs: No such file or directory
I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8174 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 7301:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_7301/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8192 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 7208:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10014/pid_7208/cgroup.procs: No such file or directory
,I/art     ( 8192): Almond Protected OAT
,D/WeatherApplication( 8192): removeAccount
,D/WeatherApplication( 8192): Account.length = 0
,E/WeatherApplication( 8192): OPERATOR:OPEN
,D/WeatherAncestor( 8192): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:2:41
D/Weather.Utils( 8192): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8192): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8192): 2 : This is isUpdating : false
,D/WeatherAncestor( 8192): connectivity changed - connection : true
,D/WeatherService( 8192): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 8192): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8192): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8192): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 8192): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8192): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:2:41
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8210 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 2399:com.google.android.gms/u0a5 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_2399/cgroup.procs: No such file or directory
,D/LGWifiP2pService( 1039): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1039):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1039):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8210): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8210): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8210): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8210): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager( 1039): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8247 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/WebViewFactory( 8210): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8210): Loading: webviewchromium
,I/LibraryLoader( 8210): Time to load native libraries: 6 ms (timestamps 9368-9374)
I/LibraryLoader( 8210): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8210): Binding Chromium to main looper Looper (main, tid 1) {df0a725}
,I/LibraryLoader( 8210): Expected native library version number "",actual native library version number ""
,I/chromium( 8210): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8210): Initializing chromium process, renderers=0
W/ResourcesManager( 8247): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/art     ( 8210): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourcesManager( 8247): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/chromium( 8210): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8210): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 8210): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb15232e0, uid 10093
W/AudioManagerAndroid( 8210): Requires BLUETOOTH permission
,I/Adreno-EGL( 8210): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8210): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8210): Build Date: 12/12/14 금
I/Adreno-EGL( 8210): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8210): Remote Branch: 
I/Adreno-EGL( 8210): Local Patches: 
I/Adreno-EGL( 8210): Reconstruct Branch: 
I/MultiDex( 8247): VM with version 2.1.0 has multidex support
I/MultiDex( 8247): install
I/MultiDex( 8247): VM has multidex support, MultiDex support library is disabled.
,I/NSApplication( 8210): Starting up...
,I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8286 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 7487:com.google.android.apps.books/u0a54 (adj 15): empty #17
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 486us total 24.119ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 700us total 21.133ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 19.581ms
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_7487/cgroup.procs: No such file or directory
,W/ResourcesManager( 8286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8247): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8247): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8247): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f58b66b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8247): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1039): Killing 7106:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10010/pid_7106/cgroup.procs: No such file or directory
,I/GLSActivity( 2139): [ac] getting account id
,I/GLSUser ( 2139): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/iu.SyncManager( 8247): SYNC; picasa accounts
,D/NetworkLogImpl( 8247): Loaded NetworkSpeedPredictor
D/ChimeraCfgMgr( 8247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 8247): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8090): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 8090): onReceive
D/AppUp4:CustFacade( 8090): Context : android.app.ReceiverRestrictedContext@bee8ac0
D/AppUp4:CustFacade( 8090): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8090): isPhone : true
D/AppUp4:CustModeStarterReceiver( 8090): begin check event
I/AppUp4:CustModeStarterReceiver( 8090): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/art     ( 1039): Explicit concurrent mark sweep GC freed 35317(1672KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.819ms total 127.527ms
,D/eas_req ( 8113): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4202): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4202): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/Settings( 8113): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3278): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3278): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3278): networkInfo.isConnected() = false
W/FormManager( 8025): Network not available. Please check & try again.
D/WeatherAncestor( 8192): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:2:43
,D/Weather.Utils( 8192): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 8192): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8192): 2 : This is isUpdating : false
D/WeatherAncestor( 8192): connectivity changed - connection : true
D/WeatherService( 8192): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@5aa7f3e
D/ForecastDataCache( 8192): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8192): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8192): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 8192): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8192): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:2:43
V/FormManager( 8025): Network unavailable.
V/FormManager( 8025): Network unavailable.
,D/ChimeraCfgMgr( 8247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 8247): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,D/GCM     ( 2139): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2139): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 8247): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1039): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8343 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 8343): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8343): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LocationInitializer( 8247): Restart initialization of location
I/MultiDex( 8343): VM with version 2.1.0 has multidex support
I/MultiDex( 8343): install
I/MultiDex( 8343): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8343): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8343): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8343): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17249c05: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8343): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2139): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2139): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 8247): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8343): callingUid 10005, callindPid: 8343
D/LocationInitializer( 8247): Restart initialization of location
,E/MDM     ( 1837): [99] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1837): [99] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3bf78afb type 2 when 832857 com.google.android.gms} when 832857
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/GAv4-SVC( 8247): Google Analytics 7.8.99 is starting up.
,I/GAV4    ( 8210): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1039): Killing 7262:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6502): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6502): android.os.DeadObjectException
W/System.err( 6502): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6502): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6502): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6502): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,W/System.err( 6502): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6502): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6502): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6502): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6502): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6502): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/UEI.SmartControl( 6502): IControl.unregisterCallback error: android.os.DeadObjectException,
W/System.err( 6502): android.os.DeadObjectException
,W/System.err( 6502): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6502): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6502): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6502): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303),
W/System.err( 6502): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6502): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6502): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6502): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6502): ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6502): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6502): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6502): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6502): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6502): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7262/cgroup.procs: No such file or directory
W/ActivityManager( 1039): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,I/ActivityManager( 1039): Killing 6502:com.lge.qremote/u0a112 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10112/pid_6502/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 838086781559; DSPS: 27603717; Offset : -4327681234
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 858088791292; DSPS: 28259143; Offset : -4327685714
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 878090984201; DSPS: 28914575; Offset : -4327690044
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 898093079714; DSPS: 29570003; Offset : -4327669726
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1470): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1470): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1967): Battery Level Remaining: 100%
,D/LEDHandler( 1967): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1470): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1470): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1470): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4202): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction,
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 918095070175; DSPS: 30225428; Offset : -4327662882
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 938096940167; DSPS: 30880850; Offset : -4327684902
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 958099095784; DSPS: 31536280; Offset : -4327665515
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 978101781246; DSPS: 32191728; Offset : -4327665652
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 998103876863; DSPS: 32847157; Offset : -4327675774
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1018105699667; DSPS: 33502577; Offset : -4327683869
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1038107771900; DSPS: 34158005; Offset : -4327686962
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1058109843558; DSPS: 34813433; Offset : -4327690446
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1078112043917; DSPS: 35468865; Offset : -4327687276
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1098113469117; DSPS: 36124271; Offset : -4327665962
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1118115284942; DSPS: 36779691; Offset : -4327681295
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1138117402799; DSPS: 37435120; Offset : -4327668865
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
,I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3ba9dbd7 type 2 when 1151505 android} when 1151505
,D/[Concierge]Service( 2644): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1158119506802; DSPS: 38090549; Offset : -4327670913
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1178121697836; DSPS: 38745981; Offset : -4327676989
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1198123763141; DSPS: 39401409; Offset : -4327686983
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
,I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1218125604800; DSPS: 40056829; Offset : -4327676093
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1238127449584; DSPS: 40712249; Offset : -4327662363
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1258129532701; DSPS: 41367678; Offset : -4327685272
,I/[SystemUI]TimeTickManager( 1470): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1470): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1470): called onTimeUpdated()
I/[SystemUI]Clock( 1470): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
I/[SystemUI]DateView( 1470): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1470): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1278131255454; DSPS: 42023094; Offset : -4327671165
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1298133773780; DSPS: 42678537; Offset : -4327686110
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1318135580803; DSPS: 43333956; Offset : -4327679625
,TIME-OUT KILL (timeout was 1200000ms),D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=230284994, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
D/LIA_Informant_Tips_DateChangeManager( 3687): onReceive() : com.lge.ia.task.informant.dyk.userguide.DateChangeManager
I/LIA_Informant_Tips_LogTracer( 3687): [Log Tracer - Schedule Transition] Date Change Alarm Received : 2016-02-10 00:10:53...... Request
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{7984cc4 type 0 when 1455059400943 com.lge.ia.task.informant} when 1455059400943
D/[Concierge]Service( 2644): onStartCommand(). Type : 9
D/LIA_Informant_Tips_DateChangeManager( 3687): setNextDayAlarm() : 2016-02-11 00:10:00
I/LIA_Informant_Tips_LogTracer( 3687): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 171, new day : true...... Request
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : SmartTips Total Working Day Count = 171
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 3687): DateInfo : Last Date Check Time = 2016-02-10 00:10:53
D/LIA_Informant_Tips_UserGuideXMLParser( 3687): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
I/LIA_Informant_Tips_UserGuideDBManager( 3687): checkUploadAllCard() : false - Some features(4) reamain to be uploaded, for example .. ugc_camera_dual
D/LIA_Informant_Tips_UserGuideCardFlowHandler( 3687): getUserGuideDuration() : duration=7, uploaded=false, allCard=false
I/LIA_Informant_Tips_UserGuideCardFlowHandler( 3687): checkUserGuideCountDay() :count is smaller than duration, count = 7
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=230284994 [*alarm*], flags=0x0
D/AndroidRuntime( 8449): 
D/AndroidRuntime( 8449): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8449): CheckJNI is OFF
D/AndroidRuntime( 8449): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 6637:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1039): Skipping PackageSetting{195f3a11 com.example.hello/10319} due to missing metadata
I/WindowState( 1039): WIN DEATH: Window{3283dfef u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1039): Client connection lost with reason: 4
D/InputDispatcher( 1039): Window went away: Window{3283dfef u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{247df317 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1039):   Force finishing activity ActivityRecord{247df317 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Duplicate finish request for ActivityRecord{247df317 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1039): Spurious death for ProcessRecord{6d497ad 6637:com.test.thalitest/u0a311}, curProc for 6637: null
I/[LGHome]EVENT( 2089): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{3c50a209 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2089): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{1ba9ec0e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2089): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1924): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3687): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]LGActivityUtil( 2089): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LIA_Service_RemotePackageHandler( 2036): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3687): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1837): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4520): Explicit concurrent mark sweep GC freed 17099(952KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 414us total 87.459ms
W/System.err( 4457): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4457): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4457): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4457): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4457): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4457): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4457): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4457): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4457): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/PostponalbeReceiver( 6248): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1039): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8495 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2089): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1470): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2089): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1924): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3687): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3687): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2089): , create_time: 1430558575574
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2089): , create_time: 1430558575600
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2089): , create_time: 1454599633839
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/WallpaperManager( 2089): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1470): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1470): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@6f4aee0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1889): split_name #11 / not available #0
D/SplitUIService( 1889): removed split : 
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1889): split_name #11 / not available #0
I/SplitUIService( 1889): split app #11
D/AppUp4:PreloadHelper( 8090): added Exclude : com.test.thalitest
I/LockScreenSettings( 8495): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager( 1039): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8518 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2089): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     ( 1039): Explicit concurrent mark sweep GC freed 28714(1741KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 44MB/66MB, paused 2.366ms total 243.468ms
I/art     ( 1039): WaitForGcToComplete blocked for 210.311ms for cause Explicit
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
D/KeyguardModel( 1470): handleShortcutListChanged...
D/KeyguardModel( 1470): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1470): createShortcutInfo...
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/KeyguardModel( 1470): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 8518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8518): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8518): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8518): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/KeyguardModel( 1470): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
W/ResourcesManager( 8518): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1470): createShortcutInfo...
W/ResourceType( 1470): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1470): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1470): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1470): createShortcutInfo...
I/ActivityManager( 1039): Killing 7926:com.lge.lifetracker/u0a37 (adj 15): empty #17
D/administrator( 1039): Handling package changes for user 0
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  333): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3151): Thermal-Lib-Client: Client request sent
I/[Concierge]WidgetView( 2089): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1470): handleShortcutListChanged...
W/libprocessgroup( 1039): failed to open /acct/uid_10037/pid_7926/cgroup.procs: No such file or directory
D/[Concierge]Service( 2644): onStartCommand(). Type : 8
D/[Concierge]Service( 2644): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1470): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{2b73c410 u0 com.lge.launcher2/.Launcher t3} time:1321625
I/[SystemUI]NavigationThemeResource( 1470): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1470):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1470): , Keyguard show=false, IME shown=false, Panel expanded=false
D/[Concierge]Service( 2644): Update widget ID : 11
D/[Concierge]WidgetView( 2089): change position of spinner
I/[Concierge]WidgetView( 2089): initWebView(). Time : 1455059454588
D/[Concierge]Service( 2644): onStartCommand(). Type : 0
I/SystemConfig( 8518): BUILD Country: EU
I/SystemConfig( 8518): BUILD Operator: OPEN
W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2089): Return exist ConciergeWebView. Reuse : 994063462
D/[Concierge]WidgetView( 2089): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]ExtViewHost( 2089): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@456d229
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1039): Explicit concurrent mark sweep GC freed 6672(347KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.563ms total 175.700ms
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2089): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2089): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2089): Widget kill message received. Destory myself. My : 1455058161215, New one : 1455059454588
D/[Concierge]WidgetView( 2089): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2089): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1039): Killing 7980:com.lge.settings.easy/1000 (adj 15): empty #17
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2089): Timeline: Activity_idle id: android.os.BinderProxy@384592d time:1321728
D/AndroidRuntime( 8449): Shutting down VM
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7980/cgroup.procs: No such file or directory
I/PackageChangeReceiver( 8113): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/SystemConfig( 8518): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8518): existFile = false
I/SystemConfig( 8518): canReadFile = false
I/SystemConfig( 8518): systemFeature RCS result false
D/SystemConfig( 8518): refreshRcsSupport() :false
D/VoicemailCleanupService( 2187): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1039): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8542 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager( 8542): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8542): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8542): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8542): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 8542): Total System Memory = 2995761152
I/chromium( 2089): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/SystemHelper( 8542): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1039): Killing 8007:com.android.bluetooth/1002 (adj 15): empty #17
D/LGBluetoothUserBindClient( 7882): [BTUI] onServiceDisconnected
I/GBoardtInterface( 2089): onReloaded()
I/GBoardWebViewClient( 2089): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2036): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2036): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1039): failed to open /acct/uid_1002/pid_8007/cgroup.procs: No such file or directory
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
D/LIA_Service_LIAService( 2036): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3687): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6248): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3687): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8565 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3687): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3687): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3687): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3687): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3687): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3687): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3687): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 8565): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 8565): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8565): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8565): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8565): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8565): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 8565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8565): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8565): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 8565): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8565): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8565): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 8565): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 8565): Unable to open database for writing.
E/LifetrackerProvider2( 8565): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 8565): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 8565): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 8565): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 8565): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 8565): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 8565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 8565): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 8565): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 8565): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 8565): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 8565): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 8565): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/ActivityThread( 8565): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 8565): No ProfileInfo entries
I/LG Account v2.2( 8565): isEnabled: false
I/Feature ( 8565): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 8565): [Lifetracker]Country: EU
I/Feature ( 8565): [Lifetracker]Operator: OPEN
I/Feature ( 8565): [Lifetracker]Ranking support: false
I/Feature ( 8565): [Lifetracker]Comfort support: false
I/Feature ( 8565): [Lifetracker]Accessory: true
I/Feature ( 8565): [Lifetracker]Health device: true
I/Feature ( 8565): [Lifetracker]Extra Pedometer: false
I/Feature ( 8565): [Lifetracker]Blood glucose device: false
I/Feature ( 8565): [Lifetracker]Device Number: 3
D/CoreEventReceiver( 8565): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7882): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7882): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7882): replacing : false
D/HideNavigationAppsReceiver( 7882): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7882): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7882): replacing : false
I/ActivityManager( 1039): Killing 7945:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_7945/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 4520): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/SIM_STK ( 1039): Menu title from STK is T-Mobile

```
