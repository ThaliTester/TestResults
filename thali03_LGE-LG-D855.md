#### Test 58380500962e22b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
E/BooksSync( 6549): Soft error: 
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2053951406240215299&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
E/BooksSync( 6549): Sync error
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2053951406240215299&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
I/BooksSync( 6549): Finished books sync
--------- beginning of system
I/ActivityManager( 1036): Killing 6198:com.android.defcontainer/u0a4 (adj 15): empty #17
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 77853, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_6198/cgroup.procs: No such file or directory
I/GAV2    ( 6549): Thread[GAThread,5,main]: No campaign data found.
,I/MusicWidget( 2690): mDelayedStopHandler : unbind
I/MusicBrowser( 2214): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2214): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2214): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2214): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2214): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2214): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1036):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2883282com.lge.music.MediaPlaybackService$5@25ed4d93
D/MusicBrowser( 2214): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@208e30a0
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2214): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2214): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2214): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2214): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2214): reset
V/MediaPlayer[Native]( 2214): setListener
V/MediaPlayer[Native]( 2214): disconnect
V/MediaPlayer[Native]( 2214): destructor
V/AudioFlinger(  318): releasing 13 from 2214 for -1
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/MediaPlayer[Native]( 2214): disconnect
D/MusicBrowser( 2214): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2214): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2214): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2214): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2214): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2214): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2214): [SmartShareManagerClient] unregisterListener: 106889680
W/SmartShareClient( 2214): [SmartShareManagerClient] unregisterListener invalid listener: 106889680
I/SmartShareClient( 2214): [SmartShareManagerClient] terminate service: 2214/MediaPlaybackService/667203142
E/HomeCloudIF( 2214): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2214): [SmartShareManagerClient] unbindService context:android.app.Application@1fe155c9
V/CloudHub( 2214): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2214): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2214): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2214): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1036): Killing 6324:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2214): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
D/AndroidRuntime( 6618): 
D/AndroidRuntime( 6618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6618): CheckJNI is OFF
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6324/cgroup.procs: No such file or directory
D/AndroidRuntime( 6618): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1980): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{31a4a422 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{31a4a422 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6654 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6618): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1874): Display #0 changed.
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{36856116 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{7633a97 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6654): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6654): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6654): Loading: webviewchromium
,I/LibraryLoader( 6654): Time to load native libraries: 4 ms (timestamps 8078-8082)
I/LibraryLoader( 6654): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6654): Binding Chromium to main looper Looper (main, tid 1) {27c4b646}
,I/LibraryLoader( 6654): Expected native library version number "",actual native library version number ""
I/chromium( 6654): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6654): Initializing chromium process, renderers=0
W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  318): registerClient() client 0xb57d7f00, uid 10311
,W/chromium( 6654): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6654): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6654): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12424f9c:true
I/Adreno-EGL( 6654): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6654): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6654): Build Date: 12/12/14 금
I/Adreno-EGL( 6654): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6654): Remote Branch: 
I/Adreno-EGL( 6654): Local Patches: 
I/Adreno-EGL( 6654): Reconstruct Branch: 
,W/chromium( 6654): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6654): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6654): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6654): CordovaWebView is running on device made by: LGE
,W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6654): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6654): Render dirty regions requested: true
I/OpenGLRenderer( 6654): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6654): Enabling debug mode 0
,W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{21686eb3 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6654): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{66d55f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6654): LgDataFeature() Constructor: none
D/LgDataFeature( 6654): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1468): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2dc7953d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +645ms (total +754ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{21686eb3 u0 com.test.thalitest/.MainActivity t4} time:108578
I/Timeline( 6654): Timeline: Activity_idle id: android.os.BinderProxy@344d3cf6 time:108586
I/chromium( 6654): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6654): 
,D/JsMessageQueue( 6654): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6654): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435010816
,I/chromium( 6654): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6654): 
,I/chromium( 6654): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  339): DFP En is all cleared set to be enabled
,E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6654): Initializing JXcore engine
W/jxcore-log( 6654): JXcore engine is ready
,W/Thread-784( 6725): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7643]" dev="sockfs" ino=7643 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-784( 6725): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-784( 6725): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9867]" dev="sockfs" ino=9867 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-784( 6725): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-784( 6725): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33065]" dev="sockfs" ino=33065 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6654): Starting JXcore engine
,W/jxcore-log( 6654): Platform android
W/jxcore-log( 6654): 
W/jxcore-log( 6654): Process ARCH arm
W/jxcore-log( 6654): 
,I/jxcore-log( 6654): JXcore Cordova bridge is ready!
I/jxcore-log( 6654): 
,W/jxcore-log( 6654): JXcore engine is started
,I/jxcore-log( 6654): Toggling radios to true
I/jxcore-log( 6654): 
,D/BluetoothAdapter( 6654): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=6654, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=6654, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1036): disconnect pid=6654, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
,D/WifiServiceImplEx( 1036): reconnect pid=6654, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6654): Radios toggled
I/jxcore-log( 6654): 
E/WifiNative: ( 1036): [110,730,953 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
I/jxcore-log( 6654): My device name is: LGE-LG-D855
I/jxcore-log( 6654): 
,I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/Tethering( 1036): InitialState.processMessage what=4
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DhcpStateMachine( 1036): RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  314): Clearing all IP addresses on wlan0
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6728 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2144): Read error: ssl=0xaa76be00: I/O error during system call, Connection timed out
V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaa76be00: I/O error during system call, Broken pipe
I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 27.357ms
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): ignoring duplicate network state non-change
E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1036): [110,874,370 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
,I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110877
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=110878
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 0
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 18.703ms
D/LGWifiP2pService( 1036): InactiveState{ when=-17ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-17ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
,D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.090ms
,D/WifiNative-wlan0( 1036): SET ps 1: returned true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=110951  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1036): hidePasspointNotification off =false
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=110952  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkManagementService( 1036): Removing idletimer
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=110963  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=110965  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6728): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6728): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6728): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6728): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsControl( 6728): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6728): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6728): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6009:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6009/cgroup.procs: No such file or directory
,I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6764): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6728): LgDataFeature() Constructor: none
D/LgDataFeature( 6728): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6788 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1036): Killing 6029:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6029/cgroup.procs: No such file or directory
W/ResourcesManager( 6788): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6788): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 6788): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6788): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6788): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6788): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6788): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6788): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6788): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6788): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6764): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 6788): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6764): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6764): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6788): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6788): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6788): LgDataFeature() Constructor: none
D/LgDataFeature( 6788): LgDataFeature() Constructor Done, null
V/SoundPool( 6788): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6788): load: fd=31, offset=10857164, length=17813, priority=1
V/SoundPool( 6788): create sampleID=1, fd=30, offset=17813 length=10857164
V/SoundPool( 6788): doLoad: loading sample sampleID=1
V/SoundPool( 6788): Start decode
V/MediaPlayer[Native]( 6788): decode(30, 10857164, 17813)
V/MediaPlayerService(  318): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1432d00, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
I/QRemote ( 6788): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6485): QS Service created
D/QRemote ( 6788): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6788): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6788): Create singleton instance
V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
V/AwesomePlayer(  318): prepareAsync_l() 
V/MediaPlayerService(  318): wait for prepare
V/AwesomePlayer(  318): onPrepareAsyncEvent() 
V/AwesomePlayer(  318): initAudioDecoder() 
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AwesomePlayer(  318): getUseOffload() = 0 
V/OMXCodec(  318): OMXCodec::Create
V/OMXCodec(  318): findMatchingCodecs()
V/OMXCodec(  318): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  318): matchingCodecs.size()=1
V/OMXCodec(  318): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  318): LG Codec Adapter start
V/OMXCodec(  318): OMXCodec Createtor
V/OMXCodec(  318): setComponentRole
V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
V/LGCodecOSAL(  318): Not support LGCodec
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  318): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  318): Could not offload audio decode, try pcm offload
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  318): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  318): init()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  318): allocateBuffers
V/OMXCodec(  318): allocateBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcb50 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcce0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcd30 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb1432d00, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb1432d00, 1, 0, 0)
V/AudioCache(  318): prepared
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): start
V/AwesomePlayer(  318): play_l() 
V/AwesomePlayer(  318): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  318): createAudioPlayer_l
V/AwesomePlayer(  318): seekAudioIfNecessary_l() 
V/AwesomePlayer(  318): startAudioPlayer_l() 
D/AudioPlayer(  318): start of Playback, useOffload 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796384
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796624
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797024
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797104
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcce0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcb50 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca60 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb1432d00, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab504000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab505000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab506000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab507000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab508000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab509000, 0xb57f7000, 4096)
I/UEI.SmartControl( 6485): Service initServices...
D/UEI.SmartControl( 6485): QS start get config
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50b000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50c000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50e000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab50f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab510000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab511000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab512000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab513000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab514000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab515000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab516000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab517000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab518000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab519000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51b000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51c000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51e000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab51f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab520000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab521000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab522000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab523000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab524000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab525000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab526000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab527000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab528000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab529000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52b000, 0xb57f7000, 4096)
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52c000, 0xb57f7000, 4096)
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52e000, 0xb57f7000, 4096)
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:459
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab52f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab530000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab531000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab532000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab533000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab534000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xab535000, 0xb57f7000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb57f7000, 280)
V/AudioCache(  318): memcpy(0xab536000, 0xb57f7000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb1432d00, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb1432d00, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): Pause Playback at 1068125
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1432d00, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca60 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcb50 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcce0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 6788): close(30)
V/SoundPool( 6788): pointer = 0xa0017000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6485): Supports setup maps: true
D/UEI.SmartControl( 6485): QS start statue = true Error code = 0
I/UEI.SmartControl( 6485): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6485): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6485): ### init IR Blaster...
D/serial_port( 6485): Configuring serial port
E/UEI.SmartControl( 6485): UEIBLaster setting for 616
I/UEI.SmartControl( 6485): Setting serial record hearder size = 2
I/UEI.SmartControl( 6485): configuring settings for MAXQ616
I/UEI.SmartControl( 6485): Get version...
D/UEI.SmartControl( 6485): serial port data available: 21
,D/UEI.SmartControl( 6485): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6485): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6485): QS saving settings...
D/UEI.SmartControl( 6485): IR Blaster version: 25672567
D/UEI.SmartControl( 6485): serial port data available: 4
,W/ContextImpl( 6485): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6485): Device manager: loading config....
,D/UEI.SmartControl( 6485): ----------- loading internal config...
,E/UEI.SmartControl( 6485): Services init done
D/UEI.SmartControl( 6485): QS Service init finished
D/UEI.SmartControl( 6485): QS Service version name: 2.1.91
D/UEI.SmartControl( 6485): QS Service version code: 201091
D/UEI.SmartControl( 6485): Service requested: Control
,E/UEI.SmartControl( 6485): Loading SETTINGS...
D/UEI.SmartControl( 6485): Request IControl service: devices are loaded...
I/QRemote ( 6788): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6485): ------ IControl API: 11
D/UEI.SmartControl( 6485): Internal service binding...
D/UEI.SmartControl( 6485): File observer start...
,E/UEI.SmartControl( 6485): IR Port is disabled: false
,D/UEI.SmartControl( 6485): Starting file observer...
I/UEI.SmartControl( 6485): Registering callback...
I/UEI.SmartControl( 6485): ------ IControl API: 19
I/UEI.SmartControl( 6485): Registering Services Ready callback...
D/UEI.SmartControl( 6485): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6485): Notify AllClients services are ready: 0
I/QRemote ( 6788): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6485): -----service ready thread exits
D/QRemote ( 6788): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6788): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 6788): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6788): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6485): ------ IControl API: 8
D/QRemote ( 6788): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6788): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6788): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6788): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6788): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6788): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6788): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6788): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6788): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6788): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6788): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454973401850]
D/QRemote ( 6788): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6346:com.lge.email/u0a23 (adj 15): empty #17
,D/QRemote ( 6788): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6346/cgroup.procs: No such file or directory
,V/QRemote ( 6788): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6788): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2688): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=112938  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=112953  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2688): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=113036  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=113037  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113037
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113037
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113037
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113038
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113038
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=113038  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6728): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6728): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6728): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=113039  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2688): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection, to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=113051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=113051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113052
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113052
D/WifiNative-wlan0( 1036): doString: [STATUS]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1036): setSupplicantStateFOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
D/UsbSettingsControl( 6728): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6728): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6728): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6728): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1036): Got NetworkAgent Messenger
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1036): NetworkAgent connected
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1036): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113103  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113104  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=113104  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113105  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113105  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=113105  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36a4a915 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36a4a915 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1036): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
,D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], sta,te: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6849): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
,W/dsqn    ( 6849): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/DSQN    ( 6849): DSQN ssw
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6788): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6788): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6788): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6788): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6764): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6764): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6728): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6728): MCCMNC not supported: null
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6788): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6788): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6788): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,W/ContextImpl( 4505): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6860): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6860): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6860): version 5.5.6 starting
E/dhcpcd  ( 6860): get_duid: m
D/dhcpcd  ( 6860): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6860): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{31fbd4c4 type 0 when 1454973402704 com.android.vending} when 1454973402704
,D/dhcpcd  ( 6860): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6860): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6860): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6860): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6860): wlan0: sending REQUEST (xid 0x8e2bc576), next in 3.84 seconds
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2144): Explicit concurrent mark sweep GC freed 26282(1568KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.292ms total 62.923ms
,D/Finsky  ( 6089): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6089): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6089): [1] 5.onFinished: Scheduling replication attempt 2.
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/Tethering( 1036): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5428): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6292): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5428): type=WIFI subType= reason=null isConnected=true
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 23:16:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454973403376], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454973403359]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Validated
D/ConnectivityService( 1036): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6876 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlarmManagerService( 1036): Setting time of day to sec=1454973404
W/AlarmManagerService( 1036): Unable to set rtc to 1454973404: Invalid argument
,V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]Clock( 1468): onReceive = android.intent.action.TIME_SET
I/SecureClockService( 1980): Intent.ACTION_TIME_CHANGED 
I/LgeClockWidgetControlView( 1468): time changed, timezoneChanged : false
,D/LIA_Informant_Tips_DateChangeManager( 3732): onReceive() : ACTION_TIME_CHANGED
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/CalendarProvider2( 5970): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5970): Scheduling check of next Alarm
I/LIA_Informant_Tips_LogTracer( 3732): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-09 00:16:44...... Request
I/LIA_Informant_Tips_LogTracer( 3732): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 170, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3732): DateInfo : SmartTips Total Working Day Count = 170
D/LIA_Informant_Tips_DateChangeManager( 3732): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 3732): DateInfo : Last Date Check Time = 2016-02-09 00:16:44
W/ActivityManager( 1036): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2089): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/AppUp4:AppBoxCP( 6876): onCreate
,W/AppUp4:DB( 6876):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6876):  setFingerPrint start
I/AppUp4:DB( 6876):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6876):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6876):  SDK version = 21
I/AppUp4:DB( 6876):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6876): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6876): onReceive
D/LgDataFeature( 6876): LgDataFeature() Constructor: none
D/LgDataFeature( 6876): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6876): Context : android.app.ReceiverRestrictedContext@1d7cf534
D/AppUp4:CustFacade( 6876): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6876): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6876): begin check event
I/AppUp4:CustModeStarterReceiver( 6876): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6876): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6876): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6876): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6876): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6050:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6050/cgroup.procs: No such file or directory
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3374): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3374): DownloadService onCreate
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/DownloadManager( 3374): in removeSpuriousFiles
,V/DownloadManager( 3374): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@10ed2e18 on behalf of 3374
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
,I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3374): in trimDatabase
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3374): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@37982071 on behalf of 3374
I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6909 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3374): DownloadService onStartCommand
V/DownloadManager( 3374): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@e475ed7 on behalf of 3374
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3374): processing inserted download 1
V/DownloadManager( 3374): processing inserted download 4
V/DownloadManager( 3374): processing inserted download 7
V/DownloadManager( 3374): processing inserted download 8
V/DownloadManager( 3374): processing inserted download 9
,V/DownloadManager( 3374): processing inserted download 10
V/DownloadManager( 3374): processing inserted download 16
V/DownloadManager( 3374): processing inserted download 17
V/DownloadManager( 3374): processing inserted download 18
V/DownloadManager( 3374): processing inserted download 21
V/DownloadManager( 3374): processing inserted download 22
V/DownloadManager( 3374): DownloadService onDestroy
,W/ResourcesManager( 6909): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6909): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6909): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6909): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 70314(3MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.815ms total 175.691ms
,I/LGEmail ( 6909): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6909): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6909): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 6909): LgDataFeature() Constructor: none
D/LgDataFeature( 6909): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524295
I/dhcpcd  ( 6860): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/eas_req ( 6909): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 6860): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6860): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6860): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6860): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6860): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6860): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6860): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6860): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6943 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6909): JNI_OnLoad()
I/HubEmail( 6909): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6909): registerNatives()
I/HubEmail( 6909): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6909): registerNativeMethods()
I/HubEmail( 6909): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6909): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1036): Killing 6070:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6070/cgroup.procs: No such file or directory
W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = false
,I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6985 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7008 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6380:com.google.android.apps.docs/u0a61 (adj 15): empty #17
V/FormManager( 6943): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6943): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6380/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Killing 5658:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10097/pid_5658/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7029 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6427:com.lge.eula/1000 (adj 15): empty #17
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6654): 
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6427/cgroup.procs: No such file or directory
,I/art     ( 7029): Almond Protected OAT
,E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{3ea50c45 type 2 when 115909 com.google.android.gms} when 115909
,D/WeatherApplication( 7029): removeAccount
,D/WeatherApplication( 7029): Account.length = 0
E/WeatherApplication( 7029): OPERATOR:OPEN
D/WeatherAncestor( 7029): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:45
D/Weather.Utils( 7029): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7029): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7029): 2 : This is isUpdating : false
,D/WeatherAncestor( 7029): connectivity changed - connection : true
D/WeatherService( 7029): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7029): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7029): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7029): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7029): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7029): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:46
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7047 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 5941:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_5941/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1036): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1036): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5428): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7047): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7047): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7047): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7047): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7047): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6654): 
I/LibraryLoader( 7047): Loading: webviewchromium
I/LibraryLoader( 7047): Time to load native libraries: 3 ms (timestamps 6459-6462)
I/LibraryLoader( 7047): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7047): Binding Chromium to main looper Looper (main, tid 1) {10152fef}
I/LibraryLoader( 7047): Expected native library version number "",actual native library version number ""
I/chromium( 7047): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7047): Initializing chromium process, renderers=0
W/art     ( 7047): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  318): registerClient() client 0xb14fd920, uid 10093
,W/chromium( 7047): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 7047): Requires BLUETOOTH permission
I/chromium( 7047): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7047): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7047): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7047): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7047): Build Date: 12/12/14 금
I/Adreno-EGL( 7047): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7047): Remote Branch: 
I/Adreno-EGL( 7047): Local Patches: 
I/Adreno-EGL( 7047): Reconstruct Branch: 
I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6654): 
I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6654): 
I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6654): 
,I/NSApplication( 7047): Starting up...
,I/ActivityManager( 1036): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7110 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6453:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6453/cgroup.procs: No such file or directory
,W/ResourcesManager( 7110): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6654): 
D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6292): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6876): onReceive
,D/AppUp4:CustFacade( 6876): Context : android.app.ReceiverRestrictedContext@1d7cf534
D/AppUp4:CustFacade( 6876): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6876): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6876): begin check event
I/AppUp4:CustModeStarterReceiver( 6876): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3374): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSActivity( 2144): [ac] getting account id
,V/DownloadManager( 3374): DownloadService onCreate
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3374): in removeSpuriousFiles
V/DownloadManager( 3374): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/GLSUser ( 2144): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@103d52ad on behalf of 3374
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3374): in trimDatabase
V/DownloadManager( 3374): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@381b19e2 on behalf of 3374
V/DownloadManager( 3374): DownloadService onStartCommand
,V/DownloadManager( 3374): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@1c896ca9 on behalf of 3374
E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3374): processing inserted download 1
V/DownloadManager( 3374): processing inserted download 4
V/DownloadManager( 3374): processing inserted download 7
V/DownloadManager( 3374): processing inserted download 8
V/DownloadManager( 3374): processing inserted download 9
V/DownloadManager( 3374): processing inserted download 10
V/DownloadManager( 3374): processing inserted download 16
,V/DownloadManager( 3374): processing inserted download 17
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3374): processing inserted download 18
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = false
V/DownloadManager( 3374): processing inserted download 21
V/DownloadManager( 3374): processing inserted download 22
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
V/DownloadManager( 3374): DownloadService onDestroy
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
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7029): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:47
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/Weather.Utils( 7029): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7029): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7029): 2 : This is isUpdating : false
D/WeatherAncestor( 7029): connectivity changed - connection : true
D/WeatherService( 7029): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a85f0d2
D/ForecastDataCache( 7029): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7029): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7029): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7029): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7029): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:47
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,V/FormManager( 6943): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6943): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1036): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7157 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 214us total 11.228ms
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 9.190ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.705ms
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
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
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/ALBootInit( 7157): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 7157): Alarm ALBootInit: TIME_SET
D/Alarms  ( 7157): [setNextAlert] start
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/Alarms  ( 7157): [setNextAlert] (1)
,D/Alarms  ( 7157):  minTime  = 0
D/Alarms  ( 7157):  -- OK multi -- 0
E/jeny.kim( 7157): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7157): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 7157): BUILD Country: EU
,D/Alarms  ( 7157): broadcastToWidgetProvider : false
D/Alarms  ( 7157): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/UEI.SmartControl( 6485): Internal timer expired: 4
D/UEI.SmartControl( 6485): unbind internal service
V/SettingsProvider( 1036): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 7157): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 7157): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3b226f5d
D/serial_port( 6485): close(fd = 24)
V/DigitalAppWidgetProvider( 7157): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3b226f5d
D/QuickCoverProvider( 7157): onReceiver
I/UEI.SmartControl( 6485): Serial port is closed.
I/indal   ( 1417): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1417): SmartCoverWidgetContext createApplicationContext
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/WeatherAncestor( 7029): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:16:47
D/Weather.Utils( 7029): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7029): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7029): 2 : This is isUpdating : false
D/WeatherService( 7029): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a85f0d2
D/ForecastDataCache( 7029): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7029): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7029): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7029): 2 : set auto-update time : 2/9 3:16
,D/WeatherAncestor( 7029): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:16:47
V/WifiInternetCheck( 1036): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager( 1036): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7183 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1036): Killing 5970:com.android.providers.calendar/u0a14 (adj 15): empty #17
,I/CloudHub( 2214): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19994
,W/libprocessgroup( 1036): failed to open /acct/uid_10014/pid_5970/cgroup.procs: No such file or directory
,D/TimeService( 7183): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454973407829
D/        ( 7183): TimeServiceNative: User Time to be set is 1454973407829
D/QC-time-services( 7183): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7183): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7183): Lib:time_genoff_operation: pargs->ts_val = 1454973407829
D/QC-time-services( 7183): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  369): Daemon: Connection accepted:time_genoff
D/QC-time-services(  369): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454973407829
D/QC-time-services(  369): Daemon:genoff_opr: Base = 2, val = 1454973407829, operation = 0
D/QC-time-services(  369): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/18/70 16:28:50
D/QC-time-services(  369): Daemon:Value read from RTC seconds = 14574530000
D/QC-time-services(  369): Daemon:new time 1454973407829 
D/QC-time-services(  369): Daemon: delta 1440398877829 genoff 1440398877829 
,D/QC-time-services(  369): Daemon:genoff_persistent_update: Writing genoff = 1440398877829 to memory
D/QC-time-services(  369): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  369): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  369): Updating the TOD offset
D/QC-time-services(  369): Daemon:genoff_persistent_update: Writing genoff = 1440398877829 to memory
D/QC-time-services(  369): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  369): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  369): Daemon:Update to modem bit set
D/QC-time-services(  369): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  369): Daemon: Base = 2, Value being sent to MODEM = 1124434077829
E/QC-time-services( 7183): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  369): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  369): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1036): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7204 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1036): Killing 6549:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/rmt_storage(  310): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  310): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  310): wakelock acquired: 1, error no: 42
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1036): failed to open /acct/uid_10054/pid_6549/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 117970396886; DSPS: 4006355; Offset : -4307793178
,W/ResourcesManager( 7204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  310): 
,I/rmt_storage(  310): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  903): [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/CalendarApplication( 7204): CalendarApplication.onCreate()
D/PreferenceKeysParser( 7204): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7204): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@d8ed888, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@cfbd221, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@27c4b646, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1e6f2007, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1d7cf534, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3b226f5d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2a85f0d2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3ed3b5a3, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@208e30a0, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2b1ba459, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3cae481e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@156208ff, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2db5b6cc, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1d92d15, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2872c82a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2c58361b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@35ed73b8, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@7ac8591, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@344d3cf6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@29ba18f7, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3de21364, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1e82e9cd, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2883282, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@25ed4d93, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@65f01d0, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe155c9, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1d8af4ce, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@10152fef, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@f7a6afc, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea08585, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce58fda, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3c2edc0b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@22813ae8, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@868f501, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@f1ccfa6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@36ed2de7, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@ea31d94, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@22eee03d, lg_preferences_alerts_default_ringtone=com.android.c,alendar.adaptation.PreferenceKey$KeyData@14364032, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3b54c183, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@45e7f00, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@20ee4339,
D/GeneralPreferenceUtils( 7204): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 7204): [init]
I/Config  ( 7204): LGCalendar ver.4.40.16
I/Config  ( 7204): start check model
I/Config  ( 7204): start check native_ca
I/Config  ( 7204): Config Operator=OPEN, Country=EU
D/Config  ( 7204): [setDefaultValuesToPref]
D/Config  ( 7204): [parseProfiles]
D/ProfilesParser( 7204): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7204): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7204): [updateProfiletoCountryInfo]
D/GeneralPreference( 7204): [checkAndMigrateOldPreference]
,E/AgendaWidgetManager( 7204): [updateWidgets] 
I/InitNotificationRingtoneService( 7204): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7204): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 7204): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,W/HolidayIntentService( 7204): onHandleIntent
D/MonthWidgetProvider( 7204): [onReceive]
D/CalendarWidgetProvider( 7204): [onReceive]
D/CalendarWidgetProvider( 7204): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 7204): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 7204): readJsonAsset : holiday.json
D/WeekWidgetProvider( 7204): [onReceive]
D/CalendarWidgetProvider( 7204): [onReceive]
D/CalendarWidgetProvider( 7204): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7204): [onUpdateAndInitCalendarTime]
,E/HolidayIntentService( 7204): onHandleIntent:holiday data empty
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6292): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6876): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6876): onReceive
,D/AppUp4:CustFacade( 6876): Context : android.app.ReceiverRestrictedContext@1d7cf534
D/AppUp4:CustFacade( 6876): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6876): isPhone : true
I/art     ( 1036): Explicit concurrent mark sweep GC freed 29127(1401KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 3.543ms total 146.083ms
D/AppUp4:CustModeStarterReceiver( 6876): begin check event
I/AppUp4:CustModeStarterReceiver( 6876): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,V/DownloadManager( 3374): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3374): DownloadService onCreate
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
D/LGDMClient( 4282): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4282): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4282): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,W/ContextImpl( 4282): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3374): in removeSpuriousFiles
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/DownloadManager( 3374): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@e7f175c on behalf of 3374
,I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,E/LGDMClient( 4282): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4282): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4282): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3374): DownloadService onStartCommand
W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3374): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3374): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@23f33beb on behalf of 3374
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = true
D/PhoneState( 3349): setPdpRejectCasuse : false
I/DownloadManager( 3374): in trimDatabase
V/DownloadManager( 3374): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7029): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:48
D/Weather.Utils( 7029): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7029): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7029): 2 : This is isUpdating : false
D/WeatherAncestor( 7029): connectivity changed - connection : true
D/WeatherService( 7029): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a85f0d2
D/ForecastDataCache( 7029): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7029): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7029): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7029): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7029): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:16:48
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
V/DownloadManager( 3374): processing inserted download 1
V/DownloadManager( 3374): processing inserted download 4
V/DownloadManager( 3374): processing inserted download 7
V/DownloadManager( 3374): processing inserted download 8
,V/DownloadManager( 3374): processing inserted download 9
V/DownloadManager( 3374): processing inserted download 10
V/DownloadManager( 3374): processing inserted download 16
V/DownloadManager( 3374): processing inserted download 17
V/DownloadManager( 3374): processing inserted download 18
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
V/DownloadManager( 3374): created cursor android.database.sqlite.SQLiteCursor@2d944d48 on behalf of 3374
V/DownloadManager( 3374): processing inserted download 21
V/DownloadManager( 3374): processing inserted download 22
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
V/DownloadManager( 3374): DownloadService onDestroy
,I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 7204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7204): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 7204): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 7204): End InitializeAlertRingtoneService.onHandleIntent
,D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/DigitalAppWidgetProvider( 7157): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 7029): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 0:16:48
D/Weather.Utils( 7029): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7029): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7029): 2 : This is isUpdating : false
D/Weather_cast( 7029): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 7029): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 0:16:48
V/FormManager( 6943): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6943): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1036): Killing 2214:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  318): 2214 died, releasing its sessions
V/AudioFlinger(  318):  pid 1874 @ 0
V/AudioFlinger(  318):  pid 3349 @ 1
V/AudioFlinger(  318):  pid 3349 @ 2
,D/GCM     ( 2144): Connected
W/libprocessgroup( 1036): failed to open /acct/uid_10034/pid_2214/cgroup.procs: No such file or directory
,D/GCM     ( 2144): Message class com.google.f.a.a.p
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
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
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{1338f5f3 type 2 when 119120 com.android.providers.calendar} when 119120
,I/ActivityManager( 1036): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7258 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 7258): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7258): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@27ae4c7a
,D/CalendarProvider2( 7258): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7258): Created com.android.providers.calendar.CalendarAlarmManager@1e6f2007(com.android.providers.calendar.CalendarProvider2@27ae4c7a)
,D/CalendarProviderBroadcastReceiver( 7258): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7258): [IntentService] WakeLock acquire, start IntentSerivce
V/QRemote ( 6788): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6788): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:459
,D/CalendarProvider2( 7258): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7258): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7258): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 7258): (284) automatic index on view_events(_id)
D/CalendarProvider2( 7258): [IntentService] Release Lock
D/CalendarProvider2( 7258): CalendarProviderIntentService.onDestroy()
,I/ActivityManager( 1036): Killing 6764:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6764/cgroup.procs: No such file or directory
,I/GAV4    ( 7047): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1036): Killing 6728:com.android.settings/1000 (adj 15): empty #17
,I/jxcore-log( 6654): Test app app.js loaded
I/jxcore-log( 6654): 
,I/chromium( 6654): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6728/cgroup.procs: No such file or directory
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a43f954 added. We now have 1 listener(s)
,I/jxcore-log( 6654): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6654): 
I/jxcore-log( 6654): TAP version 13
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 1 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 2 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 3 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 4 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 5 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 6 should throw
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 7 should throw
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons no beacons returns null
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 8 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 9 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 10 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 11 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 12 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 13 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 14 (unnamed assert)
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 15 (unnamed assert)
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=516535973, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{18395061 type 2 when 131935 android} when 131935
D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=516535973 [*alarm*], flags=0x0
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{12eaf786 type 0 when 1454973418763 com.google.android.gms} when 1454973418763
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{1dee3874 type 0 when 1454973423289 com.android.vending} when 1454973423289
,I/EventLogService( 2336): Aggregate from 1454971618685 (log), 1454971618685 (data)
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6089): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6089): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6089): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 137973010576; DSPS: 4661800; Offset : -4307774994
,E/WifiStateMachine( 1036):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1036):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 157975602444; DSPS: 5317245; Offset : -4307777068
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{29c069d3 type 0 when 1454973446209 com.android.vending} when 1454973446209
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6089): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6089): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6089): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{2ae4227d type 2 when 167870 android} when 167870
,I/ActivityManager( 1036): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7324 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7324): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7324): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7324): Created application version: 3.2.35 (30235)
,I/BooksSync( 7324): Starting books sync
,D/BooksSync( 7324): started syncMyEbooks
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7324): Authentication error
E/BooksAccountManager( 7324): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7324): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7324): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7324): null auth token
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
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7324): Error response from books API: {
W/ApiaryClient( 7324):  "error": {
W/ApiaryClient( 7324):   "errors": [
W/ApiaryClient( 7324):    {
W/ApiaryClient( 7324):     "domain": "global",
W/ApiaryClient( 7324):     "reason": "required",
W/ApiaryClient( 7324):     "message": "Login Required",
W/ApiaryClient( 7324):     "locationType": "header",
W/ApiaryClient( 7324):     "location": "Authorization"
W/ApiaryClient( 7324):    }
W/ApiaryClient( 7324):   ],
W/ApiaryClient( 7324):   "code": 401,
W/ApiaryClient( 7324):   "message": "Login Required"
W/ApiaryClient( 7324):  }
W/ApiaryClient( 7324): }
W/ApiaryClient( 7324): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7324): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3967756083355923675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7324): Headers:
W/ApiaryClient( 7324): accept-encoding: [gzip]
W/ApiaryClient( 7324): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7324): gdata-version: 2
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7324): Authentication error
E/BooksAccountManager( 7324): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7324): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7324): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7324): null auth token
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
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
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7324): Error response from books API: {
W/ApiaryClient( 7324):  "error": {
W/ApiaryClient( 7324):   "errors": [
W/ApiaryClient( 7324):    {
W/ApiaryClient( 7324):     "domain": "global",
W/ApiaryClient( 7324):     "reason": "required",
W/ApiaryClient( 7324):     "message": "Login Required",
W/ApiaryClient( 7324):     "locationType": "header",
W/ApiaryClient( 7324):     "location": "Authorization"
W/ApiaryClient( 7324):    }
W/ApiaryClient( 7324):   ],
W/ApiaryClient( 7324):   "code": 401,
W/ApiaryClient( 7324):   "message": "Login Required"
W/ApiaryClient( 7324):  }
W/ApiaryClient( 7324): }
,W/ApiaryClient( 7324): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7324): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3967756083355923675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7324): Headers:
W/ApiaryClient( 7324): accept-encoding: [gzip]
W/ApiaryClient( 7324): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7324): gdata-version: 2
I/art     ( 1036): Explicit concurrent mark sweep GC freed 35324(1678KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 3.225ms total 218.759ms
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{e7f175c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2144): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2144): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2144): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2144): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2144): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7324): Authentication error
E/BooksAccountManager( 7324): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7324): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7324): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7324): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7324): null auth token
W/ApiaryClient( 7324): Error response from books API: {
W/ApiaryClient( 7324):  "error": {
W/ApiaryClient( 7324):   "errors": [
W/ApiaryClient( 7324):    {
W/ApiaryClient( 7324):     "domain": "global",
W/ApiaryClient( 7324):     "reason": "required",
W/ApiaryClient( 7324):     "message": "Login Required",
W/ApiaryClient( 7324):     "locationType": "header",
W/ApiaryClient( 7324):     "location": "Authorization"
W/ApiaryClient( 7324):    }
W/ApiaryClient( 7324):   ],
W/ApiaryClient( 7324):   "code": 401,
W/ApiaryClient( 7324):   "message": "Login Required"
W/ApiaryClient( 7324):  }
W/ApiaryClient( 7324): }
,W/ApiaryClient( 7324): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7324): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3967756083355923675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7324): Headers:
W/ApiaryClient( 7324): accept-encoding: [gzip]
W/ApiaryClient( 7324): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7324): gdata-version: 2
,E/BooksSync( 7324): Soft error: 
E/BooksSync( 7324): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7324): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3967756083355923675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7324): Headers:
E/BooksSync( 7324): accept-encoding: [gzip]
E/BooksSync( 7324): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7324): gdata-version: 2
E/BooksSync( 7324): 
E/BooksSync( 7324): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7324): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7324): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7324): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7324): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7324): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7324): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7324): {
E/BooksSync( 7324):  "error": {
E/BooksSync( 7324):   "errors": [
E/BooksSync( 7324):    {
E/BooksSync( 7324):     "domain": "global",
E/BooksSync( 7324):     "reason": "required",
E/BooksSync( 7324):     "message": "Login Required",
E/BooksSync( 7324):     "locationType": "header",
E/BooksSync( 7324):     "location": "Authorization"
E/BooksSync( 7324):    }
E/BooksSync( 7324):   ],
E/BooksSync( 7324):   "code": 401,
E/BooksSync( 7324):   "message": "Login Required"
E/BooksSync( 7324):  }
E/BooksSync( 7324): }
E/BooksSync( 7324): 
E/BooksSync( 7324): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7324): 	... 8 more
,E/BooksSync( 7324): Sync error
E/BooksSync( 7324): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7324): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3967756083355923675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7324): Headers:
E/BooksSync( 7324): accept-encoding: [gzip]
E/BooksSync( 7324): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7324): gdata-version: 2
E/BooksSync( 7324): 
E/BooksSync( 7324): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7324): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7324): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7324): 	,at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7324): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7324): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7324): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7324): {
E/BooksSync( 7324):  "error": {
E/BooksSync( 7324):   "errors": [
E/BooksSync( 7324):    {
E/BooksSync( 7324):     "domain": "global",
E/BooksSync( 7324):     "reason": "required",
E/BooksSync( 7324):     "message": "Login Required",
E/BooksSync( 7324):     "locationType": "header",
E/BooksSync( 7324):     "location": "Authorization"
E/BooksSync( 7324):    }
E/BooksSync( 7324):   ],
E/BooksSync( 7324):   "code": 401,
E/BooksSync( 7324):   "message": "Login Required"
E/BooksSync( 7324):  }
E/BooksSync( 7324): }
E/BooksSync( 7324): 
E/BooksSync( 7324): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7324): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7324): 	... 8 more
I/BooksSync( 7324): Finished books sync
I/ActivityManager( 1036): Killing 7183:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167870, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_7183/cgroup.procs: No such file or directory
,I/GAV2    ( 7324): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 177978140873; DSPS: 5972688; Offset : -4307771729
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1036): battery changed pluggedType: 2
D/HeadsetStateMachine( 3795): Disconnected process message: 10, size: 0
D/LEDHandler( 1980): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1980): Battery Level Remaining: 100%
D/LEDHandler( 1980): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4282): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{305da193 type 0 when 1454973476118 com.android.vending} when 1454973476118
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6089): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6089): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6089): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=516535973, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{343f143d type 2 when 197948 android} when 197948
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 197983644408; DSPS: 6628229; Offset : -4307790598
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=516535973 [*alarm*], flags=0x0
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{1b346432 type 2 when 186565 com.google.android.gms} when 186565
,V/AlarmManager( 1036): RTC_WAKEUP set : Alarm{c434300 type 0 when 1454973499214 com.android.vending} when 1454973499214
,V/AlarmManager( 1036): ELAPSED_WAKEUP set : Alarm{90db739 type 2 when 211996 android} when 211996
V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,I/VacuumService( 2144): Vacuum at: now=1454973507742 tag=VacuumService
,I/GoogleURLConnFactory( 2144): Using platform SSLCertificateSocketFactory
,W/Uploader( 2144): No account for auth token provided
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2144): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2144): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2144): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2144): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2144): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 217985335598; DSPS: 7283644; Offset : -4307777432
I/art     ( 2144): Explicit concurrent mark sweep GC freed 41179(2MB) AllocSpace objects, 15(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.036ms total 63.188ms
,D/Finsky  ( 6089): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6089): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6089): [1] 5.onFinished: Giving up after 6 failures.
W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144): No account for auth token provided
,W/Uploader( 2144):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 237987089653; DSPS: 7939061; Offset : -4307764468
,D/PowerManagerServiceEx( 1036): acquireWakeLockInternal: lock=516535973, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,D/[Concierge]Service( 2618): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/PowerManagerServiceEx( 1036): releaseWakeLockInternal: lock=516535973 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 257989369854; DSPS: 8594496; Offset : -4307773164
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # multiplex can send data
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 16 String should be length:200
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # enqueue and run in order
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 17 firstPromise setTimeout
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 18 firstPromise result
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 19 firstPromise testValue
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 20 secondPromise setTimeout
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 21 secondPromise result
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 22 secondPromise testValue
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 23 thirdPromise in promise
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 24 thirdPromise result
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 25 thirdPromise testValue
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # basic
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 26 sane
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # another
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 27 sane
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 28 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 29 null
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 30 (unnamed assert)
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 31 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 32 should not throw
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 33 (unnamed assert)
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 34 (unnamed assert)
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 35 should not throw
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 36 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 37 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 38 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # failed to get mobile documents path
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 39 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 40 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 41 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 42 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #init should register the networkChanged event
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 43 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on null device name
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 44 should throw
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 45 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 46 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 47 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on negative port
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 48 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should throw on too large port
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 49 should throw
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 50 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 51 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 52 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 53 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 54 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 55 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 56 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 57 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 58 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 59 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 60 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 61 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 62 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 63 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 64 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 65 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 66 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 67 should be equal
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 68 should be equal
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6654): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe0f0fd added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556230.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556230.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556230.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3795): [BTUI] createSocketChannel FD=84 mFd=82
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556230.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556230.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556230.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@87116730 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@87116730 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363233302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363233302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363233301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363233301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556230.6654, mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/jxcore-log( 6654): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363233301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363233301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6654): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d09ff9 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556364.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556364.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556364.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556364.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556364.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556364.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@30c8dba0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@30c8dba0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363336342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363336342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363336341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363336341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556364.6654, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6654): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363336341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363336341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 6654): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 c,nt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@287242b5 added. We now have 4 listener(s)
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556425.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556425.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556425.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556425.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556425.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556425.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d942d824 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d942d824 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363432352e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363432352e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363432351f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363432351f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 6654): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556425.6654, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDe,viceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363432351f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363432351f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
,I/jxcore-log( 6654): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b515531 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556483.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556483.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556483.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556483.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556483.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556483.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2063f01c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2063f01c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363438332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363438332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363438331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363438331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FI,ND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556483.6654, mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 6654): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6654): stop
D/LGWifiP2pService( 1036): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btco,nnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363438331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363438331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/LGWifiP2pService( 1036): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/jxcore-log( 6654): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org,.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d35136d added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556542.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556542.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556542.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556542.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556542.6654","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556542.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7855a24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7855a24 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363534322e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363534322e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556542.6654, mode: WIFI
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363534321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363534321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6654): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregr,oundUser=0
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363534321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363534321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
I/jxcore-log( 6654): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c7969 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556610.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556610.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556610.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556610.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556610.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556610.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4b96cac target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4b96cac target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363631302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363631302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363631301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363631301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556610.6654, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 6654): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btcon,nectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
I/jxcore-log( 6654): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
D/LGWifiP2pService( 1036): InactiveState{ when=-8ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-8ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
,D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363631301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363631301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14fa4325 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
,D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556713.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556713.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556713.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c987c2a4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c987c2a4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363731332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363731332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556713.6654, mode: WIFI
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
,I/jxcore-log( 6654): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Cannot restart, because not initialized
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-,STOPPED 
I/jxcore-log( 6654): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b30eca1 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556772.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556772.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556772.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
,W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556772.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556772.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556772.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@995523da target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@995523da target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
,D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363737322e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363737322e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363737321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363737321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556772.6654, mode: WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 6654): ok 83 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6654): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
,I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED,
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363737321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363737321f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
,I/jxcore-log( 6654): ok 84 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	,Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	,Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	,Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ceb1dd added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556884.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556884.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556884.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556884.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556884.6654","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556884.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@14362252 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@14362252 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363838342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363838342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363838341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556884.6654, mode: WIFI
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363838341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/jxcore-log( 6654): ok 85 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
I/io.jxcore.node.ConnectionHelper( 6654): stop
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363838341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363838341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6654): ok 86 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 665,4): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22898ed9 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556990.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556990.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556990.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973556990.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973556990.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973556990.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5b0d6956 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5b0d6956 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363939302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333535363939302e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363939301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363939301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973556990.6654, mode: WIFI
I/jxcore-log( 6654): ok 87 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
I/wpa_supplicant( 2688): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1036): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1980): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
,D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler },
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363939301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333535363939301f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/jxcore-log( 6654): ok 88 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1036): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1036): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup,
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6654): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Cannot start, because not initialized
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367b3f95 added. We now have 12 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973563713.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973563713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973563713.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973563713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973563713.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973563713.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e77245a8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e77245a8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333536333731332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333536333731332e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536333731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536333731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973563713.6654, mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/jxcore-log( 6654): ok 89 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 90 Cannot call startBroadcasting twice
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536333731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536333731331f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6654): ok 91 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 277991734638; DSPS: 9249933; Offset : -4307758207
,I/jxcore-log( 6654): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6654): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c9d4011 added. We now have 13 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973568444.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973568444.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973568444.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973568444.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973568444.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973568444.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@93a2631c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@93a2631c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333536383434342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333536383434342e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536383434341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536383434341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973568444.6654, mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
,D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/jxcore-log( 6654): ok 92 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 6654): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 6654): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 6654): ok 93 Should not connect to a bad peer
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536383434341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333536383434341f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6654): ok 94 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Cannot start, because not initialized
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6654): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6654): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e04cc4d added. We now have 14 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6654): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973572208.6654
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973572208.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): start: OK
I/io.jxcore.node.ConnectionHelper( 6654): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973572208.6654, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6654): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Waiting for incoming connections...
,D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6654): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1454973572208.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: {"pi":"58:3F:54:73:64:C0","pn":"1454973572208.6654","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1454973572208.6654","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@78b3a76a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@78b3a76a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState add service
D/LGWifiP2pService( 1036): add a new client
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333537323230382e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435343937333537323230382e36363534222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333537323230381f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1036): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333537323230381f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Starting P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1980): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1036): P2P_FIND 120: returned true
D/LGWifiP2pService( 1036): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1454973572208.6654, mode: WIFI
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2688): P2P-FIND-STOPPED 
D/WfdsMonitor( 1980): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1036): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1036): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): P2P device discovery stopped successfully
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: RESTARTING
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
,D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6654): start: OK
I/jxcore-log( 6654): ok 95 Should be able to call startBroadcasting without error
I/jxcore-log( 6654): 
D/io.jxcore.node.ConnectionHelper( 6654): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.PeerAndConnectionModel( 6654): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.PeerAndConnectionModel( 6654): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6654): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 6654): ok 96 Disconnect should fail to a non-existant peer 
I/jxcore-log( 6654): 
I/io.jxcore.node.ConnectionHelper( 6654): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6654): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6654): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6654): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6654): stop: Stopping services
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1036): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333537323230381f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1036): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435343937333537323230381f36363534222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1036): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6654): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1036): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1036): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6654): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6654): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6654): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6654): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6654): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6654): ok 97 Should be able to call stopBroadcasting without error
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 98 host address should match
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 99 port should match
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 100 peer should be available
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 101 peer should be unavailable
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 102 when receiving the first byebye, the second USN should not be set yet
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 103 USN should have changed from the first one
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 104 when receiving the second byebye, the first USN should be already set
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # messages with invalid location or USN should be ignored
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 105 should not have emitted with invalid port
I/jxcore-log( 6654): 
I/jxcore-log( 6654): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 106 should not have emitted with invalid USN
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6654): start: Cannot start, because not initialized
,I/jxcore-log( 6654): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 107 irrelevant messages should be ignored
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 108 relevant messages should not be ignored
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 109 messages from this device should be ignored
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #start should fail if called twice in a row
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 110 specific error should be received
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 6654): 
,E/jxcore-log( 6654): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 111 specific error should be received
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 6654): 
,E/jxcore-log( 6654): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 112 specific error expected
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 113 server should respond with code 200
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #stop can be called multiple times in a row
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 114 should be in stopped state
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 115 should still be in stopped state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 116 should be in listening state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 117 should still be in listening state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 118 should not be in listening state
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 119 should still not be in listening state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 120 should not be in advertising state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ok 121 should still not be in advertising state
I/jxcore-log( 6654): 
I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # setup
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # functions are run from a queue in the right order
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): ok 122 call order must match
I/jxcore-log( 6654): 
,I/jxcore-log( 6654): # teardown
I/jxcore-log( 6654): 
I/jxcore-log( 6654): Tests Complete
I/jxcore-log( 6654): 
,I/chromium( 6654): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6654): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 6654): 
I/jxcore-log( 6654): Toggling radios to false
I/jxcore-log( 6654): 
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d701747 mBinding = false
,I/chromium( 6654): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
D/BluetoothManagerService( 1036): Message: 2
D/BluetoothManagerService( 1036): Sending off request.
D/LGBluetoothServiceAdapter( 3795): [BTUI] Precleanup
D/BluetoothAdapterState( 3795): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3795): Setting state to 13
I/BluetoothAdapterState( 3795): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3795): onBluetoothDisable()
I/BluetoothAdapterState( 3795): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3795): Scan Mode:20
,D/BluetoothAdapterState( 3795): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3795): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothPbapService( 3795): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3795): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3795): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3795): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3795): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3795): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3795): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3795): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3795): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
E/BtOppRfcommListener( 3795): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3795): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3795): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,W/bt-btif ( 3795): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3795): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3795): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3795): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3795): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 12 -> 13
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7530 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1036): setWifiEnabled: false pid=6654, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: false pid=6654, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothAPIService( 1980): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothMapService( 3795): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3795): STATE_TURNING_OFF
V/BluetoothMapService( 3795): Handler(): got msg=4
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothMapService( 3795): MAP Service closeService in
D/BluetoothMapMasInstance( 3795): MAP Service shutdown
D/LGBluetoothMapAdapter( 3795): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3795): MAP Service closeService out
V/BtOppService( 3795): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3795): stopping Accept Thread
V/BtOppRfcommListener( 3795): close mBtServerSocket
V/BtOppRfcommListener( 3795): waiting for thread to terminate
I/BtOppRfcommListener( 3795): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3795): done waiting for thread to terminate
E/WifiStateMachine( 1036):  ConnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6654): Radios toggled
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ****TEST TOOK:  ms ****
I/jxcore-log( 6654): 
I/jxcore-log( 6654): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6654): 
E/WifiStateMachine( 1036):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 1036):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7564 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
V/BtOppService( 3795): onDestroy
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1036): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothOppAdapter( 3795): [BTUI] LGBluetoothOppAdapter cleanup
I/jxcore-log( 6654): Toggling radios to false
I/jxcore-log( 6654): 
V/NativeCrypto( 2144): Read error: ssl=0xaa76a200: I/O error during system call, Connection timed out
,V/NativeCrypto( 2144): SSL shutdown failed: ssl=0xaa76a200: I/O error during system call, Broken pipe
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d701747 mBinding = false
D/BluetoothManagerService( 1036): Message: 2
D/BluetoothManagerService( 1036): Sending off request.
D/LGBluetoothServiceAdapter( 3795): [BTUI] Precleanup
D/BluetoothAdapterService( 3795): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1036): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1036): setWifiEnabled: false pid=6654, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: false pid=6654, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 6654): Radios toggled
I/jxcore-log( 6654): 
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e29c2fb
D/LGWifiP2pService( 1036): P2pDisablingState
D/LGWifiP2pService( 1036): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): p2p socket connection lost
D/LGWifiP2pService( 1036): P2pDisabledState
D/WifiHS20( 1036): hidePasspointNotification off =false
V/WfdStateTracker( 1980): handleWifiStateChangedEvent: 0
V/WfdStateTracker( 1980): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1980): WifiP2pState is changed : false
,D/WfdsService( 1980): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1980): Set the WFDS Monitor: false
D/WfdsMonitor( 1980): WFDS Monitor is stopped
D/WfdsService( 1980): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1980): Received on exit socket, terminate
E/CtrlSupplicant( 1980): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1980): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1980): WfdsMonitorThread is received the interrupt - closing
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WfdsSession:Controller( 1980): DefaultState - msg [9441355] is not handled
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/WfdsService( 1980): DefaultState - msg [9445378] is not handled
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1036): SCAN_AVAILABLE : 1
D/RttService( 1036): SCAN_AVAILABLE : 1
D/WifiScanningService( 1036): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1036): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1036): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,D/CommandListener(  314): Clearing all IP addresses on wlan0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1036): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1036): doBoolean: TERMINATE
D/WifiNative-p2p0( 1036): TERMINATE: returned true
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1980): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
W/ResourcesManager( 7564): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ResourcesManager( 7564): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/ResourcesManager( 7564): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7564): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7564): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7564): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisi,oningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
,E/ActivityThread( 7530): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7530): No ProfileInfo entries
I/LG Account v2.2( 7530): isEnabled: false
I/Feature ( 7530): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7530): [Lifetracker]Country: EU
I/Feature ( 7530): [Lifetracker]Operator: OPEN
I/Feature ( 7530): [Lifetracker]Ranking support: false
I/Feature ( 7530): [Lifetracker]Comfort support: false
I/Feature ( 7530): [Lifetracker]Accessory: true
I/Feature ( 7530): [Lifetracker]Health device: true
I/Feature ( 7530): [Lifetracker]Extra Pedometer: false
I/Feature ( 7530): [Lifetracker]Blood glucose device: false
I/Feature ( 7530): [Lifetracker]Device Number: 3
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7594 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 7204:com.android.calendar/u0a13 (adj 15): empty #17
D/AndroidRuntime( 7580): 
D/AndroidRuntime( 7580): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7580): CheckJNI is OFF
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2688): monitor socket send errors count : 1
I/wpa_supplicant( 2688): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1980-2\x00 that cannot receive messages
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1036): Dropping event because (p2p0) is stopped
D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-143ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2688): USIM:  scard_deinit function
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=285195
E/WifiStateMachine( 1036):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=285195
E/WifiStateMachine( 1036):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=285195  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=285196  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/Tethering( 1036): InitialState.processMessage what=4
E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_ON_QUIT 0 0
,D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
W/libprocessgroup( 1036): failed to open /acct/uid_10013/pid_7204/cgroup.procs: No such file or directory
E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 7594): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7594): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7594): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 7564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1036): Killing 6876:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/AndroidRuntime( 7580): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1036):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 63 0
,W/PackageSettings( 1036): Skipping PackageSetting{3c34cff5 com.example.hello/10319} due to missing metadata
,W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6876/cgroup.procs: No such file or directory
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1036): Killing 6654:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,V/WiFiOffLoadBroadcast( 7564): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7564): LgDataFeature() Constructor: none
D/LgDataFeature( 7564): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7564): MCCMNC not supported: null
,D/BluetoothManagerService( 1036): Message: 20
,D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@240ce0e3:true
I/WindowState( 1036): WIN DEATH: Window{66d55f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1036): Client connection lost with reason: 4
,D/InputDispatcher( 1036): Window went away: Window{66d55f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{21686eb3 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  339): DFP En is all cleared set to be enabled
,D/WifiOffDelayIfNotUsed( 1036): stopMonitoring
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
W/ActivityManager( 1036): Spurious death for ProcessRecord{18931ae0 6654:com.test.thalitest/u0a311}, curProc for 6654: null
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/[LGHome]EVENT( 2089): [Launcher.java:5338:onStart()]onStart
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{21686eb3 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{21686eb3 u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{8e42484 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1980): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1980): topRunningActivity=ActivityInfo{e5bf46d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
V/BluetoothPbapReceiver( 3795): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3795): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3795): ***********state = 13
I/[LGHome]EVENT( 2089): [Launcher.java:903:onResume()]onResume
V/BluetoothPbapReceiver( 3795): ***********Calling start service!!!! with action = null
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2050): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3732): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
D/WfdsService( 1980): Supplicant Connection state is changed : false
D/WfdsService( 1980): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1980): Set the WFDS Monitor: false
V/WfdStateTracker( 1980): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsMonitor( 1980): WFDS Monitor is stopped
W/Settings( 1839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
,D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] [+] updateMediaPlayerInfo
,D/BluetoothManagerService( 1036): Message: 30
W/System.err( 4505): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4505): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4505): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4505): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4505): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4505): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4505): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4505): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4505): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4505): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1036): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7629 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[SystemUI]QSlideListController( 1468): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1926): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2089): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2089): [Launcher.java:1056:onResume()]onResume end
,D/SplitUIManager( 1892): split_name #11 / not available #0
D/SplitUIService( 1892): removed split : 
I/[LGHome]EVENT( 2089): [Launcher.java:1114:onPause()]onPause
I/art     ( 4563): Explicit concurrent mark sweep GC freed 15240(885KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 631us total 86.080ms
D/BluetoothManagerService( 1036): Message: 30
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1468): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1926): notifyUserLog: 1000004
D/LocalBluetoothProfileManager( 7564): Adding local MAP profile
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/BluetoothMap( 7564): Create BluetoothMap proxy object
D/BluetoothManagerService( 1036): Message: 30
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
,D/WallpaperManager( 2089): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2dc7953d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIManager( 1892): split_name #11 / not available #0
I/SplitUIService( 1892): split app #11
D/BluetoothManagerService( 1036): Message: 30
D/LocalBluetoothProfileManager( 7564): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7564):  get() - isFeatureLoaded : false
I/art     ( 1036): Explicit concurrent mark sweep GC freed 62424(3MB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.535ms total 224.158ms
I/art     ( 1036): WaitForGcToComplete blocked for 222.918ms for cause Explicit
I/LockScreenSettings( 7629): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/bt-btif ( 3795): ag scb idx 1 not allocated
E/bt-btif ( 3795): BTA AG is already disabled, ignoring ...
D/bt_hci_bdroid( 3795): cleanup
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3795): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3795): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3795): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3795): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3795): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3795): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3795): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3795): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3795): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3795): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3795): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 3795): LPM is already off!!!
,I/bt_userial_mct( 3795): exiting userial_read_thread
D/bt_userial_mct( 3795): Leaving userial_evt_read_thread()
D/bt_userial_mct( 3795): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3795): hw_epilog_process
D/bt_hci_bdroid( 3795): cleanup Finalizing cleanup
D/bt_userial_mct( 3795): userial_close
E/bt_userial_mct( 3795): pthread_join() FAILED result:3
I/bt_vendor( 3795): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/LGBluetoothUserBindClient( 7564): [BTUI] initUserBindClient
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/administrator( 1036): Handling package changes for user 0
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
I/[LGHome]EVENT( 2089): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,W/ContextImpl( 7564): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/DockEventReceiver( 7564): finishStartingService: stopping service
,W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] [-] updateMediaPlayerInfo
V/BluetoothPbapService( 3795): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3795): state: 13
V/BluetoothPbapService( 3795): Pbap Service closeService in
V/BluetoothPbapService( 3795): successfully stopped pbap service
V/BluetoothPbapService( 3795): Pbap Service closeService out
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
V/BluetoothPbapService( 3795): Pbap Service onDestroy
V/BluetoothPbapService( 3795): Pbap Service closeService in
V/BluetoothPbapService( 3795): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3795): [BTUI] cleanup
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
,D/BluetoothInputDevice( 7564): Proxy object connected
D/KeyguardModel( 1468): handleShortcutListChanged...
D/HidProfile( 7564): Bluetooth service connected
D/BluetoothPan( 7564): BluetoothPAN Proxy object connected
D/PanProfile( 7564): Bluetooth service connected
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/BluetoothMap( 7564): Proxy object connected
D/MapProfile( 7564): Bluetooth service connected
D/BluetoothMap( 7564): getConnectedDevices()
,D/BluetoothMap( 7564): Bluetooth is Not enabled
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
D/BluetoothPbap( 7564): Proxy object connected
D/PbapServerProfile( 7564): Bluetooth service connected
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothPbap( 7564): Proxy object disconnected
D/PbapServerProfile( 7564): Bluetooth service disconnected
D/LGBluetoothUserBindClient( 7564): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7564): [BTUI] cancel All Notification
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/BluetoothPermissionRequest( 7564): onReceive
,D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
D/LGBluetoothAuthorization( 7564): [BTUI] cancel All Notification
I/ActivityManager( 1036): Killing 6909:com.lge.email/u0a23 (adj 15): empty #17
,I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2089): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/bt_hci_bdroid( 3795): set_power 0
I/bt_vendor( 3795): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3795): bluetooth satus is on
,I/bt_vendor( 3795): bt-vendor : resetting BT status
I/bt_vendor( 3795): Starting hciattach daemon
I/bt_vendor( 3795): try to set false
I/bt_vendor( 3795): Starting hciattach daemon
I/bt_vendor( 3795): try to set false
I/bt_vendor( 3795): cleanup
I/GKI_LINUX( 3795): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3795): GKI_exit_task 0 done
,I/GKI_LINUX( 3795): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3795): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/KeyguardModel( 1468): handleShortcutListChanged...
D/HeadsetService( 3795): Received stop request...Stopping profile...
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [1]
I/LGBluetoothHfpAdapter( 3795): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3795): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : state:0 event:1
D/HeadsetStateMachine( 3795): Exit Disconnected: -1
D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : this is not treated
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothHeadset( 1874): Proxy object disconnected
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6909/cgroup.procs: No such file or directory
D/BluetoothHeadset( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1874): Proxy object disconnected
D/[Concierge]Service( 2618): onStartCommand(). Type : 8
D/[Concierge]Service( 2618): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2089): change position of spinner
D/[Concierge]Service( 2618): Update widget ID : 11
D/A2dpService( 3795): Received stop request...Stopping profile...
D/A2dpStateMachine( 3795): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3795): [BTUI] cleanup
,I/ActivityManager( 1036): Killing 6943:com.lge.formmanager/u0a26 (adj 15): empty #17
W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 1036): Explicit concurrent mark sweep GC freed 11557(642KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.463ms total 276.686ms
,D/LGBluetoothResetSettingReceiver( 7564): return without doing reset settings.
,W/libprocessgroup( 1036): failed to open /acct/uid_10026/pid_6943/cgroup.procs: No such file or directory
,I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{210c184 u0 com.lge.launcher2/.Launcher t3} time:286124
I/[Concierge]WidgetView( 2089): initWebView(). Time : 1454973576180
,D/[Concierge]Service( 2618): onStartCommand(). Type : 0
D/LGBluetoothA2dpAdapter( 3795): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3795): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothA2dp( 1036): Proxy object disconnected
D/AudioService( 1036): onServiceDisconnected: Bluetooth profile: 2
D/HeadsetStateMachine( 3795): Unbinding service...
D/HeadsetPhoneState( 3795): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3795): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3795): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3795): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3795): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3795): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3795): [BTUI] LGBluetoothHfpAdapter cleanup
V/BluetoothOppReceiver( 3795): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3795): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3795): [BTUI] cancel opp active transfer file notification
D/HidService( 3795): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/BluetoothInputDevice( 7564): Proxy object disconnected
D/HidProfile( 7564): Bluetooth service disconnected
,D/HealthService( 3795): Received stop request...Stopping profile...
D/BluetoothAdapterState( 3795): Stopping profile services that were post enabled
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
I/BluetoothA2dpServiceJni( 3795): cleanupNative
I/GKI_LINUX( 3795): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3795): GKI_exit_task 2 done
I/GKI_LINUX( 3795): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 3795): Received stop request...Stopping profile...
,D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
D/BtGatt.DebugUtils( 3795): handleDebugAction() action=null
D/BtGatt.GattService( 3795): Received stop request...Stopping profile...
D/BtGatt.GattService( 3795): stop()
D/BtGatt.AdvertiseManager( 3795): advertise clients cleared
D/BluetoothPan( 7564): BluetoothPAN Proxy object disconnected
D/PanProfile( 7564): Bluetooth service disconnected
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
I/PCSuite ( 7594): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7594): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7594): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/BluetoothHidServiceJni( 3795): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3795): Cleaning up Bluetooth GID callback object
I/[Concierge]WebView( 2089): Return exist ConciergeWebView. Reuse : 363512134
D/[Concierge]WidgetView( 2089): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/BluetoothMapService( 3795): Received stop request...Stopping profile...
D/BluetoothMapService( 3795): stop()
D/BluetoothMapEmailAppObserver( 3795): deinitObservers()
D/BluetoothMapEmailAppObserver( 3795): removeReceiver()
D/BluetoothAdapterService( 3795): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b226f5d
I/[LgeWidgetLib]ExtViewHost( 2089): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@36794a8e
V/BluetoothFtpReceiver( 3795): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
V/BluetoothFtpReceiver( 3795): BluetoothFtpReceiver Start Service
V/WiFiOffLoadBroadcast( 7564): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/BluetoothHealthServiceJni( 3795): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3795): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3795): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3795): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3795): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3795): Handler(): got msg=4
,D/BluetoothMapService( 3795): MAP Service closeService in
D/LGBluetoothMapAdapter( 3795): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3795): MAP Service closeService out
D/BluetoothMapService( 3795): cleanup()
D/BluetoothMapService( 3795): MAP Service closeService in
D/LGBluetoothMapAdapter( 3795): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3795): MAP Service closeService out
D/BluetoothAdapterState( 3795): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3795): Setting state to 10
I/BluetoothAdapterState( 3795): Bluetooth adapter state changed: 13-> 10
V/BluetoothFtpService( 3795): Ftp Service onStartCommand
V/BluetoothFtpService( 3795): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3795): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3795): Shutdown
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1036): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothPan( 7564): onBluetoothStateChange on: false
D/BluetoothInputDevice( 7564): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3795): Entering OffState
V/BluetoothFtpService( 3795): successfully stopped ftp service
D/BluetoothPbap( 7564): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 3795): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3795): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3795): SapReceiver onReceive 
D/BluetoothA2dp( 1036): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 3795): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3795):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3795): Calling SAP service start service with action = null
D/BluetoothMap( 7564): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
V/BluetoothFtpService( 3795): Ftp Service onDestroy
V/BluetoothFtpService( 3795): Ftp Service closeService
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
,I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/WiFiOffLoadBroadcast( 7564): MCCMNC not supported: null
D/[Concierge]WidgetView( 2089): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2089): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/ActivityManager( 1036): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7659 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3795): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3795): state: 13
V/BluetoothSapService( 3795): Stopping SAP server process
D/BluetoothHeadset( 1036): onBluetoothStateChange: up=false
V/BluetoothSapService( 3795): Sap Service closeSapService in
D/BluetoothManagerService( 1036): Calling onBluetoothServiceDown callbacks
V/BluetoothSapService( 3795): Close listen Socket : 
D/BluetoothManagerService( 1036): Broadcasting onBluetoothServiceDown() to 7 receivers.
V/BluetoothSapService( 3795): Close rfcomm Socket : 
V/BluetoothSapService( 3795): Close sapd  Socket : 
W/[Concierge]WidgetView( 2089): Widget kill message received. Destory myself. My : 1454973317634, New one : 1454973576180
D/[Concierge]WidgetView( 2089): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2089): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
V/BluetoothSapService( 3795): Sap Service closeSapService out
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/BluetoothSapService( 3795): Sap Service onDestroy
V/BluetoothSapService( 3795): Sap Service closeSapService in
V/BluetoothSapService( 3795): Close listen Socket : 
V/BluetoothSapService( 3795): Close rfcomm Socket : 
V/BluetoothSapService( 3795): Close sapd  Socket : 
V/BluetoothSapService( 3795): Sap Service closeSapService out
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
D/BluetoothManagerService( 1036): Calling onQBluetoothServiceDown callbacks
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/BluetoothManagerService( 1036): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1036): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d701747 mBinding = false
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/BluetoothManagerService( 1036): Sending unbind request.
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1980): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1980): Message: 2
D/LGBluetoothAPIService( 1980): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1aee78a2 mBinding = false
D/LGBluetoothAPIService( 1980): Sending unbind request.
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1468): 278519679: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1468): 278519679: getState() :  mService = null. Returning STATE_OFF
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/AndroidRuntime( 7580): Shutting down VM
I/PCSuite ( 7594): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7594): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7594): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/GKI_LINUX( 3795): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3795): GKI_exit_task 1 done
I/GKI_LINUX( 3795): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3795): cleanupNative: return from cleanup
I/art     ( 3795): --- WEIRD: removing null entry 246
W/art     ( 3795): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3795): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3795): [BTUI] unregister observer for LG device name DB
D/LGBluetoothFeatureConfig( 7564): isPrivacyLogsEnabled : true
I/art     ( 3795): System.exit called, status: 0
I/AndroidRuntime( 3795): VM exiting with result code 0, cleanup skipped.
,E/LGBluetoothEventManager( 7564): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7564): [BTUI] clear device connection state
V/WiFiOffLoadBroadcast( 7564): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 7659): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/WiFiOffLoadBroadcast( 7564): MCCMNC not supported: null
,V/AudioFlinger(  318): 3795 died, releasing its sessions
,V/AudioFlinger(  318):  pid 1874 @ 0
V/AudioFlinger(  318):  pid 3349 @ 1
V/AudioFlinger(  318):  pid 3349 @ 2
D/LGBluetoothUserBindClient( 7564): [BTUI] onServiceDisconnected
E/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2089): Timeline: Activity_idle id: android.os.BinderProxy@39aaab51 time:286326
,I/ActivityManager( 1036): Process com.android.bluetooth (pid 3795) has died
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
D/QRemote ( 6788): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6788): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/AuthorizationBluetoothService( 2144): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/QRemote ( 6788): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ContextImpl( 7564): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7679 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/DockEventReceiver( 7564): finishStartingService: stopping service
I/ActivityManager( 1036): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7696 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6985:com.android.chrome/u0a57 (adj 15): empty #17
I/art     (  346): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 12.477ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 225us total 10.736ms
I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.524ms
,I/chromium( 2089): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/libprocessgroup( 1036): failed to open /acct/uid_10057/pid_6985/cgroup.procs: No such file or directory
D/PCSuite ( 7594): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7564): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/ResourcesManager( 7696): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7696): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7696): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7696): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/WiFiOffLoadBroadcast( 7564): MCCMNC not supported: null
I/GBoardtInterface( 2089): onReloaded()
,D/BluetoothAdapterApp( 7696): Loading JNI Library
I/GBoardWebViewClient( 2089): onPageFinished url:file:///android_asset/www/main.html
D/UsbSettingsReceiver( 7564): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7564): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7564): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7564): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/FormManager( 7679): Network not available. Please check & try again.
D/UsbSettingsReceiver( 7564): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/FormManager( 7679): Network unavailable.
D/ActionManagerService( 1926): notifyUserLog: 1000001
,D/BluetoothAdapterApp( 7696): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@27ae4c7a Instance Count = 1
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onEvent() : ACTION_BOARD_ENABLED
V/FormManager( 7679): Network unavailable.
,D/BluetoothAdapterApp( 7696): onCreate
D/UsbSettingsControl( 7564): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7564): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7564): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7564): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7564): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7564): [AUTORUN] setTetherStatus() : status=false
D/ActionManagerService( 1926): notifyUserLog: 1000001
D/PostponalbeReceiver( 6292): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/BoardContentProvider( 3732): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 3732): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3732): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3732): onSettingEvent() : GBoard On - add scheduler - 0
D/ProfileConfigQcom( 7696): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7696): Adding HeadsetService
D/ProfileConfigQcom( 7696): [BTUI] A2dpService is supported
,D/ProfileConfigQcom( 7696): Adding A2dpService
D/ProfileConfigQcom( 7696): [BTUI] HidService is supported
D/ProfileConfigQcom( 7696): Adding HidService
D/ProfileConfigQcom( 7696): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7696): Adding HealthService
D/LGBluetoothFeatureConfig( 7696): isSupportPan() :  mTargetOp=OPEN
I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7721 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 7008:com.lge.drmservice/u0a62 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10062/pid_7008/cgroup.procs: No such file or directory
,D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppUp4:AppBoxCP( 7721): onCreate
,W/AppUp4:DB( 7721):  [AppBoxDatabaseHelper] construct
,E/SQLiteDatabase( 7721): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 7721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7721): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7721): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7721): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 7721): FATAL EXCEPTION: main
E/AndroidRuntime( 7721): Process: com.lge.appbox.client, PID: 7721
E/AndroidRuntime( 7721): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( ,7721): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7721): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7721): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7721): 	... 11 more

```
