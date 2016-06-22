#### Test 721454317367600_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main,
06-22 07:43:19.713   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
06-22 07:43:20.093  5882  5892 E cutils-trace: Error opening trace file: No such file or directory (2)
06-22 07:43:20.123  5882  5882 D CustomizationManager: ====startRecUseTime====
06-22 07:43:20.123  5882  5882 D htc.customization.log.level:  is 
06-22 07:43:20.123  5882  5882 W CustomizationLogLevel: Level value is invalid, use default level 2
06-22 07:43:20.193  5882  5882 D CustomizationManager:  Read ACC file spent 0.044 (s)
06-22 07:43:20.193  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__001
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__E11
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__102
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__203
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__405
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__304
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__032
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__016
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__A48
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-22 07:43:20.203  5882  5882 D CIDMapFileReader: Parsing tag item name = HTC__002
06-22 07:43:20.203  5882  5882 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-22 07:43:20.203  5882  5882 I CustomizationCIDLoader: Parsing tag category name = system
06-22 07:43:20.203  5882  5882 I CustomizationCIDLoader: Parsing tag category name = application
06-22 07:43:20.203  5882  5882 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-22 07:43:20.213  5882  5882 I CustomizationCIDLoader: Parsing tag category name = Settings
06-22 07:43:20.213  5882  5882 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-22 07:43:20.213  5882  5882 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-22 07:43:20.213  5882  5882 I CustomizationCIDLoader: Parsing tag category name = ACC
06-22 07:43:20.213  5882  5882 D CustomizationManager:  Read CID file spent 0.092 (s)
06-22 07:43:20.213  5882  5882 D CustomizationManager:  All configurations done spent 0.093 (s)
06-22 07:43:20.233  5882  5882 E ActTriggerJNI: open library fail.
06-22 07:43:20.243  2249  2265 E MP-Decision: Update arg 2
06-22 07:43:20.253  2249  2265 E MP-Decision: Update arg 4
--------- beginning of system
06-22 07:43:20.253   905  1639 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-22 07:43:20.253   905  1015 D PMS     : acquireHCC(1bfa1e24): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 905 1000 null
06-22 07:43:20.253   905  1015 D PMS     : acquireHCC(1285fd8d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 905 1000 null
06-22 07:43:20.263  2249  2265 E MP-Decision: Update arg "0 190 240 240".
06-22 07:43:20.263  2249  2265 E MP-Decision: Update arg "0 75 400 400".
06-22 07:43:20.263   905  1006 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/3
06-22 07:43:20.263   905  1639 D PMS     : acquireWL(dfa5145): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
06-22 07:43:20.273  1493  1493 I FeedHostManager: [onPause]
06-22 07:43:20.273  1493  1493 I FeedProviderManager: onPause
06-22 07:43:20.273  1493  1493 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@102c7b0f
06-22 07:43:20.273  1493  2215 I SocialFeedProvider: +onPause
06-22 07:43:20.273  1493  2215 I SocialFeedProvider: -onPause
06-22 07:43:20.273   905  1529 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
06-22 07:43:20.303   905  1266 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5914 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:43:20.343   905  1004 D StatusBarManagerService: setSystemUiVisibility(0x8600)
06-22 07:43:20.343   905  1004 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:43:20.343   905  1004 D StatusBarManagerService: hiding MENU key
06-22 07:43:20.353  1493  1493 I TrimMemoryManager: [trimMemory] 20
06-22 07:43:20.393  5914  5914 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-22 07:43:20.413  5914  5914 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7233-7234)
06-22 07:43:20.413  5914  5914 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:20.423  5914  5914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1acad952}
06-22 07:43:20.423  5914  5914 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:20.423  5914  5914 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:43:20.443  5914  5914 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-22 07:43:20.443  5914  5914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:20.443  5914  5914 E SysUtils: ApplicationContext is null in ApplicationStatus
06-22 07:43:20.453  5914  5938 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-22 07:43:20.463  5914  5914 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-22 07:43:20.463  5914  5914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:43:20.463  5914  5914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:43:20.463  5914  5914 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:20.463  5914  5914 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:20.463  5914  5914 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:20.463  5914  5914 I Adreno-EGL: Local Branch: 
06-22 07:43:20.463  5914  5914 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:20.463  5914  5914 I Adreno-EGL: Local Patches: NONE
06-22 07:43:20.463  5914  5914 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:20.513   905  1586 W System.err: java.lang.Throwable: stack dump
06-22 07:43:20.513   905  1586 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:20.513   905  1586 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-22 07:43:20.513   905  1586 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-22 07:43:20.513   905  1586 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:20.513   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-22 07:43:20.513   905  1005 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21315dec:true
,06-22 07:43:20.513  5914  5949 D BluetoothAdapter: 800157567: getState() :  mService = null. Returning STATE_OFF
,06-22 07:43:20.583  5914  5914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:20.593  5914  5914 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:43:20.603  5914  5914 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,06-22 07:43:20.603  5914  5914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:20.603  5914  5914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:20.653  5914  5914 D Atlas   : Validating map...
,06-22 07:43:20.653  5914  5947 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-22 07:43:20.723  5914  5914 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@165e285a, mServedView=org.apache.cordova.engine.SystemWebView{5feca8b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@21b4c768
,06-22 07:43:20.723   905  1528 I InputMethodManagerService: Disable input method client, pid=1493
06-22 07:43:20.723   905  1528 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-22 07:43:20.723   905  1528 I InputMethodManagerService: Enable input method client, pid=5914
,06-22 07:43:20.723   905  1637 D PMS     : releaseWL(dfa5145): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,06-22 07:43:20.733   905  1006 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +461ms
,06-22 07:43:20.763  1285  1285 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,06-22 07:43:20.763  1285  1285 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
06-22 07:43:20.763  1285  1285 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
06-22 07:43:20.763  1285  1285 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,06-22 07:43:20.803  5914  5914 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5914
,06-22 07:43:20.873  5914  5914 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:43:20.953  5914  5963 D jxcore_app_log: JniHelper::setJavaVM(0xb7e54b98), pthread_self() = -1190309632
,06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
,06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:43:20.963  5914  5963 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c626fac added. We now have 1 listener(s)
06-22 07:43:20.963   905  1088 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,06-22 07:43:20.963  5914  5963 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
,06-22 07:43:20.963  5914  5963 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
,06-22 07:43:20.963  5914  5963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-22 07:43:20.963  5914  5963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:43:20.973  5914  5963 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299b6c7b added. We now have 1 listener(s)
06-22 07:43:20.973  5914  5963 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-22 07:43:20.973   905  1077 D WifiService: New client listening to asynchronous messages
,06-22 07:43:20.973   905   905 E WifiTrafficPoller: ADD_CLIENT: 6
06-22 07:43:20.973  5914  5963 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:20.973  5914  5963 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-22 07:43:20.973   905   921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
06-22 07:43:20.973  5914  5963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50,
06-22 07:43:20.973  5914  5963 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:20.973  5914  5963 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:20.973  5914  5963 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:43:20.973  5914  5963 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:43:20.983  5914  5963 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:43:20.993  5914  5914 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:43:21.263  5914  5928 I art     : Background partial concurrent mark sweep GC freed 3229(216KB) AllocSpace objects, 4(206KB) LOS objects, 51% free, 3MB/7MB, paused 6.703ms total 26.285ms
,06-22 07:43:21.363  3269  3289 I HtcModeClient: handler message = 4011
06-22 07:43:21.363  3269  3289 E HtcModeClient: Check connection and retry 11 times.
,06-22 07:43:21.873  5914  5970 W jxcore-log: Initializing JXcore engine
06-22 07:43:21.873  5914  5970 W jxcore-log: JXcore engine is ready
,06-22 07:43:21.943  5914  5970 W jxcore-log: Starting JXcore engine
,06-22 07:43:22.033  5914  5970 W jxcore-log: Platform android
06-22 07:43:22.033  5914  5970 W jxcore-log: 
,06-22 07:43:22.033  5914  5970 W jxcore-log: Process ARCH arm
06-22 07:43:22.033  5914  5970 W jxcore-log: 
,06-22 07:43:22.233  5914  5970 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:43:22.233  5914  5970 I jxcore-log: 
,06-22 07:43:22.233  5914  5970 W jxcore-log: JXcore engine is started
,06-22 07:43:22.243  5914  5963 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:43:22.243  5914  5914 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-22 07:43:22.253   905  1015 D PMS     : releaseHCC(1bfa1e24): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,06-22 07:43:22.253   905  1015 D PMS     : releaseHCC(1285fd8d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-22 07:43:22.253  2249  2265 E MP-Decision: Update arg 1
,06-22 07:43:25.683   905   905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:817 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,06-22 07:43:25.883   905  1586 D PMS     : acquireWL(2d4a079e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:43:25.883   905  1586 I BatteryService: n_update end
06-22 07:43:25.883   905  1586 D PMS     : releaseWL(2d4a079e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:43:25.883   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:43:25.883   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:43:25.883   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:43:25.883   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:43:25.883   905   905 D PMS     : runPSCheck
06-22 07:43:25.883   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:43:25.883   905   905 D HtcPowerSaver: Checking...
06-22 07:43:25.883   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:43:25.883   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:43:25.883  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:43:25.883   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:43:25.883  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:43:25.883  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:43:25.883  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:43:25.883   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:43:25.883  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:43:25.883   905   905 I HtcPowerSaver: << updateStatus
06-22 07:43:25.883  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,06-22 07:43:25.933  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true
,06-22 07:43:26.403  3269  3289 I HtcModeClient: handler message = 4011
06-22 07:43:26.403  3269  3289 E HtcModeClient: Check connection and retry 12 times.
,06-22 07:43:31.133   905  1065 I ActivityManager: Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5977 uid=10079 gids={50079, 9997} abi=armeabi-v7a
06-22 07:43:31.133   905  1065 D PMS     : acquireWL(190b927f): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10079}
06-22 07:43:31.133   905  1065 V AlarmManager: sending alarm PendingIntent{3dca424c: PendingIntentRecord{2199295 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1466574211117, Int=60000
06-22 07:43:31.133   905   905 D PMS     : releaseWL(190b927f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10079}
,06-22 07:43:31.173  5977  5994 D SMSBackup: SMSBackupAgentService started
06-22 07:43:31.173  5977  5994 D SMSBackup: Checking restore status
06-22 07:43:31.173  5977  5994 D SMSBackup: Restore complete
06-22 07:43:31.173  5977  5994 D SMSBackup: cancelCheckAlarm
06-22 07:43:31.173  5977  5994 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,06-22 07:43:31.193   905   920 D Process : killProcessQuiet, pid=5522,
06-22 07:43:31.193   905   920 I ActivityManager: Killing 5522:com.htc.sense.socialplugins/u0a21 (adj 15): empty #17,
,06-22 07:43:31.193   905   920 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:31.203   905  1528 I ActivityManager: Recipient 5522,
,06-22 07:43:31.223   905  1528 D Process : killProcessQuiet, pid=5522,
06-22 07:43:31.223   905  1528 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:31.223   905  1528 W libprocessgroup: failed to open /acct/uid_10021/pid_5522/cgroup.procs: No such file or directory
,06-22 07:43:31.443  3269  3289 I HtcModeClient: handler message = 4011
06-22 07:43:31.443  3269  3289 E HtcModeClient: Check connection and retry 12 times. Stop service and kill this process.
,06-22 07:43:31.443  3269  3269 D HtcModeClient: Don't start project servcice,
06-22 07:43:31.443  3269  3269 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,06-22 07:43:31.443  3269  3269 D HtcModeClient: connectState: CONNECTION_READY = false
,06-22 07:43:31.443  3269  3269 D SilentMusic: call stop
,06-22 07:43:31.443  3269  3269 D HtcModeClient: close connection
,06-22 07:43:31.443  3269  3269 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-22 07:43:31.443  3269  3297 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-22 07:43:31.493   905  1708 D Process : killProcessQuiet, pid=3269,
06-22 07:43:31.493   905  1708 I ActivityManager: Killing 3269:com.htc.autobot/u0a49 (adj 15): empty #17
06-22 07:43:31.493   905  1708 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:31.503   905  1584 I ActivityManager: Recipient 3269,
,06-22 07:43:31.603   905  1584 D Process : killProcessQuiet, pid=3269,
06-22 07:43:31.603   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:31.603   905  1584 W libprocessgroup: failed to open /acct/uid_10049/pid_3269/cgroup.procs: No such file or directory
,06-22 07:43:31.693  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
06-22 07:43:31.693  5914  5970 I jxcore-log: 
,06-22 07:43:31.693  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
06-22 07:43:31.693  5914  5970 I jxcore-log: 
,06-22 07:43:31.693  5914  5970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:31.693  5914  5970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:31.693  5914  5970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:31.693  5914  5970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-22 07:43:31.693  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-22 07:43:31.693  5914  5970 I jxcore-log: 
,06-22 07:43:31.703  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
06-22 07:43:31.703  5914  5970 I jxcore-log: 
,06-22 07:43:32.093  5914  5970 I jxcore-log: Unit Test app is loaded,
06-22 07:43:32.093  5914  5970 I jxcore-log: 
,06-22 07:43:32.093  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-22 07:43:32.093  5914  5970 I jxcore-log: 
06-22 07:43:32.103  5914  5914 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-22 07:43:32.103  5914  5970 D WifiManager: setWifiEnabled: Base Package Name=com.test.thalitest, uid=10192
,06-22 07:43:32.103   905  1528 W Settings:Agent: MONITOR_LOG
,06-22 07:43:32.103   905  1528 D WifiService: setWifiEnabled: true pid=5914, uid=10192
06-22 07:43:32.103   905  1528 W Settings:Agent: name: wifi_on
06-22 07:43:32.103   905  1528 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
06-22 07:43:32.103   905  1528 W Settings:Agent: value: 2
06-22 07:43:32.103   905  1528 I WifiService: isSprintWifiRestricted(): false
06-22 07:43:32.103   905  1528 W Settings:Agent: >> traceCallingStack()
06-22 07:43:32.103   905  1528 I WifiService: isMdmWifiRestricted(): false
06-22 07:43:32.103   905  1528 W Settings:Agent: Process.myPid(): 905
06-22 07:43:32.103   905  1528 W Settings:Agent: Process.myTid(): 1528
06-22 07:43:32.103   905  1528 W Settings:Agent: Process.myUid(): 1000
06-22 07:43:32.103   905  1528 W Settings:Agent: 
06-22 07:43:32.103   905  1528 W Settings:Agent: 
06-22 07:43:32.103   905  1528 W System.err: java.lang.Throwable: stack dump
,06-22 07:43:32.113   905  1528 W System.err: ,	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:32.113   905  1528 W System.err: 	,at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
06-22 07:43:32.113   905  1528 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
06-22 07:43:32.113   905  1528 W System.err: 	,at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
06-22 07:43:32.113   905  1528 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
06-22 07:43:32.113   905  1528 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,06-22 07:43:32.113   905  1528 W System.err: 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151),
06-22 07:43:32.113   905  1528 W System.err: 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
06-22 07:43:32.113   905  1528 W System.err: ,	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
06-22 07:43:32.113   905  1528 W System.err: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
06-22 07:43:32.113   905  1528 W System.err: ,	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:32.113   905  1528 W Settings:Agent: 
06-22 07:43:32.113   905  1528 W Settings:Agent: << traceCallingStack(): 6(ms)
,06-22 07:43:32.133   905  1077 E WifiStateMachine: setting operational mode to 1,
06-22 07:43:32.133   905  1076 E WifiStateMachine: handleMessage: E msg.what=131083
06-22 07:43:32.133   905  1076 D PMS     : acquireWL(3ed0d79b): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
06-22 07:43:32.133   905  1076 E WifiStateMachine: processMsg: InitialState
06-22 07:43:32.133   905  1076 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
06-22 07:43:32.133  5914  5970 D WifiManager: disconnect: Base Package Name=com.test.thalitest, uid=10192
06-22 07:43:32.143  5914  5970 D WifiManager: reconnect: Base Package Name=com.test.thalitest, uid=10192
,06-22 07:43:32.153   905  2090 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:43:32.153   905  2090 D BluetoothManagerService: checking for enable restriction...
06-22 07:43:32.153   905  2090 D BluetoothManagerService: checkBTEasState, ret=true
06-22 07:43:32.153   905  2090 D BluetoothManagerService: enable(): region ID = 6
06-22 07:43:32.153   905  2090 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
06-22 07:43:32.153   905  2090 W Settings:Agent: MONITOR_LOG
06-22 07:43:32.153   905  2090 W Settings:Agent: name: bluetooth_on
06-22 07:43:32.153   905  2090 W Settings:Agent: value: 1
06-22 07:43:32.153   905  2090 W Settings:Agent: >> traceCallingStack()
06-22 07:43:32.153   905  2090 W Settings:Agent: Process.myPid(): 905
,06-22 07:43:32.153   905  2090 W Settings:Agent: Process.myTid(): 2090
06-22 07:43:32.153   905  2090 W Settings:Agent: Process.myUid(): 1000
06-22 07:43:32.153   905  2090 W Settings:Agent: 
06-22 07:43:32.153   905  2090 W Settings:Agent: 
06-22 07:43:32.153   905  2090 W System.err: java.lang.Throwable: stack dump
06-22 07:43:32.153   905  2090 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:32.153   905  2090 W System.err: 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
06-22 07:43:32.153   905  2090 W System.err: 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
06-22 07:43:32.153   905  2090 W System.err: 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,06-22 07:43:32.153   905  2090 W System.err: 	at android.provider.Settings$Global.putString(Settings.java:7403)
06-22 07:43:32.153   905  2090 W System.err: 	at android.provider.Settings$Global.putInt(Settings.java:7503)
06-22 07:43:32.153   905  2090 W System.err: 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
06-22 07:43:32.153   905  2090 W System.err: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:599)
06-22 07:43:32.153   905  2090 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
06-22 07:43:32.153   905  2090 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:32.153   905  2090 W Settings:Agent: 
,06-22 07:43:32.153   905  2090 W Settings:Agent: << traceCallingStack(): 1(ms)
,06-22 07:43:32.183   905  1005 D BluetoothManagerService: Message: MESSAGE_ENABLE,
06-22 07:43:32.183   905  1005 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-22 07:43:32.193  5914  5970 I jxcore-log: My device name is: HTC-HTC One_M8
06-22 07:43:32.193  5914  5970 I jxcore-log: 
,06-22 07:43:32.203  5914  5970 I jxcore-log: WARN testUtils: myNameCallback not set!,
,06-22 07:43:32.203  5914  5970 I jxcore-log: ,
06-22 07:43:32.213   905  1005 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6018 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,06-22 07:43:32.253  6018  6018 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
,06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding HeadsetService,
06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding A2dpService
06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding HidService
06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding HealthService
06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding PanService
,06-22 07:43:32.313  6018  6018 D AdapterServiceConfig: Adding GattService
,06-22 07:43:32.333   905  1003 D Tethering: interfaceAdded wlan0,
06-22 07:43:32.333   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.343   905  1073 D PMS     : acquireWL(1255944e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
06-22 07:43:32.333  6018  6018 W linker  : libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,06-22 07:43:32.343   905   905 D UsbDeviceManager: [USBNET] bCheckSuppFunc: cdc_network
06-22 07:43:32.333   905  1005 V Tethering: TetherInterfaceSM: wlan0: enter InitialState
06-22 07:43:32.343   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 07:43:32.333   905  1005 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.343   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 07:43:32.333   905  1005 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-22 07:43:32.343   905  1073 D PMS     : releaseWL(1255944e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-22 07:43:32.333   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:43:32.343   905   905 D UsbDeviceManager: [USBNET] bCheckSuppFunc: cdc_network
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:32.343   905  1073 D PMS     : acquireWL(20854b05): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:32.353   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-22 07:43:32.353   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:32.353   905  1073 D PMS     : releaseWL(20854b05): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:32.333   455  6046 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-22 07:43:32.333   455  6046 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504,
06-22 07:43:32.333   455  6046 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
06-22 07:43:32.373   905  1076 D PMS     : releaseWL(3ed0d79b): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
06-22 07:43:32.333   455  6046 D libc    : [NET] android_getaddrinfofornet-, err=7
06-22 07:43:32.333   905  1073 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
06-22 07:43:32.343   905  1074 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:32.343   905  1074 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:32.343   905   905 D UsbnetService: ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
,06-22 07:43:32.343   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:43:32.343   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false
06-22 07:43:32.343   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:32.343   905   920 W System.err: java.lang.Throwable: stack dump
06-22 07:43:32.343   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-22 07:43:32.343   905  1005 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@988d67c:true
06-22 07:43:32.343   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.343   905  1005 D Tethering: TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
06-22 07:43:32.343   905   920 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:32.343   905  1005 V Tethering: TetherInterfaceSM: wlan0: exit InitialState
06-22 07:43:32.343   905   920 W System.err: ,	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-22 07:43:32.343   905  1005 V Tethering: TetherInterfaceSM: wlan0: enter UnavailableState
06-22 07:43:32.343   905   920 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-22 07:43:32.343   905  1005 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,06-22 07:43:32.343   905   920 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:32.403  5296  5296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:32.343   905  1005 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-22 07:43:32.343   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:43:32.343   905   905 D UsbnetService: ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
06-22 07:43:32.343   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:43:32.343   905  1073 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,06-22 07:43:32.343   905  1073 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:32.343  6018  6018 D BluetoothAdapterState: make
06-22 07:43:32.353   905  1074 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:32.353   905  1074 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:32.353   905  1003 D Tethering: interfaceAdded p2p0
06-22 07:43:32.353   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,06-22 07:43:32.353   905  1003 D Tethering: p2p0 is not a tetherable iface, ignoring
06-22 07:43:32.353  6018  6047 I BluetoothAdapterState: Entering OffState
06-22 07:43:32.353  6018  6047 I BluetoothAdapterState: notBluetoothOff()
06-22 07:43:32.353  6018  6018 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-22 07:43:32.363  6018  6050 D BluetoothAdapterProperties: Address is:50:2E:6C:AC:21:50
06-22 07:43:32.363   905   905 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
06-22 07:43:32.363   905  1005 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED,
06-22 07:43:32.363   905  1005 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-22 07:43:32.363   905  1005 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-22 07:43:32.363   905  1005 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
06-22 07:43:32.363  1709  1727 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@a8ca746
06-22 07:43:32.363  1709  1727 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  1123  1796 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@edf6c07
,06-22 07:43:32.363  1123  1796 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  1457  1475 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3a589cb9
06-22 07:43:32.363  1457  1475 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363   905  1005 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@7949281
06-22 07:43:32.363   905  1005 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  3600  3617 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@10a3c44d
06-22 07:43:32.363  3600  3617 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  6018  6038 D BluetoothAdapter: onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@2d1206d9
,06-22 07:43:32.363  6018  6038 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  5914  5929 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3433e11f
,06-22 07:43:32.363  5914  5929 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363  1476  1492 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2e95bd76
06-22 07:43:32.363  1476  1492 D BluetoothAdapter: onBluetoothServiceUp done
06-22 07:43:32.363   905  1005 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() done
06-22 07:43:32.373   905  1003 D Tethering: interfaceLinkStateChanged p2p0, false
06-22 07:43:32.373   905  1003 D Tethering: interfaceStatusChanged p2p0, false
,06-22 07:43:32.373   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.373  6018  6047 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-22 07:43:32.373  6018  6047 D BluetoothAdapterProperties: Setting state to 11
06-22 07:43:32.373  6018  6047 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-22 07:43:32.373   905  1586 D BluetoothManagerService: +onBluetoothStateChange prev=10 new=11
06-22 07:43:32.373   905  1005 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,06-22 07:43:32.373   905  1005 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-22 07:43:32.373   905  1005 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,06-22 07:43:32.373  6018  6047 D BluetoothBondStateMachine: make
,06-22 07:43:32.373  1123  1302 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
06-22 07:43:32.373  6018  6047 D BluetoothAdapterService: checkA2dpState: isA2dpSinkEnabled = false
,06-22 07:43:32.373  6018  6053 I BluetoothBondStateMachine: StableState(): Entering Off State
06-22 07:43:32.373  6018  6047 E BluetoothAdapterService: checkA2dpState: returning
06-22 07:43:32.373  6018  6047 D BluetoothAdapterService: checkHfpState: isHfpClientEnabled = false
06-22 07:43:32.373  6018  6047 E BluetoothAdapterService: checkHfpState: returning
06-22 07:43:32.373  5296  5296 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
06-22 07:43:32.373  5296  5296 D         : Cust_ConnectToPC   : Internet_Sharing>true
06-22 07:43:32.373  5296  5296 D         : Cust_ConnectToPC   : Modem_Link>false
06-22 07:43:32.373  5296  5296 D         : Cust_ConnectToPC   : spcsc>false
06-22 07:43:32.373  5296  5296 D         : Cust_ConnectToPC   : IPT>true
06-22 07:43:32.373  5296  5296 D         : Cust_ConnectToPC   : Singel_USB>false
06-22 07:43:32.373  5296  5296 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:43:32.383  5296  5296 E SmartNS_Utility: hasRemovableStorageSlot: true
06-22 07:43:32.383  5296  5296 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
06-22 07:43:32.383  5296  5296 D SmartNS_NSReceiver: onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,06-22 07:43:32.383   905  1076 D libc    : [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
06-22 07:43:32.383   905  1076 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:32.383  6018  6018 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:32.383  6018  6018 V BluetoothPbapReceiver: ***********state = 11
06-22 07:43:32.393  6018  6047 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-22 07:43:32.393   905  1528 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.393  3600  3600 D NGFService: Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:32.393  1457  1457 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.393  1123  1123 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.393  1457  1457 D BluetoothPhoneService: BluetoothHeadset onServiceConnected
06-22 07:43:32.393  1457  1457 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.393  1457  1457 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.393  6018  6018 D HeadsetService: Received start request. Starting profile...
06-22 07:43:32.393  3600  3600 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.393  3600  3600 D NGFService: BluetoothHeadset onServiceConnected: main
,06-22 07:43:32.393  6018  6018 D HeadsetStateMachine: Version 1.6
06-22 07:43:32.393  6018  6018 D HeadsetStateMachine: make
06-22 07:43:32.393  1123  1123 I QuickSettingMiniLite: btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@3c755134
06-22 07:43:32.393  3600  3600 D BluetoothAdapter: 471350018: getState(). Returning 11
06-22 07:43:32.393  3600  3600 W NGFService: Headset deviceList = 0
06-22 07:43:32.403  5296  5296 I SmartNS_Utility: setISNotification
06-22 07:43:32.403  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
06-22 07:43:32.403  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:32.403  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:32.403   905  1585 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.403  5296  5296 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
06-22 07:43:32.403   905   905 D BluetoothHeadset: Proxy object connected
06-22 07:43:32.403  6018  6018 D HeadsetStateMachine: max_hf_connections = 2
06-22 07:43:32.403   905   905 D BluetoothAdapter: 94772721: getState(). Returning 11
06-22 07:43:32.403  6018  6018 D HeadsetPhoneState: listenForPhoneState..for service and signal 
06-22 07:43:32.403  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
06-22 07:43:32.403  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:32.403  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:32.413   905  1584 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.413  1199  1223 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,06-22 07:43:32.413  1123  1123 I RemoteViews: reapply : com.android.settings 1 36
06-22 07:43:32.413  6018  6055 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-22 07:43:32.413  6018  6055 I HeadsetStateMachine: setCurrentDevice, the latest mCurrentDevice is:null
06-22 07:43:32.413  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.413   905   905 D BluetoothA2dp: Proxy object connected
06-22 07:43:32.413  6018  6018 D A2dpService: Received start request. Starting profile...
06-22 07:43:32.423  5296  5296 D SmartNS_NSReceiver: Tethered state change:false isNSOpening:false
06-22 07:43:32.423   905   905 D BluetoothAdapter: 94772721: getState(). Returning 11
06-22 07:43:32.423  3600  3600 D BluetoothA2dp: Proxy object connected
06-22 07:43:32.423  3600  3600 D NGFService: BluetoothA2dp onServiceConnected: main
06-22 07:43:32.423  3600  3600 D BluetoothAdapter: 471350018: getState(). Returning 11
06-22 07:43:32.423  3600  3600 W NGFService: A2dp deviceList = 0
06-22 07:43:32.423  6018  6018 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-22 07:43:32.423  6018  6018 D A2dpStateMachine: make
06-22 07:43:32.423  1123  1123 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
06-22 07:43:32.423  6018  6018 D A2dpService: setA2dpService(): set to: null
06-22 07:43:32.423  6018  6063 D A2dpStateMachine: Enter Disconnected: -2
06-22 07:43:32.423  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.433  6018  6018 D HidService: Received start request. Starting profile...
06-22 07:43:32.433  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.433  6018  6018 D HealthService: Received start request. Starting profile...
06-22 07:43:32.433  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.443  6018  6018 D PanService: Received start request. Starting profile...
06-22 07:43:32.443  6018  6018 D PanService: HTC_CUSTOMIZATION_MHS_ENABLE = false
06-22 07:43:32.443  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.443  6018  6018 D BtGatt.DebugUtils: handleDebugAction() action=null
06-22 07:43:32.443  6018  6018 D BtGatt.GattService: Received start request. Starting profile...
06-22 07:43:32.443  6018  6018 D BtGatt.GattService: start()
06-22 07:43:32.443  6018  6018 D BtGatt.AdvertiseManager: advertise manager created
06-22 07:43:32.453   905  1528 I ActivityManager: Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6070 uid=10036 gids={50036, 9997, 3002, 3001} abi=armeabi-v7a
06-22 07:43:32.453  6018  6018 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3fa9dd
06-22 07:43:32.463  1199  3757 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
06-22 07:43:32.463  1123  1123 I RemoteViews: reapply : com.android.settings 1 36
,06-22 07:43:32.463  1457  1457 D BluetoothAdapter: 797812831: getState(). Returning 11
06-22 07:43:32.463  1457  1457 W BluetoothHeadset: Proxy not attached to service
06-22 07:43:32.463  6018  6018 I HeadsetPhoneState: updateServiceState service = 0,roam = 0
06-22 07:43:32.463  6018  6018 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
06-22 07:43:32.473  6018  6047 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-22 07:43:32.473  5296  5296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:32.473  6018  6055 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-22 07:43:32.473  5296  5296 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
06-22 07:43:32.473  5296  5296 D         : Cust_ConnectToPC   : Internet_Sharing>true
06-22 07:43:32.473  5296  5296 D         : Cust_ConnectToPC   : Modem_Link>false
06-22 07:43:32.473  5296  5296 D         : Cust_ConnectToPC   : spcsc>false
06-22 07:43:32.473  5296  5296 D         : Cust_ConnectToPC   : IPT>true
06-22 07:43:32.473  5296  5296 D         : Cust_ConnectToPC   : Singel_USB>false
06-22 07:43:32.473  5296  5296 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:43:32.473  5296  5296 E SmartNS_Utility: hasRemovableStorageSlot: true
06-22 07:43:32.473  5296  5296 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
06-22 07:43:32.473  5296  5296 D SmartNS_NSReceiver: onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
06-22 07:43:32.473  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:43:32.473   905   921 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.473  6018  6083 I bt-btu  : btu_task pending for preload complete event
06-22 07:43:32.473  6018  6055 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: java.lang.Throwable
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:652)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5696)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 07:43:32.473  1457  1457 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
06-22 07:43:32.473  6018  6055 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-22 07:43:32.473  5296  5296 I SmartNS_Utility: setISNotification
06-22 07:43:32.473  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
06-22 07:43:32.473  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:32.473  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:32.473   905  1495 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.483  1123  1123 I RemoteViews: reapply : com.android.settings 1 36
06-22 07:43:32.483  1199  1223 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
06-22 07:43:32.483  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
06-22 07:43:32.483  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:32.483  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:32.483   905  1495 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.493  6092  6092 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
06-22 07:43:32.503  1123  1123 D BluetoothAdapter: 404492909: getState(). Returning 11
06-22 07:43:32.503  1123  1123 I QuickSettingMiniLite: updateLiteState:no connect device!
,06-22 07:43:32.503  5296  5296 D SmartNS_NSReceiver: Tethered state change:false isNSOpening:false
06-22 07:43:32.513  1199  3757 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
06-22 07:43:32.513  6093  6093 D wpa_supplicant: wpa_supplicant v2.3-devel-5.0.1
06-22 07:43:32.513  6093  6093 D wpa_supplicant: random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
06-22 07:43:32.513  6093  6093 D wpa_supplicant: random: Trying to read entropy from /dev/random
06-22 07:43:32.513  1123  1123 I RemoteViews: reapply : com.android.settings 3 36
06-22 07:43:32.513  6093  6093 D wpa_supplicant: random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
06-22 07:43:32.513  6093  6093 D wpa_supplicant: Global control interface '@android:wpa_wlan0'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: Using Android control socket 'wpa_wlan0'
06-22 07:43:32.513  6093  6093 I wpa_supplicant: Successfully initialized wpa_supplicant
06-22 07:43:32.513  6093  6093 D wpa_supplicant: Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
06-22 07:43:32.513  6070  6070 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
06-22 07:43:32.513  6070  6070 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
06-22 07:43:32.513  6093  6093 D wpa_supplicant: ctrl_interface='/data/misc/wifi/sockets'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: driver_param='use_multi_chan_concurrent=1'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: update_config=1
06-22 07:43:32.513  6093  6093 D wpa_supplicant: uuid=12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:32.513  6093  6093 D wpa_supplicant: device_name='Android_d8c3'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: manufacturer='HTC'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: model_name='HTC_PHONE'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: model_number='1234'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: config_methods='virtual_push_button physical_display keypad'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: p2p_ssid_postfix='-Android_d8c3'
06-22 07:43:32.513  6093  6093 D wpa_supplicant: persistent_reconnect=1
06-22 07:43:32.513  6093  6093 D wpa_supplicant: key_mgmt_offload=1
06-22 07:43:32.513  6093  6093 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-22 07:43:32.513  6093  6093 D wpa_supplicant: nl80211: RFKILL status not available
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:1
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:5
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:2
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:4
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-14-72:1
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:6
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Using driver-based off-channel TX
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Using driver-based roaming
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: TDLS supported
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: TDLS external setup
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supports Probe Response offload in AP mode
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported key managment offloads 0x0
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Supported key derivation offloads 0x0
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Use separate P2P group interface (driver advertised support)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Enable multi-channel concurrent (driver advertised support)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: interface p2p0 in phy phy0
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Set mode ifindex 23 iftype 2 (STATION)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Subscribe to mgmt frames with non-AP handle 0xb7ba4170
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0104
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=040a
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=040b
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=040c
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=040d
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=090a
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=090b
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=090c
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=090d
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0409506f9a09
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=7f506f9a09
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0801
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=040e
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=06
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0a07
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0a11
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7ba4170 match=0a1a
06-22 07:43:32.523  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=23 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: driver param='use_multi_chan_concurrent=1'
06-22 07:43:32.523  6093  6093 D wpa_supplicant: Add interface p2p0 to a new radio phy0
06-22 07:43:32.523  6093  6093 I wpa_supplicant: htc_wext_command_init +
06-22 07:43:32.523  6093  6093 E wpa_supplicant: htc_wext_command_init: ifname=p2p0, ignore
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=00
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 2402-2472 @ 40 MHz 20 mBm
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: 57240-63720 @ 2160 MHz 0 mBm
06-22 07:43:32.523  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.523   905  1003 D Tethering: interfaceLinkStateChanged p2p0, false
06-22 07:43:32.523   905  1003 D Tethering: interfaceStatusChanged p2p0, false
06-22 07:43:32.523   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.523   905  1003 D Tethering: interfaceLinkStateChanged p2p0, false
06-22 07:43:32.523   905  1003 D Tethering: interfaceStatusChanged p2p0, false
06-22 07:43:32.523   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.523  6099  6099 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
06-22 07:43:32.533  6100  6100 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
06-22 07:43:32.543  6102  6102 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
06-22 07:43:32.543   905  1637 I ActivityManager: Start proc com.htc.videocenter for broadcast com.htc.videohub.ui/com.htc.videohub.engine.LiteLRBroadcastReceiver: pid=6103 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-22 07:43:32.543   905  1637 D Process : killProcessQuiet, pid=4931
06-22 07:43:32.543   905  1637 I ActivityManager: Killing 4931:com.htc.mediamanager/u0a29 (adj 15): empty #17
06-22 07:43:32.543   905  1637 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
06-22 07:43:32.543  6112  6112 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
06-22 07:43:32.553  6114  6114 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
06-22 07:43:32.553  6120  6120 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
06-22 07:43:32.563   905  1528 I ActivityManager: Recipient 4931
,06-22 07:43:32.593   905  1076 E WifiStateMachine: setWifiState: enabling
,06-22 07:43:32.623   905  1528 D Process : killProcessQuiet, pid=4931
06-22 07:43:32.623   905  1528 W libprocessgroup: failed to open /acct/uid_10029/pid_4931/cgroup.procs: No such file or directory
06-22 07:43:32.623   905  1528 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:32.623  1123  1123 D WIFI_ICON: updateWifiState: WIFI_STATE_CHANGED disabled
06-22 07:43:32.623   905  1076 E WifiStateMachine: Supplicant start successful
06-22 07:43:32.623  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:32.623   905  1076 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-22 07:43:32.623   905  1076 D WifiMonitor: connecting to supplicant
06-22 07:43:32.623   905   905 D WirelessDisplayService: WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
06-22 07:43:32.623  1123  1302 I IntentController: receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
06-22 07:43:32.623  6093  6093 I wpa_supplicant: wapi_supplicant_init: Init WAI packet p2p0
06-22 07:43:32.623  6093  6093 D wpa_supplicant:  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
06-22 07:43:32.623  6093  6093 D wpa_supplicant:  Initialization: WAPI: Initializing WAPI Supplicant
06-22 07:43:32.623  6093  6093 E wpa_supplicant:  Initialization: WAPI:set Staues=1 
06-22 07:43:32.623  5914  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.623  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.623  6093  6093 D wpa_supplicant: p2p0: RSN: flushing PMKID list in the driver
06-22 07:43:32.623  6093  6093 D wpa_supplicant: nl80211: Flush PMKIDs
06-22 07:43:32.623  6093  6093 D wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,06-22 07:43:32.633  6103  6103 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1426
,06-22 07:43:32.633  6103  6103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:43:32.663  6093  6093 D wpa_supplicant: TDLS: TDLS operation supported by driver
06-22 07:43:32.663   905  1000 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6125 uid=10042 gids={50042, 9997, 3002, 3001, 3003} abi=armeabi-v7a
06-22 07:43:32.663  6093  6093 D wpa_supplicant: TDLS: Driver uses external link setup
06-22 07:43:32.663  6093  6093 D wpa_supplicant: p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:32.663  6093  6093 D wpa_supplicant: EAPOL: SUPP_PAE entering state DISCONNECTED
06-22 07:43:32.663   905  1636 I ActivityManager: Killing 5277:com.google.android.partnersetup/u0a28 (adj 15): empty #17
06-22 07:43:32.663  6093  6093 D wpa_supplicant: EAPOL: Supplicant port status: Unauthorized
06-22 07:43:32.663  6093  6093 D wpa_supplicant: nl80211: Skip set_supp_port(unauthorized) while not associated
06-22 07:43:32.663  6093  6093 D wpa_supplicant: EAPOL: KEY_RX entering state NO_KEY_RECEIVE
06-22 07:43:32.663  6093  6093 D wpa_supplicant: EAPOL: SUPP_BE entering state INITIALIZE
06-22 07:43:32.663  6093  6093 D wpa_supplicant: EAP: EAP entering state DISABLED
06-22 07:43:32.663  6093  6093 D wpa_supplicant: Using existing control interface directory.
06-22 07:43:32.663  6093  6093 D wpa_supplicant: P2P: Add operating class 81
06-22 07:43:32.663  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
06-22 07:43:32.663  6093  6093 D wpa_supplicant: P2P: Own listen channel: 81:6
06-22 07:43:32.663   905  1636 D Process : killProcessQuiet, pid=5277
06-22 07:43:32.663   905  1636 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
06-22 07:43:32.663  6093  6093 I wpa_supplicant: set country (DE) from /data/misc/wifi/countryID.conf
06-22 07:43:32.663  6093  6093 I wpa_supplicant: Get_p2p_auto_channel: Auto country group 1: ch36
06-22 07:43:32.663  6093  6093 D wpa_supplicant: P2P: Get_p2p_auto_channel: op_channel = 36, op_reg_class = 116
06-22 07:43:32.673  6093  6093 D wpa_supplicant: P2P: initialized
06-22 07:43:32.673  6093  6093 D wpa_supplicant: P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
06-22 07:43:32.673  6093  6093 D wpa_supplicant: P2P: cli_channels:
06-22 07:43:32.673  6093  6093 D wpa_supplicant: p2p0: Added interface p2p0
06-22 07:43:32.673  6093  6093 D wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
06-22 07:43:32.673  6093  6093 D wpa_supplicant: nl80211: Set p2p0 operstate 0->0 (DORMANT)
06-22 07:43:32.673  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=23 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:32.673  6093  6093 D wpa_supplicant: Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: ctrl_interface='/data/misc/wifi/sockets'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: disable_scan_offload=1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: driver_param='use_p2p_group_interface=1'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: update_config=1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: uuid=12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: device_name='htc_europe'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: manufacturer='HTC'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: model_name='HTC One_M8'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: model_number='HTC One_M8'
06-22 07:43:32.673  6093  6093 D wpa_supplicant: config_methods='physical_display virtual_push_button'
06-22 07:43:32.673  6093  6093 D, wpa_supplicant: hs20=1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: interworking=1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: external_sim=1
06-22 07:43:32.673  6093  6093 D wpa_supplicant: key_mgmt_offload=1
06-22 07:43:32.673  6131  6131 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 50:2e:6c:ac:21:50 
06-22 07:43:32.673  6137  6137 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,06-22 07:43:32.683  1123  1123 I QuickSettingWifi: receive.wifiState:WIFI_STATE_ENABLING setEnable:false,
,06-22 07:43:32.693   905  1088 I ActivityManager: Recipient 5277,
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: Priority group 254,
06-22 07:43:32.733  6093  6093 D wpa_supplicant:    id=2 ssid='NG700'
06-22 07:43:32.733  6093  6093 D wpa_supplicant: Priority group 217
06-22 07:43:32.733  6093  6093 D wpa_supplicant:    id=3 ssid='NG7005g'
06-22 07:43:32.733  6093  6093 D wpa_supplicant: Priority group 5
06-22 07:43:32.733  6093  6093 D wpa_supplicant:    id=1 ssid='Ozz'
06-22 07:43:32.733  6093  6093 D wpa_supplicant: Priority group 2
06-22 07:43:32.733  6093  6093 D wpa_supplicant:    id=0 ssid='huawei mate 7',
06-22 07:43:32.733  6093  6093 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: RFKILL status not available
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:1
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:5
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:2
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:4
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-14-72:1
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported cipher 00-0f-ac:6
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Using driver-based off-channel TX,
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Using driver-based roaming
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: TDLS supported
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: TDLS external setup
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supports Probe Response offload in AP mode
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15,
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23,
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported key managment offloads 0x0
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Supported key derivation offloads 0x0
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Use separate P2P group interface (driver advertised support)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Enable multi-channel concurrent (driver advertised support)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: interface wlan0 in phy phy0
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Set mode ifindex 22 iftype 2 (STATION)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bb5060
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0104
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040a
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040b
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040c
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040d
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090a
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090b
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090c
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090d
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0409506f9a09
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=7f506f9a09
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0801
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040e
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=06
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a07
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a11
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a1a
06-22 07:43:32.733   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false
,06-22 07:43:32.733   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:32.733   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:32.733  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=22 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: driver param='use_p2p_group_interface=1'
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Use separate P2P group interface
06-22 07:43:32.733  6093  6093 D wpa_supplicant: Add interface wlan0 to existing radio phy0
06-22 07:43:32.733  6093  6093 I wpa_supplicant: htc_wext_command_init +
06-22 07:43:32.733  6093  6093 I wpa_supplicant: htc_wext_command_init -
06-22 07:43:32.733  6093  6093 I wpa_supplicant: [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
06-22 07:43:32.733  6093  6093 I wpa_supplicant: Don't set 00 to countryID.conf
06-22 07:43:32.733  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
06-22 07:43:32.733  6093  6093 D wpa_supplicant: wlan0: Event CHANNEL_LIST_CHANGED (30) received
,06-22 07:43:32.733  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=00
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2402-2472 @ 40 MHz 20 mBm
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 57240-63720 @ 2160 MHz 0 mBm
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.733  6093  6093 D wpa_supplicant: P2P: Add operating class 81
06-22 07:43:32.733  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
06-22 07:43:32.733  6093  6093 D wpa_supplicant: P2P: Update channel list
06-22 07:43:32.733  6093  6093 D wpa_supplicant: P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
06-22 07:43:32.733  6093  6093 D wpa_supplicant: P2P: cli_channels:
06-22 07:43:32.733  6093  6093 D wpa_supplicant: p2p0: Updating hw mode
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=00
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2402-2472 @ 40 MHz 20 mBm
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 57240-63720 @ 2160 MHz 0 mBm
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=00
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2402-2472 @ 40 MHz 20 mBm
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
,06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: 57240-63720 @ 2160 MHz 0 mBm
06-22 07:43:32.733  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
,06-22 07:43:32.873  6093  6093 I wpa_supplicant: wapi_supplicant_init: Init WAI packet wlan0
,06-22 07:43:32.873  6093  6093 D wpa_supplicant:  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
06-22 07:43:32.873  6093  6093 D wpa_supplicant:  Initialization: WAPI: Initializing WAPI Supplicant
06-22 07:43:32.873  6093  6093 E wpa_supplicant:  Initialization: WAPI:set Staues=1 ,
06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0,
06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.873   905  1088 W libprocessgroup: failed to open /acct/uid_10028/pid_5277/cgroup.procs: No such file or directory
06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
06-22 07:43:32.873   905  1088 D Process : killProcessQuiet, pid=5277
06-22 07:43:32.873   905  1088 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:32.873  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0,
,06-22 07:43:32.873  6093  6093 D wpa_supplicant: wlan0: RSN: flushing PMKID list in the driver,
06-22 07:43:32.873  6093  6093 D wpa_supplicant: nl80211: Flush PMKIDs
06-22 07:43:32.873  6018  6018 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 11
,06-22 07:43:32.883  6018  6018 V BluetoothSapReceiver: SapReceiver onReceive ,
,06-22 07:43:32.883  6018  6018 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
06-22 07:43:32.883  6018  6018 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
06-22 07:43:32.883  6018  6018 V BluetoothSapReceiver: startService = false
,06-22 07:43:32.893  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,06-22 07:43:32.903  6125  6125 D HtcWiFiWidget_WiFiWidgetProvider: onWiFiStateChanged() for widget: 
,06-22 07:43:32.903  6125  6125 D HtcWiFiWidget_WiFiWidgetProvider: updateWidget(context) for widget: 
,06-22 07:43:32.903   905  1585 D Process : killProcessQuiet, pid=5574,
06-22 07:43:32.903   905  1585 I ActivityManager: Killing 5574:com.htc.backup/u0a118 (adj 15): empty #17
06-22 07:43:32.903   905  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:32.913   905  1282 I ActivityManager: Recipient 5574,
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: TDLS: TDLS operation supported by driver,
06-22 07:43:32.923  6093  6093 D wpa_supplicant: TDLS: Driver uses external link setup
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:32.923  6093  6093 D wpa_supplicant: EAPOL: SUPP_PAE entering state DISCONNECTED
06-22 07:43:32.923  6093  6093 D wpa_supplicant: EAPOL: Supplicant port status: Unauthorized
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Skip set_supp_port(unauthorized) while not associated
06-22 07:43:32.923  6093  6093 D wpa_supplicant: EAPOL: KEY_RX entering state NO_KEY_RECEIVE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: EAPOL: SUPP_BE entering state INITIALIZE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: EAP: EAP entering state DISABLED
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: Using existing control interface directory.
06-22 07:43:32.923  6093  6093 I wpa_supplicant: set country (DE) from /data/misc/wifi/countryID.conf
06-22 07:43:32.923  6093  6093 I wpa_supplicant: Initial scan channel cmd: COUNTRY DE
06-22 07:43:32.923  6093  6093 I wpa_supplicant: wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wlan0: Event CHANNEL_LIST_CHANGED (30) received
06-22 07:43:32.923  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 81
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 115
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=4): 24 28 2c 30
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 116
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 24 2c
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 117
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 28 30
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Update channel list
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: cli_channels:
06-22 07:43:32.923  6093  6093 D wpa_supplicant: p2p0: Updating hw mode
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.923  6093  6093 I wpa_supplicant: Auto country group 1: ch36
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wlan0: Added interface wlan0
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Set wlan0 operstate 0->0 (DORMANT)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: random: Got 19/20 bytes from /dev/random
06-22 07:43:32.923  6093  6093 D wpa_supplicant: CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_905-2\x00
06-22 07:43:32.923  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
06-22 07:43:32.923  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Regulatory domain change
06-22 07:43:32.923  6093  6093 D wpa_supplicant:  * initiator=1
06-22 07:43:32.923  6093  6093 D wpa_supplicant:  * type=0
06-22 07:43:32.923  6093  6093 D wpa_supplicant:  * alpha2=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: wlan0: Event CHANNEL_LIST_CHANGED (30) received
06-22 07:43:32.923  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 81
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 115
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=4): 24 28 2c 30
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 116
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 24 2c
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Add operating class 117
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 28 30
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: Update channel list
06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,06-22 07:43:32.923  6093  6093 D wpa_supplicant: P2P: cli_channels:
06-22 07:43:32.923  6093  6093 D wpa_supplicant: p2p0: Updating hw mode
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:32.923  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:32.923   905  1076 E WifiStateMachine: transitionTo: destState=SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:32.923   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
06-22 07:43:32.923   905  1076 E WifiStateMachine: invokeExitMethods: InitialState
06-22 07:43:32.923   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=1
,06-22 07:43:32.923   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine: invokeEnterMethods: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131144
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
06-22 07:43:32.923   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
06-22 07:43:32.923   905  1076 E WifiStateMachine: deferMessage: msg=131144
06-22 07:43:32.923   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  6146 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131085
06-22 07:43:32.923   905  6146 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
,06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: deferMessage: msg=131085
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131149
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: setSuspendOptimizations: 2 true
06-22 07:43:32.923   905  1076 E WifiStateMachine: mSuspendOptNeedsDisabled 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131145
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_DISCONNECT 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: DefaultState
,06-22 07:43:32.923   905  1076 E WifiStateMachine:  DefaultState CMD_DISCONNECT 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131146
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_RECONNECT 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  DefaultState CMD_RECONNECT 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131101
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:32.923   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent DefaultState
,06-22 07:43:32.923   905  1076 D WifiStateMachine: Default got CMD_TETHER_STATE_CHANGE
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=131101
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:32.923   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent DefaultState
06-22 07:43:32.923   905  1076 D WifiStateMachine: Default got CMD_TETHER_STATE_CHANGE
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:32.923   905  1076 E WifiStateMachine: handleMessage: E msg.what=147457
06-22 07:43:32.923   905  1076 E WifiStateMachine: processMsg: SupplicantStartingState
06-22 07:43:32.923   905  1076 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
06-22 07:43:32.923   905  1076 E WifiStateMachine: Supplicant connection established
,06-22 07:43:32.923   905  1076 E WifiStateMachine: setWifiState: enabled
,06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Starting delayed sched scan,
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
06-22 07:43:32.973  6093  6093 I wpa_supplicant: wpa_supplicant_scan enter
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS: Building WPS IE for Probe Request
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Version (hardcoded 0x10)
,06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Request Type
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Config Methods (4288)
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * UUID-E
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Primary Device Type
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * RF Bands (3)
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Association State
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Configuration Error (0)
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Device Password ID (0)
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Manufacturer
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Model Name
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Model Number,
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Device Name
06-22 07:43:32.973  6093  6093 D wpa_supplicant: WPS:  * Version2 (0x20)
06-22 07:43:32.973  6093  6093 D wpa_supplicant: P2P: * P2P IE header
,06-22 07:43:32.973  6093  6093 D wpa_supplicant: P2P: * Capability dev=25 group=00
06-22 07:43:32.973  6093  6093 D wpa_supplicant: P2P: * Listen Channel: Regulatory Class 81 Channel 6
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Add radio work 'scan'@0xb7bb8158
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Starting radio work 'scan'@0xb7bb8158 after 0.000022 second wait
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: nl80211: scan request
06-22 07:43:32.973  6093  6093 D wpa_supplicant: Scan requested (ret=0) - scan timeout 10 seconds
06-22 07:43:32.973  6093  6093 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: nl80211: Scan trigger
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
06-22 07:43:32.973  6093  6093 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000046 seconds
06-22 07:43:32.973  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-22 07:43:32.973   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
06-22 07:43:32.973   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:43:32.973   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,06-22 07:43:32.973   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:43:32.973   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSID
06-22 07:43:32.973   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
06-22 07:43:32.973   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
06-22 07:43:32.973   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
06-22 07:43:32.973   905  6146 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
06-22 07:43:32.973   905  6146 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,06-22 07:43:33.003   905  1282 D Process : killProcessQuiet, pid=5574,
06-22 07:43:33.003   905  1282 W libprocessgroup: failed to open /acct/uid_10118/pid_5574/cgroup.procs: No such file or directory
06-22 07:43:33.003   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:33.003  1123  1123 D WIFI_ICON: updateWifiState: WIFI_STATE_CHANGED enabled
06-22 07:43:33.003   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
06-22 07:43:33.003  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.003   905   905 D WirelessDisplayService: WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
06-22 07:43:33.003  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER MACADDR'
06-22 07:43:33.003   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
06-22 07:43:33.003  5914  5914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:33.003  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:33.003  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET update_config 1'
06-22 07:43:33.003  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'update_config'='1'
06-22 07:43:33.003  6093  6093 D wpa_supplicant: update_config=1
06-22 07:43:33.003  6093  6093 D wpa_supplicant: wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:33.003  5914  5914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:33.003  5914  5914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:43:33.013  1123  1302 I IntentController: receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,06-22 07:43:33.013   905  1076 D WifiConfigStore: Loading config and enabling all networks 
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'LIST_NETWORKS'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 ssid'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='ssid'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 bssid'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='bssid'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 priority'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='priority'
,06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
,06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 psk'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='psk'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 proto'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='proto'
06-22 07:43:33.013   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
06-22 07:43:33.013  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
06-22 07:43:33.013  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
,06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 pairwise'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 group'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='group'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
06-22 07:43:33.023   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
06-22 07:43:33.023   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
,06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
06-22 07:43:33.023   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
06-22 07:43:33.023   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
06-22 07:43:33.023   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 eap'
,06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='eap'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 phase2'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='phase2'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 identity'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='identity'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 password'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='password'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 client_cert'
,06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 subject_match'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 engine'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='engine'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 engine_id'
,06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 key_id'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='key_id'
06-22 07:43:33.023   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
06-22 07:43:33.023  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 0 private_key'
06-22 07:43:33.023  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=0 name='private_key'
06-22 07:43:33.023   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:43:33.033   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["huawei mate 7"] key=psk
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 ssid"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 ssid'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='ssid'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 bssid"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 bssid'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='bssid'
,06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 priority"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 priority'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='priority'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 scan_ssid"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 scan_ssid'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='scan_ssid'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_tx_keyidx"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wep_tx_keyidx'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wep_tx_keyidx'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key0"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wep_key0'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wep_key0'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key1"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wep_key1'
,06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wep_key1'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key2"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wep_key2'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wep_key2'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wep_key3"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wep_key3'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wep_key3'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 psk"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 psk'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='psk'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: Do not allow key_data field to be exposed
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 proto"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 proto'
,06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='proto'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 key_mgmt"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 key_mgmt'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='key_mgmt'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 auth_alg"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 auth_alg'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='auth_alg'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 pairwise"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 pairwise'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='pairwise'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 group"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 group'
06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='group'
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_psk"
06-22 07:43:33.033  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wapi_psk'
,06-22 07:43:33.033  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wapi_psk'
06-22 07:43:33.033   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.033   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_psk_hex"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wapi_psk_hex'
,06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wapi_psk_hex'
06-22 07:43:33.043   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
06-22 07:43:33.093   905  1282 D PMS     : acquireWL(2738daba): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 WorkSource{1000 android}
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_cert"
06-22 07:43:33.093   905  1281 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2bb5fd6b}
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wapi_cert'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wapi_cert'
06-22 07:43:33.043   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_as_cert"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wapi_as_cert'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wapi_as_cert'
06-22 07:43:33.043   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 wapi_user_cert"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 wapi_user_cert'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='wapi_user_cert'
06-22 07:43:33.043   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 eap"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 eap'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='eap'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 phase2"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 phase2'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='phase2'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 identity"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 identity'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='identity'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 anonymous_identity"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 anonymous_identity'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='anonymous_identity'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 password"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 password'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='password'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 client_cert"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 client_cert'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='client_cert'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 ca_cert"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 ca_cert'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='ca_cert'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 subject_match"
,06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 subject_match'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='subject_match'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 engine"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 engine'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='engine'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 engine_id"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 engine_id'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='engine_id'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 key_id"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 key_id'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='key_id'
06-22 07:43:33.043   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 1 private_key"
06-22 07:43:33.043  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 1 private_key'
06-22 07:43:33.043  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=1 name='private_key'
06-22 07:43:33.043   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:43:33.053   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["Ozz"] key=psk
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ssid"
06-22 07:43:33.093   905   921 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.093   905   921 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.093   905   921 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.093   905   921 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.093   905   921 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.093   905   921 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ssid'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ssid'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 bssid"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 bssid'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='bssid'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 priority"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 priority'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='priority'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 scan_ssid"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 scan_ssid'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='scan_ssid'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_tx_keyidx"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_tx_keyidx'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_tx_keyidx'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key0"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key0'
06-22 07:43:33.053  6093  6093 D wpa_supplica,nt: CTRL_IFACE: GET_NETWORK id=2 name='wep_key0'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key1"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key1'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key1'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key2"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key2'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key2'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key3"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key3'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key3'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 psk"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 psk'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='psk'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: Do not allow key_data field to be exposed
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 proto"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 proto'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='proto'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_mgmt"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_mgmt'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_mgmt'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 auth_alg"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 auth_alg'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='auth_alg'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 pairwise"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 pairwise'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='pairwise'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 group"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 group'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='group'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk'
06-22 07:43:33.053   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk_hex"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk_hex'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk_hex'
06-22 07:43:33.053   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_cert"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_cert'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_cert'
06-22 07:43:33.053   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_as_cert"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_as_cert'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_as_cert'
06-22 07:43:33.053   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.103  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_user_cert"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_user_cert'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_user_cert'
06-22 07:43:33.053   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 eap"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 eap'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='eap'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 phase2"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 phase2'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='phase2'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 identity"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 identity'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='identity'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 anonymous_identity"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 anonymous_identity'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='anonymous_identity'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 password"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 password'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='password'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 client_cert"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 client_cert'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='client_cert'
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.113   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ca_cert"
06-22 07:43:33.113  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ca_cert'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ca_cert'
06-22 07:43:33.053   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 subject_match"
06-22 07:43:33.053  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 subject_match'
06-22 07:43:33.053  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='subject_match'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine_id"
06-22 07:43:33.113   905  1006 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-22 07:43:33.063  1123  1123 I QuickSettingWifi: receive.wifiState:WIFI_STATE_ENABLED setEnable:true
06-22 07:43:33.113   905  1006 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine_id'
06-22 07:43:33.113   905  1006 D WifiDisplayController: mWfdEnabled :false, networkInfo.isConnected() :false
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine_id'
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.113   905  1006 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_id"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_id'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_id'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 private_key"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 private_key'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='private_key'
06-22 07:43:33.063   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:43:33.063   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 ssid"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 ssid'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='ssid'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 bssid"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 bssid'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='bssid'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 priority"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 priority'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='priority'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 scan_ssid"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 scan_ssid'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='scan_ssid'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_tx_keyidx"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wep_tx_keyidx'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wep_tx_keyidx'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key0"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wep_key0'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wep_key0'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key1"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wep_key1'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wep_key1'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key2"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wep_key2'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wep_key2'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wep_key3"
06-22 07:43:33.123   905  1006 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_d8c3
06-22 07:43:33.123   905  1006 D WifiDisplayController:  deviceAddress: 02:ee:bd:dd:33:d2
06-22 07:43:33.123   905  1006 D WifiDisplayController:  primary type: 10-0050F204-5
06-22 07:43:33.123   905  1006 D WifiDisplayController:  secondary type: null
06-22 07:43:33.123   905  1006 D WifiDisplayController:  wps: 0
06-22 07:43:33.123   905  1006 D WifiDisplayController:  grpcapab: 0
06-22 07:43:33.123   905  1006 D WifiDisplayController:  devcapab: 0
06-22 07:43:33.123   905  1006 D WifiDisplayController:  status: 3
06-22 07:43:33.123   905  1006 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
06-22 07:43:33.123   905  1006 D WifiDisplayController:  WFD CtrlPort: 0
06-22 07:43:33.123   905  1006 D WifiDisplayController:  WFD MaxThroughput: 0
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wep_key3'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wep_key3'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 psk"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 psk'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='psk'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: Do not allow key_data field to be exposed
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 proto"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 proto'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='proto'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 key_mgmt"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 key_mgmt'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='key_mgmt'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 auth_alg"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 auth_alg'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='auth_alg'
06-22 07:43:33.063   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 pairwise"
06-22 07:43:33.063  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 pairwise'
06-22 07:43:33.063  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='pairwise'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 group"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 group'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='group'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_psk"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wapi_psk'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wapi_psk'
06-22 07:43:33.073   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.073  6125  6125 D HtcWiFiWidget_WiFiWidgetProvider: onWiFiStateChanged() for widget: 
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_psk_hex"
06-22 07:43:33.073  6125  6125 D HtcWiFiWidget_WiFiWidgetProvider: updateWidget(context) for widget: 
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wapi_psk_hex'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wapi_psk_hex'
06-22 07:43:33.073   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_cert"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wapi_cert'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wapi_cert'
06-22 07:43:33.073   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_as_cert"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wapi_as_cert'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wapi_as_cert'
06-22 07:43:33.073   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 wapi_user_cert"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 wapi_user_cert'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='wapi_user_cert'
06-22 07:43:33.073   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 eap"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 eap'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='eap'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 phase2"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 phase2'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='phase2'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 identity"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 identity'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='identity'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 anonymous_identity"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 anonymous_identity'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='anonymous_identity'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 password"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 password'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='password'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 client_cert"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 client_cert'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='client_cert'
06-22 07:43:33.123  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 ca_cert"
06-22 07:43:33.123  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 ca_cert'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='ca_cert'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 subject_match"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 subject_match'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='subject_match'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 engine"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 engine'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='engine'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 engine_id"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 engine_id'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='engine_id'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 key_id"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 key_id'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='key_id'
06-22 07:43:33.073   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 3 private_key"
06-22 07:43:33.073  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 3 private_key'
06-22 07:43:33.073  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=3 name='private_key'
06-22 07:43:33.073   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:43:33.093   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
06-22 07:43:33.093   905  1076 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-22 07:43:33.093   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name htc_europe"
06-22 07:43:33.093  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET device_name htc_europe'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'device_name'='htc_europe'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: device_name='htc_europe'
06-22 07:43:33.093   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
06-22 07:43:33.093  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET manufacturer HTC'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'manufacturer'='HTC'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: manufacturer='HTC'
06-22 07:43:33.093   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One_M8"
06-22 07:43:33.093  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET model_name HTC One_M8'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'model_name'='HTC One_M8'
06-22 07:43:33.093  6093  6093 D wpa_supplicant: model_name='HTC One_M8'
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One_M8"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET model_number HTC One_M8'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'model_number'='HTC One_M8'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: model_number='HTC One_M8'
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: config_methods='physical_display virtual_push_button'
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET device_type 10-0050F204-5'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'device_type'='10-0050F204-5'
06-22 07:43:33.103   905  1076 E WifiStateMachine: transitionTo: destState=DriverStartedState
06-22 07:43:33.103   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:33.103  5727  5727 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:43:33.103   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
06-22 07:43:33.103   905  1076 E WifiStateMachine: invokeExitMethods: SupplicantStartingState
06-22 07:43:33.103   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=1,j=1
06-22 07:43:33.103   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=2
06-22 07:43:33.103   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
06-22 07:43:33.103   905  1076 E WifiStateMachine: invokeEnterMethods: SupplicantStartedState
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SCAN_INTERVAL 15'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Setting scan interval: 15 sec
06-22 07:43:33.103   905  1076 D WifiNative-HAL: Setting external_sim to 1
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET external_sim 1'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'external_sim'='1'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: external_sim=1
06-22 07:43:33.103   905  1076 D WifiStateMachine: Setting OUI to DA-A1-19
06-22 07:43:33.103   905  1076 I WifiNative-HAL: startHal
06-22 07:43:33.103   905  1076 E wifi    : getStaticLongField sWifiHalHandle 0xa08bf83c
06-22 07:43:33.103   905  1076 I WifiNative-HAL: Could not start hal
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'STA_AUTOCONNECT 0'
06-22 07:43:33.103   905  1076 E WifiStateMachine: invokeEnterMethods: DriverStartedState
06-22 07:43:33.103   905  1076 E WifiStateMachine: Driverstarted State enter
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 4096
06-22 07:43:33.103   905  1076 E WifiStateMachine: DriverStartedState call setCountryCode()
06-22 07:43:33.103   905  1076 E WifiStateMachine: setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
06-22 07:43:33.103   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.103   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 0
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-STOP'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 4096
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 4096
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-START'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 4096
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-STOP'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 4096
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 4096
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER RXFILTER-START'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 4096
06-22 07:43:33.103   905  1076 D WifiDataStallTracker: setDhcpActive: false
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'STATUS'
06-22 07:43:33.103   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,06-22 07:43:33.103   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=3 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:43:33.133   905  1077 D WifiService: New client listening to asynchronous messages
06-22 07:43:33.103   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:43:33.103   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
06-22 07:43:33.103   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSID
06-22 07:43:33.103   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
06-22 07:43:33.103   905  1076 E WifiStateMachine: transitionTo: destState=DisconnectedState
06-22 07:43:33.103   905  1076 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state DriverStartedState suppState:UninitializedState
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 1'
06-22 07:43:33.103  6093  6093 I wpa_supplicant: SET_SCREEN_ON:On
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_keepalive +
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_keepalive: enable=0, type=2, interval=15
06-22 07:43:33.103  6093  6093 D wpa_supplicant: getPrivFuncNum +	
06-22 07:43:33.103  6093  6093 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING (0)+
06-22 07:43:33.103  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
06-22 07:43:33.103   905  1076 I WifiNative-HAL: startHal
06-22 07:43:33.103   905  1076 E wifi    : getStaticLongField sWifiHalHandle 0xa08bf7fc
06-22 07:43:33.103   905  1076 I WifiNative-HAL: Could not start hal
06-22 07:43:33.103   905  1076 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
06-22 07:43:33.103   905  1076 E WifiStateMachine: handleScreenStateChanged Exit: true
06-22 07:43:33.103   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
06-22 07:43:33.103  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET ps 1'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'ps'='1'
06-22 07:43:33.103  6093  6093 D wpa_supplicant: nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
06-22 07:43:33.103  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.143   905  1076 D WifiStateMachine: Wifi band: 0, ScanBroadCastCounter: 0
06-22 07:43:33.103   905  1075 D libc    : [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
06-22 07:43:33.103   905  1075 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:33.113   905  1075 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-22 07:43:33.113   905  1076 E WifiStateMachine: Driverstarted State enter done
06-22 07:43:33.113   905  1076 E WifiStateMachine: moveDeferredMessageAtFrontOfQueue; what=131085
06-22 07:43:33.113   905  1076 E WifiStateMachine: moveDeferredMessageAtFrontOfQueue; what=131144
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:33.113   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
06-22 07:43:33.113   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=1,j=3
06-22 07:43:33.113   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=4
06-22 07:43:33.113   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
06-22 07:43:33.113   905  1076 E WifiStateMachine: invokeEnterMethods: ConnectModeState
06-22 07:43:33.113   905  1076 E WifiStateMachine: invokeEnterMethods: DisconnectedState
06-22 07:43:33.113   905  1076 E WifiStateMachine: DisconnectedState call setCountryCode()
06-22 07:43:33.113   905  1076 E WifiStateMachine:  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
06-22 07:43:33.113   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: Ongoing scan action - reject new request
06-22 07:43:33.113   905  1076 E WifiStateMachine: setScanAlarm true period 10000 initial delay 3000
06-22 07:43:33.113   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: E msg.what=131144
06-22 07:43:33.113   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.113   905  1076 E WifiStateMachine:  DisconnectedState !CMD_SET_OPERATIONAL_MODE 1 0
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: E msg.what=131085
06-22 07:43:33.113   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.113   905  1076 E WifiStateMachine:  DisconnectedState !CMD_START_DRIVER 0 0
06-22 07:43:33.113   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.113   905  1076 E WifiStateMachine:  ConnectModeState !CMD_START_DRIVER 0 0
06-22 07:43:33.113   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.113   905  1076 E WifiStateMachine:  DriverStartedState !CMD_START_DRIVER 0 0
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.113   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.113   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.113   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=99932  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-22 07:43:33.113   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
06-22 07:43:33.113   905  1076 E WifiStateMachine: setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
06-22 07:43:33.113   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SET persistent_reconnect 1"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
06-22 07:43:33.113  6093  6093 D wpa_supplicant: GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'SET persistent_reconnect 1'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'persistent_reconnect'='1'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: persistent_reconnect=1
06-22 07:43:33.143  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
06-22 07:43:33.143  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.113  6093  6093 D wpa_supplicant: P2P: New SSID postfix: -Android_d8c3
06-22 07:43:33.113   905   905 D WifiScanningService: SCAN_AVAILABLE : 3
06-22 07:43:33.113   905   905 D RttService: SCAN_AVAILABLE : 3
06-22 07:43:33.113   905  1095 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:43:33.113   905  1095 I WifiNative-HAL: startHal
06-22 07:43:33.113   905  1096 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:43:33.113   905   905 V AudioService: Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.113   905   905 V AudioService:     Client/Owner: Client
06-22 07:43:33.113   905   905 V AudioService:     GroupId: 
06-22 07:43:33.113   905   905 V AudioService:     Passphrase: 
06-22 07:43:33.113   905   905 V AudioService:     SessionId: 0
06-22 07:43:33.113   905   905 V AudioService:     IP Address: }
06-22 07:43:33.113   905   905 D HtcEffectManagerBase: onEventChanged id=5 status=false
06-22 07:43:33.113   905   905 D HtcEffectManager: checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
06-22 07:43:33.113   905   905 D HtcEffectManager: convertEffect before=902
06-22 07:43:33.113   905   905 D HtcEffectManager: convertEffect after=902
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SET device_name Android_d8c3"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 64 38 63 33
06-22 07:43:33.113  6093  6093 D wpa_supplicant: GLOBAL_CTRL_IFACE SET 'device_name'='Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'SET device_name Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'device_name'='Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: device_name='Android_d8c3'
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_d8c3"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 64 38 ...
06-22 07:43:33.113  6093  6093 D wpa_supplicant: GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'SET p2p_ssid_postfix -Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p_ssid_postfix='-Android_d8c3'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: P2P: New SSID postfix: -Android_d8c3
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
06-22 07:43:33.113  6093  6093 D wpa_supplicant: GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'SET device_type 10-0050F204-5'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'device_type'='10-0050F204-5'
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
06-22 07:43:33.113  6093  6093 D wpa_supplicant: GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
06-22 07:43:33.113  6093  6093 D wpa_supplicant: config_methods='virtual_push_button physical_display keypad'
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: p2p0: Control interface command 'P2P_SET conc_pref sta'
06-22 07:43:33.113  6093  6093 I wpa_supplicant: [p2p command] (P2P_SET conc_pref sta)
06-22 07:43:33.113  6093  6093 D wpa_supplicant: Single channel concurrency preference: sta
06-22 07:43:33.113   905  1075 D WifiNative-HAL: p2pGetDeviceAddress
06-22 07:43:33.113   905  1075 W WifiHW  : QCOM Debug wifi_send_command "STATUS"
06-22 07:43:33.113  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
06-22 07:43:33.113   905  1075 D WifiNative-HAL: p2pGetDeviceAddress returning 02:ee:bd:dd:33:d2
06-22 07:43:33.113  5296  6163 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.123   905  1095 E wifi    : getStaticLongField sWifiHalHandle 0x9f14997c
06-22 07:43:33.123   905  1095 I WifiNative-HAL: Could not start hal
06-22 07:43:33.123   905  1095 E WifiScanningService: could not start HAL
06-22 07:43:33.123   905  1075 W WifiHW  : QCOM Debug wifi_send_command "P2P_FLUSH"
06-22 07:43:33.123  6093  6093 D wpa_supplicant: p2p0: Control interface command 'P2P_FLUSH'
06-22 07:43:33.123  6093  6093 I wpa_supplicant: [p2p command] (P2P_FLUSH)
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: Stopping find
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: Clear timeout (state=IDLE)
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: State IDLE -> IDLE
06-22 07:43:33.123  6093  6093 D wpa_supplicant: wpa_driver_set_ap_wps_p2p_ie: Entry
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: Stopping find
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: Clear timeout (state=IDLE)
06-22 07:43:33.123  6093  6093 D wpa_supplicant: P2P: State IDLE -> IDLE
06-22 07:43:33.123  6093  6093 D wpa_supplicant: wpa_driver_set_ap_wps_p2p_ie: Entry
06-22 07:43:33.123   905  1075 W WifiHW  : QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
06-22 07:43:33.123  6093  6093 D wpa_supplicant: p2p0: Control interface command 'P2P_SERVICE_FLUSH'
06-22 07:43:33.123  6093  6093 I wpa_supplicant: [p2p command] (P2P_SERVICE_FLUSH)
06-22 07:43:33.123   905  1075 W WifiHW  : QCOM Debug wifi_send_command "LIST_NETWORKS"
06-22 07:43:33.123  6093  6093 D wpa_supplicant: p2p0: Control interface command 'LIST_NETWORKS'
06-22 07:43:33.123   905  1075 W WifiHW  : QCOM Debug wifi_send_command "SAVE_CONFIG"
06-22 07:43:33.123  6093  6093 D wpa_supplicant: RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
06-22 07:43:33.123  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.123  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.123  6093  6093 D wpa_supplicant: wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.123  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
06-22 07:43:33.123  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
06-22 07:43:33.123  6093  6093 D wpa_supplicant: p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.123   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 1
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.123  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.123   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=99945  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-22 07:43:33.123   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.123   905  1076 E WifiStateMachine: handleMessage: E msg.what=131323
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  DisconnectedState !what:131323 0 0
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  ConnectModeState !what:131323 0 0
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  DriverStartedState !what:131323 0 0
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  SupplicantStartedState !what:131323 0 0
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  DefaultState !what:131323 0 0
06-22 07:43:33.123   905  1076 E WifiStateMachine: setOperatorSSID enter
06-22 07:43:33.123   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.123   905  1076 E WifiStateMachine: handleMessage: E msg.what=131143
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  DisconnectedState !CMD_START_SCAN 10025 0 ic=0 proc(ms):33 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:1990365205] from screen [on:0 period:1990365205]
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.123   905  1076 E WifiStateMachine:  ConnectModeState !CMD_START_SCAN 10025 0 ic=0 proc(ms):34 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990365206]
06-22 07:43:33.123   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  DriverStartedState !CMD_START_SCAN 10025 0 ic=0 proc(ms):34 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=40000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1990365206]
06-22 07:43:33.133   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
06-22 07:43:33.133  6093  6093 D wpa_supplicant: Ongoing scan action - reject new request
06-22 07:43:33.133   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.133   905  1076 E WifiStateMachine: handleMessage: E msg.what=131104
06-22 07:43:33.133   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  DisconnectedState !what:131104 0 0
06-22 07:43:33.133   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  ConnectModeState !what:131104 0 0
06-22 07:43:33.133   905  1076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-22 07:43:33.133   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
06-22 07:43:33.133  6093  6093 D wpa_supplicant: CTRL_IFACE: field=AIR_MODE id=0
06-22 07:43:33.133  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=1): [REMOVED]
06-22 07:43:33.133   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.133   905  1076 E WifiStateMachine: handleMessage: E msg.what=131162
06-22 07:43:33.133   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  DisconnectedState !CMD_SET_FREQUENCY_BAND 0 0
06-22 07:43:33.133   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  ConnectModeState !CMD_SET_FREQUENCY_BAND 0 0
06-22 07:43:33.133   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.133   905  1076 E WifiStateMachine:  DriverStartedState !CMD_SET_FREQUENCY_BAND 0 0
06-22 07:43:33.133   905  1076 E WifiStateMachine: set frequency band 0
06-22 07:43:33.133   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER SETBAND 0'
06-22 07:43:33.133  6093  6093 D wpa_supplicant: SETBAND: 0
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 4096
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Event CHANNEL_LIST_CHANGED (30) received
06-22 07:43:33.133  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Add operating class 81
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Add operating class 115
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=4): 24 28 2c 30
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Add operating class 116
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 24 2c
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Add operating class 117
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Channels - hexdump(len=2): 28 30
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: Update channel list
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
06-22 07:43:33.133  6093  6093 D wpa_supplicant: P2P: cli_channels:
06-22 07:43:33.133  6093  6093 D wpa_supplicant: p2p0: Updating hw mode
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: Regulatory information - country=DE
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 2400-2483 @ 40 MHz 20 mBm
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5150-5250 @ 80 MHz 20 mBm (no outdoor)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5250-5350 @ 80 MHz 20 mBm (no outdoor) (DFS)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 5470-5725 @ 80 MHz 27 mBm (DFS)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
06-22 07:43:33.133  6093  6093 D wpa_supplicant: nl80211: Added 802.11b mode based on 802.11g information
06-22 07:43:33.133   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
06-22 07:43:33.133   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
06-22 07:43:33.133   905  6146 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
06-22 07:43:33.133   905  6146 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
06-22 07:43:33.133   905  1076 E WifiStateMachine: did set frequency band 0
06-22 07:43:33.133   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Control interface command 'BSS_FLUSH 0'
06-22 07:43:33.133   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
06-22 07:43:33.133  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
06-22 07:43:33.133  6093  6093 D wpa_supplicant: Ongoing scan action - reject new request
06-22 07:43:33.133   905  1076 E WifiStateMachine: done set frequency band 0
06-22 07:43:33.133   905   905 E WifiTrafficPoller: ADD_CLIENT: 7
06-22 07:43:33.133  5296  6163 D WISPrService: wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.143  5296  6163 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.143   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent DriverStartedState
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 3 0 rt=99959  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-22 07:43:33.143   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
06-22 07:43:33.143   905  1076 E WifiStateMachine: setDetailed state, old =SCANNING and new state=SCANNING hidden=false
06-22 07:43:33.143   905  1076 E WifiStateMachine: setDetailed state send new extra info0x
06-22 07:43:33.143   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 3 0 rt=99960  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: E msg.what=131154
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DisconnectedState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DriverStartedState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: E msg.what=131127
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DisconnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
06-22 07:43:33.143  5296  6163 D WISPrService: wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.143   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 2
06-22 07:43:33.143  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: E msg.what=131129
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DisconnectedState !CMD_CLEAR_BLACKLIST 0 0
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
06-22 07:43:33.143   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
06-22 07:43:33.143  6093  6093 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
06-22 07:43:33.143  6093  6093 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
06-22 07:43:33.143   905  6146 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
06-22 07:43:33.143   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=5 dispatchEvent: BLACKLIST CLEAR 
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: E msg.what=143371
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DisconnectedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  ConnectModeState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DriverStartedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  SupplicantStartedState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:43:33.143   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:33.143   905  1076 E WifiStateMachine:  DefaultState !P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
06-22 07:43:33.143   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.143  5296  6163 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.143  5296  6163 D WISPrService: wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.163  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:1
06-22 07:43:33.173  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
,06-22 07:43:33.193  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:1,
,06-22 07:43:33.343  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=23 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP]),
06-22 07:43:33.343   905  1003 D Tethering: interfaceLinkStateChanged p2p0, false
,06-22 07:43:33.343   905  1003 D Tethering: interfaceStatusChanged p2p0, false
06-22 07:43:33.343   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,06-22 07:43:33.553  6093  6093 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: nl80211: New scan results available
06-22 07:43:33.553  6093  6093 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
06-22 07:43:33.553  6093  6093 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: Scan completed in 0.579540 seconds
,06-22 07:43:33.553  6093  6093 D wpa_supplicant: nl80211: Received scan results (12 BSSes)
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2447 level=-51
06-22 07:43:33.563   905  1076 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:13935 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14100 com.android.server.wifi.WifiStateMachine.access$5400:265 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7908 
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2447 level=-51,
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2412 level=-52
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2412 level=-65
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:70 freq=2412 level=-77
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 00:1a:ef:42:f2:b0 freq=2412 level=-79
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 84:b2:61:0f:9c:30 freq=2462 level=-82
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 00:16:a6:1e:e0:a4 freq=2422 level=-85
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] f4:f2:6d:85:e5:9e freq=2412 level=-89
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 84:b2:61:1a:ce:73 freq=2412 level=-77,
,06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] 84:b2:61:0f:9c:33 freq=2462 level=-82
06-22 07:43:33.553  6093  6093 I wpa_supplicant: [NULL] e4:aa:5d:fc:5b:f3 freq=2437 level=-88
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Start scan result update 1,
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 1 BSSID f4:f2:6d:22:99:3e SSID 'NG700'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 3 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 4 BSSID 84:b2:61:1a:ce:70 SSID '\x00'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 5 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 6 BSSID 84:b2:61:0f:9c:30 SSID '\x00'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 7 BSSID 00:16:a6:1e:e0:a4 SSID ''
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 8 BSSID f4:f2:6d:85:e5:9e SSID 'cvbtemp'
,06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 9 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 10 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS'
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: BSS: Add new id 11 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS'
,06-22 07:43:33.553  6093  6093 D wpa_supplicant: BSS: last_scan_res_used=12/32
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: Scan-only results received
06-22 07:43:33.553  6093  6093 D wpa_supplicant: wlan0: Radio work 'scan'@0xb7bb8158 done in 0.581063 seconds
06-22 07:43:33.553  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8b19 len=8
06-22 07:43:33.553  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
06-22 07:43:33.553   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 f0:f2:6d:22:99:3e]
06-22 07:43:33.553   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false,
06-22 07:43:33.553   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 f4:f2:6d:22:99:3e]
06-22 07:43:33.553   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:33.553   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.553   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 00:1f:27:54:70:c0]
06-22 07:43:33.553   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 00:1f:27:54:70:c1]
06-22 07:43:33.553   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 84:b2:61:1a:ce:70]
,06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 00:1a:ef:42:f2:b0]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 84:b2:61:0f:9c:30]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 00:16:a6:1e:e0:a4]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 f4:f2:6d:85:e5:9e]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 9 84:b2:61:1a:ce:73]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 84:b2:61:0f:9c:33]
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 e4:aa:5d:fc:5b:f3]
06-22 07:43:33.563   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
06-22 07:43:33.563   905  6146 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
06-22 07:43:33.563   905  6146 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
06-22 07:43:33.563   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: WPS-AP-AVAILABLE 
06-22 07:43:33.563   905  6146 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
06-22 07:43:33.563   905  1076 E WifiStateMachine: handleMessage: E msg.what=147461
06-22 07:43:33.563   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.563   905  1076 E WifiStateMachine:  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:43:33.563   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.563   905  1076 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:43:33.563   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.563   905  1076 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:43:33.563   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.563   905  1076 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
06-22 07:43:33.563   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
06-22 07:43:33.563   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
06-22 07:43:33.563  6093  6093 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
06-22 07:43:33.563   905  1083 D WirelessDisplayService: getDiscoveryDongleList
06-22 07:43:33.563   905  1076 I WifiNative-HAL: startHal
06-22 07:43:33.563   905  1076 E wifi    : getStaticLongField sWifiHalHandle 0xa08bf8ac
06-22 07:43:33.563   905  1076 I WifiNative-HAL: Could not start hal
06-22 07:43:33.563   905  1076 E WifiStateMachine: [1,466,574,213,581 ms] noteScanEnd no scan source
06-22 07:43:33.563   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,06-22 07:43:33.563  6093  6093 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
06-22 07:43:33.573   905  1076 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1e776ac3 sup_state=SCANNING debouncing=false
06-22 07:43:33.573   905  1076 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-51 cap [WPA2-PSK-CCMP][ESS] is not scored
06-22 07:43:33.573   905  1076 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
,06-22 07:43:33.573   905  1076 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
06-22 07:43:33.573   905  1076 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
06-22 07:43:33.573   905  1076 E WifiConfigStore: linkConfiguration link due to same gw "NG7005g" and "NG700" GW c0:ff:d4:d3:aa:48
06-22 07:43:33.573   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,06-22 07:43:33.583   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG7005g"] key=psk
06-22 07:43:33.583   905  1076 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
06-22 07:43:33.593   905  1076 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
06-22 07:43:33.593   905  1076 E WifiConfigStore: linkConfiguration: will link "NG7005g"WPA_PSK and "NG700"WPA_PSK
,06-22 07:43:33.593   905  1076 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-51 freq=2447
,06-22 07:43:33.593   905  1076 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-52 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
,06-22 07:43:33.653   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.593   905  1076 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-65 cap [WPA2-EAP-TKIP][ESS] is not scored
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.653   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.593   905  1076 E WifiAutoJoinController :  84:b2:61:1a:ce:70 rssi=-77 cap [WPA2-EAP-CCMP][ESS] is not scored
06-22 07:43:33.653  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.593   905  1076 E WifiAutoJoinController : Conrad_AP 00:1a:ef:42:f2:b0 rssi=-79 cap [WPA-PSK-CCMP][WPS][ESS] is not scored
06-22 07:43:33.653  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.593   905  1076 E WifiAutoJoinController :  84:b2:61:0f:9c:30 rssi=-82 cap [WPA2-EAP-CCMP][ESS] is not scored
06-22 07:43:33.593   905  1076 E WifiAutoJoinController :  00:16:a6:1e:e0:a4 rssi=-85 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : cvbtemp f4:f2:6d:85:e5:9e rssi=-89 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : RA-WINGS 84:b2:61:1a:ce:73 rssi=-77 cap [ESS] is not scored
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : RA-WINGS 84:b2:61:0f:9c:33 rssi=-82 cap [ESS] is not scored
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : RA-WINGS e4:aa:5d:fc:5b:f3 rssi=-88 cap [ESS] is not scored
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 12 now 1466574213615
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : newSupplicantResults size=12 known=1 true
06-22 07:43:33.603   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
06-22 07:43:33.603  6093  6093 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptAutoJoin() status=wpa_state=SCANNING
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : p2p_device_address=02:ee:bd:dd:33:d2
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 ---> suppNetId=-1
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-51,-127) num=(1,0)
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptAutoJoin trying id=2 "NG700"WPA_PSK status=0
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptAutoJoin networkSwitching candidate "NG700"WPA_PSK linked=false : delta=1000 
06-22 07:43:33.603   905  1076 E WifiStateMachine: WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
06-22 07:43:33.603   905  1076 E W,ifiAutoJoinController : AutoJoin auto connect with netId 2 to "NG700"WPA_PSK
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-51 freq=2447
06-22 07:43:33.603   905  1076 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
06-22 07:43:33.603   905  1076 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.603   905  1076 E WifiAutoJoinController : Done attemptAutoJoin status=3
06-22 07:43:33.603   905  1076 E WifiConfigStore:  writeKnownNetworkHistory() num networks:4 needWrite=true
06-22 07:43:33.603   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.603   905  1076 E WifiStateMachine: handleMessage: E msg.what=131215
06-22 07:43:33.603   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.603   905  1076 E WifiStateMachine:  DisconnectedState !CMD_AUTO_CONNECT 2 3 "NG700"WPA_PSK [1 ,-51 ;0 ,-127] any roam=0 rt=100428
06-22 07:43:33.603   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.613   905  1076 E WifiStateMachine:  ConnectModeState !CMD_AUTO_CONNECT 2 3 "NG700"WPA_PSK [1 ,-51 ;0 ,-127] any roam=0 rt=100428
06-22 07:43:33.613   905  1076 E WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=2 roam=3
06-22 07:43:33.613   905  1076 E WifiStateMachine: autoRoamSetBSSID any key="NG700"WPA_PSK
06-22 07:43:33.613   905  1076 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:43:33.613   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.613  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='bssid'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=3): [REMOVED]
06-22 07:43:33.613   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.613  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.613  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.613   905  1076 E WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=2
06-22 07:43:33.613   905  1076 E WifiConfigStore: WifiConfigStore saveNetwork, size=4 SSID="NG700" Uid=1000/0
06-22 07:43:33.613   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.613  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='ssid'
06-22 07:43:33.613  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=10): [REMOVED]
06-22 07:43:33.623   905  6173 E WifiConfigStore: saving network history: "Ozz"WPA_PSK gw: null autojoin-status: 0 ephemeral=false choices:0 link:0 status:2 nid:1
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write config "Ozz"WPA_PSK
06-22 07:43:33.623   905  6173 E WifiConfigStore: saving network history: "huawei mate 7"NONE gw: null autojoin-status: 0 ephemeral=false choices:0 link:0 status:2 nid:0
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write config "huawei mate 7"NONE
06-22 07:43:33.623   905  6173 E WifiConfigStore: saving network history: "NG7005g"WPA_PSK gw: c0:ff:d4:d3:aa:48 autojoin-status: 0 ephemeral=false choices:0 link:1 status:2 nid:3
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write config "NG7005g"WPA_PSK
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write linked 1
06-22 07:43:33.623   905  6173 E WifiConfigStore: saving network history: "NG700"WPA_PSK, gw: c0:ff:d4:d3:aa:48 autojoin-status: 0 ephemeral=false choices:0 link:1 status:2 nid:2
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write config "NG700"WPA_PSK
06-22 07:43:33.623   905  6173 E WifiConfigStore: writeKnownNetworkHistory write linked 1
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='key_mgmt'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=7): [REMOVED]
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='proto'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=12): [REMOVED]
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='pairwise'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=14): [REMOVED]
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='group'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=27): [REMOVED]
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='priority'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=3): [REMOVED]
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='::ORDERlimited'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=1): [REMOVED]
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: Failed to set network variable '::ORDERlimited'
06-22 07:43:33.633   905  1076 E WifiConfigStore: will read network variables netId=2
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ssid"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ssid'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ssid'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 bssid"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 bssid'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='bssid'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 priority"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 priority'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='priority'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 scan_ssid"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 scan_ssid'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='scan_ssid'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_tx_keyidx"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_tx_keyidx'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_tx_keyidx'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key0"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key0'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key0'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key1"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key1'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key1'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key2"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key2'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key2'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key3"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key3'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key3'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 psk"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 psk'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='psk'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: Do not allow key_data field to be exposed
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 proto"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 proto'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='proto'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_mgmt"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_mgmt'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_mgmt'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 auth_alg"
06-22 07:43:33.633  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 auth_alg'
06-22 07:43:33.633  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='auth_alg'
06-22 07:43:33.633   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 pairwise"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 pairwise'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='pairwise'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 group"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 group'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='group'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk_hex"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk_hex'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk_hex'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_as_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_as_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_as_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_user_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_user_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_user_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 eap"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 eap'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='eap'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 phase2"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 phase2'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='phase2'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 identity"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 identity'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='identity'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 anonymous_identity"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 anonymous_identity'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='anonymous_identity'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 password"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 password'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='password'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 client_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 client_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='client_cert'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ca_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ca_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ca_cert'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 subject_match"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 subject_match'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='subject_match'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine_id"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine_id'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine_id'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_id"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_id'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_id'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 private_key"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 private_key'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='private_key'
06-22 07:43:33.643   905  1076 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
06-22 07:43:33.643   905  1076 E WifiConfigStore:  writeKnownNetworkHistory() num networks:4 needWrite=false
06-22 07:43:33.643   905  1076 E WifiConfigStore: WifiConfigStore: saveNetwork got config back netId=2 uid=1000
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.643   905  1076 E WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=2
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 2"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'ENABLE_NETWORK 2'
06-22 07:43:33.643  6093  6093 I wpa_supplicant: ENABLE_NETWORK (2)
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: ENABLE_NETWORK id=2
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='priority'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=3): [REMOVED]
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='::ORDERlimited'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=1): [REMOVED]
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: Failed to set network variable '::ORDERlimited'
06-22 07:43:33.643   905  1076 E WifiConfigStore: will read network variables netId=2
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ssid"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ssid'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ssid'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 bssid"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 bssid'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='bssid'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 priority"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 priority'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='priority'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 scan_ssid"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 scan_ssid'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='scan_ssid'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_tx_keyidx"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_tx_keyidx'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_tx_keyidx'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key0"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key0'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key0'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key1"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key1'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key1'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key2"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key2'
06-22 07:43:33.693   905  1636 D PMS     : acquireWL(3209e886): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6018 1002 null
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key2'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wep_key3"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wep_key3'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wep_key3'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 psk"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 psk'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='psk'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: Do not allow key_data field to be exposed
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 proto"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 proto'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='proto'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_mgmt"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_mgmt'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_mgmt'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 auth_alg"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 auth_alg'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='auth_alg'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 pairwise"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 pairwise'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='pairwise'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 group"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 group'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='group'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK key null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_psk_hex"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_psk_hex'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_psk_hex'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_PSK_HEX key null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT index null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_as_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_as_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_as_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT as cert null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 wapi_user_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 wapi_user_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='wapi_user_cert'
06-22 07:43:33.643   905  1076 D WifiConfigStore: ***WAPI : readNetworkVariables WAPI_CERT user cert null
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 eap"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 eap'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='eap'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 phase2"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 phase2'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='phase2'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 identity"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 identity'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='identity'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 anonymous_identity"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 anonymous_identity'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='anonymous_identity'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 password"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 password'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='password'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 client_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 client_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='client_cert'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 ca_cert"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 ca_cert'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='ca_cert'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 subject_match"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 subject_match'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='subject_match'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 engine_id"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 engine_id'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='engine_id'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 key_id"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 key_id'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='key_id'
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 2 private_key"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'GET_NETWORK 2 private_key'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: GET_NETWORK id=2 name='private_key'
06-22 07:43:33.643   905  1076 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> null path: /data/misc/wifi/ipconfig.txt
06-22 07:43:33.643   905  1076 E WifiConfigStore:  writeKnownNetworkHistory() num networks:4 needWrite=false
06-22 07:43:33.643   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.643  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.643  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.643  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SELECT_NETWORK 2"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SELECT_NETWORK 2'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: CTRL_IFACE: SELECT_NETWORK id=2
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Selecting BSS from priority group 255
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: 0: f0:f2:6d:22:99:3e ssid='NG700_GUEST' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-51
06-22 07:43:33.653  6093  6093 D wpa_supplicant: 0: f0:f2:6d:22:99:3e ssid='NG700_GUEST' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0:    skip - SSID mismatch
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: 1: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-51 wps
06-22 07:43:33.653  6093  6093 D wpa_supplicant: 1: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0:    selected based on RSN IE
06-22 07:43:33.653  6093  6093 W wpa_supplicant: [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
06-22 07:43:33.653  6093  6093 D wpa_supplicant:    selected WPA/WAPI AP f4:f2:6d:22:99:3e ssid='NG700'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0:    selected BSS f4:f2:6d:22:99:3e ssid='NG700'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Considering connect request: reassociate: 1  selected: f4:f2:6d:22:99:3e  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7bb65c0  current_ssid=0xb7bb65c0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Request association with f4:f2:6d:22:99:3e
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wpa_supplicant_set_is_wep_security: 0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 08
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=28): 33 1a ef 11 1b ff ff ff 00 00 00 00 00 00 00 00 00 00 00 00 00 00 04 06 e6 e7 0d 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 08 0f 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 34 16 08 0f 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 87 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: TDLS: TDLS is allowed in the target BSS
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Add radio work 'connect'@0xb7bb8158
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Starting radio work 'connect'@0xb7bb8158 after 0.000034 second wait
06-22 07:43:33.653  6093  6093 I wpa_supplicant: check if in concurrent case
06-22 07:43:33.653  6093  6093 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
06-22 07:43:33.653   905  6146 D WifiMonitor: Event [IFNAME=wlan0 Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)]
06-22 07:43:33.653   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Cancelling scan request
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wpas_start_assoc_cb, 1887
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wpas_start_assoc_cb, 1890
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wpas_start_assoc_cb, 1905
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: clearing own WPA/RSN IE
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Automatic auth_alg selection: 0x1
06-22 07:43:33.653  6093  6093 D wpa_supplicant: RSN: PMKSA cache search - network_ctx=0xb7bb65c0 try_opportunistic=0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: RSN: Search for BSSID f4:f2:6d:22:99:3e
06-22 07:43:33.653  6093  6093 D wpa_supplicant: RSN: No PMKSA cache entry found
,06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: RSN: using IEEE 802.11i/D9.0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: Selected mgmt group cipher 32
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: clearing AP WPA IE
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: using GTK CCMP
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: using PTK CCMP
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: using KEY_MGMT WPA-PSK
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: WPA: not using MGMT group cipher
06-22 07:43:33.653  6093  6093 D wpa_supplicant: WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Set wlan0 operstate 0->0 (DORMANT)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: Limit connection to BSSID f4:f2:6d:22:99:3e freq=2447 MHz based on scan results (bssid_set=0)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Set mode ifindex 22 iftype 2 (STATION)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Unsubscribe mgmt frames handle 0x3f33d8e9 (mode change)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Subscribe to mgmt frames with non-AP handle 0xb7bb5060
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0104
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040a
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040b
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040c
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040d
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090a
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090b
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090c
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=090d
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0409506f9a09
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=7f506f9a09
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0801
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=040e
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=06
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a07
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a11
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0xb7bb5060 match=0a1a
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Connect (ifindex=22)
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * bssid=f4:f2:6d:22:99:3e
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * bssid_hint=f4:f2:6d:22:99:3e
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * freq=2447
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * freq_hint=2447
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * SSID - hexdump(len=5): 4e 47 37 30 30
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * WPA Versions 0x2
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * pairwise=0xfac04
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * group=0xfac04
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * akm=0xfac02
06-22 07:43:33.653  6093  6093 D wpa_supplicant:   * Auth Type 0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0xb7bb65ea
06-22 07:43:33.653  6093  6093 D wpa_supplicant: nl80211: Connect request send successfully
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Setting authentication timeout: 10 sec 0 usec
06-22 07:43:33.653  6093  6093 D wpa_supplicant: EAPOL: External notification - EAP success=0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: EAPOL: External notification - EAP fail=0
06-22 07:43:33.653  6093  6093 D wpa_supplicant: EAPOL: External notification - portControl=Auto
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'RECONNECT'
06-22 07:43:33.653   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=2 state=5 BSSID=00:00:00:00:00:00 SSID=NG700]
06-22 07:43:33.653   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=2 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.653   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=2 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.653   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=2 state=5 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.653   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSIDNG700
06-22 07:43:33.653   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
06-22 07:43:33.653   905  1076 E WifiConfigStore: setLastSelectedConfiguration -1
06-22 07:43:33.653   905  1076 E WifiStateMachine: transitionTo: destState=DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:33.653   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
06-22 07:43:33.653   905  1076 E WifiStateMachine: invokeExitMethods: DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine: setScanAlarm false period 0 initial delay 0
06-22 07:43:33.653   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:33.653   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=4
06-22 07:43:33.653   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine: invokeEnterMethods: DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine: DisconnectedState call setCountryCode()
06-22 07:43:33.653   905  1076 E WifiStateMachine:  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 1"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'ENABLE_NETWORK 1'
06-22 07:43:33.653  6093  6093 I wpa_supplicant: ENABLE_NETWORK (1)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: CTRL_IFACE: ENABLE_NETWORK id=1
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 0"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'ENABLE_NETWORK 0'
06-22 07:43:33.653  6093  6093 I wpa_supplicant: ENABLE_NETWORK (0)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: CTRL_IFACE: ENABLE_NETWORK id=0
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 ENABLE_NETWORK 3"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'ENABLE_NETWORK 3'
06-22 07:43:33.653  6093  6093 I wpa_supplicant: ENABLE_NETWORK (3)
06-22 07:43:33.653  6093  6093 D wpa_supplicant: CTRL_IFACE: ENABLE_NETWORK id=3
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.653  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.653   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
06-22 07:43:33.653  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
06-22 07:43:33.653  6093  6093 D wpa_supplicant: Ongoing scan action - reject new request
06-22 07:43:33.653   905  1076 E WifiStateMachine: setScanAlarm true period 10000 initial delay 3000
06-22 07:43:33.653   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: E msg.what=131213
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine:  DisconnectedState !CMD_TARGET_BSSID 20 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=100474
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.653   905  1076 E WifiStateMachine:  ConnectModeState !CMD_TARGET_BSSID 20 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=100474
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.653   905  1076 E WifiStateMachine:  DriverStartedState !CMD_TARGET_BSSID 20 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=100475
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.653   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_TARGET_BSSID 20 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=100475
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.653   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=100475  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 2 state: ASSOCIATING
06-22 07:43:33.653   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
06-22 07:43:33.653   905  1076 E WifiStateMachine: setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
06-22 07:43:33.653   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
06-22 07:43:33.653   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 3
06-22 07:43:33.653   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.653  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.653   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=100478  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 2 state: ASSOCIATING
06-22 07:43:33.653   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.663  5296  6179 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.663  6093  6093 D wpa_supplicant: EAPOL: disable timer tick
06-22 07:43:33.663  5296  6179 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 2, Metered hint: false
06-22 07:43:33.683  6018  6083 I bt-btu  : btu_task received preload complete event
06-22 07:43:33.683  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
06-22 07:43:33.683  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
06-22 07:43:33.693  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
06-22 07:43:33.693  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x1487
06-22 07:43:33.693  6018  6083 D bt-btm  : btm_acl_device_down
06-22 07:43:33.693  6018  6083 D bt-btm  : btm_acl_reset_paging
06-22 07:43:33.693  6018  6083 D bt-btm  : btm_acl_set_discing
06-22 07:43:33.703  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
06-22 07:43:33.723  6018  6083 I bt-btm  : btm_reset_complete
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
06-22 07:43:33.723  6018  6083 D bt-btm  : Start reading local supported commands
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_local_supported_cmds_complete status (0x00)
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM reads next extended features page (1)
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM reads next extended features page (2)
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM reached last extended features page (2)
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
06-22 07:43:33.723  6018  6083 I bt-btm  : btm_vendor_capability_vsc_cmpl_cback: status=255
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_wl_size 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_white_list_size_complete 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_get_ble_buffer_size 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_buf_size_complete 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_local_supported_states 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_local_supported_states_complete 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_local_supported_features 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_read_ble_local_supported_features_complete 
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_reset_ctrlr_complete: max_page_number: 2
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_decode_ext_features_page page: 0
06-22 07:43:33.723  6018  6083 D bt-btm  : Local supported ACL packet types: 0xcc18
06-22 07:43:33.723  6018  6083 D bt-btm  : Local supported SCO packet types: 0x038f
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
06-22 07:43:33.723  6018  6083 I bt-btm  :                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_sec_dev_reset sec mode: 4
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_SetInquiryMode
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_SetPageScanType
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_SetInquiryScanType
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_decode_ext_features_page page: 1
06-22 07:43:33.723  6018  6083 D bt-btm  : btm_decode_ext_features_page page: 2
06-22 07:43:33.723  6018  6083 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_BleLoadLocalKeys
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_BleLoadLocalKeys
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_Sec: application registered
06-22 07:43:33.723  6018  6083 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaff6cf79 
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_Sec: SMP_Register( btm_proc_smp_cback )
06-22 07:43:33.723  6018  6083 I bt-smp  : SMP_Register state=0
06-22 07:43:33.723  6018  6083 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaff6cf79 
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM_Sec: application registered
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_SetDefaultLinkSuperTout
06-22 07:43:33.723  6018  6083 I bt-btm  : BTM: BTM_WritePageTimeout: Timeout: 8192.
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_SetDefaultLinkPolicy setting:0x000f
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
06-22 07:43:33.723  6018  6083 D bt-btm  : Set DefaultLinkPolicy:0x0007
06-22 07:43:33.723  6018  6083 D bt-btm  : BTM_RegBusyLevelNotif
06-22 07:43:33.723  6018  6083 I bt-att  : GATT_Register
06-22 07:43:33.723  6018  6083 D bt-att  : UUID=[0x87878787878787878787878787878787]
06-22 07:43:33.723  6018  6083 I bt-att  : allocated gatt_if=3
06-22 07:43:33.723  6018  6083 I bt-att  : GATT_StartIf gatt_if=3
06-22 07:43:33.723  6018  6083 D bt-att  : gatt_find_the_connected_bda start_idx=0
06-22 07:43:33.723  6018  6083 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
06-22 07:43:33.733  6018  6083 D bt-btm  : bta_dm_set_dev_name: name: HTC One_M8 
06-22 07:43:33.733  6018  6050 E bt-btif : Calling BTA_HhEnable
06-22 07:43:33.733  6018  6050 I bt-btif : BTA_MceEnable
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:3
06-22 07:43:33.733  6018  6083 D bt-btm  : BTM_AllocateSCN
06-22 07:43:33.733  6018  6083 I bt-btm  : btif_storage_get_adapter_property service_mas
06-22 07:43:33.733  6018  6050 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:4
06-22 07:43:33.733  6018  6050 I bt-btif : HAL AllocateSCN
06-22 07:43:33.733  6018  6083 D bt-btm  : BTM_AllocateSCN
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
06-22 07:43:33.733  6018  6050 D BluetoothAdapterProperties: Address is:50:2E:6C:AC:21:50
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:5
06-22 07:43:33.733  6018  6083 I bt-avp  : AVRC_AddRecord uuid: 110c
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:6
06-22 07:43:33.733  6018  6083 I bt-a2d  : A2D_AddRecord uuid: 110a
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 D bt-avp  : AVRC_Open role: 1, control:3 status:0, handle:0
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:7
06-22 07:43:33.733  6018  6083 I bt-avp  : AVRC_AddRecord uuid: 110e
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x86, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0xb6, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
06-22 07:43:33.733  ,6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
06-22 07:43:33.733  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
06-22 07:43:33.733  6018  6083 I bt-att  : GATT_Register
06-22 07:43:33.733  6018  6083 D bt-att  : UUID=[0x0000454c205245564f20484820415442]
06-22 07:43:33.733  6018  6083 I bt-att  : allocated gatt_if=4
06-22 07:43:33.733  6018  6083 I bt-att  : GATT_StartIf gatt_if=4
06-22 07:43:33.733  6018  6083 D bt-att  : gatt_find_the_connected_bda start_idx=0
06-22 07:43:33.733  6018  6083 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
06-22 07:43:33.733  6018  6050 D BluetoothAdapterProperties: Scan Mode:21
06-22 07:43:33.733  6018  6050 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:43:33.733  6018  6050 I bt-btif : BTA_JvEnable
06-22 07:43:33.733  6018  6050 I bt-btif : BTA_JvRegisterL2cCback
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_ReadConnectability
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_ReadDiscoverability
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetDiscoverability
06-22 07:43:33.733  6018  6083 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x2
06-22 07:43:33.733  6018  6083 D bt-btm  : disc_mode 0002
06-22 07:43:33.733  6018  6083 D bt-btm  : btm_ble_update_adv_flag new=0x18
06-22 07:43:33.733  6018  6083 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x3 
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetConnectability
06-22 07:43:33.733  6018  6083 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
06-22 07:43:33.733  6018  6083 D bt-btm  : disc_mode 0002
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
06-22 07:43:33.733  6018  6083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetDiscoverability
06-22 07:43:33.733  6018  6083 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x0
06-22 07:43:33.733  6018  6083 D bt-btm  : disc_mode 0000
06-22 07:43:33.733  6018  6083 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetConnectability
06-22 07:43:33.733  6018  6083 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x0
06-22 07:43:33.733  6018  6083 D bt-btm  : disc_mode 0000
06-22 07:43:33.733  6018  6083 D bt-btm  : btm_ble_update_adv_flag new=0x1c
06-22 07:43:33.733  6018  6083 D bt-btm  : btm_ble_update_adv_flag old=0x18
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
06-22 07:43:33.733  6018  6083 I bt-btif : bta_pan_co_init
06-22 07:43:33.733  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:8
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
06-22 07:43:33.743   905  1584 D PMS     : acquireWL(35005f99): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5296 1000 null
,06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
06-22 07:43:33.743  5296  5296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
06-22 07:43:33.733  6018  6083 I bt-btm  :                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.733  5914  5914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:33.733  6018  6186 E bt_mct  : hci lib postload completed
,06-22 07:43:33.733  5914  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-22 07:43:33.733  6018  6050 D bt-sdp  : SDP_CreateRecord ok, num_records:9
06-22 07:43:33.743   905  1636 D PMS     : releaseWL(35005f99): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,06-22 07:43:33.733  6018  6050 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.753   905  1708 D PMS     : acquireWL(3b57563f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5296 1000 null
06-22 07:43:33.733  6018  6050 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
,06-22 07:43:33.733  6018  6047 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,06-22 07:43:33.733  6018  6047 D BluetoothAdapterProperties: ScanMode =  21
06-22 07:43:33.733  6018  6047 D BluetoothAdapterProperties: State =  11
,06-22 07:43:33.733  6018  6050 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
,06-22 07:43:33.733  6018  6050 D BluetoothAdapterProperties: Discoverable Timeout:120
06-22 07:43:33.733  6018  6047 D BluetoothAdapterProperties: Setting state to 12
06-22 07:43:33.733  6018  6047 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-22 07:43:33.733   905   921 D BluetoothManagerService: +onBluetoothStateChange prev=11 new=12
06-22 07:43:33.733   905  1005 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,06-22 07:43:33.733   905  1005 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-22 07:43:33.733   905  1005 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 8 receivers.
06-22 07:43:33.733  6018  6047 I BluetoothAdapterState: Entering On State,
,06-22 07:43:33.733  3600  3617 D BluetoothA2dp: onBluetoothStateChange: up=true
06-22 07:43:33.733   905  1637 D BluetoothHeadset: BluetoothHeadset()
06-22 07:43:33.733   905  1637 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.733   905   905 D BluetoothHeadset: Proxy object connected
,06-22 07:43:33.743  6018  6047 I BluetoothAdapterState: notBluetoothOn(),
06-22 07:43:33.743  1123  1796 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743  1457  2166 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743   905  1005 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743  3600  4812 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743  1457  1474 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743   905  1005 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-22 07:43:33.743  1457  2092 D BluetoothHeadset: onBluetoothStateChange: up=true
06-22 07:43:33.743   905  1005 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-22 07:43:33.743   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.743   905  1005 D BluetoothManagerService: Registered receivers: 9
06-22 07:43:33.743  3600  3600 D NGFService: Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:33.743  3600  3600 D NGFService: Bluetooth Adapter: ON
06-22 07:43:33.743  1123  1302 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
06-22 07:43:33.743   905   905 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-22 07:43:33.743  6018  6018 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:33.743  6018  6018 V BluetoothPbapReceiver: ***********state = 12
06-22 07:43:33.743   905  1005 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
06-22 07:43:33.773  5296  5296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1862 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,06-22 07:43:33.743   905  1005 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,06-22 07:43:33.753  6070  6070 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
06-22 07:43:33.753  6070  6070 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
06-22 07:43:33.753   905   920 W System.err: java.lang.Throwable: stack dump
06-22 07:43:33.753   905   920 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:33.753   905   920 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-22 07:43:33.753   905   920 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-22 07:43:33.753   905   920 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,06-22 07:43:33.753   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-22 07:43:33.753   905  1005 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@66e5c55:true
,06-22 07:43:33.753  5296  5296 D BluetoothAdapter: 765538006: getState(). Returning 12
06-22 07:43:33.753  6018  6018 V BluetoothPbapService: Pbap Service onCreate
06-22 07:43:33.753  6018  6018 V BluetoothPbapService: Starting PBAP service
06-22 07:43:33.753  6018  6018 D BluetoothAdapter: 119314783: getState(). Returning 12
06-22 07:43:33.753  6018  6018 V BluetoothPbapService: Handler(): got msg=1
06-22 07:43:33.753  6018  6018 V BluetoothPbapService: Pbap Service startRfcommSocketListener
06-22 07:43:33.763  5296  5296 D BluetoothInputDevice: BluetoothInputDevice()
06-22 07:43:33.763   905  1088 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.763   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,06-22 07:43:33.763   905  1005 D BluetoothManagerService: Registered receivers: 10
06-22 07:43:33.763  6018  6193 V BluetoothPbapService: Pbap Service initSocket
06-22 07:43:33.763   905  1708 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:43:33.763  6018  6193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:43:33.763  5296  5296 D BluetoothPan: BluetoothPan()
06-22 07:43:33.763  6018  6083 I bt-btm  : BTM_SetDiscoverability
06-22 07:43:33.763  6018  6083 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x0
06-22 07:43:33.763  6018  6083 D bt-btm  : disc_mode 0000
06-22 07:43:33.763  6018  6083 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 
,06-22 07:43:33.763  6018  6083 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
06-22 07:43:33.763   905  1637 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.763  6018  6083 I bt-btm  : BTM_SetConnectability
06-22 07:43:33.763  6018  6083 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
06-22 07:43:33.763  6018  6083 D bt-btm  : disc_mode 0000
06-22 07:43:33.763  6018  6083 D bt-btm  : btm_ble_update_adv_flag new=0x18
06-22 07:43:33.763  6018  6083 D bt-btm  : btm_ble_update_adv_flag old=0x1c
06-22 07:43:33.763  6018  6083 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
06-22 07:43:33.763  6018  6050 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
,06-22 07:43:33.763  6018  6193 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:33.763  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:10
06-22 07:43:33.763  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.763  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:33.763  6018  6083 I bt-btm  : BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
06-22 07:43:33.763  6018  6083 I bt-btm  :                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,06-22 07:43:33.763  6018  6050 D BluetoothAdapterProperties: Scan Mode:21
06-22 07:43:33.763  6018  6193 V BluetoothPbapService: Succeed to create listening socket 
06-22 07:43:33.763   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.763   905  1005 D BluetoothManagerService: Registered receivers: 11
06-22 07:43:33.763  6018  6193 V BluetoothPbapService: Accepting socket connection...
06-22 07:43:33.763  5914  5914 D BluetoothAdapter: 800157567: getState(). Returning 12
06-22 07:43:33.763  5914  5914 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-22 07:43:33.773  5296  5296 D BluetoothMap: Create BluetoothMap proxy object
,06-22 07:43:33.773   905   921 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.773  5296  5296 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
06-22 07:43:33.773  5914  5914 D BluetoothAdapter: 800157567: getState(). Returning 12
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:33.773  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Registered receivers: 12
,06-22 07:43:33.773   905   920 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.773  5914  5914 D BluetoothAdapter: 800157567: getState(). Returning 12
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Registered receivers: 13
06-22 07:43:33.773  5296  5296 D BluetoothSap: BluetoothSap() call bindService
06-22 07:43:33.773  5914  5914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-22 07:43:33.773  5296  5296 D BluetoothPbap: BluetoothPbap()
06-22 07:43:33.773   905  1585 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Registered receivers: 14
,06-22 07:43:33.773   905  2090 D BluetoothManagerService: registerStateChangeCallback+
06-22 07:43:33.773   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.783   905  1005 D BluetoothManagerService: Registered receivers: 15
06-22 07:43:33.783  5296  5296 D BluetoothHeadset: BluetoothHeadset()
06-22 07:43:33.783   905  1281 D BluetoothManagerService: registerStateChangeCallback+
,06-22 07:43:33.783   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
06-22 07:43:33.783   905  1005 D BluetoothManagerService: Registered receivers: 16
,06-22 07:43:33.783  5296  5296 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete,
,06-22 07:43:33.783  5296  5296 D DockEventReceiver: finishStartingService: stopping service,
,06-22 07:43:33.783  5296  5296 D BluetoothInputDevice: Proxy object connected
06-22 07:43:33.783  5296  5296 D HidProfile: Bluetooth service connected
06-22 07:43:33.783  5296  5296 D BluetoothAdapter: 765538006: getState(). Returning 12
06-22 07:43:33.783  5296  5296 D BluetoothPan: BluetoothPAN Proxy object connected
06-22 07:43:33.783  5296  5296 D PanProfile: Bluetooth service connected
06-22 07:43:33.783  5296  5296 D BluetoothA2dp: Proxy object connected
06-22 07:43:33.783  5296  5296 D A2dpProfile: Bluetooth service connected
06-22 07:43:33.793  5296  5296 D BluetoothAdapter: 765538006: getState(). Returning 12
,06-22 07:43:33.793  5296  5296 D BluetoothHeadset: Proxy object connected
,06-22 07:43:33.793  1123  1123 D BluetoothAdapter: 404492909: getState(). Returning 12,
06-22 07:43:33.793  5296  5296 D HeadsetProfile: Bluetooth service connected
06-22 07:43:33.793   905   921 D PMS     : releaseWL(3b57563f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
06-22 07:43:33.793  1123  1123 D BluetoothAdapter: 404492909: getState(). Returning 12
06-22 07:43:33.793  5296  5296 D BluetoothAdapter: 765538006: getState(). Returning 12
06-22 07:43:33.793  1123  1123 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
06-22 07:43:33.793  1123  1123 D PhoneStatusBar: addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ac level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,06-22 07:43:33.803  6018  6018 V BluetoothPbapService: Pbap Service onBind
06-22 07:43:33.803  5296  5296 D BluetoothPbap: Proxy object connected
06-22 07:43:33.803   905  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:43:33.803  6018  6202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:43:33.813  6018  6202 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:33.813  5296  5296 D PbapServerProfile: Bluetooth service connected
06-22 07:43:33.813  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:11
06-22 07:43:33.813  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.813  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:33.813  6018  6083 I bt-btm  : BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
06-22 07:43:33.813  6018  6083 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
06-22 07:43:33.813  6018  6202 I BtOppRfcommListener: Accept thread started.
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8c02 len=263
06-22 07:43:33.813  6093  6093 I wpa_supplicant: WEXT: Custom wireless event: 'BEACONIEs='
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8c02 len=129
06-22 07:43:33.813  6093  6093 I wpa_supplicant: WEXT: Custom wireless event: 'BEACONIEs='
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8b15 len=20
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Connect event
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Associated on 2447 MHz
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Operating frequency for the associated BSS from scan results: 2447 MHz
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Event ASSOC (0) received
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Association info event
06-22 07:43:33.813  6093  6093 D wpa_supplicant: req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant: resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: freq=2447 MHz
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant: FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
06-22 07:43:33.813  6093  6093 D wpa_supplicant: nl80211: Set wlan0 operstate 0->0 (DORMANT)
06-22 07:43:33.813  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Associated to a new BSS: BSSID=f4:f2:6d:22:99:3e
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: WPA: clearing AP WPA IE
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f, ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.813  6093  6093 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: WPA: Association event - clear replay counter
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: WPA: Clear old PTK
06-22 07:43:33.813  6093  6093 D wpa_supplicant: TDLS: Remove peers on association
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: External notification - portEnabled=0
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: External notification - portValid=0
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: External notification - EAP success=0
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: External notification - portEnabled=1
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: SUPP_PAE entering state CONNECTING
06-22 07:43:33.813  6093  6093 D wpa_supplicant: EAPOL: SUPP_BE entering state IDLE
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Setting authentication timeout: 10 sec 0 usec
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Cancelling scan request
06-22 07:43:33.813  6093  6093 I wpa_supplicant: htc_wext_set_keepalive +
06-22 07:43:33.813  6093  6093 I wpa_supplicant: htc_wext_set_keepalive: enable=1, type=1, interval=30
06-22 07:43:33.813  6093  6093 D wpa_supplicant: getPrivFuncNum +	
06-22 07:43:33.813  6093  6093 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
06-22 07:43:33.813  6093  6093 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
06-22 07:43:33.813  6093  6093 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8c07 len=30
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8c08 len=30
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: Wireless event: cmd=0x8b15 len=20
06-22 07:43:33.813  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 wext ifi_flags=0x11003 ([UP][LOWER_UP])
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: Setting authentication timeout: 10 sec 0 usec
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: IEEE 802.1X RX: version=2 type=3 length=95
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0:   EAPOL-Key type=2
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0:   key_length=16 key_data_length=0
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   key_nonce - hexdump(len=32): c8 a3 e0 a8 cb ea 08 c2 36 61 85 ae 3e e8 fa 8f 6a 59 c0 73 54 98 7a 20 f6 05 4e 94 13 b2 fe 5c
06-22 07:43:33.823   905   905 D UsbDeviceManager: [USBNET] bCheckSuppFunc: cdc_network
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
06-22 07:43:33.823   905  1073 D PMS     : acquireWL(1cd9e004): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant:   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
06-22 07:43:33.813  6093  6093 D wpa_supplicant: ,RSN: msg 1/4 key data - hexdump(len=0):
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false
06-22 07:43:33.813   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:33.813   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false
06-22 07:43:33.813   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:33.813   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: Renewed SNonce - hexdump(len=32): 28 b0 df 08 05 85 a3 a9 23 b1 7d ad 20 8b c9 65 58 04 53 ef 51 95 a2 c3 03 4c 11 48 52 43 22 cb
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: Nonce1 - hexdump(len=32): 28 b0 df 08 05 85 a3 a9 23 b1 7d ad 20 8b c9 65 58 04 53 ef 51 95 a2 c3 03 4c 11 48 52 43 22 cb
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: Nonce2 - hexdump(len=32): c8 a3 e0 a8 cb ea 08 c2 36 61 85 ae 3e e8 fa 8f 6a 59 c0 73 54 98 7a 20 f6 05 4e 94 13 b2 fe 5c
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: PMK - hexdump(len=32): [REMOVED]
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: PTK - hexdump(len=48): [REMOVED]
06-22 07:43:33.833  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.833  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
06-22 07:43:33.833   905  1073 D PMS     : releaseWL(1cd9e004): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-22 07:43:33.813  6093  6093 D wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
06-22 07:43:33.833   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: KCK - hexdump(len=16): [REMOVED]
06-22 07:43:33.833   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 07:43:33.813  6093  6093 D wpa_supplicant: WPA: Derived Key MIC - hexdump(len=16): a2 8f 82 92 6d 45 3f 24 70 8d 92 76 9b e9 bd cc
06-22 07:43:33.843  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, false
06-22 07:43:33.843  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.813   905  1003 D Tethering: interfaceStatusChanged wlan0, false
06-22 07:43:33.843  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.813   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.843  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, true
06-22 07:43:33.813   905  1003 D Tethering: interfaceStatusChanged wlan0, true
06-22 07:43:33.813   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.813  6018  6018 D BluetoothAdapter: 119314783: getState(). Returning 12
06-22 07:43:33.813  6018  6018 D BluetoothFtpService: ACTION_STATE_CHANGED: state: 12mHasStarted: true
06-22 07:43:33.813  6018  6018 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 12
06-22 07:43:33.813   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=2 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
06-22 07:43:33.813  6018  6018 D BluetoothMasReceiver:  call MAP start service
06-22 07:43:33.813   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=2 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, true
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=2 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=2 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
06-22 07:43:33.813   905  1005 V Tethering: TetherInterfaceSM: wlan0: enter InitialState
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSIDNG700
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:33.843   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:33.813   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
06-22 07:43:33.813   905  6146 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447]
06-22 07:43:33.813   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813   905  6146 D WifiMonitor: WifiMonitor: Got associated with event from string: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813   905  1005 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.813   905  6146 D WifiMonitor: handleAssociatedWithEvent. Data= Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.843  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.813   905  1003 D Tethering: interfaceStatusChanged wlan0, true
06-22 07:43:33.843  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.813   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:getFrequencyFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:getFreqFromEventString() 2447
06-22 07:43:33.813   905  6146 D HTCRequest: WifiMonitor:getMacFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2447
06-22 07:43:33.813   905  6146 D WifiMonitor: handleAssociatedWithEvent. Parsed MAC Address =f4:f2:6d:22:99:3e
06-22 07:43:33.813   905  6146 D WifiMonitor: handleAssociatedWithEvent. bLFR =false
06-22 07:43:33.813   905  1003 D Tethering: interfaceLinkStateChanged wlan0, true
06-22 07:43:33.813   905  6146 D WifiMonitor: handleAssociatedWithEvent. wifiSsid ='NG700' freq=2447
06-22 07:43:33.813   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=2 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=2 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=2 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=2 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSIDNG700
06-22 07:43:33.823   905  1003 D Tethering: interfaceStatusChanged wlan0, true
06-22 07:43:33.823   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.823   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
06-22 07:43:33.823   905  1003 D Tethering: interfaceLinkStateChanged wlan0, true
06-22 07:43:33.823   905  1003 D Tethering: interfaceStatusChanged wlan0, true
06-22 07:43:33.823   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.823   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.823   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.823   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=100640  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 2 state: ASSOCIATED
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: IEEE 802.1X RX: version=2 type=3 length=151
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0:   EAPOL-Key type=2
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0:   key_length=16 key_data_length=56
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   key_nonce - hexdump(len=32): c8 a3 e0 a8 cb ea 08 c2 36 61 85 ae 3e e8 fa 8f 6a 59 c0 73 54 98 7a 20 f6 05 4e 94 13 b2 fe 5c
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   key_rsc - hexdump(len=8): 77 f1 7f 00 00 00 00 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
06-22 07:43:33.853  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED disconnected
06-22 07:43:33.823  6093  6093 D wpa_supplicant:   key_mic - hexdump(len=16): 3f 1e 86 0a 58 37 a0 7c dc d4 77 00 e8 cb b2 e8
06-22 07:43:33.853  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: RSN: encrypted key data - hexdump(len=56): fc 56 ab bf 0b 01 d3 23 af d5 94 8f 6a c4 b0 bd 47 b2 0b 7e 8f 35 f8 fb 92 6f 59 d3 80 4c c9 58 ...
06-22 07:43:33.853   905  1076 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00 dd 16 00 0f ac 01 01 00 84 21 ...
06-22 07:43:33.853   905  1079 D ConnectivityService: Got NetworkAgent Messenger
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: KCK - hexdump(len=16): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: Derived Key MIC - hexdump(len=16): 38 81 db 8b e0 36 c5 fb cf 86 10 5b e4 9f 59 a9
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: WPA: Installing PTK to the driver
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7bb6f7c key_idx=0 set_tx=1 seq_len=6 key_len=16
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant:    addr=f4:f2:6d:22:99:3e
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: External notification - portValid=1
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
06-22 07:43:33.823  6093  6093 D wpa_supplicant: RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: Group Key - hexdump(len=16): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
06-22 07:43:33.823  6093  6093 D wpa_supplicant: WPA: RSC - hexdump(len=6): 77 f1 7f 00 00 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed133a key_idx=1 set_tx=0 seq_len=6 key_len=16
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: KEY_SEQ - hexdump(len=6): 77 f1 7f 00 00 00
06-22 07:43:33.823  6093  6093 D wpa_supplicant:    broadcast key
06-22 07:43:33.823  6093  6093 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: Cancelling authentication timeout
06-22 07:43:33.823  6093  6093 E wpa_supplicant: wlan0: BLACKLIST REMOVE f4:f2:6d:22:99:3e
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-22 07:43:33.823  6093  6093 D wpa_supplicant: wlan0: Radio work 'connect'@0xb7bb8158 done in 0.172961 seconds
06-22 07:43:33.823  6093  6093 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=2 id_str=]
06-22 07:43:33.823  6093  6093 I wpa_supplicant: setConcurrentAPChannel: Set wifi.hotspot.channel to 8
06-22 07:43:33.853   905  1079 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-22 07:43:33.823  6093  6093 E wpa_supplicant: wlan0: Connect to SSID: NG700
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: Set wlan0 operstate 0->1 (UP)
06-22 07:43:33.823  6093  6093 D wpa_supplicant: netlink: Operstate: ifindex=22 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
06-22 07:43:33.853   905  1079 D ConnectivityService: NetworkAgent connected
06-22 07:43:33.823  6093  6093 I wpa_supplicant: set send_ind_to_ndc = 0
06-22 07:43:33.823  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING (1)+
06-22 07:43:33.823  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: External notification - portValid=1
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: External notification - EAP success=1
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: SUPP_PAE entering state AUTHENTICATING
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: SUPP_BE entering state SUCCESS
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAP: EAP entering state DISABLED
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: SUPP_PAE entering state AUTHENTICATED
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: Supplicant port status: Authorized
06-22 07:43:33.823  6093  6093 D wpa_supplicant: nl80211: Set supplicant port authorized for f4:f2:6d:22:99:3e
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL: SUPP_BE entering state IDLE
06-22 07:43:33.823  6093  6093 D wpa_supplicant: EAPOL authentication completed - result=SUCCESS
06-22 07:43:33.823  6093  6093 I wpa_supplicant: WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
06-22 07:43:33.823  6093  6093 D wpa_supplicant: RTM_NEWLINK: ifi_index=22 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
06-22 07:43:33.823   905  1003 D Tethering: interfaceLinkStateChanged wlan0, true
06-22 07:43:33.823   905  1003 D Tethering: interfaceStatusChanged wlan0, true
06-22 07:43:33.823   905  1003 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=2 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=2 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=2 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=2 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSIDNG700
06-22 07:43:33.823   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:43:33.823   905  6146 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST REMOVE f4:f2:6d:22:99:3e]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: BLACKLIST REMOVE f4:f2:6d:22:99:3e
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=2 id_str=]]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=2 id_str=]
06-22 07:43:33.823   905  6146 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=2 id_str=]
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 Connect to SSID: NG700]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: Connect to SSID: NG700
06-22 07:43:33.823   905  6146 W WifiMonitor: couldn't identify event type - Connect to SSID: NG700
06-22 07:43:33.823   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=2 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
06-22 07:43:33.823   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=2 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange():id=2 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:getSSIDFromString id=2 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
06-22 07:43:33.823   905  6146 D HTCRequest: WifiMonitor:handleSupplicantStateChange(): SSIDNG700
06-22 07:43:33.823   905  6146 D WifiMonitor: WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
06-22 07:43:33.823   905  1495 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:43:33.823   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
06-22 07:43:33.823   905  1076 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
06-22 07:43:33.823   905  1076 E WifiStateMachine: setDetailed state send new extra info"NG700"
06-22 07:43:33.823   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 2, Metered hint: false
06-22 07:43:33.823   905  1005 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-22 07:43:33.823   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:43:33.823   905  1073 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:33.823   905  1073 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:33.823   905   905 D UsbnetService: ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
06-22 07:43:33.823   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:43:33.823   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.823   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=100647  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 2 state: ASSOCIATED
06-22 07:43:33.823   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 4
06-22 07:43:33.823   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.823   905  1076 E WifiStateMachine: handleMessage: E msg.what=147500
06-22 07:43:33.823   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.833   905  1076 E WifiStateMachine:  DisconnectedState !what:147500 0 0
06-22 07:43:33.833   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.833   905  1076 E WifiStateMachine:  ConnectModeState !what:147500 0 0
06-22 07:43:33.8,33   905  1076 D WifiStateMachine: Enter handleAssociatedWithEvent
06-22 07:43:33.833   905  1076 D WifiStateMachine: Setting MAC Address to f4:f2:6d:22:99:3e
06-22 07:43:33.833   905  1076 D WifiStateMachine: Associated
06-22 07:43:33.833  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.833  6018  6018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:43:33.833   905  1076 D WifiStateMachine: mAssociatedMacAddress = f4:f2:6d:22:99:3e
06-22 07:43:33.833   905  1076 D WifiStateMachine: Exit handleAssociatedWithEvent
06-22 07:43:33.833   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.833   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.833   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.833   905  1074 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:33.833   905  1074 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:33.833  6018  6018 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:33.833  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:12
06-22 07:43:33.833  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:33.833  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:33.833  6018  6083 I bt-btm  : BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
06-22 07:43:33.833  6018  6083 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
06-22 07:43:33.833  6018  6203 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
06-22 07:43:33.833  6018  6018 E BluetoothMasService: BluetoothMasObexConnectionManager: mIsEmailEnabled: true
06-22 07:43:33.833   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=100651  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: FOUR_WAY_HANDSHAKE
06-22 07:43:33.833   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
06-22 07:43:33.833   905  1076 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
06-22 07:43:33.833   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 2, Metered hint: false
06-22 07:43:33.833   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.833   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=100657  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: FOUR_WAY_HANDSHAKE
06-22 07:43:33.833   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.833   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 5
06-22 07:43:33.833   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.833   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.843   905  1076 E WifiStateMachine:  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=100658  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: GROUP_HANDSHAKE
06-22 07:43:33.843  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.843   905  1076 E WifiStateMachine: SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
06-22 07:43:33.843   905  1076 E WifiStateMachine: setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
06-22 07:43:33.843   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.843   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=100659  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: GROUP_HANDSHAKE
06-22 07:43:33.843   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.843   905  1076 E WifiStateMachine: handleMessage: E msg.what=147459
06-22 07:43:33.843   905  1076 E WifiStateMachine: processMsg: DisconnectedState
06-22 07:43:33.843  6018  6018 D BluetoothMasService: Add permission for SmsProvider.
06-22 07:43:33.843   905  1076 E WifiStateMachine:  DisconnectedState !NETWORK_CONNECTION_EVENT 2 0 null nid=-1 rt=100660
06-22 07:43:33.843  6018  6018 V BluetoothMasService: Starting MAS instances
06-22 07:43:33.843   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.843  6018  6018 D BluetoothAdapter: 119314783: getState(). Returning 12
06-22 07:43:33.843   905  1076 E WifiStateMachine:  ConnectModeState !NETWORK_CONNECTION_EVENT 2 0 null nid=-1 rt=100660
06-22 07:43:33.843   905  1076 E WifiStateMachine: Network connection established
06-22 07:43:33.843   905  1076 D WifiStateMachine: fetchFrequency(), freq = 2447
06-22 07:43:33.843   905  1076 E WifiStateMachine: setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
06-22 07:43:33.843   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.843   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.843   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 6
06-22 07:43:33.843  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.843   905  1076 E WifiStateMachine: transitionTo: destState=ObtainingIpState
06-22 07:43:33.843   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:33.843   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 7
06-22 07:43:33.843   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
06-22 07:43:33.843   905  1076 E WifiStateMachine: invokeExitMethods: DisconnectedState
06-22 07:43:33.843   905  1076 E WifiStateMachine: setScanAlarm false period 0 initial delay 0
06-22 07:43:33.843   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:33.843   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=1,j=4
06-22 07:43:33.843   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=5
06-22 07:43:33.843   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
06-22 07:43:33.843   905  1076 E WifiStateMachine: invokeEnterMethods: L2ConnectedState
06-22 07:43:33.843   905  1076 E WifiStateMachine: setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
06-22 07:43:33.853   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.853   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 8
06-22 07:43:33.853  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.853  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:33.853  6018  6018 I MailMessageReceiver: reg:com.android.bluetooth.btservice.AdapterApp@10910844 with com.htc.util.mail.MailMessageReceiver@26dd6d2d
06-22 07:43:33.853   905  1076 E WifiStateMachine: L2ConnectedState f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid null
06-22 07:43:33.853   905  1076 E WifiStateMachine: L2ConnectedState "NG700" nid=2
06-22 07:43:33.863  5296  5296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:33.853   905  1076 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:43:33.853   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.853  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='bssid'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=3): [REMOVED]
06-22 07:43:33.853   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.853  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.853   905  1076 E WifiStateMachine: invokeEnterMethods: ObtainingIpState
06-22 07:43:33.853   905  1076 E WifiStateMachine: enter ObtainingIpState netId=2 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
06-22 07:43:33.853   905  1076 E WifiStateMachine: ObtainingIpAddress f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
06-22 07:43:33.853   905  1076 E WifiStateMachine: ObtainingIpAddress "NG700" nid=2
06-22 07:43:33.853   905  1076 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-22 07:43:33.853   905  1076 W WifiHW  : QCOM Debug skip set_network part for security concern!
06-22 07:43:33.853  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_NETWORK [REMOVED]'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: SET_NETWORK id=2 name='bssid'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: value - hexdump(len=3): [REMOVED]
06-22 07:43:33.853   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
06-22 07:43:33.853  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SAVE_CONFIG'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
06-22 07:43:33.853  6093  6093 D wpa_supplicant: Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
06-22 07:43:33.853  6093  6093 D wpa_supplicant: CTRL_IFACE: SAVE_CONFIG - Configuration updated
06-22 07:43:33.863   905  1076 D libc    : [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
06-22 07:43:33.863   905  1076 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:33.863   905  1003 D libc    : [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
06-22 07:43:33.863   905  1003 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:33.863   905  1076 E WifiStateMachine: Start Dhcp Watchdog 1
06-22 07:43:33.863   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.863   905  1076 E WifiStateMachine: handleMessage: E msg.what=147462
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=100684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: COMPLETED
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=100685  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: COMPLETED
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=100685  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 2 state: COMPLETED
06-22 07:43:33.863   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.863   905  1076 E WifiStateMachine: handleMessage: E msg.what=131101
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:33.863  5296  5296 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
06-22 07:43:33.863   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863  5296  5296 D         : Cust_ConnectToPC   : Internet_Sharing>true
06-22 07:43:33.863  5296  5296 D         : Cust_ConnectToPC   : Modem_Link>false
06-22 07:43:33.863  5296  5296 D         : Cust_ConnectToPC   : spcsc>false
06-22 07:43:33.863  5296  5296 D         : Cust_ConnectToPC   : IPT>true
06-22 07:43:33.863  5296  5296 D         : Cust_ConnectToPC   : Singel_USB>false
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.863  5296  5296 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
06-22 07:43:33.863  5296  5296 E SmartNS_Utility: hasRemovableStorageSlot: true
06-22 07:43:33.863  5296  5296 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
06-22 07:43:33.863  5296  5296 D SmartNS_NSReceiver: onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
06-22 07:43:33.863   905  1076 E WifiStateMachine:  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.863   905  1495 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
06-22 07:43:33.863   905  1076 E WifiStateMachine:  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:33.863   905  1076 E WifiStateMachine:  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
06-22 07:43:33.863   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent DefaultState
06-22 07:43:33.863   905  1076 D WifiStateMachine: Default got CMD_TETHER_STATE_CHANGE
06-22 07:43:33.863   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.873   905  1076 E WifiStateMachine: handleMessage: E msg.what=131155
06-22 07:43:33.873   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:33.873   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=2447 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:741] from screen [on:0 period:1990365948]
06-22 07:43:33.873   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:33.873   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=2447 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990365949]
06-22 07:43:33.873   905  1076 E WifiStateMachine:  get link layer stats 2
06-22 07:43:33.873   905  1076 I WifiNative-HAL: startHal
06-22 07:43:33.873   905  1076 E wifi    : getStaticLongField sWifiHalHandle 0xa08bf89c
06-22 07:43:33.873   905  1076 I WifiNative-HAL: Could not start hal
06-22 07:43:33.873   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
06-22 07:43:33.873  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
06-22 07:43:33.873  6093  6093 I wpa_supplicant: environment dirty rate=0 [3][0][0]
06-22 07:43:33.873   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 150
06-22 07:43:33.873   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-51 linkspeed=150
06-22 07:43:33.873   905  1094 D WifiWatchdogStateMachine: RSSI current: 0 new: -51, 3
06-22 07:43:33.873  1123  1123 D WIFI_ICON: updateWifiState: RSSI_CHANGED -1 -> 3
06-22 07:43:33.873  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
06-22 07:43:33.873   905  1076 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-51 "NG700"WPA_PSK
06-22 07:43:33.873   905  1076 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=0.50 txretriesrate=0.00 rxrate=0.00 userTriggerdPenalty0
06-22 07:43:33.873   905  1079 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
06-22 07:43:33.873   905  1076 E WifiStateMachine:  good link -> stuck count =0
06-22 07:43:33.873   905  1076 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 56
06-22 07:43:33.873   905  1076 E WifiStateMachine:  isHighRSSI       ---> score=61
06-22 07:43:33.873   905  1076 E WifiStateMachine: calculateWifiScore() report new score 60
06-22 07:43:33.873   905  1094 D WifiWatchdogStateMachine: RSSI current: 3 new: -51, 3
06-22 07:43:33.873   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.873   905  1076 E WifiStateMachine: handleMessage: E msg.what=131212
06-22 07:43:33.873   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:33.873   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.873   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:33.873   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.873   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.883   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.883   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.883   905  1079 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:43:33.883   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:33.883   905  1076 E WifiStateMachine: Link configuration changed for netId: 2 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
06-22 07:43:33.883   905  1076 E WifiStateMachine: updateLinkProperties nid: 2 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
06-22 07:43:33.883   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.883   905  1076 E WifiStateMachine: handleMessage: E msg.what=196612
06-22 07:43:33.883   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
06-22 07:43:33.883   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:33.883   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
06-22 07:43:33.883   905  1076 D WifiStateMachine: handlePreDhcpSetup Held wake lock during DHCP
06-22 07:43:33.883   905  1076 D PMS     : acquireWL(30ecd9ff): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
06-22 07:43:33.883   905  1076 D WifiStateMachine: handlePreDhcpSetup mBluetoothConnectionActive: false
06-22 07:43:33.883   905  1076 D WifiDataStallTracker: setDhcpActive: true
06-22 07:43:33.883   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 4096
06-22 07:43:33.883   905  1076 E WifiStateMachine: setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
06-22 07:43:33.883   905  1076 E native  : do suspend false
06-22 07:43:33.883   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 4096
06-22 07:43:33.883   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER POWERMODE 1'
06-22 07:43:33.883  6093  6093 I wpa_supplicant: Power_Mode_Type mode = 1
06-22 07:43:33.883  6093  6093 I wpa_supplicant: Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
06-22 07:43:33.883   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
06-22 07:43:33.883  6093  6093 D wpa_supplicant: nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
06-22 07:43:33.883  6093  6093 D wpa_supplicant: nl80211: Rekey offload event for BSSID f4:f2:6d:22:99:3e
06-22 07:43:33.883  6093  6093 D wpa_supplicant: nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Event DRIVER_GTK_REKEY (37) received
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
06-22 07:43:33.883  6093  6093 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
06-22 07:43:33.883   905  1076 E WifiStateMachine: Unexpected BatchedScanResults :null
06-22 07:43:33.883   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
06-22 07:43:33.883  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
06-22 07:43:33.883  6093  6093 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
06-22 07:43:33.883   905  1076 E WifiStateMachine: noteBatchedScanstop()
06-22 07:43:33.883   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:33.893  1123  1123 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
06-22 07:43:33.893  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
06-22 07:43:33.893  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:1
06-22 07:43:33.893  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
06-22 07:43:33.893  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
06-22 07:43:33.903  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
06-22 07:43:33.903  1123  1123 I QuickSettingWifi: receive.wifiConnect:false wifiAPname:null elapse:0
,06-22 07:43:33.923  6093  6093 D wpa_supplicant: EAPOL: startWhen --> 0
06-22 07:43:33.923  6093  6093 D wpa_supplicant: EAPOL: disable timer tick
06-22 07:43:33.923   905  2090 I art     : Explicit concurrent mark sweep GC freed 51457(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 17MB/25MB, paused 990us total 88.638ms
06-22 07:43:33.923  6018  6018 I MailManager: MailManager contruct! com.htc.util.mail.MailMessageReceiver@26dd6d2d
06-22 07:43:33.923  6018  6018 V EmailUtils: Manager Instance is not NULL
06-22 07:43:33.923  5296  5296 I SmartNS_Utility: setISNotification
06-22 07:43:33.933  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
06-22 07:43:33.933  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:33.933  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:33.933   905  1639 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,06-22 07:43:33.953   905  1584 I ActivityManager: Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6206 uid=10065 gids={50065, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,06-22 07:43:33.963  5296  5296 D SmartNS_Utility: usb_cable_connect = 1
,06-22 07:43:33.963  5296  5296 D SmartNS_Utility: usb_denied = 0
06-22 07:43:33.963  1199  1220 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
06-22 07:43:33.963  1123  1123 I RemoteViews: reapply : com.android.settings 1 36
06-22 07:43:33.963  5296  5296 I SmartNS_PSService: usb notificaiton:true
06-22 07:43:33.963   905  1088 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false,
,06-22 07:43:33.973  5296  5296 D SmartNS_NSReceiver: Tethered state change:false isNSOpening:false
,06-22 07:43:33.973  1199  1223 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
06-22 07:43:33.973  1123  1123 I RemoteViews: reapply : com.android.settings 0 36
,06-22 07:43:33.973  5296  6224 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
,06-22 07:43:33.983  5296  6224 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -51, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.983  5296  6224 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.983  5296  6224 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -51, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.983  5296  6224 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
,06-22 07:43:33.983  5296  6224 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -51, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
,06-22 07:43:33.983  5296  6224 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
06-22 07:43:33.983  5296  6224 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -51, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:33.983  5296  6224 D WISPrService: >>>>>WISPrService start isConnected = false<<<<<
,06-22 07:43:33.983  5296  6224 D WISPrService: wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -51, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
,06-22 07:43:34.023  6206  6221 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 6221
,06-22 07:43:34.043  6018  6018 D EmailUtils: ============NULL aList========
,06-22 07:43:34.043  6018  6018 V EmailUtils: <-getEmailAccountIdList
06-22 07:43:34.043  6018  6018 V BluetoothMasService: onCreate: mIsEmailEnabled: true
06-22 07:43:34.043  6018  6018 D BluetoothAdapter: 119314783: getState(). Returning 12
06-22 07:43:34.043  6018  6018 V BluetoothMasService: parseIntent 1: mIsEmailEnabled: true
06-22 07:43:34.043  6018  6018 V EmailUtils: Manager Instance is not NULL
,06-22 07:43:34.043  6018  6018 D EmailUtils: ============NULL aList========
06-22 07:43:34.043  6018  6018 V EmailUtils: <-getEmailAccountIdList
06-22 07:43:34.043  6018  6018 V BluetoothSapReceiver: SapReceiver onReceive 
06-22 07:43:34.043  6018  6018 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:34.043  6018  6018 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
06-22 07:43:34.043  6018  6018 V BluetoothSapReceiver: Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,06-22 07:43:34.053  6018  6018 V BluetoothMasService: handleMessage: mIsEmailEnabledtrue,
06-22 07:43:34.053  6018  6018 V BtMns   : BluetoothMns: isEmailEnabled: true
,06-22 07:43:34.053   905   920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
06-22 07:43:34.053  1687  1687 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-22 07:43:34.053  6018  6018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-22 07:43:34.053  6018  6018 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:34.053  6018  6083 D bt-btm  : BTM_AllocateSCN
06-22 07:43:34.053  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:13
06-22 07:43:34.053  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:34.053  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:34.053  6018  6083 I bt-btm  : BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
06-22 07:43:34.053  6018  6083 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
06-22 07:43:34.053   905  1585 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,06-22 07:43:34.053  6018  6018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-22 07:43:34.053  6018  6018 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:34.053  6018  6083 D bt-btm  : BTM_AllocateSCN
06-22 07:43:34.053  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:14
06-22 07:43:34.053  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:34.053  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:34.053  6018  6083 I bt-btm  : BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
06-22 07:43:34.053  6018  6083 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,06-22 07:43:34.053   905   921 D Process : killProcessQuiet, pid=5595
06-22 07:43:34.053   905   921 I ActivityManager: Killing 5595:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
06-22 07:43:34.063   905   921 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,06-22 07:43:34.063   905  1495 I ActivityManager: Recipient 5595
,06-22 07:43:34.093  6093  6093 D wpa_supplicant: random: Got 1/1 bytes from /dev/random
,06-22 07:43:34.093  6093  6093 D wpa_supplicant: random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,06-22 07:43:34.103  6231  6231 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-22 07:43:34.103  6231  6231 I dhcpcd  : version 5.5.6 starting
06-22 07:43:34.103  6231  6231 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
06-22 07:43:34.103  6231  6231 I dhcpcd  : wlan0: using ClientID 01:00:**:bd:dd:33:d2
06-22 07:43:34.103  6231  6231 I dhcpcd  : autoip env[11]:autoip=DISABLE
,06-22 07:43:34.143  6018  6018 V BluetoothSapService: Sap Service onCreate
06-22 07:43:34.143  6018  6018 V BluetoothSapService: initBinder
06-22 07:43:34.143   905  1495 W libprocessgroup: failed to open /acct/uid_10013/pid_5595/cgroup.procs: No such file or directory
06-22 07:43:34.143  6018  6018 V BluetoothSapService: BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@cb864b0
06-22 07:43:34.143  6018  6018 V BluetoothSapService: Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@f6f42ae
06-22 07:43:34.143   905  1495 D Process : killProcessQuiet, pid=5595
,06-22 07:43:34.143   905  1495 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:34.153  6018  6018 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-22 07:43:34.153  6018  6018 V BluetoothSapService: state: 12
,06-22 07:43:34.153  6018  6018 V BluetoothSapService: Starting SAP server process
06-22 07:43:34.153  6018  6018 V BluetoothSapService: SAP Service startRfcommListenerThread
,06-22 07:43:34.153  5296  5296 D SapServerProfile: Bluetooth service connected
06-22 07:43:34.153  6018  6240 V BluetoothSapService: Sap Service initRfcommSocket
06-22 07:43:34.153   905  1585 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-22 07:43:34.153  6231  6231 I dhcpcd  : wlan0: rebinding lease of 192.168.1.130
06-22 07:43:34.153  6018  6240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-22 07:43:34.153  6231  6231 I dhcpcd  : wlan0: sending REQUEST (xid 0x6c6abda6), next in 0.29 seconds
,06-22 07:43:34.153  6018  6240 I bt-btif : BTA_JvCreateRecordByUser
06-22 07:43:34.153  6018  6083 D bt-sdp  : SDP_CreateRecord ok, num_records:15
06-22 07:43:34.153  6018  6083 I bt-btm  : Write Extended Inquiry Response to controller
06-22 07:43:34.153  6018  6083 I bt-btif : BTA_JvRfcommStartServer
06-22 07:43:34.153  6018  6083 I bt-btm  : BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,06-22 07:43:34.153  6018  6083 I bt-btm  :                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
06-22 07:43:34.153  6018  6240 V BluetoothSapService: Succeed to create listening socket 
06-22 07:43:34.153  6018  6240 V BluetoothSapService: Accepting socket connection...
,06-22 07:43:34.203  6231  6231 I dhcpcd  : wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,06-22 07:43:34.243  6231  6231 I dhcpcd  : wlan0: leased 192.168.1.130 for 172800 seconds
06-22 07:43:34.243   905  1003 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
06-22 07:43:34.243   905  1003 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.243   905  1076 E WifiStateMachine: handleMessage: E msg.what=131212
06-22 07:43:34.243  6231  6231 I dhcpcd  : autoip env[11]:autoip=DISABLE
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:34.243  6018  6018 D A2dpService: getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@24b71bdc
06-22 07:43:34.243  6018  6018 D A2dpSinkService: getA2dpSinkService(): service is NULL
06-22 07:43:34.243   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
,06-22 07:43:34.243   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:34.243   905  1076 E WifiStateMachine:  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: DriverStartedState
,06-22 07:43:34.243   905  1076 E WifiStateMachine:  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:34.243   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: processMsg: DefaultState
,06-22 07:43:34.243   905  1076 E WifiStateMachine:  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
06-22 07:43:34.243   905  1076 E WifiStateMachine: Link configuration changed for netId: 2 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,06-22 07:43:34.243   905  1076 E WifiStateMachine: updateLinkProperties nid: 2 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
06-22 07:43:34.243   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:34.243   905  1079 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,06-22 07:43:34.383  6231  6231 I dhcpcd  : bind_interface: daemonise
,06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
06-22 07:43:34.493   905  6205 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.493   905  1076 E WifiStateMachine: handleMessage: E msg.what=196613
06-22 07:43:34.493   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:34.493   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
06-22 07:43:34.493   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:34.493   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
06-22 07:43:34.503   905  1076 E WifiStateMachine: setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
06-22 07:43:34.503   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
06-22 07:43:34.503  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER POWERMODE 0'
06-22 07:43:34.503  6093  6093 I wpa_supplicant: Power_Mode_Type mode = 0
06-22 07:43:34.503  6093  6093 I wpa_supplicant: Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,06-22 07:43:34.513   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
06-22 07:43:34.513   905  1076 D PMS     : releaseWL(30ecd9ff): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,06-22 07:43:34.513   905  1079 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 4096
06-22 07:43:34.513   905  1076 D WifiDataStallTracker: setDhcpActive: false
,06-22 07:43:34.513   905  1076 E WifiStateMachine: handlePostDhcpSetup release wake lock during DHCP
06-22 07:43:34.513   905  1076 E WifiStateMachine: WifiStateMachine DHCP successful
06-22 07:43:34.513   905  1076 E WifiStateMachine: wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds>
,06-22 07:43:34.513   905  1076 E WifiStateMachine: link address 192.168.1.130/24
06-22 07:43:34.513   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
,06-22 07:43:34.523  1123  1123 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3,
,06-22 07:43:34.513   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 MIRROR-STATUS 0",
,06-22 07:43:34.523  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wlan0: Control interface command 'MIRROR-STATUS 0'
06-22 07:43:34.523   905  1079 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
06-22 07:43:34.513  6093  6093 I wpa_supplicant: MIRROR-STATUS+
06-22 07:43:34.533   905  1079 D ConnectivityService: Adding iface wlan0 to network 100
06-22 07:43:34.513  6093  6093 I wpa_supplicant: MIRROR-STATUS : Off
06-22 07:43:34.533   905   905 D HtcWifiWanDetect: WAN detection
06-22 07:43:34.513   905  1076 E WifiStateMachine: Link configuration changed for netId: 2 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
06-22 07:43:34.533   905   905 D HtcWifiWanDetect: canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
06-22 07:43:34.513   905  1076 E WifiStateMachine: updateLinkProperties nid: 2 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
06-22 07:43:34.543   905  1074 V NetworkPolicy: mWifiStateReceiver: meteredHint=false,EPS mode=false
06-22 07:43:34.513   905  1076 E WifiStateMachine: gateway: /192.168.1.1
06-22 07:43:34.543  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED connected
06-22 07:43:34.513   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
06-22 07:43:34.553   905  1074 V NetworkPolicy: mWifiStateReceiver: meteredHint=false,EPS mode=false
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
06-22 07:43:34.573  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
06-22 07:43:34.513  6093  6093 I wpa_supplicant: WiFi gateway: 0x101a8c0
06-22 07:43:34.573   905  1079 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-22 07:43:34.513   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:34.573   905  1079 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-22 07:43:34.513   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 MIRROR-STATUS 0"
06-22 07:43:34.573   905  1079 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wlan0: Control interface command 'MIRROR-STATUS 0'
06-22 07:43:34.573   905  1079 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
06-22 07:43:34.513  6093  6093 I wpa_supplicant: MIRROR-STATUS+
06-22 07:43:34.573   905  1079 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-22 07:43:34.513  6093  6093 I wpa_supplicant: MIRROR-STATUS : Off
06-22 07:43:34.573   905  1079 D Nat464Xlat: requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
06-22 07:43:34.513   905  1076 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent L2ConnectedState
06-22 07:43:34.573   905  1079 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.513   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:34.573   905  1079 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.513   905  1076 E WifiStateMachine: handleMessage: E msg.what=131210
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo,:
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:34.583   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:34.513   905  1076 E WifiStateMachine: processMsg: ObtainingIpState
06-22 07:43:34.583   905  1079 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.513   905  1076 E WifiStateMachine:  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-22 07:43:34.583   905  1079 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.513   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:34.583   905  1079 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.513   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
06-22 07:43:34.583   905  1079 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.513   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
06-22 07:43:34.583   905  1079 D ConnectivityService: currentScore = 0, newScore = 20
06-22 07:43:34.513  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
06-22 07:43:34.583   905  1079 D ConnectivityService:    accepting network in place of null
06-22 07:43:34.523  6093  6093 I wpa_supplicant: environment dirty rate=0 [2][0][0]
06-22 07:43:34.583   905  1079 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
06-22 07:43:34.523   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 150
06-22 07:43:34.583  1123  1123 D WIFI_ICON: updateWifiState: NETWORK_STATE_CHANGED connected
06-22 07:43:34.523   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-50 linkspeed=150
06-22 07:43:34.583  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
06-22 07:43:34.523   905  1076 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-50 "NG700"WPA_PSK
06-22 07:43:34.583   905  1079 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
06-22 07:43:34.523   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
06-22 07:43:34.593   905  1079 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-22 07:43:34.523  6093  6093 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
06-22 07:43:34.593   905  1079 D ConnectivityService: sendGeneralBroadcast, restrictEnable=false
06-22 07:43:34.523  6093  6093 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
06-22 07:43:34.593   905  1079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-22 07:43:34.523   905  6146 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
06-22 07:43:34.593   905  1079 D ConnectivityService: sendGeneralBroadcastDelayed, restrictEnable=false
06-22 07:43:34.523   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: BLACKLIST CLEAR 
06-22 07:43:34.593   905  1079 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-22 07:43:34.523   905  1076 E WifiStateMachine: setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
06-22 07:43:34.593   905  1073 D PMS     : acquireWL(202db064): PARTIAL_WAKE_LOCK  NetworkStats 0x,1 905 1000 null
06-22 07:43:34.523   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -50, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:34.593   905  1079 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
06-22 07:43:34.533   905  1094 D WifiWatchdogStateMachine: RSSI current: 3 new: -50, 3
06-22 07:43:34.603  1123  1123 D DATA_ICON: updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Connected:true/Type:1/Status:0
06-22 07:43:34.533   905   905 D WifiDataStallTracker: NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
06-22 07:43:34.603  1123  1123 D DATA_ICON: dataConnected: false/false
06-22 07:43:34.533   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 9
06-22 07:43:34.603  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
06-22 07:43:34.533   905   905 E WifiTrafficPoller:  packet count Tx=2 Rx=1
06-22 07:43:34.603   905  1073 D PMS     : releaseWL(202db064): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-22 07:43:34.533  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:34.603   905  1079 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.533   905   905 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL true Token 0
06-22 07:43:34.603   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.543   905  6269 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
06-22 07:43:34.603   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.543   905  6269 D WifiDataStallTracker: updateDataStallInfo: NONE
06-22 07:43:34.613   905  1079 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.543   905  6269 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
06-22 07:43:34.613   905  1079 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.553   905  1076 E WifiStateMachine: [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -50, Link speed: 150, Frequency: 2447, Net ID: 2, Metered hint: false
06-22 07:43:34.613   905  1079 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.553   905  1076 E WifiStateMachine: transitionTo: destState=ConnectedState
06-22 07:43:34.613   905  1079 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.553   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 10
06-22 07:43:34.613   905  1079 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.553   905   905 E WifiTrafficPoller:  packet count Tx=2 Rx=1
06-22 07:43:34.613   905  1079 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-22 07:43:34.553   905  1076 E WifiStateMachine: handleMessage: new destination call exit/enter
06-22 07:43:34.613   905  1079 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-22 07:43:34.553   905  1076 E WifiStateMachine: setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
06-22 07:43:34.613   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.553   905  1076 E WifiStateMachine: invokeExitMethods: ObtainingIpState
06-22 07:43:34.613   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.553   905  1076 E WifiStateMachine: moveTempStackToStateStack: i=0,j=5
06-22 07:43:34.613   905  1079 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:34.553   905  1076 E WifiStateMachine: moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
06-22 07:43:34.613   905  1079 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
06-22 07:43:34.553   905  1076 E WifiStateMachine: invokeEnterMethods: ConnectedState
06-22 07:43:34.613   905  1079 D ConnectivityService: sendGeneralBroadcast, restrictEnable=false
06-22 07:43:34.553   905  1076 E WifiStateMachine: updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
06-22 07:43:34.613   905  1079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-22 07:43:34.573   905  1076 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
06-22 07:43:34.613  1123  1123 D DATA_ICON: updateConnectivity android.net.conn.INET_CONDITION_ACTION Connected:true/Type:1/Status:100
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
06-22 07:43:34.613  1123  1123 D DATA_ICON: dataConnected: false/false
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.613  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.573  1123  1302 I IntentController: receive(android.net.wifi.STATE_CHANGE,1,false)
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.573   905  1079 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
06-22 07:43:34.573   905  1079 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
06-22 07:43:34.573   455   855 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.583   905  6204 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:43:34.583   905  6204 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
06-22 07:43:34.583   905  6204 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-22 07:43:34.583   905  1076 E WifiStateMachine: ConnectedState Enter  mScreenOn=true scanperiod=20000
06-22 07:43:34.583   905  1076 E WifiStateMachine: setScanAlarm true period 20000 initial delay 200
06-22 07:43:34.583   905  6204 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
06-22 07:43:34.583   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:34.583   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:34.583  1123  1123 I QuickSettingWifi: receive.wifiConnect:true wifiAPname:NG700 elapse:0
06-22 07:43:34.583   905  1089 D usbnet  : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.583   905  1089 D usbnet  :   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.583   905  1089 D usbnet  : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
06-22 07:43:34.583   905  1076 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.593   905  1076 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.593   905  1076 D WIFI    : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
06-22 07:43:34.593   905   905 D WirelessDisplayService: [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
06-22 07:43:34.593   905   905 D WirelessDisplayService:  ConnectivityReceiver: receiver wifi connected, check dongle : 0
06-22 07:43:34.593   905  1074 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-22 07:43:34.593   905  1074 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:34.593   905  1074 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-22 07:43:34.593   905  1074 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:34.593   905  1074 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:34.603   905  1074 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:34.603   455  6272 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-22 07:43:34.603   455  6272 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:34.603  5296  6271 D WISPrService: >>>>>WISPrService start isConnected = true<<<<<
06-22 07:43:34.613  1123  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:43:34.613   905  1076 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.613   905  1076 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.613   905  1076 D WIFI    : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
06-22 07:43:34.613   905  1089 D usbnet  : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:34.613   905  1089 D usbnet  :   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.613   905  1089 D usbnet  : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
06-22 07:43:34.613  1123  1605 I SecurityController: onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.613  1123  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-22 07:43:34.623   905  1076 E WifiStateMachine: handleMessage: E msg.what=131131
06-22 07:43:34.623   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:34.623  1123  1605 I SecurityController: onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-22 07:43:34.623   905  1076 E WifiStateMachine:  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.623   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:34.623   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.623   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:34.623   905  1076 E WifiStateMachine:  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.623   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:34.623  1123  1123 I QuickSettingWifi: receive.wifiConnect:true wifiAPname:NG700 elapse:0
06-22 07:43:34.633  5296  6271 D WISPrService: >>>>>WISPrService start isConnected = true<<<<<
06-22 07:43:34.633   905  1076 E WifiStateMachine: handleMessage: E msg.what=131131
06-22 07:43:34.633   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:34.633   905  1076 E WifiStateMachine:  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.633   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:34.633   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.633   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:34.633   905  1076 E WifiStateMachine:  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=4
06-22 07:43:34.633   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:34.653   455  6272 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:34.653   455  6272 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:34.653   905  1074 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:43:34.673   905  1074 V NetworkPolicy: ensureActiveMobilePolicyLocked()
06-22 07:43:34.683   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 07:43:34.683   905  1074 V NetworkPolicy: updateIfacesLocked()
06-22 07:43:34.683   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 07:43:34.683   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 07:43:34.683   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 07:43:34.693   905  1065 D PMS     : acquireWL(29fd9782): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075}
06-22 07:43:34.693   905  1065 V AlarmManager: sending alarm PendingIntent{15af4e93: PendingIntentRecord{22e306 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574214702, Int=0
06-22 07:43:34.693   905   905 D PMS     : releaseWL(29fd9782): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,06-22 07:43:34.853  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:34.863  1687  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 07:43:34.863  1687  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,06-22 07:43:34.863  1687  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:34.863  1687  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:34.873  1687  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:34.873  5319  5319 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 07:43:34.873  5319  5319 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,06-22 07:43:34.873  5319  5319 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,06-22 07:43:35.363   905  1011 I PMS     : Going to sleep due to screen timeout (uid 1000)...,
,06-22 07:43:35.363   905   905 I SensorManager: unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3f9e78e3,
,06-22 07:43:35.363   905  1011 I PMS     : Sleeping (uid 1000)...,
,06-22 07:43:35.363   905   905 W SensorService: Following SensorService logs are not warning, just make sure they are printed
,06-22 07:43:35.363   905   905 D PMN     : goingToSleep
06-22 07:43:35.363   905   905 W SensorService: disable: get sensor name = Accelerometer Sensor
06-22 07:43:35.363   905   905 D PMS     : acquireWL(71ef93d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
06-22 07:43:35.363   905   905 W SensorService: pid=905, uid=1000
06-22 07:43:35.373   905  1013 D ActivityManager: getTaskThumbnailLocked mainThumbnail is null, TaskRecord{3a4ee532 #33 A=com.test.thalitest U=0 sz=1}
06-22 07:43:35.363   905   905 W SensorService: Active sensors: size = 3
06-22 07:43:35.373   905  1013 W PMS     : mWirelessDisplayManager is null
,06-22 07:43:35.363   905   905 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
06-22 07:43:35.403   905  1000 I ActivityManager: Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6297 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=armeabi-v7a
06-22 07:43:35.363   905   905 W SensorService: CM36282 Light sensor (handle=0x00000003, connections=1)
06-22 07:43:35.403   905   905 D AlarmManager: ACTION_SCREEN_ON
06-22 07:43:35.363   905   905 W SensorService: CM36282 Proximity sensor (handle=0x00000004, connections=1)
06-22 07:43:35.403   905   905 I AlarmManager: [AlarmQueuing] recover blocked alarms
,06-22 07:43:35.363   905   905 W SensorService: SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3f9e78e3, eanble = 0, strlen(mName) = 91,
06-22 07:43:35.403   905   905 I AlarmManager: [AlarmQueuing] done recovering
06-22 07:43:35.363   905   905 W SensorService: Active Listeners: mActiveListeners.size() = 2
06-22 07:43:35.403   905   905 I AlarmManager: [AlarmQueuing] recover EPS screen off blocked alarms
06-22 07:43:35.363   905   905 W SensorService: Listener[0] = com.android.server.display.AutomaticBrightnessController$1@28590165
06-22 07:43:35.403   905   905 I AlarmManager: [AlarmQueuing] done EPS screen off alarm recovering
,06-22 07:43:35.363   905   905 W SensorService: Listener[1] = com.htc.smartdim.sensor_eye@11905446
06-22 07:43:35.413   905  2090 D PMS     : releaseWL(71ef93d): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
06-22 07:43:35.363   905   905 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
06-22 07:43:35.413   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:35.413   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
,06-22 07:43:35.413   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:35.413   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:35.413   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:35.413   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:35.363  5914  5914 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-22 07:43:35.423  1123  1123 D WIFI_ICON: WifiActivity: 3
06-22 07:43:35.363  5914  5914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-22 07:43:35.423   905  1074 D NetworkPolicy: updateScreenOn: false
06-22 07:43:35.373   905  1013 D WirelessDisplayService: Screen File Receiver; callOnGoing: false, Screen On: false
06-22 07:43:35.423   905  1074 V NetworkPolicy: updateIfacesLocked()
,06-22 07:43:35.373   905  1013 D WirelessDisplayService: ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
06-22 07:43:35.433  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
06-22 07:43:35.383   905  1011 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:35.383   905  1011 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:35.383   905  1011 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:35.383   905  1011 I Adreno-EGL: Local Branch: 
06-22 07:43:35.383   905  1011 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:35.383   905  1011 I Adreno-EGL: Local Patches: NONE
06-22 07:43:35.383   905  1011 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:35.443  1123  1123 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
06-22 07:43:35.403   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL true Token 11
06-22 07:43:35.443  1123  1123 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,06-22 07:43:35.403   905   905 E WifiTrafficPoller:  packet count Tx=4 Rx=4
06-22 07:43:35.403   905   905 E WifiTrafficPoller: notifying of data activity 3
06-22 07:43:35.403   905   905 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL true Token 1
06-22 07:43:35.403   905  1076 E WifiStateMachine: handleMessage: E msg.what=131167
06-22 07:43:35.403   905  1076 E WifiStateMachine: processMsg: ConnectedState
,06-22 07:43:35.403   905  1076 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
06-22 07:43:35.403   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.403   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
06-22 07:43:35.403   905   905 D WirelessDisplayService: ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
06-22 07:43:35.413   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:35.413   905  1076 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
,06-22 07:43:35.413   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:35.413   905  1076 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
06-22 07:43:35.413   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:35.413   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
,06-22 07:43:35.413   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:35.413   905  1076 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
06-22 07:43:35.413   905  1076 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
06-22 07:43:35.413   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
06-22 07:43:35.413  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 1'
,06-22 07:43:35.413  6093  6093 I wpa_supplicant: SET_SCREEN_ON:On
,06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_keepalive +
06-22 07:43:35.473   905  1079 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_keepalive: enable=0, type=2, interval=15
06-22 07:43:35.473   905  1079 D ConnectivityService: identical MTU - not setting
,06-22 07:43:35.413  6093  6093 D wpa_supplicant: getPrivFuncNum +	
06-22 07:43:35.473   905  1079 D Nat464Xlat: requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
06-22 07:43:35.413  6093  6093 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
06-22 07:43:35.473   905  1079 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
06-22 07:43:35.473   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
06-22 07:43:35.473   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING (1)+
06-22 07:43:35.473   905  1079 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:35.413  6093  6093 I wpa_supplicant: htc_wext_set_TX_TRACKING - ret = 0
06-22 07:43:35.413  5914  5914 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@30bcb811 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@152816ca, 16908290=android.view.AbsSavedState$1@152816ca}, android:focusedViewId=100}]}]
06-22 07:43:35.413  5914  5914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-22 07:43:35.413  5914  5914 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-22 07:43:35.413  5914  5914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
06-22 07:43:35.413   905  1076 I WifiNative-HAL: startHal
06-22 07:43:35.413   905  1076 E wifi    : getStaticLongField sWifiHalHandle 0xa08bf81c
06-22 07:43:35.413   905  1076 I WifiNative-HAL: Could not start hal
06-22 07:43:35.413   905  1076 E WifiStateMachine: setScanAlarm true period 20000 initial delay 200
06-22 07:43:35.413   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:35.413   905  1076 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
06-22 07:43:35.413   905  1076 E WifiStateMachine: handleScreenStateChanged Exit: true
06-22 07:43:35.413   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.413   905  1076 E WifiStateMachine: handleMessage: E msg.what=131154
06-22 07:43:35.413   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.413   905  1076 E WifiStateMachine:  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:35.423   905  6306 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
06-22 07:43:35.423   460  1062 V SRS_Proc: ParamSet string: screen_state=on
06-22 07:43:35.423   460  1062 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-22 07:43:35.423   905  1529 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,06-22 07:43:35.423   905  6306 D WifiDataStallTracker: updateDataStallInfo: NONE
06-22 07:43:35.423   905  6306 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
06-22 07:43:35.433   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.433   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
06-22 07:43:35.433   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
06-22 07:43:35.433  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
06-22 07:43:35.433  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
06-22 07:43:35.433   905   999 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
06-22 07:43:35.433  6093  6093 I wpa_supplicant: environment dirty rate=0 [3][0][0]
06-22 07:43:35.443   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 150
06-22 07:43:35.443   905  1076 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-51 linkspeed=150
06-22 07:43:35.443   905  1076 E WifiStateMachine: BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
06-22 07:43:35.443   905  1094 D WifiWatchdogStateMachine: RSSI current: 3 new: -51, 3
06-22 07:43:35.443   905  1076 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-50 "NG700"WPA_PSK
06-22 07:43:35.443   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.443   905  1076 E WifiStateMachine: handleMessage: E msg.what=131127
06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.443   905  1076 E WifiStateMachine:  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
,06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.443   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
06-22 07:43:35.483   905  1079 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100],
06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:35.483   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-22 07:43:35.443   905  1076 E WifiStateMachine:  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
06-22 07:43:35.483   905  1079 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:35.443   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.483   905  1079 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
06-22 07:43:35.443   905  1076 E WifiStateMachine: handleMessage: E msg.what=131129
06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.443   905  1076 E WifiStateMachine:  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.443   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
06-22 07:43:35.443   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:35.443   905  1076 E WifiStateMachine:  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
,06-22 07:43:35.443   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
06-22 07:43:35.443  6093  6093 D wpa_supplicant: wlan0: Control interface command 'BLACKLIST clear'
06-22 07:43:35.443  6093  6093 E wpa_supplicant: wlan0: BLACKLIST CLEAR 
06-22 07:43:35.443   905  6146 D WifiMonitor: Event [IFNAME=wlan0 BLACKLIST CLEAR ]
06-22 07:43:35.443   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: BLACKLIST CLEAR 
06-22 07:43:35.443  1123  6307 E sensohubinterface: JNI_OnLoad called
06-22 07:43:35.443  1123  6307 E sensohubinterface: switchDebug: could not open i2c (13,Permission denied)
06-22 07:43:35.443  1123  6307 E sensohubinterface: switchDebug: cmd[0] 0xff
06-22 07:43:35.443  1123  6307 E sensohubinterface: switchDebug: cmd[1] 0x0
06-22 07:43:35.443  1123  6307 E sensohubinterface: switchDebug: failed errno = 9
06-22 07:43:35.443   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.473   905  1003 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x666538303a3a32),sn(),hints(known),family 0,flags 4
06-22 07:43:35.473   905  1003 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:35.473   905  1076 E WifiStateMachine: handleMessage: E msg.what=131212
06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,06-22 07:43:35.473   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:35.473   905  1076 E WifiStateMachine:  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
06-22 07:43:35.473   905  1076 E WifiStateMachine: Link configuration changed for netId: 2 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::2ee:bdff:fedd:33d2/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
06-22 07:43:35.473   905  1076 E WifiStateMachine: updateLinkProperties nid: 2 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
06-22 07:43:35.483  1123  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-22 07:43:35.483  1123  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-22 07:43:35.483   905  1076 E WifiStateMachine: handleMessage: X,
,06-22 07:43:35.493  1123  1302 I IntentController: receive(android.intent.action.SCREEN_ON,1,false),
06-22 07:43:35.493   905  1639 D PMS     : acquireWL(3482227e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:35.503   905  1636 D PMS     : acquireWL(2d5f43df): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:35.503   905  1528 D PMS     : releaseWL(2d5f43df): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:35.503   905   920 D PMS     : acquireWL(35b8082c): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null,
06-22 07:43:35.503   905  1266 D PMS     : releaseWL(3482227e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:35.503   905   921 D PMS     : releaseWL(35b8082c): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
,06-22 07:43:35.503  6297  6297 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-22 07:43:35.523   905   905 D AlarmManager: ACTION_SCREEN_OFF
06-22 07:43:35.523  1123  6331 E sensohubinterface: switchDebug: could not open i2c (13,Permission denied)
,06-22 07:43:35.523  1123  6331 E sensohubinterface: switchDebug: cmd[0] 0xff
06-22 07:43:35.523  1123  6331 E sensohubinterface: switchDebug: cmd[1] 0x1
06-22 07:43:35.523  1123  6331 E sensohubinterface: switchDebug: failed errno = 9
,06-22 07:43:35.523   905   905 I AlarmManager: [AlarmQueuing] screen off now: 
06-22 07:43:35.523   905  1011 I SensorManager: unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@28590165
06-22 07:43:35.523   905  1011 W SensorService: Following SensorService logs are not warning, just make sure they are printed
06-22 07:43:35.523   905  1011 W SensorService: disable: get sensor name = CM36282 Light sensor
06-22 07:43:35.523   905   905 I AlarmManager: [AlarmQueuing] data connection: false
,06-22 07:43:35.523   905   905 I AlarmManager: [AlarmQueuing] wifi connection: true
06-22 07:43:35.523   905  1006 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 449.704 x 447.412 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
06-22 07:43:35.523   905  1011 W SensorService: pid=905, uid=1000,
06-22 07:43:35.523   905   905 V ActivityManager: Display changed displayId=0
06-22 07:43:35.523   905  1011 W SensorService: Active sensors: size = 2
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:35.533   905  1076 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:35.523   905  1011 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
06-22 07:43:35.533   905  1074 D NetworkPolicy: updateScreenOn: false
06-22 07:43:35.523   905  1011 W SensorService: CM36282 Proximity sensor (handle=0x00000004, connections=1)
06-22 07:43:35.533   905  1074 V NetworkPolicy: updateIfacesLocked()
06-22 07:43:35.523   905  1011 W SensorService: SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@28590165, eanble = 0, strlen(mName) = 67
06-22 07:43:35.523   905  1011 W SensorService: Active Listeners: mActiveListeners.size() = 1
06-22 07:43:35.523   905  1011 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@11905446
06-22 07:43:35.523   905  1011 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
06-22 07:43:35.523   905   905 E WifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL false Token 12
06-22 07:43:35.523   905   905 D WifiDataStallTracker: stopDataStallAlarm 
06-22 07:43:35.523   905   905 E WifiDataStallTracker: ENABLE_DATA_MONITOR_POLL false Token 2
06-22 07:43:35.523   905  1076 E WifiStateMachine: handleMessage: E msg.what=131167
06-22 07:43:35.523   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.523   905  1076 E WifiStateMachine:  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.523   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.533  1199  1199 D DotMatrix: [EventService]  onDisplayChanged: 0
06-22 07:43:35.533   905  1076 E WifiStateMachine:  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: ConnectModeState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: DriverStartedState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine:  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
06-22 07:43:35.533   905  1076 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
06-22 07:43:35.533  6093  6093 D wpa_supplicant: wlan0: Control interface command 'SET_SCREEN_ON 0'
06-22 07:43:35.533  6093  6093 I wpa_supplicant: SET_SCREEN_ON:Off
06-22 07:43:35.533  6093  6093 I wpa_supplicant: htc_wext_set_keepalive +
06-22 07:43:35.533  6093  6093 I wpa_supplicant: htc_wext_set_keepalive: enable=1, type=2, interval=15
06-22 07:43:35.533  6093  6093 D wpa_supplicant: getPrivFuncNum +	
06-22 07:43:35.533  6093  6093 I wpa_supplicant: getPrivFuncNum -, cmd = 0x8bf6
06-22 07:43:35.533  6093  6093 I wpa_supplicant: htc_wext_set_keepalive fnum = 0x8bf6
06-22 07:43:35.533  6093  6093 I wpa_supplicant: get_ip_address source addr = c0a80182
06-22 07:43:35.533  6093  6093 I wpa_supplicant: htc_wext_set_keepalive gateway addr = c0a80101
06-22 07:43:35.533  1199  1199 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
06-22 07:43:35.533  6093  6093 I wpa_supplicant: htc_wext_set_keepalive - ret = 0
06-22 07:43:35.533   460  1087 V SRS_Proc: ParamSet string: screen_state=off
06-22 07:43:35.533   460  1087 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
06-22 07:43:35.533  1123  1123 I SensorManager: registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@598bbd8, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="HTC Group Ltd.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=20000}, delay = 200000, handler = null
06-22 07:43:35.533   905   905 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 7
06-22 07:43:35.533   905  1076 E WifiStateMachine: setScanAlarm false period 20000 initial delay 0
06-22 07:43:35.533   905  1076 D WirelessDisplayService: getMirrorDisplayStatus:falsecurState:1
06-22 07:43:35.533   905  1636 W SensorService: Following SensorService logs are not warning, just make sure they are printed
06-22 07:43:35.533   905  1636 W SensorService: enable: get sensor name = hTC Gesture Motion HIDI
06-22 07:43:35.533   905  1076 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
06-22 07:43:35.533   905  1076 E WifiStateMachine: handleScreenStateChanged Exit: false
06-22 07:43:35.533   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.533   905  1076 E WifiStateMachine: handleMessage: E msg.what=131154
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:35.533   905  1076 E WifiStateMachine:  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
06-22 07:43:35.533   905  1076 E WifiStateMachine: handleMessage: X
06-22 07:43:35.533   905  1636 W SensorService: pid=1123, uid=10043
06-22 07:43:35.533   905  1636 W SensorService: Active sensors: size = 3
06-22 07:43:35.533   905  1636 W SensorService: Accelerometer Sensor (handle=0x00000000, connections=1)
06-22 07:43:35.533   905  1636 W SensorService: CM36282 Proximity sensor (handle=0x00000004, connections=1)
06-22 07:43:35.533   905  1636 W SensorService: hTC Gesture Motion HIDI (handle=0x00000015, connections=1)
06-22 07:43:35.533   905  1586 W SensorService: SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@598bbd8, eanble = 1, strlen(mName) = 56
06-22 07:43:35.533   905  1586 W SensorService: Active Listeners: mActiveListeners.size() = 2
06-22 07:43:35.533   905  1586 W SensorService: Listener[0] = com.htc.smartdim.sensor_eye@11905446
06-22 07:43:35.533   905  1586 W SensorService: Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@598bbd8
06-22 07:43:35.533   905  1586 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
06-22 07:43:35.543  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:43:35.543  1199  1199 D DotMatrix: [EventService] getTotalRam: 1823 Mb
06-22 07:43:35.543   905   999 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
06-22 07:43:35.543  1457  6333 D ContactMessageStore: start background delete task...
06-22 07:43:35.543  1457  6333 D ContactMessageStore: size: 0 , 0
06-22 07:43:35.543  1457  6333 D ContactMessageStore: Background delete complete
06-22 07:43:35.553   905   905 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 7
06-22 07:43:35.553  1123  1302 I IntentController: receive(android.intent.action.SCREEN_OFF,1,false)
06-22 07:43:35.553  6297  6297 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@393889b4(com.htc.providers.calendar.HtcCalendarProvider@c3fa9dd)
06-22 07:43:35.553   905  1282 D PMS     : acquireWL(16b60356): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:35.553   905  1584 D PMS     : releaseWL(16b60356): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:35.553  6297  6334 D CalendarProvider2: wait start:true
,06-22 07:43:35.573   905  1282 D PMS     : acquireWL(32ba272e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:35.573   905  2090 D PMS     : releaseWL(32ba272e): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:35.573   905  1585 D PMS     : acquireWL(cc6e2cf): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
06-22 07:43:35.573   905  1708 D PMS     : releaseWL(cc6e2cf): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
06-22 07:43:35.593  6297  6334 D CalendarProvider2: wait end:false
,06-22 07:43:35.633   905  1584 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,06-22 07:43:35.653   467   467 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 143us total 13.493ms
,06-22 07:43:35.663   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 129us total 8.531ms
,06-22 07:43:35.673   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 8.949ms
,06-22 07:43:35.703  6338  6338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,06-22 07:43:35.703  6338  6356 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
06-22 07:43:35.713   905  1636 D PMS     : releaseWL(2a04d630): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,06-22 07:43:35.713   905  1100 D SurfaceControl: Excessive delay in setPowerMode(): 186ms
06-22 07:43:35.713   905  1100 D PMS     : Setting HAL interactive mode to false
06-22 07:43:35.713   905  1100 D PMS     : Setting HAL interactive mode to false done
06-22 07:43:35.713   905  1100 D PMS     : Setting HAL auto-suspend mode to true
06-22 07:43:35.713   905  1100 D PMS     : Setting HAL auto-suspend mode done
06-22 07:43:35.713   905   905 I InputManager: Cancel all due to getting PMS screen off broadcast,
06-22 07:43:35.713   905  1100 D HABCtrl : TPE algorithm. remove timeout.
06-22 07:43:35.713   905  1100 D PMS     : OOBE c monitor 11
06-22 07:43:35.713   905  1002 I InputMethodManagerService: screenObserver, isScreenOn=false
06-22 07:43:35.713   905  1002 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-22 07:43:35.713   905  1002 I InputMethodManagerService: Disable input method client, pid=5914
,06-22 07:43:35.713  5914  5914 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{5feca8b VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@233f703b
06-22 07:43:35.713   905  1529 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: C0006, enable: true
06-22 07:43:35.713  1476  1575 D NfcService: ScreenObserver: OFF
06-22 07:43:35.713  1123  1302 I IntentController: receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,06-22 07:43:35.713  6338  6338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:35.713  1476  6357 D NfcService: applyRouting - 0
,06-22 07:43:35.713   905   920 D PMS     : acquireWL(3d45883a): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1476 1027 null
06-22 07:43:35.713  1476  6357 D NfcService: applyRouting -2
06-22 07:43:35.713  1476  6357 D NfcService: applyRouting
06-22 07:43:35.713  1476  6357 D NfcService: Ignore this applyRouting...
,06-22 07:43:35.713   905  1639 D PMS     : releaseWL(3d45883a): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,06-22 07:43:35.723  6338  6358 D SmartSyncUtils: isEpsOn(), nState = 0,
06-22 07:43:35.723   905  1585 W BatSI   : Couldn't get kernel wake lock stats
06-22 07:43:35.723   905  1637 D PMS     : acquireWL(1cf8dceb): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6338 1000 null
06-22 07:43:35.743   905   905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:35.743   905  1637 D PMS     : releaseWL(1cf8dceb): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,06-22 07:43:35.743   905   905 D SmartDim: Init customizeScreenOffDelayClass error
,06-22 07:43:35.763  6338  6338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,06-22 07:43:35.763  6338  6338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
06-22 07:43:35.763  1123  1123 I ClockController: stop clock update:screen off
,06-22 07:43:35.763  6338  6338 D SmartSyncUtils: isEpsOn(), nState = 0,
06-22 07:43:35.763  6338  6363 D SmartSyncUtils: isEpsOn(), nState = 0
,06-22 07:43:35.773  6338  6338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,06-22 07:43:35.773   905   905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
06-22 07:43:35.773   905   905 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@11905446
06-22 07:43:35.773   905   905 W SensorService: Following SensorService logs are not warning, just make sure they are printed,
,06-22 07:43:35.773   905   905 W SensorService: disable: get sensor name = Accelerometer Sensor
06-22 07:43:35.773   905   905 W SensorService: pid=905, uid=1000
06-22 07:43:35.773   905   905 W SensorService: Active sensors: size = 2
06-22 07:43:35.773   905   905 W SensorService: CM36282 Proximity sensor (handle=0x00000004, connections=1)
06-22 07:43:35.773   905   905 W SensorService: hTC Gesture Motion HIDI (handle=0x00000015, connections=1)
06-22 07:43:35.773   905   905 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@11905446, eanble = 0, strlen(mName) = 36,
06-22 07:43:35.773   905   905 W SensorService: Active Listeners: mActiveListeners.size() = 1
06-22 07:43:35.773   905   905 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@598bbd8
06-22 07:43:35.773   905   905 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
,06-22 07:43:35.773   905   905 W SensorService: Following SensorService logs are not warning, just make sure they are printed,
,06-22 07:43:35.773   905   905 W SensorService: disable: get sensor name = CM36282 Proximity sensor
06-22 07:43:35.773   905   905 W SensorService: pid=905, uid=1000,
06-22 07:43:35.773   905   905 E ActivityThread: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@28456607 that was originally registered here. Are you missing a call to unregisterReceiver()?
06-22 07:43:35.773   905   905 E ActivityThread: android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@28456607 that was originally registered here. Are you missing a call to unregisterReceiver()?
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1749)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1729)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495),
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.Service.onStartCommand(Service.java:458)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
06-22 07:43:35.773   905   905 E ActivityThread: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:35.773   905   905 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 07:43:35.773   905   905 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:35.773   905   905 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028),
06-22 07:43:35.773   905   905 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
06-22 07:43:35.773   905   905 W SensorService: Active sensors: size = 1
06-22 07:43:35.773   905   905 W SensorService: hTC Gesture Motion HIDI (handle=0x00000015, connections=1)
06-22 07:43:35.773   905   905 W SensorService: SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@11905446, eanble = 0, strlen(mName) = 36
06-22 07:43:35.773   905   905 W SensorService: Active Listeners: mActiveListeners.size() = 1
06-22 07:43:35.773   905   905 W SensorService: Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@598bbd8,
06-22 07:43:35.773   905   905 W SensorService: void android::SensorService::listenerSensor(const char*, int32_t)--:
06-22 07:43:35.773   905  6365 I SensorManager: unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@11905446
,06-22 07:43:35.813   905  1586 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6366 uid=10048 gids={50048, 9997, 3003} abi=armeabi-v7a,
,06-22 07:43:35.823  6338  6356 D PowerUsageList:PowerUsageHelper: [CMD_CURRENT_TIME] rec.currentTime < startCurTime, impossible
,06-22 07:43:35.833   905  1639 W BatSI   : Couldn't get kernel wake lock stats
,06-22 07:43:35.873   905   920 D Process : killProcessQuiet, pid=4638
06-22 07:43:35.873   905   920 I ActivityManager: Killing 4638:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
06-22 07:43:35.873   905   920 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 ,
,06-22 07:43:35.883  6338  6363 D SmartSyncUtils: getMobilePolicyEnabled, result = false
,06-22 07:43:35.883   905  1077 D WifiService: New client listening to asynchronous messages,
06-22 07:43:35.883   905   905 E WifiTrafficPoller: ADD_CLIENT: 8
,06-22 07:43:35.883   905  1639 I ActivityManager: Recipient 4638,
,06-22 07:43:35.973   905  1639 D Process : killProcessQuiet, pid=4638,
06-22 07:43:35.973   905  1639 W libprocessgroup: failed to open /acct/uid_10025/pid_4638/cgroup.procs: No such file or directory
06-22 07:43:35.973   905  1639 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:35.973  6338  6356 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,06-22 07:43:35.983   905  1636 D PMS     : acquireWL(3f3ee06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:43:35.983   905  1636 I BatteryService: n_update end
,06-22 07:43:35.983   905  1636 D PMS     : releaseWL(3f3ee06): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:43:35.983   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:43:35.983   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:43:35.983  6338  6356 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
06-22 07:43:35.983   905   905 D PMS     : runPSCheck
06-22 07:43:35.983   905   905 D HtcPowerSaver: Checking...,
06-22 07:43:35.983   905   905 I HtcPowerSaver: >> updateStatus
,06-22 07:43:35.983  6338  6356 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
06-22 07:43:35.983   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
06-22 07:43:35.983   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:43:35.983  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:43:35.983  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:43:35.983  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:43:35.983  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:43:35.983  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:43:35.983  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 07:43:35.983   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:43:35.983   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:43:35.983  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:43:35.983   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:43:35.983   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:43:35.983   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:43:35.983  6338  6356 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,06-22 07:43:36.033  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:43:36.073  6338  6356 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,06-22 07:43:36.073   905  1088 W BatSI   : Couldn't get kernel wake lock stats
,06-22 07:43:36.153  6338  6356 D PowerUsageList:PowerUsageHelper: [CMD_CURRENT_TIME] rec.currentTime < startCurTime, impossible,
,06-22 07:43:36.183   905  1282 D Process : killProcessQuiet, pid=5253
06-22 07:43:36.183   905  1282 I ActivityManager: Killing 5253:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
06-22 07:43:36.183   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:36.203   905  1636 I ActivityManager: Recipient 5253,
,06-22 07:43:36.273   905  1636 D Process : killProcessQuiet, pid=5253,
06-22 07:43:36.273   905  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:36.273   905  1636 W libprocessgroup: failed to open /acct/uid_10089/pid_5253/cgroup.procs: No such file or directory
,06-22 07:43:36.403   905   905 E WifiTrafficPoller: TRAFFIC_STATS_POLL false Token 13 num clients 8,
,06-22 07:43:36.613  6297  6297 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
,06-22 07:43:36.613  6297  6297 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
06-22 07:43:36.653   905  1000 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6395 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
06-22 07:43:36.653   905  1639 D Process : killProcessQuiet, pid=5556
06-22 07:43:36.653   905  1639 I ActivityManager: Killing 5556:com.htc.cs.dm/u0a105 (adj 15): empty #17
06-22 07:43:36.653   905  1639 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:36.733   905  1495 I ActivityManager: Recipient 5556
,06-22 07:43:36.873   905  1495 D Process : killProcessQuiet, pid=5556,
06-22 07:43:36.873   905  1495 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:36.873   905  1495 W libprocessgroup: failed to open /acct/uid_10105/pid_5556/cgroup.procs: No such file or directory
,06-22 07:43:36.873   905  1076 E WifiStateMachine: handleMessage: E msg.what=131155
06-22 07:43:36.873   905  1076 E WifiStateMachine: processMsg: ConnectedState
,06-22 07:43:36.873   905  1076 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1990368956] gl hn u24 rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:43:36.873   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
,06-22 07:43:36.883  6395  6395 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,06-22 07:43:36.883   905  1076 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1990368959] gl hn u24 rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,06-22 07:43:36.883   905  1076 E WifiStateMachine: handleMessage: X
,06-22 07:43:36.893  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
06-22 07:43:36.893  5914  5970 I jxcore-log: 
,06-22 07:43:36.893  6395  6395 D CalendarApplication: onCreate,
,06-22 07:43:36.893  6395  6395 D ProviderChangeReceiver: ---------------------------------------------------,
,06-22 07:43:36.893  6395  6395 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!,
,06-22 07:43:36.903  6395  6433 D HtcAlertService: start to updateAlertNotification!,
,06-22 07:43:36.933   905  1584 I ActivityManager: Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=6435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
06-22 07:43:36.933   905  1584 I ActivityManager: Killing 5629:com.google.android.apps.docs/u0a107 (adj 15): empty #17
06-22 07:43:36.933   905  1584 D Process : killProcessQuiet, pid=5629
06-22 07:43:36.933   905  1584 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,06-22 07:43:36.943   905  1281 I ActivityManager: Recipient 5629,
,06-22 07:43:37.123   905  1281 D Process : killProcessQuiet, pid=5629,
06-22 07:43:37.123   905  1281 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
06-22 07:43:37.123   905  1281 W libprocessgroup: failed to open /acct/uid_10107/pid_5629/cgroup.procs: No such file or directory
,06-22 07:43:37.233  6395  6433 D HtcAlertService: No fired or scheduled alerts
06-22 07:43:37.233  6395  6433 D HtcAlertUtils: -- cancelReminderNotification --
06-22 07:43:37.233  6395  6433 D HtcAlertUtils: broadcastExistReminder!
,06-22 07:43:37.233  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:43:37.243  6435  6435 V Settings:HtcSettingsApplication: [6435/6435] onCreate(),
,06-22 07:43:37.253  6435  6435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 ,
,06-22 07:43:37.313   905  1639 D Process : killProcessQuiet, pid=4272,
06-22 07:43:37.313   905  1639 I ActivityManager: Killing 4272:com.google.android.gms/u0a25 (adj 15): empty #17,
06-22 07:43:37.313   905  1639 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:37.323  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
06-22 07:43:37.323  5914  5970 I jxcore-log: 
,06-22 07:43:37.333   905  1584 I ActivityManager: Recipient 4272,
,06-22 07:43:37.343  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
06-22 07:43:37.343  5914  5970 I jxcore-log: 
,06-22 07:43:37.353  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
06-22 07:43:37.353  5914  5970 I jxcore-log: 
,06-22 07:43:37.363  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
06-22 07:43:37.363  5914  5970 I jxcore-log: 
,06-22 07:43:37.373  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-22 07:43:37.373  5914  5970 I jxcore-log: 
,06-22 07:43:37.393   905  1584 D Process : killProcessQuiet, pid=4272
,06-22 07:43:37.393   905  1584 W libprocessgroup: failed to open /acct/uid_10025/pid_4272/cgroup.procs: No such file or directory
06-22 07:43:37.393   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfofornet-, err=8,
06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:37.543   905  6268 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:37.543   455  6459 D libc    : [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
06-22 07:43:37.543   455  6459 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,06-22 07:43:37.603   905  1079 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
06-22 07:43:37.603   905  1005 D Tethering: Tethering got CONNECTIVITY_ACTION
06-22 07:43:37.603   905   905 I AlarmManager: [AlarmQueuing] connectivity wifi: true
,06-22 07:43:37.603   905  1005 D Tethering: TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
,06-22 07:43:37.603   905   905 D htcCheckinService: ConnectivityReceiver - onReceive() - original mNetworkConnected = false,
06-22 07:43:37.613   905  6268 D HtcWifiWanDetect: Find DNS Address www.htc.com/104.81.130.175
06-22 07:43:37.613   905   905 D htcCheckinService: ConnectivityReceiver - onReceive() - new mNetworkConnected = true
06-22 07:43:37.613   455  6459 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:37.613   455  6459 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
06-22 07:43:37.613   905  6268 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:37.613  5914  5914 D BluetoothAdapter: 800157567: getState(). Returning 12,
06-22 07:43:37.613   905  1446 D AlarmManager:  invoke hookTimeZoneToRadio(true, 3600)
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
06-22 07:43:37.613  5914  5914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-22 07:43:37.613   905  1446 V AlarmManager: hookRadio - sign: true offset:3600,
06-22 07:43:37.613  5914  5914 D BluetoothAdapter: 800157567: getState(). Returning 12
06-22 07:43:37.613  5914  5914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-22 07:43:37.633  1493  1493 I ConnectivityHelper: [onReceive] WIFI(1): CONNECTED,
06-22 07:43:37.633   905   999 D PMS     : acquireWL(1be452f4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:37.633   905  1446 D AlarmManager: setTime() is invoked. time=1466574220541,
,06-22 07:43:37.643   482   861 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 39,
,06-22 07:43:37.643   905  1000 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6462 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:43:40.541   905  2090 D PMS     : acquireWL(e35da1d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:40.551   482   861 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 39
06-22 07:43:40.551  1123  1302 I IntentController: receive(android.intent.action.TIME_SET,4,false)
06-22 07:43:40.561   905  1637 D PMS     : acquireWL(4d0e492): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 6395 10010 null
06-22 07:43:40.561  6395  6468 D AlertReceiver: beginStartingService
06-22 07:43:40.571   905  1528 D PMS     : acquireWL(3f6daa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:40.571  1493  1493 I FeedActionBar: updateLastUpdatedTime(in String) LAST UPDATED 7:42
06-22 07:43:40.571  1199  1305 D DotMatrix: [EventService] EVENT_RESET_THEME_TIMESTAMP
,06-22 07:43:40.601  1123  1123 I Clock   : updateClock:07:43 Europe/Brussels,
,06-22 07:43:40.601  1123  1123 I Clock   : updateClock:07:43 Europe/Brussels
06-22 07:43:40.601   905  1584 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=6495 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:43:40.601  1123  1123 I Clock   : updateClock:07:43 Europe/Brussels
,06-22 07:43:40.601   905  1495 D PMS     : acquireWL(398c1dbf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10186 com.google.android.youtube}
,06-22 07:43:40.610  1123  2217 D WeatherUtility: Weather sync is On
,06-22 07:43:40.620  6125  6493 D WeatherUtility: Weather sync is On,
,06-22 07:43:40.620  1199  1305 D DotMatrix: [EventService] isTheSameDay:false,timestamp is early than today:true,
,06-22 07:43:40.631   905  1528 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6513 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:43:40.641   905  1586 D PMS     : releaseWL(e35da1d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:40.641   905   999 D PMS     : acquireWL(32730c8c): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10025}
,06-22 07:43:40.661  6495  6495 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:43:40.671  6462  6462 I MusicStore: Database version: 120,
,06-22 07:43:40.721   905   999 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.auth.api.credentials.sync.CredentialSyncService: pid=6533 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,06-22 07:43:40.721   905   999 D PMS     : acquireWL(368a6578): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10025}
,06-22 07:43:40.721  1687  1687 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-22 07:43:40.731  6395  6490 D HtcAlertService: start to updateAlertNotification!
,06-22 07:43:40.741   905   999 D PMS     : releaseWL(368a6578): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025},
,06-22 07:43:40.761   905   999 D PMS     : acquireWL(337d93c1): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10025},
,06-22 07:43:40.761   905   999 D PMS     : releaseWL(1be452f4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:40.761  1123  1302 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
06-22 07:43:40.761   905   999 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-22 07:43:40.761   905   999 D PMS     : acquireWL(3b8613f2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,06-22 07:43:40.761   905   999 D PMS     : acquireWL(11566a43): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:40.761   905   999 D PMS     : releaseWL(11566a43): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
06-22 07:43:40.761   905   999 D GpsLocationProvider: [handleMessage] UPDATE_NETWORK_STATE
,06-22 07:43:40.761   905   999 D GpsLocationProvider: updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,06-22 07:43:40.801   905  1281 I art     : Explicit concurrent mark sweep GC freed 42143(2MB) AllocSpace objects, 5(828KB) LOS objects, 33% free, 17MB/25MB, paused 1.144ms total 82.160ms,
06-22 07:43:40.801   905   920 D PMS     : acquireWL(309ff9f9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 6495 10072 null
06-22 07:43:40.811  1123  1123 D PhoneStatusBar: addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020652 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
06-22 07:43:40.821   905  1639 D PMS     : acquireWL(236b679f): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 6495 10072 null
06-22 07:43:40.821   905  1585 D PMS     : releaseWL(309ff9f9): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
06-22 07:43:40.821  6533  6533 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:43:40.821  6533  6533 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:40.841  6533  6533 I MultiDex: VM with version 2.1.0 has multidex support,
06-22 07:43:40.841  6533  6533 I MultiDex: install
06-22 07:43:40.841  6533  6533 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-22 07:43:40.861   905  1639 I ActivityManager: Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=6564 uid=10096 gids={50096, 9997, 1028} abi=armeabi-v7a,
,06-22 07:43:40.891  6495  6562 D TodoTaskshortcut: update TASK shortcut>,
06-22 07:43:40.891  6513  6563 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfofornet-, err=8,
06-22 07:43:40.901  6513  6563 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
06-22 07:43:40.951  6435  6435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2712 
06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:40.981   905  1282 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfo_proxy+,
,06-22 07:43:40.981   905  1065 D PMS     : acquireWL(3dac06a1): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{1000},
06-22 07:43:40.901  1687  6553 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:40.981   905  1065 V AlarmManager: sending alarm PendingIntent{2dca10c6: PendingIntentRecord{f49a887 com.google.android.gms broadcastIntent}}, i=ALARM_WAKEUP_LOCATOR, t=2, cnt=1, w=104910, Int=0
06-22 07:43:40.911   455  6590 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:40.991   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
06-22 07:43:40.911   455  6590 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:40.991   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:40.921  1687  6586 E SQLiteLog: (283) recovered 36 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
06-22 07:43:40.941   455  6590 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:40.941   455  6590 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:40.941  1687  6553 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:40.951  6564  6564 I WorldClock.Global: isHEPDevice = true
06-22 07:43:40.951  6513  6563 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
06-22 07:43:40.951  6564  6564 I WorldClock.Global: isHEPDevice = true
,06-22 07:43:40.961  6564  6592 I WorldClock.AlarmUtils: Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 07:12:55 CET 292278994)
06-22 07:43:40.991  6564  6592 I WorldClock.AlarmUtils: Cancel any alarm from alarm manager
06-22 07:43:40.991  6564  6592 I WorldClock.AlarmUtils: broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
06-22 07:43:40.991  1123  1302 I IntentController: receive(android.intent.action.ALARM_CHANGED,1,false)
06-22 07:43:40.991   905   999 E GpsLocationProvider: No APN found to select.
06-22 07:43:41.001  6462  6462 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-22 07:43:41.011  6533  6533 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
06-22 07:43:41.021  6513  6563 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:43:41.021  6513  6563 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:41.041  6596  6596 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1466574221053,
,06-22 07:43:41.051   905   999 D GpsLocationProvider: [handleMessage] INJECT_NTP_TIME,
,06-22 07:43:41.051  6395  6490 D HtcAlertService: No fired or scheduled alerts,
,06-22 07:43:41.051  6395  6490 D HtcAlertUtils: -- cancelReminderNotification --
,06-22 07:43:41.061   482  6615 E QC-time-services: Daemon:Update to modem bit set,
06-22 07:43:41.061  6596  6596 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,06-22 07:43:41.061  6395  6490 D HtcAlertUtils: broadcastExistReminder!,
06-22 07:43:41.061   482   863 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-22 07:43:41.071  6533  6533 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:43:41.071  6533  6533 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11b5b00e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:43:41.071  6533  6533 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:41.091   905  6617 D GpsLocationProvider: NTP server returned: 1466574217613 (Wed Jun 22 07:43:37 CEST 2016) reference: 101497 certainty: 12 system time offset: -3482,
06-22 07:43:41.091   905   999 D GpsLocationProvider: [handleMessage] INJECT_NTP_TIME_FINISHED
06-22 07:43:41.091   905   999 D PMS     : releaseWL(3b8613f2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,06-22 07:43:41.091   905  1448 D GpsLocationProvider: handleReportAgpsStatus with type = 12090status = 30767ipaddr = [B@1384b720
06-22 07:43:41.091   905  1448 D PMS     : acquireWL(20de8d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
06-22 07:43:41.091   905  1448 D GpsLocationProvider: Received Unknown AGPS status: 30767
06-22 07:43:41.091   905  1448 D GpsLocationProvider: xtraDownloadRequest
06-22 07:43:41.091   905   999 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA
06-22 07:43:41.091   905   999 D PMS     : acquireWL(db4729e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 905 1000 null
06-22 07:43:41.091   905   999 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
06-22 07:43:41.091   905   999 D PMS     : releaseWL(20de8d9): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,06-22 07:43:41.111  1687  6553 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:43:41.111   905  1282 D PMS     : releaseWL(4d0e492): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
06-22 07:43:41.111  1687  6553 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:41.111  1687  6553 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
06-22 07:43:41.111  1687  6553 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:41.111  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:43:41.121  6395  6490 W AlertReceiver: stopSelfResult true,
,06-22 07:43:41.121   905  1708 D Process : killProcessQuiet, pid=5388,
06-22 07:43:41.121   905  1708 I ActivityManager: Killing 5388:com.google.android.apps.plus/u0a176 (adj 15): empty #17
06-22 07:43:41.121   905  1708 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:41.131   905  6620 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 4,
06-22 07:43:41.131   905  6620 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:41.141   905  1088 I ActivityManager: Recipient 5388,
06-22 07:43:41.141   905  6620 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 1024
06-22 07:43:41.141   905  6620 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:41.141   905  6620 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:41.141   905  6620 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:41.141   455  6627 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 1024
06-22 07:43:41.141   455  6627 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:41.141  6495  6560 I TodoTaskNotifyService: Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,06-22 07:43:41.151   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
06-22 07:43:41.151   363   408 W Vold    : Returning OperationFailed - no handler for errno 0,
06-22 07:43:41.151  6462  6462 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,06-22 07:43:41.161   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
06-22 07:43:41.161   363   408 W Vold    : Returning OperationFailed - no handler for errno 0,
06-22 07:43:41.161  6462  6462 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,06-22 07:43:41.161  6513  6624 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:43:41.161  6513  6624 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:41.211   455  6627 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
06-22 07:43:41.211   455  6627 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:41.211   905  6620 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:41.211   905  6620 D libc    : [NET] android_getaddrinfofornet+,hn 12(0x35322e38342e31),sn(),hints(known),family 0,flags 4
06-22 07:43:41.211   905  6620 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:43:41.241   905  1088 D Process : killProcessQuiet, pid=5388
06-22 07:43:41.241   905  1088 W libprocessgroup: failed to open /acct/uid_10176/pid_5388/cgroup.procs: No such file or directory
06-22 07:43:41.241   905  1088 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:41.251  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,06-22 07:43:41.271   905  6620 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data
,06-22 07:43:41.281  6462  6462 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
06-22 07:43:41.281  6462  6462 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:41.301   905   999 D PMS     : acquireWL(242e5502): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null,
,06-22 07:43:41.301  6513  6513 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,06-22 07:43:41.311   905   999 D PMS     : releaseWL(242e5502): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
06-22 07:43:41.311  6495  6560 I TodoTaskNotifyService: Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
06-22 07:43:41.321  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,06-22 07:43:41.321  6513  6513 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
,06-22 07:43:41.321  6513  6513 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:43:41.331   905  1636 D PMS     : releaseWL(236b679f): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,06-22 07:43:41.331   905  1076 E WifiStateMachine: handleMessage: E msg.what=131155
,06-22 07:43:41.331   905  1585 I ActivityManager: Killing 5484:com.android.defcontainer/u0a15 (adj 15): empty #17
06-22 07:43:41.331   905  1076 E WifiStateMachine: processMsg: ConnectedState
06-22 07:43:41.331   905  1076 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4443] from screen [on:0 period:1990373403] gl hn u24 rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:43:41.331   905  1585 D Process : killProcessQuiet, pid=5484
06-22 07:43:41.331   905  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-22 07:43:41.331   905  1076 E WifiStateMachine: processMsg: L2ConnectedState
06-22 07:43:41.331   905  1076 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-51 f=2447 sc=60 link=150 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1990373404] gl hn u24 rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
06-22 07:43:41.331   905  1076 E WifiStateMachine: handleMessage: X
,06-22 07:43:41.331  6495  6560 W NotifyReceiver: stopSelfResult true
,06-22 07:43:41.341  6462  6462 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-22 07:43:41.341  6533  6547 W art     : Suspending all threads took: 33.479ms
,06-22 07:43:41.351   905   920 I ActivityManager: Recipient 5484
,06-22 07:43:41.351   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
06-22 07:43:41.351  6513  6513 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,06-22 07:43:41.351   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:41.361  6533  6547 I art     : Background sticky concurrent mark sweep GC freed 27568(1384KB) AllocSpace objects, 4(64KB) LOS objects, 23% free, 3MB/4MB, paused 47.980ms total 101.614ms,
,06-22 07:43:41.411  6462  6462 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:43:41.411  1123  2217 D WeatherUtility: Weather sync is On
06-22 07:43:41.411  6533  6547 W art     : Suspending all threads took: 5.147ms
06-22 07:43:41.411  6462  6462 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c345d41: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:43:41.411  6462  6462 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:43:41.411  6462  6462 D AndroidMusic: GMSCore installation verified
06-22 07:43:41.411  6533  6547 I art     : Background sticky concurrent mark sweep GC freed 1167(146KB) AllocSpace objects, 0(0B) LOS objects, 11% free, 3MB/4MB, paused 6.619ms total 15.339ms
,06-22 07:43:41.441  6649  6649 E cutils-trace: Error opening trace file: No such file or directory (2)
06-22 07:43:41.441  6649  6649 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads100568600.jar --oat-fd=42 --oat-location=/data/data/com.google.android.youtube/cache/ads100568600.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:43:41.461   905   920 D Process : killProcessQuiet, pid=5484,
06-22 07:43:41.461   905   920 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:41.461   905   920 W libprocessgroup: failed to open /acct/uid_10015/pid_5484/cgroup.procs: No such file or directory
,06-22 07:43:41.481   905  1495 D PMS     : acquireWL(88eb205): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 07:43:41.481  6462  6462 I ConfigStore: Config Database version: 1
,06-22 07:43:41.501  1123  1123 D HtcUPManager: HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,06-22 07:43:41.521  6125  6493 D WeatherUtility: Weather sync is On
,06-22 07:43:41.521  6125  6493 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-22 07:43:41.531  6649  6649 I dex2oat : dex2oat took 87.383ms (threads: 4)
,06-22 07:43:41.561  6125  6493 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,06-22 07:43:41.571  6513  6513 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
06-22 07:43:41.571   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
06-22 07:43:41.571   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:41.581  6513  6513 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files,
06-22 07:43:41.581   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/,
06-22 07:43:41.581  6513  6513 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
06-22 07:43:41.581   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:41.581   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
06-22 07:43:41.581   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:41.581   905  1088 D PMS     : releaseWL(3209e886): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,06-22 07:43:41.591  6513  6513 W InstanceID/Rpc: Found 10025
06-22 07:43:41.591  1687  1706 I art     : Explicit concurrent mark sweep GC freed 20857(1142KB) AllocSpace objects, 4(87KB) LOS objects, 46% free, 4MB/8MB, paused 2.174ms total 37.123ms,
,06-22 07:43:41.611   905   921 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6462, uid=10167, userID:0,
,06-22 07:43:41.611   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
06-22 07:43:41.611   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:41.611  6513  6513 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,06-22 07:43:41.621   905  1639 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
,06-22 07:43:41.621   905  1639 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:41.621   905  1639 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:41.621   905  1639 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:41.621   905  1639 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:41.621   905  1639 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:41.631  1687  6553 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,06-22 07:43:41.651   905  1282 D PMS     : releaseWL(3f6daa60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:41.651   905  1584 D PMS     : acquireWL(1a847c62): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.661   905  1528 D MediaRouterService: Client com.google.android.music (pid 6462): Registered
,06-22 07:43:41.671  6533  6689 W DriveInitializer: Background init thread started
06-22 07:43:41.671   905  1586 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:41.671   905  1586 D WifiDisplayAdapter:     Client/Owner: Client
,06-22 07:43:41.671   905  1586 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:41.671   905  1586 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:41.671   905  1586 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:41.671   905  1586 D WifiDisplayAdapter:     IP Address: }
06-22 07:43:41.671   905   999 D PMS     : acquireWL(854bd9d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:41.681  6462  6462 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-22 07:43:41.681  6462  6462 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-22 07:43:41.691   905  1636 D PMS     : acquireWL(2e7e53f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:41.691  1493  1493 I RemoteViews: reapply : com.htc.widget.weatherclock 5 21
,06-22 07:43:41.701   905  1495 D PMS     : acquireWL(14bf0355): PARTIAL_WAKE_LOCK  Checkin Service 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:41.701   905  1281 D PMS     : releaseWL(2e7e53f): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.711  6462  6462 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-22 07:43:41.711   905  1448 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0
06-22 07:43:41.711   905  1266 D PMS     : releaseWL(14bf0355): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:41.711   905  1448 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
06-22 07:43:41.711   905  6620 D PMS     : acquireWL(3116816a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
06-22 07:43:41.711   905  6620 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
06-22 07:43:41.721   905  6620 D PMS     : releaseWL(db4729e): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
,06-22 07:43:41.741   905   999 D PMS     : releaseWL(854bd9d): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:41.741  6462  6462 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true,
,06-22 07:43:41.741   905   999 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
06-22 07:43:41.741   905   999 D PMS     : releaseWL(3116816a): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,06-22 07:43:41.741   905  1528 D PMS     : releaseWL(1a847c62): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.741   905  1088 D PMS     : acquireWL(1f5d6a0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.751   905   920 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6462, uid=10167, userID:0
,06-22 07:43:41.761  6533  6703 W DriveInitializer: Awaiting to be initialized,
,06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfo_proxy+,
06-22 07:43:41.761  6513  6697 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:41.761   455  6705 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:41.761   455  6705 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:41.771   905  1281 I ActivityManager: Start proc com.fitbit.FitbitMobile for broadcast com.fitbit.FitbitMobile/.NetworkStateReceiver: pid=6706 uid=10023 gids={50023, 9997, 3002, 3001, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:41.781  6533  6689 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files,
06-22 07:43:41.781   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
,06-22 07:43:41.781   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:41.791  6462  6462 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-22 07:43:41.801   905  1584 D PMS     : acquireWL(310e0628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10186 com.google.android.youtube}
,06-22 07:43:41.801   455  6705 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:41.801   455  6705 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:41.801  6513  6697 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:41.811  6513  6697 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
,06-22 07:43:41.811  6513  6697 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:41.811  6462  6462 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,06-22 07:43:41.811   905  1708 D PMS     : releaseWL(1f5d6a0e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.811   905  1088 D PMS     : releaseWL(310e0628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10186 com.google.android.youtube}
,06-22 07:43:41.811   905  1639 D PMS     : acquireWL(3f3ab172): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:41.821   905  1528 D PMS     : acquireWL(3e3a79c3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 6533 10025 null
,06-22 07:43:41.821   905  1088 D PMS     : releaseWL(3f3ab172): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.821   905  1636 D PMS     : acquireWL(3fd17240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.841  1687  2089 I GLSActivity: [ac] getting account id
,06-22 07:43:41.851   905  1088 D PMS     : acquireWL(d0f5e3b): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:41.851  6533  6689 W DriveInitializer: Background init thread ended
,06-22 07:43:41.851   905  1585 D PMS     : releaseWL(3fd17240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:41.851   905   920 D PMS     : acquireWL(1ae34958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.861   905  1636 D PMS     : releaseWL(1ae34958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:41.861   905  1708 D PMS     : releaseWL(3e3a79c3): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
06-22 07:43:41.861   905   920 D PMS     : releaseWL(d0f5e3b): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:41.871   905  1281 D Process : killProcessQuiet, pid=5727,
06-22 07:43:41.871   905  1281 I ActivityManager: Killing 5727:com.google.android.talk/u0a120 (adj 15): empty #17,
06-22 07:43:41.871   905  1281 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:41.891   905  1088 I ActivityManager: Recipient 5727
,06-22 07:43:41.971  6513  6697 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:43:41.971  6513  6697 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:42.011   905  1088 D Process : killProcessQuiet, pid=5727,
06-22 07:43:42.011   905  1088 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:42.011   905  1088 W libprocessgroup: failed to open /acct/uid_10120/pid_5727/cgroup.procs: No such file or directory
,06-22 07:43:42.021  1687  2089 I GLSUser : [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,06-22 07:43:42.051   905   999 D PMS     : acquireWL(36be5b22): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null,
,06-22 07:43:42.061   905   999 D PMS     : releaseWL(337d93c1): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025}
,06-22 07:43:42.081   905   999 D PMS     : acquireWL(2d1d59b3): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10025}
,06-22 07:43:42.081   905   999 D PMS     : releaseWL(36be5b22): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:42.121  6513  6679 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:42.131   455  6742 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
,06-22 07:43:42.131   455  6742 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:42.131   455  6742 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:42.131   455  6742 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:42.131  6513  6679 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:42.131  6513  6679 D libc    : [NET] android_getaddrinfofornet+,hn 14(0x3137322e323137),sn(),hints(known),family 0,flags 4
06-22 07:43:42.131  6513  6679 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:43:42.151   905   905 I art     : Explicit concurrent mark sweep GC freed 21192(1169KB) AllocSpace objects, 4(367KB) LOS objects, 33% free, 17MB/25MB, paused 1.240ms total 66.892ms
,06-22 07:43:42.151   905   999 D PMS     : acquireWL(9764e9c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:42.151   905   999 D PMS     : releaseWL(9764e9c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:42.151  6706  6721 W art     : Suspending all threads took: 5.554ms
,06-22 07:43:42.161   905   999 D PMS     : acquireWL(3bfb30a5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:42.161   905   999 D PMS     : releaseWL(32730c8c): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10025}
,06-22 07:43:42.161   905   999 D PMS     : releaseWL(3bfb30a5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:42.171  6513  6679 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,06-22 07:43:42.171  6513  6679 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:42.181   905   999 D PMS     : acquireWL(17642c7a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:42.181   905   999 D PMS     : releaseWL(2d1d59b3): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10025}
,06-22 07:43:42.181  1123  1302 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,06-22 07:43:42.181   905   999 D PMS     : releaseWL(17642c7a): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:42.201   905  1005 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
,06-22 07:43:42.201   905  1088 W System.err: java.lang.Throwable: stack dump
06-22 07:43:42.201   905  1088 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-22 07:43:42.201   905  1088 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-22 07:43:42.201   905  1088 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-22 07:43:42.201   905  1088 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:42.201   905  1005 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16bf0459:true
,06-22 07:43:42.271  6706  6706 D HockeyApp: Current handler class = com.android.internal.os.RuntimeInit$UncaughtHandler
,06-22 07:43:42.271   905  1281 I ActivityManager: Killing 5752:com.htc.sense.mms/u0a67 (adj 15): empty #17
06-22 07:43:42.271   905  1281 D Process : killProcessQuiet, pid=5752
,06-22 07:43:42.271   905  1281 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:42.281   905  1495 I ActivityManager: Recipient 5752,
,06-22 07:43:42.411   905  1495 D Process : killProcessQuiet, pid=5752,
06-22 07:43:42.411   905  1495 W libprocessgroup: failed to open /acct/uid_10067/pid_5752/cgroup.procs: No such file or directory
06-22 07:43:42.411   905  1495 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:42.411  1380  6755 D AutoSetting: receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,06-22 07:43:42.421   905   905 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3,
,06-22 07:43:42.431   905  1708 I ActivityManager: Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.OneTimeOnConnectedReceiver: pid=6757 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,06-22 07:43:42.431   905  1584 D PMS     : releaseWL(398c1dbf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10186 com.google.android.youtube},
06-22 07:43:42.441   905  1585 D Process : killProcessQuiet, pid=5977
06-22 07:43:42.431   905  1586 D PMS     : acquireWL(34528d15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:42.441   905  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-22 07:43:42.441   905  1585 I ActivityManager: Killing 5977:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
,06-22 07:43:42.441   467   467 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 190us total 13.581ms
,06-22 07:43:42.451   905  1637 D PMS     : releaseWL(34528d15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
06-22 07:43:42.451   905  1088 D PMS     : acquireWL(2160a82a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:42.461   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 189us total 12.760ms
,06-22 07:43:42.461   905  1584 I ActivityManager: Recipient 5977
,06-22 07:43:42.471   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 184us total 12.705ms,
,06-22 07:43:42.621   905  1584 D Process : killProcessQuiet, pid=5977,
06-22 07:43:42.621  1380  1380 D AutoSetting: service - onCreate()
06-22 07:43:42.621   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:42.621   905  1584 W libprocessgroup: failed to open /acct/uid_10079/pid_5977/cgroup.procs: No such file or directory
,06-22 07:43:42.621   905  1282 D PMS     : releaseWL(2160a82a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:42.621   905  1639 D PMS     : acquireWL(283e53b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:42.621  1380  1380 D AutoSetting: service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,06-22 07:43:42.621  1380  1380 D AutoSetting: service - onStartCommand() screen is off, don't request location
,06-22 07:43:42.631   905  1708 D LocationManagerService: request 25bfd6aa passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10054),
06-22 07:43:42.631   905  1708 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,06-22 07:43:42.631  1380  1380 D AutoSetting: Util - check NLP state, Allowned:true, Enabled:true
,06-22 07:43:42.641  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-22 07:43:42.641  5914  5970 I jxcore-log: ,
,06-22 07:43:42.651   905  1584 D PMS     : acquireWL(3460f364): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10186 com.google.android.youtube}
,06-22 07:43:42.651  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-22 07:43:42.651  5914  5970 I jxcore-log: ,
,06-22 07:43:42.661   905  1528 D PMS     : acquireWL(2f521282): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:42.661  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
06-22 07:43:42.661  5914  5970 I jxcore-log: 
,06-22 07:43:42.671   905   920 D PMS     : releaseWL(283e53b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:42.681  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:42.701  1687  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement,
06-22 07:43:42.701  1687  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:42.701  1687  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:42.701  1687  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:42.701  1687  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:42.711  6533  6778 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication,
,06-22 07:43:42.711  6779  6779 E cutils-trace: Error opening trace file: No such file or directory (2),
06-22 07:43:42.711  6779  6779 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:43:42.721  6533  6778 W InstanceID/Rpc: Found 10025,
,06-22 07:43:42.721   905  1585 D PMS     : releaseWL(2f521282): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
06-22 07:43:42.721   905  2090 D PMS     : acquireWL(1bc0afa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:42.731   905  1495 D PMS     : releaseWL(1bc0afa6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:42.741   905  1586 D PMS     : releaseWL(3460f364): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10186 com.google.android.youtube},
06-22 07:43:42.741   905  1637 D PMS     : acquireWL(6f38de7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:42.751   905  1282 I ActivityManager: Killing 6070:com.htc.widget.hmsproc3/u0a36 (adj 15): empty #17,
06-22 07:43:42.751   905  1282 D Process : killProcessQuiet, pid=6070
06-22 07:43:42.751   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:42.761   905  1585 I ActivityManager: Recipient 6070,
,06-22 07:43:42.761   905  1088 D PMS     : releaseWL(6f38de7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:42.761   905  1586 D PMS     : acquireWL(1299fd94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:42.821  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
06-22 07:43:42.821  5914  5970 I jxcore-log: 
,06-22 07:43:42.871   905  1585 D Process : killProcessQuiet, pid=6070,
06-22 07:43:42.871   905  1585 W libprocessgroup: failed to open /acct/uid_10036/pid_6070/cgroup.procs: No such file or directory
,06-22 07:43:42.871   905  1585 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:42.871   905  1266 D PMS     : releaseWL(1299fd94): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:42.911  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-22 07:43:42.911  5914  5970 I jxcore-log: 
,06-22 07:43:42.961  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-22 07:43:42.961  5914  5970 I jxcore-log: 
,06-22 07:43:42.961  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-22 07:43:42.961  5914  5970 I jxcore-log: 
,06-22 07:43:43.151  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,06-22 07:43:43.151  5914  5970 I jxcore-log: 
,06-22 07:43:43.170  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-22 07:43:43.170  5914  5970 I jxcore-log: 
,06-22 07:43:43.180  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-22 07:43:43.180  5914  5970 I jxcore-log: 
,06-22 07:43:43.180  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-22 07:43:43.180  5914  5970 I jxcore-log: 
,06-22 07:43:43.201  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-22 07:43:43.201  5914  5970 I jxcore-log: 
,06-22 07:43:43.221  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-22 07:43:43.221  5914  5970 I jxcore-log: 
,06-22 07:43:43.291   905   905 E WifiDataStallTracker: DATA_MONITOR_POLL false Token 3,
,06-22 07:43:43.301  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
06-22 07:43:43.301  5914  5970 I jxcore-log: 
,06-22 07:43:43.311  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
06-22 07:43:43.311  5914  5970 I jxcore-log: 
,06-22 07:43:43.331  5914  5970 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
06-22 07:43:43.331  5914  5970 I jxcore-log: 
,06-22 07:43:43.341  5914  5970 D BluetoothAdapter: 800157567: getState(). Returning 12,
06-22 07:43:43.341  5914  5970 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-22 07:43:43.341  5914  5970 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-22 07:43:43.341  5914  5970 I jxcore-log: 
,06-22 07:43:43.401  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-22 07:43:43.401  5914  5970 I jxcore-log: 
,06-22 07:43:43.401  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-22 07:43:43.401  5914  5970 I jxcore-log: 
,06-22 07:43:43.401  5914  5970 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-22 07:43:43.401  5914  5970 I jxcore-log: 
,06-22 07:43:43.451  1457  1582 D ContactMessageStore: notify MmsSms
,06-22 07:43:43.451  1457  1582 D AccFlag : sense_version=6.0
06-22 07:43:43.461  1457  1582 D AccFlag : sku_id=99
,06-22 07:43:43.571  1457  1582 D TelephUtils: QUERY for  <hidden uri>  [ com.android.phone ] tid: 71
,06-22 07:43:43.591  6779  6779 I dex2oat : dex2oat took 876.583ms (threads: 4)
,06-22 07:43:43.601  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): VersionName:             1.2.848061
06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): VersionCode:             148001212
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,06-22 07:43:43.611  6757  6757 I PushClient: ApplicationMonitor {1399389e}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,06-22 07:43:43.641   905   921 I PackageManager:  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=2, flag=1, pid=6757, uid=10074, userID:0,
,06-22 07:43:43.651   905  1281 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6786 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a
,06-22 07:43:43.661  6757  6785 I PushClient: OnConnectedHandler {1e5c40aa}: handle(): Try update on network connected.
06-22 07:43:43.661  6757  6785 I PushClient: PnsModel {2d1206d9}: update(): Update registration caused by: android.net.conn.CONNECTIVITY_CHANGE
,06-22 07:43:43.661  6757  6785 I PushClient: PnsConfigModel {88f7e50}: <init>(): Use dm-client for provisioning.
,06-22 07:43:43.681  6757  6785 W System.err: SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,06-22 07:43:43.681  6757  6785 W System.err: SLF4J: Defaulting to no-operation (NOP) logger implementation
,06-22 07:43:43.681  6757  6785 W System.err: SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,06-22 07:43:43.691  6786  6786 D PhoneMonitor: Register our PhoneStateListener
,06-22 07:43:43.701  6757  6785 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,06-22 07:43:43.701  6786  6786 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,06-22 07:43:43.701  6786  6786 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,06-22 07:43:43.701  6786  6786 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,06-22 07:43:43.711  6786  6786 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,06-22 07:43:43.731   905  2090 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6806 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,06-22 07:43:43.731   905  1000 D Process : killProcessQuiet, pid=6206
06-22 07:43:43.731   905  1000 I ActivityManager: Killing 6206:com.htc.android.mail:sync/u0a65 (adj 15): empty #17,
06-22 07:43:43.731   905  1000 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:43.741   905  1282 I ActivityManager: Recipient 6206,
,06-22 07:43:43.761   905  1282 D Process : killProcessQuiet, pid=6206
,06-22 07:43:43.761   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:43.761   905  1282 W libprocessgroup: failed to open /acct/uid_10065/pid_6206/cgroup.procs: No such file or directory
,06-22 07:43:43.761   905  1266 D PMS     : acquireWL(3b6a4e56): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:43.761   905   921 D PMS     : acquireWL(3ab2b2ad): PARTIAL_WAKE_LOCK  Checkin Service 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
06-22 07:43:43.761   905  1584 D PMS     : releaseWL(3b6a4e56): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:43.781  6533  6823 I CheckinService: Disabling old GoogleServicesFramework version,
06-22 07:43:43.781   905  1637 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:43.781   905  1281 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:43.781   905  1585 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:43.791  6533  6824 I CheckinService: Checking schedule, now: 1466574223794 next: 1466512228042,
06-22 07:43:43.791  6533  6824 I CheckinService: active receiver: enabled
06-22 07:43:43.791   905  1528 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:43.791  6533  6824 I CheckinService: Preparing to send checkin request
06-22 07:43:43.791  6533  6824 I EventLogService: Accumulating logs since 1466573923283
,06-22 07:43:43.801  6806  6806 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=6806 dbg=false s=true,
,06-22 07:43:43.801  6806  6822 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,06-22 07:43:43.801  6806  6822 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10074) packages=[com.htc.cs.pns]
06-22 07:43:43.801  6806  6806 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,06-22 07:43:43.811  6806  6827 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,06-22 07:43:43.811  6806  6806 I DeviceManagement: WorkflowService: Starting workflow service,
,06-22 07:43:43.811  6806  6829 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@1ae8d20] args=[Bundle[mParcelledData.dataSize=720]]
,06-22 07:43:43.821  6806  6829 I DeviceManagement: NetworkChangeWorkflow: ==================================================,
06-22 07:43:43.821  6806  6829 I DeviceManagement: NetworkChangeWorkflow: NetworkChange: networkAvailable=true
06-22 07:43:43.821  6806  6829 I DeviceManagement: NetworkChangeWorkflow: ==================================================
,06-22 07:43:43.831  6806  6829 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,06-22 07:43:43.841   905  1637 I ActivityManager: Start proc com.twitter.android for broadcast com.twitter.android/.client.AppBroadcastReceiver: pid=6830 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:43.851  6806  6829 I DeviceManagement: SessionStateController: Checking invariants...
,06-22 07:43:43.961  6806  6829 I DeviceManagement: BackgroundController: Invariants are unchanged.
,06-22 07:43:43.961  6806  6848 I DeviceManagement: SessionStateController: Checking invariants...
,06-22 07:43:44.021  6533  6824 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1,
,06-22 07:43:44.031  6806  6848 I DeviceManagement: ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm,
,06-22 07:43:44.031  6806  6848 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,06-22 07:43:44.031  6806  6829 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
06-22 07:43:44.031  6806  6829 I DeviceManagement: Perf: *** Cache update - start...
,06-22 07:43:44.031  6806  6829 I DeviceManagement: Perf: *** Enabled app cache update - start...
06-22 07:43:44.031  6806  6829 I DeviceManagement: EnabledAppController: *** Updating enabled app database...
06-22 07:43:44.031  6806  6829 I DeviceManagement: Perf: *** Enabled app cache update - complete: 1 ms
06-22 07:43:44.031  6806  6829 I DeviceManagement: Perf: *** Config cache update - start...
,06-22 07:43:44.031  6806  6829 I DeviceManagement: ConfigCacheController: *** Updating config cache...,
06-22 07:43:44.031   905  1077 D WifiService: New client listening to asynchronous messages
,06-22 07:43:44.031  6806  6829 I DeviceManagement: ConfigCacheController: *** Device manifest update is pending...
06-22 07:43:44.041   905   905 E WifiTrafficPoller: ADD_CLIENT: 9
06-22 07:43:44.041  6806  6829 I DeviceManagement: ConfigCacheController: *** Sending device manifest...,
06-22 07:43:44.041   905  1528 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
06-22 07:43:44.041  6533  6824 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings,
,06-22 07:43:44.051  6830  6830 I Crashlytics: Initializing Crashlytics 1.1.13.10,
,06-22 07:43:44.121  1687  2089 I art     : Explicit concurrent mark sweep GC freed 13967(692KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 775us total 50.539ms
,06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 4,
06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 1024
,06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:44.151  6830  6853 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:44.151   455  6858 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x73657474696e67),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.151   455  6858 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:44.171   905  1266 D Process : killProcessQuiet, pid=5012
06-22 07:43:44.171   905  1266 I ActivityManager: Killing 5012:com.htc.musicenhancer/u0a51 (adj 15): empty #17
06-22 07:43:44.171   905  1266 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:44.171   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/
,06-22 07:43:44.171   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:44.171  6830  6830 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
,06-22 07:43:44.181   905  1282 I ActivityManager: Recipient 5012
,06-22 07:43:44.191   455  6858 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:44.191   455  6858 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
06-22 07:43:44.191  6830  6853 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:44.211  6806  6829 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,06-22 07:43:44.211  6806  6829 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,06-22 07:43:44.241   905  1282 D Process : killProcessQuiet, pid=5012
06-22 07:43:44.241   905  1282 W libprocessgroup: failed to open /acct/uid_10051/pid_5012/cgroup.procs: No such file or directory
06-22 07:43:44.241   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:44.261   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.twitter.android/cache/
,06-22 07:43:44.261   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:44.261  6830  6830 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.twitter.android/cache
,06-22 07:43:44.271  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,06-22 07:43:44.271  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:44.271  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:44.271  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:44.271  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:44.281  6806  6829 W System.err: Starting the internal HTTP client
,06-22 07:43:44.301  6533  6824 W CheckinRequestBuilder: awaiting user notification for token,
,06-22 07:43:44.301  1199  1223 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
06-22 07:43:44.301  1199  1223 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,06-22 07:43:44.301  1123  1123 I RemoteViews: reapply : com.google.android.gms 2 40
,06-22 07:43:44.311   905  1584 I PackageManager:  setEnabledSetting(), pkgName=com.twitter.android, clsName=com.twitter.android.samsung.single.TwitterWidgetProvider, state=2, flag=1, pid=6830, uid=10181, userID:0
,06-22 07:43:44.331  6806  6829 I DeviceManagement: DeviceClientResource: Active network...,
06-22 07:43:44.331  6806  6829 I DeviceManagement:   [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-22 07:43:44.341  6806  6829 D BuildInfo: Created new instance: com.htc.cs.lib.hms.BuildInfo@be7f882,
06-22 07:43:44.341  6806  6829 I DeviceManagement: Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,06-22 07:43:44.361  6806  6829 I System.out: isCompatible false,
06-22 07:43:44.361  6806  6829 I System.out: createObjectMapper
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false,
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
06-22 07:43:44.361  6806  6829 I System.out: isCompatible false
,06-22 07:43:44.381   905  2090 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6865 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,06-22 07:43:44.411  6865  6865 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
06-22 07:43:44.411  6865  6865 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:44.421  6865  6865 I MultiDex: VM with version 2.1.0 has multidex support
06-22 07:43:44.421  6865  6865 I MultiDex: install
,06-22 07:43:44.421  6865  6865 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-22 07:43:44.431   905  1528 D PMS     : acquireWL(38ba0b51): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.431   905  1495 D PMS     : releaseWL(38ba0b51): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:44.431  6806  6829 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.431  6806  6829 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,06-22 07:43:44.431  6806  6829 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:44.441  6806  6829 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:44.441   455  6887 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x6c6f63616c686f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.441   455  6887 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4
06-22 07:43:44.441   455  6887 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.441   455  6887 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.441  6806  6829 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:44.441  6865  6865 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 4
,06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:43:44.451  6806  6829 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:44.451   905  1584 D PMS     : acquireWL(e3b74b7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.451   455  6893 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x646d2e68746373),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.451   455  6893 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:44.461  1687  6894 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:44.461   455  6895 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.461   455  6895 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:44.481  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
06-22 07:43:44.481  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:44.481  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:44.481  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:43:44.481  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:44.491   455  6895 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,06-22 07:43:44.501   455  6895 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.501  6865  6865 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-22 07:43:44.501  1687  6894 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:43:44.501  6865  6865 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f6f42ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:43:44.501  6865  6865 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:44.501   905  1637 D Process : killProcessQuiet, pid=5296
06-22 07:43:44.501   905  1637 I ActivityManager: Killing 5296:com.android.settings/1000 (adj 15): empty #17
06-22 07:43:44.501   905  1637 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:44.511   455  6893 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:44.511   455  6893 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.511  6806  6829 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:44.521  6533  6533 I art     : Explicit concurrent mark sweep GC freed 23191(1652KB) AllocSpace objects, 26(416KB) LOS objects, 46% free, 4MB/8MB, paused 536us total 43.836ms
,06-22 07:43:44.531   905  1639 I ActivityManager: Recipient 5296,
06-22 07:43:44.531   905  1077 D WifiService: Client connection lost with reason: 4
,06-22 07:43:44.551  1687  6894 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
06-22 07:43:44.551  1687  6894 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:44.561   905  1636 I art     : Explicit concurrent mark sweep GC freed 17346(889KB) AllocSpace objects, 2(97KB) LOS objects, 33% free, 16MB/25MB, paused 929us total 70.404ms
,06-22 07:43:44.561  6533  6892 I GcmGroups: Failed to subscribe to group.
06-22 07:43:44.561  6533  6892 I GcmGroups: com.google.android.gms.auth.ad: BadAuthentication
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:442)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:365)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:318)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:44.561  6533  6892 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:43:44.581   905  1639 D Process : killProcessQuiet, pid=5296
06-22 07:43:44.581   905  1639 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:44.581   905  1639 W libprocessgroup: failed to open /acct/uid_1000/pid_5296/cgroup.procs: No such file or directory
06-22 07:43:44.581  6018  6018 V BluetoothSapService: onUnbind
,06-22 07:43:44.581  6533  6892 I GcmGroups: Groups upload failed, retrying in 24000:00:00
,06-22 07:43:44.601   905  1282 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:44.621  6533  6899 I iu.SyncManager: SYNC; picasa accounts
,06-22 07:43:44.631  6533  6533 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-22 07:43:44.631  6533  6533 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-22 07:43:44.651  6533  6899 I iu.UploadsManager: num queued entries: 0
,06-22 07:43:44.651  6533  6899 I iu.UploadsManager: num updated entries: 0
,06-22 07:43:44.651  6533  6899 I iu.SyncManager: NEXT; no task
,06-22 07:43:44.651  1687  6894 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
06-22 07:43:44.651  1687  6894 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:44.671   905   921 D PMS     : acquireWL(390ff8e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:44.691   905  1282 D PMS     : acquireWL(286e43af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:44.711  6533  6533 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-22 07:43:44.711   460  1087 I WVCdm   : CdmEngine::OpenSession,
06-22 07:43:44.721   460  1087 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,06-22 07:43:44.721  6533  6533 I Kids    : [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000,
,06-22 07:43:44.731   460  1087 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-22 07:43:44.741   460  1087 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
06-22 07:43:44.741   460  1087 D DrmWidevineDash: Service_Initialize: starts!
06-22 07:43:44.741   460  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-22 07:43:44.741   460  1087 D QSEECOMAPI: : App is not loaded in QSEE
06-22 07:43:44.741   905  1585 D PMS     : acquireWL(321869a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:44.741  1687  6902 D GCM     : Connected,
06-22 07:43:44.751   905  1088 D PMS     : releaseWL(e3b74b7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms},
06-22 07:43:44.751   905  1282 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6905 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-22 07:43:44.761   460  1087 D QSEECOMAPI: : Loaded image: APP id = 3
06-22 07:43:44.751   905  1088 D PMS     : releaseWL(321869a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.761   460  1087 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-22 07:43:44.761   460  1087 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb44c5000
06-22 07:43:44.761   905  1282 D PMS     : acquireWL(1656bcb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.761   460  1087 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb44c5000,
06-22 07:43:44.761  1687  6902 D GCM     : Message class com.google.f.a.a.p
06-22 07:43:44.771   905   921 D PMS     : releaseWL(1656bcb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-22 07:43:44.771   905  1639 D PMS     : acquireWL(2908efa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
06-22 07:43:44.771   460  1087 D DrmWidevineDash: hlos api version =  9
06-22 07:43:44.771   460  1087 D DrmWidevineDash: tz api version =  8
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-22 07:43:44.771   460  1087 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb473e948
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7748078, dataLength=8
06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,06-22 07:43:44.771   460  1087 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76fc2f8, wrapped_rsa_key_length=1280,
06-22 07:43:44.781   460  1087 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-22 07:43:44.781   905   921 D PMS     : releaseWL(390ff8e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:44.781   460  1087 I WVCdm   : CdmEngine::QueryKeyControlInfo
06-22 07:43:44.781   460  1086 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-22 07:43:44.781   460  1086 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-22 07:43:44.781   460  1086 I WVCdm   : CdmEngine::GenerateKeyRequest
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb76b5040, idLength=0xb483e718
06-22 07:43:44.781  6865  6880 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
06-22 07:43:44.781   460  1086 D DrmWidevineDash: hlos api version =  9
06-22 07:43:44.781   460  1086 D DrmWidevineDash: tz api version =  8
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-22 07:43:44.781   460  1086 D WVCdm   : PrepareKeyRequest: nonce=4031701150
06-22 07:43:44.781   460  1086 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7744090
06-22 07:43:44.781   460  1086 D DrmWidevineDash: message_length=1591, signature=0xb76b63a0, signature_length=3028543228
06-22 07:43:44.791  1687  6922 I VacuumService: Vacuum at: now=1466574224798 tag=VacuumService
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:44.801   455  6927 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.801   455  6927 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:44.801   455  6927 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:44.801   455  6927 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.801  6865  6880 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:44.811  1687  6924 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,06-22 07:43:44.811   905  1585 D PMS     : releaseWL(286e43af): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:44.811   905  1088 D PMS     : acquireWL(8daf1fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:44.811  1687  6924 W Uploader: No account for auth token provided,
,06-22 07:43:44.821  6905  6905 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:44.821  1687  6924 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:44.821   455  6928 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
06-22 07:43:44.821   455  6928 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:44.831   905   920 D PMS     : releaseWL(8daf1fd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
06-22 07:43:44.831   905  1636 D PMS     : acquireWL(21a24ef2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:44.841   905  1282 D PMS     : releaseWL(21a24ef2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:44.861   455  6928 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
06-22 07:43:44.861   455  6928 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:44.861  1687  6924 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:44.871  6865  6880 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,06-22 07:43:44.871  6865  6880 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.871  6865  6880 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
06-22 07:43:44.871   460  1086 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
06-22 07:43:44.871  6865  6880 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:44.871   460   460 I WVCdm   : CdmEngine::CloseSession
06-22 07:43:44.871   460   460 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
06-22 07:43:44.871   460   460 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-22 07:43:44.871   460   460 I WVCdm   : L3 Terminate.
06-22 07:43:44.871   460   460 D DrmWidevineDash: OEMCrypto_Terminate: starts!
06-22 07:43:44.871   460   460 D DrmWidevineDash: Service_Uninitialize: starts!
06-22 07:43:44.871   460   460 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-22 07:43:44.871   460   460 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
06-22 07:43:44.871   460   460 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
06-22 07:43:44.871   460   460 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,06-22 07:43:44.931  6905  6936 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,06-22 07:43:44.931  6905  6936 I Babel_SMS: MmsConfig.loadMmsSettings
,06-22 07:43:44.971   905  1528 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6939 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
06-22 07:43:44.971  1687  6924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
06-22 07:43:44.971  1687  6924 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:44.971  1687  6924 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
06-22 07:43:44.971  1687  6924 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:44.971  6806  6829 I DeviceManagement: DMServiceClientResourceController: handleDirectives: [],
06-22 07:43:44.971  6806  6829 I DeviceManagement: ServiceClientResourceController: handleDirectives: []
06-22 07:43:44.971  6806  6829 I DeviceManagement: DeviceClientResourceController: handleDirectives: []
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
,06-22 07:43:44.971  6806  6829 I System.out: createObjectMapper
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
,06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
06-22 07:43:44.971  6806  6829 I System.out: isCompatible false
,06-22 07:43:44.991   905  1708 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6905, uid=10120, userID:0
,06-22 07:43:45.011  6939  6939 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,06-22 07:43:45.021  6939  6939 D MessageFrequencyProvider: onCreate,
,06-22 07:43:45.031  6939  6939 V GetPrviateResource: GetPrviateResource
,06-22 07:43:45.031  1687  6924 W Uploader: No account for auth token provided,
,06-22 07:43:45.031  6939  6954 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
,06-22 07:43:45.031  6939  6939 V GetPrviateResource: GetPrviateResource
,06-22 07:43:45.041  6939  6939 D MessageCustFlag: sense_version=6.0
,06-22 07:43:45.041  6939  6955 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
,06-22 07:43:45.041  6939  6939 D BTAccessoryUtil: createReceiver
,06-22 07:43:45.041  6905  6936 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
06-22 07:43:45.041  6905  6936 I Babel_SMS: MmsConfig.loadFromDatabase
,06-22 07:43:45.041  6939  6939 D BTAccessoryUtil: registerReceiver return intent = null
,06-22 07:43:45.051  6939  6939 D MessageCustFlag: sku_id=99
,06-22 07:43:45.051  6939  6939 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
,06-22 07:43:45.051  6939  6939 W SystemReader: Cannot find qct_8960_interface, use default value instead
,06-22 07:43:45.051  6905  6936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,06-22 07:43:45.051  6905  6936 I Babel_SMS: MmsConfig.loadFromResources
,06-22 07:43:45.051  6905  6936 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,06-22 07:43:45.051  6905  6936 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml
,06-22 07:43:45.061  6905  6905 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,06-22 07:43:45.061  6905  6905 I Babel_Crash: startup - clean,
,06-22 07:43:45.081  6905  6959 I Babel   : deleted: false for 0,
,06-22 07:43:45.081   905  1266 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6905, uid=10120, userID:0
06-22 07:43:45.081   905  1586 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6905, uid=10120, userID:0
,06-22 07:43:45.091   905  2090 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6905, uid=10120, userID:0
,06-22 07:43:45.091   905  1281 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6905, uid=10120, userID:0
,06-22 07:43:45.101   905  1088 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6905, uid=10120, userID:0
,06-22 07:43:45.111  1687  6924 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
06-22 07:43:45.111  1687  6924 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:45.111  1687  6924 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:45.111  1687  6924 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:45.131   905   920 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6961 uid=10169 gids={50169, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:45.141  1687  6924 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:45.151  1687  6924 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
06-22 07:43:45.151  1687  6924 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
,06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
06-22 07:43:45.151  1687  6924 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
06-22 07:43:45.151  1199  3757 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
06-22 07:43:45.151  1199  3757 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
06-22 07:43:45.161  1123  1123 I RemoteViews: reapply : com.google.android.gms 1 40
,06-22 07:43:45.161  6905  6905 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,06-22 07:43:45.191  6905  6905 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,06-22 07:43:45.191  6905  6905 W AudioCapabilities: Unsupported mime audio/qcelp
,06-22 07:43:45.201  6905  6905 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,06-22 07:43:45.201  6905  6905 W AudioCapabilities: Unsupported mime audio/qcelp
,06-22 07:43:45.201  6905  6905 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-22 07:43:45.221  1687  6924 W Uploader: No account for auth token provided
,06-22 07:43:45.231  6905  6905 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-22 07:43:45.241  6905  6905 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,06-22 07:43:45.241  6905  6905 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:43:45.241  6905  6905 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:43:45.251  6905  6905 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-22 07:43:45.261   905  1639 D Process : killProcessQuiet, pid=5319,
06-22 07:43:45.261   905  1639 I ActivityManager: Killing 5319:com.android.vending/u0a75 (adj 15): empty #17
,06-22 07:43:45.261   905  1639 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
,06-22 07:43:45.281  1687  6924 W Uploader: No account for auth token provided
,06-22 07:43:45.291   905   920 I ActivityManager: Recipient 5319
,06-22 07:43:45.331  1687  6924 W Uploader:  no longer exists, so no auth token.
,06-22 07:43:45.391   905   920 D Process : killProcessQuiet, pid=5319,
06-22 07:43:45.391   905   920 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:45.391   905   920 W libprocessgroup: failed to open /acct/uid_10075/pid_5319/cgroup.procs: No such file or directory
,06-22 07:43:45.391  6905  6905 I vclib   : onServiceConnected
,06-22 07:43:45.391  6905  6905 W Babel   : Attempted to change video mute state without an active call.,
,06-22 07:43:45.411   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/,
06-22 07:43:45.411   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:45.411  6961  6984 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
06-22 07:43:45.411  6905  6980 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
06-22 07:43:45.411  6905  6980 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:45.411  6905  6980 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
06-22 07:43:45.411  6905  6980 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:45.411  6905  6980 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:43:45.411   460   460 I WVCdm   : CdmEngine::OpenSession
,06-22 07:43:45.421   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
06-22 07:43:45.411   460   460 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
06-22 07:43:45.421   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:45.421   460   460 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
06-22 07:43:45.421  1687  6924 W Uploader: No account for auth token provided
06-22 07:43:45.421  6905  6980 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:45.421   455  6987 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
06-22 07:43:45.421   455  6987 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:45.421  6961  6984 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,06-22 07:43:45.431   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,06-22 07:43:45.431   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:45.431  6961  6988 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,06-22 07:43:45.431   460   460 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,06-22 07:43:45.431  6806  6829 I DeviceManagement: ConfigCacheController: *** Update config cache: updating 9 entries...
06-22 07:43:45.431   460   460 D DrmWidevineDash: Service_Initialize: starts!
06-22 07:43:45.431   460   460 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-22 07:43:45.431   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
06-22 07:43:45.431   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:45.431   460   460 D QSEECOMAPI: : App is not loaded in QSEE
06-22 07:43:45.431  6961  6988 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,06-22 07:43:45.431  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,06-22 07:43:45.431  6961  6961 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-22 07:43:45.431  6961  6961 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-22 07:43:45.431  6961  6961 I GAv4    :   adb logcat -s GAv4
,06-22 07:43:45.441   460   460 D QSEECOMAPI: : Loaded image: APP id = 3
,06-22 07:43:45.441   460   460 D DrmWidevineDash: Service_Initialize: ends! returns 0
,06-22 07:43:45.441   460   460 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4615000
06-22 07:43:45.441   460   460 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4615000
,06-22 07:43:45.441  6961  6961 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
06-22 07:43:45.451   460   460 D DrmWidevineDash: hlos api version =  9
06-22 07:43:45.451   460   460 D DrmWidevineDash: tz api version =  8
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-22 07:43:45.451   460   460 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbea62308
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb771d6b0, dataLength=8
,06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
06-22 07:43:45.451   460   460 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76fc7e8, wrapped_rsa_key_length=1280
,06-22 07:43:45.451   455  6987 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:45.451   455  6987 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:45.451  6905  6980 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:43:45.461   460   460 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-22 07:43:45.461   460   460 I WVCdm   : CdmEngine::QueryKeyControlInfo
06-22 07:43:45.461   460  1062 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-22 07:43:45.461   460  1062 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-22 07:43:45.461   460  1062 I WVCdm   : CdmEngine::GenerateKeyRequest,
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb76b5080, idLength=0xb493e718
06-22 07:43:45.461  6961  6961 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-22 07:43:45.461  6905  6980 I Babel   : connection state changed from UNKNOWN to CONNECTED,
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
06-22 07:43:45.461   460  1062 D DrmWidevineDash: hlos api version =  9
06-22 07:43:45.461   460  1062 D DrmWidevineDash: tz api version =  8
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-22 07:43:45.461   460  1062 D WVCdm   : PrepareKeyRequest: nonce=3161127467
06-22 07:43:45.461   460  1062 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76b4428
06-22 07:43:45.461   460  1062 D DrmWidevineDash: message_length=1622, signature=0xb76b4a88, signature_length=3029591804
,06-22 07:43:45.471   905  1586 D Process : killProcessQuiet, pid=6338
06-22 07:43:45.471   905  1586 I ActivityManager: Killing 6338:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
06-22 07:43:45.471   905  1586 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:45.471  6961  6990 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,06-22 07:43:45.471  1687  6924 W Uploader: No account for auth token provided
,06-22 07:43:45.481   905  1088 I ActivityManager: Recipient 6338
,06-22 07:43:45.481   905  1077 D WifiService: Client connection lost with reason: 4
,06-22 07:43:45.481  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,06-22 07:43:45.501  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,06-22 07:43:45.521  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,06-22 07:43:45.531   905  1088 D Process : killProcessQuiet, pid=6338
,06-22 07:43:45.531   905  1088 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:45.531   905  1088 W libprocessgroup: failed to open /acct/uid_1000/pid_6338/cgroup.procs: No such file or directory
,06-22 07:43:45.531  1687  6924 W Uploader: No account for auth token provided
06-22 07:43:45.541  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, statusCode=0, authCode=0>
,06-22 07:43:45.551   905  1065 V AlarmManager: sending alarm PendingIntent{25ac6a20: PendingIntentRecord{77f1fd9 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=109482, Int=0,
,06-22 07:43:45.561  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.videohub.ui, versionKey=747235e1-123a-48e6-af18-c5967cf0b131, statusCode=0, authCode=0>,
,06-22 07:43:45.561   460  1062 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0,
,06-22 07:43:45.571   460   460 I WVCdm   : CdmEngine::CloseSession
06-22 07:43:45.571   460   460 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,06-22 07:43:45.571   460   460 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-22 07:43:45.571   460   460 I WVCdm   : L3 Terminate.
06-22 07:43:45.571   460   460 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-22 07:43:45.571   460   460 D DrmWidevineDash: Service_Uninitialize: starts!
06-22 07:43:45.571   460   460 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-22 07:43:45.571   460   460 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,06-22 07:43:45.571   460   460 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
06-22 07:43:45.571   460   460 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,06-22 07:43:45.591   905  1637 D PMS     : releaseWL(2908efa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:45.591   905  1281 D PMS     : acquireWL(24503077): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:45.611  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, statusCode=0, authCode=0>,
,06-22 07:43:45.611  7004  7004 E cutils-trace: Error opening trace file: No such file or directory (2)
,06-22 07:43:45.611  7004  7004 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=48 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:43:45.621   905  1281 D PMS     : releaseWL(24503077): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:45.621   905  2090 D PMS     : acquireWL(17f314e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:45.621   905  1708 D PMS     : releaseWL(17f314e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:45.641  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,06-22 07:43:45.661  7004  7004 I dex2oat : dex2oat took 45.285ms (threads: 4)
,06-22 07:43:45.671  6806  6829 I DeviceManagement: ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,06-22 07:43:45.671  6865  6880 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:45.671  6865  6880 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:45.671  6865  6880 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:45.671  6865  6880 I Adreno-EGL: Local Branch: 
06-22 07:43:45.671  6865  6880 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:45.671  6865  6880 I Adreno-EGL: Local Patches: NONE
06-22 07:43:45.671  6865  6880 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:45.701  6961  6961 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000),
,06-22 07:43:45.721  6961  6961 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9654-9655),
06-22 07:43:45.721  6961  6961 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-22 07:43:45.721  6806  6806 I DeviceManagement: ChangeEventReceiver: vvv Receive change event: <ConfigChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, configJson={"bootstrapNameSet":"com.htc.cs","preloadNameSet":"com.htc.cs"}>
,06-22 07:43:45.731  6806  6806 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow] args=[Bundle[{changeEvent=<ConfigChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, configJson={"bootstrapNameSet":"com.htc.cs","preloadNameSet":"com.htc.cs"}>}]]
,06-22 07:43:45.731  6806  6806 I DeviceManagement: ChangeEventReceiver: vvv Receive change event: <AuthorizationChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, authorizationCode=0, authorizationDataJson=null>
,06-22 07:43:45.731  6806  6806 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow] args=[Bundle[{changeEvent=<AuthorizationChangeEvent appID=com.htc.cs.dm, action=ADD, configID=0:0:2013-09-30T10:30:50.606Z, authorizationCode=0, authorizationDataJson=null>}]]
,06-22 07:43:45.731  6806  6829 I DeviceManagement: AlarmController: Scheduling TTL alarm for: 2016.06.23 at 07:43:45.490 CEST (due to: com.htc.launcher)
,06-22 07:43:45.731  6961  6961 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd54247},
06-22 07:43:45.731  6961  6961 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-22 07:43:45.731  6961  6961 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-22 07:43:45.731   905  1708 I PackageManager:  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=6806, uid=10105, userID:0
,06-22 07:43:45.740  6961  6961 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,06-22 07:43:45.740  6961  6961 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:43:45.750  6961  6961 E SysUtils: ApplicationContext is null in ApplicationStatus,
,06-22 07:43:45.750  6806  6829 I DeviceManagement: Perf: *** Config cache update - complete: 1714 ms,
,06-22 07:43:45.750  6806  6829 I DeviceManagement: Perf: *** Cache update - complete: 1717 ms
,06-22 07:43:45.750  6806  6829 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@1ae8d20]
06-22 07:43:45.750  6865  6880 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:45.750  6865  6880 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:45.750  6865  6880 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:45.750  6865  6880 I Adreno-EGL: Local Branch: 
06-22 07:43:45.750  6865  6880 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:45.750  6865  6880 I Adreno-EGL: Local Patches: NONE
06-22 07:43:45.750  6865  6880 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:45.750  6806  6829 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@19f6182e] args=[Bundle[mParcelledData.dataSize=88]],
06-22 07:43:45.750  6806  6829 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
06-22 07:43:45.750  6806  6829 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,06-22 07:43:45.750  6806  7016 I DeviceManagement: SessionStateController: Checking invariants...
,06-22 07:43:45.760  6961  6961 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-22 07:43:45.760  6961  6961 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:43:45.760  6961  6961 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:43:45.770  6961  6961 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:45.770  6961  6961 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:45.770  6961  6961 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:45.770  6961  6961 I Adreno-EGL: Local Branch: 
06-22 07:43:45.770  6961  6961 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:45.770  6961  6961 I Adreno-EGL: Local Patches: NONE
06-22 07:43:45.770  6961  6961 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:45.790  6865  6880 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-22 07:43:45.790  6865  6880 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-22 07:43:45.790  6865  6880 I Adreno-EGL: Build Date: 12/11/14 Thu
06-22 07:43:45.790  6865  6880 I Adreno-EGL: Local Branch: 
06-22 07:43:45.790  6865  6880 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-22 07:43:45.790  6865  6880 I Adreno-EGL: Local Patches: NONE
06-22 07:43:45.790  6865  6880 I Adreno-EGL: Reconstruct Branch: NOTHING
,06-22 07:43:45.810  6806  7016 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
06-22 07:43:45.820  6961  7027 W AudioManagerAndroid: Requires BLUETOOTH permission
06-22 07:43:45.830  6961  6961 I NSApplication: Starting up...
,06-22 07:43:45.870   905  1584 D Process : killProcessQuiet, pid=6366
06-22 07:43:45.870   905  1584 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7032 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
06-22 07:43:45.870   905  1584 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
06-22 07:43:45.870   905  1584 I ActivityManager: Killing 6366:com.htc.mobiledata/u0a48 (adj 15): empty #17
,06-22 07:43:45.880   905  1282 I ActivityManager: Recipient 6366
,06-22 07:43:45.920  6533  6824 I CheckinRequestBuilder: Classify the device as Phone.
06-22 07:43:45.920   905  1282 D Process : killProcessQuiet, pid=6366
06-22 07:43:45.920   905  1282 W libprocessgroup: failed to open /acct/uid_10048/pid_6366/cgroup.procs: No such file or directory
06-22 07:43:45.920   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:45.920  6806  6829 I DeviceManagement: SessionStateController: Checking invariants...
,06-22 07:43:45.960  6533  6824 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,06-22 07:43:45.960  6533  6824 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:45.970  6533  6824 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,06-22 07:43:45.970  6533  6824 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:45.970  6533  6824 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:43:45.970  6806  6829 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,06-22 07:43:45.970  6533  6824 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:45.970   455  7052 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
06-22 07:43:45.970   455  7052 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:45.970  6806  6829 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@19f6182e]
,06-22 07:43:45.970  6806  6829 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@4ab5019] args=[Bundle[mParcelledData.dataSize=416]]
,06-22 07:43:46.010   455  7052 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,06-22 07:43:46.010   455  7052 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:46.010  6533  6824 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:46.020  6806  6829 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@4ab5019]
,06-22 07:43:46.020  6806  6829 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@4ab5019] args=[Bundle[mParcelledData.dataSize=316]]
,06-22 07:43:46.020  6806  6829 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.workflow.DMChangeEventWorkflow@4ab5019]
06-22 07:43:46.020  6757  6785 I PushClient: PnsModel {2d1206d9}: update(): Start updating since the registration has expired.
,06-22 07:43:46.020  6806  6806 I DeviceManagement: WorkflowService: Stopping workflow service
,06-22 07:43:46.030   905  1282 I ActivityManager: Killing 6395:com.htc.calendar/u0a10 (adj 15): empty #17
06-22 07:43:46.030   905  1282 D Process : killProcessQuiet, pid=6395
,06-22 07:43:46.030   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:46.030   905  2090 I ActivityManager: Recipient 6395,
,06-22 07:43:46.040  6757  6785 W PushClient: GCMRegistrator {4640003}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
06-22 07:43:46.040  6757  6785 W PushClient:   	,at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:237)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:375)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.cs.pns.receiver.OnConnectedHandler.handle(OnConnectedHandler.java:31)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.handleBroadcast(AbstractIntentServiceBroadcastReceiver.java:123)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver$HandleBroadcastServiceImpl.handleBroadcast(OneTimeOnConnectedReceiver.java:33)
06-22 07:43:46.040  6757  6785 W PushClient:   	at com.htc.lib1.cs.AbstractIntentServiceBroadcastReceiver$HandleBroadcastService.onHandleIntent(AbstractIntentServiceBroadcastReceiver.java:94)
06-22 07:43:46.040  6757  6785 W PushClient:   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:43:46.040  6757  6785 W PushClient:   	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:46.040  6757  6785 W PushClient:   	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:46.040  6757  6785 W PushClient:   	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:43:46.040  6757  6785 W PushClient:   
,06-22 07:43:46.050  6533  6824 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
06-22 07:43:46.050  6533  6824 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:46.060   905  2090 D Process : killProcessQuiet, pid=6395
06-22 07:43:46.060   905  2090 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:46.060   905  2090 W libprocessgroup: failed to open /acct/uid_10010/pid_6395/cgroup.procs: No such file or directory
06-22 07:43:46.070  6533  6533 D GCM     : COMPAT: Multi user not supported
06-22 07:43:46.070  1687  2880 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:46.080   455  7056 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
06-22 07:43:46.080   455  7056 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:43:46.080   455  7056 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:46.080   455  7056 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:43:46.080  1687  2880 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:43:46.080   905  1065 V AlarmManager: sending alarm PendingIntent{16f982fe: PendingIntentRecord{1c9a5a5f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1466574226091, Int=0
,06-22 07:43:46.120  1687  2880 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
06-22 07:43:46.120  1687  2880 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:46.130   905  1282 D Process : killProcessQuiet, pid=6125
,06-22 07:43:46.130   905  1282 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7058 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
06-22 07:43:46.130   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
06-22 07:43:46.130   905  1282 I ActivityManager: Killing 6125:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,06-22 07:43:46.140   905  1636 I ActivityManager: Recipient 6125,
,06-22 07:43:46.150  6533  6824 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,06-22 07:43:46.150  6533  6824 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:46.150  6533  6824 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
06-22 07:43:46.150  6533  6824 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:46.160  6533  6824 I CheckinTask: Sending checkin request (9936 bytes)
,06-22 07:43:46.170   905  1636 D Process : killProcessQuiet, pid=6125
06-22 07:43:46.170   905  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:46.170   905  1636 W libprocessgroup: failed to open /acct/uid_10042/pid_6125/cgroup.procs: No such file or directory
,06-22 07:43:46.180  7058  7058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:43:46.220  1687  2880 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,06-22 07:43:46.220  1687  2880 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:46.220  1687  2880 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,06-22 07:43:46.220  1687  2880 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:46.350   905  1282 D Process : killProcessQuiet, pid=6495,
06-22 07:43:46.350   905  1282 I ActivityManager: Killing 6495:com.htc.task/u0a72 (adj 15): empty #17
06-22 07:43:46.350   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 4,
06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:43:46.350  6757  7086 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:43:46.360   455  7088 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024
06-22 07:43:46.360   455  7088 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:43:46.360   905  1639 I ActivityManager: Recipient 6495,
,06-22 07:43:46.400   905  1639 D Process : killProcessQuiet, pid=6495
06-22 07:43:46.400   905  1639 W libprocessgroup: failed to open /acct/uid_10072/pid_6495/cgroup.procs: No such file or directory
06-22 07:43:46.400   905  1639 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:46.410   455  7088 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
06-22 07:43:46.410   455  7088 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:46.410  6757  7086 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:46.420   905  1637 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=7091 uid=10037 gids={50037, 9997} abi=armeabi-v7a
,06-22 07:43:46.490  6533  6824 I CheckinResponseProcessor: From server: 5 gservices updates and 0 deletes
,06-22 07:43:46.510   905  2090 I art     : Explicit concurrent mark sweep GC freed 19974(979KB) AllocSpace objects, 2(97KB) LOS objects, 33% free, 17MB/25MB, paused 817us total 65.787ms,
,06-22 07:43:46.530   905  1586 D PMS     : acquireWL(3fb43d7b): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null,
06-22 07:43:46.540   905  1495 D Process : killProcessQuiet, pid=6103,
06-22 07:43:46.540   905  1495 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
06-22 07:43:46.540   905  1495 I ActivityManager: Killing 6103:com.htc.videocenter/u0a91 (adj 15): empty #17
06-22 07:43:46.540   905  1584 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2bb5fd6b}
06-22 07:43:46.540   905  1636 D PMS     : releaseWL(2738daba): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android},
06-22 07:43:46.540   905  1266 D PMS     : acquireWL(129bd798): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
,06-22 07:43:46.550   905  1708 I ActivityManager: Recipient 6103,
,06-22 07:43:46.580   905  1708 D Process : killProcessQuiet, pid=6103,
06-22 07:43:46.580   905  1708 W libprocessgroup: failed to open /acct/uid_10091/pid_6103/cgroup.procs: No such file or directory
06-22 07:43:46.580   905  1708 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:46.580   905   921 D PMS     : releaseWL(129bd798): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:46.590   905  1639 D PMS     : acquireWL(3f9b4bf1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:46.590   905  1637 D PMS     : releaseWL(3f9b4bf1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:46.590  1687  1687 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
06-22 07:43:46.590   905  1584 D PMS     : acquireWL(13a8f3d6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 null,
06-22 07:43:46.590   905  1266 D PMS     : releaseWL(13a8f3d6): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
06-22 07:43:46.590  1687  2921 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-22 07:43:46.590   905  1586 D PMS     : acquireWL(6bf3657): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
06-22 07:43:46.600  6533  6533 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-22 07:43:46.600   905  1708 D PMS     : releaseWL(6bf3657): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
,06-22 07:43:46.600   905  1586 D PMS     : acquireWL(42d544): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 WorkSource{1000 android},
06-22 07:43:46.610   905   921 D PMS     : releaseWL(42d544): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android},
,06-22 07:43:46.620   905  1584 D PMS     : releaseWL(3fb43d7b): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
,06-22 07:43:46.630   905  1636 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7109 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
06-22 07:43:46.630   905  1639 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6533, uid=10025, userID:0
06-22 07:43:46.640   467   467 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 141us total 11.247ms
,06-22 07:43:46.650   467   467 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 8.604ms
06-22 07:43:46.660   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 131us total 8.831ms
,06-22 07:43:46.670  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64,
06-22 07:43:46.670  1457  1474 D AccFlag : sku_id=99
06-22 07:43:46.670  6533  7136 D LocationInitializer: Restart initialization of location
,06-22 07:43:46.680  1457  2166 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 103,
06-22 07:43:46.680  1457  2166 D AccFlag : sku_id=99
06-22 07:43:46.680  7109  7109 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:43:46.680  7109  7109 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:46.700  7109  7109 I MultiDex: VM with version 2.1.0 has multidex support,
06-22 07:43:46.700  7109  7109 I MultiDex: install
06-22 07:43:46.700  7109  7109 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-22 07:43:46.710   905  1637 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=7145 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:46.720  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
06-22 07:43:46.720  1457  1474 D AccFlag : sku_id=99
,06-22 07:43:46.720  1457  2166 D TelephUtils: QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 103
06-22 07:43:46.720  1457  2166 D AccFlag : sku_id=99
06-22 07:43:46.720  7109  7109 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-22 07:43:46.740  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,06-22 07:43:46.760   905   921 D PMS     : acquireWL(253588dc): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 7145 10072 null,
,06-22 07:43:46.760   905  1639 D PMS     : acquireWL(1da67de5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 7145 10072 null,
06-22 07:43:46.760   905  2090 D PMS     : acquireWL(1e5d90ba): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 7145 10072 null
,06-22 07:43:46.760   905  1282 D Process : killProcessQuiet, pid=6564,
06-22 07:43:46.760   905  1282 I ActivityManager: Killing 6564:com.htc.android.worldclock/u0a96 (adj 15): empty #17
06-22 07:43:46.760   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:46.760  7109  7109 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-22 07:43:46.760  7109  7109 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f6f42ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:43:46.760  7109  7109 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:46.770   905   920 I ActivityManager: Recipient 6564,
,06-22 07:43:46.780   905  7164 I CertBlacklister: Certificate blacklist changed, updating...
,06-22 07:43:46.790   905  7164 I CertBlacklister: Certificate blacklist updated
,06-22 07:43:46.800  1687  2093 I GservicesProvider: main difference update completed,
,06-22 07:43:46.800   905   920 D Process : killProcessQuiet, pid=6564
06-22 07:43:46.800   905   920 W libprocessgroup: failed to open /acct/uid_10096/pid_6564/cgroup.procs: No such file or directory,
06-22 07:43:46.800   905   920 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:46.800   905  1088 D PMS     : releaseWL(253588dc): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,06-22 07:43:46.800   905  1584 D PMS     : acquireWL(1e5d90ba): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 7145 10072 null
,06-22 07:43:46.800  7145  7165 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,06-22 07:43:46.800  7145  7165 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,06-22 07:43:46.800  7145  7165 W System.err: ,	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,06-22 07:43:46.810  7145  7165 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
06-22 07:43:46.810   905  1281 D PMS     : releaseWL(1da67de5): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,06-22 07:43:46.810  7145  7165 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:46.810  7145  7165 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,06-22 07:43:46.810  7145  7165 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:43:46.810  6533  6824 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-22 07:43:46.810   905  1636 D PMS     : releaseWL(1e5d90ba): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
06-22 07:43:46.810  7145  7165 W NotifyReceiver: stopSelfResult true
06-22 07:43:46.810  7109  7109 D WearableService: callingUid 10025, callindPid: 7109
06-22 07:43:46.820  7145  7165 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
06-22 07:43:46.820   905  1088 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
06-22 07:43:46.820  6533  6824 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-22 07:43:46.830  7145  7165 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
06-22 07:43:46.830  7145  7165 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
06-22 07:43:46.830  7145  7165 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
06-22 07:43:46.830  7145  7165 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:43:46.830  7145  7165 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:46.830  7145  7165 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:43:46.830  7145  7165 E NotifyReceiver: mStartingService is null
06-22 07:43:46.830   905  1088 D PMS     : acquireWL(1b0056c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.830  7145  7165 W NotifyReceiver: stopSelfResult false
,06-22 07:43:46.840  1709  4633 E MDM     : [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-22 07:43:46.840   905  1281 D PMS     : releaseWL(1b0056c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.870   905  1266 D PMS     : acquireWL(461361): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.870   905  1528 D PMS     : releaseWL(461361): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.880  1687  2089 I art     : Explicit concurrent mark sweep GC freed 48396(2MB) AllocSpace objects, 9(469KB) LOS objects, 45% free, 4MB/8MB, paused 1.573ms total 61.216ms
,06-22 07:43:46.930   905  1282 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=7168 uid=10079 gids={50079, 9997} abi=armeabi-v7a
,06-22 07:43:46.930   905  1282 D PMS     : acquireWL(15c3fe86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.940   905  1266 D PMS     : releaseWL(15c3fe86): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:46.960  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
06-22 07:43:46.960  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:46.960  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:46.960  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:46.960  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:46.960  7168  7168 D SMSBackup: Got a database change event
,06-22 07:43:46.970   905  1586 I ActivityManager: Killing 6435:com.android.settings:remote/1000 (adj 15): empty #17,
06-22 07:43:46.970   905  1586 D Process : killProcessQuiet, pid=6435
06-22 07:43:46.970   905  1586 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:46.970   905  1584 I ActivityManager: Recipient 6435
,06-22 07:43:47.000   905  1584 D Process : killProcessQuiet, pid=6435
,06-22 07:43:47.000   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:47.000   905  1584 W libprocessgroup: failed to open /acct/uid_1000/pid_6435/cgroup.procs: No such file or directory
,06-22 07:43:47.000  1687  2980 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-22 07:43:47.000  1687  1687 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-22 07:43:47.010  6533  6533 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-22 07:43:47.020  1199  3757 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
06-22 07:43:47.020  1199  3757 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,06-22 07:43:47.020  1123  1123 I RemoteViews: reapply : com.google.android.gms 2 40
,06-22 07:43:47.020  6533  6824 W CheckinRequestBuilder: awaiting user notification for token
,06-22 07:43:47.030   905  1088 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:47.030  1709  5122 E MDM     : [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-22 07:43:47.040  6533  7187 D LocationInitializer: Restart initialization of location
,06-22 07:43:47.040   905  1528 D PMS     : acquireWL(29c6585e): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:47.050  1687  4324 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,06-22 07:43:47.050  6533  6824 I CheckinRequestBuilder: Classify the device as Phone.,
,06-22 07:43:47.070  6533  6824 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-22 07:43:47.080  6533  6824 I CheckinService: Checking schedule, now: 1466574227087 next: 1467143217081
,06-22 07:43:47.080  6533  6824 I CheckinService: active receiver: disabled
06-22 07:43:47.080   905   920 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:47.090  6939  6939 D Messaging: supportCMAS(SIE)/init? false/true
,06-22 07:43:47.090  6939  6939 D MmsConfig: networkCode: 
06-22 07:43:47.090  6939  6939 D MessageCustFlag: sku_id=99
06-22 07:43:47.090  6939  6939 D MmsConfig: SIE smsPri: null
,06-22 07:43:47.090  6939  6939 D MmsConfig: networkCode: 
,06-22 07:43:47.100  6757  6785 I PushClient: PnsModel {2d1206d9}: update(): Update registration succeeded.
,06-22 07:43:47.100   905  1637 D PMS     : acquireWL(2edae10c): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 6297 10011 null
,06-22 07:43:47.100   905  1585 D PMS     : releaseWL(29c6585e): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:47.110  6939  6939 D MmsConfig: packageName: com.htc.vvm.att does not exist
,06-22 07:43:47.110  6939  6939 D ReportIndicatorCache: startAsyncQueryReports ---
,06-22 07:43:47.110  6939  6956 D MmsAsyncWorkHandler: 
06-22 07:43:47.110  6939  6956 D MmsAsyncWorkHandler: HM tk = 20001
06-22 07:43:47.110  6939  6956 D ReportIndicatorCache: MSG_QUERY_REPORTS >>
,06-22 07:43:47.110  6939  6939 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@c3fa9dd,
,06-22 07:43:47.110  6939  6939 D DraftCache: [DraftCache/1] DraftCache.constructor,
06-22 07:43:47.110  6939  6939 D DraftCache: [DraftCache/1] refresh
06-22 07:43:47.110  6297  7192 E SQLiteLog: (284) automatic index on view_events(_id)
,06-22 07:43:47.110  6939  6939 D MmsConfig: networkCode: 
,06-22 07:43:47.120  6939  7193 D Messaging: mNeedToUpdateDate2 start
,06-22 07:43:47.120  6939  7195 I Messaging: mccmnc> 
,06-22 07:43:47.120  6939  7197 D Messaging: ViewCache CreatePreloadOnlyConversationList
,06-22 07:43:47.130   905  1528 I ActivityManager: Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.dm2.ConfigChangeReceiver: pid=7199 uid=10032 gids={50032, 9997, 3003} abi=armeabi-v7a,
,06-22 07:43:47.140  1457  2092 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
06-22 07:43:47.140  1457  2092 D MmsSmsV2Provider:  slotId = -1000
06-22 07:43:47.140  1457  2092 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,06-22 07:43:47.140  1457  2092 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102,
06-22 07:43:47.140  1457  2092 D AccFlag : sku_id=99
,06-22 07:43:47.140   905   921 D PMS     : releaseWL(2edae10c): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,06-22 07:43:47.150  6533  7211 I CheckinService: Checking schedule, now: 1466574227155 next: 1467143217081
,06-22 07:43:47.150  6533  7211 I CheckinService: active receiver: disabled
06-22 07:43:47.150  6939  6956 D DraftCache: [DraftCache/916] rebuildCache
06-22 07:43:47.150  6939  6939 D PhoneStorageUtil: HtcWrapEnvironment.getSupportedStorages() >1
06-22 07:43:47.150  6939  6939 D PhoneStorageUtil: HtcWrapEnvironment.hasRemovableStorageSlot()() >true
06-22 07:43:47.150  6939  6939 D PhoneStorageUtil: createReceiver
06-22 07:43:47.150  1457  2092 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
06-22 07:43:47.150  1457  2092 D MmsSmsV2Provider:  slotId = -1000,
06-22 07:43:47.150  1457  2092 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
06-22 07:43:47.150   905  1636 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:47.150   905  1708 D Process : killProcessQuiet, pid=6596,
06-22 07:43:47.150   905  1708 I ActivityManager: Killing 6596:com.qualcomm.timeservice/1000 (adj 15): empty #17
06-22 07:43:47.150   905  1708 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:47.150  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
06-22 07:43:47.150  1457  1474 D MmsSmsV2Provider:  slotId = -1000
06-22 07:43:47.150  1457  1474 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,06-22 07:43:47.150  6939  7194 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
,06-22 07:43:47.160  6939  7197 D MessageCustFlag: sense_version=6.0,
06-22 07:43:47.160  6939  7197 D Jerry   : start to preload cursor >>>>>>>
,06-22 07:43:47.160   905  1586 I ActivityManager: Recipient 6596,
,06-22 07:43:47.230   905  1586 D Process : killProcessQuiet, pid=6596
,06-22 07:43:47.230   905  1586 W libprocessgroup: failed to open /acct/uid_1000/pid_6596/cgroup.procs: No such file or directory
06-22 07:43:47.230   905  1586 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:47.230   905  1636 D PMS     : releaseWL(3ab2b2ad): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:47.230  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
06-22 07:43:47.230  1457  1475 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
06-22 07:43:47.230  1457  1475 V MmsProvider: Update uri=content://mms, match=0
06-22 07:43:47.230  1457  1475 V MmsProvider: selection=st=129 AND m_type!=134
,06-22 07:43:47.230  1457  1474 D Jerry   : URI_DRAFT
,06-22 07:43:47.230  6939  7217 D Messaging: Reset downloading state: 0
,06-22 07:43:47.230  6939  6956 D DraftCache: hasDraft() = false mNeedNotifyChange = true
,06-22 07:43:47.230  6939  6956 D DraftCache: [DraftCache/916] rebuildCache time: 3
06-22 07:43:47.230  6939  6956 D MmsAsyncWorkHandler: 
06-22 07:43:47.230  6939  6956 D MmsAsyncWorkHandler: HM tk = 20002
,06-22 07:43:47.240  6939  7217 V MmsSystemEventReceiver: TransactionService is going to be woken up.
,06-22 07:43:47.240  1457  2092 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102
,06-22 07:43:47.240  1457  2092 D MmsSmsV2Provider:  slotId = -1000
06-22 07:43:47.240  1457  2092 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,06-22 07:43:47.240  6939  7193 D Messaging: mNeedToUpdateDate2: false
,06-22 07:43:47.240  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
06-22 07:43:47.240  1457  1474 D MmsSmsV2Provider:  slotId = -1000
,06-22 07:43:47.240  6939  6939 V TransactionService: 1-Creating TransactionService
,06-22 07:43:47.250  6939  6939 V TransactionService: onStartCommand: 1
,06-22 07:43:47.250  6939  6939 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
,06-22 07:43:47.260  1457  2166 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
06-22 07:43:47.260  1457  2166 D AccFlag : sku_id=99
,06-22 07:43:47.260  6939  7218 V TransactionService: 4-Handling incoming message: { when=-9ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
06-22 07:43:47.260  6939  7218 V TransactionService: Loading previous transactions.
,06-22 07:43:47.260  1457  1474 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,06-22 07:43:47.260  1457  1474 D AccFlag : sku_id=99
,06-22 07:43:47.260  1457  2092 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 102,
06-22 07:43:47.260  1457  2092 D AccFlag : device_type: 1
,06-22 07:43:47.260  6939  7197 D Messaging: ViewCache CreatePreload
06-22 07:43:47.260  6939  7197 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList
,06-22 07:43:47.270  6939  7218 D TransactionService: Force set service start id to 1,
06-22 07:43:47.270  6939  7218 V TransactionService: stopSelfIfIdle: unRegisterForConnectionStateChanges
06-22 07:43:47.270  6939  7218 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
06-22 07:43:47.270  6939  7218 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
06-22 07:43:47.270  6939  6939 V TransactionService: Destroying TransactionService
,06-22 07:43:47.270  6939  7218 V TransactionService: 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,06-22 07:43:47.270  6939  7197 D Cust_MMSMS: _has_set_default_values_2=true,
,06-22 07:43:47.280  6939  7197 D MsgPreferenceUtils: def_index: 0,
,06-22 07:43:47.280   905  1088 D Process : killProcessQuiet, pid=6462,
,06-22 07:43:47.280   905  1088 I ActivityManager: Killing 6462:com.google.android.music:main/u0a167 (adj 15): empty #17
06-22 07:43:47.280   905  1088 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
06-22 07:43:47.280   905   905 D PMS     : acquireWL(35e50c79): PARTIAL_WAKE_LOCK  *backup* 0x1 905 1000 null
06-22 07:43:47.280  6939  7197 D MsgPreferenceUtils: globalIndex = 1
,06-22 07:43:47.280   905  1090 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
06-22 07:43:47.280   905  1090 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
06-22 07:43:47.280   905  1090 D PMS     : releaseWL(35e50c79): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,06-22 07:43:47.280  6939  7197 D MsgPreferenceUtils: phone state: true
,06-22 07:43:47.280  6939  7197 D MsgPreferenceUtils: sd state: false
06-22 07:43:47.280  6939  7197 D MsgPreferenceUtils: vIndex = 0
,06-22 07:43:47.290   905  1586 I ActivityManager: Recipient 6462
06-22 07:43:47.290   905  1636 D MediaRouterService: Client com.google.android.music (pid 6462): Died!
,06-22 07:43:47.390   905   905 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver}
,06-22 07:43:47.390   905   905 W BroadcastQueue: android.os.DeadObjectException
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:504)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:921)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:254),
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:989)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	,at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16983)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.sendFinished(BroadcastReceiver.java:435)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.finish(BroadcastReceiver.java:411)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:976)
,06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	,at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Native Method),
,06-22 07:43:47.390   905   905 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 07:43:47.390   905   905 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,06-22 07:43:47.390   905   905 W libprocessgroup: failed to open /acct/uid_10167/pid_6462/cgroup.procs: No such file or directory
,06-22 07:43:47.530   905   905 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=7246 uid=10167 gids={50167, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:43:47.530   905  1586 W ActivityManager: Spurious death for ProcessRecord{181f4653 7246:com.google.android.music:main/u0a167}, curProc for 6462: null,
,06-22 07:43:47.530   905   905 D PMS     : releaseWL(3dac06a1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,06-22 07:43:47.720  7246  7246 I MusicStore: Database version: 120,
,06-22 07:43:47.860   905  1586 I art     : Explicit concurrent mark sweep GC freed 15132(776KB) AllocSpace objects, 2(97KB) LOS objects, 33% free, 16MB/25MB, paused 1.272ms total 75.033ms,
,06-22 07:43:47.880   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
06-22 07:43:47.880  7246  7246 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
06-22 07:43:47.880   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:47.920   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
06-22 07:43:47.920   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:43:47.920  7246  7246 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,06-22 07:43:47.920   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
,06-22 07:43:47.920   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:43:47.920  7246  7246 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,06-22 07:43:47.950  7246  7246 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
06-22 07:43:47.950  7246  7246 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,06-22 07:43:47.980  7246  7246 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,06-22 07:43:48.060  7246  7246 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,06-22 07:43:48.060  7246  7246 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c345d41: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:43:48.060  7246  7246 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-22 07:43:48.060  7246  7246 D AndroidMusic: GMSCore installation verified
,06-22 07:43:48.070  7246  7246 I ConfigStore: Config Database version: 1
,06-22 07:43:48.100   905   920 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=7246, uid=10167, userID:0
,06-22 07:43:48.110   905  2090 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
06-22 07:43:48.110   905  2090 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:48.110   905  2090 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:48.110   905  2090 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:48.110   905  2090 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:48.110   905  2090 D WifiDisplayAdapter:     IP Address: }
,06-22 07:43:48.110   905  1585 D MediaRouterService: Client com.google.android.music (pid 7246): Registered,
,06-22 07:43:48.110   905   920 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
06-22 07:43:48.110   905   920 D WifiDisplayAdapter:     Client/Owner: Client
06-22 07:43:48.110   905   920 D WifiDisplayAdapter:     GroupId: 
06-22 07:43:48.110   905   920 D WifiDisplayAdapter:     Passphrase: 
06-22 07:43:48.110   905   920 D WifiDisplayAdapter:     SessionId: 0
06-22 07:43:48.110   905   920 D WifiDisplayAdapter:     IP Address: }
,06-22 07:43:48.120  7246  7246 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,06-22 07:43:48.120   905  1266 D PMS     : acquireWL(20538bd2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7246 10167 null,
,06-22 07:43:48.130  7246  7246 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-22 07:43:48.190  1687  4631 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-22 07:43:48.190  1687  1687 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
06-22 07:43:48.190  7246  7246 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-22 07:43:48.200   905  1586 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7246, uid=10167, userID:0,
06-22 07:43:48.200  6533  6533 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-22 07:43:48.200   905  1282 D PMS     : releaseWL(20538bd2): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
06-22 07:43:48.200  7246  7296 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-22 07:43:48.200  7246  7296 I MusicLeanback: Stop autocaching.
,06-22 07:43:48.210   905   920 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=7246, uid=10167, userID:0,
,06-22 07:43:48.210   905  1528 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:48.220  1709  2886 E MDM     : [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,06-22 07:43:48.250  6533  7300 D LocationInitializer: Restart initialization of location,
06-22 07:43:48.250   905   921 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7301 uid=10028 gids={50028, 9997, 3003} abi=armeabi-v7a
,06-22 07:43:48.260  7246  7246 I MusicLeanback: Stop autocaching.,
,06-22 07:43:48.270  7246  7281 I MusicLeanback: Stop autocaching.
,06-22 07:43:48.280  7246  7246 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
06-22 07:43:48.280  7246  7246 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-22 07:43:48.290  7246  7281 I MusicLeanback: Stop autocaching.
,06-22 07:43:48.340  7246  7246 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,06-22 07:43:48.340  7246  7328 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,06-22 07:43:48.340   905   921 D Process : killProcessQuiet, pid=6706
06-22 07:43:48.340   905   921 I ActivityManager: Killing 6706:com.fitbit.FitbitMobile/u0a23 (adj 15): empty #17,
06-22 07:43:48.340   905   921 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:48.360   905  2090 I ActivityManager: Recipient 6706,
,06-22 07:43:48.370   905  2090 D Process : killProcessQuiet, pid=6706,
06-22 07:43:48.370   905  2090 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:48.370   905  2090 W libprocessgroup: failed to open /acct/uid_10023/pid_6706/cgroup.procs: No such file or directory
,06-22 07:43:48.410   905   921 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7346 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,06-22 07:43:48.430   905  1584 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=7301, uid=10028, userID:0
,06-22 07:43:48.460  7346  7346 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION,
,06-22 07:43:48.470  7346  7346 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:43:48.470   905  1266 D PMS     : acquireWL(31f2ce2c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.470  7346  7346 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION,
,06-22 07:43:48.470  7346  7346 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-22 07:43:48.480   905  1585 I ActivityManager: Killing 6513:com.google.android.youtube/u0a186 (adj 15): empty #17
06-22 07:43:48.480   905  1585 D Process : killProcessQuiet, pid=6513
06-22 07:43:48.480   905  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:48.500   905   920 I ActivityManager: Recipient 6513,
,06-22 07:43:48.530   905   920 D Process : killProcessQuiet, pid=6513,
06-22 07:43:48.530   905   920 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:48.530   905   920 W libprocessgroup: failed to open /acct/uid_10186/pid_6513/cgroup.procs: No such file or directory
,06-22 07:43:48.540   905  1584 D PMS     : releaseWL(31f2ce2c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:48.540   905  1495 D PMS     : acquireWL(32943cfb): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:48.540   905  1585 D PMS     : acquireWL(c2e1771): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
,06-22 07:43:48.540   905  1586 D PMS     : releaseWL(c2e1771): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:48.540   905  1639 D PMS     : acquireWL(d2a9956): PARTIAL_WAKE_LOCK  Checkin Service 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.540   905  1586 D PMS     : releaseWL(32943cfb): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.550   905   921 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:48.550   905  1282 D PMS     : acquireWL(45fadd7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.560  6533  7377 I CheckinService: Checking schedule, now: 1466574228566 next: 1467143217081
,06-22 07:43:48.560  6533  7377 I CheckinService: active receiver: disabled
,06-22 07:43:48.560   905  1636 D PMS     : acquireWL(efeb6c4): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
06-22 07:43:48.560   905  1282 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
06-22 07:43:48.560   905  1586 D PMS     : releaseWL(efeb6c4): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:48.570  6533  6533 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,06-22 07:43:48.570   905  1708 D PMS     : acquireWL(1dbbb9ad): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.570  6533  6533 D SystemUpdateService: onCreate
,06-22 07:43:48.580  6533  6533 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,06-22 07:43:48.580   905  1528 D PMS     : releaseWL(d2a9956): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:48.590   905  1584 D PMS     : acquireWL(46b7d2e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
,06-22 07:43:48.590   905  1586 D PMS     : releaseWL(46b7d2e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:48.590  1687  2880 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,06-22 07:43:48.590   905  1637 D PMS     : releaseWL(45fadd7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.600  6533  7380 I SystemUpdateService: cancelUpdate (empty URL)
06-22 07:43:48.600  6533  7380 I SystemUpdateService: active receiver: disabled
06-22 07:43:48.600   905  1586 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:48.600   905  2090 D PMS     : acquireWL(217c80cf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.600   905  1266 D PMS     : releaseWL(217c80cf): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.610  6533  6533 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-22 07:43:48.610  6533  6533 I OcrUtils: Updating ocr activity enabled=false
,06-22 07:43:48.610   905  1585 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=6533, uid=10025, userID:0
06-22 07:43:48.620  6533  6533 D SystemUpdateService: onDestroy
06-22 07:43:48.620   905  1282 D PMS     : releaseWL(1dbbb9ad): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.620  1709  1709 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,06-22 07:43:48.630  1687  2093 I art     : Explicit concurrent mark sweep GC freed 11731(556KB) AllocSpace objects, 3(243KB) LOS objects, 46% free, 4MB/8MB, paused 727us total 28.545ms
,06-22 07:43:48.630   905  2090 D PMS     : acquireWL(27b63e3a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null,
06-22 07:43:48.640   905  1586 D PMS     : releaseWL(27b63e3a): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
,06-22 07:43:48.640   905  1495 D PMS     : acquireWL(a6a5aeb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
,06-22 07:43:48.640   905  1639 D PMS     : releaseWL(a6a5aeb): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null,
06-22 07:43:48.650  1709  1709 I GCoreUlr: DispatchingService.onCreate()
,06-22 07:43:48.650   905  1528 I ActivityManager: Killing 6757:com.htc.cs.pns/u0a74 (adj 15): empty #17,
06-22 07:43:48.650   905  1528 D Process : killProcessQuiet, pid=6757,
06-22 07:43:48.650   905  1528 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-22 07:43:48.650   905  2090 D PMS     : acquireWL(3ba0406): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
,06-22 07:43:48.660   905  1282 D PMS     : releaseWL(3ba0406): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:48.660   905  1266 I ActivityManager: Recipient 6757
,06-22 07:43:48.690   905  1266 D Process : killProcessQuiet, pid=6757,
06-22 07:43:48.690   905  1266 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:48.690   905  1266 W libprocessgroup: failed to open /acct/uid_10074/pid_6757/cgroup.procs: No such file or directory
,06-22 07:43:48.690   905  1639 D PMS     : acquireWL(2611bac7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 null
06-22 07:43:48.690   905  2090 D PMS     : releaseWL(2611bac7): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,06-22 07:43:48.690   905  1637 D PMS     : acquireWL(195f58f4): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.700   905  2090 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.copresence.service.ProximitySettingInjectorService, state=2, flag=1, pid=1709, uid=10025, userID:0
,06-22 07:43:48.700   905  1585 D PMS     : acquireWL(1b6b681d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.740  1709  2017 I art     : Explicit concurrent mark sweep GC freed 16572(988KB) AllocSpace objects, 3(48KB) LOS objects, 42% free, 5MB/9MB, paused 794us total 38.875ms
,06-22 07:43:48.750  1709  1722 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b140a6)
,06-22 07:43:48.750   905  1637 D PMS     : releaseWL(1b6b681d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.760  1709  7384 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,06-22 07:43:48.780  6533  7385 I art     : Explicit concurrent mark sweep GC freed 27682(1836KB) AllocSpace objects, 20(321KB) LOS objects, 43% free, 5MB/9MB, paused 613us total 37.319ms
,06-22 07:43:48.850  1709  7384 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]},
,06-22 07:43:48.850   905   920 D PMS     : acquireWL(9e25a92): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.850   905  1637 D PMS     : releaseWL(9e25a92): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.850  1709  7384 I GCoreUlr: Unbound from all location providers
,06-22 07:43:48.850   905   921 D PMS     : releaseWL(195f58f4): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.900  1687  1703 I art     : Explicit concurrent mark sweep GC freed 4183(166KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 601us total 32.542ms,
,06-22 07:43:48.910  1709  1709 I GCoreUlr: DispatchingService.onDestroy(),
,06-22 07:43:48.910   905  1636 D PMS     : acquireWL(be53c63): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.920   905  1088 D PMS     : releaseWL(be53c63): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.920  1709  1709 I GCoreUlr: Unbound from all location providers
,06-22 07:43:48.940   905  1637 D PMS     : acquireWL(17db6919): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:48.970   905  1266 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1709, uid=10025, userID:0
,06-22 07:43:48.970   905  1495 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1687, uid=10025, userID:0
,06-22 07:43:48.980  6533  7389 I Icing   : Storage manager: low false usage 1.59MB avail 7.54GB capacity 9.08GB
,06-22 07:43:48.980  6533  7389 W Icing   : Received bad json for section weights override -- ignoring.
,06-22 07:43:48.990  6533  7389 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,06-22 07:43:48.990  6533  7389 W Icing   : Received bad json for section weights override -- ignoring.
06-22 07:43:48.990  6533  7389 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,06-22 07:43:49.040   905   921 I art     : Explicit concurrent mark sweep GC freed 12453(716KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 16MB/25MB, paused 1.015ms total 75.333ms
,06-22 07:43:49.080   905   921 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=7398 uid=10089 gids={50089, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,06-22 07:43:49.110   905   999 D PMS     : acquireWL(39b07dd5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null,
,06-22 07:43:49.120   905   999 D PMS     : acquireWL(3e3aa9ea): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10025},
,06-22 07:43:49.130  1123  1302 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,06-22 07:43:49.130   905   999 D PMS     : releaseWL(39b07dd5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:49.130   905   999 D PMS     : acquireWL(b98e3b7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:49.130   905   999 D PMS     : releaseWL(b98e3b7): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null,
,06-22 07:43:49.180  1123  1123 D PhoneStatusBar: addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020652 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,06-22 07:43:49.200  6533  7389 I Icing   : updateResources: need to parse f{com.google.android.gms},
,06-22 07:43:49.210   905   999 D PMS     : acquireWL(1c04e724): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:43:49.210   905   999 D PMS     : releaseWL(3e3aa9ea): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10025}
,06-22 07:43:49.210  1123  1302 I IntentController: receive(android.intent.action.SYNC_STATE_CHANGED,1,false),
06-22 07:43:49.220   905   999 D PMS     : releaseWL(1c04e724): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:43:49.240  6533  7389 I Icing   : Internal init done: storage state 0
,06-22 07:43:49.240  6533  7389 I Icing   : Post-init done
,06-22 07:43:49.290   905  1088 D LocationManagerService: getProviders()=[passive, network],
,06-22 07:43:49.310   905  2090 D PMS     : releaseWL(17db6919): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:43:49.330   905  1088 I ActivityManager: Killing 6786:com.google.android.setupwizard/u0a80 (adj 15): empty #17
06-22 07:43:49.330   905  1088 D Process : killProcessQuiet, pid=6786
06-22 07:43:49.330   905  1088 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,06-22 07:43:49.340   905  1585 I ActivityManager: Recipient 6786
,06-22 07:43:49.380   905  1585 D Process : killProcessQuiet, pid=6786
,06-22 07:43:49.380   905  1585 W libprocessgroup: failed to open /acct/uid_10080/pid_6786/cgroup.procs: No such file or directory
06-22 07:43:49.380   905  1585 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:49.410   905  1639 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7429 uid=10080 gids={50080, 9997, 3003} abi=armeabi-v7a,
,06-22 07:43:49.430  7398  7444 I GservicesUpdateTask: Updating Gservices keys,
,06-22 07:43:49.460  7429  7429 D PhoneMonitor: Register our PhoneStateListener,
,06-22 07:43:49.480  1457  1582 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
06-22 07:43:49.480  1457  1582 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,06-22 07:43:49.480  7429  7429 V SetupWizard: Connected to Gservices successfully,
,06-22 07:43:49.500  7429  7429 D PhoneMonitor: onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,06-22 07:43:49.500  6533  6533 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-22 07:43:49.500  7429  7429 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,06-22 07:43:49.500  6533  6533 I Kids    : [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,06-22 07:43:49.510  1687  2921 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,06-22 07:43:49.520  1687  2980 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,06-22 07:43:49.520  6533  6533 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-22 07:43:49.520  6533  6533 I Kids    : [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,06-22 07:43:49.520   905  1088 D PMS     : acquireWL(84bfd66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:49.530   905  1088 D PMS     : releaseWL(84bfd66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:49.580   905  1528 D Process : killProcessQuiet, pid=6830,
,06-22 07:43:49.580   905  1528 I ActivityManager: Killing 6830:com.twitter.android/u0a181 (adj 15): empty #17
06-22 07:43:49.580   905  1528 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:49.590   905  1639 I ActivityManager: Recipient 6830
,06-22 07:43:49.610   905  1639 D Process : killProcessQuiet, pid=6830
06-22 07:43:49.610   905  1639 W libprocessgroup: failed to open /acct/uid_10181/pid_6830/cgroup.procs: No such file or directory
06-22 07:43:49.610   905  1639 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:50.930   905  1281 D Process : killProcessQuiet, pid=6961,
06-22 07:43:50.930   905  1281 I ActivityManager: Killing 6961:com.google.android.apps.magazines/u0a169 (adj 15): empty #17,
,06-22 07:43:50.940   905  1281 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,06-22 07:43:51.020   905  1584 I ActivityManager: Recipient 6961,
,06-22 07:43:51.050   905  1584 D Process : killProcessQuiet, pid=6961,
06-22 07:43:51.050   905  1584 W libprocessgroup: failed to open /acct/uid_10169/pid_6961/cgroup.procs: No such file or directory
06-22 07:43:51.050   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:43:51.500   905  1586 D PMS     : releaseWL(88eb205): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:43:53.130   905  1639 D PMS     : acquireWL(18026154): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 7246 10167 null,
,06-22 07:43:53.190   905  1639 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=7246, uid=10167, userID:0,
,06-22 07:43:53.200   905  1637 D PMS     : releaseWL(18026154): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
06-22 07:43:53.200  7246  7464 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false,
,06-22 07:43:53.200  7246  7464 I MusicLeanback: Stop autocaching.,
,06-22 07:43:53.210  7246  7246 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,06-22 07:43:53.230  7246  7467 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,06-22 07:43:53.240   905  1585 D Process : killProcessQuiet, pid=7032,
06-22 07:43:53.240   905  1585 I ActivityManager: Killing 7032:com.android.chrome/u0a102 (adj 15): empty #17
06-22 07:43:53.240   905  1585 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,06-22 07:43:53.250   905  1586 I ActivityManager: Recipient 7032,
,06-22 07:43:53.300   905  1586 D Process : killProcessQuiet, pid=7032
06-22 07:43:53.300   905  1586 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:53.300   905  1586 W libprocessgroup: failed to open /acct/uid_10102/pid_7032/cgroup.procs: No such file or directory
,06-22 07:43:53.770  1587  2027 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,06-22 07:43:53.900  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
06-22 07:43:53.900  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,06-22 07:43:53.900  1457  1457 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,06-22 07:43:53.900   905  1585 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=6533, uid=10025, userID:0,
,06-22 07:43:53.910  1380  7503 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
06-22 07:43:53.910  1380  7503 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
06-22 07:43:53.910  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-22 07:43:53.910  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false,
,06-22 07:43:53.920   905   905 W PackageManager: Unable to load service info ResolveInfo{63de952 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-22 07:43:53.920   905   905 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-22 07:43:53.920   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-22 07:43:53.920   905   905 W PackageManager: 	,at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:43:53.920   905   905 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:53.920   905   905 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 07:43:53.920   905   905 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 07:43:53.920   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:53.920   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:53.920   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 07:43:53.920   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,06-22 07:43:53.920   905  1495 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:53.920   905  1088 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=6533, uid=10025, userID:0,
06-22 07:43:53.930  1457  1457 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
06-22 07:43:53.940   905  1528 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=6533, uid=10025, userID:0
06-22 07:43:53.940  1587  2027 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
06-22 07:43:53.940   905  1586 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7506 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
06-22 07:43:53.940  1457  1457 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,06-22 07:43:53.950   905  1586 D Process : killProcessQuiet, pid=6806
06-22 07:43:53.950   905  1586 I ActivityManager: Killing 6806:com.htc.cs.dm/u0a105 (adj 15): empty #17
06-22 07:43:53.950   905  1586 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:43:53.960  1587  2027 E ExternalAccountType: Unsupported attribute readOnly
,06-22 07:43:53.970   905   921 I ActivityManager: Recipient 6806
,06-22 07:43:53.970  1587  2027 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,06-22 07:43:53.980  1587  2027 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,06-22 07:43:53.990  1587  2027 E ExternalAccountType: Unsupported attribute readOnly,
,06-22 07:43:53.990   905   999 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,06-22 07:43:54.000  1587  2027 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,06-22 07:43:54.010   905   921 D Process : killProcessQuiet, pid=6806
06-22 07:43:54.010   905   921 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:54.010   905   921 W libprocessgroup: failed to open /acct/uid_10105/pid_6806/cgroup.procs: No such file or directory
,06-22 07:43:54.010  1587  2027 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,06-22 07:43:54.050   905   905 W PackageManager: Unable to load service info ResolveInfo{1235c2e6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
06-22 07:43:54.050   905   905 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-22 07:43:54.050   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:43:54.050   905   905 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:54.050   905   905 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 07:43:54.050   905   905 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 07:43:54.050   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:54.050   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:54.050   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 07:43:54.050   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,06-22 07:43:54.070  1587  2027 E ExternalAccountType: Unsupported attribute readOnly
06-22 07:43:54.070  7506  7506 D HtcFingerPrintQuickLaunchProvider: -onCreate()
06-22 07:43:54.080   905   905 W PackageManager: Unable to load service info ResolveInfo{2edcde2a com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-22 07:43:54.080   905   905 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-22 07:43:54.080   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:43:54.080   905   905 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-22 07:43:54.080   905   905 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 07:43:54.080   905   905 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 07:43:54.080   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:43:54.080   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:43:54.080   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 07:43:54.080   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
06-22 07:43:54.090  7506  7506 V Settings:HtcSettingsApplication: [7506/7506] onCreate()
,06-22 07:43:54.100   905   905 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-22 07:43:54.130   905  1637 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7529 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:43:54.130   905  1637 D Process : killProcessQuiet, pid=7058
06-22 07:43:54.130   905  1637 I ActivityManager: Killing 7058:com.google.android.apps.plus/u0a176 (adj 15): empty #17
06-22 07:43:54.130   905  1637 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,06-22 07:43:54.150   905  1282 I ActivityManager: Recipient 7058
,06-22 07:43:54.180  7506  7545 E Settings:HtcWrapHeaderInfo: no such activity!
,06-22 07:43:54.190   905  1282 D Process : killProcessQuiet, pid=7058
,06-22 07:43:54.190   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:43:54.190   905  1282 W libprocessgroup: failed to open /acct/uid_10176/pid_7058/cgroup.procs: No such file or directory
,06-22 07:43:54.190  7506  7528 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.
,06-22 07:43:54.210  7506  7528 E Settings:HtcWrapHeaderInfo: updateDevelopment, bPrefShow = true,
,06-22 07:43:54.220   905   999 D LocationProviderProxy: applying state to connected service,
06-22 07:43:54.220   905  1637 D PMS     : acquireWL(3b31c4ea): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.220   905  1282 D PMS     : releaseWL(3b31c4ea): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.220  1709  2019 V GmsNetworkLocationProvi: onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000,
,06-22 07:43:54.220  1709  1709 V GmsNetworkLocationProvi: DISABLE
,06-22 07:43:54.230   905   999 D LocationProviderProxy: applying state to connected service
,06-22 07:43:54.230  7506  7528 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false
,06-22 07:43:54.230   905   999 D PMS     : acquireWL(152c53db): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.230   905  1282 D PMS     : releaseWL(152c53db): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.240  1709  1709 V GmsNetworkLocationProvi: ENABLE,
,06-22 07:43:54.240   905   905 D PMS     : acquireWL(3bce9e78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
06-22 07:43:54.240   905  1584 D PMS     : releaseWL(3bce9e78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.240  1709  1709 V GmsNetworkLocationProvi: SET-REQUEST
,06-22 07:43:54.240  1709  1709 V GmsNetworkLocationProvi: in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,06-22 07:43:54.240   905   920 D PMS     : acquireWL(168b2a24): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1709 10025 WorkSource{1000 android}
,06-22 07:43:54.240   905  1528 D PMS     : releaseWL(168b2a24): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 WorkSource{1000 android}
,06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
06-22 07:43:54.260  7506  7528 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,06-22 07:43:54.280   905  1639 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
,06-22 07:43:54.280  7506  7528 E ActivityThread: Failed to find provider info for com.htc.vowifi
06-22 07:43:54.280  7506  7528 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
,06-22 07:43:54.280  7506  7527 W Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub: The wrap header doesn't exist in header list.
06-22 07:43:54.280  7506  7527 E Settings:HtcWrapHeaderInfo: updateDevelopment, bPrefShow = true
,06-22 07:43:54.280  7506  7527 E Settings:HtcUmcWidgetEnabler: isSupportMusicChannel(): false
,06-22 07:43:54.280   905  1637 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7529, uid=10075, userID:0
,06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasNavigationBar:true
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]hasRecentAppsKey:false
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportRecentAppsButton]support         :false
,06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasNavigationBar:true
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasMenuKey      :false
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasRecentAppKey :false
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasBackKey      :false
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]hasHomeKey      :false
06-22 07:43:54.280  7506  7527 V Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags: [supportHomeButton]support         :false
,06-22 07:43:54.290  7506  7527 E Settings:HtcVoWifiWidgetEnabler: isSupportVoWifi: null
06-22 07:43:54.290   905  1585 I ActivityManager: Cannot resolve ContentProvider=com.htc.vowifi
06-22 07:43:54.290  7506  7527 E ActivityThread: Failed to find provider info for com.htc.vowifi
,06-22 07:43:54.300  7529  7529 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,06-22 07:43:54.480  7529  7529 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,06-22 07:43:54.520  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:54.570   905  1637 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7572 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,06-22 07:43:54.590   467   467 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 282us total 19.693ms
,06-22 07:43:54.610   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 267us total 17.513ms,
,06-22 07:43:54.610  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,06-22 07:43:54.610  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:54.610  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:54.610  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:43:54.620  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:54.620   467   467 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 226us total 16.941ms
,06-22 07:43:54.630  7572  7572 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:43:54.630  7572  7572 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:54.650  7529  7529 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,06-22 07:43:54.650  1687  2089 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
06-22 07:43:54.650  1687  2089 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
06-22 07:43:54.650  1687  2089 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
06-22 07:43:54.650  1687  2089 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
06-22 07:43:54.650  1687  2089 W GLSActivity: ,	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
06-22 07:43:54.650  1687  2089 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 07:43:54.650  1687  2089 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:54.650  7529  7567 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.,
06-22 07:43:54.650  7529  7567 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 07:43:54.650  7529  7567 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
06-22 07:43:54.650  7529  7567 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
06-22 07:43:54.650  7529  7567 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
06-22 07:43:54.650  7529  7567 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
,06-22 07:43:54.650  7529  7567 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
06-22 07:43:54.650  1199  1220 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
06-22 07:43:54.650  1199  1220 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
06-22 07:43:54.650  1123  1123 I RemoteViews: reapply : com.google.android.gms 1 40,
,06-22 07:43:54.660  7529  7529 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,06-22 07:43:54.660  7572  7572 I MultiDex: VM with version 2.1.0 has multidex support
,06-22 07:43:54.660  7572  7572 I MultiDex: install
06-22 07:43:54.660  7572  7572 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-22 07:43:54.680  7572  7572 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-22 07:43:54.690   905  2090 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7529, uid=10075, userID:0,
,06-22 07:43:54.690  7529  7567 W System  : Ignoring header User-Agent because its value was null.
,06-22 07:43:54.690  7529  7567 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,06-22 07:43:54.690  7529  7567 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:43:54.700  7529  7567 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,06-22 07:43:54.700  7529  7567 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:43:54.700  7529  7567 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:43:54.700  7529  7567 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:43:54.700   455  7598 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,06-22 07:43:54.700   455  7598 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
06-22 07:43:54.700   455  7598 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:43:54.700   455  7598 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:43:54.700  7529  7567 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:43:54.710  7529  7529 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-22 07:43:54.710  7529  7529 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,06-22 07:43:54.720  7529  7529 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,06-22 07:43:54.720  6533  7601 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,06-22 07:43:54.730  7398  7603 I UpdateIcingCorporaServi: Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE,
,06-22 07:43:54.740  7529  7529 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,06-22 07:43:54.740  7572  7572 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
06-22 07:43:54.740  7572  7572 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f6f42ae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
06-22 07:43:54.740  7572  7572 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:54.760   905  1637 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7608 uid=10176 gids={50176, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:43:54.770   905  1585 D PMS     : acquireWL(3cd3d716): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.780  6533  7605 I PeopleContactsSync: CP2 sync disabled
,06-22 07:43:54.780   905  1266 D PMS     : releaseWL(3cd3d716): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:54.780   905  1088 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:54.800  7608  7608 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:43:54.840  7398  7603 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] ,
,06-22 07:43:54.890   905  1065 D PMS     : acquireWL(17790733): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
,06-22 07:43:54.890   905  1065 V AlarmManager: sending alarm PendingIntent{232bcaf0: PendingIntentRecord{22e306 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574234892, Int=0
06-22 07:43:54.890   905   905 D PMS     : releaseWL(17790733): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,06-22 07:43:54.950   905  1708 I art     : Explicit concurrent mark sweep GC freed 30220(1725KB) AllocSpace objects, 3(113KB) LOS objects, 33% free, 17MB/25MB, paused 1.355ms total 78.876ms
,06-22 07:43:55.050  1687  2093 I art     : Explicit concurrent mark sweep GC freed 7237(359KB) AllocSpace objects, 3(243KB) LOS objects, 46% free, 4MB/8MB, paused 551us total 24.073ms
,06-22 07:43:55.060  7529  7529 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,06-22 07:43:55.080   905  1584 D PMS     : acquireWL(311d7225): PARTIAL_WAKE_LOCK  AsyncService 0x1 7608 10176 null
,06-22 07:43:55.080   905  1586 D PMS     : releaseWL(311d7225): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-22 07:43:55.090   905  1639 D PMS     : acquireWL(350429ab): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7608 10176 null
,06-22 07:43:55.100  1380  7643 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.pns,
,06-22 07:43:55.100  1380  7643 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,06-22 07:43:55.100  6533  7646 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.pns
,06-22 07:43:55.110  7398  7648 I UpdateIcingCorporaServi: Updating corpora: APPS=com.htc.cs.pns, CONTACTS=MAYBE
,06-22 07:43:55.110   905  1636 D PMS     : releaseWL(350429ab): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
06-22 07:43:55.110  6533  7649 I PeopleContactsSync: CP2 sync disabled
06-22 07:43:55.120   905  1708 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:55.120   905  1585 D PMS     : acquireWL(aaba452): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:55.120   905  1708 D PMS     : releaseWL(aaba452): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:43:55.120   905  1266 D PMS     : acquireWL(14ffd020): PARTIAL_WAKE_LOCK  AsyncService 0x1 7608 10176 null
,06-22 07:43:55.130   905  1528 D PMS     : releaseWL(14ffd020): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-22 07:43:55.130   905   921 D PMS     : acquireWL(83bb39e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7608 10176 null
,06-22 07:43:55.130   905  1282 D PMS     : acquireWL(3c59ce7f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6905 10120 null
,06-22 07:43:55.140   905  1495 D PMS     : releaseWL(83bb39e): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,06-22 07:43:55.150  1380  7654 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
06-22 07:43:55.150  1380  7654 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,06-22 07:43:55.150  6533  7658 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-22 07:43:55.160  6533  7658 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,06-22 07:43:55.160   905  1495 D PMS     : acquireWL(da09b4d): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:43:55.170   905   921 D PMS     : acquireWL(2741c602): PARTIAL_WAKE_LOCK  AsyncService 0x1 7608 10176 null,
06-22 07:43:55.170  6533  7389 I Icing   : updateResources: need to parse f{com.google.android.gms}
,06-22 07:43:55.170  6905  6905 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 07:43:55.170   905  1266 D PMS     : acquireWL(10378150): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7608 10176 null
,06-22 07:43:55.170  6905  6905 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:43:55.170  1687  4324 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-22 07:43:55.170  7398  7648 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] 
,06-22 07:43:55.180  1687  1687 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-22 07:43:55.180   905  1584 D PMS     : releaseWL(2741c602): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-22 07:43:55.180  7398  7648 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-22 07:43:55.180   905  1637 D PMS     : releaseWL(10378150): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,06-22 07:43:55.180  6533  6533 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-22 07:43:55.200   905  1495 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6533, uid=10025, userID:0
,06-22 07:43:55.200  1709  2922 E MDM     : [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-22 07:43:55.200  6533  7663 D LocationInitializer: Restart initialization of location,
,06-22 07:43:55.210   905  1281 D PMS     : releaseWL(da09b4d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:43:55.210   905  1639 D PMS     : releaseWL(3c59ce7f): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,06-22 07:43:55.220  6905  6905 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,06-22 07:43:55.250  7398  7648 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
,06-22 07:43:55.260  6905  6905 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-22 07:43:55.260  6905  6905 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:43:55.300  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.320  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
,06-22 07:43:55.320  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.320  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:55.320  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.320  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.330  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:43:55.330  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,06-22 07:43:55.330  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,06-22 07:43:55.370  1687  7381 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
06-22 07:43:55.370  1687  7381 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.370  1687  7381 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-22 07:43:55.370  1687  7381 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.370  1687  7381 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.380  6905  7666 E Babel   : UserRecoverableAuthException.
,06-22 07:43:55.380  6905  7666 E Babel   : eei: BadAuthentication
06-22 07:43:55.380  6905  7666 E Babel   : 	at eeg.a(Unknown Source)
06-22 07:43:55.380  6905  7666 E Babel   : 	at eeg.a(Unknown Source)
06-22 07:43:55.380  6905  7666 E Babel   : 	at eeg.a(Unknown Source)
06-22 07:43:55.380  6905  7666 E Babel   : 	at g.a(Unknown Source)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:3089)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:1131)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:4333)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:1419)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:492)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:1468)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cqu.a(SourceFile:4416)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cas.b(SourceFile:106)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cap.d(SourceFile:335)
06-22 07:43:55.380  6905  7666 E Babel   : 	at caq.run(SourceFile:81)
,06-22 07:43:55.380  6905  7666 E Babel   : Error getting auth token
06-22 07:43:55.380  6905  7666 E Babel   : dvm
06-22 07:43:55.380  6905  7666 E Babel   : 	at g.a(Unknown Source)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:3089)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:1131)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:4333)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:1419)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:492)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:1468)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cqu.a(SourceFile:4416)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cas.b(SourceFile:106)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cap.d(SourceFile:335)
06-22 07:43:55.380  6905  7666 E Babel   : 	at caq.run(SourceFile:81)
,06-22 07:43:55.380  6905  7666 E Babel   : Account registration failed 1-Redacted-21
06-22 07:43:55.380  6905  7666 E Babel   : cyp: null -- null
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:3121)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cae.a(SourceFile:1131)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:4333)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cws.a(SourceFile:1419)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:492)
06-22 07:43:55.380  6905  7666 E Babel   : 	at crl.a(SourceFile:1468)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cqu.a(SourceFile:4416)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cas.b(SourceFile:106)
06-22 07:43:55.380  6905  7666 E Babel   : 	at cap.d(SourceFile:335)
06-22 07:43:55.380  6905  7666 E Babel   : 	at caq.run(SourceFile:81)
,06-22 07:43:55.390  6905  7666 I art     : Note: end time exceeds epoch: 
,06-22 07:43:55.400  1687  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,06-22 07:43:55.400  1687  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.400  1687  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:55.400  1687  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.400  1687  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.410  1687  1706 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:43:55.430  6905  7671 E Babel   : Unexpected exception while authenticating.
,06-22 07:43:55.430  1199  3757 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
06-22 07:43:55.430  1199  3757 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
06-22 07:43:55.430  6905  7671 E Babel   : eej: User intervention required. Notification has been pushed.
06-22 07:43:55.430  6905  7671 E Babel   : 	at eeg.b(Unknown Source)
06-22 07:43:55.430  6905  7671 E Babel   : 	at eeg.b(Unknown Source)
06-22 07:43:55.430  6905  7671 E Babel   : 	at g.a(Unknown Source)
06-22 07:43:55.430  6905  7671 E Babel   : 	at cae.b(SourceFile:1146)
06-22 07:43:55.430  6905  7671 E Babel   : 	at dcg.run(SourceFile:5617)
,06-22 07:43:55.430  6905  7671 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 07:43:55.430  6905  7671 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 07:43:55.430  6905  7671 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
06-22 07:43:55.430  1123  1123 I RemoteViews: reapply : com.google.android.gms 2 40
,06-22 07:43:55.450  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,06-22 07:43:55.450  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 +
06-22 07:43:55.450  1493  1859 I Prism.WidgetManager: onLoadItems() +
,06-22 07:43:55.470  1493  1859 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-22 07:43:55.480   905  1065 D PMS     : acquireWL(2c244be5): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075}
06-22 07:43:55.480  7529  7529 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
06-22 07:43:55.480   905  1065 V AlarmManager: sending alarm PendingIntent{32b246ba: PendingIntentRecord{36a3d0c9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574235486, Int=0
06-22 07:43:55.480   905   905 D PMS     : releaseWL(2c244be5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,06-22 07:43:55.490  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.500  1687  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
06-22 07:43:55.500  1687  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.500  1687  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:55.500  1687  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.500  1687  2093 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.510  7529  7529 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,06-22 07:43:55.520  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.530  1687  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
06-22 07:43:55.530  1687  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.530  1687  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:55.530  1687  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.530  1687  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.550  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.560  1687  1703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
06-22 07:43:55.560  1687  1703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.560  1687  1703 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-22 07:43:55.560  1687  1703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.560  1687  1703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:43:55.570  7529  7529 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,06-22 07:43:55.640  1493  1859 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-22 07:43:55.720  1493  1859 E Prism.WidgetManager: The same lists. No need to update. skip it.
,06-22 07:43:55.720  1493  1859 I Prism.WidgetManager: onLoadItems() -
06-22 07:43:55.720  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 -
,06-22 07:43:55.770  1493  1493 W Prism.AllAppsManager: AllAppsMgr addApps, already exist: ApplicationInfo(id=43, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,06-22 07:43:55.770  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-22 07:43:55.770  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,06-22 07:43:55.770  1493  1493 I Launcher: Deferring update until onResume,
06-22 07:43:55.770  1493  1493 D Launcher: waitUntilResume // bindAppsUpdated
,06-22 07:43:55.790  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.810  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,06-22 07:43:55.810  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:43:55.810  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:43:55.810  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:43:55.810  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:43:55.820  7529  7529 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-22 07:43:55.820  7529  7529 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,06-22 07:43:55.820  7529  7529 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-22 07:43:55.830  7529  7529 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,06-22 07:43:55.840  1709  2019 D DeviceConnectionService: client connected with version: 7571000
,06-22 07:43:55.980  1457  1863 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,06-22 07:43:55.980  1457  1863 D PhoneApp: -- N1 =0
,06-22 07:43:55.980  1457  1863 D PhoneApp: -- N2 =0,
06-22 07:43:55.980  1457  1863 D PhoneApp: -- N3 =0,
,06-22 07:43:57.270  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
06-22 07:43:57.270  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 +,
,06-22 07:43:57.280  1493  1859 I Prism.WidgetManager: onLoadItems() +
,06-22 07:43:57.510  1493  1859 E Prism.WidgetManager: The same lists. No need to update. skip it.,
06-22 07:43:57.510  1493  1859 I Prism.WidgetManager: onLoadItems() -
,06-22 07:43:57.520  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 -
,06-22 07:43:57.600   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:43:58.520   905  1052 W PackageSettings: Skipping PackageSetting{2be7f569 com.example.hello/10380} due to missing metadata,
,06-22 07:43:59.020  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,06-22 07:43:59.030  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 +
,06-22 07:43:59.030  1493  1859 I Prism.WidgetManager: onLoadItems() +
,06-22 07:43:59.330  1493  1859 E Prism.WidgetManager: The same lists. No need to update. skip it.,
06-22 07:43:59.330  1493  1859 I Prism.WidgetManager: onLoadItems() -
06-22 07:43:59.330  1493  1859 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@3a2553b9 -
,06-22 07:44:00.260   905  1708 D Process : killProcessQuiet, pid=7145,
,06-22 07:44:00.260   905  1708 I ActivityManager: Killing 7145:com.htc.task/u0a72 (adj 15): empty #17
06-22 07:44:00.260   905  1708 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,06-22 07:44:00.290   905  1639 I ActivityManager: Recipient 7145,
,06-22 07:44:00.350   905  1708 D Process : killProcessQuiet, pid=7168,
06-22 07:44:00.350   905  1708 I ActivityManager: Killing 7168:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
06-22 07:44:00.350   905  1708 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:44:00.360   905  1584 I ActivityManager: Recipient 7168
,06-22 07:44:00.460   905  1639 D Process : killProcessQuiet, pid=7145
,06-22 07:44:00.460   905  1639 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:44:00.460   905  1639 W libprocessgroup: failed to open /acct/uid_10072/pid_7145/cgroup.procs: No such file or directory,
06-22 07:44:00.460   905  1584 D Process : killProcessQuiet, pid=7168
06-22 07:44:00.460   905  1584 W libprocessgroup: failed to open /acct/uid_10079/pid_7168/cgroup.procs: No such file or directory
06-22 07:44:00.460   905  1584 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:44:00.460   905   920 I ActivityManager: Killing 6297:com.htc.bgp/u0a11 (adj 15): empty #17,
06-22 07:44:00.460   905   920 D Process : killProcessQuiet, pid=6297
06-22 07:44:00.460   905   920 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:44:00.470   905  2090 I ActivityManager: Recipient 6297,
,06-22 07:44:00.490   905  2090 D Process : killProcessQuiet, pid=6297,
06-22 07:44:00.490   905  2090 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:44:00.490   905  2090 W libprocessgroup: failed to open /acct/uid_10011/pid_6297/cgroup.procs: No such file or directory
,06-22 07:44:03.980   905  1639 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=6533, uid=10025, userID:0,
,06-22 07:44:03.980   905  1584 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=6533, uid=10025, userID:0,
,06-22 07:44:03.990   905  1585 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=6533, uid=10025, userID:0,
,06-22 07:44:03.990  6533  6823 I CheckinService: Done disabling old GoogleServicesFramework version,
,06-22 07:44:07.610   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:44:12.670  1380  6775 D AutoSetting: service - handleMessage() stop self,
,06-22 07:44:12.700  1380  1380 D AutoSetting: service - onDestroy() END,
,06-22 07:44:12.700  1380  6775 D AutoSetting: service - handleMessage() quit looper,
,06-22 07:44:15.570   905  1065 D PMS     : acquireWL(b6333be): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
06-22 07:44:15.580   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=123924, Int=0
06-22 07:44:15.590   905  1065 V AlarmManager: sending alarm PendingIntent{15f51c1f: PendingIntentRecord{26e89b6c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=132394, Int=0,
06-22 07:44:15.620   905  1065 V AlarmManager: sending alarm PendingIntent{291acdca: PendingIntentRecord{22e306 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574255580, Int=0
06-22 07:44:15.630   905  1282 D PMS     : acquireWL(1f595b3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:44:15.660   905   905 D PMS     : releaseWL(b6333be): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,06-22 07:44:15.680   905  1636 D PMS     : acquireWL(1d7a0258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10186 com.google.android.youtube},
,06-22 07:44:15.720   905  1281 I ActivityManager: Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7697 uid=10186 gids={50186, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
06-22 07:44:15.720   905  1266 D PMS     : releaseWL(1f595b3b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:44:15.730  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:44:15.810  7697  7731 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
06-22 07:44:15.810  7697  7731 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-22 07:44:15.810  1123  2217 D WeatherUtility: Weather sync is On
06-22 07:44:15.820   905  1282 D PMS     : acquireWL(3cf87017): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 07:44:15.830  7697  7731 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,06-22 07:44:15.880  7697  7731 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-22 07:44:15.880  7697  7731 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-22 07:44:15.940  7744  7744 E cutils-trace: Error opening trace file: No such file or directory (2)
,06-22 07:44:15.940  7744  7744 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads100568600.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads100568600.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-22 07:44:15.970  7697  7697 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,06-22 07:44:15.970  7697  7697 D libc    : [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
06-22 07:44:15.970  7697  7697 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:44:15.990  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:44:16.000  7744  7744 I dex2oat : dex2oat took 56.111ms (threads: 4)
06-22 07:44:16.000   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
06-22 07:44:16.000   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:16.000  7697  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,06-22 07:44:16.060   905   905 I art     : Explicit concurrent mark sweep GC freed 32536(1880KB) AllocSpace objects, 3(113KB) LOS objects, 33% free, 17MB/25MB, paused 1.192ms total 68.373ms
,06-22 07:44:16.080  1687  7381 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 07:44:16.080  1687  7381 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:44:16.080  1687  7381 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:44:16.080  1687  7381 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:44:16.080  1687  7381 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:44:16.090  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:44:16.090  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,06-22 07:44:16.090  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,06-22 07:44:16.130   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
06-22 07:44:16.130   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:16.130  7697  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,06-22 07:44:16.140   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,06-22 07:44:16.140   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 07:44:16.140  7697  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,06-22 07:44:16.140   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
06-22 07:44:16.140   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:16.140  7697  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,06-22 07:44:16.140  7697  7697 W InstanceID/Rpc: Found 10025,
,06-22 07:44:16.160   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/,
06-22 07:44:16.160  7697  7697 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
06-22 07:44:16.160   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
,06-22 07:44:16.160   905  1636 D PMS     : acquireWL(9037cef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms},
,06-22 07:44:16.170   905   921 D PMS     : releaseWL(9037cef): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
,06-22 07:44:16.170   905  1639 D PMS     : releaseWL(1d7a0258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10186 com.google.android.youtube},
,06-22 07:44:16.170   905  1586 D PMS     : acquireWL(366733fc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
,06-22 07:44:16.180   905   920 D PMS     : releaseWL(366733fc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:44:16.210   905  1586 I ActivityManager: Killing 6939:com.htc.sense.mms/u0a67 (adj 15): empty #17,
06-22 07:44:16.210   905  1586 D Process : killProcessQuiet, pid=6939
06-22 07:44:16.210   905  1586 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:44:16.220   905  1636 I ActivityManager: Recipient 6939
,06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:44:16.230   455  7804 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
06-22 07:44:16.230   455  7804 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:44:16.230   455  7804 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-22 07:44:16.230   455  7804 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
06-22 07:44:16.230  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:44:16.250   905  1636 D Process : killProcessQuiet, pid=6939,
06-22 07:44:16.250   905  1636 W libprocessgroup: failed to open /acct/uid_10067/pid_6939/cgroup.procs: No such file or directory
06-22 07:44:16.250   905  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:44:16.360  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
,06-22 07:44:16.360  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:44:16.780   905  1076 E WifiStateMachine: handleMessage: E msg.what=131165,
06-22 07:44:16.780   905  1076 E WifiStateMachine: processMsg: ConnectedState,
,06-22 07:44:16.780   905  1076 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
06-22 07:44:16.780   905  1076 E WifiStateMachine: processMsg: L2ConnectedState,
,06-22 07:44:16.780   905  1076 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,06-22 07:44:16.780   905  1076 E WifiStateMachine: processMsg: ConnectModeState,
,06-22 07:44:16.790   905  1076 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,06-22 07:44:16.790   905  1076 E WifiStateMachine: processMsg: DriverStartedState,
06-22 07:44:16.790   905  1076 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
,06-22 07:44:16.790   905  1076 E WifiStateMachine: processMsg: SupplicantStartedState,
,06-22 07:44:16.790   905  1076 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
06-22 07:44:16.790   905  1076 E WifiStateMachine: processMsg: DefaultState
06-22 07:44:16.790   905  1076 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,06-22 07:44:16.800   905  1076 E WifiStateMachine: handleMessage: X
,06-22 07:44:17.210   905   999 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
,06-22 07:44:17.210   905   999 D PMS     : acquireWL(16bbd132): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 905 1000 null,
,06-22 07:44:17.210   905   999 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,06-22 07:44:17.230   905  7815 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 4,
,06-22 07:44:17.240   905  7815 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:44:17.240   905  7815 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 1024,
,06-22 07:44:17.250   905  7815 D libc    : [NET] android_getaddrinfofornet-, pass to proxy,
,06-22 07:44:17.250   905  7815 D libc    : [NET] android_getaddrinfo_proxy+,
,06-22 07:44:17.260   905  7815 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,06-22 07:44:17.260   455  7817 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261322e67),sn(),hints(known),family 0,flags 1024,
06-22 07:44:17.260   455  7817 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-22 07:44:17.260   455  7817 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,06-22 07:44:17.260   455  7817 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:44:17.260   905  7815 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:44:17.270   905  7815 D libc    : [NET] android_getaddrinfofornet+,hn 12(0x35322e38342e31),sn(),hints(known),family 0,flags 4,
,06-22 07:44:17.270   905  7815 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,06-22 07:44:18.530   905  7815 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,06-22 07:44:19.030   905  1448 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
,06-22 07:44:19.030   905  1448 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0,
,06-22 07:44:19.030   905  7815 D GpsLocationProvider:  [handleDownloadXtraData]inject done.,
,06-22 07:44:19.050   905  7815 D PMS     : acquireWL(1b37fdf): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null,
,06-22 07:44:19.050   905   999 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,06-22 07:44:19.060   905  7815 D PMS     : releaseWL(16bbd132): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
,06-22 07:44:19.060   905   999 D PMS     : releaseWL(1b37fdf): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,06-22 07:44:19.390   905  1528 D PMS     : acquireWL(2fdd942c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:44:19.400   905  1528 I BatteryService: n_update end
06-22 07:44:19.420   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:44:19.420   905   905 D UsbnetService: onReceive BATTERY_CHANGED,
06-22 07:44:19.420   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:44:19.420   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,06-22 07:44:19.420   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:44:19.420   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:44:19.430  1123  1123 D PowerUI : closing low battery warning: level=100
,06-22 07:44:19.420  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:44:19.430  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:44:19.420  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 07:44:19.430  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:44:19.430  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:44:19.430  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-22 07:44:19.440   905  1011 D HtcPowerSaver: updateBatteryInfo,
06-22 07:44:19.440   905   905 D PMS     : runPSCheck
,06-22 07:44:19.440   905   905 D HtcPowerSaver: Checking...
06-22 07:44:19.440   905   905 I HtcPowerSaver: >> updateStatus
,06-22 07:44:19.440   905  1528 D PMS     : releaseWL(2fdd942c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:44:19.450   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 07:44:19.450   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:44:19.470  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:44:19.570  1457  1582 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
,06-22 07:44:19.570  1457  1582 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<,
,06-22 07:44:22.610   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 07:44:25.830   905  2090 D PMS     : releaseWL(3cf87017): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:44:26.090  7697  7782 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 4,
,06-22 07:44:26.100  7697  7782 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:44:26.100  7697  7782 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 1024,
06-22 07:44:26.100  7697  7782 D libc    : [NET] android_getaddrinfofornet-, pass to proxy,
,06-22 07:44:26.100  7697  7782 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:44:26.100  7697  7782 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,06-22 07:44:26.100   455  7820 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 1024,
06-22 07:44:26.100   455  7820 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:44:26.150   455  7820 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
,06-22 07:44:26.150   455  7820 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:44:26.150  7697  7782 D libc    : [NET] android_getaddrinfo_proxy-, success,
,06-22 07:44:26.160  7697  7782 D libc    : [NET] android_getaddrinfofornet+,hn 12(0x38392e32352e32),sn(),hints(known),family 0,flags 4,
,06-22 07:44:26.160  7697  7782 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,06-22 07:44:26.200  7697  7782 D libc    : [NET] android_getaddrinfofornet+,hn 15(0x7777772e796f75),sn(),hints(known),family 0,flags 4,
,06-22 07:44:26.200  7697  7782 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:44:28.570   905   905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:817 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,06-22 07:44:36.100   905  1065 D PMS     : acquireWL(1cb8548a): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 07:44:36.100   905  1065 V AlarmManager: sending alarm PendingIntent{10fa3afb: PendingIntentRecord{22e306 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574276104, Int=0
06-22 07:44:36.100   905   905 D PMS     : releaseWL(1cb8548a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075},
,06-22 07:44:36.390  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:44:36.400  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
06-22 07:44:36.400  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:44:36.400  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:44:36.400  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:44:36.400  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:44:36.410  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 07:44:36.410  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 07:44:36.410  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.,
,06-22 07:44:36.780   905  1076 E WifiStateMachine: handleMessage: E msg.what=131326,
,06-22 07:44:36.780   905  1076 E WifiStateMachine: processMsg: ConnectedState,
,06-22 07:44:36.780   905  1076 E WifiStateMachine:  ConnectedState what:131326 1 0,
,06-22 07:44:36.780   905  1076 E WifiStateMachine: processMsg: L2ConnectedState,
,06-22 07:44:36.780   905  1076 E WifiStateMachine:  L2ConnectedState what:131326 1 0,
,06-22 07:44:36.780   905  1076 E WifiStateMachine: handleMessage: X,
,06-22 07:44:42.620   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:44:43.860  1457  1457 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,06-22 07:45:03.400   905  1065 D PMS     : acquireWL(5e13f65): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{1000},
,06-22 07:45:03.400   905   905 D PMS     : acquireWL(f56f43a): PARTIAL_WAKE_LOCK  *backup* 0x1 905 1000 null,
,06-22 07:45:03.410   905  1065 V AlarmManager: sending alarm PendingIntent{16f982fe: PendingIntentRecord{1c9a5a5f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1466574294211, Int=0,
06-22 07:45:03.410   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=183925, Int=0
,06-22 07:45:03.410   905  1065 V AlarmManager: sending alarm PendingIntent{254bd8eb: PendingIntentRecord{2e252648 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=187329, Int=0,
06-22 07:45:03.440   905  1065 V AlarmManager: sending alarm PendingIntent{23b01a06: PendingIntentRecord{22e306 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574296421, Int=0,
,06-22 07:45:03.470   905   905 D PMS     : releaseWL(5e13f65): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
06-22 07:45:03.480   905  1090 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,06-22 07:45:03.490   905  1090 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found,
,06-22 07:45:03.490   905  1090 D PMS     : releaseWL(f56f43a): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,06-22 07:45:03.510  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:45:03.640  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:45:03.650   905  1282 D PMS     : acquireWL(2a8a5ef4): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 07:45:03.730  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:45:03.750  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 07:45:03.750  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
06-22 07:45:03.750  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:45:03.750  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:45:03.750  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:03.760  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 07:45:03.760  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 07:45:03.760  7529  7529 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,06-22 07:45:07.630   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:45:13.710   905  1088 D PMS     : releaseWL(2a8a5ef4): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:45:19.480   905  1585 D PMS     : acquireWL(26b910b6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:45:19.490   905  1585 I BatteryService: n_update end
06-22 07:45:19.510   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:45:19.510   905   905 D UsbnetService: onReceive BATTERY_CHANGED,
06-22 07:45:19.510   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:45:19.510   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:45:19.510   905  1077 D WifiController: battery changed pluggedType: 2,
06-22 07:45:19.510   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:45:19.510  1123  1123 D PowerUI : closing low battery warning: level=100
,06-22 07:45:19.510  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:45:19.520  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:45:19.510  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:45:19.520   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:45:19.510  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 07:45:19.520   905   905 D PMS     : runPSCheck
06-22 07:45:19.510  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:45:19.520   905   905 D HtcPowerSaver: Checking...
,06-22 07:45:19.510  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:45:19.520   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:45:19.530   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 07:45:19.530   905   905 I HtcPowerSaver: << updateStatus
06-22 07:45:19.530   905  1585 D PMS     : releaseWL(26b910b6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:45:19.560  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:45:21.240  1123  2246 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,06-22 07:45:21.250  1380  1380 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1ef17394,
,06-22 07:45:21.270   905   921 D Process : killProcessQuiet, pid=7199,
06-22 07:45:21.270   905   921 I ActivityManager: Killing 7199:com.htc.csrecommend/u0a32 (adj 15): empty #17,
06-22 07:45:21.270   905   921 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,06-22 07:45:21.290  1123  2246 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,06-22 07:45:21.300   905  1282 I ActivityManager: Recipient 7199,
,06-22 07:45:21.330   905  1282 D Process : killProcessQuiet, pid=7199,
06-22 07:45:21.330   905  1282 W libprocessgroup: failed to open /acct/uid_10032/pid_7199/cgroup.procs: No such file or directory
06-22 07:45:21.330   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
,06-22 07:45:47.630   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:45:57.630   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:46:12.640   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:46:19.650   905  1281 D PMS     : acquireWL(2a7c1b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null
06-22 07:46:19.660   905  1281 I BatteryService: n_update end
,06-22 07:46:19.680   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:46:19.680   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:46:19.680   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:46:19.680   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:46:19.680   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:46:19.680   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:46:19.690  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:46:19.680  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 07:46:19.690  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:46:19.680  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:46:19.690   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:46:19.680  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:46:19.690   905   905 D PMS     : runPSCheck
06-22 07:46:19.680  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:46:19.690   905   905 D HtcPowerSaver: Checking...
06-22 07:46:19.680  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:46:19.690   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:46:19.700   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:46:19.700   905   905 I HtcPowerSaver: << updateStatus
06-22 07:46:19.700   905  1281 D PMS     : releaseWL(2a7c1b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:46:19.730  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:46:32.640   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:46:45.810  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
06-22 07:46:45.810  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
06-22 07:46:45.810  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
06-22 07:46:45.810  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 84:b2:61:0f:9c:30 SSID '\x00' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID f4:f2:6d:85:e5:9e SSID 'cvbtemp' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 9 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 10 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
06-22 07:46:45.820  6093  6093 D wpa_supplicant: wlan0: BSS: Remove id 11 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
,06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0,
06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c1]
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c1
06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 84:b2:61:1a:ce:70]
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 84:b2:61:1a:ce:70
06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1a:ef:42:f2:b0]
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1a:ef:42:f2:b0
06-22 07:46:45.820   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 84:b2:61:0f:9c:30],
06-22 07:46:45.820   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 84:b2:61:0f:9c:30
06-22 07:46:45.830   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:16:a6:1e:e0:a4]
06-22 07:46:45.830   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:16:a6:1e:e0:a4
06-22 07:46:45.830   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 f4:f2:6d:85:e5:9e]
06-22 07:46:45.830   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 f4:f2:6d:85:e5:9e
06-22 07:46:45.830   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 84:b2:61:1a:ce:73],
06-22 07:46:45.830   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 84:b2:61:1a:ce:73
06-22 07:46:45.830   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 84:b2:61:0f:9c:33]
06-22 07:46:45.830   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 84:b2:61:0f:9c:33
06-22 07:46:45.830   905  6146 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 e4:aa:5d:fc:5b:f3]
06-22 07:46:45.830   905  6146 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 e4:aa:5d:fc:5b:f3
,06-22 07:46:57.650   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:47:19.810   905  2090 D PMS     : acquireWL(8fd6d24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:47:19.810   905  2090 I BatteryService: n_update end
06-22 07:47:19.840  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:47:19.840  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:47:19.840  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:47:19.840  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:47:19.840   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:47:19.840   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:47:19.850   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:47:19.850   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:47:19.850  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,06-22 07:47:19.850   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:47:19.860   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:47:19.850   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:47:19.860   905   905 D PMS     : runPSCheck
06-22 07:47:19.850  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:47:19.860   905   905 D HtcPowerSaver: Checking...
06-22 07:47:19.860  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
06-22 07:47:19.860   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:47:19.860   905  2090 D PMS     : releaseWL(8fd6d24): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:47:19.860   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:47:19.860   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:47:19.900  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:47:39.020   905  1065 D PMS     : acquireWL(1900a08d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
,06-22 07:47:39.020   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=243925, Int=0,
,06-22 07:47:39.090   905  1065 I ActivityManager: Start proc com.htc.backup for service com.htc.backup/.AutoBackupNotificationScheduler: pid=7880 uid=10118 gids={50118, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-22 07:47:39.090   905  1065 V AlarmManager: sending alarm PendingIntent{103d8242: PendingIntentRecord{28ecc253 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1466574459024, Int=0,
,06-22 07:47:39.120   905   905 D PMS     : releaseWL(1900a08d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
06-22 07:47:39.190  7880  7880 I htcbackup-core: ModelRegistry: Loading model meta data from resources...,
06-22 07:47:39.220  1123  2217 D WeatherUtility: Weather sync is On
,06-22 07:47:39.300  1123  2217 D WeatherUtility: Weather sync is On,
06-22 07:47:39.300   905  1266 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7922 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,06-22 07:47:39.310   905  1637 D PMS     : acquireWL(2ec65445): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 07:47:39.340  7922  7922 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=7922 dbg=false s=true
,06-22 07:47:39.340  7922  7937 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,06-22 07:47:39.340  7922  7937 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.backup (10118) packages=[com.htc.backup]
,06-22 07:47:39.350  7922  7943 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,06-22 07:47:39.350  7922  7922 I DeviceManagement: WorkflowService: Starting workflow service
,06-22 07:47:39.350  7922  7944 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2d1206d9] args=[Bundle[mParcelledData.dataSize=132]]
,06-22 07:47:39.350  7922  7944 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
,06-22 07:47:39.360  7922  7944 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,06-22 07:47:39.370  7922  7944 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,06-22 07:47:39.370  7922  7945 I DeviceManagement: SessionStateController: Checking invariants...
,06-22 07:47:39.500  7922  7945 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,06-22 07:47:39.560  7922  7944 I DeviceManagement: SessionStateController: Checking invariants...,
,06-22 07:47:39.610  7922  7944 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true,
,06-22 07:47:39.610  7922  7944 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2d1206d9],
,06-22 07:47:39.610  7922  7922 I DeviceManagement: WorkflowService: Stopping workflow service
,06-22 07:47:39.760   905  1266 D Process : killProcessQuiet, pid=7346,
06-22 07:47:39.760   905  1266 I ActivityManager: Killing 7346:com.google.android.configupdater/u0a104 (adj 15): empty #17
,06-22 07:47:39.760   905  1266 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:47:39.770   905  1281 I ActivityManager: Recipient 7346
,06-22 07:47:39.780   905  1281 D Process : killProcessQuiet, pid=7346,
06-22 07:47:39.780   905  1281 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
06-22 07:47:39.780   905  1281 W libprocessgroup: failed to open /acct/uid_10104/pid_7346/cgroup.procs: No such file or directory
,06-22 07:47:42.650   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:47:49.320   905  1586 I ActivityManager: Killing 7301:com.google.android.partnersetup/u0a28 (adj 15): empty #17,
,06-22 07:47:49.330   905  1586 D Process : killProcessQuiet, pid=7301,
06-22 07:47:49.330   905  1586 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
06-22 07:47:49.350   905   921 D PMS     : releaseWL(2ec65445): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:47:49.380   905  1636 I ActivityManager: Recipient 7301,
,06-22 07:47:49.390   905  1636 D Process : killProcessQuiet, pid=7301
06-22 07:47:49.390   905  1636 W libprocessgroup: failed to open /acct/uid_10028/pid_7301/cgroup.procs: No such file or directory,
06-22 07:47:49.390   905  1636 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:47:52.660   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:48:07.660   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,06-22 07:48:19.970   905  1281 D PMS     : acquireWL(4befff2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null
06-22 07:48:19.980   905  1281 I BatteryService: n_update end
06-22 07:48:20.010  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:48:20.030  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:48:20.030  1123  1123 D PowerUI : closing low battery warning: level=100,
06-22 07:48:20.030  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
06-22 07:48:20.030  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:48:20.030   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:48:20.030   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:48:20.030   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:48:20.030   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:48:20.030   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:48:20.030   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:48:20.030   905   905 D UsbnetService: BroadcastReceiver::onReceive-
,06-22 07:48:20.030   905   905 D PMS     : runPSCheck
06-22 07:48:20.030  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:48:20.030   905   905 D HtcPowerSaver: Checking...
06-22 07:48:20.030  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:48:20.030   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:48:20.040   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:48:20.040   905   905 I HtcPowerSaver: << updateStatus
06-22 07:48:20.040   905  1281 D PMS     : releaseWL(4befff2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:48:20.080  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:48:27.670   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-22 07:48:40.640   905  1065 D PMS     : acquireWL(1e7ae643): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
06-22 07:48:40.640   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=363924, Int=0
06-22 07:48:40.640   905  1065 V AlarmManager: sending alarm PendingIntent{74ea4c0: PendingIntentRecord{3f2ed5f9 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=404574, Int=0
06-22 07:48:40.660   905   905 D PMS     : acquireWL(23b9293e): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,06-22 07:48:40.670   905   905 D PMS     : releaseWL(1e7ae643): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:48:40.690  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:48:40.760   905   999 D PMS     : acquireWL(45ba39f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,06-22 07:48:40.760   905   999 D PMS     : releaseWL(23b9293e): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
06-22 07:48:40.760   905   999 D PMS     : releaseWL(45ba39f): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,06-22 07:48:40.770  1123  2217 D WeatherUtility: Weather sync is On
,06-22 07:48:40.780   905  1585 D PMS     : acquireWL(67dd8b5): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 07:48:50.800   905  1088 D PMS     : releaseWL(67dd8b5): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:48:52.670   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:49:16.300  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:16.320  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:16.320  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
,06-22 07:49:16.320  7697  7800 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,06-22 07:49:16.320  7697  7800 D libc    : [NET] android_getaddrinfo_proxy+
,06-22 07:49:16.320  7697  7800 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-22 07:49:16.330   455  7981 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024,
06-22 07:49:16.330   455  7981 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:49:16.370   455  7981 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
06-22 07:49:16.370   455  7981 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
06-22 07:49:16.370  7697  7800 D libc    : [NET] android_getaddrinfo_proxy-, success
06-22 07:49:16.370  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
06-22 07:49:16.370  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:49:16.580  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:49:16.580  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:16.670  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:16.670  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:16.680  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
,06-22 07:49:16.680  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,06-22 07:49:16.790  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:16.790  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:16.890  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:16.900  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:16.910  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4
,06-22 07:49:16.910  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:49:17.030  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.030  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:17.130  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.130  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:17.130  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4
,06-22 07:49:17.140  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:49:17.200  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.210  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:17.300  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.300  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:17.310  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.310  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:49:17.410  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:49:17.410  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:17.520  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.520  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:17.530  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.530  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,06-22 07:49:17.640  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.650  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:17.760  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:49:17.770  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:17.770  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
06-22 07:49:17.770  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,06-22 07:49:17.860  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
06-22 07:49:17.860  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:17.940  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.950  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:49:17.960  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x3137322e323137),sn(),hints(known),family 0,flags 4,
,06-22 07:49:17.960  7697  7800 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,06-22 07:49:18.040  7697  7800 D libc    : [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4,
,06-22 07:49:18.040  7697  7800 D libc    : [NET] android_getaddrinfofornet-, err=8,
,06-22 07:49:20.140   905  1636 D PMS     : acquireWL(2c9a9b4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:49:20.150   905  1636 I BatteryService: n_update end
06-22 07:49:20.160   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:49:20.150  1123  1123 D PowerUI : closing low battery warning: level=100,
06-22 07:49:20.160   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:49:20.150   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:49:20.160   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
06-22 07:49:20.160   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:49:20.160  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:49:20.160  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 07:49:20.160   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:49:20.160  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:49:20.160   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 07:49:20.160  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:49:20.160   905   905 D PMS     : runPSCheck
06-22 07:49:20.160  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 07:49:20.160   905   905 D HtcPowerSaver: Checking...
06-22 07:49:20.160  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:49:20.160   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:49:20.170   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:49:20.170   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:49:20.170   905  1636 D PMS     : releaseWL(2c9a9b4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:49:20.210  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:49:42.680   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-22 07:49:52.680   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-22 07:50:07.690   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-22 07:50:20.290   905   920 D PMS     : acquireWL(3e60dabb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null
06-22 07:50:20.290   905   920 I BatteryService: n_update end
06-22 07:50:20.300  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
06-22 07:50:20.300  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 07:50:20.300  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:50:20.300  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:50:20.300   905   905 D NotificationService: plugged=true pluggin=true
,06-22 07:50:20.300  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:50:20.300   905  1077 D WifiController: battery changed pluggedType: 2
,06-22 07:50:20.300  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:50:20.310  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,06-22 07:50:20.300   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:50:20.310   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 07:50:20.300   905   905 D UsbnetService: onReceive BATTERY_CHANGED
,06-22 07:50:20.310   905   905 D PMS     : runPSCheck
06-22 07:50:20.300   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
06-22 07:50:20.310   905   905 D HtcPowerSaver: Checking...
,06-22 07:50:20.300   905   905 D UsbnetService: BroadcastReceiver::onReceive-,
06-22 07:50:20.310   905   905 I HtcPowerSaver: >> updateStatus
,06-22 07:50:20.310   905   920 D PMS     : releaseWL(3e60dabb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:50:20.320   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 07:50:20.320   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:50:20.350  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:50:27.700   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,06-22 07:50:52.700   477   477 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-22 07:51:20.450   905  1266 D PMS     : acquireWL(39844bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:51:20.460   905  1266 I BatteryService: n_update end
06-22 07:51:20.490  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:51:20.490  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:51:20.490  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:51:20.490  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:51:20.490  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:51:20.490   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:51:20.490   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:51:20.490   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:51:20.490   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:51:20.490   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
06-22 07:51:20.500   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:51:20.490   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:51:20.500   905   905 D PMS     : runPSCheck
06-22 07:51:20.490  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:51:20.500   905   905 D HtcPowerSaver: Checking...
,06-22 07:51:20.500  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:51:20.500   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:51:20.500   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:51:20.500   905   905 I HtcPowerSaver: << updateStatus
06-22 07:51:20.500   905  1266 D PMS     : releaseWL(39844bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:51:20.540  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:52:03.380   366   389 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,06-22 07:52:19.320  1457  1582 D ContactMessageStore: MSG_CHECK_DELETION >>,
,06-22 07:52:19.320  1457  1582 D ContactMessageStore: mDeleteTask = null, bDeleting = false,
,06-22 07:52:19.330  1457  1582 D AccFlag : sku_id=99,
,06-22 07:52:19.330  1457  1582 D ContactMessageStore: MSG_CHECK_DELETION <<,
,06-22 07:52:19.340  1457  7989 D ContactMessageStore: start background delete task...,
,06-22 07:52:19.370  1457  7989 D ContactMessageStore: size: 0 , 0,
,06-22 07:52:19.400  1457  7989 D ContactMessageStore: Background delete complete,
,06-22 07:52:20.600   905  1586 D PMS     : acquireWL(d804b31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:52:20.600   905  1586 I BatteryService: n_update end
06-22 07:52:20.610  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 07:52:20.610  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:52:20.610  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:52:20.610  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:52:20.610   905   905 D NotificationService: plugged=true pluggin=true,
06-22 07:52:20.610  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:52:20.620   905  1077 D WifiController: battery changed pluggedType: 2
,06-22 07:52:20.610   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:52:20.620  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
06-22 07:52:20.620   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:52:20.620   905  1011 D HtcPowerSaver: updateBatteryInfo,
06-22 07:52:20.620   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:52:20.620   905   905 D PMS     : runPSCheck,
06-22 07:52:20.620   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:52:20.620   905   905 D HtcPowerSaver: Checking...,
06-22 07:52:20.620  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:52:20.620   905   905 I HtcPowerSaver: >> updateStatus,
06-22 07:52:20.630   905  1586 D PMS     : releaseWL(d804b31): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:52:20.630   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
,06-22 07:52:20.630   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:52:20.660  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:53:20.770   905  2090 D PMS     : acquireWL(2f6f2216): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:53:20.780   905  2090 I BatteryService: n_update end,
06-22 07:53:20.780   905  2090 D PMS     : releaseWL(2f6f2216): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:54:20.920   905  1282 D PMS     : acquireWL(1b86797): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:54:20.930  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:54:20.930   905  1282 I BatteryService: n_update end
06-22 07:54:20.930  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:54:20.940  1123  1123 D PowerUI : closing low battery warning: level=100
,06-22 07:54:20.940  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:54:20.940   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:54:20.940  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 07:54:20.940   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:54:20.940  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:54:20.940  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:54:20.940   905   905 D UsbnetService: BroadcastReceiver::onReceive+,
06-22 07:54:20.940   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 07:54:20.940   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:54:20.940   905   905 D PMS     : runPSCheck
,06-22 07:54:20.940   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:54:20.940   905   905 D HtcPowerSaver: Checking...,
06-22 07:54:20.940   905   905 D UsbnetService: BroadcastReceiver::onReceive-
,06-22 07:54:20.950   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:54:20.950   905  1282 D PMS     : releaseWL(1b86797): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
06-22 07:54:20.950   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 07:54:20.950   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:54:20.990  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:56:21.240  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 07:56:21.240   905  1266 D PMS     : acquireWL(20de4d84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null
06-22 07:56:21.240  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 07:56:21.240   905  1266 I BatteryService: n_update end
06-22 07:56:21.240  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:56:21.240  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:56:21.240  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:56:21.240   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:56:21.240  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
06-22 07:56:21.250   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:56:21.240   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:56:21.250  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:56:21.240   905   905 D UsbnetService: onReceive BATTERY_CHANGED,
06-22 07:56:21.250   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:56:21.240   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:56:21.250   905   905 D PMS     : runPSCheck
,06-22 07:56:21.240   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:56:21.250   905   905 D HtcPowerSaver: Checking...
06-22 07:56:21.250   905   905 I HtcPowerSaver: >> updateStatus
,06-22 07:56:21.250   905  1266 D PMS     : releaseWL(20de4d84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:56:21.260   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 07:56:21.260   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:56:21.290  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:57:21.400   905  1586 D PMS     : acquireWL(325d696d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:57:21.410   905  1586 I BatteryService: n_update end
,06-22 07:57:21.430   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 07:57:21.430  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:57:21.430   905   905 D NotificationService: plugged=true pluggin=true
,06-22 07:57:21.430  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 07:57:21.440  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
06-22 07:57:21.440  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 07:57:21.440  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:57:21.440  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 07:57:21.440   905  1077 D WifiController: battery changed pluggedType: 2,
06-22 07:57:21.440  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,06-22 07:57:21.440   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 07:57:21.440   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:57:21.450   905   905 D PMS     : runPSCheck,
,06-22 07:57:21.440   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 07:57:21.450   905   905 D HtcPowerSaver: Checking...
06-22 07:57:21.440   905   905 D UsbnetService: BroadcastReceiver::onReceive-
,06-22 07:57:21.450   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:57:21.450   905  1586 D PMS     : releaseWL(325d696d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:57:21.460   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:57:21.460   905   905 I HtcPowerSaver: << updateStatus
,06-22 07:57:21.490  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 07:58:21.610   905   920 D PMS     : acquireWL(1f3349a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
,06-22 07:58:21.620   905   920 I BatteryService: n_update end,
06-22 07:58:21.640  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,06-22 07:58:21.640  1123  1123 D PowerUI : closing low battery warning: level=100,
,06-22 07:58:21.650  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 07:58:21.650  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 07:58:21.650   905   905 D NotificationService: plugged=true pluggin=true
06-22 07:58:21.650   905   905 D UsbnetService: BroadcastReceiver::onReceive+
,06-22 07:58:21.650   905  1077 D WifiController: battery changed pluggedType: 2
06-22 07:58:21.650   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 07:58:21.650  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 07:58:21.650   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,06-22 07:58:21.680   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 07:58:21.650   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 07:58:21.680   905   905 D PMS     : runPSCheck
06-22 07:58:21.650  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 07:58:21.680   905   905 D HtcPowerSaver: Checking...
06-22 07:58:21.660  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 07:58:21.680   905   905 I HtcPowerSaver: >> updateStatus
06-22 07:58:21.680   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 07:58:21.700  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true
,06-22 07:58:21.680   905   905 I HtcPowerSaver: << updateStatus
06-22 07:58:21.680   905   920 D PMS     : releaseWL(1f3349a2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 07:58:21.700   905  1000 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=7996 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,06-22 07:58:21.770  7996  7996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,06-22 07:58:21.780  7506  7506 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,06-22 07:58:21.780  7506  7506 D         : Cust_ConnectToPC   : Internet_Sharing>true
06-22 07:58:21.780  7506  7506 D         : Cust_ConnectToPC   : Modem_Link>false
06-22 07:58:21.780  7506  7506 D         : Cust_ConnectToPC   : spcsc>false
06-22 07:58:21.780  7506  7506 D         : Cust_ConnectToPC   : IPT>true
06-22 07:58:21.780  7506  7506 D         : Cust_ConnectToPC   : Singel_USB>false
,06-22 07:58:21.790  7506  7506 D SmartNS_NSReceiver: project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
06-22 07:58:21.790  7506  7506 D SmartNS_NSReceiver: Index of the first 1 = 3,
,06-22 07:58:21.810  7506  7506 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,06-22 07:58:21.810  7506  7506 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,06-22 07:58:21.810  7506  7506 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-22 07:58:21.810  7506  7506 E SmartNS_Utility: hasRemovableStorageSlot: true
,06-22 07:58:21.810  7506  7506 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
06-22 07:58:21.810  7506  7506 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,06-22 07:58:21.820  7506  7506 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false,
06-22 07:58:21.820  7506  7506 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
06-22 07:58:21.820   905  1282 I ActivityManager: Killing 7429:com.google.android.setupwizard/u0a80 (adj 15): empty #17
06-22 07:58:21.820   905  1282 D Process : killProcessQuiet, pid=7429
06-22 07:58:21.820   905  1282 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,06-22 07:58:21.830   905   920 I ActivityManager: Recipient 7429,
,06-22 07:58:21.850   905   920 D Process : killProcessQuiet, pid=7429,
06-22 07:58:21.850   905   920 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 07:58:21.850   905   920 W libprocessgroup: failed to open /acct/uid_10080/pid_7429/cgroup.procs: No such file or directory
,06-22 07:58:35.770   905  1065 D PMS     : acquireWL(16b4bdf0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
,06-22 07:58:35.780   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=423924, Int=0
06-22 07:58:35.790   905  1065 V AlarmManager: sending alarm PendingIntent{14742f69: PendingIntentRecord{30205dee com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1466575115781, Int=0
,06-22 07:58:35.840  7996  7996 D SmartSyncUtils: isEpsOn(), nState = 0,
,06-22 07:58:35.840  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:58:35.850   905  1586 D PMS     : acquireWL(2e7ab28f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7996 1000 null,
,06-22 07:58:35.860   905   905 D PMS     : releaseWL(16b4bdf0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,06-22 07:58:35.930   905  1636 D PMS     : releaseWL(2e7ab28f): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,06-22 07:58:35.940   905  1586 D PMS     : acquireWL(163fc91c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7996 1000 null
,06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
,06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1466658000000, randomSettingOnTime = 1466654828000,
06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1466636400000, randomSettingOffTime = 1466641476000
06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
06-22 07:58:35.940  7996  8060 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,06-22 07:58:35.940   905  1636 D PMS     : releaseWL(163fc91c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,06-22 07:58:35.960  1123  2217 D WeatherUtility: Weather sync is On
,06-22 07:58:35.970   905  1637 D PMS     : acquireWL(eb86afa): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null,
,06-22 07:58:44.780  7529  7529 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
06-22 07:58:44.800   905  1065 D PMS     : acquireWL(340e5b08): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 07:58:44.800   905  1065 V AlarmManager: sending alarm PendingIntent{3a0962a1: PendingIntentRecord{36a3d0c9 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466574821239, Int=0
06-22 07:58:44.810   905  1266 D PMS     : acquireWL(3b923cc6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:58:44.820   905  1708 D PMS     : releaseWL(3b923cc6): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:58:44.820   905  1065 V AlarmManager: sending alarm PendingIntent{32ec6487: PendingIntentRecord{3cb21fb4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1008697, Int=0
06-22 07:58:44.820   905  1065 V AlarmManager: sending alarm PendingIntent{caaadc7: PendingIntentRecord{1488cff4 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=801147, Int=0
,06-22 07:58:44.860   905  1065 I ActivityManager: Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=8077 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a,
06-22 07:58:44.880  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:58:44.860   905  1065 V AlarmManager: sending alarm PendingIntent{17e55f52: PendingIntentRecord{1b20c223 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
06-22 07:58:44.910  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
06-22 07:58:44.860   905  1065 V AlarmManager: sending alarm PendingIntent{122b8320: PendingIntentRecord{31a035d7 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1466575060053, Int=0
06-22 07:58:44.930  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:58:44.870   905   921 D PMS     : acquireWL(3415b14c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:58:44.930  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:58:44.880   905  1585 D PMS     : acquireWL(3609d595): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 07:58:44.930  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:58:44.920  7996  7996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
06-22 07:58:44.930  6533  6533 I GCM     : Message from null null
06-22 07:58:44.920   905   905 D PMS     : releaseWL(340e5b08): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
06-22 07:58:44.930  6533  6533 E GCM     : Dropping message from null
06-22 07:58:44.930   905  1637 D PMS     : releaseWL(3609d595): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10025 com.google.android.gms}
,06-22 07:58:44.940  1687  6902 D GCM     : Message class com.google.f.a.a.i
06-22 07:58:44.940   905  1708 D PMS     : releaseWL(3415b14c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms}
06-22 07:58:44.940  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:58:44.950  7529  7529 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-22 07:58:44.950  7996  8102 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,06-22 07:58:44.960  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:58:44.970  7996  8102 D PowerUsageService: repeat time = 1466576024976
,06-22 07:58:44.970   905  1637 W BatSI   : Couldn't get kernel wake lock stats
,06-22 07:58:44.980  1687  1703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
06-22 07:58:44.980  1687  1703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:58:44.980  1687  1703 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:58:44.980  1687  1703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:58:44.980  1687  1703 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:58:45.010  1687  1703 I art     : Explicit concurrent mark sweep GC freed 29674(1784KB) AllocSpace objects, 3(243KB) LOS objects, 46% free, 4MB/8MB, paused 646us total 24.313ms
,06-22 07:58:45.020   905  2090 I art     : Explicit concurrent mark sweep GC freed 29273(1570KB) AllocSpace objects, 3(341KB) LOS objects, 33% free, 17MB/25MB, paused 1.210ms total 66.546ms
,06-22 07:58:45.030  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:58:45.040  1687  1706 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
06-22 07:58:45.040  1687  1706 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:58:45.040  1687  1706 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:58:45.040  1687  1706 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:58:45.050  1687  1706 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:58:45.050  7529  7529 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-22 07:58:45.050  8077  8077 I ImageRamCache: create image Cache, size: 31457280.
,06-22 07:58:45.050  8077  8077 I ImageRamCache: [resize] ImageRamCache resized to: 30Mb.
06-22 07:58:45.050  8077  8077 I ImageRamCache: create image Cache, size: 31457280.
,06-22 07:58:45.060  8077  8077 I FeedSettings: [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
,06-22 07:58:45.060  8077  8077 I FeedSettings: GroupBudget 0.500000 0.380000
06-22 07:58:45.060  8077  8077 I FeedSettings: GroupBudget 60 45 15
,06-22 07:58:45.060  8077  8077 I Prism.ExternalStringMa_: changeLocale(): en_GB
,06-22 07:58:45.070  7996  8102 D PowerUsageList:PowerUsageHelper: [CMD_CURRENT_TIME] rec.currentTime < startCurTime, impossible
,06-22 07:58:45.070  8077  8077 I Prism.AllAppsOptionsMa_: loadSortType() with Custom
06-22 07:58:45.070  8077  8077 I Prism.AllAppsOptionsMa_: loadGridSize() with Alternative
,06-22 07:58:45.070   905  1639 W BatSI   : Couldn't get kernel wake lock stats
,06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfofornet-, err=8
,06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfo_proxy+
06-22 07:58:45.100  8077  8118 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-22 07:58:45.110   455  8120 D libc    : [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
06-22 07:58:45.110   455  8120 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,06-22 07:58:45.130  7996  8102 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,06-22 07:58:45.140  7996  8102 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,06-22 07:58:45.140  7996  8102 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,06-22 07:58:45.150  7996  8102 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,06-22 07:58:45.160   455  8120 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,06-22 07:58:45.160   455  8120 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-22 07:58:45.160  8077  8118 D libc    : [NET] android_getaddrinfo_proxy-, success
,06-22 07:58:45.240  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:58:45.250  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
06-22 07:58:45.250  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:58:45.250  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:58:45.250  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:58:45.250  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:58:45.260  7529  7529 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
06-22 07:58:45.260  7529  7529 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,06-22 07:58:45.260  7529  7529 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-22 07:58:45.260  7529  7529 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,06-22 07:58:45.270  1709  2019 D DeviceConnectionService: client connected with version: 7571000,
,06-22 07:58:46.050   905  1495 D PMS     : releaseWL(eb86afa): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:58:47.000   905  1495 D Process : killProcessQuiet, pid=7091,
06-22 07:58:47.000   905  1495 I ActivityManager: Killing 7091:com.htc.widget.hmsproc1/u0a37 (adj 15): empty #17
06-22 07:58:47.000   905  1495 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-22 07:58:47.020   905  1282 I ActivityManager: Recipient 7091,
,06-22 07:58:47.030   905  1282 D Process : killProcessQuiet, pid=7091,
06-22 07:58:47.030   905  1282 W libprocessgroup: failed to open /acct/uid_10037/pid_7091/cgroup.procs: No such file or directory
06-22 07:58:47.030   905  1282 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-22 07:58:50.030  8077  8103 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,06-22 07:59:00.050   905  1065 D PMS     : acquireWL(1ce8a074): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
06-22 07:59:00.060   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1023924, Int=0
06-22 07:59:00.090   905  1065 V AlarmManager: sending alarm PendingIntent{1133ae12: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575140062, Int=0
06-22 07:59:00.120   905   905 D PMS     : releaseWL(1ce8a074): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,06-22 07:59:00.140  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 07:59:00.240  1123  2217 D WeatherUtility: Weather sync is On
,06-22 07:59:00.250   905  1584 D PMS     : acquireWL(32d7299): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null,
,06-22 07:59:00.340  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:59:00.360  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 07:59:00.360  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,06-22 07:59:00.360  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:59:00.360  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:59:00.360  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:59:00.370  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:59:00.370  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 07:59:00.370  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,06-22 07:59:10.300   905  1282 D PMS     : releaseWL(32d7299): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 07:59:20.390   905  1065 D PMS     : acquireWL(3fa07110): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 07:59:20.390   905  1065 V AlarmManager: sending alarm PendingIntent{3c233409: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575160375, Int=0
,06-22 07:59:20.390   905   905 D PMS     : releaseWL(3fa07110): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,06-22 07:59:20.690  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:59:20.700  1687  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
06-22 07:59:20.700  1687  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:59:20.700  1687  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:59:20.700  1687  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:59:20.710  1687  2093 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:59:20.710  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 07:59:20.710  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 07:59:20.710  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,06-22 07:59:21.780   905  1281 D PMS     : acquireWL(3516f5c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 07:59:21.780   905  1281 I BatteryService: n_update end,
06-22 07:59:21.780   905  1281 D PMS     : releaseWL(3516f5c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 07:59:40.740   905  1065 D PMS     : acquireWL(35843179): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 07:59:40.740   905  1065 V AlarmManager: sending alarm PendingIntent{cf21ebe: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575180723, Int=0
06-22 07:59:40.740   905   905 D PMS     : releaseWL(35843179): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075},
,06-22 07:59:41.000  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 07:59:41.010  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
06-22 07:59:41.010  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 07:59:41.010  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:59:41.010  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:59:41.020  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:59:41.020  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 07:59:41.020  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 07:59:41.030  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,06-22 08:00:01.030   905  1065 D PMS     : acquireWL(3db9b770): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 905 1000 WorkSource{1000},
06-22 08:00:01.030   905  1065 V AlarmManager: sending alarm PendingIntent{f514aff: PendingIntentRecord{ab0d0cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1083924, Int=0
06-22 08:00:01.060   905  1065 V AlarmManager: sending alarm PendingIntent{1241b36e: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575201034, Int=0
,06-22 08:00:01.090   905   905 D PMS     : releaseWL(3db9b770): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,06-22 08:00:01.110  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 08:00:01.220  1123  2217 D WeatherUtility: Weather sync is On,
,06-22 08:00:01.230   905  1088 D PMS     : acquireWL(3e5ada9c): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1380 10054 null
,06-22 08:00:01.350  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 08:00:01.370  1687  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 08:00:01.370  1687  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 08:00:01.370  1687  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-22 08:00:01.370  1687  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 08:00:01.370  1687  2093 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:00:01.380  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 08:00:01.380  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 08:00:01.380  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,06-22 08:00:11.260   905   921 D PMS     : releaseWL(3e5ada9c): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,06-22 08:00:21.390   905  1065 D PMS     : acquireWL(321aa4ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 08:00:21.390   905  1065 V AlarmManager: sending alarm PendingIntent{fd822cc: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575221389, Int=0
06-22 08:00:21.390   905   905 D PMS     : releaseWL(321aa4ff): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,06-22 08:00:21.650  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 08:00:21.670  1687  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
06-22 08:00:21.670  1687  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-22 08:00:21.670  1687  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 08:00:21.670  1687  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 08:00:21.670  1687  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 08:00:21.680  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 08:00:21.680  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 08:00:21.680  7529  7529 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,06-22 08:00:41.710   905  1065 D PMS     : acquireWL(a2ccbef): PARTIAL_WAKE_LOCK  *alarm* 0x1 905 1000 WorkSource{10075},
06-22 08:00:41.710   905  1065 V AlarmManager: sending alarm PendingIntent{250fd6fc: PendingIntentRecord{5f6c9e3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1466575241692, Int=0
06-22 08:00:41.710   905   905 D PMS     : releaseWL(a2ccbef): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075},
,06-22 08:00:42.020  1687  1687 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,06-22 08:00:42.040  1687  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-22 08:00:42.040  1687  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
06-22 08:00:42.040  1687  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 08:00:42.040  1687  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 08:00:42.040  1687  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:00:42.050  7529  7529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
06-22 08:00:42.050  7529  7529 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-22 08:00:42.050  7529  7529 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,06-22 08:01:22.090   905  1636 D PMS     : acquireWL(8c3b97e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
,06-22 08:01:22.090   905  1636 I BatteryService: n_update end
06-22 08:01:22.100   905  1636 D PMS     : releaseWL(8c3b97e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:02:03.380   366   389 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,06-22 08:02:15.690   905   999 I UsageStatsService: User[0] Flushing usage stats to disk,
,06-22 08:02:22.260   905  1637 D PMS     : acquireWL(134e8edf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:02:22.280   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 08:02:22.260   905  1637 I BatteryService: n_update end
06-22 08:02:22.280   905   905 D UsbnetService: onReceive BATTERY_CHANGED
06-22 08:02:22.280   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
06-22 08:02:22.280   905   905 D NotificationService: plugged=true pluggin=true
06-22 08:02:22.280   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 08:02:22.280   905  1077 D WifiController: battery changed pluggedType: 2
06-22 08:02:22.280  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 08:02:22.290  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 08:02:22.290  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 08:02:22.290  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 08:02:22.290  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 08:02:22.290   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 08:02:22.290  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:02:22.290   905   905 D PMS     : runPSCheck
06-22 08:02:22.290  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
06-22 08:02:22.290   905   905 D HtcPowerSaver: Checking...
06-22 08:02:22.290   905   905 I HtcPowerSaver: >> updateStatus
06-22 08:02:22.300   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 08:02:22.300   905   905 I HtcPowerSaver: << updateStatus,
06-22 08:02:22.300   905  1637 D PMS     : releaseWL(134e8edf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:02:22.310   905  2090 D PMS     : acquireWL(774f72c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:02:22.310   905  2090 I BatteryService: n_update end
,06-22 08:02:22.310   905  2090 D PMS     : releaseWL(774f72c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:02:22.340  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 08:03:22.410   905  1528 D PMS     : acquireWL(2824d5f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:03:22.420   905  1528 I BatteryService: n_update end
06-22 08:03:22.420   905  1528 D PMS     : releaseWL(2824d5f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:04:22.600   905  1584 D PMS     : acquireWL(15def8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:04:22.610   905  1584 I BatteryService: n_update end
06-22 08:04:22.640   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 08:04:22.640   905   905 D UsbnetService: onReceive BATTERY_CHANGED
,06-22 08:04:22.640   905   905 D NotificationService: plugged=true pluggin=true
06-22 08:04:22.640   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 08:04:22.650   905  1077 D WifiController: battery changed pluggedType: 2
,06-22 08:04:22.640   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 08:04:22.650  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 08:04:22.650  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 08:04:22.650  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,06-22 08:04:22.650  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 08:04:22.650   905  1011 D HtcPowerSaver: updateBatteryInfo
06-22 08:04:22.650  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:04:22.660   905   905 D PMS     : runPSCheck,
06-22 08:04:22.650  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,06-22 08:04:22.660   905   905 D HtcPowerSaver: Checking...,
,06-22 08:04:22.650  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 08:04:22.660   905   905 I HtcPowerSaver: >> updateStatus
06-22 08:04:22.680   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
06-22 08:04:22.680   905   905 I HtcPowerSaver: << updateStatus,
06-22 08:04:22.680   905  1584 D PMS     : releaseWL(15def8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,06-22 08:04:22.700  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 08:05:22.740   905  1266 D PMS     : acquireWL(2b739fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:05:22.740   905  1266 I BatteryService: n_update end
06-22 08:05:22.770  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 08:05:22.770  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
06-22 08:05:22.770  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 08:05:22.770  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 08:05:22.770   905   905 D NotificationService: plugged=true pluggin=true,
06-22 08:05:22.770   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 08:05:22.780   905  1077 D WifiController: battery changed pluggedType: 2
06-22 08:05:22.770   905   905 D UsbnetService: onReceive BATTERY_CHANGED,
06-22 08:05:22.780  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
06-22 08:05:22.780   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 08:05:22.790   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 08:05:22.780   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 08:05:22.790   905   905 D PMS     : runPSCheck
06-22 08:05:22.780  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
06-22 08:05:22.790   905   905 D HtcPowerSaver: Checking...
06-22 08:05:22.790  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-22 08:05:22.790   905   905 I HtcPowerSaver: >> updateStatus
06-22 08:05:22.790   905  1266 D PMS     : releaseWL(2b739fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 08:05:22.790   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 08:05:22.790   905   905 I HtcPowerSaver: << updateStatus
,06-22 08:05:22.830  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,06-22 08:06:22.930   905  2090 D PMS     : acquireWL(ed05a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 905 1000 null,
06-22 08:06:22.930   905  2090 I BatteryService: n_update end
06-22 08:06:22.950  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
06-22 08:06:22.960  1199  1199 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,06-22 08:06:22.960  1123  1123 D PowerUI : closing low battery warning: level=100
06-22 08:06:22.960  1199  1199 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
06-22 08:06:22.960  1123  1123 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
06-22 08:06:22.960   905   905 D UsbnetService: BroadcastReceiver::onReceive+
06-22 08:06:22.960   905   905 D NotificationService: plugged=true pluggin=true
06-22 08:06:22.960   905   905 D UsbnetService: onReceive BATTERY_CHANGED
,06-22 08:06:22.960   905  1077 D WifiController: battery changed pluggedType: 2
06-22 08:06:22.960   905   905 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
06-22 08:06:22.960   905  1011 D HtcPowerSaver: updateBatteryInfo
,06-22 08:06:22.960   905   905 D UsbnetService: BroadcastReceiver::onReceive-
06-22 08:06:22.960   905   905 D PMS     : runPSCheck
06-22 08:06:22.960  1123  1302 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,06-22 08:06:22.960   905   905 D HtcPowerSaver: Checking...
,06-22 08:06:22.960  6018  6055 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-22 08:06:22.960   905   905 I HtcPowerSaver: >> updateStatus
06-22 08:06:22.970   905   905 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,06-22 08:06:22.970   905  2090 D PMS     : releaseWL(ed05a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
06-22 08:06:22.970   905   905 I HtcPowerSaver: << updateStatus
,06-22 08:06:23.010  1123  1123 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms),06-22 08:06:53.860  8227  8227 D CustomizationManager: ====startRecUseTime====
06-22 08:06:53.860  8227  8227 D htc.customization.log.level:  is 
06-22 08:06:53.860  8227  8227 W CustomizationLogLevel: Level value is invalid, use default level 2
06-22 08:06:53.940  8227  8227 D CustomizationManager:  Read ACC file spent 0.044 (s)
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__001
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__E11
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__102
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__203
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__405
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__304
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__032
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__016
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__A48
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-22 08:06:53.940  8227  8227 D CIDMapFileReader: Parsing tag item name = HTC__002
06-22 08:06:53.940  8227  8227 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = system
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = application
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = Settings
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-22 08:06:53.940  8227  8227 I CustomizationCIDLoader: Parsing tag category name = ACC
06-22 08:06:53.940  8227  8227 D CustomizationManager:  Read CID file spent 0.083 (s)
06-22 08:06:53.940  8227  8227 D CustomizationManager:  All configurations done spent 0.083 (s)
06-22 08:06:53.960  8227  8227 E ActTriggerJNI: open library fail.
06-22 08:06:53.970   905  1281 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=8227, uid=2000 userid=0
06-22 08:06:53.970   905  1000 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
06-22 08:06:53.970   905  1000 I ActivityManager: Killing 5914:com.test.thalitest/u0a192 (adj 0): stop com.test.thalitest
06-22 08:06:53.970   905  1000 D Process : killProcessQuiet, pid=5914
06-22 08:06:53.970   905  1000 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
06-22 08:06:54.030   905  1052 W PackageSettings: Skipping PackageSetting{2be7f569 com.example.hello/10380} due to missing metadata
06-22 08:06:54.030   905  1584 I ActivityManager: Recipient 5914
06-22 08:06:54.030   905  1495 I WindowState: WIN DEATH: Window{73e1a1c u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-22 08:06:54.030   905  1077 D WifiService: Client connection lost with reason: 4
06-22 08:06:54.100   905  1000 I ActivityManager:   Force finishing activity ActivityRecord{1e5c1b42 u0 com.test.thalitest/.MainActivity t33}
06-22 08:06:54.110   905  1584 W ActivityManager: Spurious death for ProcessRecord{10b9dc71 5914:com.test.thalitest/u0a192}, curProc for 5914: null
06-22 08:06:54.110   905  1052 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
06-22 08:06:54.110   905  1052 I ActivityManager:   Force finishing activity ActivityRecord{1e5c1b42 u0 com.test.thalitest/.MainActivity t33 f}
06-22 08:06:54.110   905  1052 W ActivityManager: Duplicate finish request for ActivityRecord{1e5c1b42 u0 com.test.thalitest/.MainActivity t33 f}
06-22 08:06:54.170  1493  1493 I art     : Explicit concurrent mark sweep GC freed 50337(3MB) AllocSpace objects, 9(1049KB) LOS objects, 40% free, 19MB/31MB, paused 1.253ms total 42.277ms
06-22 08:06:54.180   905   905 I art     : Explicit concurrent mark sweep GC freed 35092(1885KB) AllocSpace objects, 7(361KB) LOS objects, 33% free, 17MB/25MB, paused 1.253ms total 65.309ms
06-22 08:06:54.180   905  1639 D PMS     : acquireWL(30b37a56): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1709 10025 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.180  1199  1199 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-22 08:06:54.190   905  1495 D PMS     : releaseWL(30b37a56): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.180  1199  1199 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
06-22 08:06:54.180  1199  1199 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
06-22 08:06:54.180  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-22 08:06:54.180  1493  1859 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-22 08:06:54.190  1493  1493 I Launcher: Deferring update until onResume
06-22 08:06:54.190  1493  1493 D Launcher: waitUntilResume // bindAppsRemoved
06-22 08:06:54.200  1587  2027 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
06-22 08:06:54.210  8077  8257 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-22 08:06:54.210  8077  8257 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-22 08:06:54.210   905  1073 D PMS     : acquireWL(8a6a8a9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
06-22 08:06:54.220  1563  8259 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-22 08:06:54.220   905  1074 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
06-22 08:06:54.230  1587  2027 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
06-22 08:06:54.240  1587  2027 E ExternalAccountType: Unsupported attribute readOnly
06-22 08:06:54.240  1457  1457 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
06-22 08:06:54.250   905   905 W PackageManager: Unable to load service info ResolveInfo{2fce8bf com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-22 08:06:54.250   905   905 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-22 08:06:54.250   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 08:06:54.250   905   905 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-22 08:06:54.250   905   905 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-22 08:06:54.250   905   905 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-22 08:06:54.250   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 08:06:54.250   905   905 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 08:06:54.250   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-22 08:06:54.250   905   905 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
06-22 08:06:54.260  1493  1493 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
06-22 08:06:54.260  1380  8261 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
06-22 08:06:54.270  1380  8261 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
06-22 08:06:54.270   905  1073 D PMS     : releaseWL(8a6a8a9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-22 08:06:54.270   905  1074 V NetworkPolicy: writePolicyLocked()
06-22 08:06:54.280   905  1074 V NetworkPolicy: updateNetworkEnabledLocked()
06-22 08:06:54.280   905  1074 V NetworkPolicy: updateNotificationsLocked()
06-22 08:06:54.280   905  1585 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
06-22 08:06:54.310   905   905 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-22 08:06:54.350   905  1103 D TaskPersister: removeObsoleteFile: deleting file=33_task.xml
06-22 08:06:54.370  8262  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
06-22 08:06:54.370   905  1004 D StatusBarManagerService: setSystemUiVisibility(0x8700)
06-22 08:06:54.370   905  1004 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 08:06:54.370   905  1004 D StatusBarManagerService: hiding MENU key
06-22 08:06:54.370   905  1004 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
06-22 08:06:54.370   905  1004 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 08:06:54.370   905  1004 D StatusBarManagerService: hiding MENU key
06-22 08:06:54.370   905   999 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
06-22 08:06:54.380   905  1637 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5914 uid 10192
06-22 08:06:54.380   905  1637 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
06-22 08:06:54.400  1687  1687 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-22 08:06:54.400   905  2090 I ActivityManager: Killing 6865:com.google.android.gms.unstable/u0a25 (adj 15): empty #17
06-22 08:06:54.400  1687  1687 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-22 08:06:54.400   905  1495 D PMS     : acquireWL(264da938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1687 10025 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.400   905  2090 D Process : killProcessQuiet, pid=6865
06-22 08:06:54.400   905  2090 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-22 08:06:54.410   905   999 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-22 08:06:54.410   905  1052 I art     : Explicit concurrent mark sweep GC freed 16955(1216KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 17MB/25MB, paused 3.052ms total 189.394ms
06-22 08:06:54.420   905  1586 I ActivityManager: Recipient 6865
06-22 08:06:54.470  8227  8227 E cutils-trace: Error opening trace file: No such file or directory (2)
06-22 08:06:54.470   905  1586 D Process : killProcessQuiet, pid=6865
06-22 08:06:54.470   905  1586 W libprocessgroup: failed to open /acct/uid_10025/pid_6865/cgroup.procs: No such file or directory
06-22 08:06:54.470   905  1586 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 08:06:54.480   905  1282 D PMS     : releaseWL(264da938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.530   905  1052 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8289 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=armeabi-v7a
06-22 08:06:54.530  6533  8306 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-22 08:06:54.530  6533  6533 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-22 08:06:54.530  6533  6533 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
06-22 08:06:54.540  6533  8306 D AccountUtils: Clearing selected account for com.test.thalitest
06-22 08:06:54.550  6533  8306 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
06-22 08:06:54.570   905  1088 D PMS     : acquireWL(3395e144): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 6533 10025 null
06-22 08:06:54.600   905  1585 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
06-22 08:06:54.600  1687  1687 I ConfigService: onCreate
06-22 08:06:54.610  6533  6533 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-22 08:06:54.610  7398  8314 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
06-22 08:06:54.620  6533  8312 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
06-22 08:06:54.620  6533  8312 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
06-22 08:06:54.630  6533  8312 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
06-22 08:06:54.630   905  1637 I ActivityManager: Resuming delayed broadcast
06-22 08:06:54.650   905  1266 D PMS     : releaseWL(3395e144): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
06-22 08:06:54.660   905  1586 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8317 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
06-22 08:06:54.670  6533  8313 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.670  6533  8313 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
06-22 08:06:54.670  6533  8313 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
06-22 08:06:54.680   905  1586 D PMS     : acquireWL(1e46776b): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.680  6533  7389 I Icing   : doRemovePackageData com.test.thalitest
06-22 08:06:54.680   905   920 D PMS     : releaseWL(1e46776b): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.680  6533  6533 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-22 08:06:54.680  6533  6533 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-22 08:06:54.690  6533  8332 I PeopleContactsSync: CP2 sync disabled
06-22 08:06:54.690  6533  8313 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.690   905  1528 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=6533, uid=10025, userID:0
06-22 08:06:54.700  6533  6533 I ConfigFetchService: service connected
06-22 08:06:54.710   905  1639 D PMS     : acquireWL(3832a09d): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.720   905  1282 D PMS     : releaseWL(3832a09d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.740   905  1708 D PMS     : acquireWL(ddeb03f): PARTIAL_WAKE_LOCK  Icing 0x1 6533 10025 WorkSource{10025 com.google.android.gms}
06-22 08:06:54.740  7398  8314 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
06-22 08:06:54.800  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.800  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.810  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.850  1687  1706 I art     : Explicit concurrent mark sweep GC freed 20456(1178KB) AllocSpace objects, 2(32KB) LOS objects, 46% free, 4MB/8MB, paused 547us total 22.790ms
06-22 08:06:54.850  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.860  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.860  6533  8340 W BaseAppContext: Using Auth Proxy for data requests.
06-22 08:06:54.990  8317  8317 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
06-22 08:06:54.990  8317  8317 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-22 08:06:54.990  8317  8317 I GAv4    :   adb logcat -s GAv4
06-22 08:06:55.000  8317  8317 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-22 08:06:55.020  8317  8317 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
06-22 08:06:55.020  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.020  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.020  8317  8353 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
06-22 08:06:55.020  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.030  8317  8317 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.g(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.a(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.e(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdy.b(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at feb.run(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
06-22 08:06:55.030  8317  8353 E GAv4    : Opening the database failed, dropping the table and recreating it
06-22 08:06:55.030  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.g(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.a(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdw.e(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at fdy.b(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at feb.run(Unknown Source)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-22 08:06:55.030  8317  8353 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
06-22 08:06:55.040  8317  8353 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.040  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.040  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.040  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.040  8317  8353 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.040  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at ael.a(PG:1521)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at hix$a.a(PG:125)
06-22 08:06:55.060  8317  8354 E SQLiteDatabase: 	at aen.run(PG:536)
06-22 08:06:55.090  6533  6533 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
06-22 08:06:55.110  6533  6547 W art     : Suspending all threads took: 5.423ms
06-22 08:06:55.130   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
06-22 08:06:55.130   363   408 W Vold    : Returning OperationFailed - no handler for errno 0
06-22 08:06:55.130  8317  8360 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
06-22 08:06:55.130   905  1586 D PMS     : acquireWL(26e550d3): PARTIAL_WAKE_LOCK  AsyncService 0x1 7608 10176 null
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at ael.a(PG:1521)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at hix$a.a(PG:125)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at aej.c(PG:139)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at aej.b(PG:398)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at agf.f(PG:417)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at oe.run(PG:1112)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 08:06:55.140  8317  8360 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-22 08:06:55.140   905  1281 D PMS     : acquireWL(60f2b09): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7608 10176 null
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at aej.c(PG:139)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at aej.b(PG:398)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at agf.f(PG:417)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-22 08:06:55.140  8317  8360 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
06-22 08:06:55.140  7922  7922 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
06-22 08:06:55.140  7922  7922 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
06-22 08:06:55.140   905  1585 D PMS     : releaseWL(26e550d3): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
06-22 08:06:55.150  7922  7922 I DeviceManagement: WorkflowService: Starting workflow service
06-22 08:06:55.150   905  1495 D PMS     : releaseWL(60f2b09): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
06-22 08:06:55.150  7922  8365 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@237fa2b] args=[Bundle[mParcelledData.dataSize=112]]
06-22 08:06:55.150  7922  8365 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-22 08:06:55.150  7922  8365 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-22 08:06:55.150  7922  8365 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-22 08:06:55.150  7922  8365 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
06-22 08:06:55.150  7922  8365 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
06-22 08:06:55.150  8317  8361 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-22 08:06:55.150  8317  8361 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 08:06:55.160  7922  8365 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-22 08:06:55.160  7922  8365 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0xb8f45850
06-22 08:06:55.160  7922  8365 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@237fa2b]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
06-22 08:06:55.160  7922  8365 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 08:06:55.170   905  2090 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=8367 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
06-22 08:06:55.170  7922  7922 I DeviceManagement: WorkflowService: Stopping workflow service
06-22 08:06:55.170   905  2090 I ActivityManager: Killing 7246:com.google.android.music:main/u0a167 (adj 15): empty #17
06-22 08:06:55.170   905  2090 D Process : killProcessQuiet, pid=7246
06-22 08:06:55.170   905  2090 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-22 08:06:55.180   905  1586 I ActivityManager: Recipient 7246
06-22 08:06:55.180   905  1636 D MediaRouterService: Client com.google.android.music (pid 7246): Died!
06-22 08:06:55.220  8317  8361 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
06-22 08:06:55.250  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.250  8317  8353 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.250  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.250  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.250   905  1586 D Process : killProcessQuiet, pid=7246
06-22 08:06:55.250   905  1586 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-22 08:06:55.250   905  1586 W libprocessgroup: failed to open /acct/uid_10167/pid_7246/cgroup.procs: No such file or directory
06-22 08:06:55.250  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.250  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.250  6533  8340 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-22 08:06:55.250  6533  8340 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-22 08:06:55.250  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8353 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8353 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8353 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8352 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-22 08:06:55.260  8317  8354 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
06-22 08:06:55.260  8317  8354 E CAKEMIX_CRASHED: 	at aen.run(PG:536)

```
