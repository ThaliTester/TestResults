#### Test 62509094e6af764_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  973): acquireWL(5bb24bc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 973 1000 WorkSource{1000}
V/AlarmManager(  973): sending alarm PendingIntent{1c8d43a5: PendingIntentRecord{2960437a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163521, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{1b481c45: PendingIntentRecord{38af3f9a android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457695324328, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{131b30cb: PendingIntentRecord{3373d0a8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202672, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{3bd337c1: PendingIntentRecord{3431bb66 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188730, Int=0
D/PMS     (  973): acquireWL(372a0ea7): PARTIAL_WAKE_LOCK  *backup* 0x1 973 1000 null
W/BackupManagerService(  973): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  973): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  973): releaseWL(372a0ea7): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  973): acquireWL(9894f54): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(5bb24bc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  973): acquireWL(149a8efd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(9894f54): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  973): releaseWL(149a8efd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(3b782b9f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(3b782b9f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(b6f34ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(b6f34ec): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(1b01a0b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(3fa6c34a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(2990b3d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(1b01a0b5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1882): Vacuum at: now=1457695359380 tag=VacuumService
I/GoogleURLConnFactory( 1882): Using platform SSLCertificateSocketFactory
D/PMS     (  973): releaseWL(3fa6c34a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(2b15ca16): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(2b15ca16): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
W/Uploader( 1882): No account for auth token provided
D/PMS     (  973): acquireWL(1eddef97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): releaseWL(1eddef97): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1882): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1882): [NET] android_getaddrinfo_proxy+
D/libc    ( 1882): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
E/cutils-trace( 6528): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6528): ====startRecUseTime====
D/htc.customization.log.level( 6528):  is 
W/CustomizationLogLevel( 6528): Level value is invalid, use default level 2
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1882): [NET] android_getaddrinfo_proxy-, success
D/CustomizationManager( 6528):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6528): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6528): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6528): Parsing tag category name = system
I/CustomizationCIDLoader( 6528): Parsing tag category name = application
I/CustomizationCIDLoader( 6528): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6528): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6528): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6528): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6528): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6528): add string-array item, value = 42507
I/CustomizationCIDLoader( 6528): add string-array item, value = 21902
I/CustomizationCIDLoader( 6528): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6528): add string-array item, value = 23420
I/CustomizationCIDLoader( 6528): add string-array item, value = 22299
I/CustomizationCIDLoader( 6528): add string-array item, value = 24002
I/CustomizationCIDLoader( 6528): add string-array item, value = 23210
I/CustomizationCIDLoader( 6528): add string-array item, value = 23205
I/CustomizationCIDLoader( 6528): add string-array item, value = 23806
I/CustomizationCIDLoader( 6528): add string-array item, value = 23430
I/CustomizationCIDLoader( 6528): add string-array item, value = 23408
I/CustomizationCIDLoader( 6528): add string-array item, value = 27205
I/CustomizationCIDLoader( 6528): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6528): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6528):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6528):  All configurations done spent 0.096 (s)
I/ActivityManager(  973): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6528 on display 0
D/PMS     (  973): acquireHCC(3c87ee33): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 973 1000 null
D/PMS     (  973): acquireHCC(1ee625f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 973 1000 null
W/asset   (  973): Copying FileAsset 0x5596eee100 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  973): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6551 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  411): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 252us total 19.339ms
V/ActivityManager(  973): Display changed displayId=0
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 225us total 17.098ms
I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 220us total 14.965ms
W/asset   ( 6551): Copying FileAsset 0xac607ff8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
I/TrimMemoryManager( 1589): [trimMemory] 20
I/WebViewFactory( 6551): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6551): Time to load native libraries: 9 ms (timestamps 3446-3455),
,I/LibraryLoader( 6551): Expected native library version number "",actual native library version number "",
,W/Uploader( 1882): No account for auth token provided
,V/WebViewChromiumFactoryProvider( 6551): Binding Chromium to main looper Looper (main, tid 1) {3bfc2aa2}
,I/LibraryLoader( 6551): Expected native library version number "",actual native library version number ""
,I/chromium( 6551): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6551): Initializing chromium process, singleProcess=true
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6551): ApplicationContext is null in ApplicationStatus
,W/chromium( 6551): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6551): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6551): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
,I/Adreno-EGL( 6551): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6551): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6551): Local Branch: 
I/Adreno-EGL( 6551): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6551): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6551):                  d74aa161a12b9c6fc6332151
,W/Uploader( 1882): No account for auth token provided
,D/BluetoothManagerService(  973): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a707b4:true
W/System.err(  973): java.lang.Throwable: stack dump
W/System.err(  973): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  973): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  973): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  973): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6551): 118902510: getState(). Returning 12
,W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6551): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6551): CordovaWebView is running on device made by: HTC
,W/Uploader( 1882): No account for auth token provided
,W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6551): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  973): Activity pause timeout for ActivityRecord{f2d7769 u0 com.test.thalitest/.MainActivity t12},
W/HtcSystemUPManager(  973): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 6551): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  973): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  973): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  973): hiding MENU key
,D/StatusBarManagerService(  973): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  973): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  973): hiding MENU key
,W/Uploader( 1882):  no longer exists, so no auth token.
,D/FindExtension( 6551): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6551): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2801ff9b, mServedView=org.apache.cordova.engine.SystemWebView{319d3f38 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@26872b11
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false),
I/InputMethodManagerService(  973): Disable input method client, pid=1589
D/StatusBarManagerService(  973): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6551): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  973): Displayed com.test.thalitest/.MainActivity: +670ms (total +719ms)
,W/Uploader( 1882): No account for auth token provided,
,W/BindingManager( 6551): Cannot call determinedVisibility() - never saw a connection for the pid: 6551
,D/JsMessageQueue( 6551): Set native->JS mode to OnlineEventsBridgeMode
,D/PMS     (  973): releaseWL(2990b3d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): acquireWL(f46de49): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): releaseWL(f46de49): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  973): acquireWL(e5d134e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): releaseWL(e5d134e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/jxcore_app_log( 6551): JniHelper::setJavaVM(0xab4ad8f8), pthread_self() = -1401127896
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e023305 added. We now have 1 listener(s)
D/BluetoothManagerService(  973): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6551): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6551): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6551): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6551): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Discovery mode: BLE,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57ae668 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6551): addListener: New listener added - the number of listeners is now 1
,E/WifiTrafficPoller(  973): ADD_CLIENT: 8
D/WifiService(  973): New client listening to asynchronous messages
,D/BluetoothAdapter( 6551): 118902510: getState(). Returning 12
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6551): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6551): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6551): 118902510: getState(). Returning 12
,I/chromium( 6551): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,W/jxcore-log( 6551): Initializing JXcore engine,
W/jxcore-log( 6551): JXcore engine is ready
,W/jxcore-log( 6551): Starting JXcore engine,
,W/jxcore-log( 6551): Platform android,
W/jxcore-log( 6551): 
W/jxcore-log( 6551): Process ARCH arm
W/jxcore-log( 6551): 
,D/PMS     (  973): releaseHCC(3c87ee33): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  973): releaseHCC(1ee625f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6551): JXcore Cordova bridge is ready!,
I/jxcore-log( 6551): 
W/jxcore-log( 6551): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6551): execute: REQUEST_ACCESS_COARSE_LOCATION,
,E/jxcore  ( 6551): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6551): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}],
,I/chromium( 6551): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,D/Process (  973): killProcessQuiet, pid=5437
,I/ActivityManager(  973): Killing 5437:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  973): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,I/ActivityManager(  973): Recipient 5437,
,W/PluginManager( 6551): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 130ms. Plugin should use CordovaInterface.getThreadPool().
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1447): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3acccadc
,D/Process (  973): killProcessQuiet, pid=5855
,I/ActivityManager(  973): Killing 5855:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  973): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  973): Recipient 5855
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  973): acquireWL(35d72c6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
D/UsbnetService(  973): BroadcastReceiver::onReceive+
I/BatteryService(  973): n_update end
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/PMS     (  973): releaseWL(35d72c6f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/NotificationService(  973): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  973): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): processMsg: StaEnabledState
D/HtcPowerSaver(  973): updateBatteryInfo
D/WifiController(  973): processMsg: DefaultState
D/PMS     (  973): runPSCheck
D/WifiController(  973): handleMessage: X
D/HtcPowerSaver(  973): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  973): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  973): acquireWL(901ed7c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null,
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(901ed7c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  973): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/PMS     (  973): runPSCheck
,D/UsbnetService(  973): onReceive BATTERY_CHANGED,
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: DeviceActiveState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  973): processMsg: StaEnabledState
,I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1335): wlan0: BSS: Remove id 15 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 11 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:dd:eb SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 16 BSSID 00:1e:4a:8f:e3:62 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 17 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 f0:f2:6d:22:99:3e]
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 13 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:dd:e0 SSID '\x00' due to wpa_bss_flush_by_age
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 f0:f2:6d:22:99:3e
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e4 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1]
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 8 BSSID 00:1e:4a:8f:df:df SSID '\x00' due to wpa_bss_flush_by_age
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 7 BSSID 00:1e:4a:8f:df:db SSID '\x00' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 1335): wlan0: BSS: Remove id 14 BSSID 00:22:0d:46:1c:a0 SSID '\x00' due to wpa_bss_flush_by_age
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 9 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 10 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:6b]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:1e:4a:8f:e3:6b
D/wpa_supplicant( 1335): wlan0: BSS: Remove id 18 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6f]
,E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:6f
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:eb]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:dd:eb
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:e3:62]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 16 00:1e:4a:8f:e3:62
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 00:1e:4a:8f:e3:64]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 17 00:1e:4a:8f:e3:64
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:dd:ef]
,E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1f:27:54:dd:ef
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e0]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:dd:e0
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e2]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:e2
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e4]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e4
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:df:df]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:1e:4a:8f:df:df,
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:df:db]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1e:4a:8f:df:db
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:22:0d:46:1c:a0]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:22:0d:46:1c:a0
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:63]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1e:4a:8f:e3:63
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e3]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:e3,
D/WifiMonitor(  973): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 18 00:1f:27:54:e0:43]
E/WifiMonitor(  973): WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-BSS-REMOVED 18 00:1f:27:54:e0:43
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  973): acquireWL(16161605): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(16161605): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
,D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  973): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  973): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  973): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): processMsg: DeviceActiveState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  973): processMsg: StaEnabledState
I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5971): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5971): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5971): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5971): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5971): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5971): Ignoring header User-Agent because its value was null.,
D/libc    ( 5971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5971): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5971): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5971): [NET] android_getaddrinfo_proxy+
D/libc    ( 5971): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5971): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  973): acquireWL(28920f5f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 973 1000 WorkSource{1000}
,V/AlarmManager(  973): sending alarm PendingIntent{1c8d43a5: PendingIntentRecord{2960437a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223522, Int=0
,D/PMS     (  973): releaseWL(28920f5f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  973): acquireWL(959adac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(959adac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  973): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,D/PMS     (  973): runPSCheck
D/HtcPowerSaver(  973): Checking...
I/HtcPowerSaver(  973): >> updateStatus
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  973): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  973): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  973): << updateStatus
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  973): acquireWL(1af5ca0a): PARTIAL_WAKE_LOCK  *alarm* 0x1 973 1000 WorkSource{10109}
V/AlarmManager(  973): sending alarm PendingIntent{2bf2427b: PendingIntentRecord{2c89f898 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1457695497251, Int=0
,I/ActivityManager(  973): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6615 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  973): sending alarm PendingIntent{1e0d58f1: PendingIntentRecord{182e7cd6 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1457695580335, Int=0
,D/PMS     (  973): releaseWL(1af5ca0a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10071}
,D/StatusBarManagerService(  973): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  973): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  973): hiding MENU key
,D/StatusBarManagerService(  973): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  973): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  973): hiding MENU key
,D/FindExtension( 1589): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1589): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  973): Disable input method client, pid=6551,
D/StatusBarManagerService(  973): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6551): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6551): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6551): reportFullscreenMode on inactive InputConnection
,E/cutils-trace( 6637): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6637): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6637): dex2oat: override thread count:4
,I/dex2oat ( 6637): dex2oat took 616.178ms (threads: 4)
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6615): ApplicationMonitor {7164eee}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6615): PnsModel {10b74469}: update(): Update registration caused by: alarm
,I/PushClient( 6615): PnsConfigModel {30ce18b4}: <init>(): Use dm-client for provisioning.
,W/System.err( 6615): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6615): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6615): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6615): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  973): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6644 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6644): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6644 dbg=false s=true,
,I/DeviceManagement( 6644): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6644): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6644): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6644): WorkflowService: Starting workflow service
,I/DeviceManagement( 6644): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@10b74469] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6644): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6644): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6644): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6644): SessionStateController: Checking invariants...
,I/DeviceManagement( 6644): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6644): SessionStateController: Checking invariants...
,I/DeviceManagement( 6644): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6644): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@10b74469],
,I/DeviceManagement( 6644): WorkflowService: Stopping workflow service,
,D/Process (  973): killProcessQuiet, pid=6346
,I/ActivityManager(  973): Killing 6346:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  973): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  973): Recipient 6346
,I/PushClient( 6615): PnsModel {10b74469}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  973): killProcessQuiet, pid=6301
,I/ActivityManager(  973): Killing 6301:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  973): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  973): Recipient 6301
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  973): acquireWL(1814c06b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(1814c06b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): handleMessage: E msg.what=155652
D/HtcPowerSaver(  973): Checking...
D/WifiController(  973): processMsg: DeviceActiveState
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): processMsg: StaEnabledState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  973): processMsg: DefaultState
I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): handleMessage: X
,D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  973): acquireWL(1138b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(1138b7c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/PMS     (  973): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  973): Checking...
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  973): battery changed pluggedType: 2
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100,
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  428): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/PMS     (  973): acquireWL(9d56061): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
D/UsbnetService(  973): onReceive BATTERY_CHANGED
I/BatteryService(  973): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  973): releaseWL(9d56061): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/NotificationService(  973): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  973): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  973): updateBatteryInfo
,D/PMS     (  973): runPSCheck
D/HtcPowerSaver(  973): Checking...
I/HtcPowerSaver(  973): >> updateStatus
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1523): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1523): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1523): sku_id=118
D/ContactMessageStore( 1523): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1523): start background delete task...
,D/ContactMessageStore( 1523): size: 0 , 0
,D/ContactMessageStore( 1523): Background delete complete
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  973): acquireWL(1f3dc786): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  973): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  973): releaseWL(1f3dc786): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  973): updateBatteryInfo
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  973): acquireWL(37bcf847): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/UsbnetService(  973): BroadcastReceiver::onReceive+,
D/PMS     (  973): releaseWL(37bcf847): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  973): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  973): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  973): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): processMsg: StaEnabledState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  973): processMsg: DefaultState
I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(1d058874): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(1d058874): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
,D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): handleMessage: E msg.what=155652
,D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: StaEnabledState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  973): processMsg: DefaultState
I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): handleMessage: X
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(8a6a19d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(8a6a19d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
D/WifiController(  973): handleMessage: E msg.what=155652
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
D/PowerUI ( 1222): closing low battery warning: level=100
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(109ed612): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 973 1000 WorkSource{1000}
V/AlarmManager(  973): sending alarm PendingIntent{1c8d43a5: PendingIntentRecord{2960437a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=463521, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{1cc6d1e3: PendingIntentRecord{d2cb7e0 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940768, Int=0
,I/bt-btm  ( 3112): Received oneshot timer event complete,
,I/bt-btm  ( 3112): btm_ble_timeout
I/bt-btm  ( 3112): btm_gen_resolvable_private_addr
,I/art     (  973): Explicit concurrent mark sweep GC freed 30182(1711KB) AllocSpace objects, 8(716KB) LOS objects, 33% free, 16MB/24MB, paused 1.585ms total 176.285ms,
D/PMS     (  973): acquireWL(1350ba99): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3112 1002 null,
,D/bt-btm  ( 3112): btm_ble_rand_enc_complete,
I/bt-btm  ( 3112): btm_gen_resolve_paddr_low
D/bt-smp  ( 3112): smp_encrypt_data
W/bt-smp  ( 3112): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3112): Plain text(LSB ~ MSB) = 58 9e 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3112): Encrypted text(LSB ~ MSB) = 3c 44 4d d5 76 07 42 81 34 fc b9 1e 35 e2 94 1c 
I/bt-btm  ( 3112): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3112): Stopping oneshot timer
D/bt-btm  ( 3112): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  973): releaseWL(109ed612): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  973): releaseWL(1350ba99): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  973): acquireWL(3d90415e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(3d90415e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): updateBatteryInfo
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
D/WifiController(  973): handleMessage: E msg.what=155652
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  973): acquireWL(170aa93f): PARTIAL_WAKE_LOCK  *alarm* 0x1 973 1000 WorkSource{1000}
,V/AlarmManager(  973): sending alarm PendingIntent{43f79b5: PendingIntentRecord{3d1a284a android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804814, Int=0,
V/AlarmManager(  973): sending alarm PendingIntent{1c8d43a5: PendingIntentRecord{2960437a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943522, Int=0
,V/AlarmManager(  973): sending alarm PendingIntent{34d5720c: PendingIntentRecord{8e96755 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936647, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{299b156a: PendingIntentRecord{230e8f1e com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457696121854, Int=0
D/PMS     (  973): acquireWL(318a9a5b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): releaseWL(318a9a5b): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6438): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  973): releaseWL(170aa93f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 6438): MY_DEBUG = false
,D/PowerUsageService( 6438): repeat time = 1457697021907
,D/PMS     (  973): acquireWL(2a2623d1): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1882 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1882): Message class com.google.f.a.a.i
,D/PMS     (  973): releaseWL(2a2623d1): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/art     ( 1882): Explicit concurrent mark sweep GC freed 25139(1404KB) AllocSpace objects, 8(672KB) LOS objects, 48% free, 4MB/8MB, paused 1.150ms total 71.567ms,
D/PMS     (  973): acquireWL(15cd1e36): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): acquireWL(1b4e8137): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6438): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PMS     (  973): releaseWL(15cd1e36): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): acquireWL(33982c0d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:BatterySipperExt( 6438): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  973): releaseWL(33982c0d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:BatterySipperExt( 6438): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6438): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  973): releaseWL(1b4e8137): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  973): acquireWL(3444e7c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): releaseWL(3444e7c2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  973): acquireWL(1fff9d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  973): releaseWL(1fff9d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  973): acquireWL(244dd910): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 973 1000 WorkSource{1000},
V/AlarmManager(  973): sending alarm PendingIntent{1c8d43a5: PendingIntentRecord{2960437a android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1003521, Int=0
V/AlarmManager(  973): sending alarm PendingIntent{1fa87c09: PendingIntentRecord{87dbe0e com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1457696169641, Int=0
,D/SmartSyncUtils( 6438): isEpsOn(), nState = 0,
,D/PMS     (  973): acquireWL(3a46602f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6438 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6438): [updateNmRange] bManual = false
D/PMS     (  973): releaseWL(244dd910): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,D/SmartSyncScreenOnOffTimeReceiver( 6438): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/SmartSyncScreenOnOffTimeReceiver( 6438): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6438): SettingOnTime = 1457762400000, randomSettingOnTime = 1457761236000
,D/SmartSyncScreenOnOffTimeReceiver( 6438): SettingOffTime = 1457740800000, randomSettingOffTime = 1457743845000
,D/SmartSyncScreenOnOffTimeReceiver( 6438): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6438): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6438): bNightModeTurnOffOnce = false
,D/PMS     (  973): releaseWL(3a46602f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  973): acquireWL(149f763c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(149f763c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  973): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  973): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/PMS     (  973): runPSCheck
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(c53cfc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
,I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(c53cfc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  973): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): onReceive BATTERY_CHANGED,
D/PMS     (  973): runPSCheck
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(5bad1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(5bad1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  973): updateBatteryInfo
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/PMS     (  973): runPSCheck
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  973): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  973): << updateStatus
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/PMS     (  973): acquireWL(11e2d04b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
D/UsbnetService(  973): onReceive BATTERY_CHANGED
I/BatteryService(  973): n_update end
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): releaseWL(11e2d04b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/NotificationService(  973): plugged=true pluggin=true
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): battery changed pluggedType: 2
D/WifiController(  973): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  973): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): processMsg: DefaultState
D/HtcPowerSaver(  973): updateBatteryInfo
D/WifiController(  973): handleMessage: X
D/PMS     (  973): runPSCheck
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  973): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  973): >> updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  973): User[0] Flushing usage stats to disk
,D/PMS     (  973): acquireWL(1e0bba28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(1e0bba28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): updateBatteryInfo
,D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): Checking...
D/WifiController(  973): handleMessage: E msg.what=155652
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): battery changed pluggedType: 2
,D/WifiController(  973): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  973): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  973): handleMessage: X
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  973): << updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  973): acquireWL(a6a341): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(a6a341): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  973): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  973): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  973): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973): BroadcastReceiver::onReceive+,
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973): onReceive BATTERY_CHANGED
,D/WifiController(  973): battery changed pluggedType: 2
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): handleMessage: E msg.what=155652,
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0,
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  973): acquireWL(11f780e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(11f780e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  973): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  973): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  973): Checking...
D/UsbnetService(  973): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  973): battery changed pluggedType: 2
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
D/WifiController(  973): handleMessage: E msg.what=155652,
D/WifiController(  973): processMsg: DeviceActiveState
I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  973): processMsg: StaEnabledState
I/HtcPowerSaver(  973): << updateStatus
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  973): acquireWL(278c2627): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  973): n_update end
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  973): releaseWL(278c2627): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/WifiController(  973): battery changed pluggedType: 2
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  973): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/PMS     (  973): runPSCheck
D/WifiController(  973): processMsg: StaEnabledState
D/HtcPowerSaver(  973): Checking...
D/WifiController(  973): processMsg: DefaultState
I/HtcPowerSaver(  973): >> updateStatus
D/WifiController(  973): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  973): acquireWL(337650d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 973 1000 null
I/BatteryService(  973): n_update end
D/PMS     (  973): releaseWL(337650d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  973): updateBatteryInfo
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  973): plugged=true pluggin=true
D/UsbnetService(  973): BroadcastReceiver::onReceive+
D/PMS     (  973): runPSCheck
D/UsbnetService(  973): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  973): Checking...
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  973): >> updateStatus
D/UsbnetService(  973):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  973): battery changed pluggedType: 2
D/UsbnetService(  973): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  973): handleMessage: E msg.what=155652
D/WifiController(  973): processMsg: DeviceActiveState
D/WifiController(  973): processMsg: StaEnabledState
D/WifiController(  973): processMsg: DefaultState
D/WifiController(  973): handleMessage: X
D/HeadsetStateMachine( 3112): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  973): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  973): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
