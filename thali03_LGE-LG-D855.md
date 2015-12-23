#### Test 543122980a88295_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
W/ApiaryClient( 7043): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6154805012459151767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
E/BooksSync( 7043): Soft error: 
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6154805012459151767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
E/BooksSync( 7043): Sync error
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6154805012459151767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
I/BooksSync( 7043): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 298365, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/AndroidRuntime( 7199): 
D/AndroidRuntime( 7199): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7199): CheckJNI is OFF
D/AndroidRuntime( 7199): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{2b3c350f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{2b3c350f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7219 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7199): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1860): Display #0 changed.
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{1349eb5 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{c0e94a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7219): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7219): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7219): Loading: webviewchromium
I/LibraryLoader( 7219): Time to load native libraries: 3 ms (timestamps 2956-2959)
I/LibraryLoader( 7219): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7219): Binding Chromium to main looper Looper (main, tid 1) {38032ba5}
I/LibraryLoader( 7219): Expected native library version number "",actual native library version number ""
I/chromium( 7219): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7219): Initializing chromium process, renderers=0
W/art     ( 7219): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7219): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7219): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7219): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  326): registerClient() client 0xb100dde0, uid 10311
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9ad121:true
I/Adreno-EGL( 7219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7219): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7219): Build Date: 12/12/14 금
I/Adreno-EGL( 7219): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7219): Remote Branch: 
I/Adreno-EGL( 7219): Local Patches: 
I/Adreno-EGL( 7219): Reconstruct Branch: 
W/chromium( 7219): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7219): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7219): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7219): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7219): CordovaWebView is running on device made by: LGE
W/art     ( 7219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7219): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7219): Render dirty regions requested: true
I/OpenGLRenderer( 7219): Initialized EGL, version 1.4
D/OpenGLRenderer( 7219): Enabling debug mode 0
D/Atlas   ( 7219): Validating map...
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{1967599c u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1038): check instance of lgWin Window{c8c1493 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7219): LgDataFeature() Constructor: none
D/LgDataFeature( 7219): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7fbda4f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1456): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 7219): Timeline: Activity_idle id: android.os.BinderProxy@3bcf4815 time:303430
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +656ms (total +751ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{1967599c u0 com.test.thalitest/.MainActivity t4} time:303431
D/JsMessageQueue( 7219): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7219): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7219): 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 7219): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435097856
D/JX-Cordova( 7219): jxcore cordova android initializing
W/jxcore-log( 7219): Initializing JXcore engine
W/jxcore-log( 7219): JXcore engine is ready
,W/jxcore-log( 7219): Starting JXcore engine
W/.test.thalitest( 7219): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7414]" dev="sockfs" ino=7414 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7219): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 7219): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8503]" dev="sockfs" ino=8503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7219): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7219): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[35233]" dev="sockfs" ino=35233 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7219): Background sticky concurrent mark sweep GC freed 124123(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 2.261ms total 133.255ms
,W/jxcore-log( 7219): Platform android
W/jxcore-log( 7219): 
W/jxcore-log( 7219): Process ARCH arm
W/jxcore-log( 7219): 
,I/jxcore-log( 7219): JXcore Cordova bridge is ready!
I/jxcore-log( 7219): 
W/jxcore-log( 7219): JXcore engine is started
,I/chromium( 7219): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7219): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 306747266916; DSPS: 10192434; Offset : -4316061172
,I/jxcore-log( 7219): Toggling radios to true
I/jxcore-log( 7219): 
,D/BluetoothAdapter( 7219): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7219, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7219, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7219, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [306,985,611 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7219, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7219): Radios toggled
I/jxcore-log( 7219): 
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7219): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7219): 
I/jxcore-log( 7219): Perf Test app loaded loaded
I/jxcore-log( 7219): 
,I/jxcore-log( 7219): check test folder,
I/jxcore-log( 7219): 
I/jxcore-log( 7219): found test : ./testFindPeers.js
I/jxcore-log( 7219): 
I/jxcore-log( 7219): found test : ./testSendData.js
I/jxcore-log( 7219): 
,I/wpa_supplicant( 2711): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1038): InitialState.processMessage what=4
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  322): Clearing all IP addresses on wlan0
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7307 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2120): Read error: ssl=0xaf498400: I/O error during system call, Connection timed out
,V/NativeCrypto( 2120): SSL shutdown failed: ssl=0xaf498400: I/O error during system call, Broken pipe
I/jxcore-log( 7219): found test : ./testSendData2.js
I/jxcore-log( 7219): 
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [307,111,055 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 2711): wlan0: CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/DSQN    ( 1038): Dns fail occured do internet check.
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](, 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=307122
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=307122
,D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
W/ResourcesManager( 7307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7307): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7307): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7307): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7307): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7307): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CommandListener(  322): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=307160  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=307160  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1038): InternetcheckProgress is not set don't send DS quality intent
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ],
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
D/TelephonyNetworkFactory-1( 1860): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=307170  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524292
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=307172  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Glo,bal, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/Choreographer( 7219): Skipped 78 frames!  The application may be doing too much work on its main thread.
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
I/chromium( 7219): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7307): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7307): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7307): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7307): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-181ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7347 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6237:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6237/cgroup.procs: No such file or directory
,I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7347): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7307): LgDataFeature() Constructor: none
,D/LgDataFeature( 7307): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7374 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6259:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6259/cgroup.procs: No such file or directory
,W/ResourcesManager( 7374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7374): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7374): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7374): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7374): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7374): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7374): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7374): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7374): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 7374): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7347): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7374): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
,D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7347): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7347): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7374): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7374): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7374): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7374): LgDataFeature() Constructor: none
D/LgDataFeature( 7374): LgDataFeature() Constructor Done, null
,V/SoundPool( 7374): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7374): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7374): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7374): doLoad: loading sample sampleID=1
I/QRemote ( 7374): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 7374): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,V/SoundPool( 7374): Start decode
V/MediaPlayer[Native]( 7374): decode(31, 10857164, 17813)
D/UEI.SmartControl( 6809): QS Service created
E/QRemote ( 7374): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/MediaPlayerService(  326): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  326): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  326): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  326): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  326): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  326): player type = 3
V/AwesomePlayer(  326): AwesomePlayer create()
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): setAudioSink() 
V/AwesomePlayer(  326): reset_l() 
V/AudioCache(  326): notify(0xb14ce340, 8, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
D/Utils   (  326): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  326): setDataSource_l dataSource
V/LGParserOSAL(  326): SniffLGParser start
V/LGParserOSAL(  326): MainType:5, SubType=0
V/LGParserOSAL(  326): #### check Mime : application/ogg
V/LGParserOSAL(  326): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  326): Use LGExtractor :application/ogg 
V/LGMDMManager( 7374): Create singleton instance
I/UEI.SmartControl( 6809): Service initServices...
D/UEI.SmartControl( 6809): QS start get config
,V/LGParserOSAL(  326): supported mime: application/ogg
V/AwesomePlayer(  326): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  326): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  326): mBitrate = -1 bits/sec
V/AwesomePlayer(  326): AudioTrack Setting
V/AwesomePlayer(  326): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  326): setAudioSource() 
V/MediaPlayerService(  326): prepare
V/AwesomePlayer(  326): prepareAsync_l() 
V/MediaPlayerService(  326): wait for prepare
V/AwesomePlayer(  326): onPrepareAsyncEvent() 
V/AwesomePlayer(  326): initAudioDecoder() 
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  326): isAudioPlaybackHookOn() false
V/AwesomePlayer(  326): getUseOffload() = 0 
V/OMXCodec(  326): OMXCodec::Create
V/OMXCodec(  326): findMatchingCodecs()
V/OMXCodec(  326): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  326): matchingCodecs.size()=1
V/OMXCodec(  326): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  326): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  326): LG Codec Adapter start
V/OMXCodec(  326): OMXCodec Createtor
V/OMXCodec(  326): setComponentRole
V/OMXCodec(  326): configureCodec protected=0
V/LGCodecAdapter(  326): called getLGCodecSpecificData
V/LGCodecOSAL(  326): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMETA
V/LGCodecOSAL(  326): Called LGconfigureCodecMSG
V/LGCodecOSAL(  326): Not support LGCodec
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  326): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  326): Could not offload audio decode, try pcm offload
W/Utils   (  326): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  326): isOffloadSupported()
V/AudioPolicyManager(  326): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  326): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  326): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  326): init()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  326): allocateBuffers
V/OMXCodec(  326): allocateBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf240 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf510 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf650 on output port
V/OMXCodec(  326): init() mAsyncCompletion wait!!! 
V/OMXCodec(  326): [OMX.google.vorb,is.decoder] onStateChange 2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  326): init() mAsyncCompletion wait!!! 
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  326): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  326): finishAsyncPrepare_l() 
V/AudioCache(  326): notify(0xb14ce340, 5, 0, 0)
V/AudioCache(  326): ignored
V/AudioCache(  326): notify(0xb14ce340, 1, 0, 0)
V/AudioCache(  326): prepared
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): start
V/AwesomePlayer(  326): play_l() 
V/AwesomePlayer(  326): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  326): createAudioPlayer_l
V/AwesomePlayer(  326): seekAudioIfNecessary_l() 
V/AwesomePlayer(  326): startAudioPlayer_l() 
D/AudioPlayer(  326): start of Playback, useOffload 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  326): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  326): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799040
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799760
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044800080
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  326): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  326): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  326): allocateBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf510 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf240 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  326): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  326): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  326): notify(0xb14ce340, 6, 0, 0)
,V/AudioCache(  326): ignored
V/MediaPlayerService(  326): wait for playback complete
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac700000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac701000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac702000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac703000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac704000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac705000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac706000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac707000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac708000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac709000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac70a000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac70b000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac70c000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac70d000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac70e000, 0xb173c000, 4096)
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac70f000, 0xb173c000, 4096)
,D/QRemote ( 7374): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac710000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac711000, 0xb173c000, 4096)
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2223
V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac712000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac713000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac714000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac715000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac716000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac717000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac718000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac719000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71a000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71b000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71c000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71d000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71e000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac71f000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac720000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac721000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac722000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac723000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac724000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac725000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac726000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac727000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac728000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac729000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
,V/AudioCache(  326): memcpy(0xac72a000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac72b000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac72c000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac72d000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac72e000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac72f000, 0xb173c000, 4096)
V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac730000, 0xb173c000, 4096)
,V/AudioCache(  326): write(0xb173c000, 4096)
V/AudioCache(  326): memcpy(0xac731000, 0xb173c000, 4096)
,V/OMXCodec(  326): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  326): postAudioEOS() 
V/AudioCache(  326): write(0xb173c000, 280)
V/AudioCache(  326): memcpy(0xac732000, 0xb173c000, 280)
V/AwesomePlayer(  326): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  326): onStreamDone
V/AwesomePlayer(  326): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  326): notify(0xb14ce340, 2, 0, 0)
,V/AudioCache(  326): playback complete
V/AwesomePlayer(  326): pause_l() 
V/AudioCache(  326): notify(0xb14ce340, 7, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
V/AudioCache(  326): wait - success
V/MediaPlayerService(  326): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  326): Pause Playback at 1068125
V/AwesomePlayer(  326): reset_l() 
,V/AudioCache(  326): notify(0xb14ce340, 8, 0, 0)
V/AudioCache(  326): ignored
V/AwesomePlayer(  326): cancelPlayerEvents
D/AudioPlayer(  326): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 2,
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
,V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf240 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
,V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf510 on port 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  326): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,V/OMXCodec(  326): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  326): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  326): AudioPlayer releasing audio source
D/AudioPlayer(  326): AudioPlayer done releasing audio source
V/AwesomePlayer(  326): reset_l() 
V/AwesomePlayer(  326): cancelPlayerEvents
V/AwesomePlayer(  326): ~AwesomePlayer call
V/AwesomePlayer(  326): reset_l() 
,V/AwesomePlayer(  326): cancelPlayerEvents
V/SoundPool( 7374): close(31)
V/SoundPool( 7374): pointer = 0x9fe6b000, size = 205080, sampleRate = 48000, numChannels = 2
,D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
,I/UEI.SmartControl( 6809): Supports setup maps: true
,D/UEI.SmartControl( 6809): QS start statue = true Error code = 0
I/UEI.SmartControl( 6809): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6809): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6809): ### init IR Blaster...
D/serial_port( 6809): Configuring serial port
E/UEI.SmartControl( 6809): UEIBLaster setting for 616
I/UEI.SmartControl( 6809): Setting serial record hearder size = 2
I/UEI.SmartControl( 6809): configuring settings for MAXQ616
I/UEI.SmartControl( 6809): Get version...
D/UEI.SmartControl( 6809): serial port data available: 21
,D/UEI.SmartControl( 6809): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6809): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6809): QS saving settings...
D/UEI.SmartControl( 6809): IR Blaster version: 25672567
D/UEI.SmartControl( 6809): serial port data available: 4
,W/ContextImpl( 6809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6809): Services init done
,D/UEI.SmartControl( 6809): QS Service init finished
I/UEI.SmartControl( 6809): Device manager: loading config....
D/UEI.SmartControl( 6809): QS Service version name: 2.1.91
D/UEI.SmartControl( 6809): QS Service version code: 201091
D/UEI.SmartControl( 6809): Service requested: Control
D/UEI.SmartControl( 6809): ----------- loading internal config...
E/UEI.SmartControl( 6809): Loading SETTINGS...
D/UEI.SmartControl( 6809): Request IControl service: devices are loaded...
,I/QRemote ( 7374): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6809): ------ IControl API: 11
D/UEI.SmartControl( 6809): File observer start...
E/UEI.SmartControl( 6809): IR Port is disabled: false
D/UEI.SmartControl( 6809): Starting file observer...
I/UEI.SmartControl( 6809): Registering callback...
D/UEI.SmartControl( 6809): Internal service binding...
I/UEI.SmartControl( 6809): ------ IControl API: 19
,I/UEI.SmartControl( 6809): Registering Services Ready callback...
D/UEI.SmartControl( 6809): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6809): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6809): -----service ready thread exits
I/QRemote ( 7374): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7374): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7374): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7374): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7374): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6809): ------ IControl API: 8
D/QRemote ( 7374): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7374): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7374): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7374): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7374): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7374): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7374): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7374): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7374): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7374): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7374): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450834221206]
D/QRemote ( 7374): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6754:com.lge.email/u0a23 (adj 15): empty #17
D/QRemote ( 7374): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6754/cgroup.procs: No such file or directory
,V/QRemote ( 7374): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7374): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2711): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=309242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=309273  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2711): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2711): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2711): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=309351  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
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
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=309352  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=309357
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=309357
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=309359
,D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=309371
,E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=309373
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=309374  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=309390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=309391  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=309392  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=309392
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=309393
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7307): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7307): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7307): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7307): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7307): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  322): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=309442  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=309442  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=309442  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=309447  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=309448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=309448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
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
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@59c67ed target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@59c67ed target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  322): Setting iface cfg
D/CommandListener(  322): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
I/wpa_supplicant( 2711): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 1
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
E/Netd    (  322): netlink response contains error (File exists)
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
D/TelephonyNetworkFactory-1( 1860): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sen,dStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
,D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
W/dsqn    ( 7451): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7451): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7451): DSQN ssw
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7374): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  322): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7374): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7374): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7374): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  322): argv[0]=dsqncommand
D/LGDataListener(  322): argv[1]=wlan0
D/LGDataListener(  322): argv[2]=1
D/LGDataListener(  322): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7347): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7347): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 01:30:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450834222314], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450834222297]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
,D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
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
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1860): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/WiFiOffLoadBroadcast( 7307): MCCMNC not supported: null
D/QRemote ( 7374): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7374): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7374): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7374): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7374): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7457): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7457): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7457): version 5.5.6 starting
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/dhcpcd  ( 7457): get_duid: m
D/dhcpcd  ( 7457): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7457): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7457): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7457): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7457): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7457): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7457): wlan0: sending REQUEST (xid 0xcf03cea0), next in 3.27 seconds
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
I/NetworkMonitor( 6043): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 6043): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7475 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7475): onCreate
,W/AppUp4:DB( 7475):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7475):  setFingerPrint start
I/AppUp4:DB( 7475):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7475):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7475):  SDK version = 21
I/AppUp4:DB( 7475):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7475): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7475): onReceive
D/LgDataFeature( 7475): LgDataFeature() Constructor: none
D/LgDataFeature( 7475): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7475): Context : android.app.ReceiverRestrictedContext@1dd43f2b
D/AppUp4:CustFacade( 7475): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7475): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7475): begin check event
I/AppUp4:CustModeStarterReceiver( 7475): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7475): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7475): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7475): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7475): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6613:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6613/cgroup.procs: No such file or directory
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3418): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4315): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3418): DownloadService onCreate
D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4315): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3418): in removeSpuriousFiles
,V/DownloadManager( 3418): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@2b1955df on behalf of 3418
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3418): in trimDatabase
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@140674f5 on behalf of 3418
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7519 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3418): DownloadService onStartCommand
V/DownloadManager( 3418): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@19e770fb on behalf of 3418
E/LGDMClient( 4315): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4315): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3418): processing inserted download 1
D/LGDMClient( 4315): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3418): processing inserted download 4
V/DownloadManager( 3418): processing inserted download 7
V/DownloadManager( 3418): processing inserted download 8
V/DownloadManager( 3418): processing inserted download 9
V/DownloadManager( 3418): processing inserted download 10
V/DownloadManager( 3418): processing inserted download 16
,V/DownloadManager( 3418): processing inserted download 17
V/DownloadManager( 3418): processing inserted download 18
V/DownloadManager( 3418): processing inserted download 21
V/DownloadManager( 3418): DownloadService onDestroy
,W/ResourcesManager( 7519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7519): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7519): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7519): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7519): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7519): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7519): No package identifier when getting value for resource number 0x00000000
,I/dhcpcd  ( 7457): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,D/LgDataFeature( 7519): LgDataFeature() Constructor: none
D/LgDataFeature( 7519): LgDataFeature() Constructor Done, null
I/dhcpcd  ( 7457): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7457): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7457): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7457): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7457): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 7457): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7457): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7457): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/jxcore-log( 7219): Connected to the server!
I/jxcore-log( 7219): 
I/chromium( 7219): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/eas_req ( 7519): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 80167(3MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.958ms total 90.932ms
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7574 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7519): JNI_OnLoad()
I/HubEmail( 7519): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7519): registerNatives()
I/HubEmail( 7519): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7519): registerNativeMethods()
I/HubEmail( 7519): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7519): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Killing 6781:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6781/cgroup.procs: No such file or directory
,W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3392): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3392): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3392): networkInfo.isConnected() = false
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7597 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = static-avc.lglime.com, class = 1, type = 1
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
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
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524295
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7622 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6836:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6836/cgroup.procs: No such file or directory
,D/libc-netbsd(  322): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7646 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6883:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6883/cgroup.procs: No such file or directory
,V/FormManager( 7574): There are no updated forms. The schedule will be deleted.
V/FormManager( 7574): Alarm would be updated, because LastCheckTime has been updated.
,I/art     ( 7646): Almond Protected OAT
,I/ActivityManager( 1038): Killing 6929:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6929/cgroup.procs: No such file or directory
,D/WeatherApplication( 7646): removeAccount
D/WeatherApplication( 7646): Account.length = 0
E/WeatherApplication( 7646): OPERATOR:OPEN
D/WeatherAncestor( 7646): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:24
,D/Weather.Utils( 7646): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7646): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7646): 2 : This is isUpdating : false
D/WeatherAncestor( 7646): connectivity changed - connection : true
D/WeatherService( 7646): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7646): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7646): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7646): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7646): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7646): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:24
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7219): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7219): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7219): BLE supported!!
I/jxcore-log( 7219): 
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7665 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6904:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/art     (  348): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 538us total 31.372ms
,E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.494ms total 23.396ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 21.381ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6904/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7665): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7665): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7665): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7665): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
I/NetworkMonitor( 6043): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7665): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7665): Loading: webviewchromium
,I/LibraryLoader( 7665): Time to load native libraries: 5 ms (timestamps 2748-2753)
I/LibraryLoader( 7665): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7665): Binding Chromium to main looper Looper (main, tid 1) {3d9c9182}
,I/LibraryLoader( 7665): Expected native library version number "",actual native library version number ""
I/chromium( 7665): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7665): Initializing chromium process, renderers=0
,W/art     ( 7665): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7665): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7665): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953,
I/chromium( 7665): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  326): registerClient() client 0xb54f5020, uid 10093
W/AudioManagerAndroid( 7665): Requires BLUETOOTH permission
I/Adreno-EGL( 7665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7665): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7665): Build Date: 12/12/14 금
I/Adreno-EGL( 7665): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7665): Remote Branch: 
I/Adreno-EGL( 7665): Local Patches: 
I/Adreno-EGL( 7665): Reconstruct Branch: 
,I/NSApplication( 7665): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7735 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6951:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6951/cgroup.procs: No such file or directory
,W/ResourcesManager( 7735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{387a0d9f type 0 when 1450834186288 com.google.android.gms} when 1450834186288
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{24186eec type 2 when 313264 com.google.android.gms} when 313264
,D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/UEI.SmartControl( 6809): Internal timer expired: 2
,D/UEI.SmartControl( 6809): unbind internal service
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7475): onReceive
,D/AppUp4:CustFacade( 7475): Context : android.app.ReceiverRestrictedContext@1dd43f2b
,D/AppUp4:CustFacade( 7475): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7475): isPhone : true
I/GLSActivity( 2120): [ac] getting account id
D/AppUp4:CustModeStarterReceiver( 7475): begin check event
I/AppUp4:CustModeStarterReceiver( 7475): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/GLSUser ( 2120): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/DownloadManager( 3418): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3418): DownloadService onCreate
I/DownloadManager( 3418): in removeSpuriousFiles
,D/LGDMClient( 4315): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@22966b71 on behalf of 3418
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/LGDMClient( 4315): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
,I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3418): in trimDatabase
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@192e5d56 on behalf of 3418
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/serial_port( 6809): close(fd = 24)
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/UEI.SmartControl( 6809): Serial port is closed.
,E/LGDMClient( 4315): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4315): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4315): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3418): DownloadService onStartCommand
V/DownloadManager( 3418): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@14554dad on behalf of 3418
,I/LgeMiscReceiver( 3392): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3392): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3392): networkInfo.isConnected() = false
W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 3418): processing inserted download 1
V/DownloadManager( 3418): processing inserted download 4
V/DownloadManager( 3418): processing inserted download 7
V/DownloadManager( 3418): processing inserted download 8
,V/DownloadManager( 3418): processing inserted download 9
V/DownloadManager( 3418): processing inserted download 10
D/WeatherAncestor( 7646): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:26
V/DownloadManager( 3418): processing inserted download 16
V/DownloadManager( 3418): processing inserted download 17
D/Weather.Utils( 7646): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7646): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7646): 2 : This is isUpdating : false
D/WeatherAncestor( 7646): connectivity changed - connection : true
D/WeatherService( 7646): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d1fdd21
V/DownloadManager( 3418): processing inserted download 18
D/ForecastDataCache( 7646): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7646): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7646): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7646): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7646): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:26
V/DownloadManager( 3418): processing inserted download 21
V/DownloadManager( 3418): DownloadService onDestroy
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2361): [AccountUtils] Account not ready
W/Kids    ( 2361): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2361): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2361): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6701): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
V/FormManager( 7574): There are no updated forms. The schedule will be deleted.
W/ContextImpl( 6701): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,V/FormManager( 7574): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7475): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7475): onReceive
,D/AppUp4:CustFacade( 7475): Context : android.app.ReceiverRestrictedContext@1dd43f2b
D/AppUp4:CustFacade( 7475): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7475): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7475): begin check event
I/AppUp4:CustModeStarterReceiver( 7475): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3418): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3418): DownloadService onCreate
I/DownloadManager( 3418): in removeSpuriousFiles
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@3d0d0473 on behalf of 3418
D/LGDMClient( 4315): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3418): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = www.google.com, class = 1, type = 1
,D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4315): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4315): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3418): in trimDatabase
V/DownloadManager( 3418): DownloadService onStartCommand
V/DownloadManager( 3418): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@ca3c12e on behalf of 3418
,V/DownloadManager( 3418): processing inserted download 1
V/DownloadManager( 3418): processing inserted download 4
V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@1e2974cf on behalf of 3418
W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3418): processing inserted download 7
V/DownloadManager( 3418): processing inserted download 8
W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 7519): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3418): processing inserted download 9
,V/DownloadManager( 3418): processing inserted download 10
E/LGDMClient( 4315): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4315): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4315): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3418): processing inserted download 16
V/DownloadManager( 3418): processing inserted download 17
V/DownloadManager( 3418): processing inserted download 18
V/DownloadManager( 3418): processing inserted download 21
D/libc-netbsd(  322): res_queryN name = www.google.com succeed
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  322): res_queryN name = clients3.google.com succeed
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3418): DownloadService onDestroy
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2361): [AccountUtils] Account not ready
W/Kids    ( 2361): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2361): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2361): 	at java.lang.Thread.run(Thread.java:818)
I/LgeMiscReceiver( 3392): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3392): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3392): networkInfo.isConnected() = true
D/PhoneState( 3392): setPdpRejectCasuse : false
,D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/WeatherAncestor( 7646): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:26
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/Weather.Utils( 7646): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7646): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7646): 2 : This is isUpdating : false
D/WeatherAncestor( 7646): connectivity changed - connection : true
D/WeatherService( 7646): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d1fdd21
D/ForecastDataCache( 7646): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7646): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7646): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7646): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7646): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:30:26
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
D/QuickStatusbarLayout( 1406): Notification difference=198
,D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = mtalk.google.com, class = 1, type = 1
V/QRemote ( 7374): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7374): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2223
,V/FormManager( 7574): There are no updated forms. The schedule will be deleted.
I/EventLogService( 2361): Aggregate from 1450832386224 (log), 1450832386224 (data)
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/FormManager( 7574): Alarm would be updated, because LastCheckTime has been updated.
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  322): res_queryN name = mtalk.google.com succeed
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
W/Kids    ( 2361): [AccountUtils] Account not ready
W/Kids    ( 2361): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2361): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2361): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 23302(1138KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 1.669ms total 142.508ms
,D/GCM     ( 2120): Connected
I/GCM     ( 2361): Message from null null
E/GCM     ( 2361): Dropping message from null
,D/GCM     ( 2120): Message class com.google.f.a.a.p
,I/GAV4    ( 7665): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1038): Killing 6970:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6970/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 326748594044; DSPS: 10847837; Offset : -4316046640
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{22dd3c75 type 2 when 328401 android} when 328401
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 346750436537; DSPS: 11503258; Offset : -4316065641
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated(),
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 366752729759; DSPS: 12158693; Offset : -4316061368
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6347): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6347): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6347): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6347): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6347): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6347): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6347): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6347): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  322): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 386754856626; DSPS: 12814123; Offset : -4316070601
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 406756949014; DSPS: 13469551; Offset : -4316053435
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 426758728433; DSPS: 14124970; Offset : -4316074553
,I/jxcore-log( 7219): --- start :testSendData2.js---
I/jxcore-log( 7219): 
,E/jxcore  ( 7219): Error!: self.tests[testData.testName] is not a constructor
E/jxcore  ( 7219): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 7219): [INFO:CONSOLE(63)] "logCallback --- start :testSendData2.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 446760913010; DSPS: 14780401; Offset : -4316056672
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 466763028731; DSPS: 15435831; Offset : -4316077180
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 486764659140; DSPS: 16091244; Offset : -4316064204
,I/jxcore-log( 7219): Connected to the server!
I/jxcore-log( 7219): 
,I/chromium( 7219): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 506767615174; DSPS: 16746701; Offset : -4316068322
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 526769474072; DSPS: 17402122; Offset : -4316071074
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 546771672711; DSPS: 18057554; Offset : -4316069728
,I/jxcore-log( 7219): teardown
I/jxcore-log( 7219): 
,E/jxcore  ( 7219): Error!: self.currentTest is undefined
E/jxcore  ( 7219): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 7219): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{673f04f type 2 when 550894 android} when 550894
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,I/BooksSync( 7043): Starting books sync
,D/BooksSync( 7043): started syncMyEbooks
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7043): null auth token
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  322): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  322): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
W/ApiaryClient( 7043): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-158795475012888985&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-158795475012888985&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-158795475012888985&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
E/BooksSync( 7043): Soft error: 
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-158795475012888985&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
,E/BooksSync( 7043): Sync error
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-158795475012888985&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
I/BooksSync( 7043): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 566773259890; DSPS: 18712966; Offset : -4316069489
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3dd20b79 type 2 when 581117 android} when 581117
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 586775532019; DSPS: 19368400; Offset : -4316055634
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 606777351281; DSPS: 20023820; Offset : -4316067400
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 626778984711; DSPS: 20679233; Offset : -4316051376
,I/jxcore-log( 7219): Connected to the server!
I/jxcore-log( 7219): 
,I/chromium( 7219): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 646781749965; DSPS: 21334684; Offset : -4316063144
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
I/ActivityManager( 1038): Killing 6347:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6347/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 666783737873; DSPS: 21990109; Offset : -4316058956
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 686785606616; DSPS: 22645530; Offset : -4316051787
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 706787542597; DSPS: 23300954; Offset : -4316068957
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7912 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2a83f0be type 0 when 1450834615291 com.android.vending} when 1450834615291
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,I/art     ( 2120): Explicit concurrent mark sweep GC freed 46705(2MB) AllocSpace objects, 25(3MB) LOS objects, 50% free, 30MB/62MB, paused 938us total 35.706ms
,D/Finsky  ( 7912): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7912): LgDataFeature() Constructor: none
D/LgDataFeature( 7912): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7912): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1038): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7969 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7912): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7912): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7912): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7912): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7912): [1] 2.run: Finished loading 1 libraries.
W/ResourcesManager( 7969): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7969): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3418): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3418): created cursor android.database.sqlite.SQLiteCursor@2c1f8565 on behalf of 7912
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7912): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/Finsky  ( 7912): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/MultiDex( 7969): VM with version 2.1.0 has multidex support
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MultiDex( 7969): install
I/MultiDex( 7969): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7969): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 7969): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7969): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8721ac4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7969): Installed default security provider GmsCore_OpenSSL
I/art     ( 1038): Explicit concurrent mark sweep GC freed 31367(1356KB) AllocSpace objects, 8(640KB) LOS objects, 33% free, 44MB/66MB, paused 2.303ms total 97.767ms
,D/GCM     ( 2120): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2120): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1038): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8002 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Finsky  ( 7912): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/LocationInitializer( 2361): Restart initialization of location
,W/ResourcesManager( 8002): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8002): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 8002): VM with version 2.1.0 has multidex support
,I/MultiDex( 8002): install
I/MultiDex( 8002): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8002): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 8002): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8002): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8721ac4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8002): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2120): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2120): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8002): callingUid 10005, callindPid: 8002
,D/LocationInitializer( 2361): Restart initialization of location
V/Finsky  ( 7912): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/MDM     ( 1825): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1825): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{21cf8c56 type 0 when 1450834622713 com.android.vending} when 1450834622713
W/Finsky  ( 7912): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7912): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7912): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
I/ActivityManager( 1038): Killing 7148:com.lge.clock/u0a10 (adj 15): empty #17
,D/DeviceConnectionService( 1825): client connected with version: 7571000
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_7148/cgroup.procs: No such file or directory
,W/Finsky  ( 7912): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7912): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7912): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7912): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7912): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7912): [1] DailyHygiene.reschedule: Scheduling new run in 96 minutes (failures=3)
D/DeviceConnectionService( 1825): client connected with version: 7571000
,I/ActivityManager( 1038): Killing 7347:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7347/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Killing 7307:com.android.settings/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7307/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 726789800923; DSPS: 23956388; Offset : -4316068930
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{368efda8 type 0 when 1450834638016 com.android.vending} when 1450834638016
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7912): [1] 5.onFinished: Scheduling replication attempt 1.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 746792518677; DSPS: 24611837; Offset : -4316067267
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{15b7e3bb type 0 when 1450834659936 com.android.vending} when 1450834659936
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7912): [1] 5.onFinished: Scheduling replication attempt 2.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 766794127366; DSPS: 25267250; Offset : -4316075957
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2e4f37fa type 0 when 1450834681198 com.android.vending} when 1450834681198
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/art     ( 2120): Explicit concurrent mark sweep GC freed 26353(1475KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 30MB/62MB, paused 1.268ms total 35.544ms
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7912): [1] 5.onFinished: Scheduling replication attempt 3.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 786796290066; DSPS: 25922680; Offset : -4316049514
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2b71f695 type 0 when 1450834707181 com.android.vending} when 1450834707181
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7912): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 806798585684; DSPS: 26578116; Offset : -4316072998
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{cf94a7c type 0 when 1450834733741 com.android.vending} when 1450834733741
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 25299(1085KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.939ms total 90.657ms
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7912): [1] 5.onFinished: Scheduling replication attempt 5.
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{118900fe type 2 when 826344 android} when 826344
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 826801381510; DSPS: 27233567; Offset : -4316054506
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{c624aac type 0 when 1450834754178 com.android.vending} when 1450834754178
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7912): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7912): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 846803204368; DSPS: 27888987; Offset : -4316062703
,I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1038): battery changed pluggedType: 2
D/HeadsetStateMachine( 3791): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1038): battery changed pluggedType: 2
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3791): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4315): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 866805464620; DSPS: 28544421; Offset : -4316060699
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 886807590185; DSPS: 29199851; Offset : -4316071442
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 906809733719; DSPS: 29855281; Offset : -4316064088
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 926812155639; DSPS: 30510720; Offset : -4316053056
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2075a5ae type 2 when 943946 com.android.bluetooth} when 943946
,W/bt-smp  ( 3791): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
,W/bt-smp  ( 3791): Plain text(LSB ~ MSB) = ef 89 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3791): Encrypted text(LSB ~ MSB) = 6d b4 60 62 58 64 24 f8 e7 df 34 80 ee f9 7e c5 
W/bt-btm  ( 3791): Stopping oneshot timer
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 946814540995; DSPS: 31166158; Offset : -4316048071
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 966816720884; DSPS: 31821590; Offset : -4316065526
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 986818901293; DSPS: 32477021; Offset : -4316051682
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1006820889619; DSPS: 33132447; Offset : -4316077647
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7912): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7912): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7912): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7912): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7912): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7912): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7912): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7912): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  322): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1026822359872; DSPS: 33787855; Offset : -4316072420
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1046824150593; DSPS: 34443274; Offset : -4316082158
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{226004e0 type 2 when 1052488 android} when 1052488
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,I/BooksSync( 7043): Starting books sync
D/BooksSync( 7043): started syncMyEbooks
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1406): Notification difference=198
,D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  322): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6575091265299122012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6575091265299122012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6575091265299122012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
E/BooksSync( 7043): Soft error: 
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6575091265299122012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
,E/BooksSync( 7043): Sync error
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6575091265299122012&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
I/BooksSync( 7043): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1052488, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1066827482096; DSPS: 35098742; Offset : -4316046476
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1a70f5ca type 2 when 1083108 android} when 1083108
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1086829701202; DSPS: 35754175; Offset : -4316055178
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1106832554945; DSPS: 36409629; Offset : -4316070061
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1126834565354; DSPS: 37065055; Offset : -4316073786
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1146836118836; DSPS: 37720466; Offset : -4316076701
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1166838230651; DSPS: 38375895; Offset : -4316070625
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1186840433561; DSPS: 39031327; Offset : -4316064954
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8178 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8178): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8178): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2f05559c
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
I/ActivityManager( 1038): Killing 7475:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_7475/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1206842152563; DSPS: 39686743; Offset : -4316055041
,I/UsageStatsService( 1038): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1226844147712; DSPS: 40342169; Offset : -4316073896
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1246846247964; DSPS: 40997598; Offset : -4316079410
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1266848495665; DSPS: 41653031; Offset : -4316059439
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1286850975606; DSPS: 42308472; Offset : -4316051501
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1306853094244; DSPS: 42963902; Offset : -4316069144
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1138633b type 2 when 1214290 com.google.android.gms} when 1214290
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,D/GCM     ( 2120): Message class com.google.f.a.a.i
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1326855138193; DSPS: 43619329; Offset : -4316069795
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1346856977041; DSPS: 44274749; Offset : -4316061950
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1366859161929; DSPS: 44930181; Offset : -4316074379
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1386861553433; DSPS: 45585619; Offset : -4316063298
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1406863672279; DSPS: 46241049; Offset : -4316080631
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1426865191646; DSPS: 46896458; Offset : -4316056599
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1446867008409; DSPS: 47551878; Offset : -4316070891
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1466868937516; DSPS: 48207301; Offset : -4316064366
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1486871369592; DSPS: 48862741; Offset : -4316073722
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1506872852709; DSPS: 49518149; Offset : -4316055449
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1526874656608; DSPS: 50173568; Offset : -4316052165
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1546876633319; DSPS: 50828993; Offset : -4316058966
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1566878901176; DSPS: 51484427; Offset : -4316049462
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1586880793825; DSPS: 52139849; Offset : -4316048851
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1606882318713; DSPS: 52795259; Offset : -4316049946
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1626884154851; DSPS: 53450680; Offset : -4316075433
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1646886260520; DSPS: 54106109; Offset : -4316075398
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1666888354263; DSPS: 54761537; Offset : -4316056825
I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1686891052537; DSPS: 55416986; Offset : -4316074616
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1706892809352; DSPS: 56072403; Offset : -4316057301
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1726894472521; DSPS: 56727818; Offset : -4316072573
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1746896314857; DSPS: 57383238; Offset : -4316061397
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1766898381308; DSPS: 58038666; Offset : -4316070141
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1786901177915; DSPS: 58694117; Offset : -4316050607
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1806903468845; DSPS: 59349552; Offset : -4316048417
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1826905354046; DSPS: 60004974; Offset : -4316055410
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{110447b1 type 2 when 1843972 com.android.bluetooth} when 1843972
,W/bt-smp  ( 3791): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3791): Plain text(LSB ~ MSB) = 26 24 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3791): Encrypted text(LSB ~ MSB) = 28 c6 35 bc 84 ce 90 3f 92 3f 95 48 46 39 95 d1 
,W/bt-btm  ( 3791): Stopping oneshot timer
I/ProcessStatsService( 1038): Prepared write state in 17ms
I/ProcessStatsService( 1038): Prepared write state in 22ms
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,I/ProcessStatsService( 1038): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-09-10.bin
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1846907578204; DSPS: 60660407; Offset : -4316058905
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1866909512311; DSPS: 61315831; Offset : -4316077976
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1886911734440; DSPS: 61971263; Offset : -4316053086
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1906913537817; DSPS: 62626682; Offset : -4316050299
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1926915418174; DSPS: 63282104; Offset : -4316062031
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1946917504520; DSPS: 63937532; Offset : -4316050932
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1966919044564; DSPS: 64592943; Offset : -4316067233
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1986921916068; DSPS: 65248397; Offset : -4316064330
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2006924028612; DSPS: 65903826; Offset : -4316057577
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2026926042771; DSPS: 66559252; Offset : -4316057551
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2046928136201; DSPS: 67214681; Offset : -4316069912
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3090a496 type 2 when 2051964 android} when 2051964
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,I/BooksSync( 7043): Starting books sync
D/BooksSync( 7043): started syncMyEbooks
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
,W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,D/libc-netbsd(  322): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  322): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  322): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3352746757123784084&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3352746757123784084&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2120): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2120): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2120): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2120): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
W/GLSActivity( 2120): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2120): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2120): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2120): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2120): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7043): Authentication error
E/BooksAccountManager( 7043): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7043): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7043): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7043): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7043): null auth token
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{3d0d0473 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7043): Error response from books API: {
W/ApiaryClient( 7043):  "error": {
W/ApiaryClient( 7043):   "errors": [
W/ApiaryClient( 7043):    {
W/ApiaryClient( 7043):     "domain": "global",
W/ApiaryClient( 7043):     "reason": "required",
W/ApiaryClient( 7043):     "message": "Login Required",
W/ApiaryClient( 7043):     "locationType": "header",
W/ApiaryClient( 7043):     "location": "Authorization"
W/ApiaryClient( 7043):    }
W/ApiaryClient( 7043):   ],
W/ApiaryClient( 7043):   "code": 401,
W/ApiaryClient( 7043):   "message": "Login Required"
W/ApiaryClient( 7043):  }
W/ApiaryClient( 7043): }
,W/ApiaryClient( 7043): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3352746757123784084&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7043): Headers:
W/ApiaryClient( 7043): accept-encoding: [gzip]
W/ApiaryClient( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7043): gdata-version: 2
E/BooksSync( 7043): Soft error: 
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3352746757123784084&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
,E/BooksSync( 7043): Sync error
E/BooksSync( 7043): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7043): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3352746757123784084&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7043): Headers:
E/BooksSync( 7043): accept-encoding: [gzip]
E/BooksSync( 7043): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7043): gdata-version: 2
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7043): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7043): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7043): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7043): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7043): {
E/BooksSync( 7043):  "error": {
E/BooksSync( 7043):   "errors": [
E/BooksSync( 7043):    {
E/BooksSync( 7043):     "domain": "global",
E/BooksSync( 7043):     "reason": "required",
E/BooksSync( 7043):     "message": "Login Required",
E/BooksSync( 7043):     "locationType": "header",
E/BooksSync( 7043):     "location": "Authorization"
E/BooksSync( 7043):    }
E/BooksSync( 7043):   ],
E/BooksSync( 7043):   "code": 401,
E/BooksSync( 7043):   "message": "Login Required"
E/BooksSync( 7043):  }
E/BooksSync( 7043): }
E/BooksSync( 7043): 
E/BooksSync( 7043): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7043): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7043): 	... 8 more
I/BooksSync( 7043): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 2051964, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2066930342704; DSPS: 67870113; Offset : -4316060623
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3880a2d0 type 2 when 2082773 android} when 2082773
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2086932279572; DSPS: 68525537; Offset : -4316076776
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=627916798, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/DigitalAppWidgetProvider( 8178): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 8178): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2f05559c
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=627916798 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2106933913574; DSPS: 69180950; Offset : -4316060257
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2126935972577; DSPS: 69836378; Offset : -4316076528
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2146937921527; DSPS: 70491801; Offset : -4316050081
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/WifiController( 1038): battery changed pluggedType: 2
,TIME-OUT KILL (timeout was 1800000ms)
```
