#### Test 58380500fccea7e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2648): mDelayedStopHandler : unbind
,I/MusicBrowser( 2248): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2248): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2248): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2248): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2248): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2248): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1067):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@ee3d00bcom.lge.music.MediaPlaybackService$5@33e51ee8
D/MusicBrowser( 2248): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@31bf9991
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2248): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2248): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2248): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2248): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2248): reset
V/MediaPlayer[Native]( 2248): setListener
V/MediaPlayer[Native]( 2248): disconnect
V/MediaPlayer[Native]( 2248): destructor
V/AudioFlinger(  321): releasing 13 from 2248 for -1
V/AudioFlinger(  321):  decremented refcount to 0
V/AudioFlinger(  321): purging stale effects
V/MediaPlayer[Native]( 2248): disconnect
D/MusicBrowser( 2248): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2248): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2248): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2248): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2248): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2248): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2248): [SmartShareManagerClient] unregisterListener: 929630465
W/SmartShareClient( 2248): [SmartShareManagerClient] unregisterListener invalid listener: 929630465
I/SmartShareClient( 2248): [SmartShareManagerClient] terminate service: 2248/MediaPlaybackService/828030207
E/HomeCloudIF( 2248): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2248): [SmartShareManagerClient] unbindService context:android.app.Application@103d53a6
V/CloudHub( 2248): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2248): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2248): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2248): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1067): Killing 6204:com.android.defcontainer/u0a4 (adj 15): empty #17
I/CloudHub( 2248): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29932
W/libprocessgroup( 1067): failed to open /acct/uid_10004/pid_6204/cgroup.procs: No such file or directory
D/AndroidRuntime( 6706): 
D/AndroidRuntime( 6706): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6706): CheckJNI is OFF
D/AndroidRuntime( 6706): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1067): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1067): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1067): setTaskToReturnTo : TaskRecord{7162668 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1067): setTaskToReturnTo : TaskRecord{7162668 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1067): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1067): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6734 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6706): Shutting down VM
V/ActivityManager( 1067): Display changed displayId=0
D/DSDPConnection( 1851): Display #0 changed.
I/art     ( 1067): Explicit concurrent mark sweep GC freed 17593(901KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.897ms total 112.464ms
,D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{1d98998f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{2c5d241c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6734): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6734): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6734): Loading: webviewchromium
,I/LibraryLoader( 6734): Time to load native libraries: 3 ms (timestamps 6413-6416)
,I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6734): Binding Chromium to main looper Looper (main, tid 1) {315abcff}
,I/LibraryLoader( 6734): Expected native library version number "",actual native library version number ""
I/chromium( 6734): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6734): Initializing chromium process, renderers=0
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6734): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6734): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6734): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb57f7960, uid 10311
D/BluetoothManagerService( 1067): Message: 20
D/BluetoothManagerService( 1067): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2717cfb2:true
I/Adreno-EGL( 6734): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6734): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6734): Build Date: 12/12/14 금
I/Adreno-EGL( 6734): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6734): Remote Branch: 
I/Adreno-EGL( 6734): Local Patches: 
I/Adreno-EGL( 6734): Reconstruct Branch: 
,W/chromium( 6734): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6734): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6734): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6734): CordovaWebView is running on device made by: LGE
,W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6734): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6734): Render dirty regions requested: true
I/OpenGLRenderer( 6734): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6734): Enabling debug mode 0
D/Atlas   ( 6734): Validating map...
,D/SplitWindow( 1067): check instance of lgWin Window{21d40adc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6734): LgDataFeature() Constructor: none
D/LgDataFeature( 6734): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1067): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1447): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1067): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1067): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1067): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1067): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@226f982d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1067): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1447): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1447):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1447): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1067): Displayed com.test.thalitest/.MainActivity: +562ms (total +777ms)
,I/Timeline( 1067): Timeline: Activity_windows_visible id: ActivityRecord{20923a81 u0 com.test.thalitest/.MainActivity t4} time:106815
I/Timeline( 6734): Timeline: Activity_idle id: android.os.BinderProxy@5a2e3ef time:106819
D/JsMessageQueue( 6734): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6734): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6734): 
,I/chromium( 6734): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6734): 
,D/jxcore_app_log( 6734): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435192064
,I/chromium( 6734): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{1004f8c8 type 2 when 107338 android} when 107338
,I/ActivityManager( 1067): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6786 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6786): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 6786): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6786): Created application version: 3.2.35 (30235)
,I/BooksSync( 6786): Starting books sync
,D/BooksSync( 6786): started syncMyEbooks
E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com succeed
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
W/ApiaryClient( 6786): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,W/jxcore-log( 6734): Initializing JXcore engine
W/jxcore-log( 6734): JXcore engine is ready
,W/Thread-774( 6785): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8383]" dev="sockfs" ino=8383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-774( 6785): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-774( 6785): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9916]" dev="sockfs" ino=9916 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-774( 6785): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-774( 6785): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30531]" dev="sockfs" ino=30531 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6734): Starting JXcore engine
,W/jxcore-log( 6734): Platform android
W/jxcore-log( 6734): 
W/jxcore-log( 6734): Process ARCH arm
W/jxcore-log( 6734): 
,I/jxcore-log( 6734): JXcore Cordova bridge is ready!
I/jxcore-log( 6734): 
W/jxcore-log( 6734): JXcore engine is started
,I/jxcore-log( 6734): Toggling radios to true
I/jxcore-log( 6734): 
,D/BluetoothAdapter( 6734): enable(): BT is already enabled..!
,D/WifiService( 1067): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1067): setWifiEnabled: true pid=6734, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1067): setWifiEnabled: true pid=6734, uid=10311
E/WifiService( 1067): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1067): disconnect pid=6734, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1067):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1067):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1067): [109,399,232 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1067): doBoolean: DISCONNECT
,D/WifiServiceImplEx( 1067): reconnect pid=6734, uid=10311, packageName=com.test.thalitest,
I/jxcore-log( 6734): Radios toggled
I/jxcore-log( 6734): ,
I/jxcore-log( 6734): My device name is: LGE-LG-D855
I/jxcore-log( 6734): 
,I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1,
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1067): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1,
E/WifiMonitor( 1067): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1067): DISCONNECT: returned true
E/WifiStateMachine( 1067): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1067): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1067): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1067): InitialState.processMessage what=4
D/WifiNative-wlan0( 1067): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1067): doBoolean: SAVE_CONFIG
D/Tethering( 1067): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1067): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1067): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 1
D/WifiNative-wlan0( 1067): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1067): RunningState{ when=-15ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2111): Read error: ssl=0xaa6d9400: I/O error during system call, Connection timed out
,V/NativeCrypto( 2111): SSL shutdown failed: ssl=0xaa6d9400: I/O error during system call, Broken pipe
D/ConnectivityService( 1067): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/DSQN    ( 1067): Dns fail occured do internet check.
D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/DSQN    ( 1067): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1067): try Internet connection check
I/ActivityManager( 1067): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6851 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1067): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1067):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1067): [109,545,014 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1067): doBoolean: RECONNECT
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1067): RECONNECT: returned true
E/WifiStateMachine( 1067):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109547
E/WifiStateMachine( 1067):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109547
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 1
D/WifiNative-wlan0( 1067): SET ps 1: returned true
D/WifiHS20( 1067): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
,V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1067): hidePasspointNotification off =false
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/ConnectivityService( 1067): Default network via Wi-Fi disconnect. stop DSQN
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DSQN    ( 1067): disableDataServiceNotify
D/DSQN    ( 1067): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1067): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1067): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1067): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1067): InternetcheckProgress is not set don't send DS quality intent
D/WifiHS20( 1067): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=109578  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=109580  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1067):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1067):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1067):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1067): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1067):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1067): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109586  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/Nat464Xlat( 1067): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1067): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1067): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524292
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1067): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20( 1067): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1067): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1067): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1067): Removing idletimer
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=109591  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1067): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1067): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1067):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1067): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1067): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1067): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1067): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1067): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1067): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1067): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1067): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1067): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1067): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1067): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateSCANNING
D/TelephonyNetworkFactory-1( 1851): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1851):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/ApiaryClient( 6786): errCount = 2: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.ConnectException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
W/ResourcesManager( 6851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6851): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6851): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6851): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
E/BooksSync( 6786): Soft error: 
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:87)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:158)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.ConnectException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapException(HttpHelper.java:159)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:237)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	... 7 more
E/BooksSync( 6786): Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.209.42 (port 443) after 20000ms: connect failed: ENETUNREACH (Network is unreachable)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/BooksSync( 6786): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/BooksSync( 6786): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
E/BooksSync( 6786): 	at java.net.Socket.connect(Socket.java:882)
E/BooksSync( 6786): 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
E/BooksSync( 6786): 	at com.android.okhttp.Connection.connect(Connection.java:148)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
E/BooksSync( 6786): 	at com.google.api.client.http.javanet.NetHttpRequest.execute(NetHttpRequest.java:77)
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:965)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
E/BooksSync( 6786): Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
E/BooksSync( 6786): 	at libcore.io.Posix.connect(Native Method)
E/BooksSync( 6786): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/BooksSync( 6786): 	... 23 more
W/ResourcesManager( 6851): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/BooksSync( 6786): Sync error
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:87)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:158)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.ConnectException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7509805556394977345&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapException(HttpHelper.java:159)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:237)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	... 7 more
E/BooksSync( 6786): Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.209.42 (port 443) after 20000ms: connect failed: ENETUNREACH (Network is unreachable)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/BooksSync( 6786): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/BooksSync( 6786): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
E/BooksSync( 6786): 	at java.net.Socket.connect(Socket.java:882)
E/BooksSync( 6786): 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
E/BooksSync( 6786): 	at com.android.okhttp.Connection.connect(Connection.java:148)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:276)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:208)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
E/BooksSync( 6786): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
E/BooksSync( 6786): 	at com.google.api.client.http.javanet.NetHttpRequest.execute(NetHttpRequest.java:77)
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:965)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
E/BooksSync( 6786): Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
E/BooksSync( 6786): 	at libcore.io.Posix.connect(Native Method)
E/BooksSync( 6786): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
E/BooksSync( 6786): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/BooksSync( 6786): 	... 23 more
W/ResourcesManager( 6851): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/BooksSync( 6786): Finished books sync
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
I/ActivityManager( 1067): Killing 6403:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 82963, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/DhcpStateMachine( 1067): StoppedState
D/DhcpStateMachine( 1067): StoppedState{ when=-170ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup( 1067): failed to open /acct/uid_10008/pid_6403/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6851): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6851): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6851): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1067): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6879 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1067): Killing 5607:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/art     (  349): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 26.931ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.222ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 20.039ms
,W/libprocessgroup( 1067): failed to open /acct/uid_10011/pid_5607/cgroup.procs: No such file or directory
,I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6851): LgDataFeature() Constructor: none
D/LgDataFeature( 6851): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
I/ActivityManager( 1067): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6900 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1067): Killing 6017:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10019/pid_6017/cgroup.procs: No such file or directory
,W/ResourcesManager( 6900): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6900): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6900): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6900): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6900): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6900): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6900): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6900): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6900): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6900): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6900): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DSQN    ( 1067): EVENT_INTERNET_CHECK_ENABLE received
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6900): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6900): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6900): LgDataFeature() Constructor: none
D/LgDataFeature( 6900): LgDataFeature() Constructor Done, null
,V/SoundPool( 6900): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6900): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6900): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6900): doLoad: loading sample sampleID=1
I/QRemote ( 6900): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,D/UEI.SmartControl( 6581): QS Service created
V/SoundPool( 6900): Start decode
V/MediaPlayer[Native]( 6900): decode(31, 10857164, 17813)
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb5474a40, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
D/QRemote ( 6900): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6900): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6581): Service initServices...
D/UEI.SmartControl( 6581): QS start get config
,V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/LGMDMManager( 6900): Create singleton instance
D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb1a0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb380 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb3d0 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb5474a40, 5, 0, 0)
V/AudioCache(  321): ignored
,V/AudioCache(  321): notify(0xb5474a40, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782496
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782816
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782976
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783056
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb380 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb1a0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb510 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb5474a40, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac602000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac603000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac604000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac605000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac606000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac607000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac608000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac609000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60a000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60b000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60c000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60d000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60e000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac60f000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac610000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac611000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac612000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac613000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac614000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac615000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac616000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac617000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac618000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac619000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61a000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61b000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61c000, 0xb14b3000, 4096)
,V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61d000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61e000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac61f000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac620000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac621000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac622000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac623000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac624000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac625000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac626000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac627000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac628000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac629000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62a000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62b000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62c000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62d000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62e000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac62f000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac630000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac631000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac632000, 0xb14b3000, 4096)
V/AudioCache(  321): write(0xb14b3000, 4096)
V/AudioCache(  321): memcpy(0xac633000, 0xb14b3000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb14b3000, 280)
V/AudioCache(  321): memcpy(0xac634000, 0xb14b3000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb5474a40, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb5474a40, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): Pause Playback at 1068125
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb5474a40, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb510 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb1a0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb2e0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb380 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 6900): close(31)
V/SoundPool( 6900): pointer = 0x9fe2f000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6900): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1230
I/UEI.SmartControl( 6581): Supports setup maps: true
D/UEI.SmartControl( 6581): QS start statue = true Error code = 0
I/UEI.SmartControl( 6581): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6581): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6581): ### init IR Blaster...
,D/serial_port( 6581): Configuring serial port
E/UEI.SmartControl( 6581): UEIBLaster setting for 616
I/UEI.SmartControl( 6581): Setting serial record hearder size = 2
I/UEI.SmartControl( 6581): configuring settings for MAXQ616
I/UEI.SmartControl( 6581): Get version...
D/UEI.SmartControl( 6581): serial port data available: 21
,D/UEI.SmartControl( 6581): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6581): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6581): QS saving settings...
D/UEI.SmartControl( 6581): IR Blaster version: 25672567
D/UEI.SmartControl( 6581): serial port data available: 4
,W/ContextImpl( 6581): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6581): Device manager: loading config....
D/UEI.SmartControl( 6581): ----------- loading internal config...
,E/UEI.SmartControl( 6581): Services init done
D/UEI.SmartControl( 6581): QS Service init finished
D/UEI.SmartControl( 6581): QS Service version name: 2.1.91
D/UEI.SmartControl( 6581): QS Service version code: 201091
D/UEI.SmartControl( 6581): Service requested: Control
,E/UEI.SmartControl( 6581): Loading SETTINGS...
D/UEI.SmartControl( 6581): Request IControl service: devices are loaded...
I/QRemote ( 6900): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6581): ------ IControl API: 11
D/UEI.SmartControl( 6581): File observer start...
E/UEI.SmartControl( 6581): IR Port is disabled: false
D/UEI.SmartControl( 6581): Starting file observer...
I/UEI.SmartControl( 6581): Registering callback...
I/UEI.SmartControl( 6581): ------ IControl API: 19
I/UEI.SmartControl( 6581): Registering Services Ready callback...
,D/UEI.SmartControl( 6581): Internal service binding...
D/UEI.SmartControl( 6581): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6581): Notify AllClients services are ready: 0
,I/QRemote ( 6900): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 6900): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6900): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6900): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6900): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6581): ------ IControl API: 8
D/QRemote ( 6900): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6900): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6900): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6900): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/UEI.SmartControl( 6581): -----service ready thread exits
D/QRemote ( 6900): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6900): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 6900): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6900): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6900): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6900): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6900): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454717665238]
D/QRemote ( 6900): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1067): Killing 6443:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 6900): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1067): failed to open /acct/uid_10023/pid_6443/cgroup.procs: No such file or directory
,V/QRemote ( 6900): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6900): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 6900): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 6900): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6900): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2732): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1067): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1067): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1067): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine( 1067):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:3622 bcn=0
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1067):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:3622 bcn=0
E/WifiStateMachine( 1067):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:3622 bcn=0
E/WifiStateMachine( 1067):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:3622 bcn=0
D/WifiNative-wlan0( 1067): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=111591  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=111604  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
,D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2732): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering( 1067): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1067): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=49 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=111824  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=111825  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1067):  DisconnectedState CMD_ASSOCIATED_BSSID 49 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111825
E/WifiStateMachine( 1067):  ConnectModeState CMD_ASSOCIATED_BSSID 49 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111825
,D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1067):  DriverStartedState CMD_ASSOCIATED_BSSID 49 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111831
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_ASSOCIATED_BSSID 49 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111831
E/WifiStateMachine( 1067):  DefaultState CMD_ASSOCIATED_BSSID 49 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111831
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=111832  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/wpa_supplicant( 2732): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1067): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=52 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1067): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=111842  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiMonitor( 1067): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1067):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=111844  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=111845  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1067):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111847
E/WifiStateMachine( 1067):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111847
D/WifiNative-wlan0( 1067): doString: [STATUS]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1067):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1067): setVHTCapabilityType  : false
D/UsbSettingsControl( 6851): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6851): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6851): [AUTORUN] setTetherStatus() : status=false
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/WifiServerServiceExt( 1067): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1067): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1067): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1067): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1067): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1067): Got NetworkAgent Messenger
D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1067): NetworkAgent connected
D/WifiNative-wlan0( 1067): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1067): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1067): SAVE_CONFIG: returned true
E/WifiConfigStore( 1067): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1067): doBoolean: SET_NETWORK 0 bssid any
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/WifiNative-wlan0( 1067): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1067): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1067): SAVE_CONFIG: returned true
D/CommandListener(  316): Setting iface cfg
E/WifiStateMachine( 1067): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1067): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1067): WaitBeforeStartState
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1067):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=111890  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1067):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=111891  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=111891  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1067):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=111895  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1067):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=111897  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=111898  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1067):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1067):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1067):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1067): doBoolean: DRIVER SETSUSPENDMODE 0
D/ConnectivityService( 1067): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/WifiNative-wlan0( 1067): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 0
D/WifiNative-wlan0( 1067): SET ps 0: returned true
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1067): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1067): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1067): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35cb331c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35cb331c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1067): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1067): DHCP Start wake lock is acquired.
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1067): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1067):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1067):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1067): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1067): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 1
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/WifiNative-wlan0( 1067): SET ps 1: returned true
E/WifiStateMachine( 1067):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1067): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1067): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1067):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1067):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1067): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1067): ignoring duplicate network state non-change
,D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1067): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 1
,D/WifiHS20( 1067): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1067): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1067): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 0
E/ConnectivityService( 1067): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1067): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1067): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  316): netlink response contains error (File exists)
D/ConnectivityService( 1067): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1067): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1067): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1067): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1067): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1067): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1067): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1067):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1067):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1067): currentScore = 0, newScore = 20
D/ConnectivityService( 1067):    accepting network in place of null
D/ConnectivityService( 1067): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1067): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1067):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1851): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1851):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1067): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1067): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1067): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1067): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1067): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1067): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1067): validation of new default Network = false
D/ConnectivityService( 1067): Default network via Wi-Fi connected. start DSQN
D/LocSvc_java( 1067): getAGpsConnectionInfo connType - 4
D/DSQN    ( 1067): enableDataServiceNotify 
D/DSQN    ( 1067): start dsqn bin
D/LocSvc_java( 1067): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1067): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1067): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
W/dsqn    ( 6969): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6969): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
E/DSQN    ( 6969): DSQN ssw
,V/NetworkPolicy( 1067): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6900): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6900): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6900): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6900): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6900): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6900): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1067): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1067): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1067): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6973): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6973): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6973): version 5.5.6 starting
,E/dhcpcd  ( 6973): get_duid: m
D/dhcpcd  ( 6973): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6973): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6973): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6973): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6973): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6973): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6973): wlan0: sending REQUEST (xid 0x8f0f8b38), next in 4.36 seconds
,D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1067): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1067): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 06 Feb 2016 00:14:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454717666506], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454717666485]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Validated
D/ConnectivityService( 1067): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1067):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1067): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1067): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/ConnectivityService( 1067): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1851): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1851):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1067): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1067):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1067): MasterInitialState.processMessage what=3
D/Tethering( 1067): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1067): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1067): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5552): type=WIFI subType= reason=null isConnected=true
,V/AlarmManager( 1067): RTC_WAKEUP set : Alarm{386fdea3 type 0 when 1454717665558 com.android.vending} when 1454717665558
I/GAV2    ( 6786): Thread[GAThread,5,main]: No campaign data found.
I/NetworkMonitor( 5552): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1067): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1067): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1067): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7004 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/SIM_STK ( 1067): Menu title from STK is T-Mobile
I/AppUp4:AppBoxCP( 7004): onCreate
,W/AppUp4:DB( 7004):  [AppBoxDatabaseHelper] construct
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppUp4:DB( 7004):  setFingerPrint start
I/AppUp4:DB( 7004):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7004):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7004):  SDK version = 21
I/AppUp4:DB( 7004):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7004): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7004): onReceive
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgDataFeature( 7004): LgDataFeature() Constructor: none
,D/LgDataFeature( 7004): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7004): Context : android.app.ReceiverRestrictedContext@3f230115
D/AppUp4:CustFacade( 7004): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7004): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7004): begin check event
I/AppUp4:CustModeStarterReceiver( 7004): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7004): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7004): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7004): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7004): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3338): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3338): DownloadService onCreate
D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3338): in removeSpuriousFiles
I/art     ( 2111): Explicit concurrent mark sweep GC freed 21230(1264KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.222ms total 58.099ms
V/DownloadManager( 3338): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4134): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@13c500a9 on behalf of 3338
,D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3338): in trimDatabase
V/DownloadManager( 3338): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@1ccaf62e on behalf of 3338
I/ActivityManager( 1067): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7029 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3338): DownloadService onStartCommand
V/DownloadManager( 3338): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 4134): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4134): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@3c3fe65 on behalf of 3338
D/LGDMClient( 4134): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3338): processing inserted download 1
V/DownloadManager( 3338): processing inserted download 4
,V/DownloadManager( 3338): processing inserted download 7
V/DownloadManager( 3338): processing inserted download 8
V/DownloadManager( 3338): processing inserted download 9
V/DownloadManager( 3338): processing inserted download 10
V/DownloadManager( 3338): processing inserted download 16
V/DownloadManager( 3338): processing inserted download 17
V/DownloadManager( 3338): processing inserted download 18
V/DownloadManager( 3338): processing inserted download 21
V/DownloadManager( 3338): processing inserted download 22
V/DownloadManager( 3338): DownloadService onDestroy
,V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2111): innerSync failed
D/ContactsSyncAdapter( 2111): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2111): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2111): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2111): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2111): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2111): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2111): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2111): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2111): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2111): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2111): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
W/ResourcesManager( 7029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/ResourcesManager( 7029): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 110084, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1067): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 145009, reason: 10019
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/LGEmail ( 7029): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 81443(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.485ms total 110.888ms
D/LGEmail ( 7029): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6085): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6085): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6085): [1] 5.onFinished: Scheduling replication attempt 2.
,W/ResourceType( 7029): No package identifier when getting value for resource number 0x00000000
I/ActivityManager( 1067): Killing 6043:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/LgDataFeature( 7029): LgDataFeature() Constructor: none
D/LgDataFeature( 7029): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1067):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1067):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1067):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1067): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1067): identical MTU - not setting
D/Nat464Xlat( 1067): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1067): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524295
W/libprocessgroup( 1067): failed to open /acct/uid_10027/pid_6043/cgroup.procs: No such file or directory
,D/eas_req ( 7029): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 6973): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6973): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6973): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6973): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6973): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6973): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6973): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6973): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6973): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1067): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7059 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7029): JNI_OnLoad()
I/HubEmail( 7029): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7029): registerNatives()
I/HubEmail( 7029): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7029): registerNativeMethods()
I/HubEmail( 7029): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7029): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1067): Killing 6477:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10061/pid_6477/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1067): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1067): CheckDhcpDirectory [Lease File Count] : 3
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/LgDhcpStateMachineHelper( 1067): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1067): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1067): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1067): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1067): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1067): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1067): RunningState
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3275): networkInfo.isConnected() = false
,I/ActivityManager( 1067): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7097 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1067): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7117 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1067): Killing 6519:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10080/pid_6519/cgroup.procs: No such file or directory
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1067): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7134 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1067): Killing 6606:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1067): failed to open /acct/uid_1000/pid_6606/cgroup.procs: No such file or directory
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{140fcacf type 2 when 114195 com.google.android.gms} when 114195
I/art     ( 7134): Almond Protected OAT
,D/WeatherApplication( 7134): removeAccount
,D/WeatherApplication( 7134): Account.length = 0
E/WeatherApplication( 7134): OPERATOR:OPEN
D/WeatherAncestor( 7134): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:28
D/Weather.Utils( 7134): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7134): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7134): 2 : This is isUpdating : false
,D/WeatherAncestor( 7134): connectivity changed - connection : true
D/WeatherService( 7134): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7134): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7134): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7134): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7134): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7134): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:28
,I/ActivityManager( 1067): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7153 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1067): Killing 6559:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10097/pid_6559/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1067):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1067):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1067):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1067):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1067):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7153): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7153): Loading: webviewchromium
,I/LibraryLoader( 7153): Time to load native libraries: 3 ms (timestamps 4850-4853)
I/LibraryLoader( 7153): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7153): Binding Chromium to main looper Looper (main, tid 1) {1c614194}
I/LibraryLoader( 7153): Expected native library version number "",actual native library version number ""
I/chromium( 7153): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7153): Initializing chromium process, renderers=0
W/art     ( 7153): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  321): registerClient() client 0xb57f7860, uid 10093
,W/AudioManagerAndroid( 7153): Requires BLUETOOTH permission
W/chromium( 7153): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7153): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7153): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7153): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7153): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7153): Build Date: 12/12/14 금
I/Adreno-EGL( 7153): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7153): Remote Branch: 
I/Adreno-EGL( 7153): Local Patches: 
I/Adreno-EGL( 7153): Reconstruct Branch: 
,I/NSApplication( 7153): Starting up...
V/WifiInternetCheck( 1067): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6734): 
,I/ActivityManager( 1067): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7208 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1067): Killing 5944:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1067): failed to open /acct/uid_10005/pid_5944/cgroup.procs: No such file or directory
,D/Tethering( 1067): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5552): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1067): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1067): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 7208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] request level :IDLE....
W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/AppUp4:CustModeStarterReceiver( 7004): onReceive
,D/AppUp4:CustFacade( 7004): Context : android.app.ReceiverRestrictedContext@3f230115
D/AppUp4:CustFacade( 7004): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7004): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7004): begin check event
I/AppUp4:CustModeStarterReceiver( 7004): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3338): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3338): DownloadService onCreate
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3338): in removeSpuriousFiles
,V/DownloadManager( 3338): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@c322feb on behalf of 3338
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3338): DownloadService onStartCommand
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/DownloadManager( 3338): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3338): in trimDatabase
V/DownloadManager( 3338): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@76f9d06 on behalf of 3338
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@2501dfc7 on behalf of 3338
,V/DownloadManager( 3338): processing inserted download 1
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4134): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3275): networkInfo.isConnected() = false
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3338): processing inserted download 4
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3338): processing inserted download 7
D/WeatherAncestor( 7134): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:29
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Kids    ( 2287): [AccountUtils] Account not ready
W/Kids    ( 2287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2287): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2287): 	at java.lang.Thread.run(Thread.java:818)
I/CloudHub( 2248): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19922
E/LGDMClient( 4134): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4134): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4134): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/Weather.Utils( 7134): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7134): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7134): 2 : This is isUpdating : false
D/WeatherAncestor( 7134): connectivity changed - connection : true
V/DownloadManager( 3338): processing inserted download 8
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/WeatherService( 7134): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21282a1b
,D/ForecastDataCache( 7134): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7134): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7134): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7134): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7134): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:29
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
V/DownloadManager( 3338): processing inserted download 9
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
V/DownloadManager( 3338): processing inserted download 10
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6734): 
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
V/DownloadManager( 3338): processing inserted download 16
V/DownloadManager( 3338): processing inserted download 17
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
V/DownloadManager( 3338): processing inserted download 18
V/DownloadManager( 3338): processing inserted download 21
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
V/DownloadManager( 3338): processing inserted download 22
,I/GLSActivity( 2111): [ac] getting account id
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3338): DownloadService onDestroy
I/GLSUser ( 2111): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7004): [onReceive] request level :IDLE....
I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/AppUp4:CustModeStarterReceiver( 7004): onReceive
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6734): 
D/AppUp4:CustFacade( 7004): Context : android.app.ReceiverRestrictedContext@3f230115
D/AppUp4:CustFacade( 7004): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7004): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7004): begin check event
I/AppUp4:CustModeStarterReceiver( 7004): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4380): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/DownloadManager( 3338): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3338): DownloadService onCreate
W/Kids    ( 2287): [AccountUtils] Account not ready
W/Kids    ( 2287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2287): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2287): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/libc-netbsd(  316): res_queryN name = mtalk.google.com succeed
I/DownloadManager( 3338): in removeSpuriousFiles
V/DownloadManager( 3338): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@c2c951d on behalf of 3338
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3338): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
I/DownloadManager( 3338): in trimDatabase
V/DownloadManager( 3338): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@35d88392 on behalf of 3338
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
V/DownloadManager( 3338): DownloadService onStartCommand
I/LGDMClient( 4134): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateCha,nged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3275): networkInfo.isConnected() = true
D/PhoneState( 3275): setPdpRejectCasuse : false
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7134): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:29
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3338): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3338): created cursor android.database.sqlite.SQLiteCursor@38026619 on behalf of 3338
V/DownloadManager( 3338): processing inserted download 1
E/LGDMClient( 4134): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/Weather.Utils( 7134): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7134): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7134): 2 : This is isUpdating : false
D/WeatherAncestor( 7134): connectivity changed - connection : true
D/WeatherService( 7134): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21282a1b
V/DownloadManager( 3338): processing inserted download 4
D/LGDMClient( 4134): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4134): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/ForecastDataCache( 7134): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7134): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7134): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7134): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7134): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:14:29
V/DownloadManager( 3338): processing inserted download 7
V/DownloadManager( 3338): processing inserted download 8
V/DownloadManager( 3338): processing inserted download 9
V/DownloadManager( 3338): processing inserted download 10
V/DownloadManager( 3338): processing inserted download 16
V/DownloadManager( 3338): processing inserted download 17
V/DownloadManager( 3338): processing inserted download 18
,V/DownloadManager( 3338): processing inserted download 21
,V/DownloadManager( 3338): processing inserted download 22
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6734): 
V/DownloadManager( 3338): DownloadService onDestroy
I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6734): 
V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
,D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7059): There are no updated forms. The schedule will be deleted.
V/FormManager( 7059): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1067): Killing 6640:com.lge.bnr/1000 (adj 15): empty #17
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 33310(1523KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 2.459ms total 86.403ms
,D/GCM     ( 2111): Connected
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6734): 
W/libprocessgroup( 1067): failed to open /acct/uid_1000/pid_6640/cgroup.procs: No such file or directory
,D/GCM     ( 2111): Message class com.google.f.a.a.p
,V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2287): [AccountUtils] Account not ready
W/Kids    ( 2287): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2287): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2287): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2287): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2287): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2287): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6581): Internal timer expired: 4
,D/UEI.SmartControl( 6581): unbind internal service
,D/serial_port( 6581): close(fd = 24)
,I/UEI.SmartControl( 6581): Serial port is closed.
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = www.google.com succeed
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1067): isHttpConnectionAvailable - We got a valid response : 204
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 117592437668; DSPS: 3994468; Offset : -4323099373
,I/GAV4    ( 7153): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1067): Killing 5985:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10014/pid_5985/cgroup.procs: No such file or directory
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
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17a16b5 added. We now have 1 listener(s)
I/jxcore-log( 6734): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6734): 
I/jxcore-log( 6734): TAP version 13
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 1 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 2 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 3 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 4 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 5 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 6 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 7 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 8 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 9 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 10 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons no beacons returns null
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 11 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 12 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 13 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 14 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 15 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 16 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 17 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 18 (unnamed assert)
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/CloudHub( 2248): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2248): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 137596519014; DSPS: 4649961; Offset : -4323077360
,V/AlarmManager( 1067): RTC_WAKEUP set : Alarm{c77a977 type 0 when 1454717687117 com.android.vending} when 1454717687117
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{d9f99e4 type 2 when 137415 android} when 137415
V/QRemote ( 6900): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6900): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1230
V/SIM_STK ( 1067): Menu title from STK is T-Mobile
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6085): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6085): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6085): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,I/ActivityManager( 1067): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7334 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7334): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7334): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@27094c1e
I/ActivityManager( 1067): Killing 2248:com.lge.music/u0a34 (adj 15): empty #17
D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
V/AudioFlinger(  321): 2248 died, releasing its sessions
V/AudioFlinger(  321):  pid 1851 @ 0
V/AudioFlinger(  321):  pid 3275 @ 1
V/AudioFlinger(  321):  pid 3275 @ 2
,W/libprocessgroup( 1067): failed to open /acct/uid_10034/pid_2248/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1067):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1067):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1067):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1067):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1067):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1067):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 157600939267; DSPS: 5305466; Offset : -4323081948
,V/AlarmManager( 1067): RTC_WAKEUP set : Alarm{66fde67 type 0 when 1454717714468 com.android.vending} when 1454717714468
,V/SIM_STK ( 1067): Menu title from STK is T-Mobile
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6085): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6085): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6085): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{11a5cf1 type 2 when 171025 android} when 171025
,I/BooksSync( 6786): Starting books sync
,D/BooksSync( 6786): started syncMyEbooks
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3671246780376064814&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
,W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3671246780376064814&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
W/ApiaryClient( 6786): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3671246780376064814&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,E/BooksSync( 6786): Soft error: 
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3671246780376064814&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
,E/BooksSync( 6786): Sync error
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3671246780376064814&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
I/BooksSync( 6786): Finished books sync
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 171025, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 177602690093; DSPS: 5960883; Offset : -4323070598
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/WifiController( 1067): battery changed pluggedType: 2
,D/HeadsetStateMachine( 3709): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
,I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
,D/LEDHandler( 1960): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1067): RTC_WAKEUP set : Alarm{3f4ed10 type 0 when 1454717736447 com.android.vending} when 1454717736447
,V/SIM_STK ( 1067): Menu title from STK is T-Mobile
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6085): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6085): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6085): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 197604777273; DSPS: 6616312; Offset : -4323089079
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{1053b972 type 2 when 201072 android} when 201072
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 217606837055; DSPS: 7271739; Offset : -4323074314
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{1652e1c3 type 2 when 208957 android} when 208957
V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{21e5ba40 type 2 when 185634 com.google.android.gms} when 185634
V/AlarmManager( 1067): RTC_WAKEUP set : Alarm{99ffabe type 0 when 1454717769593 com.android.vending} when 1454717769593
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1067): Menu title from STK is T-Mobile
,I/VacuumService( 2111): Vacuum at: now=1454717783815 tag=VacuumService
,I/GoogleURLConnFactory( 2111): Using platform SSLCertificateSocketFactory
,W/Uploader( 2111): No account for auth token provided
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6085): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6085): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6085): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 2111): No account for auth token provided
,W/Uploader( 2111): No account for auth token provided
,W/Uploader( 2111): No account for auth token provided
,W/Uploader( 2111):  no longer exists, so no auth token.
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{27f51e46 type 2 when 231101 android} when 231101
,I/BooksSync( 6786): Starting books sync
,D/BooksSync( 6786): started syncMyEbooks
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 30563(1319KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.472ms total 159.010ms
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
E/HttpHelper( 6786): null auth token
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8410580575011946633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8410580575011946633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2111): Explicit concurrent mark sweep GC freed 53337(3MB) AllocSpace objects, 22(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.429ms total 80.379ms
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
,D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8410580575011946633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,E/BooksSync( 6786): Soft error: 
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8410580575011946633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
,E/BooksSync( 6786): Sync error
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8410580575011946633&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
I/BooksSync( 6786): Finished books sync
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 206537, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 237608887049; DSPS: 7927166; Offset : -4323068918
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # multiplex can send data
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 19 String should be length:200
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # enqueue and run in order
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 20 firstPromise setTimeout
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 21 firstPromise result
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 22 firstPromise testValue
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 23 secondPromise setTimeout
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 24 secondPromise result
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 25 secondPromise testValue
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 26 thirdPromise in promise
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 27 thirdPromise result
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 28 thirdPromise testValue
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # basic
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 29 sane
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # another
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 30 sane
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 31 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 32 null
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 33 (unnamed assert)
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 34 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 35 should not throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 36 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 37 (unnamed assert)
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 38 should not throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 39 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 40 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 41 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # failed to get mobile documents path
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 42 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 43 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 44 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 45 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #init should register the networkChanged event
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 46 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on null device name
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 47 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 48 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 49 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 50 should throw
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on negative port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 51 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should throw on too large port
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 52 should throw
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 53 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 54 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 55 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 56 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 57 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 58 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 59 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 60 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 61 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 62 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 63 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 64 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 65 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 66 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 67 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 68 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 69 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): ok 70 should be equal
I/jxcore-log( 6734): 
I/jxcore-log( 6734): ok 71 should be equal
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
I/jxcore-log( 6734): # setup
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6734): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e5014a added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811499.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811499.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811499.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811499.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811499.6734","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811499.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@963ff524 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@963ff524 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313439392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313439392e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313439391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313439391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3709): [BTUI] createSocketChannel FD=84 mFd=82
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811499.6734, mode: WIFI
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2732): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1960): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1067): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/LGWifiP2pService( 1067): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/jxcore-log( 6734): ok 72 Should be able to call startBroadcasting without error
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
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313439391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313439391f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): discovery change broadcast false
D/LGWifiP2pService( 1067): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 257612262719; DSPS: 8582637; Offset : -4323080909
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 73 Should be able to call stopBroadcasting without error
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cf9e816 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): o,nDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811605.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811605.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811605.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811605.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811605.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811605.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a46b44fa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a46b44fa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313630352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313630352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313630351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313630351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK,
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
,I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811605.6734, mode: WIFI
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P: Reject scan trigger since one is already pending,
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
I/jxcore-log( 6734): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/LGWifiP2pService( 1067): discovery change broadcast true
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
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
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=59 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
,D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313630351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313630351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
,D/LGWifiP2pService( 1067): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6734): ok 75 Should be able to call stopBroadcasting without error
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
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31a46fa2 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1067): InactiveState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811676.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811676.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811676.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811676.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811676.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811676.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94502a6a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94502a6a target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313637362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313637362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313637361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811676.6734, mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 76 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313637361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/LGWifiP2pService( 1067): discovery change broadcast true
D/LGWifiP2pService( 10,67): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313637361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313637361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1067): remove client information from framework
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned, true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
I/jxcore-log( 6734): ok 77 Should be able to call stopBroadcasting without error
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7de3ee added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811726.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811726.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811726.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811726.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811726.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811726.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a55eebf2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a55eebf2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313732362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313732362e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313732361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313732361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811726.6734, mode: WIFI
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 78 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/LGWifiP2pService( 1067): discovery change broadcast true
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
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 79 Should be able to call stopBroadcasting without error
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6850fa added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313732361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313732361f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1067): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-9ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=63 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1067): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811785.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811785.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811785.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811785.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811785.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811785.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@752c4d28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@752c4d28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313738352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313738352e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313738351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811785.6734, mode: WIFI
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313738351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/LGWifiP2pService( 1067): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=65 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1067): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313738351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313738351f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/jxcore-log( 6734): ok 81 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
,D/LGWifiP2pService( 1067): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5a82c6 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811840.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811840.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811840.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811840.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811840.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811840.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e99c9238 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e99c9238 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313834302e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313834302e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313834301f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313834301f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811840.6734, mode: WIFI
D/LGWifiP2pService( 1067): discovery change broadcast true
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 82 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-FIND-STOPPED 
,D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
,D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED,
I/jxcore-log( 6734): ok 83 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33ec0552 added. We now have 8 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313834301f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313834301f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811893.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811893.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811893.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811893.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811893.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811893.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd5c26a8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd5c26a8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313839332e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313839332e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313839331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313839331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811893.6734, mode: WIFI
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
D/LGWifiP2pService( 1067): discovery change broadcast true
I/jxcore-log( 6734): ok 84 Should be able to call startBroadcasting without error
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
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D,/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=69 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6734): ok 85 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313839331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313839331f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ba1249e added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService( 1067): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-11ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-11ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811942.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811942.6734","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811942.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717811942.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717811942.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717811942.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55be9ef2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@55be9ef2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313934322e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831313934322e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313934321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313934321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717811942.6734, mode: WIFI
,D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 86 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
I/wpa_supplicant( 2732): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1960): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
D/LGWifiP2pService( 1067): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/WifiMonitor( 1067): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=70 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
E/WifiMonitor( 1067): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313934321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831313934321f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
D/LGWifiP2pService( 1067): InactiveState{ when=-3ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thalipr,oject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
,I/jxcore-log( 6734): ok 87 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: 
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cf6ecaa added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812021.6734
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717812021.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812021.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717812021.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717812021.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717812021.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4cd308c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4cd308c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
,D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831323032312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831323032312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true,
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812021.6734, mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6734): ok 88 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
,I/io.jxcore.node.ConnectionHelper( 6734): stop,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323032311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323032311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local service added successfully
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery started successfully
D/LGWifiP2pService( 1067): discovery change broadcast true
D/LGWifiP2pService( 1067): InactiveState{ when=-2ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1067): InactiveState{ when=-4ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-4ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323032311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323032311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1067): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6734): ok 89 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6734): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	,Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): ,	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2f2976 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6734): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812091.6734
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717812091.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): start: OK
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6734): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812091.6734, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6734): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6734): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454717812091.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: {"pi":"58:3F:54:73:64:C0","pn":"1454717812091.6734","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454717812091.6734","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b40ba4fa target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b40ba4fa target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1067): P2pEnabledState add service
D/LGWifiP2pService( 1067): add a new client
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831323039312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343731373831323039312e36373334222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323039311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1067): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323039311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: OK
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454717812091.6734, mode: WIFI
I/wpa_supplicant( 2732): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1960): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiMonitor( 1067): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=74 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1067): P2P_FIND 120: returned true
D/LGWifiP2pService( 1067): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6734): start: OK
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
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2732): P2P-FIND-STOPPED 
D/WfdsMonitor( 1960): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1067): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1067): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
I/jxcore-log( 6734): ok 90 Should be able to call startBroadcasting without error
I/jxcore-log( 6734): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 6734): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): Shutting down...
I/org.thaliproject.p2p.btconn,ectorlib.internal.bluetooth.BluetoothConnector( 6734): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6734): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6734): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: 1 listener(s) left
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6734): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopForRestart
I/io.jxcore.node.ConnectionHelper( 6734): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6734): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6734): stop: Stopping services
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState clear service
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1067): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323039311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6734): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1067): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343731373831323039311f36373334222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1067): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6734): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6734): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1067): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1067): P2P_STOP_FIND: returned true
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6734): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6734): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6734): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6734): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1067): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService( 1067): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6734): Service requests cleared successfully,
I/jxcore-log( 6734): ok 91 Should be able to call stopBroadcasting without error
I/jxcore-log( 6734): 
,I/jxcore-log( 6734): # teardown
I/jxcore-log( 6734): 
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{3455c7d9 type 2 when 261174 android} when 261174
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 277614303128; DSPS: 9238064; Offset : -4323085098
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 297616326870; DSPS: 9893490; Offset : -4323075439
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{1640659e type 2 when 298060 android} when 298060
D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,I/BooksSync( 6786): Starting books sync
,D/BooksSync( 6786): started syncMyEbooks
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5149321771932296970&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5149321771932296970&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5149321771932296970&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,E/BooksSync( 6786): Soft error: 
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5149321771932296970&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
,E/BooksSync( 6786): Sync error
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5149321771932296970&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
I/BooksSync( 6786): Finished books sync
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 298060, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 317618311914; DSPS: 10548915; Offset : -4323073959
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{14bc9d44 type 2 when 328194 android} when 328194
D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 337620951230; DSPS: 11204362; Offset : -4323089516
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 357622746483; DSPS: 11859781; Offset : -4323094878
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6085): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6085): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6085): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6085): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 377624731683; DSPS: 12515206; Offset : -4323093295
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 397626407978; DSPS: 13170621; Offset : -4323095310
,I/art     ( 1067): Explicit concurrent mark sweep GC freed 31203(1661KB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/66MB, paused 3.529ms total 154.954ms
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 417628215470; DSPS: 13826040; Offset : -4323088617
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{4188686 type 2 when 427685 android} when 427685
,I/BooksSync( 6786): Starting books sync
,D/BooksSync( 6786): started syncMyEbooks
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
W/ApiaryClient( 6786): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2097822530712234629&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2097822530712234629&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2111): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2111): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2111): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2111): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2111): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1067): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1067): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1067): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1067): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1067): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2111): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2111): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2111): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2111): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2111): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6786): Authentication error
E/BooksAccountManager( 6786): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6786): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6786): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6786): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6786): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{c2c951d V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6786): Error response from books API: {
W/ApiaryClient( 6786):  "error": {
W/ApiaryClient( 6786):   "errors": [
W/ApiaryClient( 6786):    {
W/ApiaryClient( 6786):     "domain": "global",
W/ApiaryClient( 6786):     "reason": "required",
W/ApiaryClient( 6786):     "message": "Login Required",
W/ApiaryClient( 6786):     "locationType": "header",
W/ApiaryClient( 6786):     "location": "Authorization"
W/ApiaryClient( 6786):    }
W/ApiaryClient( 6786):   ],
W/ApiaryClient( 6786):   "code": 401,
W/ApiaryClient( 6786):   "message": "Login Required"
W/ApiaryClient( 6786):  }
W/ApiaryClient( 6786): }
,W/ApiaryClient( 6786): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2097822530712234629&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6786): Headers:
W/ApiaryClient( 6786): accept-encoding: [gzip]
W/ApiaryClient( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6786): gdata-version: 2
,E/BooksSync( 6786): Soft error: 
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2097822530712234629&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
,E/BooksSync( 6786): Sync error
E/BooksSync( 6786): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6786): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2097822530712234629&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6786): Headers:
E/BooksSync( 6786): accept-encoding: [gzip]
E/BooksSync( 6786): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6786): gdata-version: 2
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6786): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6786): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6786): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6786): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6786): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6786): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6786): {
E/BooksSync( 6786):  "error": {
E/BooksSync( 6786):   "errors": [
E/BooksSync( 6786):    {
E/BooksSync( 6786):     "domain": "global",
E/BooksSync( 6786):     "reason": "required",
E/BooksSync( 6786):     "message": "Login Required",
E/BooksSync( 6786):     "locationType": "header",
E/BooksSync( 6786):     "location": "Authorization"
E/BooksSync( 6786):    }
E/BooksSync( 6786):   ],
E/BooksSync( 6786):   "code": 401,
E/BooksSync( 6786):   "message": "Login Required"
E/BooksSync( 6786):  }
E/BooksSync( 6786): }
E/BooksSync( 6786): 
E/BooksSync( 6786): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6786): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6786): 	... 8 more
I/BooksSync( 6786): Finished books sync
D/SyncManager( 1067): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 427685, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 437630926765; DSPS: 14481489; Offset : -4323093307
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 457633006653; DSPS: 15136917; Offset : -4323088850
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{9649d6c type 2 when 457723 android} when 457723
D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 477635041593; DSPS: 15792344; Offset : -4323098456
,I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=76 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1067): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1067): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1067): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1067): InitialState.processMessage what=4
,E/WifiStateMachine( 1067):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=485321
E/WifiStateMachine( 1067):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=485322
E/WifiStateMachine( 1067):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=485322
E/WifiConfigStore( 1067): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1067): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=77 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1067): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1067): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1067): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6851): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/WifiNative-wlan0( 1067): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1067): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 1
D/WifiNative-wlan0( 1067): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1067): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2111): Read error: ssl=0xaf4d3600: I/O error during system call, Connection timed out
I/jxcore-log( 6734): Toggling radios to false
I/jxcore-log( 6734): 
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=79 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1067): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1067): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 77 0 rt=485429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 77 0 rt=485430  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1067):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1067):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 78 0 rt=485432  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1067):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 78 0 rt=485434  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/BluetoothManagerService( 1067): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1067): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15561f35 mBinding = false
,D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NativeCrypto( 2111): SSL shutdown failed: ssl=0xaf4d3600: I/O error during system call, Broken pipe
D/ConnectivityService( 1067): ignoring duplicate network state non-change
D/ConnectivityService( 1067): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiNetworkAgent( 1067): NetworkAgent: NetworkAgent channel lost
D/WifiHS20( 1067): hidePasspointNotification off =false
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1067): hidePasspointNotification off =false
,W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1067): hidePasspointNotification off =false
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/BluetoothManagerService( 1067): Message: 2
D/LocationManagerService( 1067): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1067): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Ulp_jni ( 1067): JNI:system_update. Event-4
D/BluetoothManagerService( 1067): Sending off request.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothServiceAdapter( 3709): [BTUI] Precleanup
D/BluetoothAdapterState( 3709): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3709): Setting state to 13
I/BluetoothAdapterState( 3709): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3709): onBluetoothDisable()
I/BluetoothAdapterState( 3709): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1067): Message: 60
D/BluetoothManagerService( 1067): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1067): Bluetooth State Change Intent: 12 -> 13
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1067): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1067): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1067): setSupplicantStateSCANNING
D/WifiServiceImplEx( 1067): setWifiEnabled: false pid=6734, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1067): setWifiEnabled: false pid=6734, uid=10311
E/WifiService( 1067): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterProperties( 3709): Scan Mode:20,
D/BluetoothAdapterState( 3709): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothPbapService( 3709): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3709): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/ConnectivityService( 1067): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1067): disableDataServiceNotify
D/DSQN    ( 1067): stop dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
V/BluetoothMapMasInstance( 3709): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3709): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3709): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3709): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3709): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3709): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3709): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3709): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/BtOppRfcommListener( 3709): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3709): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3709): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3709): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/DSQN    ( 1067): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3709): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3709): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3709): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3709): bta_gattc_deregister Deregister Failedm unknown client cif
,D/LocationManagerService( 1067): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1067): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1067): JNI:system_update. Event-4
E/WifiStateMachine( 1067):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1067):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1067):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1067):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1067): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1067): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1067): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/jxcore-log( 6734): Radios toggled
I/jxcore-log( 6734): 
D/CSLegacyTypeTracker( 1067): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1067): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1067): Disconnected - quitting
I/BluetoothMapService( 3709): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3709): STATE_TURNING_OFF
V/BtOppService( 3709): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3709): Handler(): got msg=4
D/BluetoothMapService( 3709): MAP Service closeService in
D/BluetoothMapMasInstance( 3709): MAP Service shutdown
D/LGBluetoothMapAdapter( 3709): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3709): MAP Service closeService out
I/BtOppRfcommListener( 3709): stopping Accept Thread
V/BtOppRfcommListener( 3709): close mBtServerSocket
V/BtOppRfcommListener( 3709): waiting for thread to terminate
,D/UsbSettingsControl( 6851): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6851): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6851): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6851): [AUTORUN] setTetherStatus() : status=false
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BtOppRfcommListener( 3709): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3709): done waiting for thread to terminate
D/ConnectivityService( 1067): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1067): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1067): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1067): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/BtOppService( 3709): onDestroy
D/NetworkManagementService( 1067): Removing idletimer
W/Settings( 1067): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1067): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1851): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1851):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,W/ContextImpl( 6851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/WIFI    ( 1067): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1067):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGWifiP2pService( 1067): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothOppAdapter( 3709): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiMonitor( 1067): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3911ad30
V/BluetoothPbapReceiver( 3709): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3709): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3709): ***********state = 13
V/BluetoothPbapReceiver( 3709): ***********Calling start service!!!! with action = null
V/NetworkPolicy( 1067): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1067): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1067): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1067): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1067): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1067): Sending msg: 4 arg1:0 arg2:1
D/WifiScanningService( 1067): SCAN_AVAILABLE : 1
D/RttService( 1067): SCAN_AVAILABLE : 1
D/LocSvc_java( 1067): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1067): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1067): ignore wifi update if we are not in OPENING or CLOSING
D/LGWifiP2pService( 1067): P2pDisablingState
D/LGWifiP2pService( 1067): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): p2p socket connection lost
D/LGWifiP2pService( 1067): P2pDisabledState
V/NetworkPolicy( 1067): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1067):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1067): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1067): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/RttService( 1067): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1067): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1067): doBoolean: SET ps 1
D/WifiNative-wlan0( 1067): SET ps 1: returned true
,D/CommandListener(  316): Clearing all IP addresses on wlan0
V/BluetoothPbapService( 3709): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3709): state: 13
V/BluetoothPbapService( 3709): Pbap Service closeService in
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 0
D/WifiScanningService( 1067): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1960): WifiP2pState is changed : false
D/WfdsService( 1960): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1960): Set the WFDS Monitor: false
D/WifiNative-p2p0( 1067): doBoolean: TERMINATE
D/WfdsMonitor( 1960): WFDS Monitor is stopped
D/WfdsService( 1960): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1960): Received on exit socket, terminate
D/WifiNative-p2p0( 1067): TERMINATE: returned true
E/CtrlSupplicant( 1960): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1960): Event [CTRL-EVENT-TERMINATING  - connection closed]
E/WifiStateMachine( 1067): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1067): useWiFiOffloading() : false
E/WifiStateMachine( 1067): CONFIG_LGE_WLAN_PATH : true
D/WfdsMonitor( 1960): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1960): DefaultState - msg [9445378] is not handled
V/BluetoothPbapService( 3709): successfully stopped pbap service
V/BluetoothPbapService( 3709): Pbap Service closeService out
V/BluetoothPbapService( 3709): Pbap Service onDestroy
V/BluetoothPbapService( 3709): Pbap Service closeService in
V/BluetoothPbapService( 3709): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3709): [BTUI] cleanup
W/WfdsSession:Controller( 1960): DefaultState - msg [9441355] is not handled
,D/BluetoothManagerService( 1067): Message: 20
D/BluetoothManagerService( 1067): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd679b1:true
,I/ActivityManager( 1067): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7677 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/WifiHS20( 1067): hidePasspointNotification off =false
D/DhcpStateMachine( 1067): StoppedState
D/DhcpStateMachine( 1067): StoppedState{ when=-46ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1067): hidePasspointNotification off =false
W/Settings( 1067): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1067): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1067): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1067): WIFI_STATE_CHANGED_ACTION [0]
E/WifiStateMachine( 1067):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1067):  DefaultState CMD_ON_QUIT 0 0
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 263us total 12.773ms
,D/BluetoothManagerService( 1067): Message: 30
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothManagerService( 1067): Message: 30
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 11.760ms
,D/LocalBluetoothProfileManager( 6851): Adding local MAP profile
D/BluetoothMap( 6851): Create BluetoothMap proxy object
D/BluetoothManagerService( 1067): Message: 30
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothManagerService( 1067): Message: 30
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 230us total 10.695ms
,D/LocalBluetoothProfileManager( 6851): LocalBluetoothProfileManager construction complete
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/LGBluetoothFeatureConfig( 6851):  get() - isFeatureLoaded : false
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothUserBindClient( 6851): [BTUI] initUserBindClient
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 6851): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6851): finishStartingService: stopping service
D/BluetoothInputDevice( 6851): Proxy object connected
D/HidProfile( 6851): Bluetooth service connected
D/BluetoothPan( 6851): BluetoothPAN Proxy object connected
D/PanProfile( 6851): Bluetooth service connected
D/BluetoothMap( 6851): Proxy object connected
D/MapProfile( 6851): Bluetooth service connected
D/BluetoothMap( 6851): getConnectedDevices()
D/BluetoothMap( 6851): Bluetooth is Not enabled
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 6851): [BTUI] onServiceConnected
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ActivityThread( 7677): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7677): No ProfileInfo entries
I/LG Account v2.2( 7677): isEnabled: false
I/Feature ( 7677): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7677): [Lifetracker]Country: EU
I/Feature ( 7677): [Lifetracker]Operator: OPEN
I/Feature ( 7677): [Lifetracker]Ranking support: false
I/Feature ( 7677): [Lifetracker]Comfort support: false
I/Feature ( 7677): [Lifetracker]Accessory: true
I/Feature ( 7677): [Lifetracker]Health device: true
I/Feature ( 7677): [Lifetracker]Extra Pedometer: false
I/Feature ( 7677): [Lifetracker]Blood glucose device: false
I/Feature ( 7677): [Lifetracker]Device Number: 3
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGBluetoothAuthorization( 6851): [BTUI] cancel All Notification
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/BluetoothPermissionRequest( 6851): onReceive
D/LGBluetoothAuthorization( 6851): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 6851): return without doing reset settings.
I/ActivityManager( 1067): Killing 7004:com.lge.appbox.client/u0a11 (adj 15): empty #17
,V/BluetoothOppReceiver( 3709): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup( 1067): failed to open /acct/uid_10011/pid_7004/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3709): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3709): [BTUI] cancel opp active transfer file notification
,V/BluetoothFtpReceiver( 3709): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3709): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3709): Ftp Service onStartCommand
V/BluetoothFtpService( 3709): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3709): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3709): Shutdown
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3709): successfully stopped ftp service
V/BluetoothSapReceiver( 3709): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3709): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3709): SapReceiver onReceive 
V/BluetoothSapReceiver( 3709): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3709):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3709): Calling SAP service start service with action = null
V/BluetoothFtpService( 3709): Ftp Service onDestroy
V/BluetoothFtpService( 3709): Ftp Service closeService
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1067): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7705 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3709): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3709): state: 13
V/BluetoothSapService( 3709): Stopping SAP server process
V/BluetoothSapService( 3709): Sap Service closeSapService in
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothSapService( 3709): Close listen Socket : 
V/BluetoothSapService( 3709): Close rfcomm Socket : 
V/BluetoothSapService( 3709): Close sapd  Socket : 
V/BluetoothSapService( 3709): Sap Service closeSapService out
V/BluetoothSapService( 3709): Sap Service onDestroy
,V/BluetoothSapService( 3709): Sap Service closeSapService in
V/BluetoothSapService( 3709): Close listen Socket : 
V/BluetoothSapService( 3709): Close rfcomm Socket : 
V/BluetoothSapService( 3709): Close sapd  Socket : 
V/BluetoothSapService( 3709): Sap Service closeSapService out
I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
,D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 7705): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/AuthorizationBluetoothService( 2111): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6879): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
,D/QRemote ( 6900): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6900): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6900): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7059): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
V/FormManager( 7059): Network unavailable.
,V/FormManager( 7059): Network unavailable.
I/ActivityManager( 1067): Killing 7029:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10023/pid_7029/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 3709): cleanup
,I/bt_lpm  ( 3709): LPM is already off!!!
I/bt_userial_mct( 3709): exiting userial_read_thread
W/bt-btif ( 3709): ag scb idx 1 not allocated
E/bt-btif ( 3709): BTA AG is already disabled, ignoring ...
D/bt_userial_mct( 3709): Leaving userial_evt_read_thread()
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3709): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3709): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3709): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3709): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3709): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3709): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3709): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3709): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3709): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3709): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3709): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3709): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3709): hw_epilog_process
D/bt_hci_bdroid( 3709): cleanup Finalizing cleanup
D/bt_userial_mct( 3709): userial_close
E/bt_userial_mct( 3709): pthread_join() FAILED result:3
I/bt_vendor( 3709): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 3709): set_power 0
I/bt_vendor( 3709): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3709): bluetooth satus is on
I/bt_vendor( 3709): bt-vendor : resetting BT status
I/bt_vendor( 3709): Starting hciattach daemon
I/bt_vendor( 3709): try to set false
,I/bt_vendor( 3709): Starting hciattach daemon
I/bt_vendor( 3709): try to set false
I/bt_vendor( 3709): cleanup
I/GKI_LINUX( 3709): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3709): GKI_exit_task 0 done
I/GKI_LINUX( 3709): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3709): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3709): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3709): [BTUI] LGBluetoothHfpAdapter cleanup
D/HeadsetStateMachine( 3709): Exit Disconnected: -1
W/LGBluetoothHeadsetServiceJni( 3709): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
D/BluetoothHeadset( 1851): Proxy object disconnected
D/BluetoothHeadset( 1851): Proxy object disconnected
D/BluetoothHeadset( 1851): Proxy object disconnected
D/BluetoothHeadset( 1067): Proxy object disconnected
D/AudioService( 1067): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothAdapterState( 3709): Stopping profile services that were post enabled
D/A2dpService( 3709): Received stop request...Stopping profile...
D/A2dpStateMachine( 3709): Exit Disconnected: -1
,D/LGBluetoothAvrcpQcomAdapter( 3709): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3709): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3709): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
D/BluetoothA2dp( 1067): Proxy object disconnected
D/AudioService( 1067): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3709): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
D/HealthService( 3709): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
,D/PanService( 3709): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
D/BtGatt.DebugUtils( 3709): handleDebugAction() action=null
D/BtGatt.GattService( 3709): Received stop request...Stopping profile...
D/BtGatt.GattService( 3709): stop()
D/BtGatt.AdvertiseManager( 3709): advertise clients cleared
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
D/HeadsetStateMachine( 3709): Unbinding service...
D/HeadsetPhoneState( 3709): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3709): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3709): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3709): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3709): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3709): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3709): [BTUI] LGBluetoothHfpAdapter cleanup
,D/BluetoothMapService( 3709): Received stop request...Stopping profile...
D/BluetoothMapService( 3709): stop()
D/BluetoothMapEmailAppObserver( 3709): deinitObservers()
D/BluetoothMapEmailAppObserver( 3709): removeReceiver()
D/BluetoothAdapterService( 3709): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@377a0c2a
I/BluetoothA2dpServiceJni( 3709): cleanupNative
I/GKI_LINUX( 3709): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3709): GKI_exit_task 2 done
I/GKI_LINUX( 3709): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3709): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3709): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3709): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3709): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3709): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3709): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3709): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3709): Handler(): got msg=4
D/BluetoothMapService( 3709): MAP Service closeService in
D/LGBluetoothMapAdapter( 3709): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3709): MAP Service closeService out
,D/BluetoothAdapterState( 3709): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3709): Setting state to 10
I/BluetoothAdapterState( 3709): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3709): cleanup()
D/BluetoothMapService( 3709): MAP Service closeService in
D/LGBluetoothMapAdapter( 3709): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3709): MAP Service closeService out
D/BluetoothManagerService( 1067): Message: 60
D/BluetoothManagerService( 1067): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1067): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3709): Entering OffState
D/BluetoothPan( 6851): onBluetoothStateChange on: false
D/BluetoothHeadset( 1851): onBluetoothStateChange: up=false
D/BluetoothMap( 6851): onBluetoothStateChange: up=false
D/BluetoothPbap( 6851): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1851): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1851): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 6851): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1067): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1067): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1067): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1067): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1067): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1067): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1067): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15561f35 mBinding = false
D/BluetoothManagerService( 1067): Sending unbind request.
I/GKI_LINUX( 3709): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3709): GKI_exit_task 1 done
I/GKI_LINUX( 3709): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3709): cleanupNative: return from cleanup
I/art     ( 3709): --- WEIRD: removing null entry 246
W/art     ( 3709): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3709): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3709): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1067): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3709): System.exit called, status: 0
I/AndroidRuntime( 3709): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  321): 3709 died, releasing its sessions
V/AudioFlinger(  321):  pid 1851 @ 0
V/AudioFlinger(  321):  pid 3275 @ 1
V/AudioFlinger(  321):  pid 3275 @ 2
,D/LGBluetoothAPIService( 1960): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1960): Message: 101
E/LGBluetoothAPIService( 1960): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1960): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1960): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 6851): [BTUI] onServiceDisconnected
I/ActivityManager( 1067): Process com.android.bluetooth (pid 3709) has died
W/ActivityManager( 1067): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1067): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 11000ms
,D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1960): Message: 2
D/LGBluetoothAPIService( 1960): unbindAndFinish(): null mBinding = false
D/LGBluetoothFeatureConfig( 6851): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 6851): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6851): [BTUI] clear device connection state
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,D/BluetoothAdapter( 1447): 923704292: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1447): 923704292: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 6851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1067): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7756 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 6851): finishStartingService: stopping service
,W/ResourcesManager( 7756): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7756): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7756): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7756): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7756): Loading JNI Library
,D/BluetoothAdapterApp( 7756): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1ce929a3 Instance Count = 1
,D/BluetoothAdapterApp( 7756): onCreate
,D/ProfileConfigQcom( 7756): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 7756): Adding HeadsetService
,D/ProfileConfigQcom( 7756): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7756): Adding A2dpService
D/ProfileConfigQcom( 7756): [BTUI] HidService is supported
D/ProfileConfigQcom( 7756): Adding HidService
,D/ProfileConfigQcom( 7756): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7756): Adding HealthService
D/LGBluetoothFeatureConfig( 7756): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7756): [BTUI] PanService is supported
,D/ProfileConfigQcom( 7756): Adding PanService
D/ProfileConfigQcom( 7756): [BTUI] GattService is supported
D/ProfileConfigQcom( 7756): Adding GattService
D/ProfileConfigQcom( 7756): [BTUI] BluetoothMapService is supported
,D/ProfileConfigQcom( 7756): Adding BluetoothMapService
D/ProfileConfigQcom( 7756): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7756): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 7756): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7756): ***********state = 10
V/LGMDMManagerInternal( 7756): Create singleton instance
,D/LGBluetoothUserBindClient( 6851): [BTUI] onServiceConnected,
D/LGBluetoothAPIServer( 7756): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7756): [BTUI] onBind()
D/LGBluetoothAPIService( 1960): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter,
D/LGBluetoothAPIService( 1960): Message: 100
D/LGBluetoothAPIService( 1960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothPermissionRequest( 6851): onReceive
D/LGBluetoothUtils( 6851): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 6851): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 6851): return without doing reset settings.
D/LGBluetoothOppAdapter( 7756): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 7756): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7756): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7756): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7756): SapReceiver onReceive 
V/BluetoothSapReceiver( 7756): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7756):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7705): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 2111): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2732): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2732): monitor socket send errors count : 1
,I/wpa_supplicant( 2732): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1960-2\x00 that cannot receive messages
,W/wpa_supplicant( 2732): USIM:  scard_deinit function
D/WifiMonitor( 1067): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1067): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=80 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1067):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=487513  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1067):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=487513  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1067): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1067): WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1067): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1067):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 81 0
D/WfdsService( 1960): Supplicant Connection state is changed : false
D/WfdsService( 1960): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1960): Set the WFDS Monitor: false
D/WfdsMonitor( 1960): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1067): stopMonitoring
E/WifiStateMachine( 1067): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1067): useWiFiOffloading() : false
E/WifiStateMachine( 1067): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1815): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1067): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1067): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1067): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/PCSuite ( 6879): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 6879): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6879): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6851): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6851): MCCMNC not supported: null
D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7059): Network unavailable.
,W/FormManager( 7059): Network not available. Please check & try again.
,V/FormManager( 7059): Network unavailable.
,D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1067): MasterInitialState.processMessage what=3
D/ConnectivityService( 1067): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1067): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1067): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5552): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5552): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1067): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1067): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7812 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1067): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1067): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7812): onCreate
W/AppUp4:DB( 7812):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7812):  setFingerPrint start
I/AppUp4:DB( 7812):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7812):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7812):  SDK version = 21
,I/AppUp4:DB( 7812):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7812): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7812): onReceive
,D/LgDataFeature( 7812): LgDataFeature() Constructor: none
D/LgDataFeature( 7812): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7812): Context : android.app.ReceiverRestrictedContext@3f230115
D/AppUp4:CustFacade( 7812): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7812): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7812): begin check event
,I/AppUp4:CustModeStarterReceiver( 7812): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7812): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7812): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7812): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7812): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1067): Killing 7097:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10057/pid_7097/cgroup.procs: No such file or directory
,D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1067): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7856 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7856): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7856): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7856): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7856): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7856): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7856): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7856): LgDataFeature() Constructor: none
D/LgDataFeature( 7856): LgDataFeature() Constructor Done, null
,D/eas_req ( 7856): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3275): networkInfo.isConnected() = false
,I/HubEmail( 7856): JNI_OnLoad()
I/HubEmail( 7856): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7856): registerNatives()
I/HubEmail( 7856): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7856): registerNativeMethods()
I/HubEmail( 7856): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7856): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1067): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7882 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7059): Network not available. Please check & try again.
W/Settings( 7856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7059): Network unavailable.
V/FormManager( 7059): Network unavailable.
I/ActivityManager( 1067): Killing 7117:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10062/pid_7117/cgroup.procs: No such file or directory
,I/ActivityManager( 1067): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7911 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1067): Killing 7134:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/libprocessgroup( 1067): failed to open /acct/uid_10085/pid_7134/cgroup.procs: No such file or directory
,I/ActivityManager( 1067): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7929 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ProcessCpuTracker( 1067): Skipping unknown process pid 7903
,I/ActivityManager( 1067): Killing 7153:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
W/ProcessCpuTracker( 1067): Skipping unknown process pid 7906
W/libprocessgroup( 1067): failed to open /acct/uid_10093/pid_7153/cgroup.procs: No such file or directory
,I/art     ( 7929): Almond Protected OAT
,D/LGWifiP2pService( 1067): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1067): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1067):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1067):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
D/WeatherApplication( 7929): removeAccount
,D/WeatherApplication( 7929): Account.length = 0
E/WeatherApplication( 7929): OPERATOR:OPEN
D/WeatherAncestor( 7929): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:20:44
D/Weather.Utils( 7929): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7929): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7929): 2 : This is isUpdating : false
,D/WeatherAncestor( 7929): connectivity changed - connection : true
D/WeatherService( 7929): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7929): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7929): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7929): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7929): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7929): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:20:44
,I/ActivityManager( 1067): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7950 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1067): Killing 7208:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10097/pid_7208/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7950): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7950): Loading: webviewchromium
,I/LibraryLoader( 7950): Time to load native libraries: 5 ms (timestamps 1251-1256)
I/LibraryLoader( 7950): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7950): Binding Chromium to main looper Looper (main, tid 1) {103d53a6}
I/LibraryLoader( 7950): Expected native library version number "",actual native library version number ""
I/chromium( 7950): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7950): Initializing chromium process, renderers=0
,W/art     ( 7950): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7950): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7950): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7950): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb57f76e0, uid 10093
W/AudioManagerAndroid( 7950): Requires BLUETOOTH permission
I/Adreno-EGL( 7950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7950): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7950): Build Date: 12/12/14 금
I/Adreno-EGL( 7950): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7950): Remote Branch: 
I/Adreno-EGL( 7950): Local Patches: 
I/Adreno-EGL( 7950): Reconstruct Branch: 
,I/NSApplication( 7950): Starting up...
,I/ActivityManager( 1067): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8013 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1067): Killing 7334:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10010/pid_7334/cgroup.procs: No such file or directory
I/art     ( 1067): Explicit concurrent mark sweep GC freed 63482(2MB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.368ms total 169.372ms
,W/ResourcesManager( 8013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2287): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2287): num queued entries: 0
I/iu.UploadsManager( 2287): num updated entries: 0
I/iu.SyncManager( 2287): NEXT; no task
D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6371): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GLSActivity( 2111): [ac] getting account id
,I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7812): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7812): onReceive
D/AppUp4:CustFacade( 7812): Context : android.app.ReceiverRestrictedContext@3f230115
D/AppUp4:CustFacade( 7812): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7812): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7812): begin check event
I/AppUp4:CustModeStarterReceiver( 7812): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/GLSUser ( 2111): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7856): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3275): networkInfo.isConnected() = false
W/Settings( 7856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7929): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:20:46
D/Weather.Utils( 7929): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7929): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7929): 2 : This is isUpdating : false
D/WeatherAncestor( 7929): connectivity changed - connection : true
D/WeatherService( 7929): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@21282a1b
W/FormManager( 7059): Network not available. Please check & try again.
D/ForecastDataCache( 7929): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7929): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7929): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7929): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7929): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:20:46
V/FormManager( 7059): Network unavailable.
,V/FormManager( 7059): Network unavailable.
,D/ChimeraCfgMgr( 2287): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{d81a5d5 type 2 when 494318 com.google.android.gms} when 494318
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1067): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/GAV4    ( 7950): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1067): Killing 6085:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10044/pid_6085/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 497636504762; DSPS: 16447751; Offset : -4323069484
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 517638579546; DSPS: 17103179; Offset : -4323069764
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 537641237820; DSPS: 17758627; Offset : -4323097116
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1067): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 557643147084; DSPS: 18414049; Offset : -4323080072
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 577644996034; DSPS: 19069470; Offset : -4323092668
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 597646827797; DSPS: 19724890; Offset : -4323091960
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 617648888310; DSPS: 20380317; Offset : -4323076176
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 637651075751; DSPS: 21035749; Offset : -4323085975
,D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
,I/ActivityManager( 1067): Killing 6786:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1067): failed to open /acct/uid_10054/pid_6786/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 657653199233; DSPS: 21691178; Offset : -4323068154
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 677655687246; DSPS: 22346620; Offset : -4323082739
,V/AlarmManager( 1067): ELAPSED_WAKEUP set : Alarm{2277d378 type 2 when 682927 android} when 682927
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 697657766144; DSPS: 23002048; Offset : -4323078801
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 717659567439; DSPS: 23657467; Offset : -4323078304
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 737662258265; DSPS: 24312915; Offset : -4323073051
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 757664333726; DSPS: 24968343; Offset : -4323072577
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 777666436166; DSPS: 25623772; Offset : -4323075876
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 797668491418; DSPS: 26279200; Offset : -4323095507
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 817671219224; DSPS: 26934649; Offset : -4323084156
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 837673052185; DSPS: 27590069; Offset : -4323082301
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 857675109677; DSPS: 28245497; Offset : -4323100004
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 877676937534; DSPS: 28900916; Offset : -4323072373
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 897679020391; DSPS: 29556345; Offset : -4323095437
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 917681690540; DSPS: 30211792; Offset : -4323080448
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 937683784959; DSPS: 30867221; Offset : -4323091663
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/WifiController( 1067): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 957685626514; DSPS: 31522641; Offset : -4323081136
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 977687503798; DSPS: 32178063; Offset : -4323095995
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 997689086811; DSPS: 32833474; Offset : -4323069169
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1017691784929; DSPS: 33488923; Offset : -4323087350
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1037693781640; DSPS: 34144348; Offset : -4323074256
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/PowerManagerServiceEx( 1067): acquireWakeLockInternal: lock=818665306, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1067
,I/ActivityManager( 1067): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8140 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8140): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8140): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@27094c1e
,D/PowerManagerServiceEx( 1067): releaseWakeLockInternal: lock=818665306 [*alarm*], flags=0x0
I/ActivityManager( 1067): Killing 6581:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6900): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6900): android.os.DeadObjectException
,W/System.err( 6900): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6900): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6900): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6900): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6900): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6900): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6900): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6900): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6900): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6900): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6900): android.os.DeadObjectException
W/System.err( 6900): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6900): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6900): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6900): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6900): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6900): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6900): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6900): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6900): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6900): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6900): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6900): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6900): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1067): failed to open /acct/uid_1000/pid_6581/cgroup.procs: No such file or directory
W/ActivityManager( 1067): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6900): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6900): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1067): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8175 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6900): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 24.026ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 18.910ms
,D/UEI.SmartControl( 8175): Quickset Services start...
I/UEI.SmartControl( 8175): Manufacture = LGE
D/UEI.SmartControl( 8175): Id = LGNevo
D/UEI.SmartControl( 8175): File observer start...
E/UEI.SmartControl( 8175): IR Port is disabled: false
D/UEI.SmartControl( 8175): Starting file observer...
D/UEI.SmartControl( 8175): Extracting JNI libs...
,D/UEI.SmartControl( 8175): --- this system supports 32-bit or 64-bit only
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 16.735ms
D/UEI.SmartControl( 8175): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8175): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8175): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8175): --- Selecting new region: 6
,I/UEI.SmartControl( 8175): Model = LG-D855
D/UEI.SmartControl( 8175): QS Service created
I/UEI.SmartControl( 8175): Service initServices...
,D/UEI.SmartControl( 8175): QS start get config
,D/UEI.SmartControl( 8175): Loading JNI Libs...
,I/UEI.SmartControl( 8175): Supports setup maps: true
,D/UEI.SmartControl( 8175): QS start statue = true Error code = 0
I/UEI.SmartControl( 8175): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8175): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8175): ### init IR Blaster...
D/serial_port( 8175): Configuring serial port
,E/UEI.SmartControl( 8175): UEIBLaster setting for 616
I/UEI.SmartControl( 8175): Setting serial record hearder size = 2
I/UEI.SmartControl( 8175): configuring settings for MAXQ616
I/UEI.SmartControl( 8175): Get version...
D/UEI.SmartControl( 8175): serial port data available: 21
,D/UEI.SmartControl( 8175): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 8175): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8175): QS saving settings...
D/UEI.SmartControl( 8175): IR Blaster version: 25672567
,D/UEI.SmartControl( 8175): serial port data available: 4
,I/UEI.SmartControl( 8175): Device manager: loading config....
D/UEI.SmartControl( 8175): ----------- loading internal config...
,W/ContextImpl( 8175): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 8175): Services init done
D/UEI.SmartControl( 8175): QS Service init finished
,D/UEI.SmartControl( 8175): QS Service version name: 2.1.91
D/UEI.SmartControl( 8175): QS Service version code: 201091
D/UEI.SmartControl( 8175): Service requested: Control
E/UEI.SmartControl( 8175): Loading SETTINGS...
D/UEI.SmartControl( 8175): Request IControl service: devices are loaded...
I/QRemote ( 6900): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 8175): ------ IControl API: 11
I/ActivityManager( 1067): Killing 6900:com.lge.qremote/u0a112 (adj 15): empty #17
,I/UEI.SmartControl( 8175): Registering callback...
,D/UEI.SmartControl( 8175): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 8175): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8175): -----service ready thread exits
,W/libprocessgroup( 1067): failed to open /acct/uid_10112/pid_6900/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8175): Internal service binding...,
D/serial_port( 8175): close(fd = 25)
,D/UEI.SmartControl( 8175): Internal timer expired: 1
D/UEI.SmartControl( 8175): unbind internal service
D/UEI.SmartControl( 8175): Service.onUnbind: IControl
,D/UEI.SmartControl( 8175): Service.onDestroy
,D/UEI.SmartControl( 8175): Lock is in USE false
,D/UEI.SmartControl( 8175): unbind internal service
W/System.err( 8175): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31bf9991
,W/System.err( 8175): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,W/System.err( 8175): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,W/System.err( 8175): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,W/System.err( 8175): 	at com.uei.control.Service.c(Unknown Source)
,W/System.err( 8175): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8175): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8175): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 8175): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8175): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8175): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 8175): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8175): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 8175): ,	at java.lang.reflect.Method.invoke(Method.java:372),
W/System.err( 8175): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8175): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/UEI.SmartControl( 8175): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@31bf9991
I/UEI.SmartControl( 8175): Serial port is closed.,
I/UEI.SmartControl( 8175): Serial port is closed.
I/UEI.SmartControl( 8175): Serial port is closed.
D/UEI.SmartControl( 8175): Blaster closed
D/UEI.SmartControl( 8175): Shut down QS...
D/UEI.SmartControl( 8175): Stopping QS lib
D/UEI.SmartControl( 8175): QS lib stop result = true
D/UEI.SmartControl( 8175): Stopped QS lib
D/UEI.SmartControl( 8175): Stopped file observer...
D/UEI.SmartControl( 8175): QS shutdown complete,
D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1057695596788; DSPS: 34799768; Offset : -4323090058
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1077697677301; DSPS: 35455196; Offset : -4323084507
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1097699287554; DSPS: 36110609; Offset : -4323092023
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1117701827286; DSPS: 36766052; Offset : -4323084938
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1137703895143; DSPS: 37421480; Offset : -4323092563
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1157705979875; DSPS: 38076908; Offset : -4323082949
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1177708000961; DSPS: 38732334; Offset : -4323076074
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1197718724131; DSPS: 39388046; Offset : -4323094988
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1217721206519; DSPS: 40043487; Offset : -4323084601
,I/UsageStatsService( 1067): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1237723002293; DSPS: 40698906; Offset : -4323089104
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1257725085671; DSPS: 41354334; Offset : -4323081209
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1277726960038; DSPS: 42009756; Offset : -4323099036
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
,I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1297729030550; DSPS: 42665183; Offset : -4323072810
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1067): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1067): tsOffsetIs: Apps: 1317731771013; DSPS: 43320633; Offset : -4323079294
,TIME-OUT KILL (timeout was 1200000ms)
```
