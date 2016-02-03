#### Test 58135655e794d2c_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
D/PowerManagerServiceEx( 1073): acquireWakeLockInternal: lock=671199095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1073
I/ActivityManager( 1073): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6796 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
--------- beginning of main
D/[Concierge]Service( 2601): onStartCommand(). Type : 9
I/DigitalAppWidgetProvider( 6796): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 6796): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@142b7775
D/PowerManagerServiceEx( 1073): releaseWakeLockInternal: lock=671199095 [*alarm*], flags=0x0
I/ActivityManager( 1073): Killing 6324:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1073): failed to open /acct/uid_10004/pid_6324/cgroup.procs: No such file or directory
E/BooksSync( 6732): Soft error: 
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5374071587743925895&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
E/BooksSync( 6732): Sync error
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5374071587743925895&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
I/BooksSync( 6732): Finished books sync
I/ActivityManager( 1073): Killing 6462:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/SyncManager( 1073): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77018, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
W/libprocessgroup( 1073): failed to open /acct/uid_10008/pid_6462/cgroup.procs: No such file or directory
,I/GAV2    ( 6732): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 6839): 
D/AndroidRuntime( 6839): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6839): CheckJNI is OFF
D/AndroidRuntime( 6839): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1073): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1073): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1073): setTaskToReturnTo : TaskRecord{1a2b9b02 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1073): setTaskToReturnTo : TaskRecord{1a2b9b02 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1073): AppWindowTokenEx init.. 
E/GBMv2   (  338): DFP En is all cleared set to be enabled
I/ActivityManager( 1073): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6871 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6839): Shutting down VM
V/ActivityManager( 1073): Display changed displayId=0
D/DSDPConnection( 1859): Display #0 changed.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1fe6acda co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{287e350b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6871): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6871): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6871): Loading: webviewchromium
,I/LibraryLoader( 6871): Time to load native libraries: 4 ms (timestamps 6838-6842)
I/LibraryLoader( 6871): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6871): Binding Chromium to main looper Looper (main, tid 1) {2e65b30a}
I/LibraryLoader( 6871): Expected native library version number "",actual native library version number ""
I/chromium( 6871): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MusicWidget( 2663): mDelayedStopHandler : unbind
I/MusicBrowser( 2206): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/BrowserStartupController( 6871): Initializing chromium process, renderers=0
I/MusicBrowser( 2206): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
W/art     ( 6871): Attempt to remove local handle scope entry from IRT, ignoring
D/MusicBrowser( 2206): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2206): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2206): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2206): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1073):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@4fa5d61com.lge.music.MediaPlaybackService$5@1138086
D/MusicBrowser( 2206): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@d7aa744
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2206): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2206): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
V/AudioPolicyService(  313): registerClient() client 0xb1427420, uid 10311
I/MusicBrowser( 2206): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2206): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2206): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2206): reset
D/BluetoothManagerService( 1073): Message: 20
D/BluetoothManagerService( 1073): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23ee8f7c:true
W/chromium( 6871): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
V/MediaPlayer[Native]( 2206): setListener
V/MediaPlayer[Native]( 2206): disconnect
V/MediaPlayer[Native]( 2206): destructor
V/AudioFlinger(  313): releasing 13 from 2206 for -1
V/AudioFlinger(  313):  decremented refcount to 0
V/AudioFlinger(  313): purging stale effects
V/MediaPlayer[Native]( 2206): disconnect
D/MusicBrowser( 2206): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/chromium( 6871): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6871): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/SmartShareClient( 2206): [SmartShareManagerClient] smartshare client supported version code: 305000
,I/SmartShareClient( 2206): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2206): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2206): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2206): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2206): [SmartShareManagerClient] unregisterListener: 337296711
W/SmartShareClient( 2206): [SmartShareManagerClient] unregisterListener invalid listener: 337296711
I/SmartShareClient( 2206): [SmartShareManagerClient] terminate service: 2206/MediaPlaybackService/778416906
I/Adreno-EGL( 6871): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6871): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6871): Build Date: 12/12/14 금
I/Adreno-EGL( 6871): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6871): Remote Branch: 
I/Adreno-EGL( 6871): Local Patches: 
I/Adreno-EGL( 6871): Reconstruct Branch: 
E/HomeCloudIF( 2206): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2206): [SmartShareManagerClient] unbindService context:android.app.Application@20f86974
,V/CloudHub( 2206): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2206): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2206): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2206): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1073): Killing 6114:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
,W/libprocessgroup( 1073): failed to open /acct/uid_10011/pid_6114/cgroup.procs: No such file or directory
,W/chromium( 6871): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6871): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6871): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6871): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6871): CordovaWebView is running on device made by: LGE
,W/art     ( 6871): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6871): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6871): Render dirty regions requested: true
I/OpenGLRenderer( 6871): Initialized EGL, version 1.4
D/OpenGLRenderer( 6871): Enabling debug mode 0
,W/ActivityManager( 1073): Activity pause timeout for ActivityRecord{1357cc13 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6871): Validating map...
,D/SplitWindow( 1073): check instance of lgWin Window{196e8ed6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1073): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1073): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1073): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1073): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1073): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5afac8f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1073): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/LgDataFeature( 6871): LgDataFeature() Constructor: none
D/LgDataFeature( 6871): LgDataFeature() Constructor Done, null
I/Timeline( 6871): Timeline: Activity_idle id: android.os.BinderProxy@2858f2ba time:107215
,I/ActivityManager( 1073): Displayed com.test.thalitest/.MainActivity: +600ms (total +724ms)
,I/Timeline( 1073): Timeline: Activity_windows_visible id: ActivityRecord{1357cc13 u0 com.test.thalitest/.MainActivity t4} time:107241
D/JsMessageQueue( 6871): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6871): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6871): 
,I/chromium( 6871): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6871): 
,D/jxcore_app_log( 6871): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435216768,
,I/chromium( 6871): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
E/GBMv2   (  338): Set value is all cleared set the max
I/GBMv2   (  338): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6871): Initializing JXcore engine
W/jxcore-log( 6871): JXcore engine is ready
,W/Thread-808( 6930): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8786]" dev="sockfs" ino=8786 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-808( 6930): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-808( 6930): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9723]" dev="sockfs" ino=9723 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-808( 6930): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-808( 6930): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33038]" dev="sockfs" ino=33038 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6871): Starting JXcore engine
,W/jxcore-log( 6871): Platform android
W/jxcore-log( 6871): 
W/jxcore-log( 6871): Process ARCH arm
W/jxcore-log( 6871): 
,I/jxcore-log( 6871): JXcore Cordova bridge is ready!
I/jxcore-log( 6871): 
,W/jxcore-log( 6871): JXcore engine is started
,I/jxcore-log( 6871): Toggling radios to true
I/jxcore-log( 6871): 
,D/BluetoothAdapter( 6871): enable(): BT is already enabled..!
D/WifiService( 1073): New client listening to asynchronous messages
D/WifiServiceImplEx( 1073): setWifiEnabled: true pid=6871, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1073): setWifiEnabled: true pid=6871, uid=10311
E/WifiService( 1073): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1073): disconnect pid=6871, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1073):  ConnectedState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1073):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1073): [109,386,832 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
,D/WifiNative-wlan0( 1073): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1073): reconnect pid=6871, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6871): Radios toggled
I/jxcore-log( 6871): 
I/jxcore-log( 6871): My device name is: LGE-LG-D855
I/jxcore-log( 6871): 
,I/wpa_supplicant( 2695): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiNative-wlan0( 1073): DISCONNECT: returned true
,E/WifiStateMachine( 1073): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore( 1073): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1073): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1073): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1073): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1073): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering( 1073): InitialState.processMessage what=4
E/WifiMonitor( 1073): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1073): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1073): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1073): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1073): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1073): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1073): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1073): doBoolean: SET ps 1
D/WifiNative-wlan0( 1073): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1073): RunningState{ when=-16ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2119): Read error: ssl=0xaa700a00: I/O error during system call, Connection timed out
V/NativeCrypto( 2119): SSL shutdown failed: ssl=0xaa700a00: I/O error during system call, Broken pipe
,I/ActivityManager( 1073): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1073): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1073): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService( 1073): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 0
D/WifiHS20( 1073): hidePasspointNotification off =false
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1073): hidePasspointNotification off =false
,W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1073): Start Disconnecting Watchdog 1
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1073):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_RECONNECT 0 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiNative: ( 1073): [109,517,284 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1073): doBoolean: RECONNECT
I/wpa_supplicant( 2695): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1073): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1073): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1073): RECONNECT: returned true
E/WifiStateMachine( 1073):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109519
E/WifiStateMachine( 1073):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=109520
D/LGWifiP2pService( 1073): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1073): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1073): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1073): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1073): doBoolean: SET ps 1
D/WifiNative-wlan0( 1073): SET ps 1: returned true
,D/CommandListener(  309): Clearing all IP addresses on wlan0
D/ConnectivityService( 1073): Default network via Wi-Fi disconnect. stop DSQN
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1073): disableDataServiceNotify
D/DSQN    ( 1073): stop dsqn bin
D/DSQN    ( 1073): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=109556  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=109556  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1073): hidePasspointNotification off =false
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1073):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1073):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1073): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1073):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109564  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1073): hidePasspointNotification off =false
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=109571  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/Nat464Xlat( 1073): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Disconnected - quitting
D/CSLegacyTypeTracker( 1073): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1073): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524292
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateDISCONNECTED
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): sendStickyBroadcastDelayed: delayMs=,3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1073): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1073): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1073): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1073): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1073): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1073): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1073): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1073): Removing idletimer
D/TelephonyNetworkFactory-1( 1859): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1073): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1073): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1073): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1073): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1073):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1073): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1073): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1073): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1073): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1073): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateSCANNING
W/ResourcesManager( 6933): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{2c9cc262 type 2 when 109611 com.google.android.gms} when 109611
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6933): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6933): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6933): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6933): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6933): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6933): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1073): StoppedState
D/DhcpStateMachine( 1073): StoppedState{ when=-189ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1073): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1073): Killing 6138:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1073): failed to open /acct/uid_10019/pid_6138/cgroup.procs: No such file or directory
,I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6967): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6933): LgDataFeature() Constructor: none
D/LgDataFeature( 6933): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
I/ActivityManager( 1073): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6988 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1073): Killing 6496:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1073): failed to open /acct/uid_10023/pid_6496/cgroup.procs: No such file or directory
,W/ResourcesManager( 6988): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6988): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6988): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6988): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6988): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6988): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6988): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6988): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6988): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6988): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6988): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6967): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6967): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6967): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 6988): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/DSQN    ( 1073): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QRemote ( 6988): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/LgDataFeature( 6988): LgDataFeature() Constructor: none
D/LgDataFeature( 6988): LgDataFeature() Constructor Done, null
V/SoundPool( 6988): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 6988): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6988): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6988): doLoad: loading sample sampleID=1
,I/QRemote ( 6988): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6634): QS Service created
V/SoundPool( 6988): Start decode
V/MediaPlayer[Native]( 6988): decode(31, 10857164, 17813)
D/QRemote ( 6988): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/MediaPlayerService(  313): decode(24, 10857164, 17813)
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
V/AudioCache(  313): notify(0xb1163200, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  313): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6634): Service initServices...
D/UEI.SmartControl( 6634): QS start get config
E/QRemote ( 6988): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6988): Create singleton instance
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
,D/OMXCodec(  313): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on output port
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
V/AudioCache(  313): notify(0xb1163200, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb1163200, 1, 0, 0)
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
V/OM,XCodec(  313): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  313): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977024
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1a0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb1163200, 6, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab700000, 0xb57f5000, 4096)
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab701000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab702000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab703000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab704000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab705000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab706000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab707000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab708000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab709000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70a000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70b000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70c000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70d000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70e000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab70f000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab710000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab711000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab712000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab713000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab714000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab715000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab716000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab717000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab718000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab719000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71a000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71b000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71c000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71d000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71e000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab71f000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab720000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab721000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab722000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab723000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab724000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab725000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab726000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab727000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab728000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab729000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72a000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72b000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72c000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72d000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72e000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab72f000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab730000, 0xb57f5000, 4096)
V/AudioCache(  313): write(0xb57f5000, 4096)
V/AudioCache(  313): memcpy(0xab731000, 0xb57f5000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb57f5000, 280)
V/AudioCache(  313): memcpy(0xab732000, 0xb57f5000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb1163200, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): notify(0xb1163200, 7, 0, 0)
V/AudioCache(  313): wait - success
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  313): Pause Playback at 1068125
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1163200, 8, 0, 0)
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
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1a0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
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
V/SoundPool( 6988): close(31)
V/SoundPool( 6988): pointer = 0x9ffb8000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6988): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2090
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{34684a6b type 2 when 110667 com.google.android.gms} when 110667
,I/UEI.SmartControl( 6634): Supports setup maps: true
,D/UEI.SmartControl( 6634): QS start statue = true Error code = 0
I/UEI.SmartControl( 6634): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6634): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6634): ### init IR Blaster...
D/serial_port( 6634): Configuring serial port
E/UEI.SmartControl( 6634): UEIBLaster setting for 616
I/UEI.SmartControl( 6634): Setting serial record hearder size = 2
I/UEI.SmartControl( 6634): configuring settings for MAXQ616
I/UEI.SmartControl( 6634): Get version...
D/UEI.SmartControl( 6634): serial port data available: 21
,D/UEI.SmartControl( 6634): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6634): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6634): QS saving settings...
D/UEI.SmartControl( 6634): IR Blaster version: 25672567
,D/UEI.SmartControl( 6634): serial port data available: 4
,W/ContextImpl( 6634): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6634): Services init done
,D/UEI.SmartControl( 6634): QS Service init finished
D/UEI.SmartControl( 6634): QS Service version name: 2.1.91
D/UEI.SmartControl( 6634): QS Service version code: 201091
D/UEI.SmartControl( 6634): Service requested: Control
,I/UEI.SmartControl( 6634): Device manager: loading config....
D/UEI.SmartControl( 6634): ----------- loading internal config...
D/UEI.SmartControl( 6634): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6634): Loading SETTINGS...
D/UEI.SmartControl( 6634): Internal service binding...
,I/QRemote ( 6988): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6634): ------ IControl API: 11
D/UEI.SmartControl( 6634): File observer start...
E/UEI.SmartControl( 6634): IR Port is disabled: false
D/UEI.SmartControl( 6634): Starting file observer...
I/UEI.SmartControl( 6634): Registering callback...
I/UEI.SmartControl( 6634): ------ IControl API: 19
I/UEI.SmartControl( 6634): Registering Services Ready callback...
,D/UEI.SmartControl( 6634): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6634): Notify AllClients services are ready: 0
,I/QRemote ( 6988): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/UEI.SmartControl( 6634): -----service ready thread exits
D/QRemote ( 6988): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6988): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6988): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6988): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6634): ------ IControl API: 8
D/QRemote ( 6988): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6988): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6988): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6988): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6988): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6988): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6988): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6988): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6988): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 6988): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454534107738]
D/QRemote ( 6988): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1073): Killing 6161:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6988): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1073): failed to open /acct/uid_10027/pid_6161/cgroup.procs: No such file or directory
,V/QRemote ( 6988): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6988): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 6988): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{21a65986 type 2 when 111099 com.google.android.gms} when 111099
D/QRemote ( 6988): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2695): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1073): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1073): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1073): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1073):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2038 bcn=0
E/WifiStateMachine( 1073):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2038 bcn=0
E/WifiStateMachine( 1073):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2038 bcn=0
E/WifiStateMachine( 1073):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:2038 bcn=0
D/WifiNative-wlan0( 1073): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111632  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=111662  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{6bf2247 type 2 when 111967 com.google.android.gms} when 111967
,I/wpa_supplicant( 2695): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1073): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
I/wpa_supplicant( 2695): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2695): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=112516  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=112517  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=42 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1073): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=45 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1073): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1073): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1073):  DisconnectedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112527
E/WifiStateMachine( 1073):  ConnectModeState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112528
E/WifiStateMachine( 1073):  DriverStartedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112528
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1073): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1073):  SupplicantStartedState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112541
E/WifiStateMachine( 1073):  DefaultState CMD_ASSOCIATED_BSSID 42 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112541
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=112541  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6933): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6933): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6933): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6933): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6933): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6933): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6933): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=112571  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1073):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=112571  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=112572  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1073):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112572
E/WifiStateMachine( 1073):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112573
D/WifiNative-wlan0( 1073): doString: [STATUS]
D/WifiMonitor( 1073): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1073): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1073): MasterInitialState.processMessage what=3
D/Tethering( 1073): MasterInitialState.processMessage what=3
,D/WifiNative-wlan0( 1073):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1073): setVHTCapabilityType  : false
I/NetworkMonitor( 5548): type=WIFI subType= reason=null isConnected=false
I/NetworkMonitor( 5548): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1073): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/WifiServerServiceExt( 1073): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1073): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/GpsLocationProvider( 1073): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1073): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1073): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1073): Got NetworkAgent Messenger
E/WifiConfigStore( 1073): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1073): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1073): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1073): NetworkAgent connected
D/WifiNative-wlan0( 1073): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1073): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1073): SAVE_CONFIG: returned true
E/WifiConfigStore( 1073): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1073): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1073): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1073): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1073): SAVE_CONFIG: returned true
D/CommandListener(  309): Setting iface cfg
E/WifiStateMachine( 1073): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1073): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/DhcpStateMachine( 1073): WaitBeforeStartState
E/WifiStateMachine( 1073):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112649  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=112650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateFOUR_WAY_HANDSHAKE
,D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1073):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=112655  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=112656  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=112656  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1073):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1073): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1073):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1073):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1073): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1073): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1073): doBoolean: SET ps 0
D/WifiNative-wlan0( 1073): SET ps 0: returned true
D/WifiNative-wlan0( 1073): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1073): DRIVER BTCOEXMODE 1: returned true
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1073): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1073): Current State is mWaitBeforeStartState.
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGWifiP2pService( 1073): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@978b902 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1073): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@978b902 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1073): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1073): DHCP Start wake lock is acquired.
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/LgDhcpStateMachineHelper( 1073): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1073): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1073): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1073): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1073):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
E/WifiStateMachine( 1073):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1073):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1073):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1073): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1073):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 1073):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1073): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1073): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1073): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 6430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1073): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1073): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2695): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1073): DRIVER SETSUSPENDMODE 1: returned true
,D/WifiNative-wlan0( 1073): doBoolean: SET ps 1
D/WifiNative-wlan0( 1073): SET ps 1: returned true
,E/WifiStateMachine( 1073):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1073):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1073): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1073): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1073): ignoring duplicate network state non-change
I/ActivityManager( 1073): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7098 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1073): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1073): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1073): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1073): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WifiHS20( 1073): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1073): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  309): netlink response contains error (File exists)
D/ConnectivityService( 1073): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1073): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1073): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1073): Setting Dns servers for network 101 to [/192.168.1.1]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 1
,D/WifiHS20( 1073): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1073): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1073): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1073): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1073):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1073):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1073): currentScore = 0, newScore = 20
D/ConnectivityService( 1073):    accepting network in place of null
D/ConnectivityService( 1073): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1073): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1073):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1073): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1073): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1859): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1073): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1073): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1073): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1073): validation of new default Network = false
D/ConnectivityService( 1073): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1073): enableDataServiceNotify 
D/DSQN    ( 1073): start dsqn bin
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1073): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7119): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7119): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/LocSvc_java( 1073): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1073): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1073): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1073): ignore wifi update if we are not in OPENING or CLOSING
,E/DSQN    ( 7119): DSQN ssw
V/NetworkPolicy( 1073): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/AppUp4:AppBoxCP( 7098): onCreate
,W/AppUp4:DB( 7098):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7098):  setFingerPrint start
I/AppUp4:DB( 7098):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7098):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7098):  SDK version = 21
I/AppUp4:DB( 7098):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7098): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7098): onReceive
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
,D/LgDataFeature( 7098): LgDataFeature() Constructor: none
D/LgDataFeature( 7098): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7098): Context : android.app.ReceiverRestrictedContext@299a8998
D/AppUp4:CustFacade( 7098): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7098): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7098): begin check event
I/AppUp4:CustModeStarterReceiver( 7098): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7098): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7098): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7098): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7098): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1073): Killing 6532:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1073): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1073): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1073): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7125): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7125): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7125): version 5.5.6 starting
E/dhcpcd  ( 7125): get_duid: m
D/dhcpcd  ( 7125): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7125): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  309): argv[0]=dsqncommand
D/LGDataListener(  309): argv[1]=wlan0
D/LGDataListener(  309): argv[2]=1
D/LGDataListener(  309): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1073): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1073): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 21:15:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454534109698], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454534109679]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1073): Validated
D/ConnectivityService( 1073): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1073):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1073):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1073): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1073): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1073): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1073):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1859): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1859):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/dhcpcd  ( 7125): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7125): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7125): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7125): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7125): wlan0: sending REQUEST (xid 0xf1cd1dd), next in 4.68 seconds
W/libprocessgroup( 1073): failed to open /acct/uid_10061/pid_6532/cgroup.procs: No such file or directory
,D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3317): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4297): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4297): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3317): DownloadService onCreate
,I/DownloadManager( 3317): in removeSpuriousFiles
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@394d7cc5 on behalf of 3317
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,I/DownloadManager( 3317): in trimDatabase
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@760561a on behalf of 3317
I/ActivityManager( 1073): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7139 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3317): DownloadService onStartCommand
V/DownloadManager( 3317): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@3e9f0b28 on behalf of 3317
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3317): processing inserted download 1
,V/DownloadManager( 3317): processing inserted download 4
V/DownloadManager( 3317): processing inserted download 7
E/LGDMClient( 4297): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/LGDMClient( 4297): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4297): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/DownloadManager( 3317): processing inserted download 8
,V/DownloadManager( 3317): processing inserted download 9
V/DownloadManager( 3317): processing inserted download 10
V/DownloadManager( 3317): processing inserted download 16
V/DownloadManager( 3317): processing inserted download 17
V/DownloadManager( 3317): processing inserted download 18
V/DownloadManager( 3317): processing inserted download 21
V/DownloadManager( 3317): processing inserted download 22
V/DownloadManager( 3317): DownloadService onDestroy
,W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7139): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7139): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7139): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7139): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7139): LgDataFeature() Constructor: none
D/LgDataFeature( 7139): LgDataFeature() Constructor Done, null
,D/eas_req ( 7139): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1073): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7163 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7139): JNI_OnLoad()
I/HubEmail( 7139): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7139): registerNatives()
I/HubEmail( 7139): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7139): registerNativeMethods()
I/HubEmail( 7139): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7139): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1073): Killing 6584:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1073): failed to open /acct/uid_10080/pid_6584/cgroup.procs: No such file or directory
,W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/AlarmManager( 1073): RTC_WAKEUP set : Alarm{3734f8b1 type 0 when 1454534110313 com.android.vending} when 1454534110313
,I/LgeMiscReceiver( 3271): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3271): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3271): networkInfo.isConnected() = false
,I/ActivityManager( 1073): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7190 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  354): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 14.145ms
I/art     (  354): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 14.192ms
,I/art     (  354): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 222us total 11.982ms
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 81503(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.068ms total 140.194ms
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{18329117 type 2 when 113684 com.google.android.gms} when 113684
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1073): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7212 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/FormManager( 7163): There are no updated forms. The schedule will be deleted.
V/FormManager( 7163): Alarm would be updated, because LastCheckTime has been updated.
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1073): Killing 5793:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1073):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1073):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1073):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1073):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1073):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1073):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1073): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1073): identical MTU - not setting
D/Nat464Xlat( 1073): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1073): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1073):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1073): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524295
W/libprocessgroup( 1073): failed to open /acct/uid_10097/pid_5793/cgroup.procs: No such file or directory
,I/ActivityManager( 1073): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7231 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1073): Killing 6611:com.lge.eula/1000 (adj 15): empty #17
,I/dhcpcd  ( 7125): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7125): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 7125): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7125): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7125): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7125): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7125): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7125): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7125): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/libprocessgroup( 1073): failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
,D/Finsky  ( 6205): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6205): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6205): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1073): Killing 6016:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     ( 7231): Almond Protected OAT
,W/libprocessgroup( 1073): failed to open /acct/uid_10005/pid_6016/cgroup.procs: No such file or directory
,D/WeatherApplication( 7231): removeAccount
D/WeatherApplication( 7231): Account.length = 0
E/WeatherApplication( 7231): OPERATOR:OPEN
D/WeatherAncestor( 7231): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:11
D/Weather.Utils( 7231): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7231): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7231): 2 : This is isUpdating : false
,D/WeatherAncestor( 7231): connectivity changed - connection : true
D/WeatherService( 7231): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7231): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7231): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7231): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7231): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7231): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:11
,I/ActivityManager( 1073): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7269 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1073): Killing 6666:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1073): failed to open /acct/uid_1000/pid_6666/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1073): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1073): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1073): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1073): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1073): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1073): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1073): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1073): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1073): RunningState
E/WifiStateMachine( 1073):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1073):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1073):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1073):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1073):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6871): 
,I/WebViewFactory( 7269): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7269): Loading: webviewchromium
I/LibraryLoader( 7269): Time to load native libraries: 4 ms (timestamps 4826-4830)
,I/LibraryLoader( 7269): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7269): Binding Chromium to main looper Looper (main, tid 1) {21bbe6e3}
I/LibraryLoader( 7269): Expected native library version number "",actual native library version number ""
I/chromium( 7269): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7269): Initializing chromium process, renderers=0
W/art     ( 7269): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  313): registerClient() client 0xb1427080, uid 10093
W/AudioManagerAndroid( 7269): Requires BLUETOOTH permission
,W/chromium( 7269): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7269): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7269): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7269): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7269): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7269): Build Date: 12/12/14 금
I/Adreno-EGL( 7269): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7269): Remote Branch: 
I/Adreno-EGL( 7269): Local Patches: 
I/Adreno-EGL( 7269): Reconstruct Branch: 
,I/NSApplication( 7269): Starting up...
,I/ActivityManager( 1073): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7324 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1073): Killing 6056:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1073): failed to open /acct/uid_10014/pid_6056/cgroup.procs: No such file or directory
,W/ResourcesManager( 7324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6871): 
,I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6871): 
,I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6871): 
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6871): 
W/ContextImpl( 6430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] request level :IDLE....
I/GLSActivity( 2119): [ac] getting account id
,I/AppUp4:CustModeStarterReceiver( 7098): onReceive
I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6871): 
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6871): 
D/AppUp4:CustFacade( 7098): Context : android.app.ReceiverRestrictedContext@299a8998
D/AppUp4:CustFacade( 7098): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7098): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7098): begin check event
I/AppUp4:CustModeStarterReceiver( 7098): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6871): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6871): 
I/GLSUser ( 2119): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3317): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3317): DownloadService onCreate
I/DownloadManager( 3317): in removeSpuriousFiles
D/LGDMClient( 4297): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@f1db9e6 on behalf of 3317
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LGDMClient( 4297): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3317): in trimDatabase
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@2c306b27 on behalf of 3317
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3317): DownloadService onStartCommand
,D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
I/LgeMiscReceiver( 3271): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3271): action = android.net.conn.CONNECTIVITY_CHANGE
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
I/LgeMiscReceiver( 3271): networkInfo.isConnected() = false
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
V/DownloadManager( 3317): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@5fb8e72 on behalf of 3317
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LGDMClient( 4297): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4297): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4297): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3317): processing inserted download 1
V/DownloadManager( 3317): processing inserted download 4
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7231): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:12
V/DownloadManager( 3317): processing inserted download 7
V/DownloadManager( 3317): processing inserted download 8
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
V/DownloadManager( 3317): processing inserted download 9
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,V/DownloadManager( 3317): processing inserted download 10
V/DownloadManager( 3317): processing inserted download 16
V/DownloadManager( 3317): processing inserted download 17
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/Weather.Utils( 7231): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7231): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7231): 2 : This is isUpdating : false
D/WeatherAncestor( 7231): connectivity changed - connection : true
D/WeatherService( 7231): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1d33f5d6
V/DownloadManager( 3317): processing inserted download 18
V/DownloadManager( 3317): processing inserted download 21
D/ForecastDataCache( 7231): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7231): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7231): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7231): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7231): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:12
V/DownloadManager( 3317): processing inserted download 22
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3317): DownloadService onDestroy
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6988): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6988): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6988): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6988): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6967): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6967): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6933): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6933): MCCMNC not supported: null
D/QRemote ( 6988): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6988): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6988): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6988): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6988): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  309): res_queryN name = mtalk.google.com, class = 1, type = 1
V/WifiInternetCheck( 1073): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1073): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1073): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  309): res_queryN name = mtalk.google.com succeed
D/Tethering( 1073): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1073): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5548): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7098): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7098): onReceive
,D/AppUp4:CustFacade( 7098): Context : android.app.ReceiverRestrictedContext@299a8998
D/AppUp4:CustFacade( 7098): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7098): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7098): begin check event
I/AppUp4:CustModeStarterReceiver( 7098): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4297): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3317): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3317): DownloadService onCreate
D/LGDMClient( 4297): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3317): in removeSpuriousFiles
I/LGDMClient( 4297): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@23de1740 on behalf of 3317
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3317): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3317): in trimDatabase
V/DownloadManager( 3317): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@2c259679 on behalf of 3317
,I/LgeMiscReceiver( 3271): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3271): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3271): networkInfo.isConnected() = true
D/PhoneState( 3271): setPdpRejectCasuse : false
,W/ContextImpl( 4297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4297): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4297): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4297): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3317): DownloadService onStartCommand
D/WeatherAncestor( 7231): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:12
V/DownloadManager( 3317): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3317): created cursor android.database.sqlite.SQLiteCursor@312d676c on behalf of 3317
D/Weather.Utils( 7231): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7231): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7231): 2 : This is isUpdating : false
D/WeatherAncestor( 7231): connectivity changed - connection : true
D/WeatherService( 7231): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1d33f5d6
D/ForecastDataCache( 7231): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7231): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7231): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7231): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7231): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:15:12
V/DownloadManager( 3317): processing inserted download 1
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3317): processing inserted download 4
V/DownloadManager( 3317): processing inserted download 7
V/DownloadManager( 3317): processing inserted download 8
,V/DownloadManager( 3317): processing inserted download 9
V/DownloadManager( 3317): processing inserted download 10
V/DownloadManager( 3317): processing inserted download 16
D/UEI.SmartControl( 6634): Internal timer expired: 2
D/UEI.SmartControl( 6634): unbind internal service
V/DownloadManager( 3317): processing inserted download 17
V/DownloadManager( 3317): processing inserted download 18
V/DownloadManager( 3317): processing inserted download 21
,V/DownloadManager( 3317): processing inserted download 22
,V/DownloadManager( 3317): DownloadService onDestroy
V/FormManager( 7163): There are no updated forms. The schedule will be deleted.
V/FormManager( 7163): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/FormManager( 7163): There are no updated forms. The schedule will be deleted.
V/FormManager( 7163): Alarm would be updated, because LastCheckTime has been updated.
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2119): Connected
,D/GCM     ( 2119): Message class com.google.f.a.a.p
,D/serial_port( 6634): close(fd = 24)
,I/UEI.SmartControl( 6634): Serial port is closed.
,I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19985
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.google.com succeed
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1073): isHttpConnectionAvailable - We got a valid response : 204
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 117682524960; DSPS: 3997040; Offset : -4308786991
,I/GAV4    ( 7269): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1073): Killing 6796:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1073): failed to open /acct/uid_10010/pid_6796/cgroup.procs: No such file or directory
,I/jxcore-log( 6871): Test app app.js loaded
I/jxcore-log( 6871): 
,I/chromium( 6871): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6871): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd6a798 added. We now have 1 listener(s)
,I/jxcore-log( 6871): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6871): 
,V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{4aafa24 type 2 when 130947 android} when 130947
,V/QRemote ( 6988): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6988): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2090
,I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2206): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 137684598754; DSPS: 4652468; Offset : -4308790321
,V/AlarmManager( 1073): RTC_WAKEUP set : Alarm{2b3e5742 type 0 when 1454534130967 com.android.vending} when 1454534130967
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 38732(1764KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 2.208ms total 152.229ms
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6205): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6205): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6205): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1073):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1073):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1073):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1073):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1073):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine( 1073):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 157686711611; DSPS: 5307897; Offset : -4308783253
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/PowerManagerServiceEx( 1073): acquireWakeLockInternal: lock=671199095, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1073
,V/AlarmManager( 1073): RTC_WAKEUP set : Alarm{3fd70ffd type 0 when 1454534161867 com.android.vending} when 1454534161867
,D/[Concierge]Service( 2601): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1073): releaseWakeLockInternal: lock=671199095 [*alarm*], flags=0x0
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6205): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6205): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6205): [1] 5.onFinished: Scheduling replication attempt 4.
V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{3d048897 type 2 when 167271 android} when 167271
,I/BooksSync( 6732): Starting books sync
,D/BooksSync( 6732): started syncMyEbooks
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6732): null auth token
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  309): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
W/ApiaryClient( 6732): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8929336367442308176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6732): null auth token
W/ResourcesManager( 1403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1403): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
,W/ApiaryClient( 6732): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8929336367442308176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6732): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
,W/ApiaryClient( 6732): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8929336367442308176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,E/BooksSync( 6732): Soft error: 
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8929336367442308176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
,E/BooksSync( 6732): Sync error
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8929336367442308176&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
I/BooksSync( 6732): Finished books sync
D/SyncManager( 1073): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167271, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 177688630197; DSPS: 5963320; Offset : -4308787224
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1073): battery changed pluggedType: 2
,D/LEDHandler( 1953): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1953): Battery Level Remaining: 100%
D/LEDHandler( 1953): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1073): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1073): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3763): Disconnected process message: 10, size: 0
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4297): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1073): RTC_WAKEUP set : Alarm{26b02b13 type 0 when 1454534183796 com.android.vending} when 1454534183796
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6205): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6205): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6205): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{2c9b81bd type 2 when 197295 android} when 197295
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 197690792585; DSPS: 6618751; Offset : -4308791479
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 217692634088; DSPS: 7274171; Offset : -4308780927
,V/AlarmManager( 1073): RTC_WAKEUP set : Alarm{3f49ff03 type 0 when 1454534207268 com.android.vending} when 1454534207268
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6205): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6205): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6205): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{1d15542d type 2 when 211260 android} when 211260
,V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{2988bd62 type 2 when 186340 com.google.android.gms} when 186340
,D/[Concierge]Service( 2601): onStartCommand(). Type : 9
,V/AlarmManager( 1073): ELAPSED_WAKEUP set : Alarm{3ae2b7b0 type 2 when 227321 android} when 227321
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 6732): Starting books sync
,D/BooksSync( 6732): started syncMyEbooks
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2119): Vacuum at: now=1454534224284 tag=VacuumService
,I/GoogleURLConnFactory( 2119): Using platform SSLCertificateSocketFactory
,W/Uploader( 2119): No account for auth token provided
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  309): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/libc-netbsd(  309): res_queryN name = play.googleapis.com succeed
E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6732): null auth token
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
,W/ApiaryClient( 6732): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6940654259879668861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119): No account for auth token provided
,W/Uploader( 2119):  no longer exists, so no auth token.
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2119): Explicit concurrent mark sweep GC freed 48093(2MB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.199ms total 64.086ms
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 27199(1165KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.040ms total 125.098ms
,V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6732): null auth token
D/LgeQuickCoverNLService( 1403): onNotificationPosted
D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
,W/ApiaryClient( 6732): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6940654259879668861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1073): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1073): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1073): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1073): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1073): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1403): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1403): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1403): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1403): handleNotificationPosted(true)
D/QuickCircle( 1403): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1403): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): post do just update job
D/LgeQuickCoverNotificationData( 1403): showAll3
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1403): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1403): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1403): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1403): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1403): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6732): Authentication error
E/BooksAccountManager( 6732): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6732): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6732): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6732): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6732): null auth token
D/QuickStatusbarLayout( 1403): Notification difference=198
D/QuickStatusbarLayout( 1403): child = android.widget.LinearLayout{23de1740 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6732): Error response from books API: {
W/ApiaryClient( 6732):  "error": {
W/ApiaryClient( 6732):   "errors": [
W/ApiaryClient( 6732):    {
W/ApiaryClient( 6732):     "domain": "global",
W/ApiaryClient( 6732):     "reason": "required",
W/ApiaryClient( 6732):     "message": "Login Required",
W/ApiaryClient( 6732):     "locationType": "header",
W/ApiaryClient( 6732):     "location": "Authorization"
W/ApiaryClient( 6732):    }
W/ApiaryClient( 6732):   ],
W/ApiaryClient( 6732):   "code": 401,
W/ApiaryClient( 6732):   "message": "Login Required"
W/ApiaryClient( 6732):  }
W/ApiaryClient( 6732): }
,W/ApiaryClient( 6732): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6940654259879668861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6732): Headers:
W/ApiaryClient( 6732): accept-encoding: [gzip]
W/ApiaryClient( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6732): gdata-version: 2
,E/BooksSync( 6732): Soft error: 
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6940654259879668861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
,E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
,E/BooksSync( 6732): Sync error
E/BooksSync( 6732): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6732): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6940654259879668861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6732): Headers:
E/BooksSync( 6732): accept-encoding: [gzip]
E/BooksSync( 6732): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6732): gdata-version: 2
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6732): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6732): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6732): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6732): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6732): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6732): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6732): {
E/BooksSync( 6732):  "error": {
E/BooksSync( 6732):   "errors": [
E/BooksSync( 6732):    {
E/BooksSync( 6732):     "domain": "global",
E/BooksSync( 6732):     "reason": "required",
E/BooksSync( 6732):     "message": "Login Required",
E/BooksSync( 6732):     "locationType": "header",
E/BooksSync( 6732):     "location": "Authorization"
E/BooksSync( 6732):    }
E/BooksSync( 6732):   ],
E/BooksSync( 6732):   "code": 401,
E/BooksSync( 6732):   "message": "Login Required"
E/BooksSync( 6732):  }
E/BooksSync( 6732): }
E/BooksSync( 6732): 
E/BooksSync( 6732): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6732): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6732): 	... 8 more
I/BooksSync( 6732): Finished books sync
D/SyncManager( 1073): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203692, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1073): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1073): tsOffsetIs: Apps: 237694046216; DSPS: 7929577; Offset : -4308772893
,I/jxcore-log( 6871): --= Surplus to requirements =--
I/jxcore-log( 6871): 
I/jxcore-log( 6871): ****TEST TOOK:  ms ****
I/jxcore-log( 6871): 
I/jxcore-log( 6871): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6871): 
,D/AndroidRuntime( 7533): 
D/AndroidRuntime( 7533): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7533): CheckJNI is OFF
D/AndroidRuntime( 7533): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1073): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1073): Killing 6871:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1073): Skipping PackageSetting{27dc6f09 com.example.hello/10319} due to missing metadata
,I/WindowState( 1073): WIN DEATH: Window{196e8ed6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1073): Client connection lost with reason: 4
D/InputDispatcher( 1073): Window went away: Window{196e8ed6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1073):   Force finishing activity ActivityRecord{1357cc13 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  338): DFP En is all cleared set to be enabled
,W/ActivityManager( 1073): Spurious death for ProcessRecord{1417e6c3 6871:com.test.thalitest/u0a311}, curProc for 6871: null
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{3681fe8 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{27e7601 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/ActivityManager( 1073): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/art     ( 4578): Explicit concurrent mark sweep GC freed 15072(878KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 554us total 41.867ms
,I/[LGHome]EVENT( 2075): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2075): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader( 1073): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1824): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_MrGDBLogger_PackageInfoDetector( 3657): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2031): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
V/SIM_STK ( 1073): Menu title from STK is T-Mobile
,I/art     ( 1073): Explicit concurrent mark sweep GC freed 12326(912KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.327ms total 115.485ms
,D/PostponalbeReceiver( 6430): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/[LGHome]EVENT( 2075): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 4529): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4529): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4529): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4529): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4529): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4529): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4529): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4529): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4529): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4529): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1073): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7565 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1910): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3657): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2075): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1451): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2075): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2075): [Launcher.java:1114:onPause()]onPause
D/administrator( 1073): Handling package changes for user 0
D/ActionManagerService( 1910): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3657): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3657): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2075): , create_time: 1430558575574
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2075): , create_time: 1430558575600
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
I/GBoardWebViewUtils( 2075): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2075): , create_time: 1453982950152
I/GBoardWebViewUtils( 2075): , expire_time: 0
I/GBoardWebViewUtils( 2075): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2075): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2075): , display: false
I/GBoardWebViewUtils( 2075): , animation: false }
D/WallpaperManager( 2075): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/SplitUIManager( 1876): split_name #11 / not available #0
D/SplitUIService( 1876): removed split : 
I/SystemUI[Framework]( 1073): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1073): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1073): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1073): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1073): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5afac8f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1073): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
V/SIM_STK ( 1073): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 7098): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2075): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1451): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/SplitUIManager( 1876): split_name #11 / not available #0
I/SplitUIService( 1876): split app #11
I/ActivityManager( 1073): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7586 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/SIM_STK ( 1073): Menu title from STK is T-Mobile
W/ActivityManager( 1073): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3763): [BTUI] [-] updateMediaPlayerInfo
I/LockScreenSettings( 7565): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
,D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
I/[LGHome]EVENT( 2075): [Launcher.java:5349:onStop()]onStop
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
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/NotificationService( 1073): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1073): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1073): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1073): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1451): handleShortcutListChanged...
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourcesManager( 7586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7586): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7586): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7586): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7586): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager( 1073): Killing 2206:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  313): 2206 died, releasing its sessions
V/AudioFlinger(  313):  pid 1859 @ 0
V/AudioFlinger(  313):  pid 3271 @ 1
V/AudioFlinger(  313):  pid 3271 @ 2
,I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ThermalEngine(  329): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3114): Thermal-Lib-Client: Client request sent
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2075): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 1073): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2075): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/art     ( 1073): Explicit concurrent mark sweep GC freed 9624(515KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.195ms total 298.241ms
,W/libprocessgroup( 1073): failed to open /acct/uid_10034/pid_2206/cgroup.procs: No such file or directory
D/KeyguardModel( 1451): handleShortcutListChanged...
,I/Timeline( 1073): Timeline: Activity_windows_visible id: ActivityRecord{98eace8 u0 com.lge.launcher2/.Launcher t3} time:250623
D/[Concierge]Service( 2601): onStartCommand(). Type : 8
D/[Concierge]Service( 2601): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2601): Update widget ID : 11
D/[Concierge]WidgetView( 2075): change position of spinner
W/ResourceType( 1073): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WidgetView( 2075): initWebView(). Time : 1454534247385
D/[Concierge]Service( 2601): onStartCommand(). Type : 0
,I/SystemConfig( 7586): BUILD Country: EU
I/SystemConfig( 7586): BUILD Operator: OPEN
,I/[Concierge]WebView( 2075): Return exist ConciergeWebView. Reuse : 689262090
,D/[Concierge]WidgetView( 2075): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2075): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@215ae8d2
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2075): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2075): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2075): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2075): Widget kill message received. Destory myself. My : 1454534025393, New one : 1454534247385
D/[Concierge]WidgetView( 2075): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2075): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2075): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/ActivityManager( 1073): Killing 6967:com.lge.sync/1000 (adj 15): empty #17
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7533): Shutting down VM
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2075): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2075): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2075): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2075): Timeline: Activity_idle id: android.os.BinderProxy@345cc1a5 time:250747
,W/libprocessgroup( 1073): failed to open /acct/uid_1000/pid_6967/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 2177): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7586): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7586): existFile = false
I/SystemConfig( 7586): canReadFile = false
I/SystemConfig( 7586): systemFeature RCS result false
D/SystemConfig( 7586): refreshRcsSupport() :false
I/PackageChangeReceiver( 7139): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1073): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7609 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7609): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 7609): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 2075): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/AppConfig( 7609): Total System Memory = 2995761152
,D/SystemHelper( 7609): region [EU], country [EU], operator [OPEN], sub-operator []
,I/GBoardtInterface( 2075): onReloaded()
,I/GBoardWebViewClient( 2075): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3657): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3657): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/ActivityManager( 1073): Killing 6933:com.android.settings/1000 (adj 15): empty #17
D/LIA_Service_NativeEventReceiver( 2031): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2031): startLIAService() : Trying to start LIA service ...
,W/libprocessgroup( 1073): failed to open /acct/uid_1000/pid_6933/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2031): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6430): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1073): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7633 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3657): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3657): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3657): handleMessage: what(1000) actionID(0x1000001)
V/BoardContentProvider( 3657): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_Tips_SmartTipsActionManager( 3657): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3657): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3657): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2075): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2075): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,E/SQLiteDatabase( 7633): Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
E/SQLiteDatabase( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7633): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/SQLiteDatabase( 7633): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7633): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7633): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7633): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/LifetrackerProvider2( 7633): Unable to open database for writing.
E/LifetrackerProvider2( 7633): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/Lifetrac,kerProvider2( 7633): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LifetrackerProvider2( 7633): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LifetrackerProvider2( 7633): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LifetrackerProvider2( 7633): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LifetrackerProvider2( 7633): 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
E/LifetrackerProvider2( 7633): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/LifetrackerProvider2( 7633): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/LifetrackerProvider2( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LifetrackerProvider2( 7633): 	at android.os.Looper.loop(Looper.java:135)
E/LifetrackerProvider2( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/LifetrackerProvider2( 7633): 	at java.lang.reflect.Method.invoke(Native Method)
E/LifetrackerProvider2( 7633): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/LifetrackerProvider2( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/LifetrackerProvider2( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/ActivityThread( 7633): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7633): No ProfileInfo entries

```
